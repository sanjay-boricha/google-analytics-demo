<template>
  <div class="container mx-auto">
    <Header></Header>

    <h1>Home</h1>
    <p class="mt-10">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur
      libero deserunt laborum aspernatur sit debitis voluptates necessitatibus,
      molestias nobis modi! Quidem, veniam. Officiis, officia! Animi, nesciunt,
      excepturi quos alias expedita obcaecati est iste temporibus doloremque
      reiciendis reprehenderit. Excepturi non corrupti obcaecati quibusdam
      officiis facere assumenda fugit adipisci maxime saepe animi vel, nihil
      sapiente voluptatem soluta, rerum nesciunt dignissimos quae modi minus
      eveniet iste. Autem accusantium rerum natus aut dolorum tempore, voluptate
      iste expedita, asperiores sint magnam praesentium laboriosam labore
      tenetur magni. Ex dignissimos consequuntur veniam at quidem blanditiis
      mollitia. Aliquam tenetur saepe eveniet eos. Quidem porro sunt reiciendis
      officiis autem.
    </p>

    <google-analytics />
  </div>
</template>

<script>
import GoogleAnalytics from '~/components/GoogleAnalytics.vue'
export default {
  components: { GoogleAnalytics },
  head() {
    return {
      title: 'Home',
    }
  },
}
</script>
