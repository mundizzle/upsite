# Upsite [<img src="https://jonathantneal.github.io/node-logo.svg" alt="" width="90" height="90" align="right">][Upsite]

[![NPM Version][npm-img]][npm-url]
[![Build Status][cli-img]][cli-url]
[![Support Chat][git-img]][git-url]

[Upsite] lets you start a local server without any configuration.

```bash
npx upsite
```

HTML, CSS, and JS files are automatically transformed using [pHTML], [PostCSS],
and [Babel].

---

[Upsite] automatically spins up a server and lets you start writing to files —
batteries included. Once started, Upsite creates a `package.json` file and a
`public` folder with HTML, CSS, and JS files inside of it. It also installs
[Express], configuring it to intercept `.html` files for [pHTML], `.css` files
for [PostCSS], and `.js` files for [Babel]. It also creates a self-signed SSL
certificate for HTTPS and attempts to certify it on your machine.

[cli-img]: https://img.shields.io/travis/jonathantneal/upsite.svg
[cli-url]: https://travis-ci.org/jonathantneal/upsite
[git-img]: https://img.shields.io/badge/support-chat-blue.svg
[git-url]: https://gitter.im/postcss/postcss
[npm-img]: https://img.shields.io/npm/v/upsite.svg
[npm-url]: https://www.npmjs.com/package/upsite

[Babel]: https://github.com/babel/babel/
[Express]: http://expressjs.com/
[Express Variable]: https://github.com/jonathantneal/express-variable
[pHTML]: https://github.com/phtmlorg/phtml
[PostCSS]: https://github.com/postcss/postcss
[Upsite]: https://github.com/jonathantneal/upsite
