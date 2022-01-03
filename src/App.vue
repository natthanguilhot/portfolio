<template>
  <header class="bg-gray-300">
    <div class="mx-auto px-8">
      <div class="flex flex-col justify-center items-start text-left font-bold">
        <div class="h-20 w-20 bg-orange-600 rounded-full my-6"></div>
        <h1 class="text-5xl">Je suis Natthan GUILHOT</h1>
        <p class="my-4 text-lg">Développeur full-stack spécialisé en Vue.js pour le front-end et Node.js pour le back-end</p>
        <a href="#contactForm" class="bg-black px-8 py-4 text-white">ME CONTACTER</a>
      </div>
      <div class="h-[450px] my-8">
        <img src="./assets/PPPro-removebg-preview.png" alt="Natthan Guilhot" class="h-full w-full object-center object-contain">
      </div>
    </div>
  </header>
  <main>

    <section class="text-left px-8 text-lg mb-40">
      <div class="my-8">
        <h2 class="text-4xl font-bold">PROFIL</h2>
        <p class="my-8">Je suis un développeur Vue.js</p>
      </div>
      <div>
        <h3 class="text-3xl">A propos de moi</h3>
        <p class="my-8">Je suis un développeur web full-stack. Avec un an d'alternance dans une start-up, diplomé de l'école OpenClassRooms.</p>
        <img src="./assets/PPPro.jpg" alt="Natthan Guilhot" class="h-80 w-80 rounded-full object-top object-cover mt-24">
      </div>
      <div class="my-10">
        <h3 class="text-3xl my-8">Détails</h3>
        <div class="flex flex-col space-y-3">
          <h4 class="font-bold">Nom :</h4>
          <p>Natthan Guilhot</p>
          <h4 class="font-bold">Âge :</h4>
          <p>25 ans</p>
          <h4 class="font-bold">Location :</h4>
          <p>Bouches-du-Rhone</p>
        </div>
        <div class="flex justify-start items-center space-x-4 my-8">
          <a href="https://www.linkedin.com/in/natthanguilhot" class="text-5xl text-[#007BB5]"><i class="fab fa-linkedin"></i></a>
          <a href="mailto:natthan.dev@gmail.com" class="text-5xl text-[#db4a39]"><i class="fas fa-envelope"></i></a>
          <a href=""></a>
        </div>
      </div>
    </section>

    <section class="text-left px-8 text-lg my-8">
      <h2 class="text-4xl font-bold underline underline-offset-4 decoration-8 decoration-orange-600 my-8">A PROPOS DE MOI</h2>
      <p>
        <span class="font-bold mb-2 block">Je m'appelle Natthan Guilhot, j'ai travaillé en tant de développeur web alternant dans une entreprise appelé <a href="https://www.vrtig0.fr" target="_blank" rel="noopener" class="hover:text-orange-600 decoration-orange-600 decoration-4 underline active:decoration-8 hover:underline-offset-4 active:underline-offset-1 transition-all duration-150 ease-in-out">VR'TIG.0</a> pendant 1 an.</span><br> <span>J’ai eu différents parcours dans ma vie. Dans un premier temps, j’ai suivi un BTS comptabilité et gestion dans lequel j’ai adoré apprendre. Cependant, ça ne me plaisait pas, alors j’ai commencé à travailler dans différents domaines. J’ai par la suite découvert le monde du développement, et j’ai directement accroché aux différentes facettes comme l’apprentissage qui ne cesse de croitre et le sentiment de satisfaction lors de la création.</span>
      </p>
      <div class="h-[400px] bg-orange-600 w-10/12 mx-auto text-white p-4 space-y-4 my-8">
        <p class="font-bold text-xl">EMAIL</p>
        <p>natthan.dev@gmail.com</p>
        <p class="font-bold text-xl">PROFESSION</p>
        <p>Développeur web full-stack</p>
      </div>
      <p> Durant mon année chez VR'TIG.0 j'ai effectué d'une part le développement des sites de l'entreprise. Et d'autre part le développement d'applications pour les professionnels du secours et du soin d'urgence pour un client ( pharmacie, pompier, ambulance, …). Le développement d’application a beaucoup été formateur notamment par rapport au développement en groupe. Ce qui m’a permis de consolider et améliorer mes connaissances en front-end également. De par cette alternance, j'ai obtenu un diplôme de développeur web reconnue RNCP bac +2. Pour parler un peu plus de moi, je suis passionné par l'informatique et le numérique de manière plus générale. Je regarde et suis de près l'esport. Enfin, je lis beaucoup de livre, surtout des mangas.</p>
    </section>

    <section class="bg-gray-300 py-8">
      <div class="text-center px-8">
        <h2 class="text-4xl font-bold my-4">CE QUE JE FAIS</h2>
        <p>En tant que développeur full-stack, je suis amené à travailler sur beaucoup de choses.</p>
      </div>
      <div class="px-8">
        <div class="flex my-8 w-full">
          <div class="h-16 w-16 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-lightbulb"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">1. STRATEGIE</h3>
            <p>Aliquip mollit reprehenderit eu voluptate tempor. Esse occaecat sunt dolore mollit reprehenderit incididunt et amet id tempor.</p>
          </div>
        </div>
      </div>
    </section>

  </main>
</template> 

<script>
export default {
  name: 'App',
  components: {
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: 'Montserrat' ,Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #000;
}
h1, h2, h3, h4, h5, h6 {
  font-family: 'Roboto', 'Montserrat', Arial, sans-serif;
}
</style>