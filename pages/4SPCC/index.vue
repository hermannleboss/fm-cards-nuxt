<template>
  <div class="spcc flex justify-center items-center">
    <div class="spcc-card-container text-center flex flex-col-reverse rounded-lg lg:flex-row">
      <div class="spcc-card-content lg:text-left">
        <h1> Get <span>insights</span> that help your business grow.</h1>
        <p class="pt-4 lg:pt-6 pr-3">Discover the benefits of data analytics and make better decisions regarding revenue, customer experience, and
          overall efficiency.</p>
        <div class="flex flex-col gap-6 lg:flex-row lg:gap-8">
          <div>
            <div class="counter">10k+</div>
            <div class="counter-heading">COMPANIES</div>
          </div>
          <div>
            <div class="counter">314</div>
            <div class="counter-heading">TEMPLATES</div>
          </div>
          <div>
            <div class="counter">12 M+</div>
            <div class="counter-heading">QUERIES</div>
          </div>
        </div>
      </div>
      <div class="bg-img rounded-lg">
        <div></div>
      </div>
    </div>
    <Attribution/>
  </div>
</template>

<script>
export default {
  name: "StatsPreviewCardComponentMain"
};
</script>
<style lang="scss" src="./index.scss" scoped/>
