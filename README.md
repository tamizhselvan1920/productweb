# Product Company Website
## AIM:
To develop a static company website to display the sale of products.

## Design Steps:

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

## CSSCODE:
```PYTHON
*{
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body{
  background-color: aliceblue;
}

.container{
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px #cce6ff
}

.banner{
  display: block;
  width: 100%;
  height: 250px;
  text-align: left;
  font-size: 60px;
  background-image: url("/static/img/banner2.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: midnightblue;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.banner img{
  float: left;
  width: 400px;
  height: 200px;
  margin-left: 10px; 
  margin-top: -125px;
}

.menu{
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #DACC20;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitemselected{
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #e8d870;
}

.menuitem{
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}

.menuitem a{
  text-decoration: none;
  color: #9c1018;
}


.content{
  display: block;
  width: 100%;
  background-color: ivory;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: lightgray;
  border-style: solid;
  color: teal;
}

.homecontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.homecontent h1{
  text-align: left;
}

.homecontent img{
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext{
  text-align: justify;
}

.footer{
  display: block;
  width: 100%;
  height: 40px;
  background-color: #DACC20;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

.productcontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1{
  text-align: left;
}

.productitems{
  display: block;
}

.productitem{
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

.peoplecontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.peoplecontent h1{
  text-align: left;
}

.peoplepics{
  display: block;
}

.peoplepic{
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.peoplepic img{
  width: 100px;
  height: 100px;
  display: block;
}

.peoplepic .peopleimage{
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.peoplepic .peoplename{
  display: block;
}

.peoplepic .peopledes{
  display: block;
}

.contactcontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;  
}

.contactitems{
  display: block;
}

.contactitem{
  display:block;
  text-align: left;
}

.contactitem .address{
  display: block;
  text-align: left;
}

.contactitem .number{
  display: block;
  text-align: left;
}

.conatctitem .email{
  display: block;
  text-align: left; 
}
```
HOME PAGE HTML:
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>UniShield-Home</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/logo4.png" type="image/x-icon" />    
    </head>

    <body>
        <div class="container">
            <div class="banner">
                <img src="img/logo5.png" alt="logo">
            </div>
            <div class="menu">
                <div class="menuitemselected"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitem"><a href="/static/people.html">People</a></div>  
                <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="homecontent">
                    <h1>About Us</h1>
                    <img src="./img/anti.png" alt="antivirus" />
                    <div class="contenttext">
                        Our passion is more than just offering device security, identity protection, online privacy, and all-in-one protection. It is to empower you and your family to feel safer in your everyday digital life. We believe that when you worry less about the darkness of cybercrime, you can live on the bright side. So, we make protection for your digital life easy. Opt-in to Cyber Safety.  
                        <br/>
                        Over the last 30 years, UniShield Technologies has been at the forefront of developing intelligent security solutions for millions of home and business users worldwide.
                        <ul>
                            <li>UniShield technologies blocks millions of cyberthreats every day.</li>
                            <li>Get protection against viruses, spyware and other threats.</li>
                        </ul>
                    </div>
                    <h1>Careers at UniShield</h1>
                    <div class="contenttext">
                        UniShield Technologies is a great place to work as a cybersecurity professional. You get to enjoy the best of both worlds here, working with world leaders in the industry and also being appreciated as an individual. A professional environment that drives technological innovation is nested in a friendly and connected culture, just like a close-knit family. If you are passionate about securing the digital space, driven by purpose to deliver world class products, enjoy working with techies, and have an entrepreneurial streak, UniShield Technologies is the best choice for you.
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 UniShield Technologies, Developed by Aashima Nazreen.
            </div>
        </div>
    </body>
