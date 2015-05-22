# tiny-static

> A tiny static site generator using [Jade](http://jade-lang.com).

## Install

Clone this repository.

```sh
git clone git@github.com:distilledhype/tiny-static.git
```

You might want to change your origin to the repo of your choice.

```sh
git remote set-url origin <YOUR REPO URL>
```

Install the devDependencies.

```sh
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

## License
MIT
