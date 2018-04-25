# fa-viber



## Install

* install with yarn

* package.json
```
{
  "name": "mysite",
  "version": "1.0.0",
  "repository": "myrepo.git",
  "author": "mmx <maxivak@gmail.com>",
  "license": "MIT",
  "dependencies": {
    "bootstrap": "4.1.0",
    "font-awesome": "4.7.0",
    "jquery": "3.2.1",
    "popper.js": "1.14.3",
    "fa-viber": "git+https://git@github.com/maxivak/fa-viber.git"

  }
}

```

```
yarn install
```

### Rails app with Bootstrap v4

* use fa-viber in your scss
```
@import 'font_awesome';

// fa-viber
$fa-viber-font-path:"fa-viber/fonts";

@font-face {
  font-family: 'fa-viber';
  src:font-url('#{$fa-viber-font-path}/fa-viber.eot?-3dwksg');
  src:font-url('#{$fa-viber-font-path}/fa-viber.eot?#iefix-3dwksg') format('embedded-opentype'),
  font-url('#{$fa-viber-font-path}/fa-viber.ttf?-3dwksg') format('truetype'),
  font-url('#{$fa-viber-font-path}/fa-viber.woff?-3dwksg') format('woff'),
  font-url('#{$fa-viber-font-path}/fa-viber.svg?-3dwksg#fa-viber') format('svg');
  font-weight: normal;
  font-style: normal;
}


@import 'fa-viber/fa-viber';
```


## Usage

- You can now use fa-viber like any other font awesome icon
```html
<i class="fa fa-viber fa-2x"></i>
```

# Examples
[Example](http://kukac7.github.io/fa-viber/)
