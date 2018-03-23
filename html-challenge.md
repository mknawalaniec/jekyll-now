---
layout: html-page
title: HTML and CSS Challenge
permalink: /html-challenge/
---

Use the code editor below to modify the body of the fish to an orange color.

### Navigating the editor
Click on the editor in order to navigate between the HTML and CSS files.

<iframe src="https://embed.plnkr.co/hbQCmy9BQ5BWcMvcAmZB?show=app,preview"
        frameborder="0"
        width="150%"
        height="400px"
        style="margin: 0 auto; display: block; margin-left:-25%;" onload="access()" id="preview"></iframe>

<div class="form-group" style="padding-top: 40px;">
  <div"edit">How many lines did you edit to change entire color of the fish?</div>
  <input type="test" class="form-control" id="edit">
        <button onclick="verifyAnswer()">Submit Answer</button>
</div>
<script>
function verifyAnswer(){
        if(document.getElementById("edit").value == 3){
                alert("Correct"); // edit to changing the href
        } else {
                alert("Try again!");
        }
}
</script>


