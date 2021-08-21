<template>
<div>
  <Navbar/>
  <Hero/>
  <Quote/>
  <Carousal/>
  <Timeings/>
  <Map/>
</div>
</template>

<script>
export default {
  head:{
    title: 'Chhindwada Shree Mataji Birth Shrine',
    meta: [
      {
        hid: 'Shree Mataji Birth Place Chhindwada',
        name: 'description',
        content: 'Shree Mataji Birth Place Chhindwada'
      }
    ]
  }
}
</script>

<style>
:root{
  font-size: 20px;
}
body {
  color: #411E64;
}
@media only screen and (max-width: 1020px) {
  :root{
  font-size: 15px;
}
}
@media only screen and (max-width: 600px) {
  :root{
  font-size: 14px;
}
}
</style>
