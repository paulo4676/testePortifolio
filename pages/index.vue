<script setup>
import { useI18n } from 'vue-i18n'

useHead({
})

onMounted(() => {
  useLocaleStore()
})

const { locale } = useI18n({ useScope: 'global' })

/* Testimonials */
const { data: testimonials } = await useFetch('/api/testimonials')

const testimonialItem = ref({})
const activeModal = ref(false)
const activeOverlay = ref(false)

function showTestimonial(id) {
  testimonialItem.value = testimonials.value.find(item => item.id === id)
  activeModal.value = true
  activeOverlay.value = true
}

function closeTestimonaial() {
  testimonialItem.value = {}
  activeModal.value = false
  activeOverlay.value = false
}
/* Testimonials */

/* Services */
const { data: services } = await useFetch('/api/services')
</script>

<template>
  <article class="about active" data-page="about">
    <header>
      <h2 class="h2 article-title">
        {{ $t('pageTitles.about') }}
      </h2>
    </header>

    <section class="about-text">
      <div class="row">
        <div class="col-md-6">
          <p>
            👷 Atualmente cursando B.Tech em ciência da computação pela IFC <br>
            🔭 Diploma de Técnico em Informática pelo SENAC <br>
            💼 Estou procurando oportunidades/funções de **Estágio (PPO)**. <br>
            💬 Pergunte-me sobre C#/PostgresSql/Mysql/PHP-Dev <br>
            🤔 Estou procurando ajuda para me destacar em Programação Competitiva <br>
          </p>
        </div>
        <div class="col-md-6">
          <figure class="avatar-box">
            <img src="/images/my-avatar.png" alt="Paulo Henrique" width="90">
          </figure>
        </div>
      </div>
    </section>
    <!-- service -->

    <!--  <section class="service">
      <h3 class="h3 service-title">
      </h3>
      <ul class="service-list">
        <ServiceItem v-for="service in services" :key="service.id" :service="service" />
      </ul>
    </section> -->
    <!-- clients -->
    <!-- <section class="clients">
      <h3 class="h3 clients-title">
        Clients
      </h3>

      <ul class="clients-list has-scrollbar">
        <li class="clients-item">
          <a href="#">
            <img src="images/logo-1-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="images/logo-2-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="images/logo-3-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="images/logo-4-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="images/logo-5-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="images/logo-6-color.png" alt="client logo">
          </a>
        </li>
      </ul>
    </section> -->
  </article>
</template>
