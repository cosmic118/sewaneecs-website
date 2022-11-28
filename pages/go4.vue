<template>
  <div class="container" style="text-align:center">
    <h2>How many different bells are present?</h2>
  <select name="cars" id="cars">
    <option value="c1">4</option>
    <option value="c2">24</option>
    <option value="c3">12</option>
    <option value="c4">32</option>
    <option value="c5">26</option>
  </select>
  <img src="/s1.gif" class="center">
  <h3>Tap to submit</h3>
  </div> 
  </template>
 
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@200&family=Roboto:wght@100&display=swap');
    body{
      background: black; /* not apply if you go from page-1 to page-2 */
    }
    h1   {color: rgb(72, 235, 72);text-align: center; font-family: Inconsolata}
    h2   {color: rgb(72, 235, 72); text-align: center; font-family: Inconsolata}
    h3   {color: rgb(72, 235, 72); text-align: center; font-family: Inconsolata}
    select {color: black; font-family: Inconsolata; background-color: rgb(120, 40, 200);}
    a    {color: rgb(72, 235, 72); text-align: center; font-family: Inconsolata}
    .container {
      max-width: 70%;
      margin: 0 auto;
    }

    .center {
      display: block;
      margin-left: auto;
      margin-right: auto;
      width: 50%;
      margin-top: 10%;
    }
  </style>