---
title: "Helm 插件安装"
---

## helm plugin install

安装一个或多个Helm插件

### 简介

该命令允许您通过VCS仓库url或者本地路径安装插件。

```shell
helm plugin install [options] <path|url>... [flags]
```

### 可选项

```shell
  -h, --help             help for install
      --version string   specify a version constraint. If this is not specified, the latest version is installed
```

### 从父命令继承的命令

```shell
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         username to impersonate for the operation
      --kube-ca-file string         the certificate authority file for the Kubernetes API server connection
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry/config.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### 请参阅

* [helm plugin](helm_plugin.md) - 安装、列举或卸载Helm插件
