<template>
  <div class="container">
    <div class="media mt-4">
      <div class="media-body m-2">
        <h5 class="align-items-center mt-2">Polly </h5>
        <p>Hallo! Ich bin Polly. Wenn du mich gefunden hast wäre es nett wenn du meine Besitzer kontaktierst. <br> So kannst du meine Herchen anrufen:</p>
      </div>
    </div>
    <div class="mt-4">
      <Link text="Ruf mein Haus an." icon="bi-telephone" href="tel:0511884343"/>
      <Link text="Ruf mein Frauchen an" icon="bi-phone" href="tel:+49 151 17454510"/>
      <Link text="Ruf mein Herchen an" icon="bi-phone" href="tel:+49 173 2131867"/>
      <hr/>
      <p> Oder per Email: </p>
      <Link text="Email von Frauchen" icon="bi-envelope" href="mailto:u.bernard@gmx.de" class="mt-2"/>
      <Link text="Email von Herchen" icon="bi-envelope" href="mailto:klaus.bernard@gmx.de"/>
    </div>

    <img src="require('./assets/polly.jpg')" alt="Das ist Polly!">
  </div>
</template>

<script>
import Link from '@/components/Link.vue';

export default {
  name: 'Home',
  components: {
    Link,
  },
};
</script>
