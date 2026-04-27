<template>
  <footer class="bg-gray-50 dark:bg-neutral-900">
    <div
      class="mx-auto flex flex-col max-w-7xl lg:flex-row items-center justify-between"
    >
      <section class="lg:w-2/3 p-6 lg:px-8">
        <span class="text-neutral-500 dark:text-gray-300"
          >© {{ currentYear }} Jackson Dhanyel Santin. {{ $t("text27") }}.</span
        >
      </section>
      <section id="contato" class="lg:w-2/2 grid">
        <div class="flex items-end justify-between">
          <NuxtLink
            to="[removido]"
            target="_blank"
            class="-m-1.5 p-1.5"
          >
            <Icon name="uil:facebook" color="gray" size="25" class="mr-2" />
          </NuxtLink>
          <NuxtLink
            to="[removido]"
            target="_blank"
            class="-m-1.5 p-1.5"
          >
            <Icon name="uil:instagram" color="gray" size="25" class="mr-2" />
          </NuxtLink>
          <NuxtLink
            to="[removido]"
            target="_blank"
            class="-m-1.5 p-1.5"
          >
            <Icon name="uil:twitter" color="gray" size="25" class="mr-2" />
          </NuxtLink>
          <NuxtLink
            to="[removido]"
            target="_blank"
            class="-m-1.5 p-1.5"
          >
            <Icon name="uil:linkedin" color="gray" size="25" class="mr-2" />
          </NuxtLink>
          <NuxtLink
            to="https://api.whatsapp.com/send?phone=54996262629"
            target="_blank"
            class="-m-1.5 p-1.5"
          >
            <Icon name="uil:whatsapp" color="gray" size="25" class="mr-2" />
          </NuxtLink>
          <NuxtLink
            to="https://github.com/JacksonSantin"
            target="_blank"
            class="-m-1.5 p-1.5"
          >
            <Icon name="uil:github" color="gray" size="25" class="mr-2" />
          </NuxtLink>
        </div>
      </section>
    </div>
  </footer>
</template>

<script setup>
import moment from "moment";
const currentYear = moment().year();
</script>
