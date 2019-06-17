# Go-Lang

Have:
```sh
export GOPATH="${HOME}/.go"
export GOROOT="$(brew --prefix golang)/libexec"
export PATH="$PATH:${GOPATH}/bin:${GOROOT}/bin"
```

in your `.zshrc` or `.bashrc` (or equivalent) then install `go` using brew:

```bash
brew install go
```

Run:
```bash
go run hello-world.go
```

---

Ref:
- https://ahmadawais.com/install-go-lang-on-macos-with-homebrew/