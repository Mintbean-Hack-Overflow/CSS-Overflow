# MintBean - Build Your Own Bootstrap Hackathon
This is a project created within Mintbean's hackathon. The goal is to create a landing page and a css library.

# Installation
```
npm install mintbean-byob-test2 --save
```
# Import 
After installation, you can import the CSS file into your project with this snippet

```
@import 'mintbean-byob-test2/css/index.css'

```
## Flex-box shortcuts
Some easy shortcuts you can use with flexbox if you don't want to touch the css files
* .flex => *display: flex;*  
* .j-center => *justify-content: center;*  
* .j-start => *justify-content: start;*  
* .j-end => **justify-content: flex-end;*  
* .j-between => *justify-content: space-between;*  
* .j-around => *justify-content: space-around;*  
* .j-evenly => *justify-content: space-evenly;*  
  
* .i-start => *align-items: flex-start;*  
* .i-end => *align-items: flex-end;*  
* .i-center => *align-items: center;*  
* .i-baseline => *align-items: baseline;*  
* .i-stretch => *align-items: stretch;*  



## Cards 
We've created a some sample cards for you to play with.

* .card-sm : represents a small card. The width and padding could be changed by adjusting the $padding-sm and $width-sm scss variables
  ![image]("https://user-images.githubusercontent.com/64132738/111579698-74cda880-8784-11eb-9e14-74f996e10e95.png") 

* .card-md  : represents a medium card. The width and padding could be changed by adjusting the $padding-md and $width-md scss variables
  ![image]("https://user-images.githubusercontent.com/64132738/111579751-9038b380-8784-11eb-9475-05eceb546c06.png")

* .card-lg : represents a large card. The width and padding could be changed by adjusting the $padding-lg and $width-lg scss variables
  ![image]("https://user-images.githubusercontent.com/64132738/111579834-b52d2680-8784-11eb-8aa2-5dedc030f8cd.png")

* .profile-card : an out of the box profile card for your personal usage. The padding utlizeds the $padding-md. The margin uses the $margin-sm and the width uses the $width-sm. You can cutomize the colors by changing up the $primary, $secondary and $alternate variables.
  ![image]("https://user-images.githubusercontent.com/64132738/111579264-b7db4c00-8783-11eb-9e09-5fadf5715e8c.png")

** Upon hover
  ![image]("https://user-images.githubusercontent.com/64132738/111579457-0c7ec700-8784-11eb-9a49-eca185a20609.png")
## Contributors
- Chris DiPiero
- Khuong Le 