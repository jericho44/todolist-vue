<template>
  <div class="home">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2>What I do Today?</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">
          <div
            class="tugas"
            v-for="tugasSaya in tugas"
            v-bind:key="tugasSaya.id"
          >
            <p>{{ tugasSaya.nama }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  data: function () {
    return {
      tugas: [
        {
          id: 1,
          nama: "Megalodon",
        },
        {
          id: 2,
          nama: "Mengoding",
        },
        {
          id: 3,
          nama: "Menghosting",
        },
      ],
    };
  },
  components: {},
};
</script>
