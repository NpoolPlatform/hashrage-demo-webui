<template>
  <Page>
    <template #body>
      <h2>HashRate Demo Platform - General Info</h2>

      <div class='faq-content'>
        <div class='faq-content-nav'>
          <h3>Navigation</h3>

          <ul class='faq-nav-links'>
            <li><a @click='scrollTo("How can I to register a new account with www.epool.tech:20402?")'>How can I to register a new account with www.epool.tech:20402?</a></li>
            <li><a @click='scrollTo("Does HashRate Demo have a mobile app?")'>Does HashRate Demo have a mobile app?</a></li>
            <li><a @click='scrollTo("About HashRate Demo Blog")'>About HashRate Demo Blog</a></li>
          </ul>

          <div class='hr' />
        </div>

        <div class='faq-content-main'>
          <h3 id='How can I to register a new account with www.epool.tech:20402?'>
            How can I to register a new account with www.epool.tech:20402?
          </h3>

          <p>Please receive your account registration link from the person who referred you to HashRate Demo. If your referral does not have a registration link, please contact our Customer Support team for assistance.</p>

          <p>Customer Support: <a href='mailto:support@cryptomore.io'>support@cryptomore.io</a></p>

          <h3 id='Does HashRate Demo have a mobile app?'>
            Does HashRate Demo have a mobile app?
          </h3>

          <p>We plan to launch an official mobile app for our platform in the future, but will first launch on our browser-based website.</p>

          <h3 id='About HashRate Demo Blog'>
            About HashRate Demo Blog
          </h3>

          <ul>
            <li>(1) After logging in, click on the blog button in the header.</li>
            <li>(2) Browse through the blog posts that appear and see what interests you!</li>
          </ul>

          <div class='video-box'>
            <iframe
              width='720' height='405' src='https://www.youtube.com/embed/ZxGKm-B9vU4' title='YouTube video player'
              frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen
            />
          </div>

          <div class='hr' />
        </div>
      </div>
    </template>
  </Page>
</template>

<script setup lang='ts'>
import { defineAsyncComponent } from 'vue'
import { scrollTo } from 'src/utils/scroll'

const Page = defineAsyncComponent(() => import('src/pages/faq/Page.vue'))

</script>
