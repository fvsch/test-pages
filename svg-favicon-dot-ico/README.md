# SVG favicon test case

Simple setup to test SVG favicons in two ways:

1. Referenced in HTML as `<link rel="icon" type="image/svg+xml" href="/icon.svg" />`
2. Serving a SVG icon with a `Content-Type: image/svg+xml` for HTTP requests to `/favicon.ico`.

Running the test locally:

```sh
npm install && npm start
```

Then visit:

- http://localhost:5000/ (should show a blue camera icon)
- http://localhost:5000/explicit (should show a green eyedropper icon)
