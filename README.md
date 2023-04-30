# helm-charts
A collection of Helm charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/osnabrugge)](https://artifacthub.io/packages/search?repo=osnabrugge)

## Goal

This repo contains Helm charts that I have developed to run applications in my
[home Kubernetes cluster](https://github.com/osnabrugge/k8s-gitops.git). It is
based in [bjw-s](https://github.com/bjw-s/helm-charts) work.

This repo is not intended to be a replacement for any of the large collections
of Helm charts that are out there.

## Installation

The Helm repository can be installed as follows:

```console
helm repo add osnabrugge https://osnabrugge.github.io/helm-charts
```

You can then run `helm search repo osnabrugge` to search the charts.

## Documentation

Documentation can be found [here](https://osnabrugge.github.io/helm-charts/docs/).

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md)

## License

[Apache 2.0 License](./LICENSE)
