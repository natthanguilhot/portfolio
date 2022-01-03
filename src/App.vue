<template>
  <header class="bg-gray-300">
    <div class="mx-auto px-8">
      <div class="flex flex-col justify-center items-start text-left font-bold">
        <div class="h-20 w-20 bg-orange-600 rounded-full my-6"></div>
        <h1 class="text-5xl">Je suis Natthan GUILHOT</h1>
        <p class="my-4 text-lg">Développeur full-stack spécialisé en Vue.js pour le front-end et Node.js pour le back-end</p>
        <a href="#contactForm" class="bg-black px-8 py-4 text-white hover:bg-orange-600">ME CONTACTER</a>
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
        <div class="flex my-8 w-full min-h-[200px]">
          <div class="!h-20 !w-20 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-user"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">FRONT-END</h3>
            <p>Le développement front-end correspond à la conception de l’interface graphique utilisateur.</p>
          </div>
        </div>
        <div class="flex my-8 w-full min-h-[200px]">
          <div class="!h-20 !w-20 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fab fa-vuejs"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">VUE.JS</h3>
            <p>Vue est un framework évolutif pour construire des interfaces utilisateur. Vue a été conçu et pensé pour pouvoir être adopté de manière incrémentale.</p>
          </div>
        </div>
        <div class="flex my-8 w-full min-h-[200px]">
          <div class="!h-20 !w-20 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <img src="./assets/tailwindcss.svg" alt="Tailwind" class="h-full w-full p-2">
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">TAILWINDCSS</h3>
            <p>Vue est un framework évolutif pour construire des interfaces utilisateur. Vue a été conçu et pensé pour pouvoir être adopté de manière incrémentale.</p>
          </div>
        </div>
        <div class="flex my-8 w-full min-h-[200px]">
          <div class="!h-20 !w-20 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-server"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">BACK-END</h3>
            <p>Vue est un framework évolutif pour construire des interfaces utilisateur. Vue a été conçu et pensé pour pouvoir être adopté de manière incrémentale.</p>
          </div>
        </div>
        <div class="flex my-8 w-full min-h-[200px]">
          <div class="!h-20 !w-20 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fab fa-node-js"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">NODE.JS</h3>
            <p>Vue est un framework évolutif pour construire des interfaces utilisateur. Vue a été conçu et pensé pour pouvoir être adopté de manière incrémentale.</p>
          </div>
        </div>
        <div class="flex my-8 w-full min-h-[200px]">
          <div class="!h-20 !w-20 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-database"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">MONGODB</h3>
            <p>Vue est un framework évolutif pour construire des interfaces utilisateur. Vue a été conçu et pensé pour pouvoir être adopté de manière incrémentale.</p>
          </div>
        </div>
        <div class="flex my-8 w-full min-h-[200px]">
          <div class="!h-20 !w-20 bg-orange-600 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-database"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">MYSQL</h3>
            <p>Vue est un framework évolutif pour construire des interfaces utilisateur. Vue a été conçu et pensé pour pouvoir être adopté de manière incrémentale.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="bgafter relative z-10 py-8 my-16">
      <div class="px-8">
        <div class="my-8">
          <img src="./assets/screen_vrtig0.png" alt="" class="h-[350px] w-[350px] object-cover object-center mx-auto">
        </div>
        <div class="my-8">
          <img src="./assets/screen_hyvirea.png" alt="" class="h-[350px] w-[350px] object-cover object-center mx-auto">
        </div>
        <div class="my-8">
          <img src="./assets/screen_skincasts.png" alt="" class="h-[350px] w-[350px] object-cover object-center mx-auto">
        </div>
      </div>
      <div class="px-8 bg-white h-auto py-4">
        <h2 class="text-4xl font-bold py-8">Mon travail</h2>
        <p class="py-8">Vous pouvez retrouver ici, toutes les missions qui sont accessible à tous. J'ai cependant réalisé d'autres projets qui ne sont pas forcément affichés car non ouvert au public</p>
        <a href="#contactForm" class="py-4 px-8 border border-black border-2 bg-white my-8 block w-max font-bold text-2xl">Me contacter</a>
      </div>
    </section>
  </main>

  <section class="bg-gray-300 py-16 text-center">
    <div class="px-8 flex flex-col justify-center items-center space-y-8">
      <div>
        <img src="./assets/PPPro.jpg" alt="" class="h-40 w-40 rounded-full border border-4 border-orange-600 object-cover object-top">
      </div>
      <p>In ipsum non proident aliqua enim veniam. Anim laborum consectetur mollit duis sunt labore esse enim cillum amet. Mollit velit laboris enim aliquip anim cupidatat cillum aute. Nisi esse Lorem est ipsum nisi elit et aliqua. Proident voluptate amet laborum do qui officia anim reprehenderit aliquip irure aliqua veniam. Ea magna nostrud minim ipsum velit Lorem consequat anim in minim adipisicing consequat. Ad cillum duis incididunt cillum minim id dolore nostrud cupidatat reprehenderit sit id.</p>
      <p class="text-xl">Natthan Guilhot</p>
    </div>
  </section>

  <section class="bg-[#292E33] text-white py-16">
    <div class="px-8">
      <div>
        <p class="text-xl">Prêt à échanger ?</p>
        <h2 class="text-4xl font-bold py-8">Me contacter</h2>
        <p>N'hésitez pas à prendre contact avec moi si vous souhaitez en savoir plus sur moi ou mon travail.</p>
      </div>
      <div>
        <form action="" class="flex flex-col space-y-8 my-8 justify-center items-start">
          <label for="">Votre nom :</label>
          <input type="text">
          <label for="">Votre mail :</label>
          <input type="mail">
          <label for="">Votre message :</label>
          <textarea type="text"></textarea>
          <button class="py-2 px-4 border border-2 border-white">Envoyer</button>
        </form>
      </div>
    </div>
  </section>

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
.bgafter {
  &:after {
    content: "";
    position: absolute;
    inset: 0;
    height: 100%;
    width: 300px;
    background-color: rgb(234 88 12);
    z-index: -1;
    margin-left: auto;
    margin-right: auto;
  }
}
form > input, textarea {
  background-color: #292E33;
  border-bottom: 1px solid white;
  width: 100%;
}
// form > label {
//   transform: translateY(3.5rem);
// }
// input:focus + label {
//   transform: translateY(1rem);
// }
</style>