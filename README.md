<html>
<head>
    <title>Erdeniz Site</title>
    <link href="C:\Users\Kullanıcı\Desktop\klasör\style.css" rel="stylesheet" type="text/css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

    <style>
        #altmenu{
            position:absolute;
            display:none;
            top:-10px;
            left:175px;
       
       
        }
        #altmenu>li{
            padding:10px;
            display:block;
            width:90px;
            color:#000000;
            background:#FFFFFF;
            z-index:99999999;
            border-bottom:1px solid #000;
        }
        #acil:hover ul{
            display:block;
        }
        #acil ul>li:hover{
            background:#555;
       
   
        }
    </style>
</head>
<body>
    <div class="project">
        <div class="menu">
            <ul style="position:relative;">
                <li class="logo"><img src="C:\Users\Kullanıcı\Desktop\Klasör\logo.png"></li>
                <li class="active">Anasayfa</li>
                <li id="acil">Hizmetler
                    <ul id="altmenu">
                        <li><h6>Alt başlık</h6></li>
                        <li><h6>Alt başlık</h6></li>
                        <li><h6>Alt Başlık</h6></li>
                   
                    </ul>
                </li>
                <li>Hakkımızda</li>
                <li>İletişim</li>
                <li><a href="#" class="kayitol"><pre><span><h4>Kayıt OL</h4></span></pre></a></li>
                <li><a href="#" class="girisyap"><pre><span><h4>Giriş Yap</h4></span></pre></a></li>
           
            </ul>
        </div>
        <div class="banner" style="margin-top:50px;">
            <div class="app-text">
            <h2>  BU BÖLGEYE METİN BAŞLIĞI ATABİLİRSİNİZ. </br></br> BU BÖLGEYE YAZI YAZABİLİRSİNİZ.</h2>
            <p><h2>BU BÖLGEYE YAZI YAZABİLİRSİNİZ.<br>
            <br>
             <h3></p>
             </br>
        <div class="play-btn">
            <div class="play-btn-inner"><i class="fa fa-play"></i></div>
            <small><b>Daha Fazla Bilgi Edinin.</b></small>
        </div>
    </div>
    <div class="app-picture">
            <img src="C:\Users\Kullanıcı\Desktop\Klasör\mh.jpg">
        </div>
    </div>

    <div class="quick-links">
        <ul>
        <li><i class="fa fa-share-alt"></i><p>Paylaş</p></li>
        <li><i class="fa fa-bullhorn"></i><p>Duyurular</p></li>
        <li><i class="fa fa-cog"></i><p>İstatistikler</p></li>
        <li><i class="fa fa-bell"></i><p>Bildirimler</p></li>
    </ul>
    </div>
    <div class="social-icons">
        <ul>
            <li><a href="#"><i class="fa fa-youtube"></i></a></li>
            <li><a href="#"><i class="fa fa-instagram"></i></a></li>
            <li><a href="#"><i class="fa fa-twitch"></i></a></li>
            <li><a href="#"><i class="fa fa-steam"></i></a></li>
</div>
* {
        margin:  0;
        padding: 0;
        font-family:sans-serif;
}
.project{
    width:100%;
    height:100%;
    background: #000000;
}
.menu ul{
    display:  inline-flex;
    margin: 50px;
}
.menu ul li{
    list-style: none;
    margin: 0 20px;
    color: #b2b1b1;
    cursor:pointer;
}
.logo img{
    width: 90px;
    margin-top:-35px;
    margin-right: 30px;
}
.active{
    color:#19dafa !important;
}
.kayitol{
    top: -15px;
    left: 1300px;
    position: absolute;
    text-decoration: none;
    color:#fff;
    border:3px solid transparent;
    border-radius: 50px;
    background-image: linear-gradient(#42455a,#42455a),radial-gradient(circle at top left,#fd00da,#19d7f8);
    background-origin: border-box;
    background-clip: content-box,border-box;
}
.girisyap{
    top: -15px;
    left: 1160px;
    position: absolute;
    text-decoration: none;
    color:#fff;
    border:3px solid transparent;
    border-radius: 50px;
    background-image: linear-gradient(#42455a,#42455a),radial-gradient(circle at top left,#fd00da,#19d7f8);
    background-origin: border-box;
    background-clip: content-box,border-box;
}
.kayitol span{
    display: block;
    padding:5px 25px;
}

.girisyap span{
    display:block;
    padding:5px 25px;
}
.banner{
    width: 80%;
    height: 70%;
    top: 25%;
    left: 110px;
    position: absolute;
    color:#fff;
}
.app-text{
    font-family:"Times New Roman",Times,serif;
    width:50%;
    float:left;
}
.app-text h1{
    font-size:43px;
    width:640px;
    position:relative;
    margin-left:40px;
}
.app-text p{
    width:650px;
    font-size:15px;
    margin:30px 0 30px 40px;
    line-height: 25px;
    color: #91919;
}
.app-picture{
    width:50%;
    float:right;
}
.app-picture img{
    width:100%;
    margin-top:-20px;
    padding-left:50px;
}
.play-btn{
    margin-left:40px;
    display: inline-flex;
}
.play-btn-inner{
    height:50px;
    width:50px;
    border:3px solid transparent;
    border-radius: 50%;
    background-image: linear-gradient(#42455a,#42455a),radial-gradient(circle at top left,#fd00da,#19d7f8);
    background-origin: border-box;
    background-clip: content-box,border-box;
    text-align:center;
}
.play-btn-inner .fa{
    padding:18px 0;
    font-size:13px;
    cursor:pointer;
}
small{
    margin:auto 20px;
    cursor:pointer;
    font-size:12px;
    color:#19dafa;
    letter-spacing:3px;
}
.quick-links{
    left:0;
    bottom:0;
    position:absolute;
    background:    linear-gradient(to right, #db1bf6,#19d7f8);
}
.quick-links ul{
    display: inline-flex;
    margin: 30px auto;
    text-align:center;
}
.quick-links ul li{
    list-style: none;
    margin:0 50px;
    cursor:pointer;
}
.quick-links ul li .fa{
    font-size:25px;
    color:#fff;
}
.quick-links ul li p{
    margin-top:15px;
    font-size:10px;
    color:#fff;
}
.social-icons{
    right:25px;
    bottom:35px;
    position:absolute;
}
.social-icons ul li{
    list-style:none;
    margin-top:15px;
    text-align:right;
}
.social-icons ul li a{
    color:#999;
    border-radius:10%;
    border:1px solid #999;
    padding:7px;
    display:block;

}
