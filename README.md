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

## Color scheme:
__Primary color:__ White <br />
__Secondary color:__ Black <br />
__Tertiary color:__ Grey

## PROGRAM :

### home.html:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content">
        <h1 id="home-h" >THINK DIFFERENT.</h1>
        <p id="home-p">Everything is designed. Few things are designed well. And those are designed by us.</p>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by Roghith.
      </div>
    </div>
  </body>
</html>

```

### about.html:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content p-con">
        <h1 style="margin:auto;margin-top:50px;font-size:50px;">About Us</h1><br><br>
        <p id="about-p">Apple is an American technology company founded by Steve Jobs, Steve Wozniak, and Ronald Wayne in April 1976. Incorporated in 1977, the company was one of the early manufacturers of personal computing devices with graphical user interface. Over the years, the company also forayed into other consumer electronics segments like mobile communication devices, digital music players, notebooks, and wearables. The company also develops and markets a range of related software and services, accessories, and networking solutions. Currently, the company’s chief executive officer (CEO) is Timothy Donald Cook, commonly known as Tim Cook.
            <br><br>
            From smart wearables to digital content streaming platforms, Apple offers a wide range of products and services within a closed ecosystem. Its products include iMac desktops, MacBook notebooks, iPhone mobile devices, iPad tablets, iPod digital multimedia devices, Apple Watch and Apple TV. The services include iOS operating system for mobile devices, macOS operating system for notebooks and desktops, iCloud online storage, tvOS operating system for Apple TV, watchOS operating system for Apple Watch, iTunes for digital content services, Apple Pay digital payment service, Apple Music for online multimedia streaming, and Apple News.
            <br><br>
            Apple has been known to be on the forefront of innovation. The company was among the first to develop an app-based ecosystem for smartphones. It was the first smartphone maker to introduce touchID — a fingerprint scanner module to unlock a device — and use 64-bit processors, both of which were later also adopted by most other smartphone manufacturers.
            <br><br>
            Apple’s services have so far been exclusive to its own products. However, in March 2019, the company announced that its subscription-based TV Plus service will be available as an app on televisions from other brands, too. This is for the first time that Apple has enabled its ecosystem service to work on products from other brands, and more announcements of similar nature are expected in future.
            <br><br>
            In 2019, Apple also settled its long-pending legal battle with American chipmaker Qualcomm. The move came after the company found itself in a tight spot securing 5G chips to power its future devices. With Qualcomm on board, the company is expected to bring its first 5G-ready smartphone by 2020.</p>
            <br><br>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by Roghith.
      </div>
    </div>
  </body>
</html>

```

