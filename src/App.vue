<script>
import ProductCard from './components/ProductCard.vue';

export default {
  components: {
    ProductCard
  }
};
</script>

<template>
  <div id="app">
    <ProductCard
      name="Українська вишиванка"
      description="Стильна вишиванка з традиційними орнаментами."
      :price="1500"
      image="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQlG4rzbDxYO-2iNodEyIAbZy3S_ltQAiPM7Hd21htnOQ&s=10"
    />
  </div>
</template>
