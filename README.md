<h1 align=center>
 <img align=center width="100%" src="https://www.codenameone.com/wp-content/uploads/2021/08/CN1-Banner-Dark-Blue.jpg" />
</h1>

![GitHub repo size](https://img.shields.io/github/repo-size/codenameone/CodenameOne?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/codenameone/CodenameOne?color=orange&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/codenameone/CodenameOne?color=success&style=flat-square)
![GitHub license](https://img.shields.io/badge/license-GPL%20%2B%20CE-FFFF00?style=flat-square)
[![Hacktoberfest](https://img.shields.io/badge/hacktoberfest-friendly-blueviolet?style=flat-square)](https://github.com/codenameone/CodenameOne/labels/Hacktoberfest)
[![GitHub Stars](https://img.shields.io/github/stars/codenameone/CodenameOne?label=GitHub%20stars&style=social)](https://github.com/codenameone/CodenameOne/stargazers/)

## Codename One - Cross Platform Native Apps with Java or Kotlin

[Codename One](https://www.codenameone.com/) is a mobile first cross platform environment for Java and [Kotlin](https://www.codenameone.com/blog/kotlin-support-public-beta.html) developers. It can compile Java bytecode to native OS executables (iOS, Android, UWP etc.).
It's a complete mobile platform featuring virtual machines, simulator, design tools (visual theme/builder/css), IDE integrations, ports to multiple OS's and much more. It provides full access to the underlying native OS code (e.g. Objective-C, C#, Dalvik/ART) through a portable abstraction which enables 100% code reuse.


<!-- [![Build Status](https://travis-ci.org/codenameone/CodenameOne.svg?branch=master)](https://travis-ci.org/codenameone/CodenameOne)
![GitHub language count](https://img.shields.io/github/languages/codenameone/CodenameOne?style=plastic)

<p>
<a href="https://twitter.com/CodenameOne"><img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" height=25></a> 
<a href="https://medium.com/CodenameOne"><img src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" height=25></a> 
<a href="https://dev.to/codenameone"><img src="https://img.shields.io/badge/DEV.TO-%230A0A0A.svg?&style=for-the-badge&logo=dev-dot-to&logoColor=white" height=25></a> -->

#### 🌟 &nbsp; Codename One is the only platform that..

- Has Write Once Run Anywhere support with no special hardware requirements and 100% code reuse
- Compiles Java or Kotlin into native code for iOS, UWP (Universal Windows Platform), Android and even JavaScript (with seamless PWA and Thread support)
- Is Open Source and Free with an enterprise grade commercial offering
- Is Easy to use with 100% portable Drag and Drop GUI builder
- Has Full access to underlying native OS capabilities using the native OS programming language (e.g. Objective-C) without compromising portability
- Has full control over every pixel on the screen! Just override paint and draw or use a glass pane to draw anywhere...
- Lets you use native widgets (views) and mix them with Codename One components within the same hierarchy (heavyweight/lightweight mixing)
- Supports seamless Continuous Integration out of the box

<br>

#### ✨ &nbsp; Here are some concrete benefits you can get with Codename One:

<br>

<img align="right" src="https://www.codenameone.com/img/github/content/runs-instantly.png" height="200">

### Codename One's Simulator Runs Instantly

Unlike emulators which you can see in Android etc. Codename One uses a simulator. This means it starts up fast even when debugging. You can enjoy IDE features such as live code reload to modify code in runtime etc.

This means faster debugging cycle and faster development process!

<br>

<img align="left" src="https://www.codenameone.com/img/github/content/large-selection-skins.png" height="200">

### Large Selection of Device Skins

Choose from a large selection of device “skins” to see how your app will look on particular devices. The skin takes into account factors such as resolution and
device density to provide a pixel-perfect presentation of your app, as it would appear on the real device.
Switching between device skins is nearly instant.

You can edit and contribute skins in their own open source project [here](https://github.com/codenameone/codenameone-skins).

<br>

<img align="right" src="https://www.codenameone.com/img/github/content/interactive-console.png" height="200">

### Interactive Console

Interact with your application’s APIs at runtime using the interactive Groovy Console. Inspect the application state or experiment with changes all while the app is running. 

This lets you investigate issues and experiment without even the small overhead of recompiling.

<br>

<img align="left" src="https://www.codenameone.com/img/github/content/live-reload.png" height="200">

### Live Reload

The Simulator let’s you take advantage of the "Reload Changed Classes" feature in IntelliJ (named "Apply Code Changes" in NetBeans) so that changes you make in your Java source code will be applied immediately to your already-running app in the simulator.

Note that this is often superior to the interactive console but there are limitations such as the ability to add methods/change structure of the code. These limits don't apply to the interactive console!

<br>

<img align="right" src="https://www.codenameone.com/img/github/content/css-live-update.png" height="200">

### CSS Live Update

When you make changes to your app’s CSS stylesheet, the changes are reflected instantly in the simulator. This includes changing your theme, images, fonts etc. All changes are instantly refreshed on save, no need to reload/refresh or anything of the sort!

This makes the process of styling an application remarkably easy and fast.

<br>

<img align="left" src="https://www.codenameone.com/img/github/content/component-inspector.png" height="200">

### Component Inspector

Use the powerful component inspector to browse the UI component hierarchy in your app. 
This tool makes it easy to find out where that extra padding is coming from or why something just isn’t lining up the way you’d like. You can also change the UIID (selector) of a component in runtime to see how it impacts the UI and see which component in the hierarchy maps to an element in the component tree (DOM equivalent).

<br>

<img align="right" src="https://www.codenameone.com/img/github/content/network-monitor.png" height="200">

### Network Monitor

See all of the network connections that your app makes using the Network Monitor. This valuable tool comes in handy when you’re trying to figure out why an HTTP request isn’t working for you. Check the headers and bodies of both the request and the response. You can even throttle the network to simulate a slow network connection.

<br>

<img align="left" src="https://www.codenameone.com/img/github/content/record-ui-unit-tests.png" height="200">

### Record UI Unit Tests

Use the Test Recorder tool to record unit tests for your app. Once you start recording, it will save your interactions into a unit test that can be played back later to verify that behaviour remains correct.

You can then connect the recorded tests to your CI process including automated on device testing.

<br>

## How Does it Work?

[Codename One](https://www.codenameone.com/) is a mature open source project with roots dating back to Sun Microsystems (2006) where one of its core underlying components was developed and open sourced. You can learn about its history and how it works in [this video](https://www.youtube.com/watch?v=MrwbpdMALig).

Codename One apps perform like native apps, because they are real native apps.

They are statically compiled into native binaries using the target platform’s official build tools. 

On platforms that do not support Java natively, such as iOS, the app’s JVM bytecode is first transpiled into a form that the native build tools will accept. On iOS, the app’s JVM bytecode is transformed into C source code, in a real xcode project. On Android, since Java is supported natively, no such transformation is necessary. The app jar is bundled directly into an Android studio gradle project, which can be built directly using the Android SDK build tools.

#### The figure below shows the build process for each supported platform:

<a href="https://www.codenameone.com/img/github/codename-one-architecture.jpg" target="_blank"><img width="70%" src="https://www.codenameone.com/img/github/codename-one-architecture.jpg"></a>

You can click the image to enlarge or view a PDF version [here](https://www.codenameone.com/img/github/architecture.pdf).


## Quick Start

TIP: We are currently transitioning to Maven, and have created a new, simpler method for creating projects.  Check out https://start.codenameone.com to get started now.

There is a lot to know about Codename One, this 3 minute video gives a very concise high level view. Notice there are similar videos for Eclipse, IntelliJ/IDEA and Netbeans [here](https://www.codenameone.com/download.html):

<div>
  <a href="https://www.youtube.com/watch?v=rl6z7DD2-vg "><img src="https://i.imgur.com/gXfNhFR.png" target="_blank" alt="Hello Codename One" img width="80%"> </a>
</div>

## Extensible

Codename One can be extended easily using 3rd party libraries that can include native OS code. There is an extensive list of these libraries (cn1libs) [here](https://www.codenameone.com/cn1libs.html). The libraries list is generated automatically based on [this github project](https://github.com/codenameone/CodenameOneLibs/).

You can learn more about Codename One and its capabilities at the [main site](https://www.codenameone.com) and you can see an extensive list of documentation and tutorials [here](http://www.codenameone.com/blog/tutorials-resources-learn-java-mobile-videos-courses-ios-android.html).

## Important Links & Docs

You can get started with the binary and the birds eye view in the [download section](https://www.codenameone.com/download.html). Additional important links are:

- [JavaDoc](https://www.codenameone.com/javadoc/)
- Developer Guide - [HTML](https://www.codenameone.com/manual/) & [PDF](https://www.codenameone.com/files/developer-guide.pdf)
- [How Codename One Works](http://stackoverflow.com/questions/10639766/how-does-codename-one-work/10646336) (stackoverflow)
- [Codename One Academy](http://codenameone.teachable.com/)
- [Blog](https://www.codenameone.com/blog/)
- [Community Discussion Forum](https://www.codenameone.com/discussion-forum.html)
- [Using the Kotlin Support](https://www.codenameone.com/blog/kotlin-support-public-beta.html)


## Setup & Getting Started With The Code

NOTE: *We are in the process of migrating from Ant to Maven, which simplifies the process for building from source. 
See [Ant Quick Start](#quick-start-with-ant) for the legacy Ant build instructions.*

The setup is covered in depth in [this article and video](https://www.codenameone.com/blog/building-codename-one-from-source-maven-edition.html). 

<div>
  <a href="https://www.youtube.com/watch?v=H8-QMIsTHNc " target="_blank"><img src="https://i.imgur.com/X0xzM6H.jpg" alt="Building Codename One from Source - Maven Edition
" img width="80%"> </a>
</div>

**IMPORTANT:** Building Codename One requires **JDK 8**, currently. You cannot use JDK 11 as some sub-modules must use `-source 1.5` and `-target 1.5` to maintain backward compatibility with parts of the toolchain.


### Quick Start with Maven

~~~~
git clone https://github.com/codenameone/CodenameOne
cd CodenameOne/maven
mvn install
~~~~

This will build and install Codename One in your local Maven repository. This process can take a while since it automatically downloads dependencies with a size of ~1GB.  


To build the archetype projects from source, you should check out the [cn1-maven-archetypes](https://github.com/shannah/cn1-maven-archetypes) repository and build it also:

~~~~
git clone https://github.com/shannah/cn1-maven-archetypes
cd cn1-maven-archetypes
mvn install
~~~~  


Now that Codename One is installed in your local Maven repository, you can use that version in a project instead of the release version.
A new testing project can be quickly generated with the [Codename One initializr](https://start.codenameone.com).

After downloading and extracting the project, open its pom.xml file and and look for the `<cn1.version>` and `<cn1.plugin.version>` properties.
Then change these to point to the version that got installed into your *local* maven repository by `mvn install`. The locally built version will usually be a SNAPSHOT version (e.g. 7.0.21-SNAPSHOT).


### Quick Start with Ant

**Getting and Building Sources**

~~~~
$ git clone https://github.com/codenameone/CodenameOne
$ cd CodenameOne
$ ant
~~~~

**Running Unit Tests**

~~~~
$ ant test-javase
~~~~

**Running Samples**

The Samples directory contains a growing set of sample applications.  These samples aren't meant to be demos, but rather samples of how to use APIs.

You can launch the sample runner app from the command-line using:

~~~
$ ant samples
~~~


## ParparVM
Codename One's iOS VM is quite unique and is open source as well. You can read more about it [in its dedicated folder in this repository](https://github.com/codenameone/CodenameOne/tree/master/vm).

ParparVM is a uniquely conservative VM that translates Java bytecode to C code. Thus providing native performance and access while still providing a safety net. This approach is unique to Codename One and is essential for future compatibility!

Apple has a tendency to change things abruptly e.g. 64bit support, bitcode etc. Since ParparVM generates a standard Xcode project there were no code changes required for any of these tectonic shifts. It's as if you handcoded the project yourself!

You can even open the resulting project in xcode and debug it or profile it directly on the iOS device. This provides a lot of useful information such as readable callstacks and valuable/actionable performance tracking...

Traditional compilers fall flat in these cases.

## Modified iKVM

Codename One maintains a fork of iKVM which is a JVM for CLR. This modified port allows us to run the Universal Windows Platform implementation of Codename One natively on Windows 10 devices.

## Getting Help & FAQ

<img align="right" src="http://codenameone.com/img/blog/new_icon.png" height="150">

We provide support over at [StackOverflow when you tag using codenameone](http://stackoverflow.com/tags/codenameone), you can ask anything there and we try to be pretty responsive. [The StackOverflow link](http://stackoverflow.com/tags/codenameone) also serves as an excellent community driven FAQ since it literally maps user questions to answers.

Codename One has a [discussion group](https://www.codenameone.com/discussion-forum.html) where you can post questions. However, due to the nature of that group we try to limit discussions over the source. The discussion forum is intended for simpler usage and more complex source code hacks/native compilation might create noise there.

<br>
  
## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/beazl-peter"><img src="https://avatars.githubusercontent.com/u/68695557?v=4?s=100" width="100px;" alt="beazl-peter"/><br /><sub><b>beazl-peter</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=beazl-peter" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/liannacasper"><img src="https://avatars.githubusercontent.com/u/67953602?v=4?s=100" width="100px;" alt="liannacasper"/><br /><sub><b>liannacasper</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=liannacasper" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/sergeyCodenameOne"><img src="https://avatars.githubusercontent.com/u/69102702?v=4?s=100" width="100px;" alt="sergeyCodenameOne"/><br /><sub><b>sergeyCodenameOne</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=sergeyCodenameOne" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ThomasH99"><img src="https://avatars.githubusercontent.com/u/16265939?v=4?s=100" width="100px;" alt="ThomasH99"/><br /><sub><b>ThomasH99</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=ThomasH99" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.groupsapp.online"><img src="https://avatars.githubusercontent.com/u/11293898?v=4?s=100" width="100px;" alt="Javier Anton"/><br /><sub><b>Javier Anton</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=javieranton-zz" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://diamonddevgroup.com"><img src="https://avatars.githubusercontent.com/u/7268931?v=4?s=100" width="100px;" alt="Diamond"/><br /><sub><b>Diamond</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=diamondobama" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.informatica-libera.net/"><img src="https://avatars.githubusercontent.com/u/1997316?v=4?s=100" width="100px;" alt="Francesco Galgani"/><br /><sub><b>Francesco Galgani</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=jsfan3" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kutoman"><img src="https://avatars.githubusercontent.com/u/5825645?v=4?s=100" width="100px;" alt="kutoman"/><br /><sub><b>kutoman</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=kutoman" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ramsestom"><img src="https://avatars.githubusercontent.com/u/636758?v=4?s=100" width="100px;" alt="ramsestom"/><br /><sub><b>ramsestom</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=ramsestom" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Maaartinus"><img src="https://avatars.githubusercontent.com/u/2324516?v=4?s=100" width="100px;" alt="Maaartinus"/><br /><sub><b>Maaartinus</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Maaartinus" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/DurankGts"><img src="https://avatars.githubusercontent.com/u/16245755?v=4?s=100" width="100px;" alt="Durank"/><br /><sub><b>Durank</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=DurankGts" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://boardspace.net/"><img src="https://avatars.githubusercontent.com/u/5963076?v=4?s=100" width="100px;" alt="ddyer0"/><br /><sub><b>ddyer0</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=ddyer0" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/carlosverdier"><img src="https://avatars.githubusercontent.com/u/14301433?v=4?s=100" width="100px;" alt="carlosverdier"/><br /><sub><b>carlosverdier</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=carlosverdier" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Firethunder"><img src="https://avatars.githubusercontent.com/u/1608647?v=4?s=100" width="100px;" alt="Robert Edelmann"/><br /><sub><b>Robert Edelmann</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Firethunder" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Adalbert393"><img src="https://avatars.githubusercontent.com/u/18614910?v=4?s=100" width="100px;" alt="Adalbert393"/><br /><sub><b>Adalbert393</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Adalbert393" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://sjhannah.com"><img src="https://avatars.githubusercontent.com/u/2677562?v=4?s=100" width="100px;" alt="Steve Hannah"/><br /><sub><b>Steve Hannah</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=shannah" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/digappsepp"><img src="https://avatars.githubusercontent.com/u/32707062?v=4?s=100" width="100px;" alt="digappsepp"/><br /><sub><b>digappsepp</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=digappsepp" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Pavneet-Sing"><img src="https://avatars.githubusercontent.com/u/11755381?v=4?s=100" width="100px;" alt="Pavneet Singh"/><br /><sub><b>Pavneet Singh</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Pavneet-Sing" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/vprise"><img src="https://avatars.githubusercontent.com/u/16166226?v=4?s=100" width="100px;" alt="vprise"/><br /><sub><b>vprise</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=vprise" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://jrmydev.000webhostapp.com/"><img src="https://avatars.githubusercontent.com/u/10810617?v=4?s=100" width="100px;" alt="JrmyDev"/><br /><sub><b>JrmyDev</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=JrmyDev" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://csdesigninc.ca"><img src="https://avatars.githubusercontent.com/u/1958073?v=4?s=100" width="100px;" alt="Terry Wilkinson"/><br /><sub><b>Terry Wilkinson</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=twilkinson" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jaanushansen"><img src="https://avatars.githubusercontent.com/u/11716510?v=4?s=100" width="100px;" alt="Jaanus Hansen"/><br /><sub><b>Jaanus Hansen</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=jaanushansen" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jegesh"><img src="https://avatars.githubusercontent.com/u/6535446?v=4?s=100" width="100px;" alt="Yaakov Gesher"/><br /><sub><b>Yaakov Gesher</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=jegesh" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Munken"><img src="https://avatars.githubusercontent.com/u/773660?v=4?s=100" width="100px;" alt="Michael Munch"/><br /><sub><b>Michael Munch</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Munken" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/saeder"><img src="https://avatars.githubusercontent.com/u/9945131?v=4?s=100" width="100px;" alt="saeder"/><br /><sub><b>saeder</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=saeder" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://neptunedreams.com"><img src="https://avatars.githubusercontent.com/u/19262903?v=4?s=100" width="100px;" alt="Miguel Muñoz"/><br /><sub><b>Miguel Muñoz</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=SwingGuy1024" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://ahmedengu.com"><img src="https://avatars.githubusercontent.com/u/2976004?v=4?s=100" width="100px;" alt="Ahmed Aboumalwa"/><br /><sub><b>Ahmed Aboumalwa</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=ahmedengu" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/FabioConceicao"><img src="https://avatars.githubusercontent.com/u/13354592?v=4?s=100" width="100px;" alt="Fabio"/><br /><sub><b>Fabio</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=FabioConceicao" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://forann.eu"><img src="https://avatars.githubusercontent.com/u/12081628?v=4?s=100" width="100px;" alt="Piotr"/><br /><sub><b>Piotr</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=PiotrZub" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://mat2095.de"><img src="https://avatars.githubusercontent.com/u/11258252?v=4?s=100" width="100px;" alt="Matthias Bay"/><br /><sub><b>Matthias Bay</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Mat2095" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/sannysanoff"><img src="https://avatars.githubusercontent.com/u/952071?v=4?s=100" width="100px;" alt="Sanny Sanoff"/><br /><sub><b>Sanny Sanoff</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=sannysanoff" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/McSym28"><img src="https://avatars.githubusercontent.com/u/8185872?v=4?s=100" width="100px;" alt="McSym28"/><br /><sub><b>McSym28</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=McSym28" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://ericleong.me"><img src="https://avatars.githubusercontent.com/u/1572011?v=4?s=100" width="100px;" alt="Eric Leong"/><br /><sub><b>Eric Leong</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=ericleong" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://davidday.tw/"><img src="https://avatars.githubusercontent.com/u/47077427?v=4?s=100" width="100px;" alt="David Day"/><br /><sub><b>David Day</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=dj6082013" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Rocketeer007"><img src="https://avatars.githubusercontent.com/u/11492464?v=4?s=100" width="100px;" alt="Nick Price"/><br /><sub><b>Nick Price</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Rocketeer007" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ahnafbinazad"><img src="https://avatars.githubusercontent.com/u/66205903?v=4?s=100" width="100px;" alt="Ahnaf Bin Azad"/><br /><sub><b>Ahnaf Bin Azad</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=ahnafbinazad" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/OctavioAnino"><img src="https://avatars.githubusercontent.com/u/114261436?v=4?s=100" width="100px;" alt="Octavio E Anino"/><br /><sub><b>Octavio E Anino</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=OctavioAnino" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://linktr.ee/yashpimple"><img src="https://avatars.githubusercontent.com/u/97302447?v=4?s=100" width="100px;" alt="Yash Pimple"/><br /><sub><b>Yash Pimple</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=YashPimple" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Wninayyds"><img src="https://avatars.githubusercontent.com/u/90488923?v=4?s=100" width="100px;" alt="Nina"/><br /><sub><b>Nina</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=Wninayyds" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/FercueNat"><img src="https://avatars.githubusercontent.com/u/113535859?v=4?s=100" width="100px;" alt="FercueNat"/><br /><sub><b>FercueNat</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=FercueNat" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ImmediandoSrl"><img src="https://avatars.githubusercontent.com/u/172423330?v=4?s=100" width="100px;" alt="ImmediandoSrl"/><br /><sub><b>ImmediandoSrl</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=ImmediandoSrl" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/davideprimasc"><img src="https://avatars.githubusercontent.com/u/159039808?v=4?s=100" width="100px;" alt="davideprimasc"/><br /><sub><b>davideprimasc</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=davideprimasc" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/DB107"><img src="https://avatars.githubusercontent.com/u/154587979?v=4?s=100" width="100px;" alt="DB107"/><br /><sub><b>DB107</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=DB107" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://speakerdeck.com/eltociear"><img src="https://avatars.githubusercontent.com/u/22633385?v=4?s=100" width="100px;" alt="Ikko Eltociear Ashimine"/><br /><sub><b>Ikko Eltociear Ashimine</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=eltociear" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/SamC1832js"><img src="https://avatars.githubusercontent.com/u/79888848?v=4?s=100" width="100px;" alt="Sam C"/><br /><sub><b>Sam C</b></sub></a><br /><a href="https://github.com/codenameone/CodenameOne/commits?author=SamC1832js" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome! ❤️
