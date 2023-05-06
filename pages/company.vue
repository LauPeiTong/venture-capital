<template lang="pug">
.dashboard-page.pa-0.ma-0.fill-width
  upper-title.ma-0(:title="'Company'" :titleClass="'dark-background'" :icon="'bell'" :rightIconColor="$vuetify.theme.themes.light.success")
  v-row.ma-0.pt-8.fill-width
    v-col(cols="8")
      company-details-vue.pt-12.align-center.pl-4.pb-4
      company-overview-vue.pb-8.align-center.pl-4
    v-col(cols="4")
      company-status-vue.pt-12.align-center.pr-4.pb-4
      company-news-vue.pb-8.align-center.pr-4
</template>

<script>
import { mapGetters } from 'vuex'
import CompanyStatusVue from '~/components/company/CompanyStatus.vue'
import CompanyDetailsVue from '~/components/company/CompanyDetails.vue'
import UpperTitleVue from '~/components/UpperTitle.vue'
import CompanyOverviewVue from '~/components/company/CompanyOverview.vue'
import CompanyNewsVue from '~/components/company/CompanyNews.vue'

export default {
  name: 'CompanyPage',
  components: {
    CompanyStatusVue,
    CompanyDetailsVue,
    CompanyOverviewVue,
    CompanyNewsVue,
    UpperTitleVue
  },
  layout: 'default',
  data () {
    return {
      // search: null
    }
  },
  computed: {
    ...mapGetters({
    })
  },
  methods: {
  }
}
</script>

<style lang="scss" scoped>
.fill-height {
  height: 100% !important;
}
</style>
