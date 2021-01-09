---
layout: post
title: Spencr
landing-title: 'Spencr'
nav-menu: false
show_tile: true
description: Simple URL shortener allowing you to quickly create URL shortcodes.
---
Github Page: [https://github.com/sbmercury/spencr](https://github.com/sbmercury/spencr)


Spencr is a simple URL shortener, enter a shortcode and URL and it will 
create a shortcode on spencr.me for that URL.  
You can go to https://spencr.me to try it out.
## Features

- Quickly add new codes and have the short URL added to your clipboard 
immediately after submitting


- Simple redirects for shortcodes that have been added


## Installation

#### Linux

- Install packages

`npm install`

- Set environment variables

`process.env.PORT: sets what port the app will run on (default 8070)`   
`process.env.DATABASE: a mongoDB connection URL, used to store codes and associated URLs`


- Start the app

`npm start`


