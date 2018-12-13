<template>
  <section class="section" id="services">
    <div class="row">
      <div class="col-lg-offset-8 col-lg-4 start-lg">
        <div class="pl-med">
          <h1>Our Services</h1>
          <DividerLine/>
          <p class="text-col-std">
            we offer three levels of intereactivity to fit
            your particular needs. all personas are based
            on a monthly subscription, cancel anytime.
          </p>
        </div>
      </div>
    </div>

    <div class="row py-med middle-lg">
      <div class="col-lg-6 middle-lg">
        <PackageDisplay
          title="whispers"
          v-bind:price="10.99"
          description="
       from your loved one’s social media, 
       we’ll create an active social profile
       that makes posts and responds to comments."
        />
      </div>

      <div class="col-lg-6 start-lg">
        <img class="package-image" src="../assets/whispers-package.svg">
      </div>
    </div>

    <div class="row py-med middle-lg">
      <div class="col-lg-6">
        <img class="package-image" src="../assets/semblance-package.svg">
      </div>

      <div class="col-lg-6 start-lg">
        <PackageDisplay
          title="semblance"
          v-bind:price="15.99"
          description="
        in additon to social media, 
        we’ll create an active SMS 
        service that will allow you
        to text your loved one."
        />
      </div>
    </div>

    <div class="row py-med middle-lg">
      <div class="col-lg-6">
        <PackageDisplay
          title="resurrection"
          v-bind:price="20.99"
          description="
        on top of social and SMS,
        this package includes the ability
        to make calls, using advanced vocal
        reconstruction."
        />
      </div>

      <div class="col-lg-6 start-lg">
        <img class="package-image" src="../assets/resurrection-package.svg">
      </div>
    </div>
  </section>
</template>

<script>
import DividerLine from "./DividerLine.vue";
import PackageDisplay from "./PackageDisplay";

export default {
  name: "ServiceSection",
  components: {
    DividerLine,
    PackageDisplay
  }
};
</script>