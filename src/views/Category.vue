<template>
    <div class="container">
      <CategoryCard v-for="category in categories" :key="category.id" :category="category" />
    </div>
  </template>
  
  <script setup>
  import CategoryCard from '../components/CategoryCard.vue';
  
  const categories = [
    { id: 1, name: 'Electronics', description: 'Explore our electronic products', link: '/electronics' },
    { id: 2, name: 'Clothing', description: 'Discover the latest fashion trends', link: '/clothing' },
    { id: 3, name: 'Home & Furniture', description: 'Furnish your home with style', link: '/home-furniture' },
    { id: 4, name: 'Books', description: 'Immerse yourself in a world of knowledge', link: '/books' },
    { id: 5, name: 'Beauty & Personal Care', description: 'Look and feel your best', link: '/beauty' },
    { id: 6, name: 'Sports & Outdoors', description: 'Gear up for your favorite activities', link: '/sports-outdoors' },
    { id: 7, name: 'Toys & Games', description: 'Fun and entertainment for all ages', link: '/toys-games' },
    { id: 8, name: 'Automotive', description: 'Enhance your driving experience', link: '/automotive' },
    { id: 9, name: 'Health & Wellness', description: 'Take care of your well-being', link: '/health-wellness' },
    { id: 10, name: 'Jewelry', description: 'Adorn yourself with elegance', link: '/jewelry' },
  ];
  </script>
  
  <style scoped>
  .container {
    display: flex;
    flex-wrap: wrap;
  }
  </style>
  