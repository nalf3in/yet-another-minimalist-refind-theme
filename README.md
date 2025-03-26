# yet-another-minimalist-refind-theme
My theme for rEFInd

![theme_screenshoot](screenshot.png)

## To install

- Git clone this repository in [EFI_PARTITION]/EFI/refind/themes

- Add this line to [EFI_PARTITION]/EFI/refind/refind.conf

```
include themes/yet-another-minimalist-refind-theme/theme.conf
```

Example file tree:
```
EFI
├── refind
│   ├── BOOT.CSV
│   ├── icons
│   │   ├── arrow_left.png
│   │   ├── ...
│   ├── keys
│   │   ├── altlinux.cer
│   │   ├── ...
│   ├── refind.conf
│   ├── refind.conf-sample
│   ├── refind_x64.efi
│   ├── themes
│   │   └── yet-another-minimalist-refind-theme
│   │       ├── background.png
│   │       ├── bg.png
│   │       ├── fonts
│   │       │   ├── liberation-mono-regular-12.png
│   │       │   ├── ...
│   │       ├── icons
│   │       │   ├── func_about.png
│   │       │   ├── ...
│   │       ├── LICENSE
│   │       ├── README.md
│   │       ├── screenshot.png
│   │       └── theme.conf
│   └── vars
│       └── PreviousBoot
└── tools
```

## Credits
This repo is a merge of a merge of:
- https://github.com/2KAbhishek/refind2k
- https://github.com/indgy/refind-bsd-black

Thanks to 2KAbhishek and indgy for the original icons and background