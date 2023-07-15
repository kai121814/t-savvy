<template>
    <div class="container">
        <h1>WHAT WE TEACH</h1>
      <div class="flex">
        <div class="card"><p>FIGMA</p></div>
        <div class="card"><p>HTML | CSS | JAVASCRIPT</p></div>
        <div class="card"><p>NUXT.JS | TAILWINDCSS | TYPESCRIPT</p></div>
        <div class="card"><p>PYTHON</p></div>
        <div class="card"><p>DJANGO</p></div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .container {
    display: flex;
    justify-content: center;

  }
  
  .card {
    width: 250px;
    height: 350px;
    background-color: #b6bb80;
    margin: 10px;
    border-radius: 12%;
    text-align: center;
    word-wrap: break-word;
    font-weight: 700;
  }

  .card-large {
    width: 300px;
    height: 450px;
    background-color: #6DB3B8;
    margin: 10px;
    border-radius: 12%;
    text-align: center;

  }
  
  .flex {
    display: flex;
    align-items: center;
  }
  </style>