# __PROJECT__

__PROJECT__ does something good.

[![Build Status](https://github.com/xmidt-org/__PROJECT__/workflows/CI/badge.svg)](https://github.com/xmidt-org/__PROJECT__/actions)
[![codecov.io](http://codecov.io/github/xmidt-org/__PROJECT__/coverage.svg?branch=main)](http://codecov.io/github/xmidt-org/__PROJECT__?branch=main)
[![Go Report Card](https://goreportcard.com/badge/github.com/xmidt-org/__PROJECT__)](https://goreportcard.com/report/github.com/xmidt-org/__PROJECT__)
[![Apache V2 License](http://img.shields.io/badge/license-Apache%20V2-blue.svg)](https://github.com/xmidt-org/__PROJECT__/blob/main/LICENSE)
[![GitHub release](https://img.shields.io/github/release/xmidt-org/__PROJECT__.svg)](CHANGELOG.md)
[![PkgGoDev](https://pkg.go.dev/badge/github.com/xmidt-org/__PROJECT__)](https://pkg.go.dev/github.com/xmidt-org/__PROJECT__)

## Setup

1. Search and replace __PROJECT__ with your project name.
1. Initialize `go.mod` file: `go mod init github.com/xmidt-org/__PROJECT__`
1. Add org teams to project (github.com Settings > Manage Access): 
    - xmidt-org/admins with Admin role
    - xmidt-org/server-writers with Write role
1. Add options:
    - Settings > General
        - Select 'Allow auto-merge'
        - Select 'Automatically delete head branches'
1. Releases are created by tagging the repository like: `v1.2.3` using SemVer and pushing the tag.
1. For libraries:
    1. Update the .github/workflow/ci.yml file so it says 'release-type': 'library'
1. For applications:
    1. Remove PkgGoDev badge from this file.
    1. Add project binaries to `.gitignore` file.
1. Fix the codecov.io badge by going here: https://app.codecov.io/gh/xmidt-org/__PROJECT__/config/badge and getting the badge link.


## Summary

Summary should be a small paragraph explanation of what this project does.

## Details

Add details here.

## Install

Add details here.

## Contributing

Refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## Code of Conduct

This project and everyone participating in it are governed by the [XMiDT Code Of Conduct](https://xmidt.io/docs/community/code_of_conduct/). 
By participating, you agree to this Code.

