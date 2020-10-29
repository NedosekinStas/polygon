<template lang="pug">
  v-container
    p {{paragraph}}
    v-btn(color="success" @click="paragraph = 'new Lorem Ipsum'") Нажать
</template>

<script>
export default {
  data: () => ({
    paragraph: 'Lorem ipsum'
  }),
  head () {
    return { title: 'Title' }
  }
}
</script>
