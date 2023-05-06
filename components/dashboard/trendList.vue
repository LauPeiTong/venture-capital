<template lang="pug">
  v-row.justify-center.mx-auto
    v-col(:cols="4")
      v-card.rounded-lg
        v-card-title
          p.mb-0.text-h6.primary--text Top Investable Company
        v-card-text
          v-card.px-4.py-2.mb-2(outlined)
            .d-flex.flex-no-wrap.justify-space-between
              .company
                .d-flex.flex-wrap.align-center
                  p.mb-1.text-h6.pr-2 Justy
                  v-chip.chip-small.mb-1(
                    color="#f95d6a"
                    outlined
                    pill
                  )
                    p.mb-0.caption Mobile
                p.mb-0 Revenue: RM 300,000.00
                p.mb-0.green--text +50.2%

              v-avatar(
                class="ma-1"
                size="50"
                tile
              )
                v-img(:src="require(`../../assets/company/1.png`)")

          v-card.px-4.py-2.mb-2(outlined)
              .d-flex.flex-no-wrap.justify-space-between
                .company
                  .d-flex.flex-wrap.align-center
                    p.mb-1.text-h6.pr-2 UDY
                    v-chip.chip-small.mb-1(
                      color="#2f4b7c"
                      outlined
                      pill
                    )
                      p.mb-0.caption Information Technology
                  p.mb-0 Revenue: RM 20,000.00
                  p.mb-0.green--text +80.1%

                v-avatar(
                  class="ma-1"
                  size="50"
                  tile
                )
                  v-img(:src="require(`../../assets/company/2.png`)")

          v-card.px-4.py-2(outlined)
              .d-flex.flex-no-wrap.justify-space-between
                .company
                  .d-flex.flex-wrap.align-center
                    p.mb-1.text-h6.pr-2 BerjayaGo
                    v-chip.chip-small.mb-1(
                      color="#a05195"
                      outlined
                      pill
                    )
                      p.mb-0.caption Artificial Intelligence
                  p.mb-0 Revenue: RM 10,000.00
                  p.mb-0.green--text +33.2%

                v-avatar(
                  class="ma-1"
                  size="50"
                  tile
                )
                  v-img(:src="require(`../../assets/company/3.png`)")

    v-col(:cols="4")
      v-card.rounded-lg
        v-card-title
          p.mb-0.text-h6.primary--text Top Investable Category
        v-card-text
          v-card.px-4.py-2.mb-2(outlined)
            .d-flex.flex-no-wrap.justify-space-between
              .company
                .d-flex.flex-wrap.align-center
                  p.mb-1.text-h6.pr-2 Soso
                  v-chip.chip-small.mb-1(
                    color="#f95d6a"
                    outlined
                    pill
                  )
                    p.mb-0.caption Mobile
                p.mb-0 Revenue: RM 300,000.00
                p.mb-0.green--text +50.2%

              v-avatar(
                class="ma-1"
                size="50"
                tile
              )
                v-img(:src="require(`../../assets/company/4.png`)")

          v-card.px-4.py-2.mb-2(outlined)
              .d-flex.flex-no-wrap.justify-space-between
                .company
                  .d-flex.flex-wrap.align-center
                    p.mb-1.text-h6.pr-2 Jaga
                    v-chip.chip-small.mb-1(
                      color="#2f4b7c"
                      outlined
                      pill
                    )
                      p.mb-0.caption Information Technology
                  p.mb-0 Revenue: RM 20,000.00
                  p.mb-0.green--text +80.1%

                v-avatar(
                  class="ma-1"
                  size="50"
                  tile
                )
                  v-img(:src="require(`../../assets/company/5.png`)")

          v-card.px-4.py-2(outlined)
              .d-flex.flex-no-wrap.justify-space-between
                .company
                  .d-flex.flex-wrap.align-center
                    p.mb-1.text-h6.pr-2 Liver
                    v-chip.chip-small.mb-1(
                      color="#a05195"
                      outlined
                      pill
                    )
                      p.mb-0.caption Artificial Intelligence
                  p.mb-0 Revenue: RM 10,000.00
                  p.mb-0.green--text +33.2%

                v-avatar(
                  class="ma-1"
                  size="50"
                  tile
                )
                  v-img(:src="require(`../../assets/company/6.png`)")

    v-col(:cols="4")
      v-card.rounded-lg
        v-card-title
          p.mb-0.text-h6.primary--text Latest Investable Company
        v-card-text
          v-card.px-4.py-2.mb-2(outlined)
            .d-flex.flex-no-wrap.justify-space-between
              .company
                .d-flex.flex-wrap.align-center
                  p.mb-1.text-h6.pr-2 Nanty
                  v-chip.chip-small.mb-1(
                    color="#f95d6a"
                    outlined
                    pill
                  )
                    p.mb-0.caption Mobile
                p.mb-0 Revenue: RM 300,000.00
                p.mb-0.green--text +50.2%

              v-avatar(
                class="ma-1"
                size="50"
                tile
              )
                v-img(:src="require(`../../assets/company/7.png`)")

          v-card.px-4.py-2.mb-2(outlined)
              .d-flex.flex-no-wrap.justify-space-between
                .company
                  .d-flex.flex-wrap.align-center
                    p.mb-1.text-h6.pr-2 JHG
                    v-chip.chip-small.mb-1(
                      color="#2f4b7c"
                      outlined
                      pill
                    )
                      p.mb-0.caption Information Technology
                  p.mb-0 Revenue: RM 20,000.00
                  p.mb-0.green--text +80.1%

                v-avatar(
                  class="ma-1"
                  size="50"
                  tile
                )
                  v-img(:src="require(`../../assets/company/8.png`)")

          v-card.px-4.py-2(outlined)
              .d-flex.flex-no-wrap.justify-space-between
                .company
                  .d-flex.flex-wrap.align-center
                    p.mb-1.text-h6.pr-2 Reacty
                    v-chip.chip-small.mb-1(
                      color="#a05195"
                      outlined
                      pill
                    )
                      p.mb-0.caption Artificial Intelligence
                  p.mb-0 Revenue: RM 10,000.00
                  p.mb-0.green--text +33.2%

                v-avatar(
                  class="ma-1"
                  size="50"
                  tile
                )
                  v-img(:src="require(`../../assets/company/9.png`)")

</template>

<script>
export default {
  name: 'TrendList',
  data () {
    return {
    }
  },
  computed: {

  },
  methods: {
  }
}
</script>

<style lang="scss" scoped>
.width-95 {
  width: 95% !important;
}

.chip-small {
  height: 22px;
}
</style>
