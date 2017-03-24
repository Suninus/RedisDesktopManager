How to build on OS X:

git clone --recursive https://github.com/palmtoy/RedisDesktopManager.git -b pt_0.8.0 rdm && cd ./rdm

1) Install XCode with xcode build tools

2) Build RDM dependencies: `cd ./src && ./configure`

3) Install crashreporter: `cd .. && mkdir -p ./bin/osx/release/ && cp ./crashreporter ./bin/osx/release/`

4) Install [Qt 5.7](https://www.qt.io/download-open-source/?hsCtaTracking=f977210e-de67-475f-a32b-65cec207fd03%7Cd62710cd-e1db-46aa-8d4d-2f1c1ffdacea&__hstc=152220518.7354ec057782982b1fdc9f518a6e97c3.1490251704982.1490251704982.1490321606981.2&__hssc=152220518.4.1490321606981)

5) Open `./src/rdm.pro` in Qt Creator

6) Select `Release` and run `Build`

======================================================================================

#[Redis Desktop Manager](http://redisdesktop.com "Redis Desktop Manager Offical Site")

[Install & Run](http://docs.redisdesktop.com/en/latest/install/) | 
[Quick Start](http://docs.redisdesktop.com/en/latest/quick-start/) |
[Development Guide](http://docs.redisdesktop.com/en/latest/development/) |
[Known issues](http://docs.redisdesktop.com/en/latest/known-issues/) |
:green_apple: [Bountysource](https://www.bountysource.com/teams/redisdesktopmanager)

[![Travis Build Status](https://travis-ci.org/uglide/RedisDesktopManager.svg?branch=0.8.0)](https://travis-ci.org/uglide/RedisDesktopManager) 
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/91mj2ge0lxjf693c/branch/0.8.0?svg=true)](https://ci.appveyor.com/project/uglide/redisdesktopmanager/branch/0.8.0)
[![Coverage Status](https://coveralls.io/repos/uglide/RedisDesktopManager/badge.svg?branch=0.8.0)](https://coveralls.io/r/uglide/RedisDesktopManager?branch=0.8.0)
[![Coverity Scan Build](https://scan.coverity.com/projects/3548/badge.svg)](https://scan.coverity.com/projects/3548)
[![Documentation Status](https://readthedocs.org/projects/redisdesktopmanager/badge/?version=latest)](http://docs.redisdesktop.com/en/latest/?badge=latest)
[![Stories in Progress](https://badge.waffle.io/uglide/redisdesktopmanager.svg?label=in progress&title=In Progress)](http://waffle.io/uglide/redisdesktopmanager)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/uglide/RedisDesktopManager)

Open source cross-platform Redis Desktop Manager based on Qt 5

![Redis Desktop Manager screenshoot](http://redisdesktop.com/static/img/features/all.png?v2)

**Officially Supported platforms** : Windows 7+, Mac OS X 10.11+, Ubuntu 14+, Fedora 22+ (build with automated script)

**Community Supported platforms**: [ArchLinux](https://aur.archlinux.org/packages/redis-desktop-manager/)

**Supported Redis versions** : 2.4, 2.6, 2.8, 3.0+

## Release Schedule
| Release | Original plan | Realized |
| ------- | ------------- | -------- |
| [0.8.7] (https://github.com/uglide/RedisDesktopManager/milestone/23?closed=1) | July 20, 2016 | [July 18, 2016](https://github.com/uglide/RedisDesktopManager/releases/tag/0.8.7) |
| [0.8.7-1] (https://github.com/uglide/RedisDesktopManager/milestone/23?closed=1) | - | [August 02, 2016](https://github.com/uglide/RedisDesktopManager/releases/tag/0.8.7-1) |
| [0.8.8-beta] (https://github.com/uglide/RedisDesktopManager/milestone/24) | August 17, 2016 | [August 17, 2016](https://github.com/uglide/RedisDesktopManager/releases/tag/0.8.8-beta) |
| [0.8.8] (https://github.com/uglide/RedisDesktopManager/milestone/24) | August 26, 2016 | |
| [0.9.0-alpha1] (https://github.com/uglide/RedisDesktopManager/milestone/8) | August 26, 2016 | |
| [0.9.0-alpha2] (https://github.com/uglide/RedisDesktopManager/milestone/8) | Sept 2, 2016 | |
| [0.9.0-alpha3] (https://github.com/uglide/RedisDesktopManager/milestone/8) | Sept 9, 2016 | |
| [0.9.0-beta] (https://github.com/uglide/RedisDesktopManager/milestone/8) | Sept 23, 2016 | |
| [0.9.0] (https://github.com/uglide/RedisDesktopManager/milestone/8) | Sept 30, 2016 | |
| [0.9.1-beta] (https://github.com/uglide/RedisDesktopManager/milestone/22) | Oct 21, 2016 | |
| [0.9.1] (https://github.com/uglide/RedisDesktopManager/milestone/22) | Oct 28, 2016 | |
