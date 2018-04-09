---
layout: post
title: EasyMock 3.6 is out!
date: '2018-04-08T00:00:00.000-05:00'
author: Henri Tremblay
tags:
- Projects
---

This release adds a better support to Java 9 and Java 10 and fixes an issue for interface default methods.

Release notes
-------------
* Java 10 support through an update of ASM and cglib
* Add Java 9 automodule
* Allow mocking interface default methods on a partial mock

Change log
----------
* Add Java 9 automodule ([#212](https://github.com/easymock/easymock/issues/212))
* Update asm, cglib and surefire for Java 10 support ([#211](https://github.com/easymock/easymock/pull/211))
* Mocking interface default methods ([#203](https://github.com/easymock/easymock/issues/203))
