# go-rss-aggregator

go practice: <https://github.com/bootdotdev/fcc-learn-golang-assets/tree/main>

## note

- go

```bash
go get github.com/xxx
go mod tidy
go mod vendor
```

- goose

```bash
go install github.com/kyleconroy/sqlc/cmd/sqlc@latest
cd sql/schema
goose postgres CONN up
```

- sqlc

```bash
go install github.com/pressly/goose/v3/cmd/goose@latest
sqlc generate
```

- run server

```bash
go build && ./go-rss-aggregator
```
