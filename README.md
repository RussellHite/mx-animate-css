# mx-animate-css
Animate.css file converted for use in Mendix
https://daneden.github.io/animate.css/

## Prerequisites
For easiest implementation of this or any other icon font it is reccomended you install the Vanilla theme when you start to style your applicaton.
https://appstore.home.mendix.com/link/app/2681/Mendix/Vanilla-Theme

## Configuration
Here are the steps to incorporate this file into your project. 


### Step 1
Copy and paste the _animate.scss file into the following folder your_project_folder/theme/styles/sass/lib/components
### Step 2
Open the lib.scss file under your_project_folder/theme/styles/sass and under the bottom add the following line:
```
@import "components/animate";
```
to include the _animate.scss file partial into the outputed css file

## Basic usage
The Animate classes are best used when you want to animate elements in or out from the screen. Below are some quick instructions on how to use them on your project.   

1. Add the class `animated` to the element you want to animate. You may also want to include the class
`infinite` for an infinite loop.  
2. You will also need to add one a class like `bounce` to define how ypu want the element to animate

For more details on how to use the classes included, check out:
https://github.com/daneden/animate.css