# Fonts

Popular UI fonts or just some of my favorites. Stylesheet included for imports.

## UI Fonts
- SF Pro (Apple)
- SF Compact
- SF UI
- Roboto (Google)
- Inter
- Open Sans

## Creative Fonts
- Darkmode

## CSS 
Uses [jsdeliver](https://www.jsdelivr.com/) CDN so this repository can be used for web projects.

### Import
```css
@import url(https://cdn.jsdelivr.net/gh/Pariah187/Fonts/pariahfonts.css);
```
>[!Note]
>Copy to import fonts into your stylesheet.

### Quick-copy Stylesheet
```css
@font-face {
    font-family: "SF Pro Text";
    src:
        local("SF Pro Text"),
        url("https://cdn.jsdelivr.net/gh/Pariah187/Fonts/SF%20Pro/SF-Pro-Text-Regular.otf") format("opentype");
        font-weight: normal;
        font-style: normal;
}

@font-face {
    font-family: "Roboto";
    src:
        local("Roboto"),
        url("https://cdn.jsdelivr.net/gh/Pariah187/Fonts/Roboto/Roboto-Regular.ttf") format("truetype");
        font-weight: normal;
        font-style: normal;
}

@font-face {
    font-family: "Open Sans";
    src:
        local("Open Sans"),
        url("https://cdn.jsdelivr.net/gh/Pariah187/Fonts/Open%20Sans/OpenSans-Regular.ttf") format("truetype");
        font-weight: normal;
        font-style: normal;
}

@font-face {
    font-family: "Inter 18pt";
    src:
        local("Inter 18pt"),
        url("https://cdn.jsdelivr.net/gh/Pariah187/Fonts/Inter/Inter_18pt-Regular.ttf") format("truetype");
        font-weight: normal;
        font-style: normal;
}

@font-face {
    font-family: 'Darkmode';
    src: 
        local("Darkmode"),
        url('https://cdn.jsdelivr.net/gh/Pariah187/Fonts/darkmode-font/DarkmodeRegular-X35Oo.ttf') format('truetype');
    font-weight:normal;
    font-style:normal;
}
```
>[!Note]
>Copy to make changes to the code.
