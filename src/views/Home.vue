<template>
  <div class="home">
    <div class="container">
      <div class="row">
        <div class="col-md-12 col-lg-6 profilecard mb-2">
          <b-card no-body class="overflow-hidden" style="max-width: 540px;">
            <b-row no-gutters>
              <b-col md="6">
                <b-card-img :src="profilePicture" alt="Image" class="rounded-0">
                </b-card-img>
              </b-col>
              <b-col md="6">
                <b-card-body title="Michael Pedzimaz">
                  <b-card-text>
                    Full stack developer with Java, Coldfusion, and JavaScript
                    expertise.
                  </b-card-text>
                </b-card-body>
              </b-col>
            </b-row>
          </b-card>
        </div>
        <div class="col-md-12 col-lg-6 profilecard">
          <b-card no-body class="overflow-hidden" style="max-width: 540px;">
            <b-row no-gutters>
              <b-col md="6">
                <b-card-img :src="profilePicture" alt="Image" class="rounded-0">
                </b-card-img>
              </b-col>
              <b-col md="6">
                <b-card-body title="Michael Pedzimaz">
                  <b-card-text>
                    Full stack developer with Java, Coldfusion, and JavaScript
                    expertise.
                  </b-card-text>
                </b-card-body>
              </b-col>
            </b-row>
          </b-card>
        </div>
      </div> <!--/row-->
    </div> <!--/container-->
    <div class="container mt-5">
      <div class="row bg-primary">
        <div class="col">
          <p class="bg-secondary">Test paragraph</p>
        </div>
        <div class="col">
          <p class="bg-danger">Test paragraph</p>
        </div>
        <div class="col">
          <p class="bg-info">Test paragraph</p>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
import profilePicture from '@/assets/img/ProfilePic.jpg'

export default {
  name: 'home',
  data: function () {
    return {
    }
  },
  computed: {
    profilePicture () {
      return profilePicture
    }
  }
}
</script>
<style scoped>
.profilecard {
  opacity: 0.7;
}
</style>
