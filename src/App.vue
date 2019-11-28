<template>
  <div class="app-container">
 <transition
        name="fade"
        mode="out-in"
      >    <router-view/>
        </transition>
  </div>
</template>

<script>
export default {
  name: `App`,
};
</script>

<style>
.fade-enter-active,
.fade-leave-active {
  transition-duration: .8s;
  transition-property: opacity;
  transition-timing-function: ease-in-out;
}

.fade-enter,
.fade-leave-active {
  opacity: .8
}
</style>