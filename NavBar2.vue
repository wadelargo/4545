<template>
    <div id="wrapper">
        <div id="sidebar">
        
        <ul>    
            <li><a href="#">Home</a></li>
            <li><a href="#">Chinese-Drama</a></li>
            <li><a href="#">K-Drama</a></li>
            <li><a href="#">TV Series</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">How to Download</a></li>
        </ul>

    </div>
    </div>
</template>


<style scoped>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    list-style: none;
    text-decoration: none;
}

#wrapper {
    display: flex;
    position: relative;
}

#wrapper #sidebar {
   
    width: 250px;
    height: 200vh;
   
    padding: 50px 0;
}
#wrapper #sidebar ul li {
  
    padding: 23px;
    border: 1px solid #449cf4;
 
    
}

#wrapper #sidebar a {
    border: 1px solid skyblue;
    text-align: center;
    background-color: rgb(18, 124, 167);
    padding: 8px;
    border-radius: 6px;
}

#wrapper #sidebar ul li a {
    
    color: white;
   display: block;  
   font-size: 20px;
}

#wrapper #sidebar a:hover {
    background: rgb(27, 145, 192);
    transition: 0.4s;
}
</style>