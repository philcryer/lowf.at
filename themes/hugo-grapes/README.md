# hugo-grapes
A minimalistic text based theme for Hugo inspired by [hugo-bingo](https://github.com/gundamew/hugo-bingo) theme.

![screenshot](https://github.com/shankar/hugo-grapes/blob/master/images/screenshot.png)

## Usage

### Instructions

1: Install Hugo.

2: Create a new site.

```
hugo new site mynewsite
```

3: Change to themes directory.

```
cd mynewsite/themes
```

4: Clone the repo

```
git clone git@github.com:shankar/hugo-grapes.git
```

5: Copy the `content/`, `static/`, and `config.toml` from the `exampleSite` directory into the `mynewsite` directory. The existing `content/`, `static/`, and `config.toml` files will be over-written.
```
cp -r hugo-grapes/exampleSite/* /path/to/mynewsite
```

6: Run `hugo server` within `mynewsite` and enjoy and customize to your hearts content!

### New Posts

To make new posts, simply use the command:

```
hugo new post/awesome-post.md
```

## Customize

### Change Avatar

1: The Avatar picture is to be placed in the `static` folder under your hugo site. (default picture is located in `static/img` folder)

2: Edit the config.toml file and edit the value of the `avatar` key under `params` to let hugo know its location.
```
[params]
avatar = "path/to/avatar"
# Path is relative to static folder.
# Example: "img/grapes.svg" for grapes.svg file located in static/img folder
```

## License

This theme is released under the MIT License. See [LICENSE](https://github.com/shankar/hugo-grapes/blob/master/LICENSE).
