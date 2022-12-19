<template>
    <head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  </head>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">TO-DO List</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#"><div class="align">Home</div></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><div class="align">Features</div></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><div class="align">Pricing</div></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"><div class="button">Create</div></a>
        </li>
      </ul>
    </div>
  </div>

</nav>

<!-- Gutters -->
<div class="Sr">
<div class="container overflow-hidden">
  <div class="row">
    <div class="col">
     <div class="p-3 border bg-light">
        <div class="b1">
            TO-DO
        </div>
        <div class="add-task">
         <input type="text" placeholder="Add New Task" class="task-input">
         <input type="" class="submit-task" title="Add">
</div>
        
    </div>
    </div>
    <div class="col">
      <div class="p-3 border bg-light"><div class="b2">IN PROGRESS</div></div>
    </div>
    <div class="col">
      <div class="p-3 border bg-light"><div class="b3">DONE</div></div>
    </div>  
  </div>
</div>
</div>


  </template>
  
  <script>
  export default {
  
  }
  </script>
  
  <style>
  
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  .navbar-brand {
    color: #000000;
        padding: 0 20px;
        font-weight: 600;
  }
  
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color:black;
    font-size: 14px;
    background: #e6fcff;
    font-weight: bold;

  }
  
  .flex-center{
    display: flex;
    justify-content: center;
   }
  
   .navbar{
    background-image: linear-gradient(to right, #399cde,#399cde);
   }
   
   .align {
    margin-top: 11px;
   }
  
    .nav-item {
        color: #000000;
        padding: 0 20px;
        font-size: 14px;
        font-weight: 600;
        letter-spacing: .1rem;
        text-decoration: none;
        text-transform: uppercase;
    }

  .col .p-3{
    /* position: absolute; */
    width: 332px;
    height: 657px;

    margin-top: 90px;
    background: #f4f5f7;
    color: #000000;
    border-radius: 5px;
  }

  .add-task {
    margin-top: 20px;
    height: 40px;
    font-size: 14px;
    display: flex;
  }

  .submit-task {
    width: 32px;
    height: 32px;
    flex-shrink: 0;
    border: none;
    background: var(--add-button);
    color: #272727;
    background-image: url(AddIcon.png);
    background-size: 75px;
    background-position: center;
    background-repeat: no-repeat;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 0 12px 0 var(--add-button-shadow);
    margin-top: 10px;
  }

  .task-input {
    width: 100%;
    padding: 0 5px;
    outline: none;
    border: none;
    border-bottom: 1px solid #272727;
    background-color: transparent;
    margin-right: 15px;
    color: #272727;
    box-shadow: none;
    border-radius: 0;
  }

  .task-input::placeholder {
    color: #c4c8d1;
  }

  .Sr{
    margin-left: auto;
    margin-right: auto;
    width: 75%;
  }

  .row{
    margin-right: 10px;
  }
  

  .button{
  background-color: white; 
  border: none;
  padding: 11px 11px;
  padding-top: 10px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  border-radius: 2px;
  }

  .button:hover {
    background: #acd7f3;
  }

  .b1 {
  background-color: #dfe1e6; 
  border: none;
  padding: 5px 5px;
  padding-top: 4px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  border-radius: 2px;
  color: #42526e;
  }

  .b2 {
  background-color: #deebff; 
  border: none;
  padding: 5px 5px;
  padding-top: 4px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  border-radius: 2px;
  color: #0747a6;
  }

  .b3 {
  background-color: #e3fcef; 
  border: none;
  padding: 5px 5px;
  padding-top: 4px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  border-radius: 2px;
  color: #006644;
  }

  </style>  