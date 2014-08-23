# Project: codrops2bower-tooltipMenu

> A simple tooltip menu where the submenu will either appear above or below the main menu, depending on available space.

## Codrops: [TOOLTIP MENU](http://tympanus.net/codrops/2013/05/23/tooltip-menu/)

> Thanks!

## Table of contents

- [Usage](#usage)
- [Logs](#logs)
- [Authors](#authors)
- [License](#license)

## Usage

### Install

```
$ bower install kaitoborn/codrops2bower#tooltipMenu --save

Error: 'Tag/branch master does not exist'(iTerm with Fish), try:
$ bower install kaitoborn/codrops2bower'#tooltipMenu' --save
```

### Uninstall

```
$ bower uninstall codrops2bower-tooltipMenu --save
```

### HTML

```
ul#cbp-tm-menu.cbp-tm-menu
├── li
│   ├── a
│   └── ul.cbp-tm-submenu
│       ├──li
│       └──li
└── li
    ├── a
    └── .cbp-tm-submenu
```

### JS

    <script>
      new cbpTooltipMenu( document.getElementById( 'cbp-tm-menu' ) );
    </script>

## Demo

+ [Preview](dist/demo.md)
+ [Sorce](dist/demo.html)

## Logs

```
* 6010b95 Update Readme
* f91319f Fixed: Bower dependencies
* b668593 2bower success
* 8e67e88 import codrops src
* 1dd14a6 Fixed: Lisence copyright && Readme code block
* 59bc662 General Info
* 6b1ce83 Add General .gitignore
* b3c33fa Initial commit
```

## Authors

```
project  : codrops2bower
repo age : 34 hours
active   : 2 days
commits  : 8
authors  :
    8 kaitoborn               100.0%
```

## License

Code released under [the MIT license](LICENSE).