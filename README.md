<h1>Responsive Web Design Layouts</h1>

<p>In this repository there are few examples of responsive web design layouts and one example of how to use SCSS/CSS to modify image shapes and wrap text around those images. All examples use SASS as the preprocessor, with all but the main "style.scss" set up as partials. These are from the PluralSight Course: <a href="https://www.pluralsight.com/courses/responsive-web-design-columns-flexbox-grids">Hands-on Responsive Web Design 3: Columns, Flexbox, and Grids</a>. The first example is a website made with a twelve column grid, the second shows how to modify image shapes, the third uses flexbox, the fourth examples uses the css grid, and the last one shows a combination of layouts to make a responsive mobile music player.</p>

<p>1) The twelve column grid <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Web_Design/blob/master/ColumnGrid/index.html">example</a>. Note: To get the social media icons to work in the GitHub Previewer, you have to inspect the page with developer tools, and navigate to the header, ul, li, a, and in the background-image url, delete one of the periods in the relative url (should look like: url(./images/socialSprites.png). Oddly, GitHub will not update to a single period from my end to display the icons for their previewer. Play around with resizing the browser to see how the columns adjust.</p>

<p>2) This example shows how to modify image shapes using CSS/SCSS with clip-path and shape-outside. View the <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Web_Design/blob/master/CSS_Shapes/index.html">example</a>. A great resource for shaping these images can be found <a href="https://bennettfeely.com/clippy/">here</a>.</p>

<p>3) This example uses Flexbox to arrange images and text on a site, changing the layout depending on the screen size. View the <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Web_Design/blob/master/Flexbox/index.html">preview</a>. Play around with the site with different device emulations.</p>

<p>4) These examples use the CSS Grid layout. This design is the most fluid of them all. The <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Web_Design/blob/master/CSS_Grid1/index.html">first example</a> displays eight news stories that are arranged in different positions depending if the screen is a phone, tablet, or desktop. The <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Web_Design/blob/master/CSS_Grid2/index.html">second example</a> shows how to use the grid layout with images. The <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Web_Design/blob/master/CSS_Grid3/index.html">third example</a> demonstrates how change the layout of the page depending on the screen size, with a hamburger menu for phone screens, a size nav for tablets, and a top navbar for larger screens.</p>

<p>5) Mobile Music Player Site Example. This combines many of the responsive web design practices employed in the earlier lessons. It consists of three pages: <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/DevJHennessy/Responsive_Web_Design/master/MusicPlayer/index.html">Album</a>, <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/DevJHennessy/Responsive_Web_Design/master/MusicPlayer/player.html">Player</a>, and <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/DevJHennessy/Responsive_Web_Design/master/MusicPlayer/artist.html">Artist<a>. Take a look at these on phones, rotating the screens to see the responsive design of the elements.</p>
