<template>
  <div class="ui basic center aligned segment">
    <img class="ui small image centered" src="http://www.starsatnight.org/sites/sciencetheater/themes/MaybornSemanticVue-master/images/logo.png" />
    <h1 class="ui huge header">
      Welcome to our universe!
      <br><br>
      <div class="sub header">
        We'll ask you few questions about your field trip in order to get all the information we 
        need to provide the best experience for you and your group. Thank you for choosing us!
        <i class="smile outline icon"></i>
        <i class="thumbs up icon"></i>
        <i class="heart outline icon"></i>
      </div>
    </h1>
    <div class="ui huge primary button" @click="$router.push({ name : 'attendance' })">
      <i class="thumbs up icon"></i>
      I am ready to start!
    </div>
  </div>
</template>

<style>
  
</style>