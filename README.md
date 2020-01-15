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

- [X] allow for reading files into standard input and operating on each line of a file to translate a whole file as output. basically *cat* a file in and output would be the same as *cat* but only runes
- [ ] files can be read by this script now, but using cat and piping contents into it still only returns the first line.
- [X] script is slow with operation on entire file.
	+ this was because i operated on line by line, at file size can just straight cat through the the sed pipes and it works fast
- [X] figure out how to retain functionality but remove bash substitution to be more POSIX compliant and portable
- [ ] figure out which terminal emulators support UTF-8 and which ones that dont and update README with that info in a table

## Collaboration

Got an idea that can help? open an issue ortake on a task under the *TODO* section.

## Testing

I managed to set up some unit tests for this script in the main directory of the repo you can run `./tests/test` and it will run several tests ive developed so far to see if functionality is working as it should.
