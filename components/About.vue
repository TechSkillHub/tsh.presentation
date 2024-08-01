<template>
  <v-container fluid class="about py-5">
    <div id="about" class="px-4 portfolio-container">
      <div class="section-title">Quem somos?</div>
      <div class="mb-6 text-center" data-aos="fade-up">
        <img class="me-img" src="@/assets/images/me.jpg" />
      </div>
      <div class="quotes text-center mb-10" data-aos="fade-up">
        <q>
          Se não puder se destacar pelo talento,<br/>
          vença pelo esforço!
        </q>
        <br />
      </div>
      <div class="content" data-aos="fade-up">
        <p>
          A TSH surgiu da união de amigos com uma visão compartilhada: oferecer serviços e produtos personalizados, fundamentados em processos e requisitos bem definidos. Essa abordagem garante soluções rápidas e de alta qualidade, resultado de uma trajetória construída sobre alicerces sólidos.
        </p>
        <p>
          Acreditamos firmemente em uma fórmula simples para o sucesso: reduzir o tempo e maximizar os objetivos resulta em menor custo e maior retorno para nossos clientes.
        </p>
      </div>
      <!-- <div data-aos="fade-up">
        <Technologies />
      </div> -->
    </div>
  </v-container>
</template>

<script>
import Technologies from '@/components/Technologies'

export default {
  components: {
    Technologies
  }
}
</script>

<style lang="scss" scoped>
.about {
  color: white;
  min-height: 100vh;
  // background-color: #212529;
  .content {
    padding: 0 3rem;
    p {
      font-size: 1.2rem;
      line-height: 150%;
    }
  }

  .quotes {
    margin: 2rem auto 0;
    font-size: 2rem;
    max-width: 50rem;
  }

  .me-img {
    height: 12rem;
    width: 12rem;
    border-radius: 50%;
    border: 2px solid rgb(54, 51, 51);
    object-fit: cover;
  }
}
@media screen and (max-width: 767px) {
  .content {
    padding: 0 !important;
  }
}
</style>
