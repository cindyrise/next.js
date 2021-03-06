[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/zeit/next.js/tree/master/examples/basic-css)

# With styled-jsx plugins

## How to use

Download the example [or clone the repo](https://github.com/zeit/next.js):

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/master | tar -xz --strip=2 next.js-master/examples/with-styled-jsx-plugins
cd with-styled-jsx-plugins
```

Install it and run:

```bash
npm install
npm run dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

Next.js ships with [styled-jsx](https://github.com/zeit/styled-jsx) allowing you
to write scope styled components with full css support. This is important for
the modularity and code size of your bundles and also for the learning curve of the framework. If you know css you can write styled-jsx right away.

This example shows how to configure styled-jsx to use external plugins to modify the output. Using this you can use PostCSS, SASS (SCSS), LESS, or any other pre-processor with styled-jsx. You can define plugins in `.babelrc`. In this case PostCSS was used as an example. PostCSS plugins are defined in `package.json`.

More details about how plugins work can be found in the [styled-jsx readme](https://github.com/zeit/styled-jsx#css-preprocessing-via-plugins)
