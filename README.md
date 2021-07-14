This repository contains generated golang code for:
* Event Family: https://desp.kroger.com/event-family/5a39f520-f574-35a3-934e-6ca71e182ddf
* Version: v0.1.0

To use this in your go client, add the following requirements to your go.mod file.

```
module github.com/krogertechnology/my-go-client-application

go 1.13

require (
	github.com/actgardner/gogen-avro/v9 v9.0.0 // indirect
	github.com/rhammonds1-kr/desp-catalog-go-post-order-ratings v0.1.0
	...
```