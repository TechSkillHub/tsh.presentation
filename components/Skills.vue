<template>
  <v-container id="skills" fluid class="skills">
    <div class="portfolio-container py-5">
      <div class="section-title">Nossos Serviços</div>
      <v-row no-gutters class="px-5">
        <v-col class="text-center px-4 mx-auto" cols="12">
          <img
            alt="frontend"
            class="skill-img"
            src="@/assets/images/web.gif"
            data-aos="fade-up"
          />
          <div class="skill-title" data-aos="fade-up">Sites Profissionais</div>
          <div class="skill-description" data-aos="fade-up">
            Nossa empresa oferece serviços de desenvolvimento de sites sob medida, com designs exclusivos e personalizados. Aplicamos as melhores práticas de SEO para garantir que seu site tenha visibilidade e atraia mais visitantes. Transforme sua presença online com soluções criativas e eficazes.
          </div>
        </v-col>
        <v-col class="text-center px-4 mx-auto" cols="12">
          <img
            alt="backend"
            class="skill-img"
            src="@/assets/images/design.gif"
            data-aos="fade-up"
          />
          <div class="skill-title" data-aos="fade-up">Identidade Visual</div>
          <div class="skill-description" data-aos="fade-up">
            Criamos identidades visuais únicas e impactantes, projetadas especificamente para ressoar com seu público-alvo. Nosso processo inclui análise aprofundada do mercado e das necessidades dos consumidores para garantir que sua marca se comunique de forma eficaz e atraente. Através de elementos visuais personalizados, garantimos que sua empresa se destaque e conquiste o reconhecimento desejado.
          </div>
        </v-col>
        <v-col class="text-center px-4 mx-auto" cols="12">
          <img
            alt="mobileapp"
            class="skill-img"
            src="@/assets/images/social.gif"
            data-aos="fade-up"
          />
          <div class="skill-title" data-aos="fade-up">Redes Sociais</div>
          <div class="skill-description" data-aos="fade-up">
            Na nossa empresa, oferecemos serviços de otimização de perfis no Instagram e desenvolvemos estratégias de postagem personalizadas. Maximize seu engajamento e alcance com soluções que destacam sua marca e atraem seu público-alvo.
          </div>
        </v-col>
        <v-col class="text-center px-4 mx-auto" cols="12">
          <img
            alt="mobileapp"
            class="skill-img"
            src="@/assets/images/ads.gif"
            data-aos="fade-up"
          />
          <div class="skill-title" data-aos="fade-up">Tráfego Pago</div>
          <div class="skill-description" data-aos="fade-up">
            Nossa empresa especializa-se em campanhas de Google Ads e Facebook Ads, criando estratégias personalizadas para maximizar sua visibilidade online. Alcançamos seu público-alvo com precisão e otimizamos seus resultados, garantindo o melhor retorno sobre seu investimento.
          </div>
        </v-col>
      </v-row>
    </div>
  </v-container>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.skills {
  color: white;
  // margin-top: 3rem;
  background-color: #212529;
  .skill-title {
    font-size: 1.4375rem;
    font-weight: bold;
    margin: 1rem 0;
  }
  .skill-description {
    margin-bottom: 3.5rem;
    font-size: 1rem;
    line-height: 1.5rem;
    color: #f5f5f7;
  }
  .skill-img {
    height: 25rem;
  }
}
</style>
