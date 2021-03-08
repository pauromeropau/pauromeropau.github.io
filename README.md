# CARTO Annual Conference 

👉🏻 [Demo here](pauromeropau.github.io )

## About
### CARTO Annual Conference
_We're preparing our annual conference. For this conference, we've decided to create a new landing page that will keep all the information of the event and past events._

## Tech Stack 
This landing page has been developed using *Jekyll* (Static Site Generator) and *SCSS*. Also *Figma* and *Zeplin*.

## Development
Principles of Software Engineering (KISS, DRY & SOLID) has been followed:<br> 
**1. KISS** - _"Keep it simple, Stupid!"_ <br>
**2. DRY** - _"Don't Repeat Yourself"_<br>
**3. SOLID** - Easy to maintain and extend over time. <br>

## Design
A mockup has been given as style guide.

### Responsive/Mobile First
This landing page is also Responsive. 

### Colors 
It's been used CARTO brand palette: 
- Location Red #EB1510 
- Navy Blue #162745 
- Prediction Blue #1785FB 

### Animation
Some animations hover has been config.

## Development Environment
- To set up your environment to develop  run 
```
bundle install
```

- To test run 
```
bundle exec jekyll serve --incremental --livereload
```
and open your browser at 
```
http://localhost:4000
```

## Build
If you want to build (./_site) run 
```
jekyll build --watch
```

## Add new content
*How can non-technical people add new content to the site?* Easy. <br>
Front Matter. 
The front matter must be the first thing in the file and must take the form of valid YAML set between triple-dashed lines. Something like...  

```
---
layout: home
title: Carto Annual Conference
---
``` 

you can use them wherever you want (e.g such as {{ page.title }}). That's what makes Jekyll so easy to maintain for non-technical people :)

You can also set more variables on the *_config.yml* file (e.g twitter username) and use them everywhere. 

## Live Demo
Visit pauromeropau.github.io 

## Author
👩🏼‍💻 Paula Romero <br>
👤 [LinkedIn](https://www.linkedin.com/in/pauromeropau/) <br>
📩 pauromeropau@gmail.com <br>
📍 Madrid, Spain <br>




