# Trade Collector
Import all trades from Bitfinex, BTC-E, MtGox, BTC-China, OKCoin and more.

# install
```
gvm install go1.1.1
gvm use go1.1.1 --default
export GOPATH=$HOME/golibs/
go get github.com/go-sql-driver/mysql
go get launchpad.net/goyaml
```

# run
```
export DB=username:password@tcp(host:port)/dbname
go run harvest/harvest.go harvest/btce.go harvest/mtgox.go  harvest/okcoin.go harvest/btcchina.go  harvest/utils.go harvest/bitfinex.go
```
