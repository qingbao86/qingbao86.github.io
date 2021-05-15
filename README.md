# Requirement
- Install go
https://golang.org/doc/install

- [Hugo](https://gohugo.io/)

```sh
git clone https://github.com/gohugoio/hugo.git
cd hugo
go install --tags extended
```

# Build
```sh
hugo server --renderToDisk --disableFastRender -t zzo -b  "https://yubaoliu.github.io/passive-income/"
```


# Add image

```sh
{{< img src="/images/ethprofitminer.png" title="ethprofitminer" caption="" alt="ethprofitminer" width="700px" position="center" >}}
```
