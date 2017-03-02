# IT102.Modify.HTML.Styles
Changing HTML style tags with JavaScript!

Here is a script that changes something a on a web page. Try it!

<!DOCTYPE html>
<html>
<body>
<!-- HTML Table for Testing Purposes -->
<table id = "myTable" style="border: 10px solid red; font-size: 20px; font-weight: bold">
<tr id = "row1" style = "color: blue" >
<td id = "1.1" style = "border: 2px solid black">Row 1 Col 1</td>
<td id = "1.2" style = "border: 2px solid black">Row 1 Col 2</td>
</tr>
</table>
<!--Button to Launch a Function -->
<br><br><button type="submit" onclick = "changeTextColor()">Change</button>
<script>
// First JavaScript Function
// Changes text color from blue to green and back again
function changeTextColor(){
var textcolor = document.getElementById("row1").style.color;
if (textcolor== "green"){textcolor = "blue";}
else{textcolor = "green";}
document.getElementById("row1").style.color = textcolor;
}
</script>
</body>
</html>
Your assignment: write three more JavaScript functions to control other things about how this web page looks. Each function should have its own button. 

Note: This assignment assumes you are going to have to look up information about HTML and CSS object properties. Here are some references:

https://www.w3schools.com/css/css_syntax.asp (Links to an external site.)

https://www.w3schools.com/html/html_styles.asp (Links to an external site.)
