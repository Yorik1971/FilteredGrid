<script>
function myFunction() {
  // Declare variables
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");

  // Loop through all table rows, and hide those who don't match the search query
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[0];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }
  }
}


/* ============================================ */
function filterTableFunc() {
 var filterResult = document.getElementById("search").value.toLowerCase();
 var empTable = document.getElementById("employeeData");
 var tr = empTable.getElementsByTagName("tr");
 for (var i = 1; i < tr.length; i++) {
  tr[i].style.display = "none";
  const tdArray = tr[i].getElementsByTagName("td");
  for (var j = 0; j  -1) {
    tr[i].style.display = "";
    break;
    }
   }
  }
}
</script>

<style>
#myInput {
  background-image: url('/css/searchicon.png'); /* Add a search icon to input */
  background-position: 10px 12px; /* Position the search icon */
  background-repeat: no-repeat; /* Do not repeat the icon image */
  width: 100%; /* Full-width */
  font-size: 16px; /* Increase font-size */
  padding: 12px 20px 12px 40px; /* Add some padding */
  border: 1px solid #ddd; /* Add a grey border */
  margin-bottom: 12px; /* Add some space below the input */
}

#myTable {
  border-collapse: collapse; /* Collapse borders */
  width: 100%; /* Full-width */
  border: 1px solid #ddd; /* Add a grey border */
  font-size: 18px; /* Increase font-size */
}

#myTable th, #myTable td {
  text-align: left; /* Left-align text */
  padding: 12px; /* Add padding */
}

#myTable tr {
  /* Add a bottom border to all table rows */
  border-bottom: 1px solid #ddd;
}

#myTable tr.header, #myTable tr:hover {
  /* Add a grey background color to the table header and on hover */
  background-color: #f1f1f1;
}

</style>

<div>
<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for names..">

<table id="myTable">
  <tr class="header">
    <th style="width:60%;">Name</th>
    <th style="width:40%;">Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Berglunds snabbkop</td>
    <td>Sweden</td>
  </tr>
  <tr>
    <td>Island Trading</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Koniglich Essen</td>
    <td>Germany</td>
  </tr>
</table>
</div>

<br>

<div>
<input type="text" id="search" onkeyup="" placeholder="Search....." ><br><br>

<table id="employeeData" border="1">
 <tr>
  <th>Name</th>
  <th>Email</th>
  <th>Gender</th>
  <th>Designation</th>
  <th>Joining Date</th>
 </tr>
 <tr>
  <td>John</td>
  <td>john@gmail.com</td>
  <td>Male</td>
  <td>CPA</td>
  <td>5/5/2020</td>
 </tr>
 <tr>
  <td>Stephen</td>
  <td>stephen@gmail.com</td>
  <td>Male</td>
  <td>HRM</td>
  <td>21/10/2020</td>
 </tr>
 <tr>
  <td>Mari</td>
  <td>mari78@gmail.com</td>
  <td>Female</td>
  <td>HRM</td>
  <td>16/05/2022</td>
 </tr>
 <tr>
  <td>Rhonda</td>
  <td>rhonda12@hotmail.com</td>
  <td>Male</td>
  <td>CFA</td>
  <td>23/06/2022</td>
 </tr>
</table>

</div>
