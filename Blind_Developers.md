---
title: "Blind Developers"
subtitle: "30 Creators of Apps While Blind or Low Vision"
author: "Jamal Mazrui"
date: "June 2026"
version: "v2.11.0"
lang: en-US
toc: true
toc-depth: 3
abstract: |
  A directory of software developers who are blind or have low vision. Every developer listed has at least
  one app or tool with a working link to where it can be obtained and used,
  actively developed in the year 2020 or later. Each developer is listed
  alphabetically by last name with up to three projects and a Profiles list.
keywords:
  - blind developers
  - low vision developers
  - screen reader
  - JAWS
  - NVDA
  - VoiceOver
  - accessibility
  - assistive technology
  - open source
---

# Blind Developers

This directory lists 28 developers who are blind or have low vision, along with software each has built. It is meant in part as a resource for aspiring blind developers, and as a way to find and reach the developers listed.

This is one of three companion directories, alongside [Blind Authors](https://jamalmazrui.github.io/BlindAuthors/) and [Blind Presenters](https://jamalmazrui.github.io/BlindPresenters/).

A developer is included when they were blind or had low vision while creating the work and have at least one app or tool reachable through a working link. The focus is contemporary: each developer's software has been active in the year 2020 or later, so long-running tools such as JAWS, NVDA, and Emacspeak appear alongside newer projects. Up to three projects are shown per developer, followed by a "Profiles:" line with GitHub, LinkedIn, a website, or other relevant pages. Some of these tools are built in collaboration, but everyone listed has individually created or led at least one app of their own, and those are the projects highlighted here.

Developers are listed alphabetically by last name, with the projects grouped by platform in an appendix.

This selection carries an English-language bias: it relies on documentation, code, and sources available to me in English, so blind developers who build and publish in other languages are certainly underrepresented here.

## Table of Contents

- Developers (alphabetical by last name):
  - [Taylor Arndt](#dev-arndt)
  - [Jeff Bishop](#dev-bishop)
  - [John Boyer](#dev-boyer)
  - [Mike Calvo](#dev-calvo)
- [Matt Campbell](#dev-campbell)
  - [Michael Curran](#dev-curran)
  - [Michael Doise](#dev-doise)
  - [Liam Erven](#dev-erven)
  - [Kelly Ford](#dev-ford)
  - [Bryan Garaventa](#dev-garaventa)
  - [Tony Gebhard](#dev-gebhard)
  - [Quin Gillespie](#dev-gillespie)
  - [Glen Gordon](#dev-gordon)
  - [Brian Hartgen](#dev-hartgen)
  - [Doug Lee](#dev-dlee)
  - [Joseph Lee](#dev-jlee)
  - [Andre Louis](#dev-louis)
  - [Tony Malykh](#dev-malykh)
  - [Jamal Mazrui](#dev-mazrui)
  - [Marc Mulcahy](#dev-mulcahy)
  - [Ken Perry](#dev-perry)
  - [André Polykanine](#dev-polykanine)
  - [T. V. Raman](#dev-raman)
  - [Derek Riemer](#dev-riemer)
  - [Saqib Shaikh](#dev-shaikh)
  - [Tyler Spivey](#dev-spivey)
  - [James Teh](#dev-teh)
  - [Carter Temm](#dev-temm)
  - [Christopher Toth](#dev-toth)
  - [Sam Tupy](#dev-tupy)
- [Projects by Platform](#projects-by-platform)

## Developers (Alphabetical by Last Name)

### Taylor Arndt {#dev-arndt}

Developer and Chief Operating Officer at Techopolis who builds Swift and web apps with accessibility designed in from the start.
Profiles: [LinkedIn](https://www.linkedin.com/in/taylor-arndt-3ab16a142/), [Website](https://taylorarndt.com/).

#### [accessibility-agents](https://github.com/Community-Access/accessibility-agents) {#accessibility-agents}
A team of AI review agents for Claude Code, GitHub Copilot, and Claude Desktop that enforce WCAG 2.2 compliance, co-founded with Jeff Bishop.

#### [Quill](https://github.com/Community-Access/quill) {#quill}
An accessible, screen-reader-first text and code editor for Windows and macOS, co-created with Jeff Bishop. The name stands for Quality, Usable, Inclusive, Lightweight, and Literate, and the goal is a first-class editing experience for screen reader users from the first line of code. Released as a public beta with downloadable installers.

#### [wx-accessible-webview](https://github.com/Community-Access/wx-accessible-webview) {#wx-accessible-webview}
A wxPython library, installable with `pip install wx-accessible-webview`, that makes embedded web views report correctly to screen readers such as JAWS and NVDA, solving a long-standing accessibility gap for blind developers building Python desktop apps. Also published on PyPI.

### Jeff Bishop {#dev-bishop}

President of Blind Information Technology Solutions (BITS) and an IT accessibility consultant at the University of Arizona.
Profiles: [BITS](https://bits-acb.org/), [Community Access](https://community-access.org/).

#### accessibility-agents (co-founder) {#agents-bishop}
Co-founded the AI accessibility-agents project; see the full entry under [accessibility-agents](#accessibility-agents).

#### [GLOW Accessibility Toolkit](https://bits-acb.org/) {#glow}
A BITS accessibility toolkit that audits, fixes, and templates Word, Excel, PowerPoint, Markdown, PDF, and ePub documents to meet accessibility guidelines.

#### Quill (co-creator) {#quill-bishop}
Co-created the screen-reader-first Quill editor; see the full entry under [Quill](#quill).

### John Boyer {#dev-boyer}

A software engineer from Minnesota who founded the nonprofit Computers to Help People and led the development of widely used open-source braille software until his death in 2023.
Profiles: [Wikipedia](https://en.wikipedia.org/wiki/John_Boyer_(software_engineer)).

#### [Liblouis](https://github.com/liblouis/liblouis) {#liblouis}
The open-source braille translator and back-translator, named for Louis Braille, that produces the braille output used by NVDA, Orca, and many commercial tools.

#### [BrailleBlaster](https://www.brailleblaster.org/) {#brailleblaster}
A free, cross-platform application for transcribing print documents into well-formatted braille.

### Mike Calvo {#dev-calvo}
Blind from birth; an accessibility-software entrepreneur who founded Serotek and co-founded Pneuma Solutions.
Profiles: [LinkedIn](https://www.linkedin.com/in/mikecalvo/), [Website](https://pneumasolutions.com/).

#### [System Access (Serotek)](https://pneumasolutions.com/) {#proj-system-access}
He conceived and led the delivery of the System Access screen reader and pioneering web-based access tools, and co-founded Pneuma Solutions, maker of the Remote Incident Manager.

### Matt Campbell {#dev-campbell}

Co-founder and CTO of Pneuma Solutions who has built accessibility software since the late 1990s, including work on Windows Narrator.
Profiles: [GitHub](https://github.com/mwcampbell), [Mastodon](https://toot.cafe/@matt).

#### [AccessKit](https://github.com/AccessKit/accesskit) {#accesskit}
A cross-platform Rust library that exposes accessibility APIs to UI toolkits on Windows, macOS, and Linux.

#### [Remote Incident Manager](https://pneumasolutions.com/remote-incident-manager/) {#rim}
An accessible cross-platform remote-support and remote-desktop tool for Windows and macOS.

### Michael Curran {#dev-curran}

Known as "Mick," he is the original creator of NVDA and co-founded NV Access to sustain it.
Profiles: [GitHub](https://github.com/michaeldcurran), [NV Access](https://www.nvaccess.org/).

#### [NVDA](https://github.com/nvaccess/nvda) {#nvda}
The free, open-source NonVisual Desktop Access screen reader for Windows, co-created with James Teh.
Wikipedia: [NVDA](https://en.wikipedia.org/wiki/NonVisual_Desktop_Access)

### Michael Doise {#dev-doise}

iOS and macOS developer, creator of the Perspective suite of apps and the engineer behind the ACB Link app.
Profiles: [App Store](https://apps.apple.com/us/developer/michael-doise/id586844934), [LinkedIn](https://www.linkedin.com/in/mikedoise).

#### [ACB Link](https://link.acb.org/) {#acb-link}
The American Council of the Blind's official app for iOS and Android.

#### Perspective Intelligence {#perspective-intelligence}
An AI visual-assistance app for iPhone, iPad, and Mac.

#### [VO Starter](https://apps.apple.com/us/app/vo-starter/id586844936) {#vo-starter}
An iOS app that teaches new VoiceOver users the gestures and basics of the screen reader.

### Liam Erven {#dev-erven}

Self-employed audio-game designer and founder of LWorks, making accessible games since 2002.
Profiles: [LWorks](https://l-works.net/), [YouTube](https://www.youtube.com/user/liamerven).

#### [LWorks audio games](https://l-works.net/) {#lworks}
A catalog of fully accessible audio games, including LWorks Arcade, Pigeon Panic, Super Egg Hunt Plus, and a browser-based Super Liam 2 alpha.

### Kelly Ford {#dev-ford}

Longtime accessibility leader who publishes accessible Windows utilities and Apple-platform tools.
Profiles: [GitHub](https://github.com/kellylford), [The Idea Place blog](https://www.theideaplace.net/).

#### [WeatherFast](https://apps.apple.com/us/app/weather-fast/id6757891543) {#weatherfast}
A clutter-free iOS weather app built by and for VoiceOver users, with a “Weather Around Me” feature for tracking conditions in nearby cities and historical weather going back decades.

#### [Image Description Toolkit](https://github.com/kellylford/Image-Description-Toolkit) {#image-description-toolkit}
A toolkit for generating and managing image descriptions.

#### [RSSQuick](https://github.com/kellylford/rssquick) {#rssquick}
An accessible WPF RSS reader for Windows.

### Bryan Garaventa {#dev-garaventa}

Accessibility engineer and W3C ARIA Working Group member, formerly an accessibility fellow at SSB BART Group and Level Access, who builds open-source JavaScript libraries for accessible dynamic web content.
Profiles: [LinkedIn](https://www.linkedin.com/in/bgaraventa/), [WhatSock](https://whatsock.com/), [WhatSock on GitHub](https://github.com/WhatSock).

#### [AccDC API](https://github.com/WhatSock/accdc) {#accdc}
A JavaScript engine that renders dynamic web content with accessibility built in for screen-reader and keyboard users.

#### [AccDC Technical Style Guide](https://github.com/WhatSock/tsg) {#tsg}
A library of tested, accessible interface-widget patterns and practical ARIA design guidance.

### Tony Gebhard {#dev-gebhard}

A totally blind multi-instrumentalist and assistive technology instructor from Michigan who builds free training tools for screen reader users.
Profiles: [GitHub](https://github.com/tonygeb23), [Website](https://tonygebhard.me/)

#### [NVDA Coach](https://github.com/tonygeb23/nvdaCoach-) {#nvda-coach}
A free, open-source NVDA add-on that teaches screen reader commands through guided, step-by-step lessons built directly into NVDA, with 35 lessons across five chapters covering basic navigation, browse mode, and object navigation. Also available in the NVDA Add-on Store.

### Quin Gillespie {#dev-gillespie}

Systems-level developer at Pneuma Solutions.
Profiles: [GitHub](https://github.com/trypsynth).

#### [Paperback](https://paperback.dev/) {#paperback}
An accessible, cross-platform e-reader.

#### podfeed {#podfeed}
A command-line podcast tool.

#### [Codestats](https://github.com/trypsynth/codestats) {#codestats}
A very fast command-line code-analysis tool that reports detailed statistics about a codebase across 544 programming languages, with prebuilt binaries for Linux, macOS, and Windows.

### Glen Gordon {#dev-gordon}

The original architect of the JAWS screen reader; previously a Software Fellow at Freedom Scientific.

#### [JAWS](https://www.freedomscientific.com/products/software/jaws/) {#jaws}
Job Access With Speech, the long-standing and widely used commercial Windows screen reader.
Wikipedia: [JAWS](https://en.wikipedia.org/wiki/JAWS_(screen_reader))

### Brian Hartgen {#dev-hartgen}

UK developer and JAWS scripter who builds productivity software for blind and low-vision users.
Profiles: [Hartgen Consultancy](https://www.hartgen.org/), [X](https://twitter.com/hartgenconsult).

#### J-Say {#jsay}
Links JAWS with Dragon speech recognition for hands-free, eyes-free computing.

#### [Leasey](https://www.hartgen.org/) {#leasey}
A suite of JAWS scripts that simplifies common Windows tasks for users of all experience levels.

#### Zoom Accessible Meetings app {#zoom-meetings}
Makes Zoom meetings easier to run and join with JAWS.

### Doug Lee {#dev-dlee}

Assistive-technology programmer known for a large catalog of JAWS scripts and cross-platform Python tools.
Profiles: [Website](https://www.dlee.org/).

#### BX scripting framework {#bx}
A JAWS scripting framework that underpins many of his application scripts.

#### JAWS application scripts {#dlee-scripts}
Scripts that improve JAWS access to apps such as Teams, Discord, and WhatsApp.

#### [TTCom](https://www.dlee.org/) {#ttcom}
A cross-platform, command-line TeamTalk client written in Python.

### Joseph Lee {#dev-jlee}

One of the most prolific authors of NVDA add-ons.
Profiles: [GitHub](https://github.com/josephsl).

#### [Add-on Updater](https://github.com/josephsl/addonUpdater) {#addon-updater}
Keeps other NVDA add-ons up to date.

#### [StationPlaylist](https://github.com/josephsl/stationPlaylist) {#stationplaylist}
Gives NVDA users accessible control of StationPlaylist broadcasting software.

#### [Windows App Essentials](https://github.com/josephsl/wintenApps) {#windows-app-essentials}
Improves NVDA access to built-in Windows apps.

### Andre Louis {#dev-louis}

A blind musician, producer, and accessibility advocate from London (known as Onj) who builds accessibility-first Windows tools; he was the first blind person to beta-test Native Instruments' Komplete Kontrol accessibility features.
Profiles: [GitHub](https://github.com/OnjLouis), [Website](https://onj.me/)

#### [Sensor Readout](https://github.com/OnjLouis/accessible-sensor-readout) {#sensor-readout}
An accessibility-first hardware monitoring tool that reports a computer's sensor readings, such as temperatures and fan speeds, to screen reader users.

### Tony Malykh {#dev-malykh}

Software engineer who publishes a popular family of NVDA add-ons.
Profiles: [GitHub](https://github.com/mltony).

#### [BrowserNav](https://github.com/mltony/nvda-browser-nav) {#browsernav}
Fast, structured navigation of web and document content in NVDA.

#### [Tony's Enhancements](https://github.com/mltony/nvda-tonys-enhancements) {#tonys-enhancements}
A bundle of quality-of-life tweaks for NVDA.

### Jamal Mazrui {#dev-mazrui}

Accessibility officer and developer who publishes accessibility and developer tooling.
Profiles: [GitHub](https://github.com/jamalmazrui), [LinkedIn](https://www.linkedin.com/in/jamalmazrui/).

#### [2htm](https://github.com/JamalMazrui/2htm) {#app-2htm}
Converts Word, Excel, PowerPoint, PDF, and Markdown files into accessible HTML that preserves headings, lists, tables, and image alt text.

#### [extCheck](https://github.com/JamalMazrui/extCheck) {#extcheck}
Checks the accessibility of Word, Excel, PowerPoint, and Markdown files, writing per-file CSV reports of issues found by an extensible rule registry.

#### [urlCheck](https://github.com/JamalMazrui/urlCheck) {#urlcheck}
Drives Microsoft Edge through Playwright to run axe-core on each page, producing per-page reports plus a session-level Accessibility Conformance Report against all 86 WCAG 2.2 success criteria.

### Marc Mulcahy {#dev-mulcahy}

Principal software development engineer at Amazon Lab126 who created the first working prototype of the Orca screen reader and co-founded LevelStar.
Profiles: [LinkedIn](https://www.linkedin.com/in/marcmulcahy/).

#### [VoiceView](https://www.amazon.com/b?node=21213727011) {#voiceview}
Amazon's built-in screen reader for Fire tablets, Fire TV, and Echo Show smart displays.

### Ken Perry {#dev-perry}

Senior software engineer at the American Printing House for the Blind (APH) and a volunteer programming instructor; a contributor to the Liblouis braille translation library (see [Liblouis](#liblouis)).
Profiles: [APH](https://www.aph.org/), [LinkedIn](https://www.linkedin.com/in/ken-perry-70637b5/).

#### [Graphiti](https://www.aph.org/) {#graphiti}
A refreshable tactile graphics display he leads at APH, presenting braille and images on a pin array.

#### Orion TI-84 Plus Talking Graphing Calculator {#orion-ti84}
An accessible, speech-enabled version of the TI-84 Plus graphing calculator.

### André Polykanine {#dev-polykanine}

Backend software engineer and accessibility specialist in Strasbourg, France, blind since birth; co-founder of Oire Software with his wife Nathalie, a longtime JAWS beta tester, and CTO of AccessMind, maker of the Optima braille laptop.
Profiles: [GitHub](https://github.com/Menelion), [Mastodon](https://dragonscave.space/@menelion), [Oire Software on GitHub](https://github.com/oire).

#### [SIC! (Simple Image Converter)](https://github.com/Oire/sic) {#sic}
A Windows image converter with batch conversion across eight formats, resize and crop, multi-size icon creation, a command-line mode, and signed automatic updates.

#### [Iridium](https://github.com/Oire/Iridium-php) {#iridium}
A PHP security library for encrypting data, hashing passwords, and managing secure tokens, installable via Composer.

### T. V. Raman {#dev-raman}

Computer scientist at Google and a pioneer of auditory user interfaces.
Profiles: [blog](https://emacspeak.blogspot.com/), [GitHub](https://github.com/tvraman), [home page](https://emacspeak.sourceforge.net/raman/), [Wikipedia](https://en.wikipedia.org/wiki/T._V._Raman).

#### [Emacspeak](https://github.com/tvraman/emacspeak) {#emacspeak}
The "Complete Audio Desktop," an actively maintained speech interface built on Emacs for Linux and other systems.
Wikipedia: [Emacspeak](https://en.wikipedia.org/wiki/Emacspeak)

### Derek Riemer {#dev-riemer}

Software engineer at Google who has written NVDA core code and a large set of add-ons.
Profiles: [GitHub](https://github.com/derekriemer), [LinkedIn](https://www.linkedin.com/in/derek-riemer-2a613082/).

#### [NVDA add-ons](https://github.com/derekriemer) {#riemer-addons}
Roughly two dozen NVDA add-ons plus contributions to NVDA core.

### Saqib Shaikh {#dev-shaikh}

Microsoft software engineer who founded and leads the Seeing AI project.
Profiles: [LinkedIn](https://www.linkedin.com/in/saqibshaikh).

#### [Seeing AI](https://apps.apple.com/us/app/seeing-ai/id999062298) {#seeing-ai}
A free app that narrates the visual world for blind and low-vision users, on iOS and Android.

### Tyler Spivey {#dev-spivey}

Developer of remote-access and console screen-reading tools.
Profiles: [GitHub](https://github.com/tspivey).

#### [NVDA Remote](https://github.com/NVDARemote/NVDARemote) {#nvda-remote}
An add-on, co-created with Christopher Toth, for controlling a remote computer with NVDA; it was folded into NVDA core in 2025.

#### [tdsr](https://github.com/tspivey/tdsr) {#tdsr}
A lightweight console screen reader for macOS and Linux terminals.

### James Teh {#dev-teh}

Known as "Jamie," he co-founded NV Access and is now an accessibility tech lead at Mozilla.
Profiles: [GitHub](https://github.com/jcsteh).

#### NVDA (co-founder) {#nvda-teh}
Co-created the NVDA screen reader; see the full entry under [NVDA](#nvda).

#### [OSARA](https://github.com/jcsteh/osara) {#osara}
Makes the REAPER digital-audio workstation accessible on Windows and macOS.

### Carter Temm {#dev-temm}

Accessibility consultant and software developer focused on AI-assisted tooling.
Profiles: [GitHub](https://github.com/cartertemm).

#### [AI Content Describer](https://github.com/cartertemm/AI-content-describer) {#ai-content-describer}
An NVDA add-on that uses AI to describe images and on-screen content.

### Christopher Toth {#dev-toth}

Known as "Q," he founded Accessible Apps / Q Software Solutions.
Profiles: [Accessible Apps](https://getaccessibleapps.com/), [GitHub](https://github.com/ctoth).

#### [CAPTCHA Be Gone](https://getaccessibleapps.com/) {#captcha-be-gone}
A service and browser integration that solves CAPTCHAs accessibly.

#### NVDA Remote (co-created) {#nvda-remote-toth}
Co-created NVDA Remote; see the full entry under [NVDA Remote](#nvda-remote).

#### [QRead](https://getaccessibleapps.com/) {#qread}
An accessible Windows e-reader for documents and books.

### Sam Tupy {#dev-tupy}

C++ developer focused on accessible games and game tooling.
Profiles: [GitHub](https://github.com/samtupy), [Website](https://samtupy.com/).

#### [NVGT](https://github.com/samtupy/nvgt) {#nvgt}
The NonVisual Gaming Toolkit, a cross-platform engine and scripting environment for building audio games.

#### [Survive the Wild](https://samtupy.com/) {#survive-the-wild}
A multiplayer survival audio game.

## Projects by Platform {#projects-by-platform}

Each project links back to its full entry above, ordered by title. Projects that span platforms appear in more than one group.

### Windows desktop applications
- [JAWS (Gordon)](#jaws)
- [LWorks audio games (Erven)](#lworks)
- [NVDA (Curran and Teh)](#nvda)
- [OSARA (Teh)](#osara)
- [Paperback (Gillespie)](#paperback)
- [QRead (Toth)](#qread)
- [Quill (Arndt)](#quill)
- [Remote Incident Manager (Campbell)](#rim)
- [RSSQuick (Ford)](#rssquick)
- [Sensor Readout (Louis)](#sensor-readout)
- [SIC! (Polykanine)](#sic)
- [Survive the Wild (Tupy)](#survive-the-wild)
- [System Access (Calvo)](#proj-system-access)
- [Zoom Accessible Meetings (Hartgen)](#zoom-meetings)

### macOS desktop applications
- [OSARA (Teh)](#osara)
- [Perspective Intelligence (Doise)](#perspective-intelligence)
- [Quill (Arndt)](#quill)
- [Remote Incident Manager (Campbell)](#rim)
- [tdsr (Spivey)](#tdsr)

### iOS apps (iPhone and iPad)
- [ACB Link (Doise)](#acb-link)
- [WeatherFast (Ford)](#weatherfast)
- [Perspective Intelligence (Doise)](#perspective-intelligence)
- [Seeing AI (Shaikh)](#seeing-ai)
- [VO Starter (Doise)](#vo-starter)

### Android apps
- [ACB Link (Doise)](#acb-link)
- [Seeing AI (Shaikh)](#seeing-ai)
- [VoiceView, on Fire tablets (Mulcahy)](#voiceview)

### Linux and cross-platform desktop
- [AccessKit (Campbell)](#accesskit)
- [BrailleBlaster (Boyer)](#brailleblaster)
- [Emacspeak (Raman)](#emacspeak)
- [NVGT (Tupy)](#nvgt)
- [tdsr (Spivey)](#tdsr)

### NVDA add-ons
- [Add-on Updater (Joseph Lee)](#addon-updater)
- [AI Content Describer (Temm)](#ai-content-describer)
- [BrowserNav (Malykh)](#browsernav)
- [NVDA add-ons (Riemer)](#riemer-addons)
- [NVDA Coach (Gebhard)](#nvda-coach)
- [NVDA Remote (Spivey and Toth)](#nvda-remote)
- [StationPlaylist (Joseph Lee)](#stationplaylist)
- [Tony's Enhancements (Malykh)](#tonys-enhancements)
- [Windows App Essentials (Joseph Lee)](#windows-app-essentials)

### JAWS scripts and extensions
- [BX scripting framework (Doug Lee)](#bx)
- [J-Say (Hartgen)](#jsay)
- [JAWS application scripts (Doug Lee)](#dlee-scripts)
- [Leasey (Hartgen)](#leasey)

### Alexa and smart-display screen reading
- [VoiceView, on Echo Show and Fire TV (Mulcahy)](#voiceview)

### Developer tools, libraries, and game engines
- [AccDC API (Garaventa)](#accdc)
- [AccDC Technical Style Guide (Garaventa)](#tsg)
- [accessibility-agents (Arndt and Bishop)](#accessibility-agents)
- [AccessKit (Campbell)](#accesskit)
- [Codestats (Gillespie)](#codestats)
- [extCheck (Mazrui)](#extcheck)
- [Image Description Toolkit (Ford)](#image-description-toolkit)
- [Iridium (Polykanine)](#iridium)
- [Liblouis (Boyer)](#liblouis)
- [NVGT (Tupy)](#nvgt)
- [urlCheck (Mazrui)](#urlcheck)
- [wx-accessible-webview (Arndt)](#wx-accessible-webview)

### Command-line tools
- [2htm (Mazrui)](#app-2htm)
- [Codestats (Gillespie)](#codestats)
- [extCheck (Mazrui)](#extcheck)
- [podfeed (Gillespie)](#podfeed)
- [tdsr (Spivey)](#tdsr)
- [TTCom (Doug Lee)](#ttcom)
- [urlCheck (Mazrui)](#urlcheck)

### Web services and online tools
- [CAPTCHA Be Gone (Toth)](#captcha-be-gone)
- [GLOW Accessibility Toolkit (Bishop)](#glow)

### Audio games
- [LWorks audio games (Erven)](#lworks)
- [Survive the Wild (Tupy)](#survive-the-wild)

### Document and authoring tools
- [2htm (Mazrui)](#app-2htm)
- [BrailleBlaster (Boyer)](#brailleblaster)
- [GLOW Accessibility Toolkit (Bishop)](#glow)
- [Image Description Toolkit (Ford)](#image-description-toolkit)
- [Paperback e-reader (Gillespie)](#paperback)
- [Quill (Arndt)](#quill)
- [QRead e-reader (Toth)](#qread)

### Hardware and tactile devices
- [Graphiti tactile display (Perry)](#graphiti)
- [Orion TI-84 Plus Talking Graphing Calculator (Perry)](#orion-ti84)

### Audio-production extensions (REAPER)
- [OSARA (Teh)](#osara)
