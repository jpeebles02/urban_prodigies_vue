<template>
  <div class="artists">
    <div id="fh5co-why-us" class="animate-box" style="background-image: url(images/blackwall.jpg);">
      <div class="container">
        <div class="row">
          <div class="col-md-6 col-md-offset-3 text-center fh5co-heading">
            <h2>Ghetto Geniuses</h2>
            <p>
              These are all of the artists we interviewed for this project.
            </p>
          </div>

          <div v-for="artist in artists">
            <div class="card mb-3" style="max-width: 540px;">
              <div class="row no-gutters">
                <div class="col-md-6 col-md-offset-3 text-center fh5co-heading">
                  <img v-bind:src="artist.image_url" v-bind:alt="artist.name" />
                </div>
                <div class="col-md-8">
                  <div class="card-body">
                    <h3 class="card-title">{{ artist.name }}</h3>
                    <p class="card-text">{{ artist.bio }} | {{ artist.genre }} | {{ artist.video_url }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
img {
  width: 250px;
}
h2 {
  color: silver;
}
h3 {
  color: silver;
}
p {
  color: silver;
}
</style>

<script>
import axios from "axios";
export default {
  data: function() {
    return {
      artists: []
    };
  },
  created: function() {
    axios.get("/api/artists").then(response => {
      this.artists = response.data;
    });
  },
  methods: {}
};
</script>
