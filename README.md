# alien-mintty 

[![GitHub tag](https://img.shields.io/github/tag/eendroroy/alien-mintty.svg)](https://github.com/eendroroy/alien-mintty/tags)

[![Contributors](https://img.shields.io/github/contributors/eendroroy/alien-mintty.svg)](https://github.com/eendroroy/alien-mintty/graphs/contributors)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/eendroroy/alien-mintty/master.svg)](https://github.com/eendroroy/alien-mintty)
[![license](https://img.shields.io/github/license/eendroroy/alien-mintty.svg)](https://github.com/eendroroy/alien-mintty/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/eendroroy/alien-mintty.svg)](https://github.com/eendroroy/alien-mintty/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/eendroroy/alien-mintty.svg)](https://github.com/eendroroy/alien-mintty/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/eendroroy/alien-mintty.svg)](https://github.com/eendroroy/alien-mintty/pulls)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/eendroroy/alien-mintty.svg)](https://github.com/eendroroy/alien-mintty/pulls?q=is%3Apr+is%3Aclosed)

This is a port of [alien-minimal](https://github.com/eendroroy/alien-minimal) theme for windows (on cygwin).

**For details see the original [readme](https://github.com/eendroroy/alien-minimal/README.md)

## Installation

Add the following line to your .zshrc depending on your zsh plugin manager

##### [antigen](https://github.com/zsh-users/antigen):

    antigen theme eendroroy/alien-mintty alien-mintty

##### [zgen](https://github.com/tarjoilija/zgen):

    zgen load eendroroy/alien-mintty

##### [zplug](https://github.com/zplug/zplug):

    zplug "eendroroy/alien-mintty"

##### [oh-my-zsh: Overriding and Adding Themes](https://github.com/robbyrussell/oh-my-zsh/wiki/Customization#overriding-and-adding-themes)

##### Manually clonning

```bash
git clone https://github.com/eendroroy/alien-mintty.git
cd alien-mintty
git submodule update --init --recursive
```

Add the following line to your `~/.zshrc`

```bash
source ~/alien-win/alien-mintty.zsh
```

## Libraries Used

- ['256color'](https://github.com/chrissicool/zsh-256color) by **[@chrissicool](https://github.com/chrissicool)**
- ['promptlib-zsh'](https://github.com/eendroroy/promptlib-zsh) by **[@eendroroy](https://github.com/eendroroy)**

## Contributing

Bug reports and pull requests are welcome on GitHub at [alien-mintty](https://github.com/eendroroy/alien-mintty) repository.
This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Author

* **indrajit** - *Owner* - [eendroroy](https://github.com/eendroroy)

## License

The project is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
