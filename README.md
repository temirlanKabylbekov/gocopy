# Utility to copy files
[![Coverage Status](https://coveralls.io/repos/github/temirlanKabylbekov/gocopy/badge.svg?branch=master)](https://coveralls.io/github/temirlanKabylbekov/gocopy?branch=master)
## Installation

```
go get -d github.com/temirlanKabylbekov/gocopy
go install github.com/temirlanKabylbekov/gocopy
```   

## Documentation
```bash
gocopy --help
  -from string
        file path to read from
  -limit int
        limit bytes to read from file (default -1)
  -offset int
        offset bytes in input file
  -to string
        file path to write to
```

## Quick start 
```bash
cd $GOPATH/bin
gocopy -from src.txt -to dest.txt -limit 10 -offset 5
```

## Development
```$xslt
git clone https://github.com/temirlanKabylbekov/gocopy
make test
```