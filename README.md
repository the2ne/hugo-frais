# Hugo frais

**/!\ Please note that this is a Work In Progress theme**

A fresh and french theme for [Hugo](//gohugo.io/) which i'll use for my personal website (blog and portfolio): olivierfredon.com

Recipe for a good theme:
- **light**: minimum viable dependencies
- **responsive**: mobile-first is not an option
- **accessible**: a11y is quality
- **SVG**: ligt + responsive + accessibility = Epic win
- **consistent**: maintainability is king
- **customizable**: make it yours
- ...

## How to install

Inside the folder of your Hugo site run:

```sh
$ cd themes
$ git clone https://github.com/the2ne/hugo-frais
```

Then update your _config.toml_ file:

```toml
theme = "hugo-frais"
```

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Configuration

You can define some social network bullshit like:
- [author] **name** *str* : the author's website name;
- [author] **pseudo** *str* : the author's online pseudonym;
- [author] **twitter** *str* : Twitter account;
- [author] **github** *str* : GitHub account;
- [author] **linkedin** *str* : LinkedIn account;

_./config.toml example:_
```toml
[author]
    name = "Olivier Fredon"
    pseudo = "the2ne"
    twitter = "the2ne"
    github = "the2ne"
    linkedin = "the2ne"
```

You can add some features with extra partial templates (Do you enjoy Konami Code?.)

## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//github.com/the2ne/hugo-frais/issues) to let me know. Or make directly a [pull request](//github.com/the2ne/hugo-frais/pulls).


## License

This theme is released under the MIT license. For more information read the [License](//github.com/the2ne/hugo-frais/blob/master/LICENSE.md).


## Annotations

Thanks to:
- [Steve Francia](//github.com/spf13) for creating Hugo (and for the shortcodes) and the awesome community around the project.
