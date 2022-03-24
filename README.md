# ☕️ Cafe - reservation system

# 👨‍💻 Author :
Dominik Blak : <a href="https://github.com/dominikblak">GitHub</a>
## 🚀 Demo :
<a href="https://cafe-cracow.herokuapp.com/">Cafe - reservation system</a>

### 📖 Description :
On the website, the user has the option to book an appointment and view recommendations, the content of which is loaded using Ajax from the api: https://jsonplaceholder.typicode.com/comments. The fragments of content on the home page and animation effects are loaded dynamically using jQuery. The site is serviced by the node.js server in the Heroku cloud service. The reply after sending the form together with the data entered by the user is loaded dynamically when using jQuery. The form has a standard validation provided by the browser. The form has been given a mechanism protecting against bots in the form of the Google ReCaptcha API.In the contact section, the map is displayed using the Google Maps API. The slider was created using the jquery-rwd-slider library. The animation was created using ScrollReval 4 libraries.The site is responsive - its layout automatically adapts to the screen size of the device.

<img src="https://github.com/dominikblak/Cafe-reservation-system/blob/master/DemoAnimation.gif" alt="demo_coffe">



#### 🧰 Technology :
-HTML<br>
-CSS<br>
-JavaScript<br>
-jQuery v3.3.1<br>
-Node.js<br>
-Ajax<br>

#### 🗃 Project structure :
```
📦caffe
 ┗ 📂Coffee
 ┃ ┣ 📂public
 ┃ ┃ ┣ 📂img
 ┃ ┃ ┃ ┣ 📜banner01.jpg
 ┃ ┃ ┃ ┣ 📜banner02.jpg
 ┃ ┃ ┃ ┣ 📜banner03.jpg
 ┃ ┃ ┃ ┣ 📜caffe-inside.jpg
 ┃ ┃ ┃ ┣ 📜caffe-logo.png
 ┃ ┃ ┃ ┣ 📜caffe_background.jpg
 ┃ ┃ ┃ ┣ 📜dekor.jpg
 ┃ ┃ ┃ ┣ 📜ikona_1.jpg
 ┃ ┃ ┃ ┣ 📜ikona_2.jpg
 ┃ ┃ ┃ ┣ 📜ikona_3.jpg
 ┃ ┃ ┃ ┣ 📜plaid.jpg
 ┃ ┃ ┃ ┣ 📜slajd1.jpg
 ┃ ┃ ┃ ┣ 📜slajd2.jpg
 ┃ ┃ ┃ ┣ 📜slajd3.jpg
 ┃ ┃ ┃ ┣ 📜slajd4.jpg
 ┃ ┃ ┃ ┣ 📜slajd5.jpg
 ┃ ┃ ┃ ┗ 📜top.jpg
 ┃ ┃ ┣ 📂js
 ┃ ┃ ┃ ┣ 📂libs
 ┃ ┃ ┃ ┃ ┗ 📜jquery.secret-source.min.js
 ┃ ┃ ┃ ┣ 📜bjqs-1.3.js
 ┃ ┃ ┃ ┣ 📜bjqs-1.3.min.js
 ┃ ┃ ┃ ┣ 📜jquery-3.3.1.min.js
 ┃ ┃ ┃ ┣ 📜jquery.js
 ┃ ┃ ┃ ┗ 📜scripts.js
 ┃ ┃ ┣ 📂style
 ┃ ┃ ┃ ┣ 📜animate.min.css
 ┃ ┃ ┃ ┣ 📜main.css
 ┃ ┃ ┃ ┣ 📜slider.css
 ┃ ┃ ┃ ┣ 📜sliderbjqs.css
 ┃ ┃ ┃ ┗ 📜style.css
 ┃ ┃ ┣ 📜gallery.html
 ┃ ┃ ┣ 📜index.html
 ┃ ┃ ┗ 📜offer.html
 ┃ ┣ 📜.gitignore
 ┃ ┣ 📜app.json
 ┃ ┣ 📜index.js
 ┃ ┣ 📜package.json
 ┃ ┣ 📜Procfile
 ┃ ┗ 📜README.md
```
