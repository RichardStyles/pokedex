Single page API Test
===

Important
---
This project will be based on your ability to create a frontend matching the design criteria, for a web based encyclopedia based on the popular franchise Pokémon - also known as a Pokédex 


Instructions
---
This is a fairly basic front-end piece to give us a general idea of where you are as a developer. 
We don't expect you to spend several days creating a fully finished page, but try and spend a few hours on it and 
see how far you can get. If you're short on time we'd like to see the API interaction and search ability, rather than 
the whole page being rushed. You should use it to demonstrate the following:

- Version control: Ideally you will fork from this repo and provide us a link to your new repo containing the finished files.
- Basic task runner workflow: There are instructions below for getting going in this very basic gulp project, but you should be comfortable using Gulp to compile SCSS and concatenate JS.
- Javascript: This design presents a couple of opportunities to use JS. Using the Javascript framework of choice to connect to the API and show the resulting data.
- SCSS: Make the most of the added functionality SCSS brings to the table.
- Responsive: Don't worry about coding for every possible device. All we ask is that it looks ok on screens larger than 1024px and smaller than 500px (Just desktop and mobile). 
We have included an example for a responsive behaviour in the design folder.
- Keen eye for detail: Your main priority here should be pixel perfect/close reproduction of the design in the PDF.
- Clean, readable code

Requirements
---

There should be;
- A paginated list of pokemon on the left hand side of the page, as shown in the design.
- A search box, which can be used to search for a pokemon. This should at least be complete match, but can be improved using fuzzy search.
- The results of the search, should be displayed below the search box. If more than one pokemon are returned in the results then these should be listed 
in the style shown in the design.

A RESTful API is available at [Pokéapi](https://pokeapi.co/) which will provide you with all the data that you will need. You do not need to create
an account nor authenticate in order to consume the API, however please be aware that this API is rate-limited.

Resources
---

This repo contains the follow resources you'll need to complete the task:

- Design: The one page design is available in PDF and PNG format in the design folder.
- SCSS Framework: We have incuded a basic gulp file which you can use but we are interested to see your choice of 
style framework, feel free to pick any that you want which allows you to match the design. 
- Images: The image urls of each Pokémon are included in the API response. 
- Fonts: This design uses Open Sans, which has already been included via their respective CDN's in the <head>.

Installation
---

1. Clone repo
2. Run npm install to install dependencies.


Build
---

Depending on your methodology and the Javascript framework (if any) that you choose to use. Please define how this webpage should be compiled.
i.e. using `gulp`

Submission
---
To submit your solution, please fork this repository and provide us a link to your finished version.

Copyright
---
All trademarks as the property of their respective owners.
