<template>
  <div class="myService">
    <h1 class="text-center">
      Classes
    </h1>
    <h6 class="text-center">
      All classes take place in the temple, contact our staff for more info.
    </h6>
    <b-row class="my_row">
      <b-col class="my_col_one" xl="3" lg="3" md="6" sm="12">
        <b-card
          class="my-custom-class"
          title="Meditation Hall"
          img-src="https://live.staticflickr.com/4169/34303404360_a02a652182_z.jpg"
          img-alt="Image"
          img-top
        >
          <b-card-text>
            There are many Meditation Hall's at shrine and are open for every
            sahaja yogi. sahaja yogi's can feel very intense mother's love
            (vibrations)
          </b-card-text>
        </b-card>
      </b-col>
      <b-col class="my_col_one" xl="3" lg="3" md="6" sm="12">
        <b-card
          class="my-custom-class"
          title="NITL"
          img-src="https://live.staticflickr.com/4165/34526468232_ff438c0aaf_z.jpg"
          img-alt="Image"
          img-top
        >
          <b-card-text>
            NITL is like store for sahaja yogi's where one can take anything
            related to sahaj like Mother's photographs, kumkum, books any many
            others.
          </b-card-text>
        </b-card>
      </b-col>
      <b-col class="my_col_one" xl="3" lg="3" md="6" sm="12">
        <b-card
          class="my-custom-class"
          title="Rest Place"
          img-src="https://live.staticflickr.com/4189/34526454682_f765ef8407_z.jpg"
          img-alt="Image"
          img-top
        >
          <b-card-text>
            By the grace of mother big halls are available for sahaja yogi's who
            are comming from any place and all the amenities are present to stay
            at shree mataji shrine.
          </b-card-text>
        </b-card>
      </b-col>
      <b-col class="my_col_one" xl="3" lg="3" md="6" sm="12">
        <b-card
          class="my-custom-class"
          title="Kitchen"
          img-src="~/static/kitchen.jpg"
          img-alt="Image"
          img-top
        >
          <b-card-text>
            Very clean and hygenic kitchen with every utensils, gas is open for
            all sahaja yogi's. Just bring raw materials that you want to prepare
            for Mother.
          </b-card-text>
        </b-card>
      </b-col>
    </b-row>
  </div>
</template>

<style scoped>
.myService {
  background-color: #f7f4e7;
  padding: 2rem;
}
h1 {
  color: #ff9a32;
}
.my-custom-class .card-title {
  color: #ff9a32 !important;
}
.my-custom-class {
  background-color: #f7f4e7;
}
h6 {
  margin-bottom: 2rem;
}
@media only screen and (max-width: 786px) {
  .my_col_one {
    margin-top: 10px;
  }
}
</style>
