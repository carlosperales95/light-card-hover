<template>
  <div class="card">
    <div class="card-content">
      <div class="card-image">
        <img :src="require(`@/assets/${filename}.png`)">
      </div>
      <div class="card-info-wrapper">
        <div class="card-info">
          <div class="card-info-title">
            <h3> {{ title }} </h3>  
            <h4> {{ description }} </h4>
          </div>    
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
  name: 'OptionCard',
  props: {
    title: String,
    description: String,
    filename : String
  }
  }
</script>
