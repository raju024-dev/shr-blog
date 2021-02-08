<template>
  <div>
    <h1 class="mt-4">Post Title</h1>
    <p class="lead">by <a href="#">User</a></p>
    <hr />
    <p>Posted on January 1, 2019 at 12:00 PM</p>
    <hr />
    <img class="img-fluid rounded" src="http://placehold.it/900x300" alt="" />
    <hr />
    <p class="lead">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus iure
      quos distinctio totam numquam nam vel qui illum magnam, ipsum eius aut
      necessitatibus, soluta harum, ducimus repellendus rerum ipsa! Libero nulla
      provident, alias magni voluptatibus, natus et laborum quasi sit inventore
      accusamus culpa. Labore nihil nobis accusantium cupiditate illum quam
      optio voluptates ratione cum corrupti mollitia saepe nulla nisi, deserunt
      impedit nostrum velit molestias dignissimos. Accusamus rerum, aliquid sit
      omnis suscipit quisquam iusto dignissimos! Nulla fugit unde accusamus
      accusantium. Similique repellendus eveniet porro omnis ut. Cupiditate
      laboriosam molestias voluptate animi doloribus voluptas suscipit odio
      maiores. Non possimus sit fuga exercitationem.
    </p>
    <hr />

    <!-- Comments Form -->
    <div class="card my-4">
      <h5 class="card-header">Leave a Comment:</h5>
      <div class="card-body">
        <form>
          <div class="form-group">
            <textarea class="form-control" rows="3"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
    </div>

    <!-- Single Comment -->
    <div class="media mb-4">
      <img
        class="d-flex mr-3 rounded-circle"
        src="http://placehold.it/50x50"
        alt=""
      />
      <div class="media-body">
        <h5 class="mt-0">Commenter Name</h5>
        Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque
        ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus
        viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla.
        Donec lacinia congue felis in faucibus.
      </div>
    </div>
    <!-- Comment with nested comments -->
    <div class="media mb-4">
      <img
        class="d-flex mr-3 rounded-circle"
        src="http://placehold.it/50x50"
        alt=""
      />
      <div class="media-body">
        <h5 class="mt-0">Commenter Name</h5>
        Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque
        ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus
        viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla.
        Donec lacinia congue felis in faucibus.
        <div class="media mt-4">
          <img
            class="d-flex mr-3 rounded-circle"
            src="http://placehold.it/50x50"
            alt=""
          />
          <div class="media-body">
            <h5 class="mt-0">Commenter Name</h5>
            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus
            scelerisque ante sollicitudin. Cras purus odio, vestibulum in
            vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi
            vulputate fringilla. Donec lacinia congue felis in faucibus.
          </div>
        </div>
        <div class="media mt-4">
          <img
            class="d-flex mr-3 rounded-circle"
            src="http://placehold.it/50x50"
            alt=""
          />
          <div class="media-body">
            <h5 class="mt-0">Commenter Name</h5>
            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus
            scelerisque ante sollicitudin. Cras purus odio, vestibulum in
            vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi
            vulputate fringilla. Donec lacinia congue felis in faucibus.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>
