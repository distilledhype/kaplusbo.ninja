# Tiny Static

> A tiny static site generator for tiny sites, using [Jade](http://jade-lang.com) and
the [npm scripts property](https://docs.npmjs.com/misc/scripts).

## Install

Clone this repository.

```
git clone git@github.com:distilledhype/tiny-static.git <TARGET DIR>
```

You may want to change `origin` to the remote repo of your choice.

```
git remote set-url origin <YOUR REPO URL>
```

Install the devDependencies.

```
npm install
```

## Use

Edit the jade files in `jade/site` to your heart's content.

Run tiny-static with

```sh
npm run tiny-static
```

or

```sh
npm start
```

This will compile the Jade files in `jade/site` into a folder called `out`.
Extend this static site generator with more npm tasks to add your asset building and so forth.

## Markdown Support

Install the `marked` package and save it as a devDependency.

```
npm install marked --save-dev
```

Now use the `:markdown` filter in your Jade files as described
[here](http://jade-lang.com/reference/filters/).

## License
MIT
