KivyMD
======

<img align="left" height="256" src="https://github.com/HeaTTheatR/KivyMD/blob/master/kivymd/images/kivy-logo-white-512.png"/>

KivyMD is a collection of Material Design compliant widgets for use with [Kivy](http://kivy.org), a framework for cross-platform, touch-enabled graphical applications.

The project's goal is to approximate Google's [Material Design spec](https://www.google.com/design/spec/material-design/introduction.html) as close as possible without sacrificing ease of use or application performance.

Currently we're in **alpha** status, so things are changing all the time and we cannot promise any kind of API stability. However it is safe to vendor now and make use of what's currently available.

Join the project! Just fork the project, branch out and submit a pull request when your patch is ready. If any changes are necessary, we'll guide you through the steps that need to be done via PR comments or access to your for may be requested to outright submit them.

If you wish to become a project developer (permission to create branches on the project without forking for easier collaboration), have at least one PR approved and ask for it. If you contribute regularly to the project the role may be offered to you without asking too.

Documentation
=============

Some very early documentation can be found at our project's website, other than that we recommend checking the [demos/kitchen_sink/main.py](https://github.com/HeaTTheatR/KivyMD/blob/master/demos/kitchen_sink/main.py) file for examples or [look here](https://github.com/HeaTTheatR/KivyMD/wiki/MDUserAnimationCard).

Support
=======
If you need assistance, you can ask for help on our mailing list:

* User Groups: [vk group](https://vk.com/kivy_development), [google group](https://groups.google.com/forum/#!categories/kivymd-users-support), [Discord Channel](https://discord.gg/TegSJDD)
* Email: kivydevelopment@gmail.com


Installation and use with Buildozer
===================================

#### Dependencies:
* Kivy version is not less than 1.10.1
* PIL
* Python 3 (Python 2 not supported)

#### How to install

To install KivyMD, clone the project and run the setup.py script. The following line works on Linux and Mac OS, other OSes not tested:

    sudo python ./setup.py install

Replace "python" with the Python interpreter you want to install KivyMD on (Python 3 is supported)


#### How to use with Buildozer

If you want to use KivyMD with buildozer, in your buildozer.spec's requirements line you should add the full git HTTPS address, like this example:

    requirements = kivy==master,git+https://github.com/HeaTTheatR/KivyMD.git

Running on Android
==================
Android 6.0 and higher [kitchen_sink-0.98.4-x86.apk](https://github.com/HeaTTheatR/KivyMD-data/tree/master/bin/python3) or [kitchen_sink-0.98.4-armeabi-v7a.apk](https://github.com/HeaTTheatR/KivyMD-data/tree/master/bin/python3/armeabi-v7a)

What's new in version 0.98.4:
============================
* Added functionality for viewing demo applications [Shop Window](https://www.youtube.com/watch?v=ZGd2Lvikki0), [Coffee Menu](https://www.youtube.com/watch?v=6U59VsRGRNE), [Fitness Club](https://www.youtube.com/watch?v=x7Tn5vu-5FY), [Registration Form](https://www.youtube.com/watch?v=h4ntfEkvpxU)
* Added new class [MDTextFieldRound](https://github.com/HeaTTheatR/KivyMD/wiki/MDTextFieldRound)
* [The source code of the demo applications](https://github.com/HeaTTheatR/KivyMD/tree/master/demos/kitchen_sink/demo_apps)

API Breaking changes:
=====================
* Renamed files, classes and variables:

| Old                                                  | New                                 |
|------------------------------------------------------|-------------------------------------|
| `kivymd.elevationbehavior`                           | `kivymd.elevation`                  |
| `kivymd.grid`                                        | `kivymd.imagelists`                 |
| `kivymd.date_picker`                                 | `kivymd.pickers`                    |
| `kivymd.time_picker`                                 | `kivymd.pickers`                    |
| `kivymd.time_picker`                                 | `kivymd.pickers`                    |
| `kivymd.card`                                        | `kivymd.cards`                      |
| `kivymd.menu`                                        | `kivymd.menus`                      |
| `kivymd.snackbar`                                    | `kivymd.snackbars`                  |
| `Toolbar` (from `kivymd.toolbar`)                    | `MDToolbar` (from `kivymd.toolbar`) |

* Changed font styles:

| Old      | New       |
|----------|-----------|
| Icon     | Icon      |
| -        | Overline  |
| Caption  | Caption   |
| Button   | Button    |
| Body2    | Body2     |
| Body1    | Body1     |
| -        | Subtitle2 |
| Subhead  | Subtitle1 |
| Title    | H6        |
| Headline | H5        |
| Display1 | H4        |
| Display2 | H3        |
| Display3 | H2        |
| Display4 | H1        |

* Colors `BlueGrey` and `Grey` renamed to `BlueGray` and `Gray` (for better fit MD spec)


Video previous
==============
<p align="center">
    <a href="https://youtu.be/Jbi20FGZ8KM"><img src="https://github.com/HeaTTheatR/KivyMD-data/blob/master/gallery/prevideo.png"></a>
</p>

Image previous
==============
<p align="center">
    <img src="https://github.com/HeaTTheatR/KivyMD-data/blob/master/gallery/previous.png">
</p>

Sister project:
==============

[Creator Kivy Project](https://github.com/HeaTTheatR/CreatorKivyProject) - Wizard for creating a new project for applications written using the Kivy framework

License
=======

MIT, same as Kivy.

Roboto font is licensed and distributed under the terms of the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

[Material Design Iconic Font](https://github.com/zavoloklom/material-design-iconic-font) by [Sergey Kupletsky](https://twitter.com/zavoloklom) covered by the licenses described at https://zavoloklom.github.io/material-design-iconic-font/license.html.

Icons by the materialdesignicons.com community covered by SIL OFL 1.1