### people.html:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
        <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content p-con">
        <h1 style="margin:auto;margin-top:50px;font-size:50px;">People</h1>
        <div class="p-page">
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url(https://pm1.narvii.com/7721/6550eae21d1637c54ac4f4ff15bea4010f728cc5r1-554-554v2_hq.jpg);"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">Jonny Sins</h3>
                        <p class="profile-desc">All Rounder</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">751</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.8m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">4</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" ></div>
                    <div class="profile-info">
                        <h3 class="profile-name">Powervel</h3>
                        <p class="profile-desc">Developer/Conent Creator</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://m.media-amazon.com/images/M/MV5BNzg1MTUyNDYxOF5BMl5BanBnXkFtZTgwNTQ4MTE2MjE@._V1_.jpg');"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">RDJ</h3>
                        <p class="profile-desc">Genius, billionaire,philanthropist.</p>
                    </div>
                </div>
                 <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://file1.telestar.fr/var/telestar/storage/images/3/3/2/3/3323904/chris-evans-comment-failli-refuser-role-vie.jpg?alias=exact1024x768_l');"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">Cris Evans</h3>
                        <p class="profile-desc">Conent Creator</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://image.gala.de/21743318/t/N_/v12/w960/r0.6667/-/elizabeth-olsen.jpg');"></div>
            
                    <div class="profile-info">
                        <h3 class="profile-name">Elizabeth Olsen</h3>
                        <p class="profile-desc">Developer</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card-header">
                    <div class="profile-image" style="background-image: url('https://a1cf74336522e87f135f-2f21ace9a6cf0052456644b80fa06d4f.ssl.cf2.rackcdn.com/images/characters/large/800/Bruce-Banner.The-Incredible-Hulk.webp');"></div>
                    <div class="profile-info">
                        <h3 class="profile-name">Bruce Banner</h3>
                        <p class="profile-desc">Scientist</p>
                    </div>
                </div>
                <div class="profile-card-body">
                    <ul class="status">
                        <li>
                            <span class="status-value">532</span>
                            <span class="status-text">Posts</span>
                        </li>
            
                        <li>
                            <span class="status-value">1.5m</span>
                            <span class="status-text">Followers</span>
                        </li>
            
                        <li>
                            <span class="status-value">423</span>
                            <span class="status-text">Following</span>
                        </li>
                    </ul>
            
                    <div class="action">
                        <button class="btn btn-pink">Follow</button>
                        <button class="btn btn-gray-outline">Message</button>
                    </div>
                </div>
            </div>
        </div>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by Roghith.
      </div>
    </div>
  </body>
</html>

```

### products.html:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content p-con" style="border:none">
        <h1 style="margin:auto;margin-top:40px;font-size:50px;">Products</h1>
        <div class="p-page">
          <div class="product-card">
              <div class="badge new">New</div>
              <div class="product-tumb">
                <img src="{% static 'img/pro/13promax.jpg' %}" alt="">
              </div>
              <div class="product-details">
                <span class="product-catagory">Mobile</span>
                <h4><a href="">IPhone 13 Pro Max</a></h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
                <div class="product-bottom-details">
                  <div class="product-price"><small>$96.00</small>$230.99</div>
                  <div class="product-links">
                    <a href=""><i class="fa fa-heart"></i></a>
                    <a href=""><i class="fa fa-shopping-cart"></i></a>
                  </div>
                </div>
              </div>
    
          </div>
          <div class="product-card">
            <div class="badge new">New</div>
            <div class="product-tumb">
              <img src="{% static 'img/pro/airpods.jpg' %}" alt="">
            </div>
            <div class="product-details">
              <span class="product-catagory">Airpods</span>
              <h4><a href="">Apple Airpods Pro</a></h4>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
              <div class="product-bottom-details">
                <div class="product-price"><small>$96.00</small>$230.99</div>
                <div class="product-links">
                  <a href=""><i class="fa fa-heart"></i></a>
                  <a href=""><i class="fa fa-shopping-cart"></i></a>
                </div>
              </div>
            </div>
          </div>
          <div class="product-card">
            <div class="badge">Hot</div>
            <div class="product-tumb">
              <img src="{% static 'img/pro/macair.jpg' %}" alt="">
            </div>
            <div class="product-details">
              <span class="product-catagory">Laptop</span>
              <h4><a href="">Macbook Air</a></h4>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
              <div class="product-bottom-details">
                <div class="product-price"><small>$96.00</small>$230.99</div>
                <div class="product-links">
                  <a href=""><i class="fa fa-heart"></i></a>
                  <a href=""><i class="fa fa-shopping-cart"></i></a>
                </div>
              </div>
            </div>
          </div>
          <div class="product-card">
            <div class="badge">Hot</div>
            <div class="product-tumb">
              <img src="{% static 'img/pro/watch.jpg' %}" alt="">
            </div>
            <div class="product-details">
              <span class="product-catagory">IWatch</span>
              <h4><a href="">Apple Watch</a></h4>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
              <div class="product-bottom-details">
                <div class="product-price"><small>$96.00</small>$230.99</div>
                <div class="product-links">
                  <a href=""><i class="fa fa-heart"></i></a>
                  <a href=""><i class="fa fa-shopping-cart"></i></a>
                </div>
              </div>
            </div>
        </div>
        <div class="product-card">
          <div class="badge">Hot</div>
          <div class="product-tumb">
            <img src="{% static 'img/pro/tv.png' %}" alt="">
          </div>
          <div class="product-details">
            <span class="product-catagory">Monitor</span>
            <h4><a href="">Apple Monitor</a></h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
            <div class="product-bottom-details">
              <div class="product-price"><small>$96.00</small>$230.99</div>
              <div class="product-links">
                <a href=""><i class="fa fa-heart"></i></a>
                <a href=""><i class="fa fa-shopping-cart"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="product-card">
          <div class="badge">Hot</div>
          <div class="product-tumb">
            <img src="{% static 'img/pro/tab.jpg' %}" alt="">
          </div>
          <div class="product-details">
            <span class="product-catagory">Tab</span>
            <h4><a href="">Apple Tablet</a></h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
            <div class="product-bottom-details">
              <div class="product-price"><small>$96.00</small>$230.99</div>
              <div class="product-links">
                <a href=""><i class="fa fa-heart"></i></a>
                <a href=""><i class="fa fa-shopping-cart"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="product-card">
          <div class="badge">Hot</div>
          <div class="product-tumb">
            <img src="{% static 'img/pro/14pro.jpg' %}" alt="">
          </div>
          <div class="product-details">
            <span class="product-catagory">Mobile</span>
            <h4><a href="">IPhone 14 Pro</a></h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
            <div class="product-bottom-details">
              <div class="product-price"><small>$96.00</small>$230.99</div>
              <div class="product-links">
                <a href=""><i class="fa fa-heart"></i></a>
                <a href=""><i class="fa fa-shopping-cart"></i></a>
              </div>
            </div>
          </div>

      </div>
      <div class="product-card">
        <div class="badge">Hot</div>
        <div class="product-tumb">
          <img src="{% static 'img/pro/13.jpg' %}" alt="">
        </div>
        <div class="product-details">
          <span class="product-catagory">Mobile</span>
          <h4><a href="">IPhone 14</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
          <div class="product-bottom-details">
            <div class="product-price"><small>$96.00</small>$230.99</div>
            <div class="product-links">
              <a href=""><i class="fa fa-heart"></i></a>
              <a href=""><i class="fa fa-shopping-cart"></i></a>
            </div>
          </div>
        </div>
      </div>
      <div class="product-card">
        <div class="badge">Hot</div>
        <div class="product-tumb">
          <img src="{% static 'img/pro/11.jpg' %}" alt="">
        </div>
        <div class="product-details">
          <span class="product-catagory">Mobile</span>
          <h4><a href="">IPhone 11</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
          <div class="product-bottom-details">
            <div class="product-price"><small>$96.00</small>$230.99</div>
            <div class="product-links">
              <a href=""><i class="fa fa-heart"></i></a>
              <a href=""><i class="fa fa-shopping-cart"></i></a>
            </div>
          </div>
        </div>
      </div>
      <div class="product-card">
        <div class="badge">Hot</div>
        <div class="product-tumb">
          <img src="{% static 'img/pro/7.jpg' %}" alt="">
        </div>
        <div class="product-details">
          <span class="product-catagory">Mobile</span>
          <h4><a href="">IPhone 7</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
          <div class="product-bottom-details">
            <div class="product-price"><small>$96.00</small>$230.99</div>
            <div class="product-links">
              <a href=""><i class="fa fa-heart"></i></a>
              <a href=""><i class="fa fa-shopping-cart"></i></a>
            </div>
          </div>
        </div>

    </div>
    <div class="product-card">
      <div class="badge">Hot</div>
      <div class="product-tumb">
        <img src="{% static 'img/pro/12mini.jpg' %}" alt="">
      </div>
      <div class="product-details">
        <span class="product-catagory">Mobile</span>
        <h4><a href="">IPhone 12 Mini</a></h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
        <div class="product-bottom-details">
          <div class="product-price"><small>$96.00</small>$230.99</div>
          <div class="product-links">
            <a href=""><i class="fa fa-heart"></i></a>
            <a href=""><i class="fa fa-shopping-cart"></i></a>
          </div>
        </div>
      </div>
    </div>
    <div class="product-card">
      <div class="badge">Hot</div>
      <div class="product-tumb">
        <img src="{% static 'img/pro/se.png' %}" alt="">
      </div>
      <div class="product-details">
        <span class="product-catagory">Mobile</span>
        <h4><a href="">IPhone SE</a></h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
        <div class="product-bottom-details">
          <div class="product-price"><small>$96.00</small>$230.99</div>
          <div class="product-links">
            <a href=""><i class="fa fa-heart"></i></a>
            <a href=""><i class="fa fa-shopping-cart"></i></a>
          </div>
        </div>
      </div>
    </div>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by Roghith.
      </div>
    </div>
  </body>
</html>

```

### contact.html:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content p-con">
        <h1 style="margin:auto;margin-top:50px;font-size:50px;">Contact Us</h1><br><br>
          <p id="about-p" style="font-size:19px;line-height:33px;"><b>Email: </b>applestore@inc.com<br>
            <b>Contact Number: </b>+44 467 467 23<br>
            <b>Facebook: </b>Apple Inc.<br>
            <b>Instagram: </b>Apple Inc.<br>
            <b>Linkedin: </b>Apple Inc.<br>
            <b>Address: </b>One Apple Park Way; Cupertino, CA 95014, U.S.A.<br></p>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by Roghith.
      </div>
    </div>
  </body>
</html>

```

### layout.css:
```

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background-color: whitesmoke;
}

