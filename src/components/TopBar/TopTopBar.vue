<script>
import ArrowDownIcon from "../Icons/ArrowDownIcon.vue";
export default {
  components: { ArrowDownIcon },
  setup() {
    //
  },
};
</script>

<template>
  <div class="bg-gray-50 border px-10 md:px-24 lg:px-c165">
    <div class="md:flex justify-between text-sm py-3">
      <div>demo@godwinolokor.com</div>
      <div class="space-x-6 flex text-gray-800">
        <div class="flex cursor-pointer hover:text-blue-600">
          <div>My Account</div>
          <div class="pl-2">
            <arrow-down-icon :width="'w-2'"></arrow-down-icon>
          </div>
        </div>
        <div class="text-gray-400">|</div>
        <div class="flex cursor-pointer hover:text-blue-600">
          <div>USD $</div>
          <div class="pl-2">
            <arrow-down-icon :width="'w-2'"></arrow-down-icon>
          </div>
        </div>
        <div class="text-gray-400">|</div>
        <div class="flex cursor-pointer hover:text-blue-600">
          <div>English</div>
          <div class="pl-2">
            <arrow-down-icon :width="'w-2'"></arrow-down-icon>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
