# Descheduler Package

A Kpt package for [kubernetes Descheduler](https://github.com/kubernetes-sigs/descheduler).

## Requirement

* [Kpt](https://github.com/GoogleContainerTools/kpt)
* [Kustomize](https://github.com/kubernetes-sigs/kustomize)

## Usege

```console
$ kpt pkg get https://github.com/y-taka-23/kpt-descheduler.git descheduler
$ kpt live init descheduler/
$ kustomize build descheduler/ | kpt live apply
```
