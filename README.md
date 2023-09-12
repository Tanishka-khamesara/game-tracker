# game-tracker
https://tanishka-khamesara.github.io/game-tracker/games.html



![game-tracker-1](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/0924ec4a-198b-4c23-ab78-2fd16cbb394a)
![game-tracker-2](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/a16973a9-b2a1-4fca-b738-abb3cecce0ca)
![game-tracker-3](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/a0173758-1222-4a70-992f-b197e5c8baa8)
![game-tracker-4](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/a54b7eb6-ab8d-407c-9db8-2dd22000ac40)
![game-tracker-5](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/8e0b5bb4-eee4-4863-93b9-7268e9ab1837)
![game-tracker-6](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/9a85c55a-e555-4ac4-a9e1-3157d964f93b)
![game-tracker-7](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/e0925706-0c02-478f-94fa-0ab59c7c4a88)
![game-tracker-8png](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/34000591-f7a9-4684-a860-c657ad3071a4)
![game-tracker-9png](https://github.com/Tanishka-khamesara/game-tracker/assets/127411985/f6c634cf-570e-4801-b0c5-30e43e164340)



html explaination->
<title>games template</title>: This tag specifies the title of the webpage, which appears in the browser's title bar or tab.

<link href="./style.css" rel="stylesheet">: This line links an external CSS stylesheet named "style.css" to apply styling to the HTML elements on the page.

<body>: The body section contains the actual content of the webpage.

Inside the <body>, there is a <div class="main"> element, which likely serves as the main container for the webpage's content.

Inside the main container, there is a sidebar (<div class="sidebar">) and a content container (<div class="container">), representing two main sections of the webpage.

Within the sidebar, there is a user profile section (<div class="profile">) containing an image, user name, and membership status.

Below the profile section, there is a set of icons with associated labels. Each icon is created using SVG images and has a title (e.g., "Streams," "Games," "New," "Library"). These icons likely represent navigation links or categories related to the website's content.

There is also a promotional box at the bottom of the sidebar encouraging users to join a pro membership for free games.

Inside the content container, there is a section for "Active Games" with a heading and an underline for emphasis. Below the heading, there is a list of game cards, each featuring an image, game title, platform information, and a percentage value. These cards likely represent currently active games or game recommendations.

This HTML code provides the basic structure and layout for a gaming website. The styling and interactivity would depend on the associated CSS and JavaScript code, which is linked to or embedded in the HTML document but is not included in the provided code snippet.


css explaination->
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;500;600;700;800;900&display=swap');: This line imports the Google Fonts stylesheet for the "Poppins" font family with various weights and styles. This font family will be used throughout the webpage.

*: The asterisk is a universal selector, which means it targets all elements on the page. In this case:

margin: 0%; sets the margin of all elements to 0% (effectively removing margins).
box-sizing: border-box; sets the box-sizing property to "border-box," which includes padding and borders in the element's total width and height.
font-family: 'Poppins', sans-serif; sets the default font-family to "Poppins" with a fallback to a generic sans-serif font if "Poppins" isn't available.
opacity: 98%; sets the opacity of all elements to 98%.
.main: This class styles the main container of the webpage.

background-color: Sets the background color to a linear gradient that combines multiple shades of green.
height and width: Sets the height and width of the container.
margin: Adds space around the container, centering it horizontally with 30px margin on all sides.
display: flex;: Makes the container a flex container.
.sidebar: Styles the sidebar section.

height and width: Sets the height and width of the sidebar.
background: Applies a linear gradient background with different shades of green.
display: flex;: Makes the sidebar a flex container.
flex-direction: column;: Stacks its child elements vertically.
justify-content and align-items: Centers its child elements vertically and horizontally.
border-radius: 20px;: Rounds the corners of the sidebar.
.container: Styles the content container.

height and width: Sets the height and width of the content container.
display: flex;: Makes the container a flex container.
flex-direction: column;: Stacks its child elements vertically.
.blur: Styles a circular blur element.

height and width: Sets the dimensions of the circular element.
background-color: Sets the background color with transparency (rgba).
position: absolute;: Positions the element absolutely within its parent.
top and right: Positions the element relative to the top and right edges of its parent.
filter: blur(30px);: Applies a blur effect to the element.
overflow: hidden;: Hides any overflow content.
border-radius: 50%;: Rounds the corners to create a circular shape.
.profile, .box, .icon, .heading, .underline, .cards, .card, .name, .blue-line: These are various classes used to style specific elements within the sidebar and content container. They control properties like colors, font sizes, padding, margins, box shadows, and more.

These CSS styles are responsible for the layout, colors, and overall appearance of the webpage. They work together with the HTML structure you provided to create the visual design of the gaming website.