#home-h{
  width: 50%;
  margin-left: 20px;
}

h1{
  font-size:100px;
  letter-spacing: 1px;
  width: fit-content;
}

.container {
  width: 1080px;
  margin: auto;
  margin-top: 25px;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 50px;
  border-radius: 10px;
}

.banner {
  display: block;
  width: 100%;
  height: 10px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/applelogo.png");
  background-size:25%;
  background-repeat: no-repeat;
  background-position: center;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  border-radius: 5px;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #000000;
  text-align: center;
  margin: 0px 0px 0px 0px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  height: 100%;
  padding: 10px;
  padding-top: 15px;
}

.menuitem a {
  text-decoration: none;
  color: #fff;
}

.content {
  display: block;
  width: 100%;
  background-color: #ffffff;
  min-height: 500px;
  border-width: 0.1px;
  border-color: white white black white;
  border-style: solid;
  background-image: url('/static/img/iPhone.jpg');
  background-position: right bottom;
  background-size: 45%;
  background-repeat: no-repeat;
}

#home-p{
  font-size: larger;
  width: 50%;
  margin-left: 30px;
  margin-top: -50px;
  color: rgb(73, 73, 73);
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

a
{
    text-decoration: none;
}
.p-page{
  display: grid;
  grid-template-columns: auto auto;
  padding: 70px;
}
.product-card {
    width: 400px;
    position: relative;
    box-shadow: 0 2px 7px #dfdfdf;
    background: #fafafa;
    margin: auto;
    margin-bottom: 50px;
}

