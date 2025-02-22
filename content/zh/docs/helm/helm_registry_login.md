---
title: "Helm 注册表登录"
---

## helm registry login

登录注册表

### 简介

用远程注册表进行身份验证。

```shell
helm registry login [host] [flags]
```

### 可选项

```shell
  -h, --help              help for login
      --insecure          allow connections to TLS registry without certs
  -p, --password string   registry password or identity token
      --password-stdin    read password or identity token from stdin
  -u, --username string   registry username
```

### 从父命令继承的可选项

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

* [helm registry](helm_registry.md) - 登录或登出注册表
