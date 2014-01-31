# Makerstrap

## Usage

```
bower install makerstrap
```

## How lazy are you?

### Real frikin lazy

Includes Font Awesome and Open Sans automagically. Don't use this in production please.

```html
<link rel="stylesheet" href="bower_components/makerstrap/makerstrap.complete.min.css">
```

### Somewhat lazy

```html
<link href="https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,700italic,400,300,700" rel="stylesheet">

<link href="https://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css" rel="stylesheet">

<link href="bower_components/makerstrap/makerstrap.min.css" rel="stylesheet">
```

### Actually, I'm a ninja, hit me

This is for Less importing:

```css
@makerstrap-bower-path: '../bower_components';
@import 'bower_components/makerstrap/less/makerstrap';

```

## Contributing

### Development environment

1. Install bower and grunt-cli if you don't have them:

```
npm install -g bower
npm install -g grunt-cli

```

2. Clone this repo
3. Run `npm install` from the root of `makerstrap`.
4. Run `grunt` to start the dev server and LESS watch task, navigate to `http://localhost:1944/demo` to see the demo page.
5. The main LESS files are in the `less/` directory.
6. Read http://getbootstrap.com/css/#less to orient yourself on extending Bootstrap with LESS
