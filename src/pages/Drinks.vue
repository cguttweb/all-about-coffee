<template>
    <DrinksLayout>
        <main>
            <div class="text-center">
                <h1>Coffee Drinks</h1>
                <form action="#">
                <!-- <label class="block" for="name">Enter your name:</label>
                <input type="text" name="name" id="name" v-model="name">
                <p>Welcome {{ name }}!</p> -->
                <div class="py-4">
                <label class="block" for="getcoffees">Get coffees by type:</label>
                    <select name="getcoffees" id="getcoffees" v-model="getcoffees">
                        <option value="hot">hot</option>
                        <option value="cold">cold</option>
                        <option value="alcoholic">alcoholic</option>
                    </select>
                        <p class="py-4" v-if="getcoffees">You selected {{ getcoffees }}. Here are your options:</p>
                        <div v-if="getcoffees === 'cold'">
                        </div>
                </div>
                <button class="bg-green-700 p-2" @click="getCoffeeTypes">Get Coffees</button>
                    <!-- <label class="block" for="searchcoffees">Search for coffees</label>
                    <input type="search" name="searchcoffees" id="searchcoffees" v-model="searchcoffees">
                    <p>You searched for {{ searchcoffees }}</p> -->
                </form>
            <!-- <div class="lg:grid grid-cols-3">
                <DrinksCard
                v-for="coffee in filteredCoffees"
                :key="coffee.name"
                :coffee="coffee"
                ></DrinksCard>
            </div> -->
            <!-- options for different categories hot, cold, includes alcohol and search bar -->
            </div>
        </main>
    </DrinksLayout>
</template>

<script>
import DrinksLayout from '~/layouts/Drinks.vue'
import DrinksCard from '~/components/DrinksCard'
import coffees from '~/coffees'

    export default {
        metaInfo: {
            title: 'Coffee Drinks'
        },
        data() {
            return {
                name: '',
                coffees: null,
                getcoffees: '',
                searchcoffees: ''
            }
        },
        components: {
            DrinksCard,
            DrinksLayout
        },
        methods: {
            getCoffeeTypes(e){
               e.preventDefault()
                // console.log(coffees.slice(0, -1))
                for (let i = 0; i < coffees.length; i++) {
                    const types = coffees[i].type;
                    console.log(coffees[i].name, types)
                }
            },
        },
        computed: {
            // filteredCoffees(){
                // let searchForCoffee = this.searchcoffees.toLowerCase()
                // coffees.filter(coffee => {
                    // return coffees.name.toLowerCase().includes(searchcoffees)
                // })
            // }
        }
    }
</script>

<style scoped>

</style>