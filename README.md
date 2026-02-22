# My-first
Html code
<!DOCTYPE html>
<html>
<head>
<title>Student Bio Data</title>
<style>
body{
    font-family: Arial, sans-serif;
}
.container{
    width: 80%;
    margin: auto;
}
.photo{
    width: 150px;
    height: 150px;
    border: 2px solid black;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
}
input{
    width: 100%;
    padding: 6px;
    margin: 5px 0;
}
table{
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
}
table, th, td{
    border: 1px solid black;
}
th, td{
    padding: 8px;
    text-align: center;
}
h2{
    text-align: center;
}
button{
    padding: 8px 15px;
    margin-top: 15px;
}
</style>
</head>

<body>

<div class="container">

<h2>Student Bio Data</h2>

<div class="photo">PHOTO</div>

<label>Name:</label>
<input type="text" value="Asmi Dumre" readonly>

<label>Class:</label>
<input type="text" value="11" readonly>

<label>DOB:</label>
<input type="text" value="2067-5-11" readonly>

<label>Father:</label>
<input type="text" value="Arjun Dumre" readonly>

<label>Mother:</label>
<input type="text" value="Laxmi Dumre" readonly>

<label>Gender:</label>
<input type="text" value="Female" readonly>

<label>Address:</label>
<input type="text" value="Sekham 5, Syangja Sim" readonly>

<label>Contact:</label>
<input type="text" value="9868854631" readonly>

<h2>Hobby</h2>
<ol>
<li>Traveling</li>
<li>Writing</li>
<li>Singing</li>
</ol>

<h2>Education</h2>
<table>
<tr>
<th>S.N</th>
<th>Level</th>
<th>GPA</th>
<th>Remark</th>
</tr>
<tr>
<td>1</td>
<td>8</td>
<td>3.01</td>
<td>Pass</td>
</tr>
<tr>
<td>2</td>
<td>SEE</td>
<td>2.97</td>
<td>Pass</td>
</tr>
</table>

<h2>Language</h2>

<label>English</label>
<input type="range" value="80">

<label>Nepali</label>
<input type="range" value="90">

<label>Hindi</label>
<input type="range" value="75">

<br><br>

<button>Submit</button>

</div>

</body>
</html>
