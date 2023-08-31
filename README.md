HCL-LINT
---

Forked from github.com/n2ux/hcl-lint 

## Usage:

```sh
$ go install github.com/chrisvanmeer/hcllint@latest
$ hcllint - < config_file
$ hcllint directory config_file ...
```

Lint's an arbitrary number of input arguments. If a directory is specified,
it will check that directory for *.hcl files and run the linter on them as well.
If the first argument is a '-' it will read from stdin and ignore any following arguments.
