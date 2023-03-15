# Go Multimodule Sample

Modules:

- `mod-a`
- `mod-b`

### How to tag version?

Add module name to tag version such as `mod-a/v0.0.1`, `mod-b/v0.0.2`

### How to install each module?

```shell
# install latest version of mod-a
go get github.com/abdularis/go-multimodule-sample/mod-a

# install specific version of mod-b
go get github.com/abdularis/go-multimodule-sample/mod-b@v0.0.2
```