# Cyborgui - an open-source graphical user interface library

Cyborgui lets you build beautiful applications that work across all operating system and languages. It exposes a sensible DSL for writing your applications in and is based on the new Enlightenment Foundantion Libraries. Each host language has their own language bindings.

## Use Cases

* We need a gui that'll serve for our prototype. We select a good prototyping language say Python.

* Once the prototype is proven, we may swap out our backend for something more resilient say Erlang.

* Certain parts of our application require high throughput so we swap that section out with the JVM.

* Each part of the application using a different language talks to the same front facing view.

* Each language has its own language bindings to libcgui.so.

* Handlers, written in your chosen language, are executed by a callback mechanism, when a gui widget signals an event.

## Project Vision

Cyborgui will run on everything that speaks TCP/IP and about 8 megs memory and up.

## Project Organization

libcgui.so is written in C++, abstracting out the Enlightenment Foundation Libraries. For more information please refer to [Cyborg's site](http://cyborgos.org) also take a look at [enlightenment](http://enlightenment.org)

## Who owns Cyborgui?

Cyborgui is owned by all its authors and contributors. This is an open source project licensed under the LGPLv3. To contribute to Cyborgui please read the [C4 process](http://rfc.zeromq.org/spec:16) that we use.