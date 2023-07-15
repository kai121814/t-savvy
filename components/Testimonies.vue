<template>
    <div class="container">
        <h1 class="title">testimonies</h1>
      <div class="border align-end">
        <div class="circle"></div>
        This Code Camp has helped me get the job of my dreams.
      </div>
      <div class="border align-left">
        <div class="circle2"></div>
        This Code Camp has helped me get the job of my dreams.
      </div>
      <div class="border align-end">
        <div class="circle"></div>
        This Code Camp has helped me get the job of my dreams.   
      </div>
    </div>
  </template>
  
  <style>
  .container {
    display: flex;
    flex-direction: column;
    margin-top: 20px;
    align-items: center;
  }
  
  .circle {
    width: 90px;
    height: 90px;
    border-radius: 50%;
    background-color: #B3C890;
    margin-right: 10px;
    position: absolute;
    top: 50%;
    left: -15px;
    transform: translateY(-50%);
  }
  .circle2 {
    width: 90px;
    height: 90px;
    border-radius: 50%;
    background-color: #B3C890;
    margin-right: 10px;
    position: absolute;
    top: 50%;
    right: -30px;
    transform: translateY(-50%);
  }
  
  .border {
    border-radius: 5px;
    border-style: solid;
    border-color: #B3C890;
    background-color: #DBDFAA;
    padding: 20px;
    position: relative;
    margin-bottom: 30px;
    width: 80%;
    font-family: sans-serif;
  }
  
  .align-end {
    text-align: end;
  }
  
  .align-left {
    text-align: left;
  }
  .title
  {
    text-transform: uppercase;
    color: #4AA3AA;
    outline: #ffffff;
    outline-width: 2px;
    
  }
  </style>
  