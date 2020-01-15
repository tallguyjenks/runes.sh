# runes.sh

![Gif preview](./assets/preview.gif)

## Who?

For anyone

## What?

A script that reads standard string input and outputs elder futhark runes

> Note that because elder futhark doesn't have representative characters for `Q` or `Z`, those characters will pass through the script unaltered. As will special characters, numbers, and punctuation `123456789<>!@#$%^&*(),./\|~_`

## When?

ALWAYS, pipe everything into runes.sh

## Where?

In terminal emulators near you, as long as they support UTF-8

## Why?

Because its freakin awesome!

> CASTING SPELLS IN YOUR TERMINAL IS THE FUTURE
>
> --- Bryan 2020

# TODO

- [ ] allow for reading files into standard input and operating on each line of a file to translate a whole file as output. basically *cat* a file in and output would be the same as *cat* but only runes
- [ ] figure out how to retain functionality but remove bash substitution to be more POSIX compliant and portable
- [ ] figure out which terminal emulators support UTF-8 and which ones that dont and update README with that info in a table
