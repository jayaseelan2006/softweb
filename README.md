# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

</head>

<body>
  <!----Navbar-->

  <nav class="navbar navbar-expand-lg navbar-dark" id="navbar">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Vipro</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item">
            <a class="nav-link" href="#HOME"><b>Home</b></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"PEOPLE><b>People</b></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><b>About</b></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><b>Contact</b></a>
          </li>


        </ul>
        <button class="btn p-2 my-lg-0 my-2 "><b>Sign In</b></button>
      </div>
    </div>
  </nav>




  <section id="home">
    <h1 class="text-center">SOFTWARE COMPANY</h1>
    <p>The fastest, simplest, and most secure way to measure development performance.</p>
    <div class="input-group m-4">
      <input type="text" class="form-control" placeholder="Email Address">
      <button class="btn signin">Grt Started</button>

    </div>
  </section>


  <section id="about">
        <div class="contaniner-fluid">
             <div class="row">
                 <div class="col-lg-6 col-md-6 col-12">
                         <img src="software.png" class="img-fluid">

                 </div>
                 <div class="col-lg-6 col-md-6 col-12">
                         <h1>ABOUT US</h1>
                         <p><b> Wipro Limited is a leading global information technology,
                             consulting and business process services company.
                             Wipro is recognized globally for its comprehensive portfolio of services,
                             practitioners’ approach to delivering innovation,
                             and as an organization with a wide commitment to sustainability and business ethics.
                             Wipro has more than 131,000 employees and clients across 53 countries.</b></p>

                 </div>

             </div>

        </div>

  </section>


  <section id="people">
    <div class="container m-5">
       <h1 class=" text-center my-5">PEOPLE</h1>
       <div class="row">
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo1.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">CEO</h5>
                  <a href="#" class="btn signin">MR.JAYASEELAN</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo6.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">CO FOUNDER</h5>
                  <a href="#" class="btn signin">MR.SURENDHARAN</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo2.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">CO FOUNDER</h5>
                  <a href="#" class="btn signin">MR.SIVAKUMAR</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo3.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">FOUNDER</h5>
                  <a href="#" class="btn signin">MR.SURIYAPARAKASH</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo4.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">DIRECTOR</h5>
                  <a href="#" class="btn signin">MR.PANDIKUMAR</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo5.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">DIRECTOR 1</h5>
                  <a href="#" class="btn signin">MR.SRIDHER</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo8.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">CEO 1</h5>
                  <a href="#" class="btn signin">MR.ELAVARASU</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo7.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">MANAGER</h5>
                  <a href="#" class="btn signin">MR.HARISH</a>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-4 col-12">
              <div class="card">
                <img src="photo10.jpg" class="card-img-top" >
                <div class="card-body">
                  <h5 class="card-title">Ass-MANAGER</h5>
                  <a href="#" class="btn signin">MR.VIGNESH</a>
                </div>
              </div>
            </div>
       </div>
    </div>
  </section>
     

  <section id="contact">
         <div class="container">
             <div class="row">
                <div class="col-lg-6 col-md-6 col-12">
                    <img src="round.jpeg">
                </div>  
                    <div class="col-lg-6 col-md-6 col-12">
                       <h1>CONTACT US</h1>
                       <form>
                        <input type="text" class="form-control"
                        placeholder="Enter your name">
                        <input type="email" class="form-control"
                        placeholder="Enter your mail">
                        <textarea class="form-control"
                        placeholder="Enter your message"></textarea>
                        <button class="btn signin"> Send message</button>
                      </form>

                
                    </div>
             </div>
         </div>

  </section>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dict/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>

## CSS
@import url('https://fonts.googleapis.com/css2?family=Poppins& display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins'sans-serif;
}
#navbar{
    position: sticky;
    top: 0;
    left: 0;
    z-index: 100;
    padding: .5rem 5rem;
    box-shadow: 5px 5px 20px rgba(0,0,0,.5);
    background: black;
}
.navbar .navbar-brand{
    font-size: 25px;
    font-weight: 800;
    color:#29f700 ! important;
}
#navbarSupportedContent a:hover{
    border-bottom: 2px solid #29f700;
}
#navbarSupportedContent button{
    background: #29f700;
    width: 5rem;
    border-radius: 15px;
}
section{
    width:100%;
    min-height:100vh;
    display: flex;
    justify-content:center;
    align-items:center;

}
#home{
    background: url(img1.png);
    background-size: cover;
    background-position: center;
    flex-direction: column;

}

#home h1{
    font-size: 60px;
    color: white;
    letter-spacing: 3px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    text-shadow:0px 1px 0px #ccc,
                0px 2px 0px #ccc,
                0px 3px 0px #ccc,
                0px 4px 0px #ccc,
                0px 5px 0px #ccc,
                0px 6px 0px #ccc,
                0px 7px 0px #ccc;
}
#home p{
    font-size: 18px;
    color: #fff;
}

#home .input-group{
    width: 40%;
    height: 45px;

}
.signin{
    background: green !important;
    color: white !important;
    box-shadow: 2px 4px 5px rgba(0,0,0,.5);
}



#about h1{
    font-weight: 800;
    font-size: 50px;
  
}

#people{
    background:#948b8b;
}
#people h1{
    font-size: 50PX;
    letter-spacing: 2PX;
    font-weight: 700;

}
#people img{
    width: 200px;
    height: 250px;
}
.card{
    width: 210px;
    height: 210px;
    background: #948b8b !important;
    border: none !important;
    box-shadow: 15px 20px 20px rgba(0,0,0,.3),
                inset 4px 4px 10px white;
    border-radius: 20px !important;
    overflow: hidden;
    justify-content: center;
    align-items: center; 
    margin: 20px 60px;           
            
}


```


## OUTPUT:
![alt text](<Screenshot 2024-04-29 025532.png>)
![alt text](<Screenshot 2024-04-29 025544.png>)
![alt text](<Screenshot 2024-04-29 025559.png>)
![alt text](<Screenshot 2024-04-29 025630.png>)
![alt text](<Screenshot 2024-04-29 025655.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
