# ESEP Grade Calculator

Overview:

The Grade Calculator is a Go library that calculate your grades using assignment, exam, and essay scores. It converts the numerical value into a final letter grade.
Each category can have a different weight to make it more adaptable. 

Structure:

grade_calculator.go - Contains the grade calculator implementation and grading logic\
grade_calculator_test.go - Contains the unit tests for the calculator\
go.mod - defines Go module and version

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
