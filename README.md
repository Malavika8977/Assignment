# Assignment Resume Creation
# Codepen link(https://codepen.io/Malavika-Mulupuru/pen/MYYwLJL)

<html>
  <head>
    <style>
      table,th,td{
        border:2px solid black;
        border-collapse:collapse;
        padding:5px;
      }
      h1{
  color:black;
  font-size:50px;
  Text-align:center;
}
h3{
  font-size:30px;
  background-color:grey;
}
body{
  font-size:17px;
}

    </style>
  </head>
  
  <body>
    <h1>Resume</h1>
    <h3>Career Objective</h3>
    <p style="font-size:20px">                    "To pursue a challenging career where I can apply my technical skills and continuously enhance my 
            knowledge in a professional environment, contributing effectively to the organization's success."</p>
    <h3>Educational Details</h3>
    <table style="width:100%">
      <tr>
        <th>QUALIFICATION</th>
        <th>YEAR OF PASSING</th>
        <th>INSTITUTION</th>
        <th>PERCENTAGE</th>
      </tr>
      <tr>
        <td>MCA</td>
        <td>2026</td>
        <td>Sri Venkateswara University,Tirupati</td>
        <td>-</td>
      </tr>
      <tr>
        <td>B.Sc. in Computer Science</td>
        <td>2024</td>
        <td>Sri Pragathi Degree College</td>
        <td>95%</td>
      </tr>
      <tr>
        <td>Intermediate</td>
        <td>2021</td>
        <td>Sri Pragathi Junior College</td>
        <td>93.7%</td>
      </tr>
      <tr>
        <td>10th Standard</td>
        <td>2019</td>
        <td>A.V.K.R.Z.P High School</td>
        <td>97%</td>
      </tr>
    </table>
    <h3>Area of Interest</h3>
    <ul type="disc">
      <li>Software Engineering</li>
      <li>Frontend Web Development</li>
    </ul>
    <h3>Key Skills</h3>
    <p><b> Relevant Coursework:</b>
      <ul type="disc">
      <li>Programming languages: Python,Java,Web Development</li>
        <li>Testing: Performance Testing</li>
    </ul>
    <b> Strength:</b>
   <ul type="disc">
     <li> Believe in hardwork</li>
     <li>Effective communication skills</li>
     <li>Always ready for taking risk</li>
     <li>Sharp analytical and decision-making skill</li>
     <li>Fast learner and positive thinker</li>
    </ul>
    <h3>Personal Details</h3>
    <b>Name:</b>Malavika<br>
    <b>Date Of Birth:</b>28-06-2004<br>
    <b>Gender:</b>Female<br>
    <b>Nationality:</b>Indian<br>
    <b>Religion:</b>Hindu<br>
    <b>Languages:</b>English,Telugu<br>
    <b>Hobbies:</b>
    <ul type="bullet">
      <li>Sports</li>
      <li>Reading Newspaper</li>
      <li>Reading story books</li>
    </ul>
    </p>
  <h3>Declaration</h3>
  <p>"I hereby declare that all the information provided above is true and correct to the best of my knowledge.”</p>
  <p><b>Place:Nellore</b><br>
    <b>Date:19-04-2025</b></p>
  <p style="text-align:right"><b>Signature</b><br>M.Malavika</p>
  </body>
  </html>


  # Assignment Simple Calculator
# Codepen link(https://codepen.io/Malavika-Mulupuru/pen/WbbxEBQ)
<!DOCTYPE html>
<head>
</head>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: #222;
    margin: 0;
}

.calculator {
    background:#ddd;
    border-radius: 20px;
    padding: 20px;
    width: 250px;
   
}

.display {
    background: grey;
    height: 60px;
    border-radius: 10px;
    margin-bottom: 15px;
    font-size: 2rem;
    text-align: right;
    padding: 10px 15px;
    color:black;
   
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
}

.buttons div {
    background: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 10px;
    font-size: 1.5rem;
    font-weight: bold;
    
}

.buttons .op {
    background: #f0f0f0;
    color: black;
}

.buttons .equal {
    background: orange;
    color: white;
}
</style>
</head>
<body>
    <div class="calculator">
        <div class="display">0</div>
        <div class="buttons">
            <div>7</div>
            <div>8</div>
            <div>9</div>
            <div class="op">÷</div>

            <div>4</div>
            <div>5</div>
            <div>6</div>
            <div class="op">×</div>

            <div>1</div>
            <div>2</div>
            <div>3</div>
            <div class="op">−</div>

            <div>0</div>
            <div>.</div>
            <div class="op">+</div>
            <div class="equal">=</div>
        </div>
    </div>
</body>
</html>

