## Module 1

Print the environment information:
```
go env > module1.txt
```

Print the environment information in JSON format:
```
env -json > module1.json  
```

## Module 2

Use go fmt to format and write back to the source file:
```
go fmt module2_hello.go
```

Format source code using a standalone program with proper flags:
```
gofmt -l -w module2_code.go
```
