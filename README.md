# lingwei
CGO_ENABLED=1 CC=x86_64-w64-mingw32-gcc CXX=x86_64-w64-mingw32-g++ GOOS=windows GOARCH=amd64 go build -o lingwei.exe main.go


CGO_ENABLED=1 GOOS=windows GOARCH=amd64 go build -o lingwei.exe main.go