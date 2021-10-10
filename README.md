![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

<h3 align="center">Contact Info</h3>
<p align="center">Email: <a href="mailto: Hchristiansen2010@gmail.com">Hchristiansen2010@gmail.com</a></p>
<p align="center">Phone: (503)410-9280</p>
<p align="center">Linkedin: <a href="https://www.linkedin.com/in/hunter-christiansen-59835776/">Hunter Christiansen</a></p>

<h3>About</h3> 

<p>I recently graduated (2021) from Oregon State University where I obtained a Bachelor's of Computer Science. Throughout college and my personal projects I have gained experience in a wide variety of areas including web application development, mobile, and data science/artificial intelligence.</p>

<h3>Portfolio</h3>

<h4><a href="https://github.com/hchrist2010/ModularEncryptionDaemon">Modular Encryption Daemon</a></h4>

<p>The Modular Encryption Daemon contains three programs. A keygen, an encryption and a decryption program. These programs are not actually Daemons but function very similarly to one.</p>

<p>The keygen will create a string of capital letters and spaces of a length defined by the user.</p>

<p>otp_enc_d is the decryption daemon. When starting this program, the user will define a listening port and run it in the background. When the user wishes to encrypt a file, the user calls this program and passes in the file to be encrypted, the key, and the port assigned to otp_enc followed by a redirect to the file destination.</p>

<p>opt_dec_d works the same as opt_enc_d, it is a process run in the background that can decrypt a file that was previously encrypted by otp_enc_d using the same keygen.</p>

<p>The encryption and decryption programs are capable of running 5 processes simultaneously.</p>

<h4><a href="https://github.com/hchrist2010/SmallShell">Small Shell</a></h4>

<p>Small Shell is a simplified shell written in C. The shell functionally is very similar to bash, it allows for file navigation as well as the execution of simple commands such as "cat", "ls", and "echo". The user can also launch programs from the shell and can run anything either in the foreground or the background.</p>

<h4><a href="https://github.com/hchrist2010/WasteAGram">WasteAGram</a></h4>
<p>WasteAGram is an android mobile application that is used to record food waste. This application is meant to be used by multiple users at a time.</p>
<p>When a user is about to throw out any food, they can use this app to take a picture of it and record the amount about to go to waste.</p>
<p>The application will then capture the GPS coordinates of the user, and the date the post was created in order to finish the post.</p>
<p>These posts are then displayed to the homepage where there is a newsfeed of previous posts and a running total amount. Each feed item shows the date the post was created and the amount of waste.</p>
<p>If the user selects an individual post, they are taken to a page that will display the photo of the waste, the date it was created, the amount,
       and the GPS location of the user when they created the post. This application was created using the Flutter SDK and utilizes the firebase cloud server for persistent storage.</p>
       
<h4>Custom Flutter Geofencing</h4>
<p>This was my senior capstone project. My team and I were tasked with building a proof of concept mobile application that would dynamically load data based on whether the user was inside or outside of a defined area. These areas are meant to surround locations like buildings or campuses. The primary challenge we faced was to find a way to represent these abstract areas using only GPS coordinates.</p>

<p>During development, I created an algorithm that can determine if the user is inside or outside one of these shapes using only the coordinates of the corners of each area and the user’s current location. I did this by defining a side of the shape using a linear equation that will determine what side of the boundary the user is on. By taking an aggregate of these measurements, I was able to determine if the user is inside, if they are not, I was also able to determine how far away the object is. This whole process functions in O(n) time.</p>

<p>To store all of the data, we created a firebase backend. This contains the GPS coordinates that make up each object as well as some information tied to each object that can be presented to the user when it is determined that they are inside an object or very near one.</p>
