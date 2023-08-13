# Active-games-template

Hosted Link:- https://lok-ii.github.io/Active-games-template/


![Screenshot 2023-08-13 175848](https://github.com/Lok-ii/Active-games-template/assets/129180844/0cda52c2-f0b3-48f2-8877-aa87f854e746)
    
body Contains the main content of the webpage.  
    
    The main element wraps the entire content of the webpage. The following CSS properties are applied:
    This section is created using a <div> container within the main tag. 

    <main>: Represents the main content section of the page.
        <div class="sidebar">: A container for the sidebar content.
            <div class="avatar">: Container for the user's avatar and information.
                <img>: Displays the user's avatar image.
                <h3>: Heading displaying the user's name.
                <p>: Paragraph displaying the user's membership status.
            <div class="menu">: Container for the navigation menu options.
                .option: Container for each navigation option.
                <img>: Displays an image icon for the navigation option.
                <h2>: Heading displaying the name of the navigation option.
            <div class="free-games">: Container for free games offer.
                <h2>: Heading displaying the offer message.
                <img>: Displays an image icon for the free games offer.


    CSS Properties used in this section:- 

        h1: Selects all <h1> elements on the page.
            color: #426696;: Sets the text color to a shade of blue.
            font-weight: 600;: Sets the font weight to semi-bold.
            font-size: 48px;: Sets the font size to 48 pixels.
            opacity: 0.8;: Sets the opacity to 80%, making the text slightly transparent.

        h2, p: Selects all <h2> and <p> elements on the page.
            color: #658ec6;: Sets the text color to a shade of blue.
            font-weight: 500;: Sets the font weight to normal.
            opacity: 0.8;: Sets the opacity to 80%, making the text slightly transparent.

        h3: Selects all <h3> elements on the page.
            color: #426696;: Sets the text color to a shade of blue.
            font-weight: 600;: Sets the font weight to semi-bold.
            opacity: 0.8;: Sets the opacity to 80%, making the text slightly transparent.

        main: Selects the <main> element on the page.
            display: flex;: Uses flexbox layout for the main content container.
            font-family: "Poppins", sans-serif;: Sets the font family to "Poppins" or a generic sans-serif font.
            min-height: 100vh;: Sets the minimum height of the element to 100% of the viewport height.
            background: linear-gradient(to right top, #65dfc9, #6cdbeb);: Applies a linear gradient background from bottom-left (#65dfc9) to top-right (#6cdbeb).
            align-items: center;: Aligns flex items vertically at the center.
            justify-content: center;: Centers flex items horizontally.

        .sidebar: Targets elements with the class name "sidebar".
            display: flex;: Turns the element into a flex container.
            flex-direction: column;: Arranges child elements in a column.
            flex-wrap: wrap;: Allows wrapping of child elements within the column.
            width: 25%;: Sets the width to 25% of the parent's width.
            height: 99vh;: Sets the height to 99% of the viewport height.
            align-items: center;: Centers items horizontally within the container.
            justify-content: space-around;: Distributes items evenly with space around them.
            border-radius: 30px;: Adds rounded corners to the element.
            background: linear-gradient(to right bottom, rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0.3));: Applies a gradient background from top left to bottom right.
        .avatar: Targets elements with the class name "avatar".
            display: flex;: Turns the element into a flex container.
            flex-direction: column;: Arranges child elements in a column.
            text-align: center;: Centers the text within the container.

        .menu: Targets elements with the class name "menu".
            display: flex;: Turns the element into a flex container.
            flex-direction: column;: Arranges child elements in a column.
            width: 50%;: Sets the width to 50% of the parent's width.

            
![Screenshot 2023-08-13 175853](https://github.com/Lok-ii/Active-games-template/assets/129180844/e72a3392-6dd7-4f04-bcb2-1834a98fc335)

    <div class="active-games">: Container for the active games section.
        <div class="right-side">: Container for the game listings.
            <h1>: Heading displaying "Active Games".
            <div class="bar">: Div element representing a horizontal bar.
            <div class="game">: Container for each game listing.
                <img>: Displays an image icon for the game.
                <div class="progress">: Container for game progress details.
                    <h3>: Heading displaying the game title.
                    <p>: Paragraph displaying the game version.
                    <div class="long-bar">: Div element representing a long bar.
                <p>: Paragraph displaying the game progress percentage.


    CSS Properties used :-

        active-games: Targets elements with the class name "active-games".
            width: 70%;: Sets the width to 70% of the parent's width.
            height: 100vh;: Sets the height to 100% of the viewport height.

        .right-side: Targets elements with the class name "right-side".
            margin: 75px;: Adds a margin around the element for spacing.

        .bar: Targets elements with the class name "bar".
            width: 350px;: Sets the width of the bar.
            height: 30px;: Sets the height of the bar.
            background: linear-gradient(to right bottom, rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0.3));: Applies a gradient background from top left to bottom right.
            border-radius: 30px;: Adds rounded corners to the element.

        .game: Targets elements with the class name "game".
            display: flex;: Turns the element into a flex container.
            justify-content: space-around;: Distributes child elements evenly with space around them.
            align-items: center;: Centers items vertically within the container.
            background: linear-gradient(to right bottom, rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0.3));: Applies a gradient background from top left to bottom right.
            height: 140px;: Sets the height of the container.
            border-radius: 30px;: Adds rounded corners to the element.
            margin: 30px 0;: Adds margin at the top and bottom for spacing.
