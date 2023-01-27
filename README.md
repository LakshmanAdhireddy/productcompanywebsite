# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

## PROGRAM :
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/d1.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>google Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <d

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
~~~

HOME
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>google Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/g2.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Obed Otto.
      </div>
    </div>
  </body>
</html>
~~~

products
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/n1.jfif" alt="product image">
                  </div>
                  <div class="itemname">google</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/n3.jfif"  alt="product image">
                </div>
                <div class="itemname">gmail</div>
                <div class="itemprice">Price: Rs.20,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/n2.jfif"  alt="product image">
              </div>
              <div class="itemname">chrome</div>
              <div class="itemprice">Price: Rs.30,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/n4.jfif"  alt="product image">
            </div>
            <div class="itemname">maps</div>
            <div class="itemprice">Price: Rs.20,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/n5.jfif"  alt="product image">
          </div>
          <div class="itemname">drive</div>
          <div class="itemprice">Price: Rs.10,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/n6.jfif"  alt="product image">
        </div>
        <div class="itemname">google photos</div>
        <div class="itemprice">Price: Rs.5,000.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/n7.jfif"  alt="product image">
      </div>
      <div class="itemname">gmeet</div>
      <div class="itemprice">Price: Rs.6,000.00 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/n8.jfif"  alt="product image">
    </div>
    <div class="itemname">gpay</div>
    <div class="itemprice">Price: Rs.8,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/n9.jfif"  alt="product image">
  </div>
  <div class="itemname">google files</div>
  <div class="itemprice">Price: Rs.9,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/n10.jfif"  alt="product image">
  </div>
  <div class="itemname">google podcasts</div>
  <div class="itemprice">Price: Rs.2,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/n11.jfif"  alt="product image">
  </div>
  <div class="itemname">google news</div>
  <div class="itemprice">Price: Rs.4,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/n12.jfif"  alt="product image">
  </div>
  <div class="itemname">google play music</div>
  <div class="itemprice">Price: Rs.2,000.00 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Tharun.A.
      </div>
    </div>
  </body>
</html>
~~~
people
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Vasu Health Care</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitems"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/pk.jfif" alt="product image">
                </div>
                <div class="itemname">pavan kalyan</div>
                <div class="itemprice">CEO</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/sonu.jfif"  alt="product image">
                </div>
                <div class="itemname">Sonu sood</div>
                <div class="itemprice">DSM</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/sai dh.jfif"  alt="product image">
              </div>
              <div class="itemname">sai </div>
              <div class="itemprice">Assistant HR </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/varun.jfif"  alt="product image">
              </div>
              <div class="itemname">varun tej</div>
              <div class="itemprice">HR </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/karthike.jfif"  alt="product image">
            </div>
            <div class="itemname">Karthikeya</div>
            <div class="itemprice">RSM </div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/mb.jfif"  alt="product image">
          </div>
          <div class="itemname">mahesh babu</div>
          <div class="itemprice">senior manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Vasu health Care Private Limited, Developed by Lakshman reddy
    </div>
  </div>
</body>
</html>
~~~

contactus
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>google products </title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            967/4 G.I.D.C., MAKARPURA, VADODARA  390010, GUJARAT, INDIA.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mr.Lakshman(HR):9573819022<br><br>
              Mr.Dharanesh(Assistant HR):9010525372
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:Lakshmanreddy002@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  google products Private Limited, Developed by Lakshman reddy
      </div>
    </div>
  </body>
</html>
~~~


## OUTPUT:

### Home Page:

![HOME 1](https://user-images.githubusercontent.com/118707265/215053635-7b6295e2-cf84-469c-8ac5-57454359d956.jpeg)

products

![PRODUCTS1](https://user-images.githubusercontent.com/118707265/215054690-52d92ea6-963e-4968-94a8-050fef824f71.jpeg)

people

![people 1](https://user-images.githubusercontent.com/118707265/215054802-ac3beeb2-4c8b-4ae6-a99d-1fb31480251d.jpeg)


## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
