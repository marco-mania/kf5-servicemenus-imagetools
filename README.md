# KDE service menus for image file processing

KDE service menus for image file processing.

* Special functions for JPEG and PNG files

Originally derived from [KDE 5 Service Menu ReImage v2.5](https://www.egregorion.net/),
Copyright (C) 2018-2019 Giuseppe Benigno <giuseppe.benigno@gmail.com>, GPL-3.0+

## Prerequisites

* [KDE](https://www.kde.org/)
* [ImageMagick](https://imagemagick.org/index.php)
* [ExifTool](https://exiftool.org/)
* [OptiPNG](http://optipng.sourceforge.net/)

## Installation

    sudo cp ServiceMenus/* /usr/share/kservices5/ServiceMenus/
    sudo cp bin/imagetools-kdialog /usr/local/bin/

## Uninstall

    sudo rm /usr/share/kservices5/ServiceMenus/image-tools*.desktop
    sudo rm /usr/local/bin/imagetools-kdialog

## Contributing

Pull requests are welcome. For major changes, please open an issue first to
discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GPL-3.0+](https://www.gnu.org/licenses/gpl-3.0.html)
