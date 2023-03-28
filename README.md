# Gatling Cloud Documentation

## Prerequisites:

You need [Go](https://golang.org/doc/install) and [Hugo](https://gohugo.io/getting-started/installing/) installed.

## Setup:

```
hugo mod get -u 
hugo mod npm pack
npm install
```

## Development server:

```
hugo server -D --debug --baseURL="http://localhost:1313/docs/cloud/"
```

In case of issue such as `failed to extract shortcode: template for shortcode "img" not found`, run `hugo mod clean`.
