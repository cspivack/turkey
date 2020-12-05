<template>
  <div class="container">
    <div>
      <h1 class="title">
        Recipes
      </h1>
      <div>
        <a v-for="recipe in recipes" :key="recipe.name" :href="recipe.link" target="_blank">
          {{ recipe.name }}
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      recipes: [
        {
          name: 'Cranberry sauce',
          link: 'https://cooking.nytimes.com/recipes/10267-cranberries-and-port-wine'
        },
        {
          name: 'Turkey',
          link: 'https://recipes.craigspivack.com/posts/spatchcocked-turkey-with-herb-butter'
        },
        {
          name: 'Collard greens',
          link: 'https://recipes.craigspivack.com/posts/vegan-collard-greens'
        },
        {
          name: 'Stuffing',
          link: 'https://www.thecomfortofcooking.com/2010/02/old-fashioned-bread-stuffing.html'
        },
        {
          name: 'Mac and cheese',
          link: 'https://recipes.craigspivack.com/posts/simple-mac-cheese'
        },
        {
          name: 'Gravy',
          link: 'https://recipes.craigspivack.com/posts/turkey-gravy'
        }
      ]
    }
  }
}
</script>
