# go-webApp

Go WebApp Tutorial

Covered in this tutorial:

-   [x] Creating a data structure with load and save methods
-   [x] Using the net/http package to build web applications
-   [ ] Using the html/template package to process HTML templates
-   [ ] Using the regexp package to validate user input
-   [ ] Using closures

## 1st step

```go
go build wiki-page.go
```

To run the Wiki App

Wiki 1st (will generate the Sample Page file)

```go
./wiki-page
```

## 2nd step

Build the webserver

```go
go build webserver.go
```

To start the webserver

```go
./webserver
```

Then http://localhost:8080/Beautiful

Wiki Webserver

```go
go build wiki-web.go
```

```go
./wiki-web
```

Then http://localhost:8080/view/TestPage
(requires TestPage.txt)
