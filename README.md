# My_Webpage
<!DOCTYPE HTML>
  <HTML lang="en">
  
  <head></head>
      <meta charset="utf-8">
           <title>Creating Edit Box</title>
  <style type="text/css">
  body{
    margin: 30px;
    padding: 30px;
    background-color:transparent;
  }



  .style1{
    color:#FF5733 ; 
    font-style: bold;
   
  }
   .style2{
     color:#FFC300; 
    font-family: arial;
     font-size: 100;
   }
 #tb1{background-color:green;
  text-decoration:underline;
  font-weight: bold;
  opacity: 0.4;
 display: inline;
 }

 #fld{
  width:50%;
}

 a.skip-link {
    left:-999px;
    top:-999;
    position:absolute;
    width:1px;
    height:1px;
    overflow:hidden;
    z-index:-999;
}
a.skip-link:focus, a.skip-link:active {
    color: #fff;
    background-color:#000;
    left:0;
    top: 0;
    width: 25%;
    height: auto;
    overflow:auto;
    margin: 0 auto;
    padding:5px;
    border-radius: 15px;
    border:4px solid yellow;
    text-align:center;
    font-size:1.2em;
    z-index:999;
}

 #nav{
background-color: green;
display:inline-block;
 text-align: center;
 border-radius: 20px;
 }
#nav ul li{
list-style-type: none;
float: left;
margin: 20px

}
#nav ul li a{

text-decoration: none;
}
#nav ul li a:hover{
 text-decoration: underline;
color: red;
}   
#main{
  margin:10px; 
float:center;
}
   
#b1{width:100px;
     height: 50px;  
        background-color:#2C14B3 ;
        font-size:20px;
       font-weight:bold;
     
 }

 #b2{
        background-color:#FF5733 ;
        font-size:20px;
       font-weight:bold;
      margin:30px;
     width: 100px;
height:50px;
}  
#myinfo{ background-color:yellow;
 width: 150px;
height: 100px;
border-radius: 30px;
padding: 5px;  
font-weight: bold;
 }
  
</style>
  </head>
  <body>
          <a href="main"class="skip-link">skip to main content</a>
<div>
  <img src="C:\Users\prola\OneDrive\Documents\pen (1)icon.svg"width="50px"height="50px"align="left">
</div>
<header role="banner"> 
  <div id="nav"role="navigation">
          
   
    <ul>	
              <li><a href="#" class="style2">teacher</a>
              <li><a href="#" class="style2">student</a>
              <li><a href="#" class="style2">doctor</a>
   </ul>
   <br><br>
    </div>
     <br><br>
    </header>
	          <span id="myinfo"><u>provide all infomations:</span></u>
               <h1 id="main"><mark><u><a href="main-content">Registration Form<a/></u></mark></h1>
               
   
   <form>   
   <fieldset id="fld" roll="fieldset">
               <legend aria-roll="contact"><u><b>contact info:</u></b></legend><br/><br/>
               <b class="style1 ">First Name:</b><br/>
               <input type="text"name="txtbox"><br/><br/>
               <b class="style1 ">Last Name:</b><input type="text"name="txtbox"><br/><br/>
               <b class="style1 ">Email:</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text"name="email"size="40"placeholder="please enter a valid email" required="[a-zA-Z0-9symbol]+">required<br/><br/>
               <b class="style1 ">Password:</b>&nbsp;&nbsp;<input type="Password"name="pwd"placeholder="enter password"required>*<p/>
               <!reading order is not sequential for gender> 
               <b class="style2">Gender:</b><input type="radio"name="gender"value="male"checked="male">male
                                     <input type="radio"name="gender"value="other">other              
                                     <input type="radio"name="gender"value="female">female <p/>
         <!Reading order is not sequential for age>    
        <b class="style2">Age:</b><input type="checkbox"name="cb1"value="18-25"checked="18-25">18-25
                               <input type="checkbox"name="cb3"value="35-45"    >35-45
                             <input type="checkbox"name="cb2"value="25-35"    >25-35
                            
                     </fieldset>
                 <form/><p/>
                 <b class="style2">Country Of Birth:</b>
                    <select name="country">
                     <option>BANGLADESH</option>
                     <option>INDIA</option>
                     <option>USA</option>
                      <option>UK</option>
                       <option>ARMENIA</option> 
         
                    </select><br/><br/>
      <Ol type="A">
          <li> <a href ="https://www.google.com"target="blank"class="style2"> click here to visit google hompage.</a><br/><br/>  
     </Ol>
      <p id="tb1"> I am creating a basic table where i can insert some tabular data. </p>   
<table border="2"height="100px"width="100px"align="center "bgcolor="pink"cellspacing="5px"cellpadding="5px">
   <caption><b>personal contact info</caption><b>

   <tr>
     <td>0</td>
     <th scope="col"> First name</th>
     <th scope="col"> Last name</th>
      <th scope="col"> Phone no</th>
   </tr>

  <tr>
     <td>1.</td>
     <th scope="row"> proloy</th>
     <td > biswas</td>
      <td> 2672625005</td>
   </tr>
     <tr>
     <td>2.</td>
     <th scope="row"> protim</th>
     <td> biswas</td>
      <td> 2672625055</td>
   </tr>
     <tr>
     <td>3.</td>
     <th scope="row"> seema</th>
     <td> biswas</td>
      <td> 2672623303</td>
   </tr>
</table>




          <!there is no label in button>
         <input type="submit"name="btn"value="submit " id="b1">
         <input type= "submit"name="btn"value="cancel" id="b2">
         
   
 


 

<footer>
        <a href=" #" roll="contentinfo"class="style1"> click here to go back to top</a>
</footer>
       </body>
 </HTML>
