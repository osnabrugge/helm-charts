# multus

![Version: 4.0.1](https://img.shields.io/badge/Version-4.0.1-informational?style=flat-square) ![AppVersion: v4.0.1](https://img.shields.io/badge/AppVersion-v4.0.1-informational?style=flat-square)

multus CNI allows multiple NICs per pod

**Homepage:** <https://github.com/k8s-at-home/charts/tree/master/charts/stable/multus>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| sean | <sean@seanv.com> |  |

## Source Code

* <https://github.com/k8snetworkplumbingwg/multus-cni>

## Requirements

Kubernetes: `>=1.16.0-0`

| Repository | Name | Version |
|------------|------|---------|
| https://bjw-s.github.io/helm-charts | common | 1.3.2 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| cni.image.pullPolicy | string | `"IfNotPresent"` | CNI installer pull policy |
| cni.image.repository | string | `"ghcr.io/osnabrugge/cni-plugins"` | CNI installer repostory |
| cni.image.tag | string | `"v1.2.0"` | CNI installer tag |
| cni.paths.bin | string | `"/opt/cni/bin"` | CNI plugin binaries folder Older versions of CNI for k3s may need this changed |
| cni.paths.config | string | `"/etc/cni/net.d"` | CNI config folder Older versions of CNI for k3s may need this changed |
| cni.version | string | `"0.3.1"` | CNI interface version |
| image.pullPolicy | string | `"IfNotPresent"` | multus installer pull policy |
| image.repository | string | `"ghcr.io/k8snetworkplumbingwg/multus-cni"` | multus installer repostory |
| image.tag | string | `"v4.0.1"` | multus installer tag |

----------------------------------------------
