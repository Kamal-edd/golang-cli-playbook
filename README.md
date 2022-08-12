## Module 1: Print environment information using go env

Print the environment information:
```
cd module1
go env > module1.txt
```

Print the environment information in JSON format:
```
env -json > module1.json  
cd ..
```

## Module 2: Format source code using go fmt and gofmt

Use `go fmt` to format and write back to the source file:
```
cd module2
go fmt module2_hello.go
```

Format source code using a standalone program with proper flags:
```
gofmt -l -w module2_code.go
cd ..
```

## Module 3: Download and install packages using go get

Use `go get` to install a package:
```
go get github.com/nathan-osman/go-sunrise
cp .\go.mod .\module3\go.mod.copy
```

## Module 4: Compile and install packages using go install

Use `go install` to compile and install a package
```
go get github.com/codemodus/kace 
go install github.com/codemodus/kace
cp .\go.mod .\module4\go.mod.copy
```

## Module 5: Import missing packages

Install and run the *goimports* command
```
go install golang.org/x/tools/cmd/goimports@latest
cd .\module5\
goimports -w .\module5_code.go
cd ..

```

## Module 6: Print the document for a function

Print out the added comment and direct to a file
```
cd .\module6\
go doc FunctionForModule6GoDoc > module6.txt
cd ..
```

## Module 7: Scan for directives and run commands on existing source code

Add the directive, then Run go generate to import the packages
```
cd .\module7\
go generate

```