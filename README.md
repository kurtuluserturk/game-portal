# game-portal

Game portal with SCSS

# Website link of the projet

https://responsive-game-portal.netlify.app/

# My Notes:

I used some Sass partial such as \_abstracts, etc. but I didn't need to use 7-1 Sass Pattern because this project is not that complex big project so I chose this way.

Owl carousel library,

CSS gradient,

CSS flex and grid system was used.

Responsive design was checked using google device toolbar.

## Install Sass

You can install Sass on Windows, Mac, or Linux by downloading the package for
your operating system [from GitHub][] and [adding it to your `PATH`][path].
That's all—there are no external dependencies and nothing else you need to
install.

[from github]: https://github.com/sass/dart-sass/releases
[path]: https://katiek2.github.io/path-doc/

If you use Node.js, you can also install Sass using [npm][] by running

[npm]: https://www.npmjs.com/

```
npm install -g sass
```

**However, please note** that this will install the pure JavaScript
implementation of Sass, which runs somewhat slower than the other options listed
here. But it has the same interface, so it'll be easy to swap in another
implementation later if you need a bit more speed!

See [the Sass website](https://sass-lang.com/install) for more ways to install
Sass.

Once you have Sass installed, you can run the `sass` executable to compile
`.sass` and `.scss` files to `.css` files. For example:

```
sass source/stylesheets/index.scss build/stylesheets/index.css
```

## Learn Sass

Check out [the Sass website](https://sass-lang.com/guide) for a guide on how to
learn Sass!

## This Repository

This repository isn't an implementation of Sass. Those live in
[`sass/dart-sass`][] and [`sass/libsass`][]. Instead, it contains:

[`sass/dart-sass`]: https://github.com/sass/dart-sass
[`sass/libsass`]: https://github.com/sass/libsass

- [`spec/`][], which contains specifications for language features.
- [`proposal/`][], which contains in-progress proposals for changes to the
  language.
- [`accepted/`][], which contains proposals that have been accepted and are
  either implemented or in the process of being implemented.

[`spec/`]: https://github.com/sass/sass/tree/master/spec
[`proposal/`]: https://github.com/sass/sass/tree/master/proposal
[`accepted/`]: https://github.com/sass/sass/tree/master/accepted

Note that this doesn't contain a full specification of Sass. Instead, feature
specifications are written as needed when a new feature is being designed or
when an implementor needs additional clarity about how something is supposed to
work. This means many of the specs in `spec/` only cover small portions of the
features in question.

### Versioning Policy

The proposals in this repository are versioned, to make it easy to track changes
over time and to refer to older versions. Every version has a Git tag of the
form `proposal.<name>.draft-<version>`. A new version should be created for each
batch of changes.

Every version has a major version, and they may have a minor version as well
(indicated `<major>.<minor>`). The minor version should be incremented for
changes that don't affect the intended semantics of the proposal; otherwise, the
major version should be incremented.
