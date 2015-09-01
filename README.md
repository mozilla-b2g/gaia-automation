Gaia Automation
===============

### Mission

The Gaia Automation team takes responsibility for issues at the
intersection of Firefox OS and automation. We aim to make it easy for
developers of the FxOS system frontend and core FxOS apps to

1. use external code,
2. build gecko profiles for different scenarios (dev, test, prod),
3. and test their code with unit and UI tests.

You can expect our group to ensure that Gu and Gij can be run by
developers locally and by taskcluster continuously.

### Plan for 2015 (Q3 + Q4)

+ ~~[confidant](https://github.com/gaye/confidant)~~
+ confidant builds gaia
+ [exhibition](https://github.com/lightsofapollo/exhibition)
+ Get test configuration into the gaia tree
+ Code coverage dashboard across test suites
+ Gij on devices
+ Stabilize Gij

### Things We Do (Present)

+ Maintain and improve test frameworks and utilities used by Firefox OS
  developers including harnesses for running marionette tests and unit
  tests,
+ support developers who want to write and run tests,
+ and maintain our taskcluster/ci setup.

### Things We Want To Do (Future)

+ Help developers decouple the different, package-level units that live
  in the gaia repo into independent entities,
+ maintain and improve tooling for building the system frontend, core
  apps, and shared libraries,
+ and provide a code coverage dashboard.

### Things We Don't/Won't Do

+ Write or maintain tests for individual applications,
+ Write library-level test code (including mocks for platform apis),
+ maintain individual build configurations,
+ and sheriff the tests on ci (responsibility delegated to whomever broke
  the build).

We're excited to help everyone improve FxOS quality and maintainability!
Our team is  _very_ small right now, but we want to provide mentorship
and guidance to FxOS developers (especially those motivated to
contribute to build and test issues) who approach us respectfully. You
know, more honey, less vinegar :).
