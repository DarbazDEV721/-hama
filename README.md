<!DOCTYPE html>
<html dir="eng">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>my profile</title>
  <link href="http://services.webchin.org/web-fonts/web-font?font=UniQAIDAR_MUHAMMAD" rel="stylesheet" type="text/css">
 
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css"/>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Kaushan+Script&display=swap" rel="stylesheet"
        <style>
  *{
  margin: 0;
  padding: 0;
  font-family: "Ubuntu", sans-serif;
  box-sizing: border-box;
  text-decoration: none;
}

body{
  height: 100vh;
  background: url(./dar.webp) no-repeat center;
  background-size: cover;
  display: flex;
  align-items: center;
  justify-content: center;
}

.profile-card{
  width: 400px;
  text-align: center;
  border-radius: 32px;
  overflow: hidden;
}

.card-header{
  background: #66ff0054;
  padding: 60px 40px;
}

.pic{
  display: inline-block;
  padding: 8px;
  background: linear-gradient(130deg, #000000, #28ff0b);
  margin: auto;
  border-radius: 50%;
  background-size: 200% 200%;
  animation: animated-gradient 2s linear infinite;
}

@keyframes animated-gradient{
  25%{
    background-position: left bottom;
  }
  50%{
    background-position: right bottom;
  }
  75%{
    background-position: right top;
  }
  100%{
    background-position: left top;
  }
}

.pic img{
  display: block;
  width: 100px;
  height: 100px;
  border-radius: 50%;
}

.name{
  color: #000000;
  font-family: 'Kaushan Script', cursive;
  font-size: 28px;
  font-weight: 600;
  margin: 10px 0;
}
.dar{
  color: #000000;
  font-family: 'Luxurious Roman', cursive;
  font-size: 16px;
  font-weight: 600;
  margin: 10px 0;
}
.desc{
  font-size: 28px;
  color: #000000;
}

.sm{
  display: flex;
  justify-content: center;
  margin: 20px 0;
}

.sm a{
  color: #f2f2f2;
  width: 56px;
  font-size: 22px;
  transition: .3s linear;
}

.sm a:hover{
  color: #000000;
}

.contact-btn{
  display: inline-block;
  padding: 12px 50px;
  color: #000000;
  border: 2px solid #ffffff;
  border-radius: 6px;
  margin-top: 16px;
  transition: .3s linear;
}

.contact-btn:hover{
  background: #000000;
  color: #ffffff;
}

.card-footer{
  background: #ffffff;
  padding: 60px 10px;
}

.numbers{
  display: flex;
  align-items: center;
}

.item{
  flex: 1;
  text-transform: uppercase;
  font-size: 13px;
  color: #00be39;
}

.item span{
  display: block;
  color: #2c3a47;
  font-size: 30px;
}

.border{
  border-radius: 12px;
  width: 1px;
  height: 30px;
  background: #bbb;
}
.go{
  width: 12px;
}
  </style>
</head>
<body>
  <div class="profile-card">
    <div class="card-header">
      <div class="pic">
        <img src="./mohamd.jpg" alt="">
      </div>
      <div class="name">Mohammad Basher Alsurchy</div>
      <div class="desc">Agricultural engineer</div>
      <br>
      <span class="dar">
       <p class="dar"> I'm studying at Salahaddin University College of Agricultural Engineering, I wish to be a skilled engineer to serve  my people  I proudly chose  that job . </p>
      </span>
      <div class="sm">
        <a href="https://www.facebook.com/mohammad.basheralsurchy" class="fab fa-facebook-f"></a>
        <a href="https://www.snapchat.com/add/mohammadsurch20?share_id=4vrdNgzyK9A&locale=en-GB" class="fab fa-snapchat"></a>
        <a href="https://instagram.com/muhamad_surchi12?utm_medium=copy_link" class="fab fa-instagram"></a>

      </div>
      <a href="https://instagram.com/darbaz_rasul_721?utm_medium=copy_link" class="contact-btn">Developer Darbaz Rasull</a>
    </div>
    <div class="card-footer">
      <div class="numbers">
        <div class="item">
          <span>213</span>
          Posts
        </div>
        <div class="border"></div>
        <div class="item">
          <span>127</span>
          Following
        </div>
        <div class="border"></div>
        <div class="item">
          <span>100K</span>
          Followers
        </div>
      </div>
    </div>
  </div>
</body>
</html>
