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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### Home:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./im/building.png" alt="building" />
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
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Vijay.
      </div>
    </div>
  </body>
</html>
~~~

### Product:
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
      <div class="banner">Edusoft Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/imp/1.jpeg" alt="earphone">
                  </div>
                  <div class="itemname">earphone</div>
                  <div class="itemprice">Price: &#8377; 1,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/imp/2.jpeg"  alt="watch">
                  </div>
                  <div class="itemname">Watch</div>
                  <div class="itemprice">Price: &#8377; 3,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/3.jpeg"  alt="Msi Laptop">
                </div>
                <div class="itemname">Msi Laptop</div>
                <div class="itemprice">Price: &#8377; 50,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/4.jpeg"  alt="Display">
                </div>
                <div class="itemname">Display</div>
                <div class="itemprice">Price: &#8377; 10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/5.jpeg"  alt="Speaker">
                </div>
                <div class="itemname">Speaker</div>
                <div class="itemprice">Price: &#8377; 3,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/6.jpeg"  alt="DJ box">
                </div>
                <div class="itemname">DJ box</div>
                <div class="itemprice">Price: &#8377; 20,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/7.jpeg"  alt="Mic">
                </div>
                <div class="itemname">Mic</div>
                <div class="itemprice">Price: &#8377; 25,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/8.jpeg"  alt="HandBand">
                </div>
                <div class="itemname">HandBand</div>
                <div class="itemprice">Price: &#8377; 4,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/9.jpeg"  alt="Pendrive">
                </div>
                <div class="itemname">Pendrive</div>
                <div class="itemprice">Price: &#8377; 1,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/10.jpeg"  alt="Mouse">
                </div>
                <div class="itemname">Mouse</div>
                <div class="itemprice">Price: &#8377; 600.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/11.jpeg"  alt="iphone">
                </div>
                <div class="itemname">iphone</div>
                <div class="itemprice">Price: &#8377; 75,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/imp/12.jpeg"  alt="UPS">
                </div>
                <div class="itemname">UPS</div>
                <div class="itemprice">Price: &#8377; 10,000.00 </div>
              </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Avengers Private Limited, Developed by Vijay
      </div>
    </div>
  </body>
</html>
~~~

### People:
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
        <div class="banner">Edusoft Private Limited</div>
        <div class="menu">
          <div class="menuitem"><a href="/static/home.html">Home</a></div>
          <div class="menuitem">
            <a href="/static/products.html">Products</a>
          </div>
          <div class="menuitemselected"><a href="/static/people.html">People</a></div>
          <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
        <div class="content">
            <div class="productcontent"> 
                <h1>Our Leadership</h1>
                <div class="productitems">
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/im/1.jpeg" alt="Robert Downey Jr">
                        </div>
                        <div class="itemname">Robert</div>
                        <div class="itemprice"><b>Chairman</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/im/2.jpeg" alt="Chris Evans">
                        </div>
                        <div class="itemname">Evans</div>
                        <div class="itemprice"><b>Chief Executive Officer</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/im/3.jpeg" alt="Chris Hemsworth">
                        </div>
                        <div class="itemname">Chris </div>
                        <div class="itemprice"><b>Managing Director</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/im/4.jpeg" alt="Mark Ruffalo">
                        </div>
                        <div class="itemname">Ruffalo</div>
                        <div class="itemprice"><b>Chief Operating Officer</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/im/5.jpeg" alt="Scarlett Johansson">
                        </div>
                        <div class="itemname">Mark</div>
                        <div class="itemprice"><b>Executive Director</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/im/6.jpeg" alt="Jeremy Renner">
                        </div>
                        <div class="itemname">Renner</div>
                        <div class="itemprice"><b>Director</b></div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 Avengers Private Limited, Developed by Vijay
              </div>
        </div>
    </div>
  </body>
</html>
~~~

### Contact:
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
      <div class="banner">EduSoft Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">
            <h2>Contact Info</h2>
            <div>AMR Tech Park II,No.23 & 24,<br> 
                Chennai 600 068, India<br>
                Customer Care:1800 362 4866<br>
                E-mail: edusoftpvt@gmail.com
            </div>
        </div>
       </div>
       <div class="footer">
        Copyright &#169; 2021 Avengers Private Limited, Developed by Vijay
      </div>
    </div>
   </body>
</html> 
~~~
### CSS:
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
  text-align: left;
  font: italic small-caps bold 12px/30px
  Georgia, serif;
  font-size: 60px;
  background-image: url("/static/im/bg.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 20px;
  padding-left: 10px;
  color: #3bff5c;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #0d0586;
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
  color: whitesmoke;
}

.menuitem a {
  text-decoration: none;
  color: whitesmoke;
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
  background-color: #084475;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: whitesmoke;
}
~~~

## OUTPUT:

### Home Page:

![output](https://github.com/vijay21500269/productcompanywebsite/blob/main/Screenshot%20(39).png?raw=true)
### Product Page:

![output](https://github.com/vijay21500269/productcompanywebsite/blob/main/Screenshot%20(40).png?raw=true)
### People Page:

![output](https://github.com/vijay21500269/productcompanywebsite/blob/main/Screenshot%20(41).png?raw=true)
### Contact Page:

![output](https://github.com/vijay21500269/productcompanywebsite/blob/main/Screenshot%20(42).png?raw=true)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
