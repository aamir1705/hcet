<template>
  <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
    <table
      class="w-full text-sm text-left rtl:text-right text-gray-500 dark:text-gray-400"
    >
      <thead class="text-xs text-gray-700 uppercase dark:text-gray-400">
        <tr>
          <th
            scope="col"
            class="px-6 py-3 bg-gray-50 dark:bg-gray-800"
            v-for="(title, index) in table_row_names"
            :key="index"
          >
            {{ title }}
          </th>
        </tr>
      </thead>
      <tbody>
        <tr
          class="border-b border-gray-200 dark:border-gray-700"
          v-for="(cols, index) in data_sets"
          :key="index"
        >
          <th class="px-6 py-4" v-for="data in cols">{{ data }}</th>
        </tr>
      </tbody>
    </table>
  </div>
</template>
<script>
export default {
  props: ["table_row_names", "data_sets"],
};
</script>
