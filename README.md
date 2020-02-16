# go-tmpl | A Template Repository for Golang Project

[![CI](https://github.com/Shivam010/go-tmpl/workflows/CI/badge.svg)](https://github.com/Shivam010/go-tmpl/actions)
[![Coverage Status](https://coveralls.io/repos/github/Shivam010/go-tmpl/badge.svg)](https://coveralls.io/github/Shivam010/go-tmpl)
[![Go Report Card](https://goreportcard.com/badge/github.com/Shivam010/go-tmpl?dropcache)](https://goreportcard.com/report/github.com/Shivam010/go-tmpl)
[![GoDoc](https://godoc.org/github.com/Shivam010/go-tmpl?status.svg)](https://godoc.org/github.com/Shivam010/go-tmpl)
[![License](https://img.shields.io/badge/license-apache2-mildgreen.svg)](https://github.com/Shivam010/go-tmpl/blob/master/LICENSE)

`go-tmpl` repository let users generate new repositories with the simplest 
structure for any Golang project.

Package `tmpl` is the template repository for any Golang project, that
can be used to generate new project with a simplest file structure, along
with a build workflow and code of conducts & guidelines, a make utility
file, a license and a readme. The Package is initialised with go modules,
and a doc file.

The Project structure:
```
    .
    ├── .github
    │   ├── workflows
    │   │   └── build.yml
    │   └── FUNDING.yml
    ├── .gitignore
    ├── CODE_OF_CONDUCT.md
    ├── CONTRIBUTING.md
    ├── LICENSE
    ├── Makefile
    ├── README.md
    ├── doc.go
    ├── go.mod
    ├── main.go
    └── main_test.go
```

### Request for Contribution
Changes and improvements are more than welcome!! <br>
Feel free to fork, create issues or pull a request. <br>
And be sure to review the [contributing guidelines](./CONTRIBUTING.md) and [code of conduct](./CODE_OF_CONDUCT.md).

### License
The package, its design and code all are licensed under the [Apache license 2.0](./LICENSE)
