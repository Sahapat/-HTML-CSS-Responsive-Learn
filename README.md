# Goal
This is my learning project on HTML/CSS without framework. The goal is to create a responsive website as i show.

![Goal Image](https://github.com/Sahapat/HTML-CSS-Responsive-Learn/blob/master/MD-Image/Goal.png)

# What technique i use ?
For create a responsive i use a CSS row and column by create a class and use media query to handle display on different screen size.<br>
Row class is define a workspace width for a Column class. The after selector is for confirm that after the row class will break into new line.

```css
.row {
    width: 100%;
}

.row::after {
    clear: both;
    display: block;
    content: "";
}
```
Column class is separate workspace width into 12 column.

```css
.col-1 {
    width: 8.33%;
}

.col-2 {
    width: 16.66%;
}

.col-3 {
    width: 25%;
}

.col-4 {
    width: 33.33%;
}

.col-5 {
    width: 41.66%;
}

.col-6 {
    width: 50%;
}

.col-7 {
    width: 58.33%;
}

.col-8 {
    width: 66.66%;
}

.col-9 {
    width: 75%;
}

.col-10 {
    width: 83.33%;
}

.col-11 {
    width: 91.66%;
}

.col-12 {
    width: 100%;
}
```

Media query for handle in different screen width. For this website, i has query 2 width 1100px and 800px.

```css
@media only screen and (max-width:1100px) {}
@media only screen and (max-width:820px) {}
```

# What does it look like ?
![PC Version](https://github.com/Sahapat/HTML-CSS-Responsive-Learn/blob/master/MD-Image/screenshot-1.PNG)
[Link to view the website](https://sahapat.github.io/HTML-CSS-Responsive-Learn/)