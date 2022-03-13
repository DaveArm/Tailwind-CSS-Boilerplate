# Tailwind CSS Boilerplate

Tailwind CSS boilerplate for HTML projects. Bare-bones HTML starter template with Tailwind CSS, PostCSS, Gulp, Browsersync &amp; Imagemin.

The main purpose of this boilerplate is to simplify the configuration of Tailwind CSS for beginners.

## How to use this Tailwind CSS Boilerplate


1. Install the dependencies:

    ```bash
    # if you are using npm
    npm install
    ```

2. Start the development server:

    ```bash
    # if you are using npm
    npm run dev
    ```

    Now you should be able to see the project running at [localhost:3000](http://localhost:3000)

    ```bash
    # if you see a PostCSS error, try running
    npm i postcss -D
    ```

4. Open `./index.html` in your editor (VS Code recommended) and start editing!

## Optimizing for production

Tailwind CSS output needs to be optimized for the production use. The development version for the CSS file is almost 4MB which is not good for production websites. [Read this for more details](https://tailwindcss.com/docs/optimizing-for-production). This boilerplate **helps you generate the production version** of your CSS file easily & quickly.

I have configured `purge` option for PostCSS & Tailwind CSS. To build optimized version of your custom CSS, simply run:

```bash
# if you are using npm
npm run build
```

For optimising your images, simply run:

```bash
# if you are using npm
npm run build-images
```
