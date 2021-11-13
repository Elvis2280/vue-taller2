<template>
    <article class="mt-auto mb-auto self-center border border-blue-800 rounded-xl bg-white z-10 py-4 px-8 layoutCard">
        <figure class="flex justify-center">
            <img src="../../static/musicImage.svg" class="w-40 h-auto">
        </figure>

        <h2 class="text-center text-3xl font-bold text-gray-900">Order Summary</h2>
        <p class="text-center pt-4 pb-8 text-gray-500">You can now listen to millons of songs, audiobooks, and podcasts on any device anywhere you like!</p>
        <MusicPlanCard />

        <div class="flex flex-col gap-y-4 mt-6">
        <Btn text="Proceed to Payment" v-bind:primary="true" />
        <Btn text="Cancel Order" v-bind:primary="false" />
        </div>


    </article>
</template>

<style>
   .layoutCard{
        display: grid;
        grid-template-columns: minmax(min-content, 320px);
    }
</style>