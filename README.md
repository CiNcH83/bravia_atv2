# BRAVIA Android TV Knowledge Base

Welcome to the BRAVIA Android TV Knowledge Base. The main purposes of this repository are to document known issues and to give advice on how to squeeze the maximum out of BRAVIAs based on Sony’s second generation Android TV platform (ATV2) which has been introduced in mid-2016, featuring a MediaTek MT5891 (MT5596) SoC.

Here is a list of BRAVIAs based on ATV2:

* ZD9 / Z9D (2016)
* XD70 / X700D (2016)
* XD75 / X750D (2016)
* XD80 / X800D (2016)
* XD83 / X830D (2016)
* A1 / A1E (2017)
* XE80 / X800E (2017)
* XE83 / X830E (2017)
* XE85 / X850E (2017)
* XE90 / X900E (2017)
* XE93 / X930E (2017)
* XE94 / X940E (2017)
* XF75 / X750F (2018)
* XF80 / X800F (2018)
* XF83 / X830F (2018)
* XF85 / X850F (2018)
* XF87 / X870F (2018)
* XF90 / X900F (2018/2019)
* AF8 / A8F (2018)
* XG80 / X800G (2019)
* XG81 / X810G (2019)
* XG83 / X830G (2019)
* XG90 / X900G (2019)
* AG8 / A8G (2019)

## Issues

Central to this knowledge base is an issue tracker, detailing major and minor flaws of the Sony/MediaTek Android TV integration. One can filter for problem categories via labels (e.g. USB, Standby,...) or for a specific firmware version via milestones, e.g.:

* [Issues resolved with FW V6.7140](https://github.com/CiNcH83/bravia_atv2/issues?q=is%3Aissue+milestone%3A%22FW+V6.7140%22+is%3Aclosed)
* [New issues introduced with Pie](https://github.com/CiNcH83/bravia_atv2/issues?q=is%3Aissue+is%3Aopen+label%3APie)

Feel free to leave comments in case you have further information. Please also note that the issue tracker is no support forum though. It is important to keep the place clean so that it can act as a reference. Feel free to use the [Discussions](https://github.com/CiNcH83/bravia_atv2/discussions) area in order to leave comments or report reproducible issues.

## Debloat

Sony has a track record of cluttering their BRAVIAs with all kinds of bloat- and spyware, occupying hundreds of megabytes RAM, inevitably leading to frequent background app killing due to shortage, also resulting in glitches of various kinds. 

When looking at the installed packages and running processes, one might find deprecated technologies (BIVL, DIAL, Miracast/WiFi Direct,...), most of which are poorly implemented anyway, platforms in the platform (Sony Select, BRAVIA B2B/Hotelmode, Opera TV Store), promotional stuff (Gameloft etc.) and even a spy trojan in the form of Samba TV.

In order to "debloat" the BRAVIA operating system, an ADB (Android Debug Bridge) script will soon be revealed, listing packages that can safely be removed, leading to an Android TV operating system that is more responsive and stable. Please do not execute it unless you know exactly what you are doing as the script might remove functionality you are actively using.

### ADB Howto

TBD
