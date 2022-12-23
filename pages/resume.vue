<script setup>
useHead({
  title: 'Resume',
})
</script>

<template>
  <article class="resume active" data-page="resume">
    <header>
      <h2 class="h2 article-title">
        {{ $t('pageTitles.resume') }}
      </h2>
    </header>

    <section class="timeline">
      <div class="title-wrapper">
        <div class="icon-box">
          <ion-icon name="book-outline" />
        </div>

        <h3 class="h3">
          Escolaridade
        </h3>
      </div>

      <ol class="timeline-list">
        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">
            Intituto Federal Catarinense (IFC)
          </h4>
          <span>2020 — Present</span>
          <p class="timeline-text">
            Bacharelado em Ciencias da computação
          </p>
        </li>

        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">
            Senac Itaquera
          </h4>
          <span>2018 — 2020</span>
          <p class="timeline-text">
            Análise e Desenvolvimento de Sistemas
          </p>
        </li>
      </ol>
    </section>

    <section class="timeline">
      <div class="title-wrapper">
        <div class="icon-box">
          <ion-icon name="book-outline" />
        </div>

        <h3 class="h3">
          Experiencia
        </h3>
      </div>

      <ol class="timeline-list">
        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">
            Cubus Soluções
          </h4>
          <span>Desenvolvedor Back-End</span>
          <div class="div-inline">
            <div class="icon-box paddingBox">
              <h5 class="h5">
                C#
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                SQL Server
              </h5>
            </div>
          </div>
        </li>

        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">
            Tidas Ltda
          </h4>
          <span>Desenvolvedor Full Stack</span>
          <div class="div-inline">
            <div class="icon-box paddingBox">
              <h5 class="h5">
                Html
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                CSS
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                Javascript
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                Python
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                PHP
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                PostgreSQL
              </h5>
            </div>
          </div>
        </li>

        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">
            Digiliza Ltda
          </h4>
          <span>Desenvolvedor Full Stack</span>
          <div class="div-inline">
            <div class="icon-box paddingBox">
              <h5 class="h5">
                Vue.js
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                Laravel
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                PostgreSQL
              </h5>
            </div>
          </div>
        </li>
        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">
            Magazord LTDA
          </h4>
          <span>Desenvolvedor BackEnd</span>
          <div class="div-inline">
            <div class="icon-box paddingBox">
              <h5 class="h5">
                PHP
              </h5>
            </div>
            <div class="icon-box paddingBox">
              <h5 class="h5">
                PostgreSQL
              </h5>
            </div>
          </div>
        </li>
      </ol>
    </section>

    <section class="skill">
      <h3 class="h3 skills-title">
        My skills
      </h3>

      <ul class="skills-list content-card">
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              Web design
            </h5>
            <data value="80">80%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 80%;" />
          </div>
        </li>

        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              Graphic design
            </h5>
            <data value="70">70%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 70%;" />
          </div>
        </li>

        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              Branding
            </h5>
            <data value="90">90%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 90%;" />
          </div>
        </li>

        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              WordPress
            </h5>
            <data value="50">50%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 50%;" />
          </div>
        </li>
      </ul>
    </section>
  </article>
</template>

<style scoped>
.div-inline {
  display: inline-flex;
  margin-top: 5px;
}
.paddingBox{
  margin-right: 10px;
}
.icon-box{
  min-width: 48px;
  width: auto;
  padding: 10px;
}
</style>
