[# Ex.06 Book Front Cover Page Design
## Date:8/10/25

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
book.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>A SWEET MEMORIES</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Georgia', serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #f5f5f5;
    }

    .book-cover {
      width: 350px;
      height: 500px;
      background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
                  url('https://www.google.com/search/about-this-image?img=H4sIAAAAAAAA_wEWAOn_ChQIvq_X_rGtsLhhEM66xfTS39emVG6XraEWAAAA&q=https:%2F%2Fwww.ooijianhui.com%2Fthe-psychology-of-money%2F&cs=1&ctx=iv&hl=en-IN&sa=X&ved=0CA4Qg4ILahcKEwjY38m3mZSQAxUAAAAAHQAAAAAQBA') center/cover;
      border-radius: 10px;
      box-shadow: 0 15px 25px rgba(0,0,0,0.3);
      color: #fff;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 20px;
    }

    .book-title {
      font-size: 2em;
      font-weight: bold;
      margin-bottom: 15px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    .subtitle {
      font-size: 1.1em;
      font-style: italic;
      margin-bottom: 50px;
    }

    .author {
      font-size: 1.3em;
      margin-top: auto;
      border-top: 1px solid rgba(255,255,255,0.5);
      padding-top: 15px;
    }
  </style>
</head>
<body>

  <div class="book-cover">
    <div class="book-title">The pschology of money</div>
    
    <div class="author">by Morgan huosel </div>
  </div>

</body>
</html>




## OUTPUT:
![alt text](book.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
](https://www.google.com/search/about-this-image?img=H4sIAAAAAAAA_wEWAOn_ChQIvq_X_rGtsLhhEM66xfTS39emVG6XraEWAAAA&q=https:%2F%2Fwww.ooijianhui.com%2Fthe-psychology-of-money%2F&cs=1&ctx=iv&hl=en-IN&sa=X&ved=0CA4Qg4ILahcKEwjY38m3mZSQAxUAAAAAHQAAAAAQBA)
