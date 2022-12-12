
<!DOCTYPE html>
<html lang="tr">

<head>
    <title>Ravza Akkum- Kişisel Web Sitesi</title>
    <meta charset="UTF-8">
    <meta name="description" content="E-ticaret">
    <meta name="keywords" content="HTML5,Git,Github,Python,Django,Bootstrap,SQL,PL/SQL">
    <meta name="author" content="E-ticaret">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <style>
        body {
            font: 20px Montserrat, sans-serif;
            line-height: 1.8;
            color: #f5f6f7;
        }
        
        p {
            font-size: 16px;
        }
        
        .margin {
            margin-bottom: 45px;
        }
        
        .bg-1 {
            background-color:#0F219F;
         
            color: #333333;
           
        }
        
        .bg-2 {
            background-color: #585d47;
            
            color: #ffffff;
        }
        
        .bg-3 {
            background-color: #ffffff;
           
            color: #555555;
        }
        
        .bg-4 {
            background-color: #735131;
            
            color: #fff;
        }
        
        .bg-5 {
            background-color: #ecebe8;
            
            color: #333;
        }
        
        .container-fluid {
            padding-top: 70px;
            padding-bottom: 70px;
        }
        
        .navbar {
            padding-top: 15px;
            padding-bottom: 15px;
            border: 0;
            border-radius: 0;
            margin-bottom: 0;
            font-size: 12px;
            letter-spacing: 5px;
        }
        
        .navbar-nav li a:hover {
            color: #4C3173 !important;
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-default">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#">E-ticaret</a>
            </div>
            <div class="collapse navbar-collapse" id="myNavbar">
                <ul class="nav navbar-nav navbar-right">
                    <li><a href="#kimdir">Kimdir?</a></li>
                    <li><a href="#neyapar">Ne yapar?</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- First Container -->
    <div id="kimdir" class="container-fluid bg-1 text-center">
        <h3>Proje Sahipleri</h3>
        <h3 class="margin">Scrum Master: Ahmet Eren Çelik</h3>
        <h3 class="margin">Frontend: Ravza Akkum,Barış Yesari</h3>
        <h3 class="margin">Backend: Muharrem Candan</h3>
        
    </div>

    <!-- Second Container -->
    <div id="neyapar" class="container-fluid bg-2 text-center">
        <h3 class="margin">Projemiz ne hakkında?</h3>
        <p> </p>
    </div>

   

    <!-- Contact -->
    <div id="iletisim" class="container-fluid bg-5 text-center">
        <h3 class="margin">İletişim</h3>
        <br>
        <div class="row ">
            <div class="col-sm-5 text-left">
                <p>Şikayet ve önerileriniz için iletişim adresleri</p>
                <p><span class="glyphicon glyphicon-map-marker"></span> Elazığ, TR</p>
                <p><span class="glyphicon glyphicon-envelope"></span> ravzaAkkum@gmail.com</p>
            </div>
            <div class="col-sm-7 ">
                <div class="row">
                    <div class="col-sm-6 form-group">
                        <input class="form-control" id="name" name="name" placeholder="İsim" type="text" required>
                    </div>
                    <div class="col-sm-6 form-group">
                        <input class="form-control" id="email" name="email" placeholder="Mail" type="email" required>
                    </div>
                </div>
                <textarea class="form-control" id="comments" name="comments" placeholder="Mesaj" rows="5"></textarea>
                <br>
                <div class="row">
                    <div class="col-sm-12 form-group">
                        <button class="btn btn-default pull-right" type="submit">Gönder</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="container-fluid bg-4 text-center">
        <p>Tüm Hakları Saklıdır. 2022-2023 </br><a href="http://www.bilgisayarmagazasi.com">www.bilgisayarmagazasi.com</a></p>
        <i class="fa fa-instagram" aria-hidden="true"></i>
        <i class="fa fa-github" aria-hidden="true"></i>
        <i class="fa fa-skype" aria-hidden="true"></i>
        <i class="fa fa-linkedin" aria-hidden="true"></i>
    </footer>

</body>

</html>