# Assignment: Introduction,Fundamentals, Basic Element,Headings,Paragraph
# Codepen link(https://codepen.io/Malavika-Mulupuru/pen/bNNeLKB)
<html>
  <body style="background-color:#B5C2A8;">
    <p>This paragraph is left aligned</p>
    <p style="text-align:center">This paragraph is center aligned</p>
    <p style="text-align:right">This paragraph is right aligned</p>
    <p style="color:green">This text is green</p>
    <p style="font-family:'Trebuchet MS';">This is Trebuchet.</p>
    <h1>This is big text.</h1>
    <p style="font-size:small;color:white;font-family: Arial;">This text is arial,small and white</p>
    <p>This is a link to<a href="https://www.bing.com/search?filters=ufn%3a%22Stevenson+High+School+(Lincolnshire%2c+Illinois)%22+sid%3a%22bd52cffa-2a80-c6f0-cadd-aaa45c4bef32%22&qs=MB&pq=stevenson+hi&sk=CSYN1&sc=16-12&pglt=425&q=stevenson+high+school&cvid=46ae82113bbc410d91368958d03e0966&gs_lcrp=EgRlZGdlKgYIARAuGEAyBggAEEUYOTIGCAEQLhhAMgYIAhAAGEAyBggDEAAYQDIGCAQQABhAMgYIBRAAGEAyBggGEAAYQDIGCAcQABhAMgYICBAAGEDSAQg4MTg5ajBqMagCALACAA&FORM=ANNTA1&PC=ACTS"> Stevenson High School.</a></p>
    <p>This is an email link to<a href="smith@gmail.com"> Mrs Smith</a></p>
    <img src="https://wallpaperaccess.com/full/1101027.jpg"style="display:block; margin:auto;width: 300px; height: 300px;">
  </body>
</html>

# Assignment: Basic Elements,Attributes, Formatting and Quotation, Lists
# Codepen link(https://codepen.io/Malavika-Mulupuru/pen/azzBLQY)

<html>
  <head>
  <style>
    body{
  background-color:#B5C2A8;
}
  .link{
  text-align:center;
}
.Create{
  text-align:center;
}
  </style>
    
  </head>
  <body>
    <h1 style="color:red;text-align:center">
      The Beatles</h1>
    <img src="https://www.itl.cat/pngfile/big/206-2061097_the-beatles-wallpaper-beatles-band.jpg" style="height:100; width:300; display:block; margin:auto">
    <p class="link"><a href="https://www.thebeatles.com/">This is a link to the official Beatles Website</a></p>
    <p>Albums</p>
    <ul>
      <li>With the Beatles</li>
      <li>Let It Be</li>
      <li>Yellow Submarine</li>
      <li>Revolver</li>
      <li>Sgt Pepper</li>
      <li>Abbey Road</li>
    </ul>
    <div class="Create">
    <p>Created 9-5-14</p>
      <p> by <a href="https://en.wikipedia.org/wiki/Joseph_Y._Yun">Joseph Yun</a>
      </p>
    </div>
  </body>
</html>

# Assignment: Header that links to home,about,contact page
# Codepen link(https://codepen.io/Malavika-Mulupuru/pen/vEEgQOb)

<html>
  <head>
    <style>
      .navbar{
  background:black;
  color:white;
  padding:20px;
  width:100%;
  font-size:40px;
    }
    </style>
  </head>
  <body>
<header>
      
      <nav class="navbar">
        <h2 style="text-align:center; color:green">W3 schools</h2>
        <ul class="nav-links">
          <li><a href="https://www.w3schools.com/">Home</a>
          </li>
          <li><a href="https://www.w3schools.com/about/">About</a>
          </li>
          <li>
            <a href="https://www.w3schools.in/page/contact">Contact</a>
          </li>
        </ul>
        </nav>
    </header>
  </body>
</html>

# Assignment: Semantic and Non-semantic special symbols and characteristics
# codepen link:(https://codepen.io/Malavika-Mulupuru/pen/MYYmVwa)
<html>
  <head>
    <style>
      body {
  font-family: Arial, sans-serif;
  background-color: orange;
  margin: 20px;
  padding: 20px;
}

h1 {
  text-align: center;
  color: blue;
}

.departments {
  list-style-type: square;
  padding-left: 40px;
}

.departments >li {
  margin-bottom: 20px;
  font-size: 1.5rem;
  font-weight: bold;
}

.departments ul {
  margin-top: 10px;
  list-style-type: circle;
  padding-left: 20px;
}

.departments a {
  text-decoration: none;
  color: #0077cc;
  font-size: 1.2rem;
}

.departments a:hover {
  text-decoration: underline;
  color: #005999;
}
    </style>
  </head>
<body>

  <h1>Academics</h1>

  <ul class="departments">
    <li>Arts
      <ul>
        <li><a href="https://en.wikipedia.org/wiki/English_language">English</a></li>
        <li><a href="https://en.wikipedia.org/wiki/Sociology">Sociology</a></li>
      </ul>
    </li>

    <li>Science
      <ul>
        <li><a href="https://en.wikipedia.org/wiki/Computer_science">Computer Science</a></li>
        <li><a href="https://maths.iiserb.ac.in/">Mathematics</a></li>
      </ul>
    </li>

    <li>Commerce
      <ul>
        <li><a href="https://www.wallstreetmojo.com/accounting-department/">Accounting</a></li>
        <li><a href="https://en.wikipedia.org/wiki/Business_studies">Business Studies</a></li>
      </ul>
    </li>
  </ul>