</html>
```
PRODUCT PAGE HTML :
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>UniShield-Products</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo4.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">
        <img src="img/logo5.png" alt="logo">
      </div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">
          <h1>Our Premium Products</h1>
          <div class="productitems">
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p1.png" alt="product 1">
              </div>
              <div class="itemname">Total Security</div>
              <div class="itemprice">Price: Rs.1,244.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p8.png" alt="product 8">
              </div>
              <div class="itemname">Total Security Plus</div>
              <div class="itemprice">Price: Rs.1,599.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p11.png" alt="product 11">
              </div>
              <div class="itemname">Total Security X5</div>
              <div class="itemprice">Price: Rs.3,542</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p3.png" alt="product 3">
              </div>
              <div class="itemname">Ultimate Security</div>
              <div class="itemprice">Price: Rs.999.00</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="./img/p10.png" alt="product 10">
            </div>
            <div class="itemname">Ultimate Security GOLD</div>
            <div class="itemprice">Price: Rs.2,499</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="./img/p2.png" alt="product 2">
            </div>
            <div class="itemname">Lifetime Antivirus</div>
            <div class="itemprice">Price: Rs.3,999.00</div>
          </div>
          <div class="productitem">
              <div class="itemimage">
              <img src="./img/p4.png" alt="product 4">
              </div>
              <div class="itemname">Antivirus Premium</div>
              <div class="itemprice">Price: Rs.584.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p12.png" alt="product 12">
              </div>
              <div class="itemname">Antivirus Plus</div>
              <div class="itemprice">Price: Rs.949.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p9.png" alt="product 9">
              </div>
              <div class="itemname">Internet Security</div>
              <div class="itemprice">Price: Rs.895.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p5.png" alt="product 5">
              </div>
              <div class="itemname">Antivirus for Mac</div>
              <div class="itemprice">Price: Rs.779.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p6.png" alt="product 6">
              </div>
              <div class="itemname">Mobile Security - Android</div>
              <div class="itemprice">Price: Rs.149.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p7.png" alt="product 7">
              </div>
              <div class="itemname">Mobile Security - iOS</div>
              <div class="itemprice">Price: Rs.149.00</div>
            </div>
          </div>
        </div>
      </div>      
      <div class="footer">
        Copyright &#169;2021 UniShield Technologies, Developed by Aashima Nazreen.
      </div>
    </div>
  </body>
</html>
```
PEPOLE PAGE HTML:
```python
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>UniShield-Products</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo4.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">
        <img src="img/logo5.png" alt="logo">
      </div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">
          <h1>Our Premium Products</h1>
          <div class="productitems">
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p1.png" alt="product 1">
              </div>
              <div class="itemname">Total Security</div>
              <div class="itemprice">Price: Rs.1,244.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p8.png" alt="product 8">
              </div>
              <div class="itemname">Total Security Plus</div>
              <div class="itemprice">Price: Rs.1,599.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p11.png" alt="product 11">
              </div>
              <div class="itemname">Total Security X5</div>
              <div class="itemprice">Price: Rs.3,542</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p3.png" alt="product 3">
              </div>
              <div class="itemname">Ultimate Security</div>
              <div class="itemprice">Price: Rs.999.00</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="./img/p10.png" alt="product 10">
            </div>
            <div class="itemname">Ultimate Security GOLD</div>
            <div class="itemprice">Price: Rs.2,499</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="./img/p2.png" alt="product 2">
            </div>
            <div class="itemname">Lifetime Antivirus</div>
            <div class="itemprice">Price: Rs.3,999.00</div>
          </div>
          <div class="productitem">
              <div class="itemimage">
              <img src="./img/p4.png" alt="product 4">
              </div>
              <div class="itemname">Antivirus Premium</div>
              <div class="itemprice">Price: Rs.584.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p12.png" alt="product 12">
              </div>
              <div class="itemname">Antivirus Plus</div>
              <div class="itemprice">Price: Rs.949.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p9.png" alt="product 9">
              </div>
              <div class="itemname">Internet Security</div>
              <div class="itemprice">Price: Rs.895.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p5.png" alt="product 5">
              </div>
              <div class="itemname">Antivirus for Mac</div>
              <div class="itemprice">Price: Rs.779.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p6.png" alt="product 6">
              </div>
              <div class="itemname">Mobile Security - Android</div>
              <div class="itemprice">Price: Rs.149.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/p7.png" alt="product 7">
              </div>
              <div class="itemname">Mobile Security - iOS</div>
              <div class="itemprice">Price: Rs.149.00</div>
            </div>
          </div>
        </div>
      </div>      
      <div class="footer">
        Copyright &#169;2021 UniShield Technologies, Developed by Aashima Nazreen.
      </div>
    </div>
  </body>
</html>
```
CONTACT PAGE HTML:
```python
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>UniShield-Contact Us</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/logo4.png" type="image/x-icon" />    
    </head>

    <body>
        <div class="container">
            <div class="banner">
                <img src="img/logo5.png" alt="logo">
            </div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitem"><a href="/static/people.html">People</a></div>  
                <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="contactcontent">
                    <div class="contactitems">
                        <div class="contactitem">
                            <h2>Bengaluru</h2>
                            <div class="address">Offshore Development Center, Plot No. 26A<br>
                                Electronics City, Hosur Road<br>
                                Banglore 560 100</div>
                            <div class="number">Mobile: +91 80 2852 0261</div>
                            <div class="email">E-mail: info@unishield.com</div>
                        </div>
                        <div class="contactitem">
                            <h2>Chennai</h2>
                            <div class="address">Plot No.TP1/1, Central Avenue, Techno Park (SEZ)<br>
                                Mahindra World City<br>
                                Kancheepuram District 603 004</div>
                            <div class="number">Mobile: +91 44 4741 1111</div>
                            <div class="email">E-mail: info@unishield.com</div>
                        </div>
                        <div class="contactitem">
                            <h2>Hyderabad</h2>
                            <div class="address">Survey No. 210, Manikonda Village,<br>
                                Lingampally, Rangareddy (Dist.),<br>
                                Hyderabad 500 032</div>
                            <div class="number">Mobile: +91 40 6642 0000</div>
                            <div class="email">E-mail: info@unishield.com</div>
                        </div>
                        <div class="contactitem">
                            <h2>Pune</h2>
                            <div class="address">Plot No. 24/2, Rajiv Gandhi Infotech Park<br>
                                Phase II, Village Maan Taluka Mulshi, <br>
                                Pune 411 057</div>
                            <div class="number">Mobile: +91 20 3982 7000</div>
                            <div class="email">E-mail: info@unishield.com</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 UniShield Technologies, Developed by Aashima Nazreen.
            </div>
        </div>
    </body>
</html>
```

## Output:

![output](https://user-images.githubusercontent.com/121148386/215554214-21e7482b-ece7-4736-b953-d5139437229c.png)


![output1](https://user-images.githubusercontent.com/121148386/215554222-36eb1a9a-6b99-4781-a7e6-ee60943e2d0a.png)

![output 2](https://user-images.githubusercontent.com/121148386/215554235-7264d399-47b8-4065-ac4b-48dc1a6a1471.png)

![homepage](https://user-images.githubusercontent.com/121148386/215554247-7413fe03-e917-40c7-9e37-c28a014a6e1b.jpg)




## HTML Validator


## Result:
The program for designing company website for sale of products using HTML and CSS is completed successfully.
