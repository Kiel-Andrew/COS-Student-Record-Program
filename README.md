<h1>COS Student Record Program</h1>
<p>This project is used to maintain students information within college of science building</p>
<h3>How to Install?</h3>
<ol>
  <li>The programming language used is Java</li>
  <li>Use Apache NetBeans as IDE to run the files</li>
  <li>Download MySQL Workbench as your database</li>
  <li>Create a database and connect MySQL into Apache NetBeans</li>
  <li>To do this follow the video link: https://www.youtube.com/watch?v=rgF-5CwTZeE&t=480s</li>
  <li>Next, create 2 tables in MySQL named "login_tbl" and "reg_tbl"</li>
  
  <h3>login_tbl consist of</h3>
  <table>
    <thead>
      <tr>
        <td>Column Name</td>
        <td>Data Type</td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ID</td>
        <td>int AI PK</td>
      </tr>
      <tr>
        <td>username</td>
        <td>varchar(45)</td>
      </tr>
      <tr>
        <td>password</td>
        <td>varchar(45)</td>
      </tr>
    </tbody>
  </table>
  <h3>reg_tbl consist of</h3>
  <table>
    <thead>
      <tr>
        <td>Column Name</td>
        <td>Data Type</td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ID</td>
        <td>int AI PK</td>
      </tr>
      <tr>
        <td>fname</td>
        <td>varchar(45)</td>
      </tr>
      <tr>
        <td>lanme</td>
        <td>varchar(45)</td>
      </tr>
      <tr>
        <td>address</td>
        <td>varchar(45)</td>
      </tr>
      <tr>
        <td>mobileno</td>
        <td>varchar(45)</td>
      </tr>
      <tr>
        <td>email</td>
        <td>varchar(45)</td>
      </tr>
      <tr>
        <td>password</td>
        <td>varchar(45)</td>
      </tr>
    </tbody>
  </table>
  <li>After creating database table, go to Login.java and change the link url of line 236 JDBC into your database link</li>
  <li>If you have the password of your database then put it in line 236</li>
  <li>Repeat the processes for other ".java" files:</li>
  <li>MainFrame.java: Line 365</li>
  <li>Register.java: Line 25</li>
  <li>SignUp.java: Line 28</li>
  <li>Update.java: Line 393, 436, 470, and 563</li>
  <li>After configuring your code, try build and run</li>
</ol>
<h3>Reminder!</h3>
<p>These logo are edited and the author does not intend to copy the logo and disclaims all of the pictures used are original. Thus, the author only use the edited logo for school project purposes only. </p>
