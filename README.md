<style>
    @font-face {
	font-family: 'JetBrainsMono'; 
	src: url(misc/fonts/JetBrainsMono-Regular.woff2); 
}

@font-face {
    font-family: 'JetBrainsMono-Light';
    src: url(misc/fonts/JetBrainsMono-Light.woff2); 
}

@font-face {
    font-family: 'JetBrainsMono-SemiBold';
    src: url(misc/fonts/JetBrainsMono-SemiBold.woff2); 
}

@font-face {
    font-family: 'JetBrainsMono-Bold';
    src: url(misc/fonts/JetBrainsMono-Bold.woff2); 
}

body {
    font-family: 'JetBrainsMono';
    font-size: 16pt;
    background-color: #191C21;
    color: #FCFEF1;
    letter-spacing: 2px;
    margin-left: 20px;
  }

h1, h2, h3, h4 {
    font-family: 'JetBrainsMono-Bold';
}

b {
    font-family: 'JetBrainsMono-SemiBold';
}

li {
    font-family: 'JetBrainsMono-Light';
    font-size: 14pt;
}

p {
   border:#9E363A  solid;
   padding: 15px;
}

img {
    display: block;
    margin-left: auto;
    margin-right: auto;
}

img.smallImage {
    width: 500px;
}

img.midleImage {
    width: 600px;
}

</style>

<img class="smallImage" src="misc/images/logo.png">

<h1>DOCUMENTATION MAZE</h1>
<h2>LET'S GO!</h2>
<p>MAZE - is an application that allows you to build mazes and find the shortest path.
</p>
<h4>BASIC MAZE FUNCTIONS:</h4>
<ul>
    <li>Drawing area, where you can choose the start and end point of the path (Wave Algorithm).</li>
    <li>Uploading file from txt-file (show maze).</li>
    <li>Adjust the height and width of the generate maze (Eller Algorithm).</li>
</ul>
<h4>EXAMPLE:</h4>
<img class="midleImage" src="misc/images/example_maze.gif">
<h5>Finding the shortest path</h5>
<h4>HOW TO USE:</h4>
<ul>
    <li>First, when you run the program you have the choice to load the maze from a file or "GENERATE".</li>
    <li>You can change the height and width of the maze. Setting height and width in windows.</li>
    <li>Select the start point with the left mouse button and the end point with the right mouse button.</li>
</ul>
<h4>RECOMENDATION:</h4>
<ul>
    <li>Upload a file of a certain format that you can find in the dataset.</li>
    <li>Don't use large txt-files.</li>
</ul>
<h3>LET'S TALK ABOUT CAVE</h3>
<p>CAVE - A cave is a certain type of branching location. Such locations can be generated by generation using a cellular automaton.</p>
<h4>EXAMPLE:</h4>
<img class="midleImage" src="misc/images/example_cave.gif">
<h4>BASIC CAVE FUNCTIONS:</h4>
<ul>
    <li>Uploading file from txt-file (show cave).</li>
    <li>Adjust the height and width of the generate cave (cellular automaton)</li>
    <li>Run сave generation simulation</li>
</ul>
<h4>HOW TO USE:</h4>
<ul>
    <li>First, when you run the program you have the choice to load the cave from a file or "GENERATE".</li>
    <li>You can change the height and width of the cave. Setting height and width in windows.</li>
    <li>Need sets the limits of "birth" and "death" of the cell, as well as the chance for the initial initialization of the cell</li>
    <li>Need to press the step button or adjust the generation speed</li> 
</ul>
<h4>RECOMENDATION:</h4>
<ul>
    <li>Upload a file of a certain format that you can find in the dataset.</li>
    <li>Don't use large txt-files.</li>
</ul>
