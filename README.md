# Paramita store catalog

Product catalog for a store.
Build using [Hugo](https://gohugo.io/) and hosted on [Netlify](https://www.netlify.com/).

Hugo is a static site generator, so static pages and assets are generated a publishing time. 
After that the content is pushed to a [github repo](https://github.com/PiterDaCosta/productos-paramita), configured to sync with Netlify cdns so 
whenever something is pushed there Netlify with be notified and the content will be automatically exposed.

The site is currently online on the following address: [https://param-hugo.netlify.app](https://param-hugo.netlify.app)

## Hugo installation

On ubuntu/debian, just do:
```
sudo apt install hugo
```

## Dev notes
Hugo comes with a built in development server that can be run with

```
hugo server -D
```

To generate the static files just run the hugo command without parameters.
```
hugo
```

Then just push the generated content to the repository main branch and wait, the content will be automatically published.
