# helix

Helix editor config

## Languages

### Go

Required dependencies;

- SDK Download from https://go.dev/dl
- gopls installed `go install golang.org/x/tools/gopls@latest`
- goimports installed `go install golang.org/x/tools/cmd/goimports@latest`
- delve installed `go install github.com/go-delve/delve/cmd/dlv@latest` 

### C#

Required dependencies;

- dotnet sdk `sudo apt install dotnet-sdk-8.0`
- language server
  - This is a whole problem of OmniSharp just not working, 
    we need to install [this](https://github.com/razzmatazz/csharp-language-server)
    as a dotnet tool instead
  - `dotnet tool install --global csharp-ls`

### JSON

Required dependencies;

- npm, unfortunately :(
- vscode-json-languageserver installed `npm install -g vscode-json-languageserver`

### Jsonnet

Required dependencies;

- [Go](#go) SDK
- jsonnet install `go install github.com/google/go-jsonnet/cmd/jsonnet@latest`
- download *jsonnet-language-server* to a location in $PATH from [github project](https://github.com/grafana/jsonnet-language-server)

### YAML

Required dependencies;

- npm, again...
- yaml-language-server installed `npm install -g yaml-language-server`
