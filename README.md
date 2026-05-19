## About programm:

Compares two configuration files and shows a difference.

### Install:

for install all dependencies:
```sh
make install
```
for install packages:
```sh
npm link
```

### Tests

for to run tests:
```sh
make test
```

## Use of the programm

### Help

For to get help:
```sh
gendiff --help
```
or:
```sh 
gendiff -h
```
Formats supported by the program:
`.json`, `.yml`, `.yaml`

Supported output formats:
`json`, `plain`, `stylish`

### How to use
```sh
gendiff [options] <filepath1> <filepath2>
```

Options:
* -V, --version             output the version number
* -f, --format [type]       output format (choices: "stylish", "plain", "json", default: stylish)
* -h, --help                display help for command

### Example JSON and yml files:
[![asciicast](https://asciinema.org/a/461793.svg)](https://asciinema.org/a/461793)
