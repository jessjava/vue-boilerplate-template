<template>
  <div>
    hello
  </div>
</template>

<script>
  export default{
    data () {
      return {
        isLoading: false,
        account: {
          username: '',
          password: ''
        },
        rules: {
          username: [
            {
              required: true,
              message: this.$t('pleaseEnter') + this.$t('username'),
              trigger: 'change,blur'
            }
          ],
          password: [
            {
              required: true,
              message: this.$t('pleaseEnter') + this.$t('password'),
              trigger: 'change,blur'
            }
          ]
        }
      }
    },

    mounted () {
    },

    components: {
    },

    computed: {
    },

    methods: {
    }
  }
</script>

<style lang="less">
</style>
