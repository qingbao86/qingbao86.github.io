
#Install hugo

see https://github.com/gohugoio/hugo

```sh
CGO_ENABLED=1 go install --tags extended
```

# Build
```sh
hugo server --renderToDisk --disableFastRender -t zzo -b  "https://yubaoliu.github.io/passive-income/"
```


# Add image

```sh
{{< img src="/images/ethprofitminer.png" title="ethprofitminer" caption="" alt="ethprofitminer" width="700px" position="center" >}}
```
