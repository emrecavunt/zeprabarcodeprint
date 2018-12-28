# zepra barcode print with WPF 
ZPL BARCODE PRINTER / ZEBRA OVER USB



 ### TODOS 
 
- Add referance below .dll from `zeprabarcodeprint/lib` file 

```sh
SdkApi.core
SdkApi.desktop,
SdkApi.desktop.usb
newtonsoft.json.dll
```

- Install Zebra .NET SDK via nuget. Behave your self and ensure you are using .Net Framework 4.7.2

```sh
Install-Package Zebra.Printer.SDK -Version 2.15.2634
```



### Resources 
| Source | README |
| ------ | ------ |
| ZPL MANUAL | [support.zebra.com/cpws/docs/zpl/zpl_manual.pdf][PlDb] |
| ZPL ONLINE VIEWER | [labelary.com/viewer.html][PlGh] |

[PlDb]: <https://support.zebra.com/cpws/docs/zpl/zpl_manual.pdf>
[PlGh]: <http://labelary.com/viewer.html>
