<template>
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <div id="navbar">
      <div id="brand">
        Jflix
      </div>
        <div class="sud">
          <div class="search">
            <input type="text" placeholder="Seach..">
            <button id="search-button"><i class="fa fa-search"></i></button>
          </div>
        </div>
      <div id="main-nav">
        <img src="love1.jpg" alt="profile">
      <a href="#">Logout</a>
      </div>

  </div>
  

</template>

<style scoped>
.sud {
  padding: 5px;
  background-color: white;
  border-radius: 10px;
}
#navbar {
    padding: 15px;
    background-color: #449cf4;
    display: flex;
    justify-content: space-between;
    align-items: center;
   
}
#main-nav {
    display: flex;
    align-items: center; /* Vertically center-align items */
}

#main-nav img {
    width: 45px;
    height: 45px;
    border-radius: 50%;
    margin-right: 10px;
}

#main-nav a {
    text-decoration: none;
    color: white;
    font-size: 20px;
}

.search {
   
    color: white;
    font-size: 20px;
    margin-bottom: 1px;
}


#brand {
   
    border: 4px solid white;
    background-color: white;
    border-radius: 5px; 
    margin-left: 20px;
    font-size: 30px;
    
    
}

.search input {
  padding: 9px;
  width: 250px;
  border-radius: 1px;
}

.search button {
  padding: 9px;
  border-radius: 1px;
  cursor: pointer;
}

.search button:hover {
  background: rgb(142, 212, 240);
  transition: 0.2s;
}
</style>