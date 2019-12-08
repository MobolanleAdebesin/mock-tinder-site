# Project One
### Description 
- This project focuses on recreating a popular dating app website homepage using the fundamentals of HTML and CSS. 
- As the life cycle of this project began with the development of a wireframe based on the layout of the original site, it demonstrates my ability to design a mobile-first responsive webpage from start to finish. 

### Examples
![screenshot](https://github.com/MobolanleAdebesin/mock-tinder-site/blob/master/Desktop%20Version%20Tinder%20Image%20Grab.png)

![screenshot](https://github.com/MobolanleAdebesin/mock-tinder-site/blob/master/Mobile%20Version%20Tinder%20Image%20Grab.png)

This project was completed using a combination of fundamental HTML and CSS3 such as flexbox, grid, media queries, and keyframes 
``` css 
@keyframes colorChange{
  0% {background-image: linear-gradient( to right, ##E9D840,#FD95E1, #6D4CDE);}
  25% {background-image: linear-gradient( to right, #FD95E1,#50BCF3,#E9D840);}
  50% {background-image: linear-gradient( to right, #0AFFB3,#50BCF3, #FD95E1);}
  100% {background-image: linear-gradient( to right, ##E9D840,#FD95E1, #6D4CDE);}
}

@media screen and (max-width: 576px){
body{
  font-size: 16px;
  grid-template-rows: 6.25rem 1fr 3rem;
}
header{
  display: flex;
  align-items: center;

  }
  
  body{
  display: grid;
  grid-template-rows: 6.25rem 1fr 6.25rem;
  grid-template-columns: 25vw 25vw 25vw 25vw;
  margin: 0;
  font-family: 'Montserrat', sans-serif;
}
header{
  /* background-color: pink; */
  grid-row: 1 / span 1;
  grid-column: 1 / span 4;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}
```

### Technologies 
- HTML 
- CSS 

### Getting Started 
1. Fork and clone the [project repository](https://github.com/MobolanleAdebesin/MobolanleAdebesin.github.io)

### Contribute 
Source code: https://github.com/MobolanleAdebesin/MobolanleAdebesin.github.io

Issue Tracker: https://github.com/MobolanleAdebesin/MobolanleAdebesin.github.io/issues
