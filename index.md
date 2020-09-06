<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Font Awesome -->
  <script src="https://kit.fontawesome.com/69e8874ccd.js" crossorigin="anonymous"></script>
  <!-- Load Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Roboto+Slab|Roboto:300" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
  <title>Youtube Mobile</title>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <i class="fab fa-youtube"></i>
      <span class="title">Youtube</span>
    </div>
    <div class="icons">
      <i class="fas fa-search"></i>
      <i class="fas fa-ellipsis-v"></i>
    </div>
  </header>

  <!-- Video Player -->
  <section class="player">
    <video controls src="https://youtu.be/8JZXV3uI8_4" type="video/mp4"></video>
  </section>

  <div class="infoUpNext">
      <!-- Video Info -->
  <section class="info">
    <div class="metadata">
      <ul class="hashtags">
        <li>#Javascript</li>
        <li>#Object Orient</li>
        <li>#Class</li>
      </ul>
      <div class="titleAndButton">
        <span class="title">Javascript Master Challenge! What is Object and Class? Do I need to know both? What's the difference?</span>
        <button class="moreBtn"><i class="fas fa-caret-down"></i></button>
      </div>
        <span class="views">1M views 1 month ago</span>
    </div>
    <ul class="actions">
      <li><button><i class="active fas fa-thumbs-up"></i><span>1K</span></button></li>
      <li><button><i class="fas fa-thumbs-down"></i><span>0</span></button></li>
      <li><button><i class="fas fa-share"></i><span>Share</span></button></li>
      <li><button><i class="fas fa-plus"></i><span>Save</span></button></li>
      <li><button><i class="fab fa-font-awesome-flag"></i><span>Report</span></button></li>
    </ul>
    <div class="channel">
      <div class="metadata">
       <img src="image/jiwon-image.jpg" alt="jiwon"/>
        <div class="info">
          <span class="name">Jiwon</span>
          <span class="subscribers">122 subscribers</span>
        </div>
      </div>
      <button class="subscribe">subscribe</button> 
    </div>
  </section>

  <!-- UpNext -->
  <setion class="upNext">
    <span class="title">Up Next</span>
    <ul>
      <li class="item">
        <div class="img"><img src="image/play1.jpg" alt="Traditional-show"></div>
        <div class="info">
          <span class="title">Traditional Instrument Show</span>
          <span class="name">Jiwon</span>
          <span class="views">82K views</span>
        </div>
        <button class="moreBtn"><i class="fas fa-ellipsis-v"></i></button>
      </li>
      <li class="item">
        <div class="img"><img src="image/play2.jpg" alt="LA"></div>
        <div class="info">
          <span class="title">LA SunSet</span>
          <span class="name">Jiwon</span>
          <span class="views">10K views</span>
        </div>
        <button class="moreBtn"><i class="fas fa-ellipsis-v"></i></button>
      </li>
      <li class="item">
        <div class="img"><img src="image/play3.jpg" alt="Beach"></div>
        <div class="info">
          <span class="title">Beach is everything!</span>
          <span class="name">Jiwon</span>
          <span class="views">55K views</span>
        </div>
        <button class="moreBtn"><i class="fas fa-ellipsis-v"></i></button>
      </li>
    </ul>
  </setion>
  </div>

</body>
</html>
