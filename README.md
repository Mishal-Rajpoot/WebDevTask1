# WebDevTask1
Create a basic HTML page with a heading,paragraph,and an image.Add a hyperlink to another page.Use basic CSS to change the background color and font. Create a form with input fields (name, email, password) and a submit  button Apply basic CSS to style the form Use the Required Attributes For Validation Use the Pattern For Form Validation 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mishal</title>
    <style>
        body{
            background-image: url(mashroomhosue.jpg) ;
            background-repeat: no-repeat;
            background-size: cover;
        }
        .container{
            background-color: rgba(255, 255, 255, 0.5); /* Transparent white background with 80% opacity */
            justify-content: center;
            padding: 50px;
            border-radius: 8px;
            box-shadow: 7px 8px 8px rgba(0, 0, 0, 0.1);
            display: flex;
            width: 600px;
        }
    </style>
</head>

<body>
    
    <h1><p>Welcome to Comic Hub</h1>
    
        <div class="container">
            <p>
                If you're a fan of animated stories, quirky characters, and visually stunning comics, you've found your new favorite spot! <br>
                This platform is your go-to hub for all things cartoon comics—whether you’re in the mood for classic, webcomics,<br>
                 or exclusive new releases. Our platform brings together the best in illustrated humor, adventure, and heartwarming tales,<br>
                  all crafted by talented artists from around the world.<br>

                Why?<br>
                
                Diverse Selection: From classic slapstick comedy strips to cutting-edge webcomics and even animated graphic novels, there's something for everyone! Whether you enjoy fantasy, slice-of-life, action-packed adventures, or quirky humor, we've got a comic for you.
                
                Free and Easy Access: Browse through an extensive library of cartoons and comics—no subscription required. Just hop on and start reading instantly, whether on your desktop or mobile device.
                
                High-Quality Art: All comics are carefully curated to showcase the best art and storytelling. You’ll be captivated by the unique art styles and engaging stories.
                
                Regular Updates: We believe in keeping things fresh! Our library is updated frequently with new comics and cartoons, giving you plenty of content to explore every week.
                
                Community of Comic Lovers: Join a vibrant community where you can discuss your favorite characters, share fan art, and even interact with the creators through our forums and social media channels.
    </p>
    </div>
    
    <a href="loginpage.html" style="color: black; font-size: 30px; font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif">LOGIN</a>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task 1 web</title>
    <style>
        body{
            /* background-color: rgb(248, 255, 148); */
            background-image: url(mashroomhosue.jpg);
            font-family:Georgia, 'Times New Roman', Times, serif;
          
            justify-content: center;
            display: flex;
            padding: 50px;
            background-size: cover;
        }
        .container{
            padding: 20px;
            border-radius: 8px;
            box-shadow: 8px 8px 8px rgba(1, 1, 1, 3);
            width: 500px;
            background-image: url(image.jpg); 
            background-size: cover;

        }
    
        input[type="text"],
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }
    </style>
</head>
<body>
    
    <div class="container">
        <h1>Form</h1>
        <form action="">
            <div class="input">
                <label for="name">Name</label>
                <input type="text" name="name" id="name" required>
            </div>
            <div class="input">
                <label for="email">Email</label>
                <input type="email" name="email" id="email" required>
            </div>
            <div class="input">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required pattern=".{6,}" title="Password must be at least 6 characters long.">
            </div>
            <input type="submit" value="Submit">
        </form><br><br>
        <div>
            <a href="IntTask1.html"style="background-color: beige; font-size: 20px; font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-seri ">Back</a>
        </div>
            
    </div>
    
</body>
</html>
