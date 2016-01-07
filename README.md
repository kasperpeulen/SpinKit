# [SpinKit](http://tobiasahlin.com/spinkit/)

Simple loading spinners animated with CSS. See [demo](http://tobiasahlin.com/spinkit/). SpinKit uses hardware accelerated (`translate` and `opacity`) CSS animations to create smooth and easily customizable animations. 

## Usage

### Regular CSS

Grab the HTML and CSS for a spinner from the example files, or add SpinKit directly to your project with `pub`:

```bash
$ den install spinkit
```

### SCSS

If you're using SCSS you can include specific spinners (rather than all of them) by importing them one by one:

```scss
@import 'packages/spinkit/scss/spinners/1-rotating-plane',
        'packages/spinkit/scss/spinners/3-wave';
```

You currently need to use an [autoprefixer](https://github.com/postcss/autoprefixer) if you want to support all browsers. If you're compiling your SCSS with gulp you can use [gulp-autoprefixer](https://github.com/sindresorhus/gulp-autoprefixer), and [grunt-autoprefixer](https://github.com/nDmitry/grunt-autoprefixer) if you use grunt.

Variables that can be overridden are listed in [scss/_variables.scss](https://github.com/tobiasahlin/SpinKit/blob/master/scss/_variables.scss).

## Contributing

See [CONTRIBUTING.md](https://github.com/tobiasahlin/SpinKit/blob/master/CONTRIBUTING.md) for details.
