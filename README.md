# The-Place-You-Love
Site map generator for websites that serve static content or auto generated indexes from Nginx
<br><br>
**But what's up with the weird name?**
<br>
*It's one of my favourite songs, [The place you love by Have mercy](https://www.youtube.com/watch?v=egkQvExJ1m8) :)*
## Table of contents
- [How does it work?](#how-does-it-work)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributions](#contributions)

## How does it work
The script crawls through all the files and directories present in the mentioned folder and generates HTML code for them.

## Installation
`$ wget https://raw.githubusercontent.com/realaravinth/The-Place-You-Love/master/the-place-you-love.sh && chmod +x the-place-you-love.sh`

## Usage
`the-place-you-love.sh <my.example.com> <dir>`
<br>
NOTE: don't add '/' in both the url and the directory

## Example 
`the-place-you-love.sh google.com Documents`

## Contributions
Yes please!
