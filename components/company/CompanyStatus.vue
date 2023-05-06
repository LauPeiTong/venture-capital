<template lang="pug">
  v-row.justify-center.mx-auto
    v-card.pa-4.rounded-lg.fill-width.fill-height
      .company.fill-width.py-4
        p.subtitle-2.px-4.pt-2.mb-0 Prediction
        p.text-h3.px-4.mb-2.pt-0.green--text Investable
          |
          span.text-h6.font-weight-regular.secondary--text.ml-2 (85.6%)
        a.subtitle-1.px-4.mb-0.font-weight-regular.text-decoration-underline View Details

</template>

<script>
export default {
  name: 'CompanyStatus',
  data () {
    return {
    }
  },
  methods: {
    getColor (category) {
      const result = this.colors.find((c) => { return c.name === category })
      if (result) {
        return result.color
      } else {
        return this.$vuetify.theme.themes.primary
      }
    },
    onRowClick (item) {
      this.$router.push('/company')
    }
  }
}
</script>

<style lang="scss" scoped>
.width-95 {
  width: 95% !important;
}

.fill-height {
  height: 100% !important;
}
</style>
