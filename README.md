# **Y**et **A**nother **A**ddress **S**hortener

Another URL shortener, because why not?

## Overview

While looking around and reading various tech blogs and articles, I came across [this article by Sandeep Verma](https://medium.com/@sandeep4.verma/system-design-scalable-url-shortener-service-like-tinyurl-106f30f23a82) which goes into detail about how some of the system design decisions that need to be made when building a URL shortener service.

A simple, single instance, short lived URL shortener is pretty trivial to implement, but a scalable, reliable service that can handle a large volume of requests and never expires URLs is more of a challenge that I wanted to implement.

So this project is somewhat my attempt at implementing a URL shortener service that meets the requirements outlined in the article, but I will also be making some decisions for my own learning and exploration along the way. I'm also just a guy with a job and a family, so I don't have a lot of time to work on this and will not be investing such amounts of resources into this to test it to the limits (with TBs of URL data and millions of requests per second).

## Design

Diagrams for the system can be found in [diagrams.md](diagrams.md) and [board.excalidraw](board.excalidraw). I use both because I like diagrams as code, but it can be limiting and tedious sometimes, so a simple drawing tool is also useful.
