# Project: codrops2bower-tooltipMenu

> A simple tooltip menu where the submenu will either appear above or below the main menu, depending on available space.

## Codrops: [TOOLTIP MENU](http://tympanus.net/codrops/2013/05/23/tooltip-menu/)

> Thanks!

## Table of contents

- [Usage](#usage)
- [Authors](#authors)
- [License](#license)

## Usage

### Install

```
$ bower install kaitoborn/codrops2bower#tooltipMenu --save
```

```
Or, try(Error: 'Tag/branch master does not exist'):
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

+ [Preview](http://htmlpreview.github.io/?https://github.com/kaitoborn/codrops2bower/blob/tooltipMenu/dist/demo.html)
+ [Sorce](dist/demo.html)

## Authors

```
project  : codrops2bower
repo age : 35 hours
active   : 2 days
commits  : 10
authors  :
   10 kaitoborn               100.0%
```

## License

Code released under [the MIT license](LICENSE).