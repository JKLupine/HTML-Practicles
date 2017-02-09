# HTML-Practicles
These are some HTML common HTML practices to be implemented daily.
<!DOCTYPE html>
<html>
<head>
<body>
<h3>The following is a demonstration of Various list styles</h3>
<ol type="1" start="9">
  <li>Seepz</li>
  <li>TIC</li>
  <li>MIDC</li>
</ol>
<hr>

<h3>Unordered list i.e using UL and LI</h3>
<ul style="list-style-type:square">
  <li>Seepz</li>
  <li>TIC</li>
  <li>MIDC</li>
</ul>
</body>
</HEAD>
</html>




###############################################################################################

<!DOCTYPE html>
<html>
<head>
<body>
<h3>The following is a demonstration of Various list styles</h3>
<ol type="1" start="1">
  <li>Language</li>
    <ol type="i">
       <li>English</li>
          <ol type="A">
             <li>Prose</li>
             <li>Poetry</li>
         </ol>
	   <li>Hindi</li>
				<ol type="A">
             <li>Prose</li>
             <li>Poetry</li>
         </ol>
		 <li>Marathi</li>
				<ol type="A">
             <li>Prose</li>
             <li>Poetry</li>
         </ol>
		 </ol>
		<li>Social Study</li>
    <ol type="i">
       <li>History</li> 
	   <li>Geography</li>
	   </ol>
	   
	   <li>Science</li>
    <ol type="i">
       <li>Physics</li>
          <ol type="A">
             <li>Part 1</li>
             <li>Part 2</li>
         </ol>
	   <li>Chemistry</li>
				<ol type="A">
             <li>Organic</li>
             <li>Inorganic</li>
         </ol>
		 <li>Biology</li>
				<ol type="A">
             <li>Botany</li>
             <li>Zoology</li>
         </ol>
		 </ol>
		<li>Maths</li>
    <ol type="i">
       <li>Algebra</li> 
	   <li>Geometry</li>
	   </ol>
	   
<hr>


</body>
</HEAD>
</html>



############################################################################################################



<!DOCTYPE html>
<html>
<head>
<body>
<style>
body {
  background: #fafafa ;
  color: #444;
  font: 100%/30px 'Helvetica Neue', helvetica, arial, sans-serif;
  text-shadow: 0 1px 0 #fff;
}

strong {
  font-weight: bold;
}

em {
  font-style: italic;
}

table {
  background: #f5f5f5;
  border-collapse: separate;
  box-shadow: inset 0 1px 0 #fff;
  font-size: 12px;
  line-height: 24px;
  margin: 30px auto;
  text-align: left;
  width: 800px;
}

