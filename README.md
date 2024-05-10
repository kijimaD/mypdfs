# 送信

```
rsync -r -e ssh * xsrv:/home/kijima9791/mypdfs/
```

# 受信

```
rsync -r -e ssh xsrv:/home/kijima9791/mypdfs/* .
```
