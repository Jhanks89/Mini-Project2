<html>
<head>
	<meta charset="utf-8">
	<meta name="description" content="Mini Project 2 for the CNIT-132 class">
  	<meta name="keywords" content="HTML and CSS">
	<title>Mini Project 2</title>
	<link rel="stylesheet" type="text/css" href="miniproject2.css">
</head>
body {
	background-color: yellow;

}

h1 {
	color: red;
	text-align: center;
}

#bigger {
	font-size: 48px;
	font-weight: bold;
	font-style: italic;
}

h2 #bigger2 {
	font-size: 48px;
}

#red {
	color: red;
}

h2 {
	text-align: right;
	color: blue;
	font-style: italic;
}

a {
	color: red;

}

a:visited { 
  color: blue;
}

h3 {
	text-align: right;
	color: red;
	position: relative;
	-webkit-animation: mymove 5s infinite;
	-webkit-animation-delay: 2s;
	animation: mymove 5s infinite;
	animation-delay: 2s;
}

@-webkit-keyframes mymove {
	from {
		right: 0px;
	}
	to {
		right: 800px;
	}
}

@keyframes mymove {
	from {right: 0px;}
	to {right: 800px;}
}

table {
	border-spacing: 5px;
	animation: pulse 10s infinite;
}

@keyframes pulse {
	0% {
		background-color: cyan;
		color: black;
	}

	100% {
		background-color: green;
		color: white;
	}
}

td {
	text-align: center;
	padding: 10px;
}

#tablestyle {
	font-weight: bold;
}<body>

	<h1>This is the first heading</h1>

	<p>
		<label id="bigger">T</label>his is my first paragraph and all the paragraphs in this page will start with a bigger font
	</p>
	<p>
		<label id="bigger">M</label>y life as a web developer, has been pretty much amazing! I started developing web pages when there was no CSS to be used and all formatting was done using HTML tags that currently are considered deprecated or even eliminated from good web developed pages. One example of tags that have been eliminated are:<label id="red">&lt;font&gt;, &lt;center&gt;</label>. There are some attributes that have been also eliminated in order to clean more the HTML code and put all the formatting (style) to CSS.
	</p>

	<h2>Using CSS</h2>

	<p>
		<label id="bigger">W</label>hen CSS was created, the main idea was exactly to take all of these formatting tags and attributes from the HTML document and transfer them to an external file that would only take care of formatting the HTML page. The idea is that the HTML document should be focused on the content of the page and the formatting, even layout, would be in a separated file.
	</p>

	<p>
		<label id="bigger">W</label>his standard has been supported and adopted world wide by W3C (<label id="red">World Wide Web Consortium</label>) which is the organization that sets the standards for web development.
	</p>

	<h2>
		<label id="bigger2">End of this exercise</label>
	</h2>

	<p>
		<label id="bigger">A</label>t the end of this exercise, you will take all of these bad attributes and formatting tags that are taking too much space in this HTML document and you will create an <label id="red">embedded CSS</label> using the <label id="red">&lt;style&gt; tag</label> (of course, placing this tag in the appropriate section of your document). Within that style tag, you will transfer all the formatting you see in this page and create appropriate CSS in order to clean the HTML document without changing the formatting that this old style HTML has created!
	</p>

	<p>
		<label id="bigger">T</label>is a link to <a href="http://www.ccsf.edu">City College web site</a>. After you visit this page, this link should be white due to the vlink attribute in the body tag. If you have never visited this link, then, it will be red due to the link attribute in the body tag as well.
	</p>

	<h3>The table showing below</h3>

	<table>
		<tr>
			<td><label id="tablestyle">This table should have a cyan background color and the text is centralized within each column</label></td>
			<td>Second column, first row</td>
		</tr>
		<tr>
			<td><label id="tablestyle">Would you please animate from cyan to green background?</label></td>
			<td>Second column, second row</td>
		</tr>
		<tr>
			<td><label id="tablestyle">Remember to also animate the color of the font from black to white</label></td>
			<td>Third column, third row</td>
		</tr>
	</table>

</body>
</html>
element.style {

