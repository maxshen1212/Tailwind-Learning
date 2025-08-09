# Tailwind CSS v4. intro (simplest version)


Look at the [Tailwind documentation](https://tailwindcss.com/docs/installation/tailwind-cli) to learn more.

## Initialize
npm init -y (-y=yes for all)

## Install
npm i tailwindcss @tailwindcss/cli
1. (We don't need to install postcss and autoprefixer anymore)
2. Tailwind CSS v4 they seperate CLI from tailwindcss to @tailwindcss/cli.

## Make Directories
1. mkdir src
    nano mytailwind.css
3. mkdir css

## Run Script
1. Dev "tailwindcss -i ./src/mytailwind.css -o ./css/tailwind.css --watch"
(Using npx "npx @tailwindcss/cli -i ./src/mytailwind.css -o ./css/tailwind.css --watch")
2. Build "NODE_ENV=production tailwindcss -i ./src/mytailwind.css -o ./css/tailwind.css --minify"

## Import
Add <link href="./css/tailwind.css" rel="stylesheet" /> in your index.html

Then you have a static html file using TailwindCSS.