</body>
</html>

# Assignment: Add media to webpage
# codepen link:(https://codepen.io/Malavika-Mulupuru/pen/LEExwaZ)
<html>
  <body>
    
    <iframe width="928" height="522" src="https://www.youtube.com/embed/D97zRAqseyY" title="Gaur Gopal Das | Must Watch Motivational video  #motivation #inspiration" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>"
    <br>
    <br>
    <img src="https://th.bing.com/th/id/R.124a1db7be2c13d936d8a71bd43ffd5f?rik=2ZT%2baXLkZYcxWg&riu=http%3a%2f%2fthewowstyle.com%2fwp-content%2fuploads%2f2015%2f01%2fnature-wallpaper-27.jpg&ehk=jIVFSOxLN%2fQKs4hEfZHNWAeXoeXkeEXooP%2fTy9Vwkek%3d&risl=&pid=ImgRaw&r=0" height="400" width="500" alt="nature image" ><br><br>
    <iframe src="https://youtu.be/meOWV1w2GE8" height="300" width="400"></iframe>
  </body>
</html>


# Assignment: Forms
# Codepen Link:(https://codepen.io/Malavika-Mulupuru/pen/bNNgZqE)
<html>
  <head>
  <style>
    .form{
  padding:20px;
  border:2px solid black;
  margin:auto;
  border-radius:20px;
  background-color:#f9f9f9;
}
.form input{
  width:20%;
  border:1px solid black;
  border-radius:5px;
  margin-top:5px;
}
.form label{
 
  font-weight:bold;
}
.form button{
  font-weight:bold;
  background-color:orange;

}
  </style>
  
</head>
  <body>
    <div class="form">
    <form>
      <label for="name">Name:</label>
   <input type="text" id="name"><br><br>
      <label for="age">Age:</label>
      <input type="number" id="age"><br><br>
      <label for="designation">Designation:</label>
      <input name="text" id="designation"><br><br>
      <label for="email">Email:</label>
      <input type="email" id="email"><br><br>
      <label for="pwd">Password:</label>
      <input type="password" id="pwd"><br><br>
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob"><br><br>
      
      <button type="submit">Submit</button>
    </form>
    </div>
  </body>
</html>

# Assignment: Creating a div with Background image and button and text over it
# Codepen link(https://codepen.io/Malavika-Mulupuru/pen/VYYbrvX)
<html>
  <head>
    <style>
    body,html{
  margin:0;
  padding:0;
  font-family: Arial, sans-serif;
}
.title{
  background-image:url('https://tse1.mm.bing.net/th/id/OIP.cNSbI9obHyKD4_vkDoVcOQHaEK?rs=1&pid=ImgDetMain');
  background-size:cover;
  background-position:center;
  position:relative;
  color:white;
  display:flex;
  align-items:center;
  justify-content;center;
}
.content{
  background-color:dark overlay;
  padding:2rem;
  border-radius:10px;
}
button{
  margin-top:1rem;
  padding:10px 20px;
  font-size: 1rem;
  background-color:#ff6b6b;
  border:none;
  color:white;
  cursor:pointer;
  border-radius:5px;
}
button:hover{
   background-color:#ff3b3b;
}
      
    </style>
    </head>
  
  <body>
    <div class="title">
      <div class="content">
        <h1>welcome to my website</h1>
        <button>Get Start</button>
      </div>
    </div>
        </body>
</html>

# Assignment: Border Margins,Padding, Box Model,Text,Font
# Codepen link(https://codepen.io/Malavika-Mulupuru/pen/wBBdyvp)
<html>
  <head>
  <style>
    body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  display: flex;
  flex-wrap: wrap;
  padding: 40px;
  justify-content:center;
}

.box {
  width: 300px;
  height: 400px;
  border: 2px solid #333;
  margin: 10px;
  background-image: url('https://cdn.magicdecor.in/com/2024/06/04183214/Beach-Sunset-Wallpaper-Mural.jpg');
  
  background-size: cover;
  background-position: center;
  position: relative;
  
}

.content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  background-color: rgba(0, 0, 0, 0.5); 
  padding: 20px;
  border-radius: 10px;
  color: white;
}

.content h2 {
  font-size: 20px;
   }

button {
  padding: 10px 20px;
  font-size: 16px;
  background-color: #ff6b6b;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

  </style>
    
  </head>
  <body>
    <div class="box">
      <div class="content">
        <h2>Box 1</h2>
        <button>Click</button>
      </div>
    </div>
        <div class="box">
      <div class="content">
        <h2>Box 2</h2>
        <button>Learn</button>
      </div>
    </div>
        <div class="box">
      <div class="content">
        <h2>Box 3</h2>
        <button>Start</button>
      </div>
    </div>


  </body>
</html>
