<template>
  <div class="about">
    <Mainheader />

    <v-row no-gutters>
      <v-col>
        <img
          src="https://images.pexels.com/photos/674010/pexels-photo-674010.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
          alt=""
        />
      </v-col>
      <v-col>
        <div style="height: 77%">
          <v-carousel cycle class="v" :show-arrows="false">
            <v-carousel-item v-for="slide in slides" :key="slide">
              <v-sheet height="80%" width="70%" class="sheet">
                <!-- <v-row class="fill-height" align="center" justify="center"> -->
                <div class="text-h2" style="text-align: center">
                  <h1 style="color: black">{{ slide.title }} slide</h1>
                </div>
                <!-- </v-row> -->
              </v-sheet>
            </v-carousel-item>
          </v-carousel>
        </div>
      </v-col>
      <v-col>
        <img
          src="https://images.pexels.com/photos/674010/pexels-photo-674010.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
          alt=""
        />
      </v-col>
    </v-row>
    <Footer />
  </div>
</template>

<script>
export default {
  data() {
    return {
      slides: [
        { title: 'first' },
        { title: 'second' },
        { title: 'third' },
        { title: 'fourth' },
        { title: 'fifth' },
      ],
    }
  },
}
</script>

<style>
.about {
  background-image: url('https://image.shutterstock.com/image-photo/old-brick-black-color-wall-260nw-1605128917.jpg');
  background-size: cover;
  height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  width: 210vh;

  /* background-origin: border-box; */
  border: rgb(243, 72, 100) 10px solid;

  text-align: center;
}

.sheet {
  margin-left: 15%;
  margin-top: 10%;
}
.v {
  background-color: rgb(224, 108, 128);
  width: 100%;
  height: 100%;
  margin-left: 0%;
}
img {
  height: 74%;
  width: 100%;
}
</style>