This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving Console and TCC/LE tool bundles.

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [a Console bundle](#download).
* Extract archive in `neard\tools\console\`. Directory structure example :

```
[-] neard
 | [-] tools
 |  | [-] console 
 |  |  | [-] console2.00.148
 |  |     | neard.conf
 |  |  | [-] consolep1
 |  |     | neard.conf
```

* Edit the `neard.conf` file and replace the key `consoleVersion` with the correct version.
* Start Neard.

## Download

![](https://raw.github.com/crazy-max/neard-tool-console/master/img/star-20160403.png) : Default bundle on Neard.

|                      | Console pack releases | Console and TCC/LE release date | Neard release | Neard compatibility | Download |
| ---------------------|:---------------------:|:-------------------------------:|:-------------:|:-------------------:|:--------:|
| **Console 2.00.148** | N/A | 2011/10/03 | [r1](https://github.com/crazy-max/neard-tool-console/releases/tag/r1) | <= 1.0.16 | [neard-console-2.00.148-r1.zip](https://github.com/crazy-max/neard-tool-console/releases/download/r3/neard-console-2.00.148-r1.zip) |
| **Console p1**       | Console 2.00.148<br />TCC/LE 14.0.0.6 | 2011/10/03<br />2015/09/01 | [r3](https://github.com/crazy-max/neard-tool-console/releases/tag/r3) | >= 1.0.19 | [neard-console-p1-r3.zip](https://github.com/crazy-max/neard-tool-console/releases/download/r3/neard-console-p1-r3.zip) |
| **Console p2** ![](https://raw.github.com/crazy-max/neard-tool-console/master/img/star-20160403.png) | Console 2.00.148<br />TCC/LE 14.0.0.9 | 2011/10/03<br />2016/02/05 | [r3](https://github.com/crazy-max/neard-tool-console/releases/tag/r3) | >= 1.0.19 | [neard-console-p2-r3.zip](https://github.com/crazy-max/neard-tool-console/releases/download/r3/neard-console-p2-r3.zip) |

## Sources

* http://sourceforge.net/projects/console/files/console-devel/2.00/
* https://jpsoft.com/all-downloads/downloads.html

## Contribute

If you want to contribute to this bundle and create new bundles, you have to download [neard-dev](https://github.com/crazy-max/neard-dev) in the parent folder of the bundle.
Directory structure example :

```
[-] neard-dev
 | [-] build
 |  |  | build-commons.xml 
[-] neard-tool-console
 |  | build.xml
```

To create a new bundle :
* Do not forget to increment the `build.release` in the `build.properties` file.
* If you want you can change the `build.path` (default `C:\neard-build`).
* Open a command prompt in your bundle folder and call the Ant target `release` : `ant release`.
* Upload your release on a file hosting system like [Sendspace](https://www.sendspace.com/).
* Create an [issue on Neard repository](https://github.com/crazy-max/neard/issues) to integrate your release.

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.
