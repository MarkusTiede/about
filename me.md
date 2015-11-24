# Markus Tiede

```
> Dipl.-Inf. (FH)
> Softwaredeveloper
```

![An official picture of me - Markus Tiede](me.jpg "Markus Tiede")


```
* 28.06.1985
```

## bio

### en
Markus is a software developer and tester at [BREDEX GmbH][bredex]. His main areas of expertise are the design of automated tests and Eclipse-RCP development. He is one of the core developers for the open-source, UI test automation tool [Jubula][], Package Maintainer for „Eclipse for Testers“ and holds a Diplom (German degree) in Computer Science from the [University of Applied Sciences in Braunschweig][ostfalia-en].

### de
Markus Tiede arbeitet als Softwareentwickler und Testberater bei der [BREDEX GmbH][bredex] mit den Schwerpunkten auf Eclipse RCP-Entwicklung und dem Design von automatisierten Regressionstests. Markus ist darüber hinaus Eclipse Committer im UI-Testautomatisierungsprojekt [Jubula][], Package Maintainer für „Eclipse for Testers“ und hat einen Abschluss als Diplom-Informatiker von der [FH Braunschweig-Wolfenbüttel][ostfalia-de].

![Friend of Eclipse](http://eclipse.org/donate/images/friendslogo200.png "Friend of Eclipse")

## ToC / Inhaltsverzeichnis

|      | [talks / Vorträge](#talks--vorträge) | [paper / Artikel](#paper--Artikel)  |
| ---- | ------------------:| ------------------:|
| 2015 | [...](#talks-2015) | [...](#paper-2015) |
| 2014 | [...](#talks-2014) | [...](#paper-2014) |
| 2013 | [...](#talks-2013) | [...](#paper-2013) |
| 2012 | [...](#talks-2012) | [...](#paper-2012) |
| 2011 | [...](#talks-2011) |                    |
| 2010 | [...](#talks-2010) | [...](#paper-2010) |
| 2009 | [...](#talks-2009) |                    |
| 2008 | [...](#talks-2008) |                    |

 - [other qualifications / weitere Qualifikationen](#other-qualifications--weitere-qualifikationen)
 - [other references / weitere Referenzen](#other-references--weitere-referenzen)

 - [VNC remote support / Fernwartung][support]

## talks / Vorträge

### talks 2015


#### `en` Jubula 101
 - [EclipseCon Europe][t.2015.ece.j101]
 - [Video @ YouTube][t.2015.ece.j101.video]

Come to this talk to get your 101, your 411 and possibly some other important numbers about the Eclipse Jubula project for functional testing.

Jubula is an automated GUI testing tool for a variety of applications (including JavaFX, SWT/RCP, GEF, Swing, ...). The focus of the tool is on improving communication about and through testing, and on providing up to date quality information throughout the development process. It does this in three main ways:

Tests aren’t written in program code, so they are accessible and writable by anyone on the team (even, and especially, members who are not software engineers).
Tests aren’t written by recording actions and replaying them, since this leads to redundancies, a great deal of effort, and also means that testing can only begin when the feature is completely implemented.
There’s plenty of support for writing good, stable and robust tests by using reusable modules, separation of data and objects from the test workflow, intelligent checks and error handling.
Basically, if you want to test that your use cases are actually doable – in the same way that the users will work with your software – but you don’t want to test all your use cases manually, then you should come along to find out more.

This talk will take you on a journey through the "what is Jubula“ via the "how does it work” to a demonstration of the tool including how it plays well with continuous integration and application lifecycle management tools. There'll be time for questions at the end to cover anything else that’s important.

#### `en` Jekyll and Hyde with Jubula
 - [EclipseCon North America][t.2015.ec.jekyll]
 - [EclipseCon Europe][t.2015.ece.jekyll]
 - [Teaser Video][t.2015.ec.jekyll.teaser]

Can a test tool have more than one personality? Can a new alter ego develop over time? It turns out, yes!

One of the most salient features of working with Jubula is that tests are created via drag and drop from a library of pre-defined actions. While knowledge about testing and a certain technical affinity / capability to structure and model is required, programming knowledge is not.

Jubula’s main target group is teams with members who don’t program – to ensure that test automation is something that the whole team can work on. The question has frequently been asked though: isn’t there a way to let a developer write tests in Java using the mature Jubula remote control code? We’re pleased to announce that the answer is now yes.

And so we introduce Mr Hyde – the Jubula API. He’s not actually evil, but he is definitely a new and exciting personality for Jubula. This talk will present participants with both aspects of Jubula’s personality:
- Dr Jekyll: writing tests with the Jubula actions in the ITE
- Mr Hyde: writing Jubula tests in Java

We’ll show how the steps to start AUTs, write tests and perform test execution can be done using both aspects of Jubula. The talk will be on an introductory level to show participants their way around the tool and its features from both perspectives.

### talks 2014

#### `en` J2J - JavaFX testing with Jubula
 - [EclipseCon Europe][t.2014.ece.j2j]

JavaFX is the new black in modern Java based Ul technologies - again. And as of Java 8 a stable and refined JavaFX API is available out-of-the-box for the general public. That said, it's no wonder that we - the Jubula team - have been working very hard to support this new Ul technology for test automation right from the very beginning.

In this session Markus
- will give a brief introduction to Jubula and its concepts,
- demonstrate how easy it is to automate Ul tests for JavaFX / e(fx)clipse based AUTs (Application Under Test).
- point out the current development status of the JavaFX support and its architecture

This talk is primarily aimed at people with a general interest in JavaFX and code-free test automation.

### talks 2013

#### `en` To infinity and beyond – making Jubula surpass its limits
 - [EclipseCon Europe][t.2013.ece.extend]
 - [PDF Slides][t.2013.ece.extend.slides]
 - [Video @ YouTube][t.2013.ece.extend.video]

As the Jubula team, we’re generally quite proud of the out-of-the-box support we have. However, we’ve been involved in enough projects to know that there are sometimes boundaries that are hard to solve when thinking about realizing them with Jubula, for example:

- working with custom test data and data structures
- robust UI widget recognition
- remote controlling custom UI controls
- addressing GEF figures
- getting individual test results
- ...

Even if what you’re looking for isn’t in the tool, there are many ways in which you can extend Jubula to go beyond its limits:

- Integrated Testing Environment – extending the ITE
 - Adding test data functions
 - Writing your own BIRT reports
 - Providing your own unbound_modules_*
 - Defining your own test style rules
 - Installing your own plugins e.g. Mylyn connectors
 - Writing your own views
- Remote Controlling – extending the RC
 - Improving UI-widget recognition in Swing, SWT, HTML, iOS
 - Improving GEF testing by enhancing the identifier
 - Supporting custom renderer solutions for Swing, SWT, iOS
 - Adding support for custom monitoring agents
 - Adding support for foreign keyboard layouts
- Toolkit extensions for “wacky widgets”
 - Adapting your widgets to our toolkit abstraction
 - Supporting your own components, actions and toolkits

In this talk Markus will give an overview of Jubula's concepts and architecture as well as many hands-on examples how to extend all these different aspects of Jubula to make it fit your specific needs.

This talk is aimed at people who have a general interest in UI test automation and Jubula, as well as users who may have already faced some of the limits of test automation. We won’t be losing you in the minute details of each aspect, but we will make sure you know what’s possible and how to go about doing it.

#### `en` Jubula Tutorial – Specify, execute, analyze
 - [EclipseCon Europe][t.2013.ece.tutorial]
 - [PDF Slides][t.2013.ece.tutorial.slides]

The world needs more acceptance tests. They tell us whether or not the software being developed does what the customer ordered and give us a great opportunity to amend misunderstandings and problems before a product is released. Doing this kind of testing manually is repetitive, error-prone, boring, and also hopeless – there is no way that manual acceptance testing can keep up with development, especially if you aim to have continuous feedback about quality.
The Eclipse Jubula Project for functional testing lets you automate these kinds of tests, and it does so without requiring you to write program code, and also without having to resort to recording user actions.

“How does that work?” we hear you ask. How are tests specified to be intelligent and robust? What happens if changes occur? And how do tests fit into the development process? All excellent questions. [...]

#### `en` Testing mobile applications with Jubula
 - [EclipseCon Europe][t.2013.ece.mobile]

After multiple years of experience with testing desktop toolkits, the GUIdancer / Jubula team made their first foray into the world of mobile testing with version 7.0 of GUIdancer. Since the feature-merge in the standalone versions of Jubula and GUIdancer, iOS testing is now available to everyone, and we’ve already started work on other mobile toolkits.

This talk looks at mobile testing both from a technical perspective as well as from the view of a tester of mobile applications. We cover points such as:

- Transferable knowledge from desktop testing – test design and component interaction
- New aspects involved with mobile testing
 - increased variety and diversity (platforms, devices, versions)
 - new functions to consider (external applications, GPS, battery)
 - new interactions (gestures)
- The interesting challenge of cross-platform applications
- Setup and environment considerations for mobile testing
 - Starting and connecting to applications
 - Communication with an application under test
 - Continuous integration
- Specialties of mobile robots

The aim of the talk is to present the support in Jubula and GUIdancer for mobile testing, as well as to provide background information on mobile testing in general. Alongside the theory, we’ll also show some demonstrations.

#### `de` UI-Testautomatisierung für mobile Plattformen
 - [DWX - Mobile Developer Conference][t.2013.dwx]
 - [PDF Slides][t.2013.dwx.slides]

Die BREDEX GmbH hat als Open-Source Testtoolhersteller für Desktop-Applikationen jahrelang ausgiebig Erfahrungen im Bereich der User-Interface Testautomatisierung sammeln können. Dabei haben sich eine Vielzahl von Konzepten als tragfähige Grundlage für die Qualitätssicherung von Anwendungen bewiesen, um eine nachhaltige und kosteneffiziente Automatisierung betreiben zu können. Zu diesen Konzepten zählen

 - die strikte Entkopplung von UI-Toolkit-Technologie und Testsprache
 - das Bereitstellen von „high-level“ UI-Automatisierungsbausteinen die eine natürlich-sprachliche Testspezifikation ermöglichen
 - die Wiederverwendbarkeit von Tests zu fordern und zu fördern

Dieser Vortrag zeigt am konkreten Beispiel „iOS“ die Probleme und Schwierigkeiten des Transfers eben diese Konzepte in die Welt der mobilen Plattformen zu übertragen und demonstriert zugleich das große Potential der technologieübergreifenden Testautomatisierung auf mobiler Hard- und Software.

#### `de` UI-Testautomatisierung für mobile Plattformen – Herausforderung und Chance zugleich!
 - [iqnite Deutschland][t.2013.iq.de]
 - [iqnite Schweiz][t.2013.iq.ch]

Dieser Vortrag zeigt am konkreten Beispiel iOS und Windows 8 die Probleme und Schwierigkeiten, die Konzepte der Desktopwelt in die der mobilen Plattformen zu übertragen und demonstriert zugleich das große Potential der technologieübergreifenden Testautomatisierung auf mobiler Hard- und Software. Es werden dabei sowohl die grundlegenden Technologien und Konzepte, als auch konkrete Erfahrungen der mobilen cross-plattform „App“-entwicklung und -testautomatisierung erläutert. Belegt und unterstrichen wird dies durch eine Reihe von Demonstrationen.

#### `en` Continuous testing with Jubula – where the rubber meets the road!
 - [EclipseCon North America][t.2013.ec]
 - [PDF Slides][t.2013.ec.slides]

You've got software. You've got a list of features to implement. You've got some automated tests. You've got upcoming releases. The only glue that is going to make this scenario work is Continuous Integration. When you're adding and changing functionality, knowing what your changes are doing to your quality on a daily basis can be the difference between a successful release and a horrifically painful one. A project team needs to be able to make qualified decisions based on quality information at any given time, which is why you’ve got to hit the road (the application under test) with the rubber (the automated tests) as often as possible!

In this session Markus will give a full technical walk-through of all the necessary steps to setup Jubula tests in various continuous integration scenarios.

After starting with a super-quick overview of Jubula's concepts and architecture for any Jubula "newbies" in the audience, Markus moves onto a live walk-through of the necessary steps to get Jubula and Hudson playing well together. On the way, we'll look at topics such as:

- setup, maintenance and teardown of the test environment
- useful Jubula tools, configurations and settings
- Hudson options to optimize scheduling and test distribution
- making the whole system work for more complex test scenarios such as testing multiple AUTs and projects on various architectures and operating systems.

This talk is designed to give a detailed technical road-map for successful continuous testing with Jubula.

### talks 2012

#### `en` UI testing with Jubula - wacky widgets
 - [EclipseCon Europe][t.2012.ece]
 - [PDF Slides][t.2012.ece.slides]

Standard widgets and usage concepts are great. They are known by users, respond in expected ways, and are generally testable out-of-the-box with UI automation tools like Jubula.

Apparently though, standard widgets are boring, that table-in-a-combo-box-with-a-tree-in-it is the new black. Joking aside, the temptation (or necessity) to stray from the standard path will happen to all of us at one time or another. Good examples for that can e.g. be found in the Nebula project.
You may well ask yourself what that means for UI testing ...

In this session Markus will give a brief introduction to Jubula and its toolkit concepts, as well as demonstrate how easy it is to extend Jubula to support custom UI widgets.

### talks 2011

#### `en` Starting an Eclipse Project: The first 90 days… and the year that follows
 - [EclipseCon Europe][t.2011.ece]

What are you getting yourself into by deciding to host your project at Eclipse? From the decision to open source your software, to the formal processes for intellectual property and development, all the way up to the generation and care of the community, the road may contain more twists and turns than you expect. Unless of course, you have a map – which is what we’d like to try and give you.

This talk looks at the steps for hosting your project at Eclipse from various aspects, and through two sets of eyes. Wayne Beaton combines his knowledge of the Eclipse and IP processes with the recent experiences of Markus Tiede, a committer on the new Jubula project. Together, they navigate through the “why” of open sourcing software, the “how” it is done at Eclipse, the “what” else to expect, and the “who” of the project – the community.

### talks 2010

#### `de` Automatisiertes Testen mit Jubula
 - [SEACON][t.2010.seacon]

Ab März werden Kernteile von GUIdancer als Open Source Projekt in der Eclipse Foundation veröffentlicht. Das Jubula Functional Testing Tool Projekt ermöglicht die Erstellung und Ausführung automatisierter Akzeptanztests anhand von den bekannten Best-Practices aus der Softwareentwicklung (Lesbarkeit, Modularität, Wartbarkeit) ohne jeglichen Programmieraufwand. Das Verfahren des Keyword-Driven Testings erlaubt außerdem eine frühzeitige Testfallerstellung, welches die Einbindung in agilen Prozessen unterstützt. In diesem Talk stellen wir das Jubula Projekt vor und geben eine Vorführung des Tools.

### talks 2009

#### `en` Write Once, Test Everywhere? Cross Platform Development and Testing with Eclipse
 - [Eclipse Summit Europe][t.2009.ese]
 - [Eclipse Live - Webinar][t.2009.el]
 - [PDF Slides][t.2009.el.slides]

How platform independent are Eclipse applications in practice? This talk looks at some of the differences between operating systems supported by Eclipse with respect to RCP applications and examines their effects on usability, development and testing.

This webinar is aimed at developers, project managers and testers (automated and manual) working on RCP applications that are intended to run on more than one platform. Participants will learn about large and small differences between the platforms. Some of these differences must simply be considered in the development and testing process, others mean that testing, documentation and development are affected.

Some of the points raised include:

 - How widgets can behave differently on the platforms
 - Variation in the library support for each platform
 - Other GUI considerations such as tooltips, toolbars, buttons and focus
 - Automated testers will also benefit from the information and examples in the talk. Ideally, only one automated test should be necessary to test all versions of an application. Some of the differences between the platforms make this aim difficult, and some differences mean finding a lowest common denominator to be able to write tests. The variation between the platforms is therefore something which must be considered at the test planning stage, and in the test design itself.

Participants will learn to consider and deal with any variations between platforms to make cross-platform projects a success.

### talks 2008

#### `en` Best Practices for the Creation of Automated Agile GUI Tests 
 - [STPCon][t.stpcon]

This class uses insights and project experience from agile development processes to suggest requirements and solutions for automated agile test design.
Begin by looking at the agile development process to determine the requirements for agile testing. Then hear practical solutions to achieving these goals within a project based on real industrial project experience with automated agile testing. Aimed at testers and project managers, the class offers a set of practices that enable tests to grow alongside product development, ensuring that both new and old functions are tested at each release.

#### `en` Automated GUI Testing - common misbeliefs
 - [STPCon][t.stpcon]
 - [PDF Slides][t.2008.stpcon.slides]

This 5-minute lightning talk emphasised spotting the spam when thinking about UI test automation tools.

## paper / Artikel

### paper 2015

#### `de` Jubula goes JUnit – Eine Einführung in das Jubula-Client-API
 - [Eclipse Magazin][p.2015.em] - 5.2015

Seit nunmehr zehn Jahren verfolgen wir im Jubula-Team das Ziel, Testautomatisierung für grafische Benutzeroberflächen zu ermöglichen, ohne dabei zwingend notwendig über tiefgehende Programmierkenntnisse im zugrunde liegenden UI-Toolkit oder im internen Aufbau der AUT (Application under Test) zu verfügen. Und auch auf unserem Weg zu Mars haben wir trotz der Einführung eines Java-API für Entwickler stets darauf geachtet, dieses Ziel nicht aus den Augen zu verlieren.  [...]

### paper 2014

#### `de` Jubula goes JavaFX: Technologietransfer leicht gemacht
 - [Eclipse Magazin][p.2014.em] - 5.2014

Pünktlich mit Java 8 hat Oracle im Frühjahr dieses Jahres eine grundlegend überarbeitete Version der Benutzeroberflächentechnologie JavaFX veröffentlicht. Dieses auf multimediale Inhalte und Effekte optimierte UI-Toolkit gilt bereits seit einiger Zeit als Nachfolger von Swing und erlaubt es, mit Leichtigkeit moderne, reaktive und ansprechende Benutzeroberflächen zu gestalten. Für uns, das Jubula-Team, bedeutete das: neues Jahr – neues Toolkit! Standen für uns im letzten Jahr mobile Plattformen wie iOS im Fokus, so war es im „Luna“-Jahr die einfache und zuverlässige Anbindung zur Fernsteuerung und Testautomatisierung von JavaFX-Oberflächen. Wir geben einen detaillierten technischen Einblick in die notwendigen Grundlagen zur Anbindung von JavaFX-Applikationen in Jubula und zeigen die notwendigen Schritte des Testtechnologie-und Know-how-Transfers von bekannten Jubula-Toolkits wie Swing und SWT zu JavaFX. [...]

#### `en` Automated Acceptance Tests for Mobile Applications: Thoughts on Test Strategy
 - [testing experience EN][p.2014.te] - Testing Experience – 26 - June 2014

First impressions count when it comes to apps, be they tailor-made enterprise apps or apps from a store. It has never been so easy to try out new applications – and then uninstall them if they are not suitable or acceptable. The consequences can be much worse than just losing one customer or user; public feedback systems and disappointed customers can damage the reputation and image of an app, as well as of the company behind it.

For this reason, the user perspective is of utmost importance when developing mobile applications. Acceptance tests help teams to recognize early whether an app behaves as expected and does not produce any unwanted side effects during use. As for any project, we need to decide what to test, how to test, when to test, and how much to automate. However, automation in particular can be a tricky subject for mobile applications, and the specific challenges should be taken into account when defining a test strategy. [...]

### paper 2013

#### `de` Automatische Akzeptanztests für mobile Anwendungen - Überlegungen zur Teststrategie
 - [testing experience DE][p.2013.te] - Ausgabe #3

Ob individuell entwickelte Enterprise-Apps oder Apps aus dem Store – die Meinung zu einer App wird schnell gefällt. Noch nie war es so einfach, eine Anwendung auszuprobieren und bei Nichtgefallen zu deinstallieren. Die entsprechenden öffentlichen Bewertungen oder das Feedback vom Kunden können den Ruf und das Image der App und auch der dahinter stehenden Firma schnell verbessern oder verschlechtern.

Die Benutzerperspektive anhand von Akzeptanztests zu vertreten ist deshalb für mobile Anwendungen besonders wichtig. So kann man frühzeitig feststellen, ob eine App einerseits das gewünschte Verhalten besitzt und andererseits keinerlei unerwünschten Nebeneffekte bei der Bedienung auftreten. Wie für jedes Projekt muss dafür eine geeignete und angemessene Teststrategie einschließlich Testarten und -methoden, Automatisierungsgrad und Zielplattformen definiert werden. Besondere Herausforderungen lauern allerdings beim automatischen Testen mobiler Apps, die – so viel sei schon vorweg gesagt – Auswirkungen auf Ihre Teststrategie haben werden. [...]

#### `de` Tip, Tap, Test: Automatisierte Tests im mobilen Umfeld – der Umstieg aus der Desktopwelt
 - [Eclipse Magazin][p.2013.em] - 3.2013

Im privaten Bereich ist der mobile Zugang zu Daten und Diensten schon alltäglich – im Arbeitsumfeld noch nicht überall. Aber gerade dort kann der direkte Zugang zu aktuellen Daten und Diensten enorm vorteilhaft sein. Für den Kunden sowie für den Dienstleister ist also ein Umdenken erforderlich – insbesondere beim Thema Testen. Welche Besonderheiten gibt es beim automatisierten Testen? Und mit welchen Techniken und Technologien lässt sich erfolgreich Qualitätssicherung betreiben? [...]

### paper 2012

#### `de` Open Sourcing and Release Engineering @ Eclipse.org - The Making of an Eclipse Project 
 - [JAXenter][p.2012.jx]
 - [Eclipse Magazin][p.2012.em] - 1.2012

Was steckt eigentlich hinter einem Eclipse-Projekt? Welche Entscheidungen sind zu treffen, welche Bedingungen zu erfüllen, wie läuft das alles? Das Eclipse-Jubula-Team berichtet in loser Folge über seine Erfahrung beim Open Sourcing von Jubula. Dabei geht es nicht nur um Technik, sondern auch um Strategien, Abläufe und schwierige Entscheidungen. [...]

### paper 2010

#### `de` Refaktorisieren von Tests - Erfahrungen aus der schlüsselwortgetriebenen Testentwicklung
 - [OBJEKTspektrum][p.2010.os] - Ausgabe 04/2010

Tests und Testautomatisierung sollen helfen, Kosten zu sparen und die Softwarequalität zu erhöhen. Damit das mittel- bis langfristig gelingt, müssen auch Tests „gehegt und gepflegt” werden. In diesem Artikel erfahren Sie anhand ausführlicher Beispiele, welche Möglichkeiten des Refaktorisierens dabei helfen, dieses Ziel zu erreichen und es nachhaltig zu sichern. Der Artikel basiert auf mehrjährigen Erfahrungen im Bereich des schlüsselwortbasierten Testens, gibt konkrete Hinweise zum erfolgreichen Refaktorisieren in diesem Umfeld und verdeutlicht diese an einer Beispielapplikation mit dazugehörigem Test. [...]

#### `en` Test design for stubborn applications - Event handling in automated acceptance tests
 - [testing experience][p.2010.te]

At the beginning of any test automation project for acceptance tests, the focus is usually on creating a set of running tests to cover the most critical or newest aspects of the software being developed. Such acceptance tests see the application as a black-box, testing the business logic through the GUI. Once a good base of runnable tests has been produced, however, it quickly becomes critically important to ensure that events that affect one part of the test do not lead to all other tests subsequently failing (due to “inherited” problems from the first failure), or not running at all (because the whole test has been aborted) . The discovery of errors in an application is a natural and desired effect of automated acceptance tests; however, the other aim of acceptance testing should always be to have the most comprehensive knowledge of the software quality. If 90% of the tests cannot run because an event occurred in the first 10%, this aim cannot be achieved. The quality will suffer as a result, and the costs to fix any subsequent untested errors will increase as more time passes between introducing the error and finding and resolving it.

A well thought-out system of event handling is therefore necessary to ensure that the quality of the whole software project can be monitored despite problems in individual areas. In addition, adding event handling to the project can make it easier to find and reproduce errors to allow them to be fixed in a short time. This article offers strategies and suggestions on introducing robust and understandable event handling in automated acceptance tests. [...]

#### `de` Modellbasiertes Testen grafischer Benutzeroberflächen: Ein Erfahrungsbericht
 - [Amazon.de][p.2010.bk]

```
Taschenbuch: 108 Seiten
Verlag: VDM Verlag Dr. Müller
Erscheinungsdatum: 21. März 2010
Sprache: Deutsch
ISBN-10: 3639239334
ISBN-13: 978-3639239331
```
Dieses Buch beschäftigt sich mit dem Thema, aus Modellgraphen, die Informationen zur Funktionsweise eines Systems beinhalten, Testabläufe zu generieren. Das Buch erläutert dabei das zugrundeliegende Datenmodell der Modelle und zeigt, wie auf dieser Basis Testabläufe erstellt und gepflegt werden können. Auch die zur Umsetzung verwendeten Frameworks, wie das "Eclipse Modeling Framework" (EMF), das "Graphical Modeling Framework" (GMF) und die "Eclipse RCP" werden detailliert vorgestellt. Softwareergonomische Aspekte und Anwendungsbeispiele der Software schließen das Buch ab.

## other qualifications / weitere Qualifikationen

### 2013: Certified ScrumMaster®

Erfolgreiche Zertifizierung zum [CSM¹](http://www.scrumalliance.org/community/profile/mtiede).

---
![My CSM certificate.](documents/cert-csm.png "ScrumMaster® certificate")
---
¹ Certified ScrumMaster is a certification mark of [Scrum Alliance, Inc](http://www.scrumalliance.org).  Any unauthorized use is strictly prohibited.

### 2009: IHK Ausbilderschein

Erfolgreich absolvierte [Ausbilder-Eignungsprüfung](http://de.wikipedia.org/wiki/Ausbilder#Ausbildung_in_Deutschland) der [IHK Braunschweig](http://www.braunschweig.ihk.de).

---
![My AEVO certificate.](documents/cert-aevo.jpg "AEVO certificate")
---

## other references / weitere Referenzen

```
XING:       http://www.xing.com/profile/Markus_Tiede
Twitter:    http://twitter.com/MarkusTiede
Atlassian:  http://bitbucket.org/markus_tiede
this:       http://raw.github.com/MarkusTiede/about/master/me.md
```


==========================
[bredex]: http://www.bredex.de
[ostfalia-en]: http://www.ostfalia.de/cms/en/index.html
[ostfalia-de]: http://www.ostfalia.de
[Jubula]: http://www.eclipse.org/jubula
[support]: http://mtiede.de/misc/vncSupport-win32-win32-x86.exe

[t.2015.ece.j101]: https://www.eclipsecon.org/europe2015/session/jubula-101
[t.2015.ece.j101.video]: https://www.youtube.com/watch?v=Xrfasxp77r4
[t.2015.ece.jekyll]: https://www.eclipsecon.org/europe2015/session/jekyll-and-hyde-jubula-automated-testing-both-sides
[t.2015.ec.jekyll.teaser]: https://www.youtube.com/watch?v=jeNBKf-hAmc
[t.2015.ec.jekyll]: https://www.eclipsecon.org/na2015/session/jekyll-and-hyde-jubula
[t.2014.ece.j2j]: https://www.eclipsecon.org/europe2014/session/j2j-javafx-testing-jubula
[t.2013.ece.extend]: http://www.eclipsecon.org/europe2013/infinity-and-beyond-–-making-jubula-surpass-its-limits-presented-bredex
[t.2013.ece.extend.slides]:  talks/2013-ece-jubula-extend.pdf?raw=true
[t.2013.ece.extend.video]:  http://www.youtube.com/watch?v=prNt5_LhXdo
[t.2013.ece.tutorial]: http://www.eclipsecon.org/europe2013/jubula-tutorial-–-specify-execute-analyze
[t.2013.ece.tutorial.slides]: http://www.eclipsecon.org/europe2013/sites/eclipsecon.org.europe2013/files/JubulaTutorial.pdf
[t.2013.ece.mobile]: http://www.eclipsecon.org/europe2013/testing-mobile-applications-jubula
[t.2013.dwx]: http://www.developer-week.de/Programm/Veranstaltung/(event)/11089
[t.2013.dwx.slides]: talks/2013-dwx-mobile-testing.pdf?raw=true
[t.2013.iq.de]: http://www.iqnite-conferences.com/de/programm/25april.aspx
[t.2013.iq.ch]: http://www.iqnite-conferences.com/ch/
[t.2013.ec]: http://www.eclipsecon.org/2013/sessions/continuous-testing-jubula-–-where-rubber-meets-road 
[t.2013.ec.slides]:  talks/2013-ec-ci-jubula-hudson.pdf?raw=true
[t.2012.ece]: http://www.eclipsecon.org/europe2012/sessions/ui-testing-jubula-wacky-widgets
[t.2012.ece.slides]: http://www.eclipsecon.org/europe2012/sites/eclipsecon.org.europe2012/files/UI%20testing%20with%20Jubula%20-%20wacky%20widgets.pdf
[t.2011.ece]: http://www.eclipsecon.org/europe2011/sessions/starting-eclipse-project-first-90-days…-and-year-follows
[t.2010.seacon]: http://www.sigs-datacom.de/seacon2011/konferenz/sessiondetails.html?tx_mwconferences_pi1%5BshowUid%5D=559&tx_mwconferences_pi1%5Banchor%5D=%23Di41&tx_mwconferences_pi1%5Bs%5D=0
[t.2009.ese]: http://www.eclipsecon.org/summiteurope2009/sessions?id=920
[t.2009.el]: http://live.eclipse.org/node/834
[t.2009.el.slides]: http://www.eclipse.org/community/training/webinars/091201_CrossPlatform_Webinar.pdf
[t.stpcon]: http://www.stpcon.com
[t.2008.stpcon.slides]: talks/2008-stpcon-lt.pdf?raw=true

[p.2015.em]: https://jaxenter.de/jubula-goes-junit-25358
[p.2014.em]: https://jaxenter.de/jubula-goes-javafx-897
[p.2014.te]: http://www.testingexperience.com
[p.2013.te]: http://www.mtiede.de/paper/p.2013.te.pdf
[p.2013.em]: http://www.mtiede.de/paper/p.2013.em.pdf
[p.2012.jx]: https://jaxenter.de/open-sourcing-release-engineering-eclipse-org-5085
[p.2012.em]: http://www.mtiede.de/paper/p.2012.em.pdf
[p.2010.te]: http://www.mtiede.de/paper/p.2010.te.pdf
[p.2010.os]: http://www.sigs-datacom.de/fachzeitschriften/objektspektrum/aktuelle-ausgabe.html?tx_mwjournals_pi1%5Bpointer%5D=0&tx_mwjournals_pi1%5Bmode%5D=1&tx_mwjournals_pi1%5BshowUid%5D=6634
[p.2010.bk]: http://www.amazon.de/Modellbasiertes-Testen-grafischer-Benutzeroberflächen-Erfahrungsbericht/dp/3639239334/
