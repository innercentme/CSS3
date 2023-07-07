# Composite Selectors 02

Here is an explanation of each code block:

/* Styling the h1 heading */
h1 {
    color: blue;
}
This code styles the <h1> heading and sets the text colour to blue.

/* Styling a paragraph p, which is a child of an element with the .content class */
.content p {
    font-size: 16px;
}
This code styles all <p> paragraphs that are children of an element with the .content class. The font size is set to 16px.

/* Styling the ul list, which is a direct child of the element with the .sidebar class */
.sidebar > ul {
    list-style: none;
}
This code styles the <ul> list, which is a direct child of the element with the .sidebar class. It sets the list style without bullets.

/* Styling the li element that follows directly after another li element */
ul li + li {
    margin-top: 10px;
}
This code styles the <li> element that immediately follows another <li> element. The top margin is set to 10px.

/* Styling the li elements that follow the h2 element */
h2 ~ ul li {
    colour: green;
}

This code styles all <li> elements that follow the <h2> element. It sets the green colour of the text.

These styles are used to define the appearance of specific elements on a page. You can change the values of the properties (e.g., colour, font size, padding) to suit your needs and desired design.
