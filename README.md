**Status: DEV**

Declarative Core-Composed System Orchestration Template
=======================================================

An opinionated minimal primitive-component-based development and runtime system template for declarative front- and back-ends that deploys and automatically tests itself.

> Create stable static assets for deployment from your dynamic source logic.


Requirements
------------

  * NodeJS
  * OSX (only for now)
  * Heroku acccount


Install
-------

	git clone https://github.com/LogicCores/0.git myProject
	cd myProject

	nvm use 0.12
	npm install

	npm start

	// ... follow the prompts ...

	open http://0/


FAQ
===

### What is the scope of this project?

We are focusing on creating stable models for declarative development of distributed systems by validating them with minimal implementation in the form of a unified system template containig generic interface modules with adapters to popular domain-specific tool implementations.

The idea is that this system template is cloned many times and the systems built with it can provide feedback to refine the primitives that are needed as a foundation for all.

This project strictly focuses on minimal code and implementing *one* example of each *core* along with adapters using **NodeJS** as a backend and any JavaScript runtime as a front-end. It is left to other projects and communities to build on this foundation. It is anticipated that this foundation is continuously refined to reflect the advances made in derivative and alternative works in an effort to build and maintain compatibility.

### What is `PINF.Genesis.json`?

[PINF.Genesis](https://github.com/pinf/genesis.pinf.org) is a *Declarative Web Software Systems Domain Model and Manifestation Platform*.

This *Declarative Core-Composed System Template* is a crystalization of core primitives from the *PINF.Genesis* platform and will be leveraged within the *PINF.Genesis* platform to ready it for general use over time.

We do not **use** *PINF.Genesis* in this template but are *implementing one model* of the *PINF.Genesis approach* using minimal implementation and targeting it to **NodeJS** and **JavaScript** specifically. Whatever we do here will be compatible with the **much wider scoped** *PINF.Genesis* platform which targets many runtimes and languages when it is released for general use.