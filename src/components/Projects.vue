<template>
    <div class="main">
        <div v-for="value in myJson" :key="value.id">
            <div class="row d-flex mb-5 align-items-center">
                <div class="col-sm-4">
                    <img class="img-fluid" :src="value.img" :alt="value.name">
                </div>
                <div class="col-6">
                    <!-- {{ value }} -->
                    <h1>{{ value.name }}</h1>
                    <p>{{ value.projectGoal }} </p>
                    <p> {{ value.totalSlots }} </p>
                    <p>{{ value.description }}</p>
                    <p hidden>{{ value.category }}</p>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
import { properties } from '../../dbB.json'
// json.forEach(x => { console.log(x.firstname, x.lastname); });

export default {
  data () {
    return {
      myJson: properties
    }
  }
}
</script>

<style>
    main
    .main {
        margin-top: 100px;
        /* margin-left: 200px; Same as the width of the sidenav */
    }
</style>
