# desktop

Go/HTML/CSS/JS Desktop application scaffold.

## How it works

Build your application using Go APIs, and an HTML/CSS/JavaScript front-end
inside the `www` folder, just like a normal web root.

Building the package will generate a `.app` mac application file that will
host a simple web server serving the assets and any other endpoints you build.

When run, the application will open a web view into the `www` folder.

## Usage

Build with: `make build`

## Dependencies

* https://github.com/zserge/webview - Web view
* https://github.com/jteeuwen/go-bindata and https://github.com/elazarl/go-bindata-assetfs - Asset binding

## Install

Use `make install` to run:

```
& go get github.com/machinebox/appify
$ go get github.com/jteeuwen/go-bindata/...
$ go get github.com/elazarl/go-bindata-assetfs/...
```

## Contribute?

We think this project could be much bigger. Got ideas? Get in touch.

## What next?

If you want to build other kinds of Go application, and have them built into
macOS applications, check out our [machinebox/appify](https://github.com/machinebox/appify)
project.