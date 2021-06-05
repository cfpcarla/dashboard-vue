<template>
<header class="header">
<div class="header-group">
<div class="flex items-center justify-between py-10">
<div class="w-28 lg:w-36">
<img class="w-full" src="../../assets/images/logo_white.png" alt="logo">
</div>

<div class="flex">
<button class="px-6 py-2 font-bold rounded-full text-white focus:outline-none">
Create an account
</button>
<button class="px-6 py-2 font-bold bg-white rounded-full text-brand-main focus:outline-none">
enter
</button>
</div>
</div>

<div class="flex flex-col mt-28">
<h1 class="text-4xl font-black text-white">
Get feedback. <br>
And make customers <br class="hidden lg:inline-block">
happier!
</h1>
<br>
<p class="text-lg font-medium text-white">
Receive ideas, complaints and feedback with a <br class="hidden lg:inline-block">
simple widget on the page.
</p>
<div>
<button class="px-6 py-2 mt-10 font-bold bg-white rounded-full text-brand-main focus:outline-none">
Create an account for free
</button>
</div>
</div>

</div>
</header>
</template>

<script>
export default {
}
</script>

<style lang="postcss" scoped>
.header {
    @apply bg-brand-main w-full flex justify-center;
    height: 700px;
}
.header-group {
    @apply flex flex-col w-4/5 max-w-6xl;
}
@media (min-width: 640px) {
    .header-group {
        background-image: url(../../assets/images/ballon.png);
        background-size: 628px;
        background-position: 90% 100%;
        background-repeat: no-repeat;
    }
}
</style>
