<h1 align="center">Terminal Dictionary</h1>
<p align="center">A simple CLI tool that scrapes https://www.thefreedictionary.com/ and returns definitions to words.</p>

# Usage

Usage: `Dictionary $query`

If you get this error it means that isn't listed as a word:
```
Traceback (most recent call last):
	4: from /sbin/nokogiri:23:in `<main>'
	3: from /sbin/nokogiri:23:in `load'
	2: from /usr/lib/ruby/gems/2.7.0/gems/nokogiri-1.11.1/bin/nokogiri:112:in `<top (required)>'
	1: from /usr/lib/ruby/gems/2.7.0/gems/nokogiri-1.11.1/bin/nokogiri:112:in `eval'
<main>:1:in `<top (required)>': undefined method `text' for nil:NilClass (NoMethodError)
```

# Requirements
[Ruby](https://www.ruby-lang.org/en/)

[Nokogiri](https://nokogiri.org/)

[Curl](https://curl.se/)

Gentoo:

`Sudo emerge dev-lang/ruby dev-ruby/nokogiri net-misc/curl`

Arch Linux:

`Sudo pacman -S ruby ruby-nokogiri curl`

Debian:

`Sudo apt install ruby ruby-nokogiri curl`

# Installation

```
$ git clone https://github.com/Yosuu69/Terminal-Dictionary
$ cd Terminal-Dictionary
$ sudo cp Dictionary /usr/bin
```

# AUR
Terminal Dictionary is available in the Arch User Repository as [terminal-dictionary-git](https://aur.archlinux.org/packages/terminal-dictionary-git/).

`$ yay -S terminal-dictionary-git `
