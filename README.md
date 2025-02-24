[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_zIxYTtp)
# INST377-Lab

# Name (Please Input your name): Blen Bekele
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>INST377 - Lab 4</title>
  <style>
    /* Basic page styling */
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #ADD8E6; /* Light blue background (#ADD8e6 */
    }

    h1 {
      text-align: left;
      color: #fff;
      padding: 1rem;
      margin: 0;
    }

    /* Container to hold all sections in a row */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-bottom: 2rem;
    }

    /* Each purple section box with white borders */
    .section {
      background-color: #6a0dad; /* Purple background */
      border: 2px solid #fff;    /* White border */
      border-radius: 10px;
      width: 220px;
      margin: 1rem;
      padding: 1rem;
      text-align: center;
      color: #fff;
    }

    .section h2 {
      margin-top: 0;
    }

    label {
      display: inline-block;
      margin-bottom: 0.5rem;
    }

    /* text inputs styles*/
    input[type="text"] {
      width: 90%;
      padding: 5px;
      border-radius: 5px;
      border: none;
      margin-bottom: 1rem;
    }

    /* button style */
    button {
      background-color: #a020f0;
      border: none;
      border-radius: 5px;
      color: #fff;
      padding: 8px 16px;
      cursor: pointer;
      font-size: 1rem;
    }

    button:hover {
      background-color: #8B008B;
    }
  </style>
</head>
<body>
  <h1 id="pageHeading">INST377 - Lab 4</h1>

  <div class="container">
    <!-- Alert Me Section -->
    <section class="section" id="alertSection">
      <h2>Alert Me Section</h2>
      <form id="alertForm">
        <label for="nameInput">Name:</label><br>
        <input type="text" id="nameInput" name="name" required><br>
        <button type="button" onclick="alertName()">Alert Me</button>
      </form>
    </section>

    <!-- Change Color Section -->
    <section class="section" id="colorSection">
      <h2>Change Color Section</h2>
      <button type="button" onclick="changeColor()">Change Color</button>
    </section>

    <!-- Text Tester Section -->
    <section class="section" id="textTesterSection">
      <h2>Text Tester Section</h2>
      <form id="textTesterForm">
        <label for="textInput">Text:</label><br>
        <input type="text" id="textInput" name="text"><br>
        <button type="button" onclick="validateText()">Validate Text</button>
      </form>
    </section>

    <!-- Add Text Section -->
    <section class="section" id="addTextSection">
      <h2>Add Text Section</h2>
      <button type="button" onclick="addText()">Add Text</button>
    </section>
  </div>



# Comments: 
