<template>

  <div id="cards">
    <OptionCard title="Events" description="Check what goes on in your neighborhood" filename="event"/>
    <OptionCard title="Festivals" description="The right mood at the right time" filename="festival" />
    <OptionCard title="Bars" description="This is my last drink..." filename="bar" />
    <OptionCard title="Clubs" description="Say bye to your money" filename="club" />
    <OptionCard title="Piazza Verdi" description="Gathering odore di birkenstock" filename="verdi" />
    <OptionCard title="Raves" description="Until the popos get us" filename="rave" />
  </div>

</template>

<script>
  import OptionCard from './OptionCard.vue';

  export default {
  name: 'CardContainer',
  // props: {
  //   title: String,
  //   description: Strin
  // }
  components: {
    OptionCard
  }
  }
</script>
