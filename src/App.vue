<template>
  <div>
    <Modal />
    <router-view />
  </div>
</template>

<script>
import Modal from './components/Modal.vue';

export default {
  components: {
    Modal,
  }
}
</script>
