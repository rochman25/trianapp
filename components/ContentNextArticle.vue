<template>
     <div class="pt-2 pb-2">
            <h2
              class="
                text-xs
                tracking-wide
                text-gray-500
                uppercase
                dark:text-gray-400
              "
            >
              Next Article
            </h2>
               <nuxt-link :to="link"
               class=" text-green-500
                hover:text-green-600
                dark:hover:text-green-400"
                >{{desc}}</nuxt-link
              >
    </div>
</template>
<script>
export default {
  props:['link','desc']
}
</script>