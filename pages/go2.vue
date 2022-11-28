<template>
  <div class="container" style="text-align:center">
    <h2>What year was this built?</h2>
  <select name="cars" id="cars">
    <option value="c1">1957</option>
    <option value="c2">1902</option>
    <option value="c3">1750</option>
    <option value="c4">1857</option>
    <option value="c5">1895</option>
  </select>
  <img src="/s1.gif" class="center">
  <a href="/go3">Continue</a>
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
    select {color: greenyellow; font-family: Inconsolata; background-color: rgb(200, 40, 200);}
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