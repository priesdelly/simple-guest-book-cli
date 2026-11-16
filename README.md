# Simple Guest Book CLI

A command-line guest book. It stores guest entries in a SQLite database.

Status: early stage. The program has an entry point only.

## Stack

| Part     | Choice  |
| -------- | ------- |
| Language | Go      |
| Database | SQLite  |
| Editor   | VS Code |

## Prerequisites

### Go

Install Go 1.23 or later from <https://go.dev/dl/>. Choose the installer for your platform. Then check the install:

```sh
go version
```

### SQLite

You do not need to install SQLite itself. The Go standard library has the `database/sql` package, but it has no SQLite driver. Add a driver to the project when you start the database code. For example, `modernc.org/sqlite` is pure Go and needs no C compiler:

```sh
go get modernc.org/sqlite
```

### Editor

1. Install VS Code from <https://code.visualstudio.com/>.
2. Install the [Continue extension](https://marketplace.visualstudio.com/items?itemName=Continue.continue).

## Run

```sh
go run .
```

Expected output:

```text
This is the main entry point
```
