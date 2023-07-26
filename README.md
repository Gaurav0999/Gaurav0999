<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">


    <title>Document</title>
    <style>
        #lik{
            display: block;
        }
        .font-div{
            width: 33%;
        }
        img{
            height: 100%;
            width: 100%;
        }
        #use{
            padding: 10px 14px;
        }

    </style>
</head>
<body>
 
   <header>
       <div class="container">
           <div class="row no-gutters">
               <div class="col-lg-4 col-md-4">
              <img src="me2.jpg" >
               </div>
               <div class="col-lg-8 col-md-8 ">
                   <div class="d-flex  flex-column">
                       <div class="p-5 bg-dark text-white">
                           <div class="d-flex flex-row justify-content-between align-items-center " >
                               <h1 class="d-block">khan shakil</h1>

                               <div>  <i class="fa fa-facebook"></i></div>
                               <div>  <i class="fa fa-google-plus"></i></div>
                               <div> <i class="fa fa-instagram"></i></div>
                               <div>  <i class="fa fa-linkedin"></i></div>
  
                            </div>
                           
                       </div> 
                       <div class="p-3 text-white bg-black" style="background-color: black;">
                           web developer 
                       </div>

                       <div class="d-flex flex-row text-center text-white">
                           <div class="p-4 bg-success font-div" data-toggle="collapse" data-target="#home">
                            <i class="fa-2x fa fa-home  d-block " ></i> 
                            home 
                           </div>

                           <div class="p-4 bg-danger font-div " data-toggle="collapse" data-target="#resume">
                            <i class=" fa-2x fa fa-graduation-cap  d-block" ></i> 
                            Resume
                           </div>

                           <div class="p-4 bg-warning font-div" data-toggle="collapse" data-target="#work">
                            <i class=" fa-2x fa fa-folder  d-block" ></i> 
                            work
                           </div>


                           <div class="p-4 bg-info font-div" data-toggle="collapse" data-target="#contact">
                            <i class="fa-2x fa fa-envelope  d-block" ></i> 
                            contact 
                           </div>
                       </div>
                   </div>

               </div>
           </div>
       </div>
   </header> 
