# go-stripe-payments

Collecting payments with golang

## Setup

Replace ===YOUR STRIPE SECRET KEY=== with your stripe Publishable key in payments/setup.go
and     ===YOUR STRIPE PUBLIC KEY===  with your stripe Secret key in frontend/src/App.js

## Run go API

 In the parent directory run `go run main.go`

if using air for live reload, first install the Air CLI tool by running the following command:
`go install github.com/cosmtrek/air@latest`

Finally, run the Gin application from the terminal using Air:
`air`

## Run React frontend

``` bash
cd frontend
npm i
npm start
```
