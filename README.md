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

### [Demo](dist/demo.html)

## Logs

+ 2bower @done (2014-08-22 17:30)
+ Simplify CSS @done (2014-08-22 17:30)
- Update Readme: Usage

## Authors

**Kaitoborn**

- <https://github.com/kaitoborn>

## License

Code released under [the MIT license](LICENSE).