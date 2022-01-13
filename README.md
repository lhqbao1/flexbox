# flexbox
!DOCTYPE html>
<html> 
    <head>
        <title>HTML</title>
        <!--ho tro viet tieng viet-->
        <meta charset="utf-8">
        <link rel="stylesheet" href="main.css">
    </head>
    
    <body>
        <!--nav layout-->
       <div class="nav">
           <ul class="nav-list">
               <li class="nav-items">Giới thiệu</li>
               <li class="nav-items">Kết nối</li>
               <li class="nav-items">Tải ứng dụng</li>
           </ul>
           <ul class="nav-list">
               <li class="nav-items">Đăng kí</li>
               <li class="nav-items">Đăng nhập</li>
           </ul>
       </div>
       <!--column layout-->
       <div class="column-layout">
           <div class="column-item layout1">
               <h2>Introduction</h2>
               <p>This is my first website</p>
           </div>
           <div class="column-item layout2">
               <h2>Description</h2>
               <p>Practicing HTML and CSS</p>
               <p>Know how to use flexbox to create a website</p>
           </div>
           <div class="column-item layout3">
               <h2>Skills</h2>
               <p>HTML</p>
               <p>CSS</p>
           </div>
       </div>
       <div class="feature-layout">
           <div class="feature-item">
               <h2>Menu</h2>
               <p>Cá đúi chiên sả</p>
               <p>Giò heo nướng</p>
            </div>
            <div class="feature-item">
                <h2>Giá món</h2>
                <p>100.000đ</p>
                <p>200.000đ</p>
            </div>
            <div class="feature-item">
                <h2>Số lượng</h2>
                <p>tồn kho 2</p>
                <p>tồn kho 5</p>
            </div>
            
       </div>
       <div class="box">
           <div class="box-item">1</div>
           <div class="box-item">2</div>
           <div class="box-item">3</div>
           <div class="box-item">4</div>
           <div class="box-item">5</div>
       </div>
       <div class="center-layout">
           <h2 class="center-layout-item">Center</h2>
       </div>

       <div class="chart-layout">
           <div class="chart-layout-item" style="--percent:10%">10%</div>
           <div class="chart-layout-item" style="--percent:20%">20%</div>
           <div class="chart-layout-item" style="--percent:30%">30%</div>
           <div class="chart-layout-item" style="--percent:40%">40%</div>
           <div class="chart-layout-item" style="--percent:50%">50%</div>


       </div>

    <body>
</html>
