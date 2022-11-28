<template>
  <div class="container" style="text-align:center">
    <h2>What type of bedrock is exposed on the side of the ditch here?</h2>
  <select name="cars" id="cars">
    <option value="c1">Whitwell Shale</option>
    <option value="c2">Sewanee Conglomerate</option>
    <option value="c3">Warren Point Sandstone</option>
    <option value="c4">Racoon Mountain Mudstone</option>
    <option value="c5">Pennington Limestone</option>
  </select>
  <img src="/s1.gif" class="center">
  <a href="/go2">Continue</a>
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
    a    {color: rgb(72, 235, 72); text-align: center; font-family: Inconsolata}
    select {color: greenyellow; font-family: Inconsolata; background-color: rgb(200, 40, 200);}

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