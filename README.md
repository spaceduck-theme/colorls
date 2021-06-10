# Spaceduck for [colorls](https://github.com/athityakumar/colorls)

> A [spaceduck](https://github.com/pineapplegiant/spaceduck) theme for [colorls](https://github.com/athityakumar/colorls).

![Screenshot](./screenshot.png)

> (note: `ls` has been aliased to `colorls --sd --dark` above)

## Install

First, get the source code via one of the download methods, then proceed to activating.

### Getting Theme
#### Download using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone git@github.com:bigpick/spaceduck-colorls.git
```

#### Download manually

Download using the [GitHub .zip download](https://github.com/bigpick/spaceduck-colorls/archive/main.zip) option and unzip them.

### Activating theme

1. First you need to have installed [colorls](https://github.com/athityakumar/colorls#installation). Ensure you are running the latest release of colorls, as support for hex string values were added as of the [1.4.2 release](https://github.com/athityakumar/colorls/releases/tag/v1.4.2)


2. (Optionally) Make a backup of your current dark colorscheme:

    ```bash
    cp ~/.config/colorls/dark_colors.yaml ~/.config/colorls/dark_colors.yaml.backup
    ```
3. Copy the [`dark_colors.yaml`](https://github.com/bipick/spaceduck-colorls/blob/main/dark_colors.yaml) file to the dark color scheme location for colorls:

    ```bash
    cp dark_colors.yaml ~/.config/colorls/dark_colors.yaml
    ```
4. Use the `--dark` option when utilizing `colorls`:

    ```bash
    colorls --dark
    # Additionally: alias ls="colorls --dark"
    # or, perhaps more sanely: alias cls="colorls --dark"
    ```

---

## Samples

Some examples of a select set of `colorls` options (see the colorls repo for full optional flags).

### File Sizes

> Notice the sizing coloration based on small/medium/large size in the 5th column.

![file-size-screenshot](./sample/spaceduck_sizes.png)

### Tree
![tree-screenshot](./sample/spaceduck_tree.png)

### Git Status (addition, modified, deleted, unchanged, untracked)
> Shown: unchanged (green), modified (yellow), untracked (orange); Not-shown: addition (cyan), deletion (red)

![git-demo-screenshot](./sample/spaceduck_git.png)

## Team

This theme is maintained by the following person(s) in addition to being helped by a bunch of [awesome contributors](https://github.com/spaceduck-theme/colorls/graphs/contributors).

| [![bigpick](https://avatars1.githubusercontent.com/u/9803299?v=4&s=70)](https://github.com/bigpick) |
| --- |
| [bigpick](https://github.com/bigpick) |

## License

[MIT License](./LICENSE)
