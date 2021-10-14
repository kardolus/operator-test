# Operator-test

Walked through [this demo](https://medium.com/manikkothu/build-kubernetes-operator-using-kubebuilder-4bfef299757d).

## Init
```
go mod init github.com/kardolus/operator-test

kubebuilder init --domain demo.operator-test.io
```

## Create API and controllers
```
kubebuilder create api --group elastic --kind MyOperatorTest --version v1

Create Resource [y/n]
y
Create Controller [y/n]
y
```
