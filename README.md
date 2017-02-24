# tmpl

An command line tool for parsing and generating template files for Go (Golang).

[![](https://img.shields.io/circleci/token/________________________________________/project/abcum/tmpl/master.svg?style=flat-square)](https://circleci.com/gh/abcum/tmpl) [![](https://img.shields.io/badge/status-alpha-ff00bb.svg?style=flat-square)](https://github.com/abcum/tmpl) [![](https://img.shields.io/badge/godoc-reference-blue.svg?style=flat-square)](https://godoc.org/github.com/abcum/tmpl) [![](https://goreportcard.com/badge/github.com/abcum/tmpl?style=flat-square)](https://goreportcard.com/report/github.com/abcum/tmpl) [![](https://img.shields.io/coveralls/abcum/tmpl/master.svg?style=flat-square)](https://coveralls.io/github/abcum/tmpl?branch=master) [![](https://img.shields.io/badge/license-Apache_License_2.0-00bfff.svg?style=flat-square)](https://github.com/abcum/tmpl) 

#### Features

- Generate files from templates
- Useful for go:generate commands
- Accepts data as json or from a file
- Templates are processed and compiled
- Process and compile multiple templates at once

#### Installation

```bash
go get github.com/abcum/tmpl
```

#### Usage

```bash
tmpl -file data.json file1.go.tmpl file2.go.tmpl
```

```bash
tmpl -data '["foo","bar","baz"]' file1.go.tmpl file2.go.tmpl
```
