# Transparent Replugged! - AKA TransparentCord

This is my original work so feel free to use / edit it however you want.</br></br>
Found something that isn't transparent that should be? Either fix it and [create a PR](https://github.com/JJ-VP/transparent-replugged/pulls), or [create an issue](https://github.com/JJ-VP/transparent-replugged/issues/new/choose) and let me know where to find the element.

## What does this theme do?

It simply makes as many elements as possible transparent. No layout changes, no fancy features, just transparency.

## Install

### Automatic:

[![Install in Replugged](https://img.shields.io/badge/-Install%20in%20Replugged-blue?style=for-the-badge&logo=none)](https://replugged.dev/install?identifier=dev.jj.transparent&source=store)

### Manual:

1. Download the latest
   [dev.jj.transparent.asar](https://github.com/JJ-VP/transparent-replugged/releases/latest/download/dev.jj.transparent.asar)
2. [Place the asar into the replugged themes folder](https://github.com/replugged-org/replugged/wiki/Installing-plugins-and-themes)
3. Load Missing Themes

### Development:

1. Clone this repo `git clone https://github.com/JJ-VP/transparent-replugged.git`
2. Install dependencies `pnpm i`
3. Build the theme using `pnpm run build` or `pnpm run bundle` *if you bundle you will have to manually move the theme from repo/bundle to your [themes folder](https://github.com/replugged-org/replugged/wiki/Installing-plugins-and-themes).*
4. Load Missing Themes

## Customize

1. Open `Settings` > `Replugged` > `Quick CSS`.
2. Add the following CSS:
```css
:root {
  --transparent-bg-dim-upper: 0.75;
  --transparent-bg-dim-lower: 0.75;
  --transparent-bg-image: url("https://wallpaperaccess.com/full/260168.jpg");
}
```
3. Change the values to your liking.

| Description                   | Variable name                | Valid values                     | Default value                                        |
| ----------------------------- | ---------------------------- | -------------------------------- | ---------------------------------------------------- |
| Background dim gradient upper | `--transparent-bg-dim-upper` | `0` (transparent) - `1` (opaque) | `0.75`                                               |
| Background dim gradient lower | `--transparent-bg-dim-lower` | `0` (transparent) - `1` (opaque) | `0.75`                                               |
| Background image              | `--transparent-bg-image`     | Image link wrapped in `url()`    | `url("https://wallpaperaccess.com/full/260168.jpg")` |

## Preview

![Preview1](https://i.imgur.com/Bcn5hQb.png)
![Preview2](https://i.imgur.com/s69hTmv.png)
