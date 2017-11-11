# QT For Beginners

QT Learning Started on : 07/11/2017

## Installing QT

**need to test the installation again**

## Basics

* pronounced as cute not cu-tee
* cross-platform application framework (that is usually used as a graphical toolkit ,but also helpful in creating CLI applications) used for developing application software that can be run on various s/w and h/w platforms with little or no change in underlying codebase, while still being a native application with native capabilities and speed.
* Developed by both QtCompany and Qt Project ( under open source governance )
* Hence it is available both as proprietary and under opensource

* It runs on 
    * three major desktop OSes
    * mobile OSes like Symbian,Nokia Belle,etc
    * on embedded devices
    * Ports for Android (Necessitas) and iOS are also in development.
* It has an impressive collection of modules including,
    * QtCore
        * base library
        * provides containers,thread mgmt,event mgmt etc
    * QtGui and QtWidgets
        * Gui Toolkit for Desktop
        * Provides a lot of graphical components to design applications
    * QtNetwork
        * Deals with network communications
    * QtWebkit
        * webkit engine
        * enable the use of web pages and web apps in a Qt application
    * QtSQL
        * full featured SQL RDBM abstraction layer extensible with own drivers
        * support of ODBC,Sqlite,MySql and PostgreSql is available out of the box
    * QtXML
        * support for simple XML parsing and Dom
    * QtXmlPatterns
        * support for XSLT,XPath,XQuery and Schema validation
## Programming Language Bindings

* Qt uses standared c++ with extensions including signals and slots that simplify handling of events.
* Qt supports many compilers including GCC C++ compiler and Visual Studio suite
* Qt also provides Qt Quick 
    *( another free s/w application framework developed with in the Qt frmaework)
    * **needs better description**
    * it includes a declarative scripting language called `QML` that allows javascript to provide the logic.
    * it will enhance rapid app development for mobile devices

* Qt can be used in several other pgming languages via language bindings.

## installing QtSDK

    * need to download the SDK for Qt , that contains the libraries and IDE
    * it may include cross compilers for different platforms eg for desktops,mobiles
    * download the online installer and make it executable and run it
    * create an account at qt company 
    * from the components listing page,select
        * QMake Documentation
        * Qt Documentation
        * Qt 4.8.1 (Desktop)
        * Qt Creator
        * Qt Examples, Qt Linguist (optional)

    * On linux , there are distributions
        * apt-get install qt5-default,qtcreator
        * need to check the dependencies



## QtCreator
    * IDE For C++
    * suited for coding Qt Applications
    * also provides doc broser and designer for GUI
    * fastest IDE 

## Lets Get Started
    * File >> New file or project > Other Projects >> Empty Qt project
    * select project name and location
    * .pro -- project file used by `qmake` to generate makefiles 
    





