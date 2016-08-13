# Promesse

[![Build Status](https://travis-ci.org/djfm/promesse.svg?branch=master)](https://travis-ci.org/djfm/promesse)

<a href="https://promisesaplus.com/">
    <img src="https://promisesaplus.com/assets/logo-small.png" alt="Promises/A+ logo"
         title="Promises/A+ 1.0 compliant" align="right" />
</a>

*Promesse* is a [Promises/A+](https://github.com/promises-aplus/promises-tests) compliant Promise library.

I've written it because I love promises in JS and I like to know how the tools I use work.
Besides, it's a nice exercise to work against an existing **huge** test suite.

## Installing

This is probably not very useful since promises are standard, but, if for some reason you need to:

```bash
npm i --save aplus-promesse
```

## Testing

```bash
git clone https://github.com/djfm/promesse
cd promesse
npm i
npm test
```

There are two test suites, the one from [Promises/A+](https://github.com/promises-aplus/promises-tests), and the one I wrote to help me when I did not understand the feedback from the official tests.

## Making it Smaller

Now that the library is working and tested, I want to make it smaller in terms
of number of lines of code.

The rules are:
  - lines must not exceed 80 columns
  - block declarations (*by that I mean a declaration that takes more than one line or a succession of one line declarations*) and top level declarations are
    followed with one blank line at least
  - more subjectively: the code needs to remain easy
    to read
