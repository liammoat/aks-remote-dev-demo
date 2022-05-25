# AKS Remote Dev Demo

## Setup

```
./scripts/setup d36b4d03-f667-4aaa-b4fd-b68086aa791a lm-k8s-demo-rg lm-k8s-demo-aks dev-containers
```

## Build

```
./scripts/build lmk8sdemoarc dotnet 3.1 3.1
```

## Run

Run a self-built images:

```
./scripts/run lajm-dev-dotnet-31 lmk8sdemoarc.azurecr.io/dev-containers/dotnet:3.1
```

Run a public image:

```
./scripts/run lajm-dev-dotnet-60 mcr.microsoft.com/vscode/devcontainers/dotnet:6.0
```