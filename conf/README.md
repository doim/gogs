Execute following command in ROOT directory when anything is changed:

```
$ go get -u github.com/go-bindata/go-bindata/...
$ make bindata
```
�°�ʹ�÷�ʽ
```
$ cd github.com\gogs\gogs
$ go get -u github.com/go-bindata/go-bindata/...
$ go-bindata -pkg bindata -o pkg/bindata/bindata.go conf/...
```