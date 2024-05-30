---
layout: post
title:  "Observing With NASA."
date:   2022-07-15
categories: [ "Creating with Software" ]
tags: [ nasa, software, technology, javascript, electron, astronomy ]
---

Created an Electron-bassed kiosk application for [RLMG](https://rlmg.com) and
the [Center for Astrophysics: Harvard & Smithsonian](https://cfa.harvard.edu)
to allow science museum visitors to investigate and maniupulate astronomical
images taken by a wide range of NASA telescopes telescopes and observatories.

The visitor also has the capability to have copies of the astronomical images
they modify sent to them via email. In addiotion visitors can select from a
number of astronomical objects and schedule an observation from one of the
telescopes in the
[MicroObservatory Robotic Telescope Network](https://mo-www.cfa.harvard.edu/MicroObservatory/).

![MicroObservatory]({{site.url}}/assets/images/cfa/micro-observatory.jpg)

When deployed to a science museum the application displays on a
large touchscreen integrated into a kiosk.

While the Electron app is compiled and distributed as native application
on both MacOS and Windows the structure of the development environment I put
together also deploys a web version that is updated everytime a commit
is pushed to github.

[Observing With NASA](https://stepheneb.github.io/cfa-own-electron-gh-pages/) NOTE: main repository now private.

[Observing With NASA]https://stepheneb.github.io/cfa-own-electron-gh-pages/

### Application User Interface Elements

- **Splash Page** the application layout is optimized for display at 1920x1080.
  For development purposes a fading information box is temporarily displayed
  on startup and whenever the window is resized.
  ![Name]({{site.url}}/assets/images/cfa/cfa-opening-screen.jpg)

- **Main menu**
  ![Name]({{site.url}}/assets/images/cfa/cfa-main-menu.jpg)

- **Find the Apollo Site**
  ![Name]({{site.url}}/assets/images/cfa/cfa-find-apollo-menu.jpg)

- Zoom in on where the Apollo 17 mission lander touched down on the moon.
  ![Name]({{site.url}}/assets/images/cfa/cfa-find-apollo-17.jpg)

- **Create Your Own Masterpiece**
  ![Name]({{site.url}}/assets/images/cfa/cfa-make-masterpiece-menu.jpg)

- Choose from a variety of filters and effects to transform the Whirlpool
  galaxy image.
  ![Name]({{site.url}}/assets/images/cfa/cfa-make-masterpiece-whirlpool.jpg)

- **Animate Images Over Time**.
  ![Name]({{site.url}}/assets/images/cfa/cfa-animate-images-menu.jpg)

- Animate through 10 separate images of UV light from the Sun..
  ![Name]({{site.url}}/assets/images/cfa/cfa-animate-images-solar-uv.jpg)

- **What's Red + Green + Blue**
  ![Name]({{site.url}}/assets/images/cfa/cfa-rgb-menu.jpg)

- Cosmic Reef Nebula
  ![Name]({{site.url}}/assets/images/cfa/cfa-rgb-cosmic-reef.jpg)

- **Invisible Light**
  ![Name]({{site.url}}/assets/images/cfa/cfa-invisible-light-menu.jpg)

- Combine separate infrared, visible and UV images of the whirlpool Galaxy into
  a visible image mapped to red, green, and blue.
  ![Name]({{site.url}}/assets/images/cfa/cfa-invisible-light-whirlpool.jpg)

- **Take Your Own Telescope Image**
  ![Name]({{site.url}}/assets/images/cfa/cfa-make-observation-menu.jpg)

- Request an observation of the Whirlpool Galaxy from a MicroObservatory
  telescope.
  ![Name]({{site.url}}/assets/images/cfa/cfa-make-observation-cigar.jpg)
