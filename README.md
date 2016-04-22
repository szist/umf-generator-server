UMF generator server
=======================

In case you end up using our source code in research, please add a reference to one of our relevant publications:

Binary UMF markers:

I. Szentandrasi, M. Zacharias, J. Havel, A. Herout, M. Dubska, and R. Kajan. Uniform Marker
Fields: Camera localization by orientable De Bruijn tori. In ISMAR 2012, 2012

Grayscale UMF/Colorful:

Adam Herout, Istvan Szentandrasi, Michal Zacharias, Marketa Dubska, and Rudolf Kajan.
Five shades of grey for fast and reliable camera pose estimation. In Proceedings of CVPR,
pages 1384�1390. IEEE Computer Society, 2013

Alexander Paldy and Adam Herout. Advanced markers for augmented reality. Proceedings
of CESCG 2013: The 17th Central European Seminar on Computer Graphics, 2013.

Honeycomb markers:

Zs. Horvath, A. Herout, I. Szentandrasi, and M. Zacharias. Design and detection of local
geometric features for deformable marker fields. In Proceedings of 29th Spring conference
on Computer Graphics, pages 85�92. Comenius University in Bratislava, 2013.

Installation
-----------------------------------------

Requirements (LAMP/LEMP):

* php > 5.4
* mysql
* nginx/apache

No rewrite is needed, just point the server to this directory.

### Installation

1. import mysql database: db/pmgen.sql
2. create and update the configuration file:
    * ```$ cp inc\server-settings.php.example inc\server-settings.php```
    * update configuration file based on your needs
    

Related Projects
----------------------------------------

* [UMF generator client](https://github.com/szist/umf-generator-client)
* [UMF detector](https://github.com/szist/umf-detector)
* [UMF unity plugin] (https://github.com/szist/umf-unity)