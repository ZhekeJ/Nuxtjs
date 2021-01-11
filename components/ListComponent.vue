<template>
  <div>
    <pre>{{header}}</pre>
    <Header/>
     <div class="flex items-center justify-center h-screen overflow-hidden" style="background: #edf2f7;">
    <table class="w-full border-collapse">
    <thead>
        <tr>
            <th v-for="(h,index) in header" :key="index" class="hidden p-3 font-bold text-gray-600 bg-gray-200 border border-gray-300 lg:table-cell">{{h.headertext}}</th>

        </tr>
    </thead>
    <tbody>
        <tr v-for="item in records" :key="item.id" class="flex flex-row flex-wrap mb-10 bg-white lg:hover:bg-gray-100 lg:table-row lg:flex-row lg:flex-no-wrap lg:mb-0">
            <td v-for="hdet in header" :key="hdet.value" class="relative block w-full p-3 text-center text-gray-800 border border-b lg:w-auto lg:table-cell lg:static">
                <span class="absolute top-0 left-0 px-2 py-1 text-xs font-bold bg-blue-200 lg:hidden">Company name</span>
                {{ item[hdet.value]}}
            </td>

        </tr>
    </tbody>
</table>
</div>
  </div>
</template>>

<script>
export default {
  props: ['header','records']

}
</script>

<style>

</style>
