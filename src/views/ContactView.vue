<template>
      
  
  <h3 id="contact">if you liked what you saw, please do not hesitate to
    <br id="contact-me"><span id="contactme">CONTACT ME!</span></h3>
    
    
    
    
    
    
       <div class="social">
         <a href="https://www.instagram.com/xx.aliyahh.xx?r=nametag" id="social-link"><i class="fa-brands fa-instagram"></i>Instagram</a>
         <br><a href="#" id="social-link"><i class="fa-brands fa-slack"></i>Slack</a>
         <br><a href="https://twitter.com/golden_ghoull?s=21&t=XF4X7Qtb2OF-AQkjicMGug" id="social-link"><i class="fa-brands fa-twitter"></i>Twitter</a>
         <br><a href="https://github.com/aliyahdutoit" id="social-link"><i class="fa-brands fa-github"></i>Github</a>
        </div>
        
        <br><i class="fa-solid fa-phone"></i> +27 61 440 2813
        <br><i class="fa-solid fa-envelope"></i>  aliyah.dutoit@gmail.com
        <br><i class="fa-solid fa-location-dot"></i> Cape Town, South Africa
        <br>
        <br>
        <!--Contact Form section-->
        <div id="form_">
          
        <form class="align-self-center" action="https://formspree.io/f/xdojpryw" method="POST" id="form">
      
          <label for="fname" id="labels">Your Name</label>
          <input type="text" id="fname"  name="firstname" placeholder="Your name..">
      
          <label for="cname" id="labels">Company Name</label>
          <input type="text" id="cname" name="companyname" placeholder="Your company name..">
      
          <label for="email" id="labels">Your Email</label>
          <input type="text" id="email" name="email" placeholder="Your email..">
      
          <label for="message" id="labels">Message</label>
          <textarea id="message" name="message" placeholder="Write something.." style="height:200px"></textarea>
      
          <input type="submit" id="button" value="Submit"  onclick="myFunction()">
      
        </form>
      </div>
</template>

<script>

    export default  {

    }
    </script>

<style>
h1 {
  font-weight: bolder;
}
/*Contact info*/

#contact {
    font-family: 'Courier New', Courier, monospace;
    font-weight:bold;
    padding-top: 30px;
  }
  
  #contactme {
    font-weight: bolder;
    font-size: 80px;
  }
  
  #social-link {
    text-decoration: none;
    color: #531063;
    font-weight: bold;
    font-size: 20px;
    padding: 20px;
  }


  /*Contact Form*/
  /* Style inputs with type="text", select elements and textareas */
  input[type=text], select, textarea {
    width: 320px; /* Full width */
    padding: 12px; /* Some padding */ 
    padding-left: 10px;
    position: relative;
    margin-left: 40px;
    border: 1px solid #ccc; /* Gray border */
    border-radius: 4px; /* Rounded borders */
    box-sizing: border-box; /* Make sure that padding and width stays in place */
    margin-top: 6px; /* Add a top margin */
    margin-bottom: 16px; /* Bottom margin */
    resize: vertical /* Allow the user to vertically resize the textarea (not horizontally) */
  }
  
  /* Style the submit button with a specific background color etc */
  input[type=submit] {
    background:linear-gradient(to bottom right, violet, rgb(100, 42, 139));
    color: white;
    padding: 13px 40px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  /* When moving the mouse over the submit button, add a darker green color */
  input[type=submit]:hover {
    background-color: #b09cd1;
  }
  
  #button {
    margin-left: 130px;
  }
  
  /* Add a background color and some padding around the form */
  #form {
    border-radius: 5px;
    background-color: #d6cae5;
    padding: 30px;
    width: 400px;
    box-shadow: 0 1rem 2rem rgba(0, 0, 0, .67);
    
  }
  
  #form {
    padding-left: 0px;
    margin-bottom: 40px;
    /* float: right; */
  }
  
  
  #labels {
    padding-left: 40px;
  }
  
#form_ {
  padding-left: 585px;
}

</style>