<!DOCTYPE html>
<html lang="">
<header>
    <h1>Activity 43: Research HTML </h1>
    <nav>
        <ul>
            <li><a href="#header">Header</a>
            <li> <a href="#headings">Headings h1 - h6</a> </li>
            <li> <a href="#ul&ol">Unordered List and Ordered List</a> </li>
            <li> <a href="#tables">Table</a> </li>
            <li> <a href="#forms">Forms</a> </li>
            <li> <a href="#images">Images</a> </li>
            <li> <a href="#canvas">canvas</a></li>
            <li> <a href="#Video">Videos</a></li>
            <li> <a href="#Youtube">Youtube</a></li>
            <li> <a href="#DragandDrop">Drag and Drop</a></li>
        </ul>
    </nav>
</header>
<body>
<h1> This tag defines the most important heading on <br>
    the page, typically used for the main title. </h1>
<h2> This tag is used for subheadings, providing a <br>
    secondary level of importance. </h2>

<h3> Represents a third-level heading, used <br>
    for subsections under the "H2" heading.</h3>
<h4> A fourth-level heading, further categorizing content under h3 </h4>
<h5> This tag is for fifth-level headings, providing more granularity. </h5>
<h6> The least important heading, used for the smallest sections of content. </h6>
<p> This tag defines a paragraph of text, used for general content.</p>
<h2> Unordered List </h2>
<ul>
    <li> This is First Unordered List </li>
    <li> This is Second Unordered List </li>
    <li> This is Third Unordered List </li>
</ul>
<h2> Ordered List</h2>
<ol>
    <li> This is First Ordered List </li>
    <li> This is Second Unordered List </li>
    <li> This is Third Unordered List </li>
</ol>
<h2> Tables </h2>
<style>
    table, th, td {
        border: 1px solid black;
    }
    </style>
<table style = "width: 100%">
    <tr>
    <td> Name </td>
    <td> Age  </td>
    <td> Country </td>
    </tr>
    <tr>
    <td> Carl </td>
    <td> 21  </td>
    <td> Canada </td>
    </tr>
    <tr>
    <td> Jen </td>
    <td> 21  </td>
    <td> Philippines </td>
    </tr>
    <tr>
    <td> Flore </td>
    <td> 40  </td>
    <td> Philippines </td>
    </tr>
    </table>
<h2> Forms </h2>
<form action="/action_page.php"></form>
<label for="fname"> First Name: </label><br>
<input type = "text" id="fname" name="fname" value= "Jinelyn">
</body>
<label for = "lname" > Last Name: </label> <br>
<input type="text" id="lname" name="lname" value="Mangubat">
<br> </br>
<input type="Submit" value="Submit">
</form>
<h2> DIV IMAGES </h2>
<div class = "Sample">
    <a target="_blank" href="Jin.jpg">
    <img src ="Jin.jpg" alt= "Sample" width="612" height="769">
    </a>
</div>
<h2> CANVA </h2>
<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAGE_SnNtPE/QSPTpqzhLipCZYiHWUVb2A/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<h2> DIV VIDEO </h2>

https://github.com/user-attachments/assets/f19ae29e-1214-48f1-be8e-fc72cbee5b42

<H2> DIV YOUTUBE </H2>
   <iframe width="1280" height="720" src="https://www.youtube.com/embed/sZEhMUsyaN0" title="Taylor Swift Greatest Hits Full Album 2023 2024  Taylor Swift Best Songs Playlist 2023 2024" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <iframe width="1280" height="720"<iframe width="1513" height="569" src="https://www.youtube.com/embed/CevxZvSJLk8" title="Katy Perry - Roar" frameborder="0" 
<script>
function allowDrop(ev) {
  ev.preventDefault();
}
function drag(ev) {
  ev.dataTransfer.setData("text", ev.target.id);
}
function drop(ev) {
  ev.preventDefault();
  var data = ev.dataTransfer.getData("text");
  ev.target.appendChild(document.getElementById(data));
}
</script>
</video>
<body>
<div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"></div>
<img id="drag1" src="url-image-link" draggable="true" ondragstart="drag(event)" width="336" height="69">
<h6> ps: this code is from w3schols.com</h6>
<a href="https://www.w3schools.com/html/html5_draganddrop.asp">This is the source code</a>
</body>
</html>
