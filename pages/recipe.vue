<template>
  <div class="container text-center my-5">
    <h1 class="border-bottom border-top border-3">{{ data.title }}</h1>
    <div class="border-bottom border-top css-test" role="alert">{{ data.description }}</div>
  </div>
  <div class="container mb-5">
    <div class="card mb-3 mx-auto">
      <div class="row g-0">
        <div class="col-md-4">
          <img
            src="https://img.cpcdn.com/recipes/3695776/894x1461s/03855e67f64548a05b1f995faabe8f57?u=12868943&p=1455726325"
            class="img-fluid rounded-start"
            alt="..."
          />
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title border-bottom border-2 css-mta">{{ data.material.title }}</h5>
            <div class="card-text">
              <ul>
                <li v-for="item in data.material.items" class="border-bottom">{{ item.text }}</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container mb-5">
    <h2>{{ data.make.title }}</h2>
    <ol>
      <li v-for="item in data.make.items" class="css-test pb-3">{{ item.text }}</li>
    </ol>
  </div>
  <div class="container mb-5">
    <div class="row gx-5">
      <div class="col-sm">
        <h3>{{ data.point.title }}</h3>
        <p v-for="item in data.point.lines">{{ item }}</p>
      </div>
      <div class="col-sm">
        <h3>{{ data.history.title }}</h3>
        <p v-for="item in data.history.lines">{{ item }}</p>
      </div>
    </div>
  </div>
</template>
<script setup>
const data = useRecipe();
</script>

<style scoped>
.css-test {
white-space:pre-wrap;
}
.css-mta {
display: inline-block;
}
</style>