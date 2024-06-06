<template>
    <div class="category-card">
      <div class="card-details">
        <div class="card-row">
          <span class="label">Category:</span>
          <span class="category-name">{{ category.name }}</span>
        </div>
        <div class="card-row">
          <span class="label">Description:</span>
          <span class="category-description">{{ category.description }}</span>
        </div>
        <div class="card-row">
          <span class="label">View Products:</span>
          <a :href="category.link" class="category-link">Explore</a>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  const props = defineProps({
    category: {
      name: String,
      description: String,
      link: String,
    },
  });
  </script>
  
  <style scoped>
  .category-card {
    display: flex;
    flex-direction: column;
    border: 1px solid #ddd;
    border-radius: 8px;
    max-width: 300px;
    margin-bottom: 20px;
    margin-left: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease-in-out;
  }
  
  .category-card:hover {
    transform: translateY(-5px);
  }
  
  .card-details {
    padding: 15px;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
  }
  
  .card-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 10px;
  }
  
  .category-name {
    color: #4CAF50;
    font-weight: bold;
  }
  
  .category-description {
    color: #555;
  }
  
  .category-link {
    display: inline-block;
    padding: 8px 12px;
    background-color: #4CAF50;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease-in-out;
  }
  
  .category-link:hover {
    background-color: #45a049;
  }
  
  .label {
    font-weight: bold;
    margin-right: 5px;
  }
  </style>
  