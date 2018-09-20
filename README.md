# HTML-Setup
Setting up an HTML file
<p>
  <strong>Declaration:</strong><br>
  !DOCTYPE html>
<p>
  <strong>Starting and Ending the File:</strong><br>
  html><br>
  /html>
<p>
  <strong>Setting up the file:</strong><br>
  head><br>
    body>
<p>
  <strong>Head:</strong><br>
  head><br>
    title>TEST TITLE NAME (shows up in browser tab) /title>
<p>
  <strong>Directory:</strong><br>
  Below head> and below body> you can add an anchor tag with a relative path.<br>
  <a href="./index.html">TEXT HERE INDEX</a><br>
  <a href="./about.html">TEXT HERE ABOUT</a><br>
  <a href="./contact.html">TEXT HERE CONTACT</a><br>
<p>
  <strong>Comments:</strong><br>
  Begin with < !-- and end with -- ><br>
<p>
  <strong>Tables:</strong><br>
  table><br>
  tr><br>
  thead><br>
  th><br>
  /th><br>
    < !-- th scope="row OR col"> to add a table heading to the row or column --><br>
  /thead><br>
      tbody><br>
  td><br>
  /td><br>
  /tr><br>
    /tbody><br>
      tfoot><br>
      < !--Section off bottom part of a table with a foot --><br>
        tr><br>
        th> XXX /th><br>
        td> XXX /td><br>
        /tr<br>
        /tfoot><br>
  /table><br>
  < !-- CSS is used to customize the table --><br>
  td colspan OR rowspan="NUMBER">XXXXXXX /td><br>
    < !--This allows X number of cells to go across the span of 1 column/row -->
  <p>
    <strong>Table Styling with CSS:</strong><br>
    Example: table, th, td {<br>
  border: 1px solid black;<br>
  font-family: Arial, sans-serif; <br>
  text-align: center;<br>
}<br>
                                      
