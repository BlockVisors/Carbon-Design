<template>
  <div class="bx--grid bx--grid--full-width bx--grid--no-gutter repo-page">
    <div class="bx--row repo-page__r1">
      <div class="bx--col-lg-16">
        <repo-table
        :headers="headers"
        :rows="rows"
        title="Carbon Repositories"
        helperText="A collection of public Carbon repositories."
        />
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'RepoPage',
  components: { RepoTable },
  data() {
    return {
      headers,
      rows,
    };
  },  
}
</script>

<style lang="scss">
@import '../../styles/carbon-utils';
.repo-page .bx--row {
  padding-top: $spacing-05;
  padding-bottom: $spacing-05;
}
</style>