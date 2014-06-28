# Notes


A clean responsive theme for [Hexo](http://zespia.tw/hexo/).

- [Preview](http://notes.iissnan.com/)

## Installation

### Install

```
cd path-to-hexo 
git clone https://github.com/iissnan/hexo-theme-notes themes/notes
```

### Enable

Open `_config.yml` (locates in `path-to-hexo/_config.yml`), and set `theme` to `notes`.
The settings may look like:

```
theme:
    #landscape
    notes
```

### Update

```
cd themes/notes
git pull
```

### Configuration

```
menu:
  home: /
  archives: /archives

favicon: /favicon.ico

# Specify icon form apple devices
touch_icons:
  57x57: /images/apple-touch-icon-precomposed.png
  114x114: /images/apple-touch-icon-114x114-precomposed.png
  72x72: /images/apple-touch-icon-72x72-precomposed.png
  144x144: /images/apple-touch-icon-144x144-precomposed.png

# Specify a background image for content area
background_image: /images/gplaypattern.png

# Theme color schema
## Default: mild
## Available: mild | silence
theme_schema: silence


# Date / Time format
## Hexo uses Moment.js to parse and display date
## You can customize the date format as defined in
## http://momentjs.com/docs/#/displaying/format/
date_format: MMM D YYYY
time_format: H:mm:ss


# Code Highlight theme
## Available value: normal | night | night eighties | night blue | night bright
## https://github.com/chriskempson/tomorrow-theme
highlight_theme: night eighties

# Specify the date when the site was setup
since: 2013

version: 1.0
```