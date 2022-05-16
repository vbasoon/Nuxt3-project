<template>
  <header>
    <div
      class="flex items-center justify-center py-7 mx-auto lg:px-desktop sticky top-0"
    >
      <NuxtLink to="/" class="flex items-center mr-auto">
        <h1 class="text-red-600 text-2xl">NuxtLink</h1></NuxtLink
      >
      <ul class="lg:flex hidden items-center space-x-14">
        <li
          v-for="link in links"
          :key="link.id"
          class="group"
          :class="{ 'text-gray-500': activeLink !== link }"
        >
          <NuxtLink
            to="#"
            class="font-medium group-hover:text-black transition-all duration-300"
          >
            {{ link.name }}
          </NuxtLink>
          <div
            :class="{ 'text-gray-500': activeLink == link }"
            class="h-0.5 mt-0.5 group-hover:scale-y-100 group-hover:bg-black group-hover:block w-[80%] transition-all duration-300"
          ></div>
        </li>
      </ul>
    </div>
  </header>
</template>

<script setup>
/* const links = [
  {
    id: 1,
    name: "Home",
    path: "/",
  },
  {
    id: 2,
    name: "About Us",
    path: "/about",
  },
  {
    id: 3,
    name: "Pricing",
    path: "/pricing",
  },
  {
    id: 4,
    name: "Blog",
    path: "/blog",
  },
  {
    id: 5,
    name: "Contact",
    path: "/contact",
  },
]; */
const links = ["Home", "About Us", "Pricing", "Blog", "Contact"];
const activeLink = useState("activeLink", () => "Home");
</script>

<style></style>
