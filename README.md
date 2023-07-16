<h1>Login App</h1>

<h2>Overview</h2>
<p>The Login App is a simple Java application that provides a graphical user interface (GUI) for users to enter their username and password and attempt to log in. It uses Swing components for the GUI and implements basic login functionality.</p>
<p>You can find the video tutorial <a href="https://youtu.be/UhsXtDm30cE"> here </a></p>

<h2>Files</h2>

<ol>
  <li><strong>App.java</strong>: This file contains the main class <code>LoginApp</code> which serves as the entry point for the application. It creates an instance of the <code>LoginGUI</code> class and makes the GUI visible.</li>

  <li><strong>LoginGUI.java</strong>: This file contains the <code>LoginGUI</code> class, which extends <code>JFrame</code> and represents the main GUI window of the application. It sets up the GUI components, including labels, text fields, and a login button. It also handles the login button's action event to perform the login logic.</li>

  <li><strong>CommonConstants.java</strong>: This file contains the <code>CommonConstants</code> class, which defines common constants used in the application, such as the application name, the frame size, and the text field size.</li>
</ol>

<h2>Usage</h2>

<p>To use the Login App, follow these steps:</p>

<ol>
  <li>Compile the Java files:</li>
  <pre><code>javac App.java LoginGUI.java CommonConstants.java</code></pre>

  <li>Run the compiled Java program:</li>
  <pre><code>java App</code></pre>

  <li>The Login App GUI window will appear. Enter your username and password in the respective text fields.</li>

  <li>Click the "Login" button.</li>

  <li>The application will check if the entered username and password match the expected values ("username" and "password" respectively). If the login is successful, the message "LOGIN SUCCESSFUL!" will be printed to the console. Otherwise, the message "LOGIN FAILED..." will be printed.</li>
</ol>

<h2>Class Details</h2>

<h3>1. App.java</h3>

<p>This class contains the <code>LoginApp</code> class, which serves as the entry point for the application.</p>

<h4>Methods</h4>
<ul>
  <li><code>main(String args[])</code>: The main method creates an instance of <code>LoginGUI</code> and makes the GUI visible.</li>
</ul>

<h3>2. LoginGUI.java</h3>

<p>This class represents the main GUI window of the application.</p>

<h4>Constructors</h4>
<ul>
  <li><code>LoginGUI()</code>: Constructs a new <code>LoginGUI</code> object. It sets up the JFrame with the application name, size, and close operation. It then calls the <code>addGUIComponents()</code> method to add the GUI components.</li>
</ul>

<h4>Methods</h4>
<ul>
  <li><code>addGUIComponents()</code>: This method sets up the GUI components, including labels, text fields, and a login button. It also sets up the layout using <code>SpringLayout</code> and adds event handling for the login button.</li>
</ul>

<h3>3. CommonConstants.java</h3>

<p>This class contains common constants used in the application.</p>

<h4>Constants</h4>
<ul>
  <li><code>APP_NAME</code>: Represents the name of the application.</li>
  <li><code>FRAME_SIZE</code>: Represents the size of the main GUI window as an array of two integers: width and height.</li>
  <li><code>TEXTFIELD_SIZE</code>: Represents the size of the text fields used in the GUI.</li>
</ul>