.badge {
    position: absolute;
    left: 0;
    top: 20px;
    text-transform: uppercase;
    font-size: 13px;
    font-weight: 700;
    background: red;
    color: #fff;
    padding: 3px 10px;
}

.p-con{
  background: none;
}

.product-tumb {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 300px;
    padding: 50px;
    background: #fff;
}

.product-tumb img {
    max-width: 100%;
    max-height: 100%;
}

.product-details {
    padding: 30px;
    background-color: rgb(250, 250, 250);
}

.product-catagory {
    display: block;
    font-size: 12px;
    font-weight: 700;
    text-transform: uppercase;
    color: rgb(108, 108, 108);
    margin-bottom: 18px;
}

.product-details h4 a {
    font-weight: 500;
    display: block;
    margin-bottom: 18px;
    text-transform: uppercase;
    color: #363636;
    text-decoration: none;
    transition: 0.3s;
}

.product-details h4 a:hover {
    color: #fbb72c;
}

.product-details p {
    font-size: 15px;
    line-height: 22px;
    margin-bottom: 18px;
    color: #999;
}

.product-bottom-details {
    overflow: hidden;
    border-top: 1px solid #eee;
    padding-top: 20px;
}

.product-bottom-details div {
    float: left;
    width: 50%;
}

.product-price {
    font-size: 18px;
    color: #fbb72c;
    font-weight: 600;
}

