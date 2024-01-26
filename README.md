# STA553
<!DOCTYPE html>
<html lang = "en">                        <!-- open html tag: required  -->
  <head>                                  <!-- open page header: required -->
    <title>My First Web Page</title>      <!-- page title appears on the tab -->
    <style>
        body{
            font-family: Arial, sans-serif;
            background-image: url('img/bgIMG.jpg');
            font-size: 15px;
            line-height: 25px;
        }
       
        table, th, td {
               border-collapse: collapse;
        }
        
        h3 {
		    font-family:  Verdana, sans-serif; 
            font-weight: bold;
            font-size: 16px;
            text-align: center;
           font-variant: small-caps;
        }
        
        h2 {
		    font-family:  Verdana, sans-serif; 
            font-weight: bold;
            font-size: 18px;
           font-variant: small-caps;
        } 
        
        a{
           text-decoration:none; 
           target-name:new;
           target-new:tab;
           font-size: 14px; 
           font-style: italic;
        }
      </style>
  </head>                                 <!-- close page header: required -->
    
  <body>                                  <!-- open html body: required -->
    <!-- All contents of the web page MUST be placed between <body> and </body> -->
 <br><br>
 <table border = 2 bordercolor="gray" bgcolor='#f6f6f6'  width=80%  align = center> 
    <tr>
      <TD>     
        <br>      
    <center><img src="img/w02-wculogo.jpg" alt="w02-wcu-logo" width = "300" height = "90"></center> 
    <center><h2><font color="darkblue"> Your Name</font></h2> 
        
      <!-- contact information  -->
    <table border = 0 bordercolor="darkgreen" width=80%  align = center> 
        <tr>
            <TD style="width:40%; text-align: left;line-height: 19px; ">
             <font style ='font-family: "Times New Roman", Times, serif; font-style: normal;' color = "navy"  size="3">
             Phone: xxx-xxx-xxxx<br>
             Email: xxx@wcupa.edu <br>
             GitHub:               <br>
             LinkEdin
            </font>
            </TD>
            
            <TD style="width:20%"></TD>

             <TD style="width:40%; text-align: right; line-height: 19px; ">
             <font style ='font-family: "Times New Roman", Times, serif; font-style: italic' color = "navy"  size="3">
                25 University Avenue <br>
                Department of Mathematics<br>
                West Chester University <br>
                West Chester, PA 19383.
             </font>
           </TD>
        </tr>
        </table>
        
    <br>
    <br>
    <table border = 0 bordercolor="darkgreen" width=90%  align = center> 
        <tr>
            <TD style="width:20%">
                 <h3><font color = "navy">Short Bio</font></h3>
            </TD>
            
            <TD style="width:5%"></TD>
            
            <TD style="width:75%">
                  <p> write your short bio here.....</p>
            </TD>
        </tr>

         <tr>
            <TD style="width:20%">
                <h3><font color = "navy">Education</font></h3>
            </TD>
             
            <TD style="width:5%"></TD>
             
            <TD style="width:75%">
                  <p> your educational background.....</p>
            </TD>
        </tr>        
        
         <tr>
            <TD style="width:20%">
                <h3><font color = "navy">Experience</font></h3>
            </TD>
             <TD style="width:5%"></TD>
             
            <TD style="width:75%">
                  <p> write your professional experience here.....</p>
            </TD>
             
        </tr>
        
         <tr>
            <TD style="width:20%">   
              <h3><font color = "navy">Projects</font></h3>
            </TD>
             
            <TD style="width:5%"></TD>
             
            <TD style="width:75%">
               <p> list your project here.....</p>
                <ol>
                <li><a href="https://pengdsci.github.io/eCOTS2022/" 
                       onclick="return !window.open(this.href);"> 
                    An end-to-end project-based approach to teaching data mining process 
                    <img src="img/outlink.jpg" width=12 height=12>.</a></li>
                 <li><a href="proj/published-01.pdf" 
                       onclick="return !window.open(this.href);"> 
                    Semiparametric tests for equality of two independent variances
                     <img src="img/outlink.jpg" width=12 height=12>.</a></li>
                  <li><a href="proj/published-03.pdf" 
                       onclick="return !window.open(this.href);"> 
                    A new formulation of generalized gamma: some results and applications
                      <img src="img/outlink.jpg" width=12 height=12>. </a></li>
                    <li><a href="proj/UnderReview03-IM.pdf" 
                       onclick="return !window.open(this.href);"> 
                    A general framework of semiparametric polychotomous logit regression
                        <img src="img/outlink.jpg" width=12 height=12>.</a></li> 
                </ol>
            </TD>
        </tr>
        
        <tr>
          <TD style="width:20%">
            <h3><font color = "navy">Skills</font></h3>
          </TD>
            
            <TD style="width:5%"></TD>
            
            <TD style="width:75%">
             <p> list your skills here.....</p>
          </TD>
        </tr>        
       </table>   
      </TD>
    </tr>        
   </table> 
  <br><br><br><br>              
 </body>                                 <!-- close html body: required -->
</html> 
