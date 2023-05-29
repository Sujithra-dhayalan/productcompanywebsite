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

## HTML:

## HOME PAGE:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KOLLYWOOD STATION</title>
    <link rel="stylesheet" href="./css/layout.css" />
    
  </head>

  <body>
    
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/home07.png" alt="Building" />
          <div class="contenttext">
            Welcome to our "KOLLYWOOD STATION"
            Here you can find your favourite movie posters, famous dialogues, customized phone cases
            <br />
             
            Each poster tells a story, enticing you to embark on a thrilling cinematic journey that transcends 
            the boundaries of the screen.
            <ul>
              <li>POSTERS</li>
              <li>CUSTOMIZED T-SHIRTS</li>
              <li>MOBILE CASES</li>
            </ul>
          </div>
          <DIV>
              Don't forgot to check out our new arrivals!!!
          </DIV>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by Sujithra D.
      </div>
   
  </body>
</html>

```
## PRODUCT PAGE:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FULLY FILMY</title>
    <link rel="stylesheet" href="./css/layout.css" />
    
  </head>

  <body>
    
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1 >Our Premium Products</h1>
          <h2 >MOVIE POSTERS</h2>
          
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro01.png" alt="product image">
                  </div>
                  <div class="itemname">THALAPATHY</div>
                  <div class="itemprice">Price: Rs.190 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro02.png"  alt="product image">
                  </div>
                  <div class="itemname">OK KANMANI</div>
                  <div class="itemprice">Price: Rs.200 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro03.png"  alt="product image">
                  </div>
                  <div class="itemname">VINNAI THAANDI VARUVAAYA</div>
                  <div class="itemprice">Price: Rs.199 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro04.png"  alt="product image">
                  </div>
                  <div class="itemname">GVM</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro05.png"  alt="product image">
                  </div>
                  <div class="itemname">ALAIPAAYUTHEY</div>
                  <div class="itemprice">Price: Rs.333 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro06.png"  alt="product image">
                  </div>
                  <div class="itemname">JIGARTHANDA</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro07.png"  alt="product image">
                  </div>
                  <div class="itemname">MINNALE</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro08.png"  alt="product image">
                  </div>
                  <div class="itemname">96'</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro001.png"  alt="product image">
                  </div>
                  <div class="itemname">ADUKALAM</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro002.png"  alt="product image">
                  </div>
                  <div class="itemname">ANJALI</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro003.png"  alt="product image">
                  </div>
                  <div class="itemname">SUPER STAR</div>
                  <div class="itemprice">Price: Rs.399 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro006.png"  alt="product image">
                  </div>
                  <div class="itemname">VIVEK POSTER</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <h2>PHONE CASES</h2>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro09.png"  alt="product image">
                  </div>
                  <div class="itemname">ANBE SIVAM</div>
                  <div class="itemprice">Price: Rs.699 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro10.png"  alt="product image">
                  </div>
                  <div class="itemname">VADIVELU</div>
                  <div class="itemprice">Price: Rs.499 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro11.png"  alt="product image">
                  </div>
                  <div class="itemname">VADIVELU DIALOGUE</div>
                  <div class="itemprice">Price: Rs.499 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro12.png"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.599 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro004.png"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.599 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro005.png"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.599 </div>
              </div>
              
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by SUJITHRA D.
      </div>
    
  </body>
</html>
```

## PEOPLE PAGE:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>KOLLYWOOD STATION</title>
        <link rel="stylesheet" href="./css/layout.css" />
    </head>
    <body>

            <div class="banner"></div>
            <div class="menu">
            <div class="menuitem"><a href="/static/home.html">Home</a></div>
            <div class="menuitem"><a href="/static/products.html">Products</a></div>
            <div class="menuitemselected"><a href="/static/people.html">People</a></div>
            <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
            
        </div>
        <div class="content">
        <div class="productcontent">    
        <h2 style="text-align:center;">PEOPLE</h2>
          
        <div class="productitems">
            
        <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/c01.png"  alt="product image">
                  </div>
                  <div class="itemname">VETRI MARAN</div>
                  
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/c02.png"  alt="product image">
                  </div>
                  <div class="itemname">RAM</div>
                  
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/C03.png"  alt="product image">
                  </div>
                  <div class="itemname">THIYAGARAJA KUMARARAJA</div>
                  
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/c04.png"  alt="product image">
                  </div>
                  <div class="itemname">BALU MAHENDRAN</div>
                  
              </div>
              </div>
              </div>
    <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by SUJITHRA D.
    </div>
              
        
                  
    </body>
</html>
```

## CONTACT US:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>KOLLYWOOD STATION</title>
        <link rel="stylesheet" href="./css/layout.css" />
    
    </head>
    <body>
        <div class="banner"></div>
            <div class="menu">
            <div class="menuitem"><a href="/static/home.html">Home</a></div>
            <div class="menuitem"><a href="/static/products.html">Products</a></div>
            <div class="menuitem"><a href="/static/people.html">People</a></div>
            <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
            
        </div>
        <div class="content">
            <h1>CONTACT US</h1>
            <div class="contenttext">
            <h2>ADDRESS:</h2>
            <p>#42 ooty road</p>
            <p>Kodaikanal</p>
        </div>
        <div>
            <h2>EMAIL id: </h2>
            <p>sujithradhayalan@gmail.com</p>
            <p>sujithra@kollywoodstation.com</p>
        </div>
        <h2>CONTACT NUMBER</h2>
        <p>1235679040</p>
        <h2>You may also contact us through</h2>
        <p><strong>INSTAGRAM</strong> @kollywood_station</p>
        <p><strong>FACEBOOK</strong> @kollywood_station</p>
        <p><strong>LINKEDIN</strong> @kollywood_station</p>

        </div>
    <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by SUJITHRA D.
    </div>
            
    </body>
</html>
```

## STYLE.CSS CODE:

```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: black;
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
  background-image: url("/static/img/proj07.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #000000;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #000000f9;
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
  color: #f8f8f8;
}

.menuitem a {
  text-decoration: none;
  color: #fdfdfd;
}

.content {
  display: block;
  width: 100%;
  background-color: palegoldenrod;
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
  background-color: #000000;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #e9c836;
}
```
## OUTPUT:

### Home Page:
![proj001](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/a42a3db4-6534-419a-bafc-4209aef51b9b)
![proj002](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/baeb79a4-973c-4f44-ba67-64d90ac2c878)
![proj003](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/a2934b77-8fef-452a-8b7d-55085fa25299)
![proj004](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/447ab2cd-e0f3-422e-83e5-d78d6890c39e)
![proj005](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/9929ad90-df53-4d94-8b8f-f179532d47f7)
![proj006](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/8bd65eaf-fd29-4ee0-b9a5-f55a0ff9aab0)
![proj007](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/19a2fd95-ca19-4374-9f51-8ab6a05b22dd)
![proj008](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/04f7129f-254c-4496-9761-3f7c12687c96)
![proj009](https://github.com/Sujithra-dhayalan/productcompanywebsite/assets/115523950/0d7e1f54-ff71-4ccc-8fc6-19ebdf0bf539)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
