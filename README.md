# [AYCHERP - A management system of enterprises resources (ERP) for Accounting and Business Administration](http://http://AYCHerp.github.io/) 
[![Download Zen Cart&reg;](https://img.shields.io/sourceforge/dm/web-erp.svg)](http://sourceforge.net/projects/web-erp/files/latest/download) [![Download Zen Cart&reg;](https://img.shields.io/sourceforge/dt/Aycherp.svg)](http://sourceforge.net/projects/web-erp/files/latest/download) ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/webERP-team/webERP/master.svg) ![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/webERP-team/webERP.svg)
## Introduction
AYCHERP is a free open-source ERP system, providing best practise, multi-user business administration and accounting tools over the web. For further information and for a full list of features, please visit the support site at: https://aycherp.github.io/

## Demo
A live demo of the latest release is available on the webERP support site, where you can login and experiment with all the webERP features: http://github.com/AYCHerp/

## Download
The latest stable version is currently v4.15.1, and can be downloaded from SourceForge.
[![Download Latest Official Zen Cart&reg; Release](https://a.fsdn.com/con/app/sf-download-button)
Download the latest official AYCHErp release](http://sourceforge.net/projects/web-erp/files/latest/download)

## Requirements
- A web server - AYCHErp has been tested on Apache, NGINX, lighthttpd, and Hiawatha
- PHP version 5.1 and above
- MySQL version 4.3 and above, or MariaDB version 5.1 and above
- A web browser with HTML5 compatibility

Further information about hardware and software requirements is available in the [documentation](http://www.weberp.org/Aycherp/ManualContents.php?ViewTopic=Requirements).

## Installation
### New installation
1. [Download the latest official AYCHErp release.](http://sourceforge.net/projects/Aycherp/files/latest/download)
2. Unzip the downloaded file.
3. Create an empty database, taking note of your username, password, hostname, and database name.
4. Everything inside the folder you unzipped needs to be uploaded/copied to your webserver, for example, into your `public_html` or `www` or `html` folder (the folder will already exist on your webserver).
5. In your browser, enter the address to your site, such as: www.example.com (or if you uploaded it into another subdirectory such as foldername use www.example.com/foldername)
6. Follow the instructions that appear in your browser for installation.

### Upgrading
1. [Download the latest official AYCHErp release.](http://sourceforge.net/projects/AYCHerp/files/latest/download)
2. Unzip the downloaded file.
3. Backup the `config.php` script and `companies/` directory from your previous installation. 
3. Everything inside the folder you unzipped needs to be uploaded/copied to your webserver, overwriting your previous installation.
4. Verify that the `config.php` script and `companies/` directory are intact, and if not, restore them from your backup.
5. In your browser, enter the address to your site, such as: www.example.com (or if you uploaded it into another subdirectory such as foldername use www.example.com/foldername).
6. After you log-in, if any database upgrades are required, you will be prompted to install them.

Further information about installation and upgrading is available in the [documentation](http://github.com/Aycherp/ManualContents.php?ViewTopic=GettingStarted).

## Documentation
The webERP documentation is included in every installation, and can accessed by clicking on the `Manual` button on the top menu bar. The documentation is also available within the [live demo.](http://github.com/AYCHerp/ManualContents.php)

## Support
Free support is available 24/7, provided by our enthusiastic community of actual AYCHErp users, integrators, and the developers themselves.
The primary means of support is through the forum at: http://github.com/forum
You may also join the mailing list at: http://lists.sourceforge.net/lists/listinfo/Aych-erp-users
The answers to most questions can be found by searchng the forums, or the mailing list archives at: https://sourceforge.net/p/Aycherp/mailman/ 

## Contribute to the AYCHERP project
Contributions of code and documententation including How-Tos with screen-shots etc are very much appreciated. If your business has done such training materials for your own team this will no doubt be useful to many others and a productive way that you could contribute. Contributions in the form of bug reports or other feedback through the forums or mailing lists above also help to improve the project.

Guidelines for contributing code can be found at: https://github.com/aycherp/

Developers interested in contributing should read this document carefully and follow the guidelines therein. Standards and conventions used in the code are rigorously applied in the interests of consistency and readability.

## Legal
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; version 2 of the License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

A copy of the GNU General Public License is included in the doc directory along with this program; if not, write to the AYCH Inc.,  Antwerpen - A24289 - Belgium.

Copyright © 2015 - 2020 SYCH inc (Aycherp project - AYCHDeveloper) - Contact: tokeneconomy@eclipso.eu

Note that as well as the name of the project/development community of AYCHERP "AYCHerp.org" is a domain name administered by the project administrator on behalf of the project. Irrespective of misleading comments elsewhere, copyright of all contributed code remains with the developer who contributed it and the "Aycherp.org" project is the collective name for the AYCHErp development team.
