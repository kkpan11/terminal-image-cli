# terminal-image-cli

> Display images in the terminal

Works in any terminal that supports colors. Supports animated GIFs.

<img src="screenshot.png" width="1082">

*In iTerm, the image will be [displayed in full resolution](screenshot-iterm.jpg), since iTerm has [special image support](https://www.iterm2.com/documentation-images.html).*

## Install

```sh
npm install --global terminal-image-cli
```

## Usage

```
$ image --help

  Usage
    $ image <image>
    $ cat <image> | image

  Examples
    $ image unicorn.jpg
    $ cat unicorn.jpg | image
```

## Related

- [terminal-image](https://github.com/sindresorhus/terminal-image) - API for this package
- [terminal-link-cli](https://github.com/sindresorhus/terminal-link-cli) - Create clickable links in the terminal
