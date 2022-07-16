# my-operator

Initalize the operator with the following command:
```bash
go mod init my-operator
```

Initalize kubebuilder:
```bash
kubebuilder init --domain shubhamtatvamasi.com
```

Create new API:
```bash
kubebuilder create api \
  --group my-operator \
  --kind MyCRD \
  --version v1
```


```bash
make manifests
```

