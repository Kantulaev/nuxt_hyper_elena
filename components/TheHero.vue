<template >
  <section class="overflow-hidden bg-gray-50 dark:bg-gray-900 sm:grid sm:grid-cols-2">
    <div class="p-8 md:p-12 lg:px-16 lg:py-24">
      <div class="mx-auto max-w-xl text-center sm:text-left">
        <h2 class="text-3xl font-bold text-gray-900 dark:text-white md:text-5xl">
          Онлайн логопед для всей семьи
        </h2>

        <p class="hidden text-gray-500 dark:text-gray-300 text-xl md:mt-4 md:block">
          Индвидульная подготовка и занятия
        </p>

        <div class="mt-4 md:mt-8">
          <NuxtLink to="/"
            class="inline-block rounded btn-info px-12 py-3 text-xl font-bold text-white transition hover:bg-emerald-700 focus:outline-none focus:ring focus:ring-yellow-400">
            Связаться
          </NuxtLink>
        </div>
      </div>
    </div>

    <img alt="Student"
      src="https://images.unsplash.com/photo-1464582883107-8adf2dca8a9f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1770&q=80"
      class="h-56 w-full object-cover sm:h-full" />
  </section>

</template>