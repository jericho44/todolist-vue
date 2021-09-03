<template>
  <div class="profile">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 mx-auto">
          <div class="d-flex">
            <div class="flex-shrink-0">
              <img
                src="../assets/+62856-0453-374320210815_193303.jpg"
                class="user-pic"
              />
            </div>
            <div class="flex-grow-1 ms-3">
              <h3>Heading</h3>
              <p>
                This is some content from a media component. You can replace
                this with any content and adjust it as needed.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "Profile",
  components: {},
};
</script>

<style scoped>
.user-pic {
  height: 120px;
  width: 120px;
  border-radius: 200%;
}
</style>