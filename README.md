# Webflow Dev Setup

This is a basic setup for developing JavaScript and TypeScript inside of Webflow.

### Setup

1. [Clone the repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)


2. Install packages

```npm install```

### Local Development

1. Place this script tag in your Webflow Site.

```<script src="http://localhost:8080/bundle.js" type="text/javascript" crossorigin="anonymous"></script>``` 

2. Run the webpack dev server

```npm run serve```

### Production

1. Build the production JavaScript

```npm run build```
