


|Technology|Why|How|
|:-:|:--:|:--:|
|Variables|We will use variables so that we can change a specific value that was used more than once. We will use a variable for fonts, colors, and breakpoints.|Inside of the abstracts/_variables.scss file, "$variable-name: value;" will be added. Then in the code where a value belongs "$variables-name" is inserted (Make sure files are imported).|
|Mixins|We will use mixins so we do not have to repeat groups of css properties and so we can change them all at once. Mixins will be used for our rows.|Inside of the abstracts/_mixins.scss file add @mixin followed by the name of the mixin. A block containing the content of the mixin is then inserted.|
|Media Queries|We will use media queries so we can restyle the website based on the user screen width.|In the folder that is being worked on add "@media screen and (max-width:pixel-count)or(min-width:pixel-count){}". Inside of the curly brackets add the code you want for that screen size.|
|For loop|--|--|
|partials|We will use partials to separate pieces of our code.|The file name will always have an underscore before it. See import.|
|import|we will import all of our partials to the main.scss file|In the main.scss file add @import "folder-name/partial-name"|
|scroll function|We are adding a scrolling function so that when the user gets to the bottom of the page they can scroll to the top with one button click|By creating an animate function inside of a click function inside of the jquery we will be able to design a scroll function.|
|Folder Structure|We will use a folder structure so we can separate pieces of code into other folders so it becomes clearer to read.|Create folders containing partial files and import them in the main.scss|
|Collapsable menu|We will add a collapsable menu so the user only sees the menu optopns if they click the button|:--:|
|Carousel|We will add a carousel so the user can see multiple images while not cluttering the page.|:--:|
