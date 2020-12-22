

<!DOCTYPE html>
<html>
    <head>
        <title>Home</title>
        <style>
          #my_headerbackground {
              background-image: url(Untitled-1.jpg);
              height: 400px;
          }
          img {
              
              padding-left: 40px;
              padding-top: 65px;
              float: left;
          }
          
          #profile_header {
              background-color: black; 
              display: inline-block;
              margin-top: 90px;
              margin-left: 15px;
              padding: 10px;
              font-family: Times New Roman;
              color:white;
              font-size: 20px;
              font-weight: bold;
          }
          #profile_header2 {
              background-color: black; 
              display: inline-block;
              margin-left: 15px;
              padding: 10px;
              font-family: Times New Roman;
              color:white;
              margin-top: 15px;
              font-size: 15px;
              font-weight: bold;
          }
          article {
              margin-top: 10px;
              background-color: #eceaeb;
              float: left;
              width: 70%;
              color: black;
              height: 550px;
              padding-right: 50px;
          }
          #article_heading {
              margin-top: 5%;
              color: white;
              background-color:#ad0a0b;
              display: inline-block;
              padding: 10px;
              font-size: 25px;
              margin-left: 40px;
          }
          #article_paragraph {
              margin-left: 30px;
              font-size: 20px;
          }
          nav {
              background-color: #eceaeb;
              height: 550px;
              width: 25%;
              float: right;
              margin-top: 8px;
              padding-left: 5   px;
              margin-bottom: 2%;
          }
          #nav_heading {
              margin-top: 15%;
              color: white;
              background-color: #0b7bad;
              display: inline-block;
              padding: 10px;
              margin-left: 20px;
              font-size: 25px;
              padding-right: 100px;
          }
          #nav_link {
              font-size: 25px;
              list-style-type: none;
              padding-bottom: 20px;
              display: block;
          }
          footer {
              background-color: #ad0a0b;
              float: left;  
              height: 200px;
              width: 100%;
          }
          #footer_title {
              color: white;
              font-size: 25px;
              margin-top: 4%;
              margin-left: 30px;
          }
          #footer_links {
              color: white;
              text-decoration: none;
              font-size: 20px;
              margin-left: 30px;
              padding-bottom: 10px;
          }
          #footer_author {
              float: right;
              color: white;
              font-size: 30px;
              padding-right: 20px;
          }
        </style>    

    </head>
    <body>
        <header id="my_headerbackground">
            <img src="me.jpg" height="250px" width="300px">
            <ul>
                <li id="profile_header">Kenneth T. Albino</li><br>
                <li id="profile_header2">Web Development Activity</li><br>
                <li id="profile_header2">kenot269@gmail.com</li><br>
                <li id="profile_header2">San Isidro Labrador Quiot, Cebu City</li>
            </ul>
        </header>
        <article>
            <h2 id="article_heading">Web Development</h2>
            <p id="article_paragraph"> Web development is the work involved in developing a Web site for the Internet 
                (World Wide Web) or an intranet (a private network). Web development can range 
                from developing a simple single static page of plain text to complex Web-based 
                Internet applications (Web apps), electronic businesses, and social network 
                services. A more comprehensive list of tasks to which Web development commonly
                refers, may include Web engineering, Web design, Web content development, client 
                iaison, client-side/server-side scripting, Web server and network security configuration, 
                and e-commerce development.
            </p>
            <p id="article_paragraph"> Web development can range from developing a simple single static page of plain text to complex Web-based 
                Internet applications (Web apps), electronic businesses, and social network 
                services. A more comprehensive list of tasks to which Web development commonly
                refers, may include Web engineering, Web design, Web content development, client 
                iaison, client-side/server-side scripting, Web server and network security configuration, 
                and e-commerce development.
            </p>
            <p id="article_paragraph">A more comprehensive list of tasks to which Web development commonly
                refers, may include Web engineering, Web design, Web content development, client 
                iaison, client-side/server-side scripting, Web server and network security configuration, 
                and e-commerce development.
            </p>
        </article>
        <nav>
            <p id="nav_heading">Other Links</p>
            <ul>
                <li id="nav_link"><a href="log%20in.html">Login</a></li>
                <li id="nav_link"><a href="register.html">Registration</a></li>
                <li id="nav_link"><a href="#">About Me</a></li>
                <li id="nav_link"><a href="#">My Image Gallery</a></li>
                <li id="nav_link"><a href="#">Contacts</a></li>
            </ul>
        </nav>
        <footer>
            <p id="footer_title">Footer Links</p>
            <span id="footer_author">&copy; Kenneth T. Albino 2020</span>
            <a href="#" id="footer_links">About Me</a> <br>
            <a href="#" id="footer_links">My Image Gallery</a> <br>
            <a href="#" id="footer_links">Contacts</a>
            
        </footer>
    </body>
</html>
