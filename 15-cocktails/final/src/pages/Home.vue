<template>
  <Search />
  <CocktailList />
</template>

<script>
import CocktailList from '@/components/CocktailList.vue';
import Search from '@/components/Search.vue';

export default {
  name: 'Home',
  components: {
    CocktailList,
    Search,
  },
}
</script>
