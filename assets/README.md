# Code Refactor

    The purpose of the following will be to improve on the the current codebase, making it more accessable for users 
with disabilites or socio-economic restrictions, as well as organizing the overall semantic strucute of the html 
and css. All edits made have been noted with in-code citations.

## Method

Inorder to champion accesability in the HTML and CSS code I was given by Horiseon Social Solution Services, Inc I will be implementing several tactics. First adding alt tags to all images so those with visual impairments or those without access to proper internet services can still gleen information from the site. Next I will be centering the text under 'Lead Generation', 'Brand Awareness' and 'Cost Management' as well as changing the text color to black and outlining it to make it easier to read. Lastly I will be fixing the webpage size to fit the window width. 

## Tools Used

* HTML
* CSS
* GitHub
* VS Code 
* Google

## Code Snippet 

- HTML 
 <p class="ridge">As the search ranking for your business increases, 
your advertising costs decrease, and you no longer need to advertise your page.</p>

- CSS 
/*centered text*/
div.benefit-lead {
    text-align: center;
}
/*centered text*/
div.benefit-brand {
    text-align: center;
}
/*centered text*/
div.benefit-cost {
    text-align: center;
}
/*added double border around footer*/
p.double {
    border-style: double;
}
/*added a ridge border around the text*/
p.ridge {
    border-style: ridge;
}
/*Fixing the sites window size*/
.Container {
    width: 90%;
    min-width: 500px;
    margin: auto;
}

## Screenshots
<img
scr="![image](https://user-images.githubusercontent.com/65733607/84339102-8ed1bf00-ab52-11ea-80e3-76289a39f6bc.png)" alt="screenshot-of-how-I-centered-text-with-css"
>

<img 
scr="![image](https://user-images.githubusercontent.com/65733607/84399591-e35a5600-abb5-11ea-8707-85d3f797f0f9.png)"
alt="screenshot-before"
>

<img
scr="![image](https://user-images.githubusercontent.com/65733607/84401499-31705900-abb8-11ea-983b-c3ea1a7f0764.png)"
alt="screenshot-after-I-changed-the-text-color-and-added-a-border"
>

## Authors
    Ayla Dillis in collaboration with Horiseon Social Solution Services, Inc. 
* [Linkedin](https://www.linkedin.com/in/ayladillis/)
* [GitHub] (https://github.com/ayladillis)
* [Portfolio] (Coming soon)

### Acknowledgments 

* Berkeley Full Stack Bootcamp instructors Jerome Chenette and Manuel Nunes
* GitHub and GitLab 
* [w3school.com] (https://www.w3schools.com/) 
* Horiseon Social Solution Services, Inc.