<template>
    <base-card>
      <!-- <li> -->
        <header>
          <h3>{{title}}</h3>
          <button>Delete</button>
        </header>
        <p>{{description}}</p>
        <nav>
          <a href="link">View Resources</a>
        </nav>
      <!-- </li> -->
    </base-card>
</template>

<script>
// import BaseCard from './../../UI/BaseCard.vue'

export default{
    props: ['title', 'description', 'link'],
    // components: {  // no need as base-class declared as a global component in App.vue
    //   BaseCard
    // }
}
</script>

<style scoped>

li {
  margin: auto;
  max-width: 40rem;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h3 {
  font-size: 1.25rem;
  margin: 0.5rem 0;
}

p {
  margin: 0.5rem 0;
}

a {
  text-decoration: none;
  color: #ce5c00;
}

a:hover,
a:active {
  color: #c89300;
}

</style>