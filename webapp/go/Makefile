GOPATH := /home/isucon/cco/webapp/go
export GOPATH

build:
		/home/isucon/local/go/bin/go build -v app

ensure:
		cd src/app && /home/isucon/go/bin/dep ensure -vendor-only

update:
		cd src/app && dep ensure

test:
		go test -v app

vet:
		go vet ./src/app/...
