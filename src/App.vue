<template>
  <div v-for="card in cardtable"><card-table v-bind="table"></card-table></div>
</template>
<script>
import CardTable from "./components/cardtable";

export default {
  name: "App",
  components: {
    CardTable
  },

  data() {
    return {
      cards: [
        {
          title: "CN Tower",
          subtitle: "Best place ever",
          body: "The food is pretty bad but the view is great",
          imgSrc:
            "https://www.torontobusco.com/wp-content/uploads/2017/05/n-dd-600x400.jpg"
        },
        {
          title: "Niagara Falls CA",
          subtitle: "Second best",
          body: "The food is horrible but the view is decent",
          imgSrc:
            "https://media-cdn.tripadvisor.com/media/photo-s/0f/73/db/0a/niagara-falls-boat-tour.jpg"
        },
        {
          title: "Niagara Falls US",
          subtitle: "Second best",
          body: "The food is horrible but the view is decent",
          imgSrc:
            "https://media-cdn.tripadvisor.com/media/photo-s/0f/73/db/0a/niagara-falls-boat-tour.jpg"
        }
      ]
    };
  }
};
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
