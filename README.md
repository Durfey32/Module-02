# Portfolio

In this project we created a resposive portfolio for future employers to view our work. 

## Description

The goal of this project was to creat the HTML and link the CSS to creat a funtional portfolio. To do this I started by creating an HTML with the bones and link the CSS page to it using the provided CSS style sheet. Once the HTML was successfully link I then needed to add the responsive elements if the page were to be resized. This was accomplished by using the Media query feature to have the page respond if the page was lower than 768px. We also need to add funtional links along with at least 5 images. 

## Code Refactor Example

```css
@media screen and (min-width: 980px) {
  .flex-item,.page-section,.hero-banner {
    flex-direction: inline;
    max-width: 100%;
    padding: 2%;
  }
}
@media screen and (max-width: 768px) {
  nav {
    flex-direction: column;
  }
  .page-section, .hero-banner, .flex-item{
    flex-direction: column;
    align-items: center;
    max-height: fit-content;
    padding: 2%
  }
}
```

This is an image of a page at 980px
![alt text](<assets/css/980px screen shot.png>)
This is an image that is less than 768px
![alt text](<assets/css/768px screen shot.png>)

## Learning Points

In this project I was able to dive deeper into the way CSS works with HTML and link properties to see different effects. The most challenging aspect for me was creating the responsive media querries to the page. I was able to master it in the end to have it look the way I wanted it to. Currently there are only two funtional pages that are successfully linked to the page, in the future I hope to add many more. 

# Thank you

### Spencer Durfey 

* [email] durfey_32@yahoo.com
* [GitHub] https://github.com/Durfey32
* [LinkedIn] www.linkedin.com/in/spencer-durfey-636579256
