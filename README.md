# Tamara Wells • Fluid Worlds

Fluid Worlds is for art lovers who enjoy seeking out the novel and unconventional in art. A particular target of the site are purchasers of art, frequent or infrequent, who may be looking for something attention grabbing to hang on their wall. A better feel for the art can often be gained from knowing a little more about the person who made it, and so an aim of the site is to help reveal the art through the artist.

## Features 

#### index.html
The landing page takes you straight into the art with a gallery display showcasing the range of Tamara's work. No eye-catching ‘hero’ image necessary here as the art should speak entirely for itself. Each painting has a description of the medium and type of support used, as well as the metric dimensions of that support. Each image will increase in size as the viewport increases in size, while also ensuring the images never get too big; this is art that has its greatest effect at a distance.

#### about.html
The about page should give a sense of the person who produced the art, but while perhaps also preserving something of the mystique of the artist.

#### contact.html
And so for those who have truly connected with what they've seen, their further interest can be registered here, and by submitting an email address they can be kept informed of future exhibitions. The form also serves as a means of expressing a possible interest in buying some of the art

### Existing Features

- __Navigation Bar__

  - It's the same on all three pages, and by design as the consistency aids the user with a familiar method of navigating the site.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

- __The Footer__ 

  - The footer section is just a series of links to the relevant social network sites. The links open to a new tab to allow easy navigation for the user. 
  - The footer is has value as it allows the user to connect to the artist on other social networks and gain a different insight into the artist behind the art.

### Features Left to Implement

- The ability to enlarge each image. This is a standard capability of art websites and by not having it the user's expections are at risk of being frustrated. Nevertheless, how much zooming should be permitted needs consideration. As noted, ‘too much’ is very possible and may only serve to weaken the overall impression of the art.
- The ability to make online purchases of the art would be a great feature to implement. People like it. People expect it.

## Testing

- How the pages cope at different screen sizes formed the bulk of the testing, and in any case took up the bulk of the time in coding too.

### Browsers
- Chrome
- Firefox
- Qutebrowswer
- Nyxt

#### Issues

- **Chrome**: The `header` element would move a few pixels and then back again when navigating between pages. However, it would only do so inconsistently; perhaps 25% of the time. I couldn't track down the cause of this either. All other browsers were perfectly fine, but Chrome has the highest number of users so it requires further investigation.

### Validator Testing 

- HTML
  - Errors were initially found when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwymmij.github.io%2Fci-portfolio-project1%2Findex.html) 
    These were closing forward slashes on img tags that the beautifier had added.
- CSS
  - Errors were initially found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fwymmij.github.io%2Fci-portfolio-project1%2Findex.html)
    The error was from a property/value pair supplied by Google fonts. `font-size-adjust: auto;` but apparently auto is not recognized as a permissible value. After reading about the property correctly, I removed the pair since it wasn't necessary for my usage.
- All errors were corrected and re-validation was successful in both cases.

### Unfixed Bugs

None I'm aware of.

## Deployment

Initially, I deployed the site on my local machine and ran on an `apache` server while I played around with a few ideas.

Later I deployed the site using **GitHub Pages**: [https://wymmij.github.io/ci-portfolio-project1/index.html](https://wymmij.github.io/ci-portfolio-project1/index.html)

- The steps to deploy are as follows: 
  - On the GitHub repository, go to the Settings tab 
  - Select ‘Pages’ on the menu on the left under ‘Code and automation’
  - Make sure the ‘main’ branch is selected and that the /(root) folder is also selected
  - Deployment should take a few minutes or so. 

## Credits 

- Generally, I consulted the references page on [W3Schools](https://www.w3schools.com/) extensively
- I also worked my way through ‘CSS in Depth’ by Keith J. Grant, published by Manning and now in its 2nd edition. In particular Chapter 4 on Flexbox.
- I adapted the ‘Hamburger Menu’ example from the ‘Love Running’ project to use in my project. 

### Content 

- The main text on the About page was used with permission from both the artist and the author, Mathias Beck. 
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)

### Media

- All images were provided by the artist.
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The favicon was converted from one of the artist's images. I used the website [favicon.io](https://favicon.io/favicon-converter/) to do the conversion.