# Milik.css

Milik is a classless CSS library. This means, you styling is done directly on HTML tag level, without requiring you to add additional classes to an element. This enables you to write clean HTML document and style it at the same time.

## Goal

The goal of this library is to have sets of themeable CSS that you can directly use inside your HTML file. I find the Design Token approach for Design System is something very inspiring and I think I can follow its method here as well.  The ideal experience of using Milik would be:

1. Write Design Token(s)
2. Build Token into milik.css
3. Use Milik.css
4. Profit?

## Use Cases

I think this approach would be very good for a site that's pretty small in terms of visual complexity, with styling that can be directly implemented using just HTML elements with minimal variation between them (it's going to be hard if you have a lot of divs with same content but has visual variation between them). Some good examples are:

- Blog
- Documentation page
- Single Page Website
- Quick website prototype

## Roadmap

This year, I'm aiming to realease an early version of the library that can be used by a lot of people. Industry standard practice such as Responsive Design and Accessibility should all be embodied on the release version. I've yet to choose an appropriate build tool for this, but looking forward to tinker with either Snowpack or Rollup.

## Motivation

I'm writing this library as an effort of writing minimal website. If I can style it directly in HTML, without using additional classes, I think, maintaining the website would be a lot better experience. Also, I think I need a strong refreshment in a lot of new HTML tags, so forcing myself to write just that (plus some CSS), would be a great practice.

## Library State

As it stands, this is still under heavy development, so expect major changes.

## Who Made This?

This library is written by me, Adityo Pratomo. I'm currrently working as a UX designer for Tetrate.