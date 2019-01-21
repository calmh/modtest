There are two commands:

- `cmd/cmda` which depends only on `github.com/alecthomas/kingpin`

- `cmd/cmdb` which depends only on `github.com/sirupsen/logrus`

The go.mod / go.sum files should track all of these regardless of the sequence of `go build`, `go install`, etc.

The Makefile builds both commands.
