<html>
<head>

<style>
/* Full-width input fields */
input[type=text], input[type=password] {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
}

/* Set a style for all buttons */
button {
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;
}

button:hover {
    opacity: 0.8;
}

/* Extra styles for the cancel button */
.cancelbtn {
    width: auto;
    padding: 10px 18px;
    background-color: #f44336;
}

/* Center the image and position the close button */
.imgcontainer {
    text-align: center;
    margin: 24px 0 12px 0;
    position: relative;
}

img.avatar {
    width: 40%;
    border-radius: 50%;
}

.container {
    padding: 16px;
}

span.psw {
    float: right;
    padding-top: 16px;
}

/* The Modal (background) */
.modal {
    display: none; /* Hidden by default */
    position: fixed; /* Stay in place */
    z-index: 1; /* Sit on top */
    left: 0;
    top: 0;
    width: 100%; /* Full width */
    height: 100%; /* Full height */
    overflow: auto; /* Enable scroll if needed */
    background-color: rgb(0,0,0); /* Fallback color */
    background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
    padding-top: 60px;
}

/* Modal Content/Box */
.modal-content {
    background-color: #fefefe;
    margin: 5% auto 15% auto; /* 5% from the top, 15% from the bottom and centered */
    border: 1px solid #888;
    width: 80%; /* Could be more or less, depending on screen size */
}

/* The Close Button (x) */
.close {
    position: absolute;
    right: 25px;
    top: 0;
    color: #000;
    font-size: 35px;
    font-weight: bold;
}

.close:hover,
.close:focus {
    color: red;
    cursor: pointer;
}

/* Add Zoom Animation */
.animate {
    -webkit-animation: animatezoom 0.6s;
    animation: animatezoom 0.6s
}

@-webkit-keyframes animatezoom {
    from {-webkit-transform: scale(0)} 
    to {-webkit-transform: scale(1)}
}
    
@keyframes animatezoom {
    from {transform: scale(0)} 
    to {transform: scale(1)}
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
    span.psw {
       display: block;
       float: none;
    }
    .cancelbtn {
       width: 100%;
    }
}
</style>
<body>


<h1 style="font-size:48px;"><center><b><i><font color="DarkSlateGrey">Food Corner</font></i></b></center></h1>

<button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Login</button>

<div id="id01" class="modal">
  
  <form class="modal-content animate" action="/action_page.php">
    <div class="imgcontainer">
      <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
      <img src="Login.jpg" alt="Loginr" class="avatar">
    </div>

    <div class="container">
     

      <label><b>Password</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>
        
      <button type="submit">Login</button>
      <input type="checkbox" checked="checked"> Remember me
    </div>

    <div class="container" style="background-color:#f1f1f1">
      <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
      
    </div>
  </form>
</div>

<script>
// Get the modal
var modal = document.getElementById('id01');

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}
</script>
<style>

table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
}
th, td {
    padding: 5px;
    text-align: left;
}
table tr:nth-child(even) {
    background-color: #eee;
}
table tr:nth-child(odd) {
   background-color:#fff;
}
table th {
    background-color: black;
    color: white;
}
</style>
</head>
<body background="home.jpg">



<p style="font-size:24px;"><font color="DarkSlateGrey"><b>Welcome to our resturant! this is a fast food resturant where you can find every kind of fast food. Have a look at the resturant menu:</b></font></p>
<table style="width:100%">
  <caption>MENU</caption>
  <tr>
    <th>Item</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>Pizza(per slice)</td>
    <td>Rs 100</td>
  </tr>
  <tr>
    <td>Zinger Burger</td>
    <td>Rs 320</td>
  </tr>
<tr>
    <td>Double Zinger (served with fries and drink)</td>
    <td>Rs 520 </td>
  </tr>
<tr>
    <td>paratha roll(served with drink)</td>
    <td>Rs 250</td>
  </tr>
<tr>
    <td>chucken shawarma</td>
    <td>Rs 100</td>
  </tr>
<tr>
    <td>chicken cheese shawarma</td>
    <td>Rs 120</td>
  </tr>
<tr>
    <td>zinger paratha roll</td>
    <td>Rs 300</td>
  </tr>
<tr>
    <td>club sandwich</td>
    <td>Rs 250</td>
  </tr>
<tr>
    <td>chicken burger</td>
    <td>Rs 200</td>
  </tr>

  <tr>
    <td>Soft Drinks (Pepsi,Fanta,7up)</td>
    <td>Rs 50</td>
    
  </tr>
  <tr>
    <td>Coffee</td>
    <td>Rs 250</td>
    
  </tr>
  <tr>
    <td>Tea</td>
    <td>Rs 50</td>
    
  </tr>
<tr>
    <td>Mint Margarita</td>
    <td>Rs 150</td>
    
  </tr>
<tr>
    <td>Mineral Water (small)</td>
    <td>Rs 30</td>
    
  </tr>
</table>

<p style="font-size:24px;"><font color="DarkSlateGrey"><b> *All Prices are inclusive of tax.</b></font></p>

</body>
</html>