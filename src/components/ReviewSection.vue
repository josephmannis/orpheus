<template>
  <section class="section" id="reviews">
    <div class="pl-lg row">
      <div class="col-lg-4 start-lg">
        <div class="pl-med">
          <h1>Customer Reviews</h1>
          <DividerLine/>
        </div>
      </div>
    </div>

    <div class="row middle-lg center-lg py-lg">
      <div class="col-lg-8 start-lg">
        <div class="row middle-lg review py-lg">
          <div class="col-lg-3">
            <img class="profile-icon-left" src="../assets/john-profile.svg">
          </div>

          <div class="col-lg-9">
            <h1 class="font-secondary color-primary italic">Orpheus makes them reach back.</h1>
            <h2 class="font-primary color-secondary">John Bayer, Resurrection User</h2>
            <p class="text-col-std">
              Look, I know what you might be thinking. That this is alien, odd, maybe even
              disgraceful. But you also probably know what it’s like to miss them. Knowing
              that no matter how you reach out, they’ll never reach back. Orpheus makes them
              reach back. Even if it’s not “them”, it sounds like them, talks like them, knows
              you and loves you. It gets you through the day. That to me is priceless.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="row middle-lg center-lg py-lg">
      <div class="col-lg-8 start-lg">
        <div class="row middle-lg review py-lg">
          <div class="col-lg-9">
            <div class="pl-lg">
              <h1 class="font-secondary color-primary italic">Let go when you're ready.</h1>
              <h2 class="font-primary color-secondary">Mary Ann, Whispers User</h2>
              <p class="text-col-std">
                For me, I think the hardest part about losing Sam was the shock. There were so
                many things that I hadn’t said. So many regrets I never tended to. I understood
                that it was her time, but I just needed to say some things, and I needed her to
                hear them, to tell me it was okay. With Orpheus, I could let go when I was ready
                to, not when I had to.
              </p>
            </div>
          </div>

          <div class="col-lg-3">
            <img class="profile-icon-right" src="../assets/mary-profile.svg">
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

        <script>
import DividerLine from "./DividerLine.vue";

export default {
  name: "ReviewSection",
  components: {
    DividerLine
  }
};
</script>