<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://music.youtube.com">Youtube Music</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/youtubemusic/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/youtubemusic?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/youtubemusic/issues"><img src="https://img.shields.io/github/issues/catppuccin/youtubemusic?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/youtubemusic/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/youtubemusic?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="assets/res.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage
### [Youtube Music Desktop App (th-ch)](https://github.com/th-ch/youtube-music)

1. Download a CSS file with your desired flavor from `src` e.g. `mocha.css` (NOT `youtubemusic.user.css`).
2. Open the app, click `Options > Visual Tweaks > Theme > Import custom CSS file`, and choose the downloaded CSS file.

### [Youtube Music Desktop App (ytmdesktop)](https://github.com/ytmdesktop/ytmdesktop)

1. Download a CSS file with your desired flavor from `src` e.g. `mocha.css` (NOT `youtubemusic.user.css`).
2. Navigate to Settings > Appearance and enable Custom CSS
3. In Custom CSS file path, choose the CSS file you created.

### Changing the accent

```css
/* find the --ctp-accent variable in the file and change it to your desired color in hex -
   or use one of the predefined colors with var(--ctp-'color') - e.g. --ctp-accent: var(--ctp-maroon) !important; */
html:not(.style-scope) {
/*...*/
    --ctp-accent: #f5e0dc !important; /* example */
/*...*/
}
```

### [Stylus](https://github.com/openstyles/stylus)

1. Install Stylus extension for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/)
2. Then install with Stylus (click on the link):
  - [🎧 Catppuccin for Youtube Music](https://github.com/catppuccin/youtubemusic/raw/main/src/youtubemusic.user.css)
3. Choose your flavor and accent color in the Configure window in Stylus Options

### Overriding Colors

If you wish to change the default colors to something different, like an OLEDpuccin variant, replace them in the CSS file within `html:not(.style-scope)`:

```css
html:not(.style-scope) {
/*...*/
    --ctp-base: #020202 !important;
    --ctp-crust: #010101 !important;
    --ctp-mantle: #000 !important;
/*...*/
}
/* OLEDpuccin */
```

All of the colors available for change are in the beginning of the CSS file.

## 💝 Thanks to

### Current maintainer

- [kerichdev](https://github.com/kerichdev)

### Contributions

- [Anubis](https://github.com/anubisnekhet)
- [OceanicSquirrel](https://github.com/OceanicSquirrel)
- [Sofiedotcafe](https://github.com/sofiedotcafe)

### Previous maintainer

- [rubyowo](https://github.com/rubyowo)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
