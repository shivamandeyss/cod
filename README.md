<!DOCTYPE html>
<html>
<head>
<title> Assignment 2 </title>
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<style>
 * {
    box-sizing: border-box;
    font-family: Helvetica;
}
body {
    background-color: #d6d6d6;
}
h1 {
    text-align: center;
    color: black;
}
section {
    border: 1px solid black;
    background-color: #b5c4d2;
    margin: 10px;
}
section>h2 {
    float: right;
    border-bottom: 1px solid black;
    border-left: 1px solid black;
    margin: 0;
    width: 230px;
    text-align: center;
    font-style: Times;
    font-size: 24px;
    font-weight: bold;
    height: 45px;
    padding-top: 10px;
}
section.chinese>h2 {
    background-color: #76b8db;
}
section.north>h2 {
    background-color: #4f7acd;
}
section.south>h2 {
    color: #e2e2e2;
    background-color: #10328a;
}
section>p {
    padding: 40px 15px 15px 15px;
}
.row {
    width: 100%;
}
@media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left; }
    .col-lg-1 { 
        width: 8.33%;}
    .col-lg-2 { 
        width: 16.66%; }
    .col-lg-3 {
        width: 25%;  }
    .col-lg-4 {
        width: 33.33%;}
    .col-lg-5 {
        width: 41.66%;}
    .col-lg-6 {
        width: 50%;}
    .col-lg-7 {
        width: 58.33%; }
    .col-lg-8 {
        width: 66.66%; }
    .col-lg-9 {
        width: 74.99%;}
    .col-lg-10 {
        width: 83.33%;}
    .col-lg-11 {
        width: 91.66%;}
    .col-lg-12 {
        width: 100%;}
}
@media (min-width: 768px) and (max-width: 991px) {
    .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
        float: left;}
    .col-md-1 {
        width: 8.33%; }
    .col-md-2 {
        width: 16.66%; }
    .col-md-3 {
        width: 25%; }
    .col-md-4 {
        width: 33.33%;}
    .col-md-5 {
        width: 41.66%;}
    .col-md-6 {
        width: 50%;}
    .col-md-7 {
        width: 58.33%;}
    .col-md-8 {
        width: 66.66%;}
    .col-md-9 {
        width: 74.99%;}
    .col-md-10 {
        width: 83.33%;}
    .col-md-11 {
        width: 91.66%;}
    .col-md-12 {
        width: 100%;}
}
@media (max-width: 767px) {
    .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
        float: left; }
    .col-sm-1 {
        width: 8.33%; }
   .col-sm-2 {
        width: 16.66%;  }
    .col-sm-3 {
        width: 25%;}
    .col-sm-4 {
        width: 33.33%;  }
    .col-sm-5 {
        width: 41.66%;}
    .col-sm-6 {
        width: 50%; }
    .col-sm-7 {
        width: 58.33%; }
    .col-sm-8 {
        width: 66.66%;  }
    .col-sm-9 {
        width: 74.99%;}
    .col-sm-10 {
        width: 83.33%;}
    .col-sm-11 {
        width: 91.66%; }
    .col-sm-12 {
        width: 100%; }
}
</style>
</head>
<body>
<h1> Our Menu </h1>
<div class="row">
        <div class="col-lg-4 col-md-6 col-sm-12">
            <section class="chinese">
             <h2>CHINESE</h2>
                   <p1><br><br><ol><li>Noddles</li><li>Chili paneer</li><li>Fried rice</li><li>Manchurian</li></ol></p1>
            </section>
        </div>
<div class="col-lg-4 col-md-6 col-sm-12">
            <section class="north">
              <h2>NORTH INDIAN</h2>
                <p2> <br><br> <ol><li>Chola batura</li><li>Rajma chawal</li><li>Dal makhani</li><li>Kadhai paneer</li></ol></p2>
            </section>
        </div>
          <div class="col-lg-4 col-md-12 col-sm-12">
            <section class="south">
              <h2>SOUTH INDIAN </h2>
               <p3> <br><br> <ol><li>Masala dosa</li><li>Idli sambhar</li><li>Uttapam</li><li>Vada sambhar</li></ol></p3>
            </section>
        </div>
    </div>
</body>
</html>
