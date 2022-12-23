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
        Skills
      </h3>
      <ul class="skills-list content-card">
        <!-- #region frontend  -->
        <h3 class="h3 skills-title">
          Front-end
        </h3>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              VUE.JS
            </h5>
            <data value="50">50%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 50%;" />
          </div>
        </li>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              HTML
            </h5>
            <data value="100">100%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 100%;" />
          </div>
        </li>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              CSS
            </h5>
            <data value="100">100%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 100%;" />
          </div>
        </li><li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              jAVASCRIPT
            </h5>
            <data value="100">100%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 100%;" />
          </div>
        </li>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              SASS
            </h5>
            <data value="50">50%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 50%;" />
          </div>
        </li><li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              JQUERY
            </h5>
            <data value="50">50%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 50%;" />
          </div>
        </li>
      <!-- #endregion frontend -->
        <!-- #region backend  -->
        <h3 class="h3 skills-title">
          BACK-END
        </h3>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              PHP
            </h5>
            <data value="100">100%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 100%;" />
          </div>
        </li>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              LARAVEL
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
              DJANGI
            </h5>
            <data value="50">50%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 50%;" />
          </div>
        </li><li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              PYTHON
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
              C#
            </h5>
            <data value="80">80%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 80%;" />
          </div>
        </li>
        <!-- #endregion backend -->
        <!-- #region database  -->
        <h3 class="h3 skills-title">
          DATABASE
        </h3>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              MYSQL
            </h5>
            <data value="100">100%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 100%;" />
          </div>
        </li>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              POSTGESQL
            </h5>
            <data value="100">100%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 100%;" />
          </div>
        </li>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              SQLSERVER
            </h5>
            <data value="100">100%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 100%;" />
          </div>
        </li>
        <!-- #endregion database -->
        <!-- #region CSV  -->
      <h3 class="h3 skills-title">
          CSV
        </h3>
        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              GIT HUB
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
              GITLAB
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
              BITBUCKET
            </h5>
            <data value="80">80%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 80%;" />
          </div>
        </li><li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">
              TORTOISE SVN
            </h5>
            <data value="80">80%</data>
          </div>
          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 80%;" />
          </div>
        </li>
      <!-- #endregion CSV -->
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
