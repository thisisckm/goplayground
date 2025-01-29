build:
	go build -o hello ./src

build-windows:
	GOOS=windows GOARCH=amd64 go build -o hello.exe ./src

build-linux:
	GOOS=linux GOARCH=amd64 go build -o hello ./src

build-mac:
	GOOS=darwin GOARCH=amd64 go build -o hello ./src

run: build
	./hello

clean:
	rm -f hello