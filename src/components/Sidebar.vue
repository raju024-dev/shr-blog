<template>
  <div>
    <b-card header="Search" class="my-4">
      <b-input-group class="mt-3">
        <b-form-input></b-form-input>
        <b-input-group-append>
          <b-button variant="secondary">Go</b-button>
        </b-input-group-append>
      </b-input-group>
    </b-card>
    <b-card class="my-4" header="Categories">
      <b-row>
        <b-col md="6" sm="12">
          <ul class="list-unstyled mb-0">
            <li>
              <a href="#">Web design</a>
            </li>
            <li>
              <a href="#">HTML</a>
            </li>
            <li>
              <a href="#">Freebies</a>
            </li>
          </ul>
        </b-col>
        <b-col md="6" sm="12">
          <ul class="list-unstyled mb-0">
            <li>
              <a href="#">Javascript</a>
            </li>
            <li>
              <a href="#">CSS</a>
            </li>
            <li>
              <a href="#">Tutorials</a>
            </li>
          </ul>
        </b-col>
      </b-row>
    </b-card>
    <b-card header="Side widgest">
      You can put anything you want inside of these side widgets. They are easy
      to use, and feature the new Bootstrap 4 card containers!
    </b-card>
  </div>
</template>

<script>
export default {
};
</script>

<style>
</style>