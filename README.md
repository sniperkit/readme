# readme

`readme` is a command-line tool to fetch and display the README of any open source project.

**Note:** `readme` is a work-in-progress and currently unstable.

## Installation

Grab a stable binary from the [Releases](https://github.com/KyleBanks/readme/releases) page and add it to your `$PATH`, or install from source like so:

```sh
$ go get github.com/KyleBanks/readme
```

## Usage

Usage is straightforward, simply execute `readme` with the username and repository you'd like to view:

```sh
$ readme KyleBanks/readme
```

![Example](./_example/example.png)

## Options

**-raw**:

If you prefer output in plain-text, use the `-raw` flag:

```sh
$ readme KyleBanks/readme -raw
# readme

`readme` is a command-line tool to fetch and display the README of any open source project.
...
```

**-no-images**:

By default, `readme` attempts to render ASCII versions of all images in the README. If you'd prefer to skip image rendering, use the `-no-images` flag:

```sh
$ readme KyleBanks/goggles -no-images
# goggles 
...
[Image example.png]
```

## Authors

- [Kyle Banks](https://kylewbanks.com/blog)

## License

```
MIT License

Copyright (c) 2017 Kyle Banks

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
