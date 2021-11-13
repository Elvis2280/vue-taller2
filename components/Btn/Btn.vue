<template>
    <button :class="primary ? 'bg-indigo-700 text-white shadow-xl' : 'text-gray-400'" class=" w-full py-2 px-4 rounded-2xl ">{{text}}</button>
</template>

<script>
export default {
    props: ['text', 'primary']
}
</script>
