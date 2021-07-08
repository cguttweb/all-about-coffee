<template>
    <Layout>
      <main class="container">
        <h1>Coffee Beans and grinding</h1>
          <section class="beans border border-gray-800">      
            <div class="py-2">
              <h2 class="">Beans</h2>
              <ul class="list-inside pb-4">
                <li>
                  <strong>Arabica</strong> - c.60% of world coffee production caffeine levels vary
                  c.0.8-1.6%
                </li>
                <li>
                  <strong>Robusta</strong> - c.40% of world production higher caffeine levels
                  between c.1.7-4%
                </li>
              </ul>
            <!-- <p class="imageref text-sm"><span>Photo by <a href="https://unsplash.com/@asthetik?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Mike Kenneally</a> on <a href="/s/photos/coffee-beans?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span></p> -->
          </div>
          </section>
          <section class="grinds border border-gray-800">
            <div class="py-2">
              <h2 class="">Types of grind:</h2>
              <p>The grind is important depending on which type of coffee you wish to make. </p>
              <ul class="list-inside">
                <li>
                  <strong>Super fine</strong> - suitable for Turkish coffee using an Ibrik
                </li>
                <li><strong>Fine</strong> - suitable for espresso machines and moka pots</li>
                <li><strong>Medium coarse</strong> - suitable for many brewing options including pour over filter and cloth brewer</li>
                <li><strong>Coarse</strong> - suitable for the French press/cafetiere</li>
              </ul>
              <!-- <p class="text-sm"><span>Photo by <a href="https://unsplash.com/@krewellah87?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Andrea Tummons</a> on <a href="/s/photos/coffee-grounds?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span></p> -->
            </div>
          </section>
          <section class="border border-gray-800">
            <div>
              <h2>Blends vs Single Origin</h2>
              <p><strong>Blends</strong> are a mix of different beans creating a particular flavour profile. They are popular because the flavour profiles remain consistent throughout the year. The best quality beans are usually described in detail including the variety, flavour and region. </p>
              <p><strong>Single Origin</strong> usually means a coffee from a single country, however when dealing with speciality coffee this can be more specific:</p>
              <ul>
                <li>a single farm,</li>
                <li>a single producer,</li>
                <li>a group of producers</li>
              </ul>
              <p>Often they are limited or seasonal options so will only be sold until the supply lasts.</p>
            </div>
          </section>
        </main>
    </Layout>
</template>

<script>
    export default {
        metaInfo: {
          title: 'Coffee Beans and Grinds'
        }
    }
</script>

<style scoped>
main {
  /* background-color: rgba(226, 94, 6, 0.5); */
  /* min-height: 95vh; */
  @apply max-w-6xl;
  @apply mx-auto;
  /* background-image: url(../images/coffee-beans.jpg); */
  /* background-position: left; */
  /* background-size: cover;  */
  /* background-image: url(../images/ground-coffee.jpg); */
}

section {
  @apply mb-4;
}

h2 {
  @apply font-bold text-left;
}




</style>