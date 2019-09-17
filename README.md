# Self-Paced Project: Snake

## Overview
This game was created using canvas as an opportunity to understand the basic principles and practice javascript. The repo can be accessed on [GitHub](https://github.com/Iamshola/snake) and the deployed site can be viewed on [Gh-Pages](https://iamshola.github.io/snake/).

### Languages and Technologies Used:
* HTML5
* CSS3
* JavaScript (ES6)
* Git
* GitHub
* Google Fonts

### Timeframe:
2 days


### Snippet of Code

#### Collision Check

``` javascript
this.checkCollision = function() {
  for (var i=0; i<this.tail.length; i++) {
    if (this.x === this.tail[i].x &&
      this.y === this.tail[i].y) {
      this.total = 0
      this.tail = []
    }
  }
}
```

#### Movement of Snake
``` javascript
this.changeDirection = function(direction) {
  switch(direction) {
    case 'Up':
      this.xSpeed = 0
      this.ySpeed = -scale * 1
      break
    case 'Down':
      this.xSpeed = 0
      this.ySpeed = scale * 1
      break
    case 'Left':
      this.xSpeed = -scale * 1
      this.ySpeed = 0
      break
    case 'Right':
      this.xSpeed = scale * 1
      this.ySpeed = 0
      break
  }
}

```

### Course Curriculum
  Details of my training and links to more projects whilst at General Assembly -  12 Week Immersive.

> **Week 1-3 | Module One - Fundamentals**

  - HTML5
  - CSS3
  - Sass
  - JavaScript


> **Week 4**

  Project 1 : Frogger  | [GitHub](https://github.com/Iamshola/project-01) | [GH-Pages](https://iamshola.github.io/project-01/)

>**Week 5 | Module Two - React**

  - React.js
  - Routing
  - RESTFUL API
  - Third-party APIs

>**Week 6**

  Project 2 : CocktailBored  | [GitHub](https://github.com/Iamshola/Project3) | [GH-Pages](https://iamshola.github.io/Project-2/#/)

>**Week 7-8 | Module Three - Node and Express**

  - RESTFUL Routing
  - Node.js
  - Express
  - Token Authentication & Session Authentication
  - API Creation
  - Mocha and Chai

>**Week 9**

  Project 3 : Date-a-base | [GitHub](https://github.com/Iamshola/Project3) | [Herouku](https://datingexp.herokuapp.com/#/)

>**Week 10-11 | Module Four - Python and Django**

  - Python
  - SQL
  - Django
  - Token Authentication

>**Week 12**

  Project 4 : Space | [GitHub](https://github.com/Iamshola/project-04) | [Herouku](https://date-a-base-aos.herokuapp.com/#/)


  ### Contact
  Adesola Oni-Shogbonyo\
  Email : s.oni-shogbonyo@hotmail.co.uk\
  [Portfolio](https://iamshola.github.io/) | [Linkedin](https://www.linkedin.com/in/adesola-oni-shogbonyo/) | [GitHub](https://github.com/Iamshola)
