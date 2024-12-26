# Frontend Mentor - Intro component with sign up form solution

This is a solution to the [Intro component with sign up form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - Any `input` field is empty. The message for this error should say *"[Field Name] cannot be empty"*
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Looks like this is not an email"*

### Screenshot

![Desktop version](./screenshotDesktop.png)
![Mobile version](./screenshotMobile.png)

### Links

- Solution URL: [https://github.com/toshirokubota/intro-component-with-signup-form](https://github.com/toshirokubota/intro-component-with-signup-form)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I was able to use Flexbox at multiple levels (some elements being a flex item and a flex container at the same time).

I was able to customize the form validation, except the email input. I could not override the built-in validation 
for the email input so that the custome validation responds to 'email@example/com' example shown in one of design files. I
could make the custom validation responds with 'email@a.a', however.

I was able to place an icon inside the input text book. I made a container relatively positioned and the icon absolutely
positioned (thanks to a Stackoverflow article). I am still not quite sure why the container has to be relatively positioned...


### Continued development

I want to continue learning how to position elements in a clean manner. I think I am getting better at but there are still 
many questions and I often rely on trial and error.

I am still uncomfortable with mobile first approach; I feel it is easier to design the destkop first and tweak the code 
with media query to adjust to mobile devices. In previous project, I did the other way around, and felt it was more difficult.
I trust the opinions of more experienced people and want to do the coding in the mobile first fashion.

I want to get more comfortable with traversing DOM programmatically and manipulate it. I still need a lot of looking up on the
web to find the solution. 
