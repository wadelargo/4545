<template>
    <div class="container">
      <div class="header">
        <img src="../bg.png" alt="Profile Picture" class="profile-picture">
        <div class="heading">
          <h1 class="main-title">Darel's Profile</h1>
          <hr class="divider">
        </div>
      </div>
      <div class="info">
        <div class="info-item">
          <h2>Name:</h2>
          <p>Darel Amizola Tibong</p>
        </div>
  
        <div class="info-item">
          <h2>Address:</h2>
          <p>Centro, Bosongon, Tubigon, Bohol, PH</p>
        </div>
  
        <div class="info-item">
          <h2>Sex:</h2>
          <p>Male</p>
        </div>
  
        <div class="info-item">
          <h2>Birth Date:</h2>
          <p>February 14, 2003</p>
        </div>
  
        <div class="info-item">
          <h2>Height:</h2>
          <p>5.7ft</p>
        </div>
  
        <div class="info-item">
          <h2>Hobbies:</h2>
          <p>Reading, Coding, Traveling</p>
        </div>
  
        <div class="info-item">
          <h2>Languages:</h2>
          <p>Visayan, English, Tagalog</p>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 3%;
    text-align: center;
    background: linear-gradient(135deg, #4f44ff, #ff6c3d);
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  
  .header {
    position: relative;
  }
  
  .profile-picture {
    width: 150px;
    height: 150px;
    background-color: #fff;
    border-radius: 50%;
    margin: 0 auto 20px;
    display: block;
    object-fit: cover;
    border: 3px solid #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  .heading {
    text-align: center;
  }
  
  .main-title {
    font-size: 2.5em;
    color: #fff;
    margin-bottom: 10px;
  }
  
  .divider {
    border: 1px solid #fff;
    width: 50%;
    margin: 10px auto;
  }
  
  .info {
    text-align: left;
    margin-top: 20px;
  }
  
  .info-item {
    margin-bottom: 20px;
  }
  
  h2 {
    font-size: 1.5em;
    margin-bottom: 5px;
    color: #fff;
  }
  
  p {
    margin: 0;
    color: #f0f0f0;
    font-size: 1.2em;
  }
  </style>
  