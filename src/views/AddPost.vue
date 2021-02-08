<template>
  <div>
     <b-form @submit.prevent="onSubmit"class="mt-4">
      <b-form-group
        id="title-input-group"
        label="Title:"
        label-for="title"
      >
        <b-form-input
          id="title"
          v-model="post.title"
          type="text"
          placeholder="Enter Title"
          required
        ></b-form-input>
      </b-form-group>
      
      <b-form-group id="input-group-3" label="Post Content:" label-for="input-3">
        <b-form-textarea
          id="input-3"
          v-model="post.text"
          :state="post.content.length >= 10"
          placeholder="Enter at least 10 characters"
          rows="10"
        ></b-form-textarea>
      </b-form-group>

      <b-form-group id="input-group-2" label="Tags:" label-for="input-2">
        <b-form-input
          id="input-2"
          v-model="tag"
          placeholder="Type your tag and enter semicolon"
        ></b-form-input>
      </b-form-group>
      

      <b-button class="mr-2" type="submit" variant="primary">Submit</b-button>
      <b-button type="reset" variant="danger">Reset</b-button>
    </b-form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      post: {
        title: "",
        content: "",
        tag: '',
        tags: []
      },      
      show: true,
    };
  },
  methods: {
    onSubmit(event) {
      alert(JSON.stringify(this.form));
    }
  },
};
</script>
<style>
</style>