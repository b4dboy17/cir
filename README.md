# cir
A go language based script which will bypass AV (for now)

# Usage
### First write your shellcode in `main.go` file using any C2 like metasploit, sliver, AdaptixC2 or any C2 you like
### then compile into exe
```
GOOS=windows GOARCH=amd64 go build -ldflags="-s -w -H=windowsgui"
```
