Self-study from the GOLANG free course : https://www.youtube.com/watch?v=O_UuGuF_tcE&fbclid=IwAR3DKyW7ctIiRAdjTS2uo3UPtY_2AI2qsdx4B9mzmpfXRfD3y0NWVeKQEXY

My short note from VDO

---------------
### GO CLI : How to run the GO code?
---------------
go Run xxx.go : compiles a bunch of go source code files
go Build xxx.go : compiles and execute one or two files
go fmt : formats all the code in each file in the current directory
go install : compiles and installs a package
go get : downloads the raw source code of someone else's package
go test : runs any tests associated with the current project

---------------
### Anatomy of 'package main'
---------------
[Package] == [Project] == [Workspace]
Package Main
    -main.go >> must 'import "fmt" // package name and file name must be the same.
    -xxx.go >> must refer to 'package main' at  the first line and each file contain 'func main'
Types of Packages
    -Executable: Generates a file that we can run
    -Reusable: Code used as 'helpers'. Good place to put reusable logic



