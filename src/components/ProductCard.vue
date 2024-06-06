<template>
    <div class="product-card">
      <div class="card-details">
        <img :src="product.thumbnail" :alt="product.title" class="thumbnail">
        <div class="card-row">
          <span class="label">Id:</span>
          <span>{{ product.id }}</span>
        </div>
        <div class="card-row">
          <span class="label">Title:</span>
          <span>{{ product.title }}</span>
        </div>
        <div class="card-row">
          <span class="label">Description:</span>
          <span>{{ product.description }}</span>
        </div>
        <div class="card-row">
          <span class="label">Discount %:</span>
          <span>{{ product.discountPercentage }}</span>
        </div>
        <div class="card-row">
          <span class="label">Rating:</span>
          <span>{{ product.rating }}</span>
        </div>
        <div class="card-row">
          <span class="label">Stock:</span>
          <span>{{ product.stock }}</span>
        </div>
        <div class="card-row">
          <span class="label">Brand:</span>
          <span>{{ product.brand }}</span>
        </div>
        <div class="card-row">
          <span class="label">Category:</span>
          <span>{{ product.category }}</span>
        </div>
        <div class="card-rowPrice">
          <span class="label">Price:  $</span>
          <span>{{product.price }}</span>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  const props = defineProps({
    product: {
      id: Number,
      title: String,
      description: String,
      price: Number,
      discountPercentage: Number,
      rating: Number,
      stock: Number,
      brand: String,
      category: String,
      thumbnail: String,    
    },
  });
  </script>
<style scoped>
.product-card {
  display: flex;
  flex-direction: column;
  border: 1px solid #ccc;
  border-radius: 8px;
  max-width: 300px;
  margin-bottom: 20px;
  margin-left: 10px;
}

.thumbnail {
  width: 100%;
  object-fit: cover;
  height: 40%;
}

.card-details {
  padding: 10px;
  flex-grow: 1;
  display: flex;
  flex-direction: column;
}

.card-row {
  display: flex;
  justify-content: space-between;
  margin-bottom: 5px;
}

.card-rowPrice {
  justify-content: space-between;
  background-color: rgb(234, 72, 72);
  padding: 10px;
  margin-top: auto;
  font-size: 30px;
}

.label {
  font-weight: bold;
  margin-right: 5px;
}
</style>

 