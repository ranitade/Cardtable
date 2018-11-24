<template>
  <table class="table">
    <thead class="card-header">
      <tr>
        <th><h2>title</h2></th>
        <th><h2>Subtitle</h2></th>
        <th><h2>Body</h2></th>
        <th><h2>Image</h2></th>
      </tr>
    </thead>
    <tbody>
      <tr class="active">
        <td class="card-title h5">{{ title }}</td>
        <td class="card-subtitle">{{ subtitle }}</td>
        <td class="card-body">{{ body }}</td>
        <td class="card-imgSrc">{{ imgSrc }}</td>
      </tr>
    </tbody>
  </table>
</template>

<script>
export default {
  name: "card-table",
  props: ["title", "subtitle", "body", "imgSrc"]
};
</script>
