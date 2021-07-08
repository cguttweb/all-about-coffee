<template>
  <DrinksLayout>
    <main class="container">
      <h1>World Coffees</h1>
      <div class="grid lg:grid-cols-2 gap-2">
      <section>
        <h2>Brazil</h2>
        <p>The largest coffee producer in the world. In 1920 it produced c.80% of all coffee grown in the world and with increased production elsewhere today the current market share of c.35%. There are around 300,000 farms ranging in size around the country from half hectare to 10,000+ hectares. Most of production c.80% is Arabica with nearly half of that produced in plantations that were setup in Minas Gerais. 
        <!-- The coffee produced is processed using the dry process (unwashed coffee) where the coffee cherries are left in the sun rather than washed in a wet process.  -->
        Arabicas produced here are soft washed and sweet naturals with mild acidity and medium texture.</p>
        <p>Harvest period is May to September</p>
      </section>

      <section>
        <h2>Vietnam</h2>
        <p>In the coffee producing stakes the second largest producer in the world and unlike Brazil c.95% of its production is Robusta. Production here began in the mid 19th century and in early 20th century farmers increased their production to take advantage of better market prices. In a decade it became the worlds 2nd largest producer which saw lower quality beans flood the market, but today they aim for a better balance between supply and demand.
        </p>
        <p>Harvest is done between October and April</p>
      </section>

      <section>
        <h2>Colombia</h2>
        <p class="pb-3">Colombian coffee is world famous and is a key player in the global market. However recently climate has had a negative effect on production with both temperature and preciptation increasing it affects the climate for producing beans favoured in Colombia.
        It is the 4th largest producer in the world and has c.6% of the world market. Most of the people working in the industry are from small farms with increased recent interest from the speciality industry. It produces solely Arabica they are rich and full bodied with a range of flavour profiles from nutty, sweet and chocolatey to floral, fruity and tropical.</p>
        <p>Depending on the region there are 1 or 2 harvests a year. The harvest period is March - June and September - December</p>
      </section>

      <section>
        <h2>Ethiopia</h2>
        <p>Ethiopia is often seen the geographic home of Arabica coffee it has c.5% share of the world market and as a result has a rich coffee culture. Unlike other countries it does not have large number of farms instead the coffee often grows wild and is only harvested for a couple of months of the year by subsistence farmers. In addition it has a diversity of species and varieties not found elsewhere with these regional varieties each with their own characteristics and taste including <abbr title="coffee">Limu</abbr>, The Harar among others.
        The flavour profiles are commonly distinct and elegantly floral, herbal and citrus notes.
        </p>
        <p>Harvest period is between October and December</p>
      </section>

      <section>
        <h2>Indonesia</h2>
        <p>Coffee production in Indonesia was introduced by Dutch colonists and continued because the climate is well suited to the plant and its location near the equator and has mountainous regions good for production. This climate favours the production of (lower quality?) Robusta beans.</p>
      </section>

      <section>
        <h2>Honduras</h2>
        <p>Honduras produces Arabiac and hold asround 3% of the world market. It uses the washed method and is capable of growing clean complex coffees, but a lack of production does hinder production at times. It offers a variety of contrasting flavours from soft, low-acidity and toffee-like to more acidic Kenyan style coffees.</p>
        <p>Harvest period: November - April</p>
      </section>

      <section>
        <h2>Jamaica</h2>
        <p>Although not a large producer and not having a big percentage of the world market some of the most expensive coffees are prudced here. The most famous of these are those from the Blue Mountain range in the east of the country. It provides a cool, misty climate which is well suited to gorwing coffee. The variety is expensive and often counterfeit so measures are being put in place to try and protect it. The flavours are sweet, soft and mellow with nutty notes and medium textures.</p>
        <p>Harvest period: September - March</p>
      </section>

      <section>
        <h2>Peru</h2>
        <p>Peru produces Arabica with around 90% of the coffee grown on small farms each of c. 5 acres (2 hectares). It has c.3% of the world market. The coffee produced is high quality but inconsistent. Moat of it is from the north where new Arabica is being planted and it is also organic. The coffee is well-textured and balanced with earthly herbal flavours.</p>
        <p>Harvest period: May - September</p>
      </section>
      </div>
    </main>
  </DrinksLayout>
</template>

<script>

import DrinksLayout from '~/layouts/Drinks.vue'

export default {
  metaInfo: {
    title: "World Coffees",
  },
  components: {
    DrinksLayout
  }
};
</script>

<style scoped>
/* main {
  @apply max-w-6xl;
  @apply mx-auto;
}

h2 {
  @apply text-left;
  @apply font-semibold;
}

section {
  @apply bg-orange-700;
  @apply px-5;
  @apply py-4;
}

section p {
  @apply py-3;
} */

</style>