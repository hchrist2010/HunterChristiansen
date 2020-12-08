<h3 align="center">Contact Info</h3>
<p align="center">Email: christhu@oregonstate.edu</p>
<p>Phone: (503)410-9280</p>
<p>Linkedin: <a href="https://www.linkedin.com/in/hunter-christiansen-59835776/">Hunter Christiansen</a></p>

<h3>About</h3> 

<p>I am a senior computer science student at Oregon State University working towards a bachelor's degree in Artificial Intelligence</p>    

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
       
<h4><a href="https://github.com/hchrist2010/CustomFlutterGeofencing">CustomFlutterGeofencing</a></h4>
<p>This mobile application was created for my senior capstone project to explore the location and geofencing capabilities of the 
      <a href="https://pub.dev/packages/location">Location</a> package for Google's Flutter SDK.</p>
<p>The home screen presents the user with a constant stream of their GPS coordinates, followed by the ability to create custom geofencing objects.</p>
<p>The user is able to create these objects by capturing their current point, as soon as the user has captured at least 3 points, they can press the Create Object button which will transform those points into an object. This is done by creating a linear equation between two points to create a virtual line in space. This also contains a min/max of the latitude and longitude for the entire object as well as each line.</p>
<p>The user is able to clear all objects and points from the home screen.</p>
<p>When the user presses the GeoFence button, they are navigated to a screen that will alert them as to whether they are in an object or not. This is done by applying the user's current position to the linear equations created during the object creation process. If the user's location is within the min/max boundary of the line and when applied to the equation is less than the constant defined during creation, the user is directly west of the current line. If the user is west of an odd number of lines, then we know the user is inside the area defined by the object.</p>
<p>Currently, this portion of the application is set up to use some test data I created so I didn't have to walk around whenever I wanted to test the application, but it can be easily modified to use the location stream and custom objects created by the user.</p>