th {
  background: linear-gradient(#777, #444);
  border-left: 1px solid #555;
  border-right: 1px solid #777;
  border-top: 1px solid #555;
  border-bottom: 1px solid #333;
  box-shadow: inset 0 1px 0 #999;
  color: #fff;
  font-weight: bold;
  padding: 10px 15px;
  position: relative;
  text-shadow: 0 1px 0 #000;
}

th:after {
  background: linear-gradient(rgba(255, 255, 255, 0), rgba(255, 255, 255, .08));
  content: '';
  display: block;
  height: 25%;
  left: 0;
  margin: 1px 0 0 0;
  position: absolute;
  top: 25%;
  width: 100%;
}

th:first-child {
  border-left: 1px solid #777;
  box-shadow: inset 1px 1px 0 #999;
}

th:last-child {
  box-shadow: inset -1px 1px 0 #999;
}

td {
  border-right: 1px solid #fff;
  border-left: 1px solid #e8e8e8;
  border-top: 1px solid #fff;
  border-bottom: 1px solid #e8e8e8;
  padding: 10px 15px;
  position: relative;
  transition: all 300ms;
}

td:first-child {
  box-shadow: inset 1px 0 0 #fff;
}

td:last-child {
  border-right: 1px solid #e8e8e8;
  box-shadow: inset -1px 0 0 #fff;
}



tr:nth-child(odd) td {
  background: #f1f1f1 ;
}

tr:last-of-type td {
  box-shadow: inset 0 -1px 0 #fff;
}

tr:last-of-type td:first-child {
  box-shadow: inset 1px -1px 0 #fff;
}

tr:last-of-type td:last-child {
  box-shadow: inset -1px -1px 0 #fff;
}

tbody:hover td {
  color: transparent;
  text-shadow: 0 0 3px #aaa;
}

tbody:hover tr:hover td {
  color: #444;
  text-shadow: 0 1px 0 #fff;
}
</style>
	<table>
  <thead>
    <tr>
      <th>Empcode</th>
      <th>EmpName</th>
      <th>DeptCode</th>
	  <th>Experience</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1001</td>
      <td>Kiran Rao</td>
      <td><a href="D1.html" target="_blank">10</a></td>
	  <td>8 Yrs.</td>
    </tr>
    <tr>
      <td>1002</td>
      <td>Aamir Khan</td>
      <td><a href="D2.html" target="_blank">20</a></td>
	  <td>5 Yrs.</td>
    </tr>
    <tr>
      <td>1003</td>
      <td>Ishita Shah</td>
      <td><a href="D3.html" target="_blank">30</a></td>
	  <td>10 Yrs.</td>
    </tr>

  </tbody>
</table>
<hr>


</body>
</HEAD>
</html>


#########################################################################################



<!DOCTYPE html>
<html>
<head>
<body>
<h1>This Sales department is located at Mumbai</h1>

</body>
</HEAD>
</html>


###########################################################################################
<!DOCTYPE html>
<html>
<head>
<body>
<h1>This training department is located at Pune</h1>

</body>
</HEAD>
</html>

##############################################################################################
<!DOCTYPE html>
<html>
<head>
<body>
<h1>This Accounts department is located at Chennai</h1>

</body>
</HEAD>
</html>

#############################################################################################

<!DOCTYPE html>
<html>
<head>
<body>
<style>
div.imgs{
 max-width: 550px;
    height: auto;
border-style: solid;
    border-color: red;
	border-width: 8px;
}
</style>
<div class="imgs">
<img src="img1.png" alt="image 1" height="300" width="450">
<span align="centre" >Dessert</span><br>
<img src="img2.png" alt="image 2" height="300" width="450">
<span align="centre" >Jellyfish</span><br>

<img src="img3.png" alt="image 3" height="300" width="450">
<span align="centre" >Koala</span><br>

<img src="img4.png" alt="image 4" height="300" width="450">
<span align="centre" >Penguins</span><br>

</div>

</body>
</HEAD>
</html>


###################################################################################################
<!DOCTYPE html>
<html>
<head>
<body>
<style>
table {
  background: #f5f5f5;
  border-collapse: separate;
  box-shadow: inset 0 1px 0 #fff;
  font-size: 12px;
  line-height: 24px;
  margin: 30px auto;
  text-align: left;
  width: 800px;
}

td {
  border-right: 1px solid #000;
  border-left: 1px solid #000;
  border-top: 1px solid #000;
  border-bottom: 1px solid #000;
  padding: 10px 15px;
  position: relative;
}
</style>
	<table>
  
  <tbody>
    <tr>
      <td align="centre"><b>Name</b></td>
      <td><input type="text" name="name" placeholder="Name..." class="txtInput" required="" maxlength=20/>
    </tr>
    <tr>
<td align="centre"><b>Employee code</b></td>
      <td><input type="text" name="EmpC" placeholder="Employee Code..." class="txtInput" required="" maxlength=4/>
    </tr>
    <tr>
      <td align="centre"><b>Department</b></td>
      <td> 
	  <input type="radio" name="dept" value="Admin" checked> Admin<br>
  <input type="radio" name="dept" value="HR"> HR<br>
  <input type="radio" name="dept" value="Technical"> Technical <br>
  <input type="radio" name="dept" value="Accounts"> Accounts </td>
    </tr>
	 <tr>
<td align="centre"><b>Date of Joining</b></td>
      <td><input type="date" name="doj"/></td>
    </tr>
	
 <tr>
<td align="centre"><b>Address</b></td>
<td><textarea name="textarea" placeholder="Address..." style="width:250px;height:150px;"></textarea></td>
    </tr>
	<tr>
<td align="centre"><b>Training programs attended</b></td>
      <td><label><input type="checkbox" id="cbox1" value="first_checkbox"> Html/DHtml</label><br>

<input type="checkbox" id="cbox2" value="second_checkbox"> <label for="cbox2">Java</label> <br>
	<input type="checkbox" id="cbox2" value="third_checkbox"> <label for="cbox3">Client/Server</label><br> 
<input type="checkbox" id="cbox2" value="fourth_checkbox"> <label for="cbox4">.NET</label> </td>	
    </tr>
	<tr>
      <td align="centre"><b>Training programs to be attended</b></td>
      <td><select>
  <option value="volvo">JavaScript</option>
  <option value="saab">Sql</option>
  <option value="mercedes">CSS</option>
  <option value="audi">PseudoCode</option>
</select>
    </tr>
	<td align="centre"><b>Send the information at </b></td>
      <td><a href="empinfo@capgemini.com">empinfo@capgemini.com</a></td>
    </tr>
  </tbody>
</table>
</body>
</HEAD>
</html>
