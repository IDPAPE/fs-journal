# Foundations of Web Development
01. In your own words, why do we use Git?
    > Verison control is helpful for keeping projects organized. Git is also extremely useful for storing a library of code and making it publicly viewable.

02. In the terminal, what is the command `mkdir` used for?
    > It creates a new directory/folder inside your current directory

03. What is a ***pseudo-class*** and what are some of the most common ones you think you will use?
    > A pseudo-class is a class that modifies an element based on its current state. I'm sure we will use the :hover pseudo selector hundreds of times throughout this course. We will also probably use :checked for check boxes and :blank :valid :invalid for user inputs of sections later on in the course.
        > Note: I was only able to find one reference to pseudo classes in the readings attatched, only took a quick google search to learn more though.

04. What is ***specificity*** and how might you use it to your benefit?
    > specificity is a score that is given to CSS rules in order to decide which one should ultimately apply to an element. The more specific the rule, the higher the specificity score. a rule targeting an element gives a specificity score of 1, a rule targeting a class gives a score of 10, and a rule targeting a specific id gives a score of 100. Example: there is a rule that tells all text in the header of a page to be a certain font, and a class that tells one element to be a different font.

05. What problems do you think you could run into if you over-utilized the `!important` feature?
    > It could lead to your code being filled with !important, since !important overrides #id tags and class rules, you can only modify the element with another !important tag, so all of your css rules will end up needing !important to actually change anything. 

06. What are the three components that makeup a `CSS` rule? <br> Example:

    ```css
        h1 {
            color: rgba(255, 210, 33, .75);
        }
    ```

    > 'h1' is a selector, 'color' is a property, 'rgba(255, 210, 33, .75)' is a value.

07. How do you think good design influences people when visiting a website, and what sorts of things could you convey through design alone?
    > A visually pleasing page makes an immediate positive impression on visitors of a site, and makes them more likely to view more of the page.good design can make the most important things stand out on a page through text formatting such as weight, color, underlines. When making buttons they should pop out from the background to draw people's attention to them. Sometimes with buttons, they really should be a specific color, for example, making a window with a red 'confirm' and green 'cancel' button would be an easy way to make a lot of people push the wrong button.

08. What is the purpose of ***wireframing***?
    > Wireframing is important firstly because if helps with planning out how a webpage will ultimately look. Wireframing also is good for recieving user feedback before lots of code is written. A wireframe can also expose issues with the layout of a page and inspire new ideas

09. Do you think wireframes are worth the time, energy, and effort that they require? Why or Why not?
    > I think wireframes ultimately save time because if you waited until your page was fully completed to decide what needs to be changed or removed, you would end up wasting a lot of time coding on things that never make it to the final version.

10. Define the display `:flex property:`
    > display:flex is used to alter how elements on a webpage are aligned. display:flex is very FLEXible and can do things like align elements into rows or columns, reverse these rows and columns, and alter the alignment of individual elements within these rows and columns.

11. What `CSS` properties affect the size of a box model?
    > Height and width, along with padding and border. Margin affects the spacing but doesn't change the size of each individual item.
