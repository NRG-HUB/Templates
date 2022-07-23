<p align="center"> <img width="200" src="https://raw.githubusercontent.com/NRG-HUB/SMARTPHONE_Study/main/nrg-logo.jpg" alt="logo"> </p> 
<!-- NRG lab's logo should go at the top of the page, aligned center.-->

<body style="background-color:{enter colour code here.};"></body> 

[HTML colour codes](https://htmlcolorcodes.com/) <!--Setting up the page's background colour. white (#fffff) is best.-->

This page contains information about the {{Insert Study Name Here}} study being conducted by the NRG lab, University of Reading. <br>

##### This is a study being conducted by the NRG ([nrg-lab.co.uk](https://www.nrg-lab.co.uk/)) by the following researchers:
Prof. Ciara McCabe (<a href="mailto:c.mccabe@reading.ac.uk">c.mccabe@reading.ac.uk</a>) 

Angad Sahni, PhD Student (<a href="mailto:a.sahni@pgr.reading.ac.uk">a.sahni@pgr.reading.ac.uk</a>) 

<!-- Use '<a href' section to link to your email address-->

<br>

#### You can view the instructions in [<u>HEADING 1</u>](template_instruction_page.md#heading-1) and/or [<u>HEADING 2</u>](template_instruction_page.md#heading-2). 

<br>
<br>

# Heading 1

<br>

<h3 style="color:red">IMPORTANT</h3> <!-- Here you have RED text to stress an IMPORTANT point. -->
<!-- Make list of IMPORTANT points here. -->

<br>
<br>
<br>

# Heading 2

<br>
<br>
<br>


<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 20px;
}

#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: red;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: white;
  color: red;
}
</style>

<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>

<script>
//Get the button
var mybutton = document.getElementById("myBtn");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>
