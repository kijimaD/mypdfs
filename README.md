[shelf](https://github.com/kijimaD/shelf)で生成したPDF本棚のメタ情報。PDF本体はプライベートな空間にある。

## Prepare

```
go install github.com/kijimaD/shelf@main
shelf gen .
shelf web
```

## (private) Sync PDF

事前にSSH configを設定しておくこと。

送信

```
rsync -r -e ssh * xsrv:~/mypdfs/
```

受信

```
rsync -r -e ssh xsrv:~/mypdfs/* .
```
