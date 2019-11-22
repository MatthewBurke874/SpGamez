<DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
  	<meta charset="utf-8">
    <title>Login and Registration Form Design</title>
  	<link rel="stylesheet" type="text/css" href="">
  </head>
  <body style = "background: url(https://cdn4.vectorstock.com/i/1000x1000/44/13/funny-cartoon-whale-jumps-out-of-the-water-vector-13784413.jpg); background-size: 100%;">  
      <div class="login-page">
      <div class="form">
         <form class="register-form"/>
         <input type="text" placeholder="user name"/>
         <input type="text" placeholder="password"/>
         <input type="text" placeholder="email id"/>
         <button>Create</button>
         <p class="message">Already Registered? <a href="#" </a></p>
         </form>
         <form class="login-form">
         <input type="text" placeholder="user name"/>
         <input type="password" placeholder="password"/>
         <button>login</button>
        <p class="message">Not Registered? <a href="#">Register</a></p>
         </form>
         </div>   
         </div>   
           <script>
           $('.message a').click(function(){
           $('form').animate({height: "toggle", opacity: "toggle"}, "slow");
    });
           </script>                                        
      <div class="search-box">
         <input class="search-txt" type="text" name=""  placeholder="Type to search">
  		<a class="search-btn" href='#'>
    <i class="fas fa-search"></i>  
  		</a>
      </div>                        
        <ul>
         <li><a href="#platformers">Platformers</a></li>
         <li><a href="#racing">Racing</a></li>
         <li><a href="#adventure">Adventure</a></li>
         <li><a href="#rpg">Rpg</a></li>
       </ul>  
         <h2><p style='padding: 2px 6px 4px 20px; background-color: #339FFF; border: #FFFFFF 2px solid'>Platformers</p></h2>
         <h2><p style='padding: 2px 6px 4px 20px; background-color: #339FFF; border: #FFFFFF 2px solid'>Racing</p></h2>
         <h2><p style='padding: 2px 6px 4px 20px; background-color: #339FFF; border: #FFFFFF 2px solid'>Adventure</p></h2>
         <h2><p style='padding: 2px 6px 4px 20px; background-color: #339FFF; border: #FFFFFF 2px solid'>Rpg</p></h2>
         <h3><p style='padding: 2px 6px 4px 20px; background-color: #339FFF; border: #FFFFFF 2px solid'>About</p></h3> 
         <h3><p style='padding: 2px 6px 4px 20px; background-color: #339FFF; border: #FFFFFF 2px solid'>Contact</p></h3>                
  </body>
</html>

