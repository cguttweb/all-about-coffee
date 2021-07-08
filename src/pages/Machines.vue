<template>
    <Layout>
        <main>
            <div class="overflow-y-auto h-700">
            <h1>Coffee Machines</h1>
                <div class="grid lg:grid-cols-3 gap-2">
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="Espresso Machine"
                            class="mx-auto"
                            src="~/images/espresso-machine.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="espresso machine" 
                        description="The machine used in coffee shops producing espresso which is the base for most drinks. It uses pump pressure to force the water through the coffee. When done correctly it produces a small drink - an intense shot balanced between sweet and acidic."
                        />
                        <p class="credit"><span>Photo by <a href="https://unsplash.com/@kronemberger?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Isabela Kronemberger</a> on <a href="/s/photos/espresso-machine?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span></p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="french press"
                            class="mx-auto"
                            src="~/images/espresso-machine.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="french press" 
                        description="The most common and easy to use which gives the coffee a great texture. Water and coffee infused together with a mesh filter which pushes through the brew leaving finer particles."
                        />
                        <p class="credit">Photo credit to be added</p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="aeropress"
                            class="mx-auto"
                            src="~/images/aeropress.jpg"
                            height="200"
                            width="300"
                        />
                        <MachinesCard 
                        name="aeropress" 
                        description="A quick and easy to use brewer which can be used for filter style coffee or something stronger if preferred. The grind, amount of coffee and the pressure can be tweaked to your own preferences."
                        />
                        <p class="credit"><span>Photo by <a href="https://unsplash.com/@relentlessjpg?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">William Moreland</a> on <a href="/s/photos/aeropress-coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span></p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="Moka pot"
                            class="mx-auto"
                            src="~/images/espresso-machine.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="Moka pot" 
                        description="This method brews a strong cup of coffee using steam pressure with a silky texture. The temperature gives it an intense flavour unlike what is commonly believed it does not make espresso"
                        />
                        <p class="credit">Photo credit to be added</p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="Ibrik"
                            class="mx-auto"
                            src="~/images/ibrik.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="Ibrik" 
                        description="This method is popular throughout the Middle East and Eastern Europe. It is a copper pot with long handle and brews a distinctive thick texture. It uses a super fine grind with the water-grind ratio and heat producing a full-flavoured coffee."
                        />
                        <p class="credit">Photo from <a href="https://www.turkishcoffeeworld.com" target="_blank">turkish coffee world</a></p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="phin"
                            class="mx-auto"
                            src="~/images/phin.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="phin" 
                        description="This method is Vietnamese and uses a gravity-based filter insert to compress the coffee. Chinese version has the filter is screwed on allowing more control over the extraction. It is easy to use and can change dose and grind to your personal preferences."
                        />
                        <p class="credit">Photo from amazon</p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="filter pourover"
                            class="mx-auto"
                            src="~/images/filter-pourover.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="filter pourover" 
                        description="This is an easy to use brewing method done through a paper filter means the grounds are easily disposed of and it can be brewed straight into a cup"
                        />
                        <p class="credit">Photo from <a href="https://coffeemakered.com" target="_blank">coffeemakered.com</a></p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="electric filter brew"
                            class="mx-auto"
                            src="~/images/espresso-machine.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="electric filter brew" 
                        description="This produces great coffee using good quality beans and fresh water. It is easy to clean as grounds can be removed easily and composted"
                        />
                        <p class="credit">Photo credit to be added</p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="syphon"
                            class="mx-auto"
                            src="~/images/syphon.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="syphon" 
                        description="This takes time it is a visually interesting method of brewing coffee and they are very popular in Japan."
                        />
                        <p class="credit">Photo from <a href="https://coffeegram.com">coffeegram.com</a></p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="cloth brewer"
                            class="mx-auto"
                            src="~/images/cloth-brewer.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="cloth brewer" 
                        description="It is a traditional way of filtering through ground coffee and is also known as 'sock' or 'nel brewing. It has a richer texture because of the oils that pass through the cloth and is preferred to paper filters as there is no papery flavour"
                        />
                        <p class="credit">Photo from <a href="https://beanground.com" target="_blank">beanground.com</a></p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="cold dripper"
                            class="mx-auto"
                            src="~/images/cold-dripper.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="cold dripper" 
                        description="This uses cold water for brewing low-acidity coffee but can be served hot or cold and it requires more time. It can also be done in a french press by leaving overnight in the fridge and straining through a filter"
                        />
                        <p class="credit">Photo from <a href="https://trendhunter.com" target="_blank">trendhunter.com</a></p>
                    </div>
                    <div class="p-4 flex flex-col justify-center">
                        <g-image
                            alt="cold dripper"
                            class="mx-auto"
                            src="~/images/espresso-machine.jpg"
                            width="300"
                        />
                        <MachinesCard 
                        name="Single serve" 
                        description="Single serve machines have gained huge popularity in recent years with their ease of use with the two more popular being Tassimo and Nespresso. Tassimo uses pods and Nespresso use capsules with many of the better known coffee shops creating their own capsules suitable for use at home in these machines."
                        />
                        <p class="credit">Photo credit to be added</p>
                    </div>
                </div>
            </div>
        </main>
    </Layout>
</template>

<script>
import MachinesCard from '@/components/MachinesCard'

    export default {
        metaInfo: {
            title: 'Coffee Machines'
        },
        components: {
            MachinesCard
        }
    }
</script>

<style scoped>
li {
    list-style-type: disc;
}

.h-700 {
    height: 800px;
}

.credit {
    @apply text-sm;
    @apply font-semibold;
    @apply text-center;
}
</style>