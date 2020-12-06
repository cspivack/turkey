<template>
  <div class="container">
    <div>
      <h1 class="title">
        Ingredients
      </h1>
      <p>
        All ingredients of course in order by section in my local grocery store.
      </p>
      <ul>
        <li v-for="ingredient in ingredients" :key="ingredient.name">
          {{ ingredient.name }} ({{ ingredient.amount }})
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      ingredients: [
        {
          name: 'Celery',
          amount: '1 bunch'
        },
        {
          name: 'Carrot (large)',
          amount: '1'
        },
        {
          name: 'Garlic',
          amount: '10 cloves'
        },
        {
          name: 'Fresh chives',
          amount: '1/4 cup'
        },
        {
          name: 'Fresh parsley',
          amount: '1/4 cup'
        },
        {
          name: 'Fresh sage',
          amount: '1/4 cup'
        },
        {
          name: 'Fresh thyme',
          amount: '2 tbsp'
        },
        {
          name: 'Fresh rosemary',
          amount: 'Some sprigs'
        },
        {
          name: 'Shallot',
          amount: '1'
        },
        {
          name: 'Onion (large)',
          amount: '2'
        },
        {
          name: 'Onion (small)',
          amount: '1'
        },
        {
          name: 'Collard greens',
          amount: '3-4 lbs'
        },
        {
          name: 'Cranberries',
          amount: '12 oz'
        },
        {
          name: 'Cinnamon stick',
          amount: '1'
        },
        {
          name: 'Bay leaves',
          amount: '2'
        },
        {
          name: 'Smoked paprika',
          amount: '2 tsp'
        },
        {
          name: 'Crushed red pepper',
          amount: '1 tsp'
        },
        {
          name: 'Kosher salt',
          amount: 'Buy a box if low'
        },
        {
          name: 'Flour',
          amount: 'Buy a bag if low'
        },
        {
          name: 'Sugar',
          amount: 'Buy a bag if low'
        },
        {
          name: 'Baking powder',
          amount: '2 tbsp'
        },
        {
          name: 'Soy sauce',
          amount: '1 tsp'
        },
        {
          name: 'Chicken stock',
          amount: '2 32 oz boxes'
        },
        {
          name: 'Better Than Bouillon',
          amount: '1 jar'
        },
        {
          name: 'Macaroni',
          amount: '1/2 lb'
        },
        {
          name: 'Turkey',
          amount: '12-14 lbs'
        },
        {
          name: 'Milk',
          amount: '1 cup'
        },
        {
          name: 'Butter',
          amount: '3 sticks'
        },
        {
          name: 'Egg',
          amount: '1'
        },
        {
          name: 'Cheddar cheese',
          amount: '8 oz'
        },
        {
          name: 'Port wine',
          amount: '1 cup'
        },
        {
          name: 'Baguette',
          amount: '1'
        }
      ]
    }
  }
}
</script>
