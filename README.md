# URLChecker

Node.js command-line tool to bulk check URL status codes

## Installation

On your command line or git terminal 
```git clone https://github.com/danishalim/URLChecker```

Open the directory and paste the following in the command line
```npm install``` OR ```npm i```

Type in the following to create a symlink
```npm link```

## Usage:

Find and check URLs inside file:

```urlcheck -f filename```

Find and check URLS inside files and test them as https where they are https

```urlcheck -f filename -s```

## Version information:

```urlcheck -v```

## Help:

```urcheck or urlcheck -h```

## Features

* The script matches all URLs in a given file and bulk-checks their status codes
* Links with successful responses are printed in green, 400 and 404 status codes are printed in red; all others (unknown) are printed in grey.
* Code is optimized to only request headers.
* Results contain clickable links
* Test http links as https
