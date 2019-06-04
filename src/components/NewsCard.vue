<template>
  <div class="ds-shadow-raised ds-slide-up">
    <li>
      <img class="ds-img-responsive" :src="newsObject.imageSrc" alt="”PictureHere”">
      <h1>
        {{newsObject.title}}
        <br>
        <!-- TODO: Add Author -->
              <p>Author here</p>
      </h1>
      {{newsObject.description}}
      <hr>
      <span class="ds-icon-size-default ds-icon-link-external ds-pad-r-0_5"></span>
      <a :href="newsObject.blogPostURL">View Full Post</a>
    </li>
  </div>
</template>

<script>
export default {
  props: ["newsObject"]
};
</script>

<style>
</style>