.product-price small {
    font-size: 80%;
    font-weight: 400;
    text-decoration: line-through;
    display: inline-block;
    margin-right: 5px;
}

.product-links {
    text-align: right;
}

.product-links a {
    display: inline-block;
    margin-left: 5px;
    color: #e1e1e1;
    transition: 0.3s;
    font-size: 17px;
}

.product-links a:hover {
    color: #fbb72c;
}

.profile-card {
	width: 300px;
  margin: auto;
  margin-bottom: 80px;
	display: flex;
	flex-direction: column;
	align-items: center;
	padding: 2rem;
	background-color: white;
	border-radius: 1rem;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 50px;
}

.profile-image {
	position: relative;
	top: -60px;
	border-radius: 100px;
	width: 11rem;
	height: 11rem;
  background-image: url('/static/img/shakthi.png');
	background-position: center;
	background-size: cover;
  border:rgb(0, 0, 0) 3px solid; 
	box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 50px;
}

.profile-info {
	text-align: center;
	margin-top: -3rem;
	margin-bottom: 1rem;
}

.profile-info > .profile-name {
	color: #212121;
}

.profile-info > .profile-desc {
	color: #666666;
	font-size: 0.9rem;
}

.status {
	list-style: none;
	display: flex;
	justify-content: space-between;
	text-align: center;
	line-height: 1rem;
	margin-bottom: 1.3rem;
  padding: 10px;
}

.status-value {
	color: #212121;
	font-weight: 700;
}

.status-text {
	font-size: 0.8rem;
	color: #7c7c7d;
}

.action {
	display: flex;
	justify-content: space-between;
}

.btn {
	border: none;
	padding: 0.8em 1.9em;
	border-radius: 0.35rem;
	cursor: pointer;
	font-weight: 600;
}

.btn-pink {
	background: #000000;
	color: white;
}

.btn-gray-outline {
	border: 1px solid;
	background: transparent;
	color: #000000;
}

#about-p{
  padding:0px 70px;
  line-height: 25px;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #000;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #ffffff;
  border-radius: 0px 0px 10px 10px ;
}

.fill{
  transition: all 0.3s ease-in-out;
}

.fill:hover{
  background-color: #fff;
  cursor: pointer;
}

.fill:hover a{
  color: black;
}
```

## OUTPUT:

### Home Page:
![home](https://github.com/MohamedMunthasir/productcompanywebsite/assets/121957086/61e17e5c-4d1c-4074-8373-e872e931cdf3)

### Contact Page:
![output](output/people.png)![contact](https://github.com/MohamedMunthasir/productcompanywebsite/assets/121957086/2dbe6073-4dfa-4d80-9c32-fb1315535795)


### People Page:

![output](output/about.png)![people](https://github.com/MohamedMunthasir/productcompanywebsite/assets/121957086/12442a4c-0498-4ffd-ada1-5474c4a65aba)


### About Page:
![output](output/products.png)![about](https://github.com/MohamedMunthasir/productcompanywebsite/assets/121957086/d67fda06-a4ed-4f7a-98ec-0c848e735c01)

### Products Page:
![products](https://github.com/MohamedMunthasir/productcompanywebsite/assets/121957086/bafce06d-074b-47a0-9ed7-1d8fdc309e12)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
