# Hacker's Web Toolbox

## Table of Contents

- [About](#about)
- [Purpose](#purpose)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>

This little gem has several parts.  Angular 11 GUI.  Python + GO with some Rust, maybe.

## Purpose: <a name = "purpose"></a>

(1). Build an intelligent Reverse-Proxy that gather's up all the JavaScript content from a site and presents it in an editable form to allow the user to make changes to the content that then interacts with the intended back-end.

(2).  This toolbox can be used to ensure your website cannot be hacked using this tool by making sure the Security Model does not depend on the state of the client which is typically a web browser and since most of the time your typical web browser cannot make changes to the JavaScript content without a good deal of effort, most lazy web developers just do not pay much attention to their Security Models and this can leave them open to this type of "hacking".

(3). IFF (If and Only If) the Security Model has been invested in the client (web browser) this tool may prove useful to allow the user to take-control over the web app such that the user should be able to gain access to certain parts of the web site that would have been denied otherwise.  Obviously this could prove to be a problem IFF the site has not been handled correctly.  For instance, IFF the site does not use "sessions" to store the idenity of the user once logged-in then this toolbox could be used to fake the login when no login has happened.  IFF the site uses sessions properly then no such access would be granted regardless of what may be done with the content.

(4). One sure tell that the site has their Security Model in the client alone would be if one can find content in the form of JavaScript that mentioned being logged-in, for instance, with the boolean flag appearing as a JavaScript variable or a cookie or something in local storage or in the DOM.  

(5). Single Page Applications might fall into the category of sites for which this toolbox may prove useful.  I have been told by certain web developers that there is no need to use sessions for SPAs because... well who knows but that conversation has kick-started my desire to prove whether that is true or false.

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## Usage <a name = "usage"></a>

Add notes about how to use the system.

(c). Copyright 2008-2020, Ray C Horn, All RIghts Reserved.