BUILDING AN ANIMATED SLIDER
1. embed the necessary css and javascript files.
2. Set up the header and menu
3. import fonts to be used in the project, this will be placed at the top of the css stylesheet
4. the poppins font will be used for the entire body of the site
5. in this design, there's a white line that divides the page into two unequal parts, one question we're trying to solve is: how would we know the ratio we want
6. well since each product image has a width of 500px, then the space will be (500px(an image) * 3)/2, meaning we're going to make space for 3 images and divide that space into 2. That number is 750px, so essentially we will allocate 750px for that space("which is the right side of the page")
7. Set up the global variables needed inside the ":root" object, we do this instead of setting the attribute for element because when we make it responsive these values will change to suit the screens of those devices. when using variables it's convenient because you just need to change the values of the variables there
8. to set up the header element, we'll use grid to divide the columns
9. now implement the slider, create a section tag where the carrousel class contains the
entire slider content
10. create all the various elements for the description and slider
11. next manually add a couple of images and set up their code
12. in our design, the item at the center of the frame will be called active item and also because the animation effect occurs with the surrounding items, the surrounding items will be marked other_1 and other_2
13. a slider always includes two states, the first is the next state, so enter the html in slider active state, and set it to recognize that between the active state is other_1 and other_2