<div class="container">
    <div class="collapse" id="home">
        <div class="p-4 text-center bg-success">
            <h2>mohammad shakil khan</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit.</p>
        </div>
        <div class="card card-body">
            <h2>
                khan shakil developer
            </h2>
            <h3>HTML</h3>
            <div class="progress w-75" style="height: 20px;">
            <div class="progress-bar progress-bar-striped bg-danger progress-bar-animated" style="height: 20px; width: 100%;">
                100%
            </div>
            </div>

            <h3>css</h3>
            <div class="progress w-75" style="height: 20px;">
            <div class="progress-bar progress-bar-striped bg-warning progress-bar-animated" style="height: 20px; width: 100%;">
                100%
            </div>
            </div>

            <h3>bootstrap 4</h3>
            <div class="progress w-75" style="height: 20px;">
            <div class="progress-bar progress-bar-striped  progress-bar-animated" style="height: 20px; width: 100%; background-color:aquamarine;">
                100%
            </div>
            </div>


            <h3>javascript</h3>
            <div class="progress w-75" style="height: 20px;">
            <div class="progress-bar progress-bar-striped bg-info progress-bar-animated" style="height: 20px; width: 80%;">
                80%
            </div>
            </div>


            <h3>react-native</h3>
            <div class="progress w-75" style="height: 20px;">
            <div class="progress-bar progress-bar-striped bg-success progress-bar-animated" style="height: 20px; width: 20%;">
                20%
            </div>
            </div>

            <h3>phpmyadmin</h3>
            <div class="progress w-75" style="height: 20px;">
            <div class="progress-bar progress-bar-striped  progress-bar-animated" style="height: 20px; width: 60%; background-color: magenta;">
                60%
            </div>
            </div>
      
        </div>
    </div>

    <div class="collapse text-center" id="resume">
        <div class="p-4 text-center bg-danger">
            <h2>mohammad shakil khan</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit.</p>
        </div>
        <div class="card card-body">
        <h2>mohammad shakil khan</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit.</p> 
            <div class="card-deck">
                <div class="card">
                    <div class="card-header text-uppercase font-weight-bold">
                        web developer
                    </div>
                    <div class="card-body">
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam aliquam non tenetur error, voluptatibus minima.</p>
                        <p class="bg-dark text-white p-2">10th            Maharashtra board    2015    66.20%</p>
                    </div>
                    <div class="card-footer">
                        Date : 2015
                    </div>
                </div>

                <div class="card">
                    <div class="card-header text-uppercase font-weight-bold">
                        web developer
                    </div>
                    <div class="card-body">
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam aliquam non tenetur error, voluptatibus minima.</p>
                        <p class="bg-dark text-white p-2">Diploma (electronic)    Msbte    2018    61%</p>
                    </div>
                    <div class="card-footer">
                        Date : 2018
                    </div>
                </div>

                <div class="card">
                    <div class="card-header text-uppercase font-weight-bold">
                        web developer
                    </div>
                    <div class="card-body">
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam aliquam non tenetur error, voluptatibus minima.</p>
                        <p class="bg-dark text-white p-2">Graduation        Mumbai university    2021    pursuing</p>
                    </div>
                    <div class="card-footer">
                        Date : 2021
                    </div>
                </div>
            </div>
        </div>
    </div>



   <div class="collapse text-center" id="work">
        <div class="p-4 text-center bg-warning">
            <h2>mohammad shakil khan</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit.</p>
        </div>

        <div class="card-body ">
            <h2>what have i build  ?</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laborum labore nobis perspiciatis autem, nemo inventore!</p>
            <div class="row no-gutters">
                <div class="col-lg-4"><img src="office1.jpg"></div>
                <div class="col-lg-4 order-3"><img src="office2.jpg"></div>
                <div class="col-lg-4"><img src="office3.jpg"></div>
                <div class="col-lg-4"><img src="office1.jpg"></div>
                <div class="col-lg-4"><img src="office2.jpg"></div>
                <div class="col-lg-4"><img src="office4.jpg"></div>
            </div>
        </div>
   </div>
   






   <div class="collapse text-center" id="contact">
    <div class="p-4 text-center bg-info">
        <h2>mohammad shakil khan</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit.</p>
    </div>
    <div class="card card-body">
        <div class="row d-flex justify-content-center align-item-center">
            <div class="col-lg-8  col-md-8 col-12">
                <form >
                    <div class="form-group">
                        <div class="input-group input-group-lg">
                            <span class="input-group-addon bg-warning text-white " id="use">
                                <i class="fa fa-user"></i>
                            </span>
                            <input type="text" name="" placeholder="name" class="form-control bg-dark">
                        </div>
                    </div>

                    <div class="form-group">
                        <div class="input-group input-group-lg">
                            <span class="input-group-addon bg-warning text-white " id="use">
                                <i class="fa fa-user"></i>
                            </span>
                            <input type="email" name="" placeholder="email" class="form-control bg-dark">
                        </div>
                    </div>

                    <div class="form-group">
                        <div class="input-group input-group-lg">
                            <span class="input-group-addon bg-warning text-white " id="use">
                                <i class="fa fa-user"></i>
                            </span>
                            <input type="text" name="" placeholder="message" class="form-control bg-dark">
                        </div>
                    </div>
                    <input type="submit" name=" " class="btn btn-danger" value="send">
                </form>
            </div>
        </div>
    </div>


   </div>



</div>

<div class="container">
    <footer class="p-3 bg-dark text-center ">
        <button class="btn "> <i class="fa-2x fa fa-download  d-block" >download</i> 
 
        </button>
    </footer>
</div>




    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script>
        $('.font-div').click(function(){
            $('.collapse').collapse('hide');
        })
    </script>
  
</body>
</html>
