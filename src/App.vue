<template>
  <header class="bg-gray-300">
    <div :class="[isScrolling ? 'sm:pt-40': '']" class="mx-auto px-8 sm:flex max-w-screen-xl sm:pt-20">
      <div class="flex flex-col justify-center items-start text-left font-bold sm:w-6/12">
        <div class="h-20 w-20 bg-sky-700 rounded-full my-6"></div>
        <h1 class="text-5xl lg:text-7xl h-[150px] sm:h-[200px]">Je suis <span id="typewriter1"></span></h1>
        <p class="my-4 text-lg">Développeur full-stack spécialisé en Vue.js pour le front-end et Node.js pour le back-end</p>
        <a href="#contactForm" class="bg-black px-8 py-4 text-white hover:bg-sky-700">ME CONTACTER</a>
      </div>
      <div data-aos="fade-left" class="h-[450px] lg:h-full my-8 relative sm:w-6/12 sm:mb-0">
        <img src="./assets/PPPro-removebg-preview.png" alt="Natthan Guilhot" class="h-full w-full object-center object-contain">
      </div>
    </div>
  </header>
  <main>

    <section data-aos="fade-up" id="profil" class="text-left px-8 text-lg mb-40 max-w-screen-xl lg:mx-auto">
      <div class="my-8 pt-24 sm:text-center">
        <h2 class="text-4xl font-bold mb-16">PROFIL</h2>
        <!-- <p class="my-8">Je suis un développeur Vue.js et Node.js</p> -->
      </div>
      <div class="sm:flex sm:justify-around sm:items-start sm:space-x-12 h-min">
        <div data-aos="fade-right" class="sm:w-3/12">
          <!-- <h3 class="text-3xl">A propos</h3> -->
          <p class="my-8">Je suis un développeur web full-stack. Avec un an d'alternance dans une start-up, diplomé de l'école OpenClassRooms.</p>
          <div class="flex justify-start items-center space-x-4 my-8">
            <a aria-label="Lien vers mon Linkedin" target="_blank" rel="noopener" href="https://www.linkedin.com/in/natthanguilhot" class="text-5xl text-[#007BB5]"><i class="fab fa-linkedin"></i></a>
            <a aria-label="Lien vers mon adresse mail" href="mailto:natthan.dev@gmail.com" class="text-5xl text-[#db4a39]"><i class="fas fa-envelope"></i></a>
            <a aria-label="Lien vers mon profil Malt" href="https://www.malt.fr/profile/natthanguilhot?overview=true" target="_blank" rel="noopener"><img src="./assets/malt-red.svg" alt="Profil Malt" class="h-20 w-20"></a>
          </div>
        </div>
        <img data-aos="fade-up" src="./assets/PPPro.jpg" alt="Natthan Guilhot" class="h-80 w-80 sm:h-60 sm:w-60 rounded-full object-top object-cover mt-24 sm:w-3/12 sm:mt-0">
        <div data-aos="fade-left" class="my-10 sm:w-3/12 sm:mt-0">
          <!-- <h3 class="text-3xl my-8 sm:mt-0">Détails</h3> -->
          <div class="flex flex-col space-y-3">
            <h4 class="font-bold">Nom :</h4>
            <p>Natthan Guilhot</p>
            <h4 class="font-bold">Âge :</h4>
            <p>25 ans</p>
            <h4 class="font-bold">Localisation :</h4>
            <p>Bouches-du-Rhone, France</p>
          </div>
        </div>
      </div>
    </section>

    <section class="text-left text-lg px-8 my-8 max-w-screen-xl lg:mx-auto">
      <h2 class="text-4xl font-bold underline underline-offset-4 decoration-8 decoration-sky-700 my-8">A PROPOS DE MOI</h2>
      <p>
        <span class="font-bold mb-2 block">Je m'appelle Natthan Guilhot, j'ai travaillé en tant que développeur web alternant dans une entreprise appelé <a href="https://www.vrtig0.fr" target="_blank" rel="noopener" class="hover:text-sky-700 decoration-sky-700 decoration-2 underline-offset-1 underline active:decoration-8 hover:underline-offset-4 active:underline-offset-1 transition-all duration-150 ease-in-out">VR'TIG.0</a> pendant 1 an.</span><br> <span>J’ai eu différents parcours dans ma vie. Dans un premier temps, j’ai suivi un BTS comptabilité et gestion dans lequel j’ai adoré apprendre. Cependant, je ne me sentais pas épanoui dans ce domaine, alors j’ai commencé à travailler dans différents domaines. Puis j’ai découvert le monde du développement, et j’ai tout de suite accroché aux différentes facettes comme l’apprentissage qui ne cesse de croitre et le sentiment de satisfaction lors de la création.</span>
      </p>
      <div class="lg:flex lg:flex-row-reverse">
        <div data-aos="fade-left" class="h-[400px] !w-[250px] bg-sky-700 mx-auto text-white p-4 my-8">
          <p class="font-bold text-xl mt-8">EMAIL</p>
          <p>natthan.dev@gmail.com</p>
          <p class="font-bold text-xl mt-8 block">PROFESSION</p>
          <p>Développeur web full-stack</p>
        </div>
        <p class="lg:mt-8"> Durant mon année chez VR'TIG.0 j'ai effectué d'une part le développement des sites de l'entreprise. Et d'autre part le développement d'applications pour les professionnels du secours et du soin d'urgence pour un client (pharmacie, pompier, ambulance, …). Le développement d’application a été très formateur notamment par rapport au développement en groupe. Ce qui m’a permis de consolider et améliorer mes connaissances en front-end également. De par cette alternance, j'ai obtenu un diplôme de développeur web reconnu  au RNCP bac +2. <br>Pour parler un peu plus de moi, je suis passionné par l'informatique et le numérique de manière plus générale. Je regarde et suis de près l'esport. Enfin, je lis beaucoup de livre, surtout des mangas.
        </p>
      </div>
    </section>

    <section id="howiwork" class="bg-gray-300 py-8 lg:-mt-20">
      <div class="text-center px-8 max-w-screen-xl lg:mx-auto">
        <h2 class="text-4xl font-bold my-4">CE QUE JE FAIS</h2>
        <p>En tant que développeur full-stack, je suis amené à travailler sur beaucoup de choses.</p>
      </div>
      <div class="px-8 sm:flex sm:flex-wrap max-w-screen-xl lg:mx-auto">
        <div data-aos="fade-right" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-user"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">FRONT-END</h3>
            <p>Le développement front-end correspond à la conception de l’interface graphique utilisateur.</p>
          </div>
        </div>
        <div data-aos="fade-left" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fab fa-vuejs"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">VUE.JS</h3>
            <p>Vue.Js est un framework évolutif pour construire des interfaces utilisateur. Vue a été conçue et pensé pour pouvoir être adopté de manière incrémentale.</p>
          </div>
        </div>
        <div data-aos="fade-right" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <img src="./assets/tailwindcss.svg" alt="Tailwind" class="h-full w-full p-2">
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">TAILWINDCSS</h3>
            <p>Un framework CSS contenant des classes, et qui peut être composé pour créer n'importe quel design, directement dans le balisage HTML.</p>
          </div>
        </div>
        <div data-aos="fade-left" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fab fa-sass"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">SASS</h3>
            <p>Sass est le langage d'extension CSS de qualité professionnelle le plus mature, stable et puissant  au monde.</p>
          </div>
        </div>
        <div data-aos="fade-right" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-server"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">BACK-END</h3>
            <p>Le back-end est la maîtrise toute la partie invisible pour l’utilisateur, mais qui va permettre le bon fonctionnement d’un site internet</p>
          </div>
        </div>
        <div data-aos="fade-left" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fab fa-node-js"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">NODE.JS</h3>
            <p>Node.js est un environnement d'exécution JavaScript open source et multiplateforme.</p>
          </div>
        </div>
        <div data-aos="fade-right" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-database"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">MONGODB</h3>
            <p>MongoDB est un système de gestion de base de données orienté documents, répartissable sur un nombre quelconque d'ordinateurs et ne nécessitant pas de schéma prédéfini des données.</p>
          </div>
        </div>
        <div data-aos="fade-left" class="flex my-8 w-full min-h-[200px] sm:w-6/12">
          <div class="!h-20 !w-20 bg-sky-700 rounded-full text-5xl w-3/12 flex justify-center items-center">
            <i class="fas fa-database"></i>
          </div>
          <div class="ml-4 w-9/12">
            <h3 class="text-2xl font-bold mb-4">MYSQL</h3>
            <p>MySQL est un système de gestion de bases de données relationnelles.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="mywork" class="bgafter relative z-10 py-8 my-16 sm:relative max-w-screen-xl lg:mx-auto">
      <div class="px-8 sm:flex sm:flex-wrap sm:space-y-8">
        <div data-aos="zoom-out-right" class="my-8 sm:w-5/12 sm:mx-auto lg:w-4/12 !h-[350px] sm:!w-[350px]">
          <a href="https://mangaup.netlify.app/" target="_blank" rel="noopener">
            <img src="./assets/screenmangaup.png" alt="Projet MangaUp" class="h-[350px] w-[350px] object-cover object-center mx-auto">
          </a>
        </div>
        <div data-aos="zoom-out-down" class="my-8 sm:w-5/12 sm:mx-auto lg:w-4/12 !h-[350px] sm:!w-[350px]">
          <a href="https://vrtig0.fr" target="_blank" rel="noopener">
            <img src="./assets/screen_vrtig0.png" alt="Site vitrine pour l'entreprise : VR'TIG.0" class="h-[350px] w-[350px] object-cover object-center mx-auto">
          </a>
        </div>
        <div data-aos="zoom-out-left" class="my-8 sm:w-5/12 sm:mx-auto lg:w-4/12 !h-[350px] sm:!w-[350px]">
          <a href="https://hyvirea.fr" target="_blank" rel="noopener">
            <img src="./assets/screen_hyvirea.png" alt="Site vitrine pour l'entreprise : HYVIREA" class="h-[350px] w-[350px] object-cover object-center mx-auto">
          </a>
        </div>
        <!-- <div data-aos="zoom-out-right" class="my-8 sm:w-5/12 sm:mx-auto lg:w-4/12 !h-[350px] sm:!w-[350px]">
          <a href="https://github.com/natthanguilhot/GUILHOTNATTHAN_7_12082021" target="_blank" rel="noopener">
            <img src="./assets/screengroupo.png" alt="Projet réalisé lors de ma formation OpenClassRooms" class="h-[350px] w-[350px] object-cover object-center mx-auto">
          </a>
        </div> -->
        <div data-aos="zoom-out-up" class="my-8 sm:w-5/12 sm:mx-auto lg:w-4/12 !h-[350px] sm:!w-[350px]">
          <a href="https://skincasts.fr" target="_blank" rel="noopener">
            <img src="./assets/screen_skincasts.png" alt="Site vitrine pour l'entreprise : SKINCASTS" class="h-[350px] w-[350px] object-cover object-center mx-auto">
          </a>
        </div>
        <div data-aos="zoom-out-left" class="my-8 sm:w-5/12 sm:mx-auto lg:w-4/12 !h-[350px] sm:!w-[350px]">
          <a href="https://theonlinetodoapp.netlify.app/" target="_blank" rel="noopener">
            <img src="./assets/screenonelinetodoapp.png" alt="Projet réalisé en autonomie" class="h-[350px] w-[350px] object-cover object-center mx-auto">
          </a>
        </div>
        <div data-aos="zoom-out-left" class="my-8 sm:w-5/12 sm:mx-auto lg:w-4/12 !h-[350px] sm:!w-[350px] bg-transparent">
          <!-- <a href="https://theonlinetodoapp.netlify.app/" target="_blank" rel="noopener">
            <img src="./assets/screenonelinetodoapp.png" alt="Projet réalisé en autonomie" class="h-[350px] w-[350px] object-cover object-center mx-auto">
          </a> -->
        </div>
      </div>
      <div class="px-8 bg-white h-auto py-4 sm:w-8/12 lg:w-[450px] sm:my-8 sm:translate-x-52 sm:-translate-y-20 sm:pr-0 lg:!translate-x-[32rem] xl:!translate-x-[42rem]">
        <h2 class="text-4xl font-bold py-8">Mon travail</h2>
        <p class="py-8">Vous pouvez retrouver ici, toutes les missions qui sont accessibles à tous. J'ai cependant réalisé d'autres projets qui ne sont pas forcément affichés, car non ouvert au public.</p>
        <a href="#contactForm" class="py-4 px-8 border border-black border-2 bg-white my-8 block w-max font-bold text-2xl hover:text-white hover:bg-black active:text-black active:bg-white">Me contacter</a>
      </div>
    </section>
  </main>

  <!-- <section class="bg-gray-300 py-16 text-center">
    <div class="px-8 flex flex-col justify-center items-center space-y-8 max-w-screen-xl lg:mx-auto">
      <div>
        <img src="./assets/PPPro.jpg" alt="" class="h-40 w-40 rounded-full border border-4 border-sky-700 object-cover object-top">
      </div>
      <p>In ipsum non proident aliqua enim veniam. Anim laborum consectetur mollit duis sunt labore esse enim cillum amet. Mollit velit laboris enim aliquip anim cupidatat cillum aute. Nisi esse Lorem est ipsum nisi elit et aliqua. Proident voluptate amet laborum do qui officia anim reprehenderit aliquip irure aliqua veniam. Ea magna nostrud minim ipsum velit Lorem consequat anim in minim adipisicing consequat. Ad cillum duis incididunt cillum minim id dolore nostrud cupidatat reprehenderit sit id.</p>
      <p class="text-xl">Natthan Guilhot</p>
    </div>
  </section> -->

  <footer class="bg-[#292E33] text-white py-16">
    <div class="px-8 max-w-screen-xl lg:mx-auto">
      <div>
        <p class="text-xl">Prêt à échanger ?</p>
        <h2 id="contactForm" class="text-4xl font-bold py-8">Me contacter</h2>
        <p>N'hésitez pas à prendre contact si vous souhaitez en savoir plus sur moi ou mon travail.</p>
      </div>
      <div>
        <form ref="form" @submit.prevent="sendEmail" class="flex flex-col space-y-8 my-8 justify-center items-start">
          <label for="name">Votre nom :</label>
          <input name="from_name" type="text" id="name" minlength="2" required>
          <label for="mail">Votre mail :</label>
          <input name="reply_to" type="mail" id="mail" minlength="4" required>
          <label for="msg">Votre message :</label>
          <textarea name="message" type="text" id="msg" minlength="20" maxlength="250" required></textarea>
          <button type="submit" class="py-2 px-4 border border-2 border-white">Envoyer</button>
        </form>
      </div>
      <div class="flex justify-start items-center space-x-8">
        <a aria-label="Lien vers mon Linkedin" target="_blank" rel="noopener" href="https://www.linkedin.com/in/natthanguilhot" class="text-5xl text-[#007BB5]"><i class="fab fa-linkedin"></i></a>
        <a aria-label="Lien vers mon GitHub" href="https://github.com/natthanguilhot" target="_blank" rel="noopener" class="text-5xl"><i class="fab fa-github"></i></a>
        <a aria-label="Lien vers mon adresse mail" href="mailto:natthan.dev@gmail.com" class="text-5xl text-[#db4a39]"><i class="fas fa-envelope"></i></a>
        <a aria-label="Lien vers mon profil Malt" href="https://www.malt.fr/profile/natthanguilhot?overview=true" target="_blank" rel="noopener"><img src="./assets/malt-red.svg" alt="Profil Malt" class="h-20 w-20"></a>
      </div>
    </div>
  </footer>

</template> 

<script>
import emailjs from '@emailjs/browser';
import Typewriter from 'typewriter-effect/dist/core';

export default {
  name: 'App',
  data(){
    return {
      isScrolling: false,
    }
  },
  methods: {
    typewriter(){
      var typewriter1 = document.querySelector('#typewriter1');
      var typewriter = new Typewriter(typewriter1, {
        loop:true,
      })
      typewriter
      .typeString('Natthan GUILHOT')
      .pauseFor(2000)
      .deleteAll()
      .typeString('développeur web')
      .pauseFor(2000)
      .deleteChars(3)
      .typeString('Vue.Js')
      .pauseFor(2000)
      .deleteChars(6)
      .typeString('Node.Js')
      .pauseFor(2000)
      .start()
    },
    sendEmail() {
      emailjs.sendForm('service_eqenvec', 'template_htic5me', this.$refs.form, 'user_wKmhV5TATN5TzDkCyot3l')
        .then((result) => {
            console.log('SUCCESS!', result.text);
            alert('Email envoyé !');
        }, (error) => {
            alert('Erreur lors de l\'envoie ' + error.text);
            console.log('FAILED...', error.text);
        });
    },
  },
  mounted(){
    this.typewriter();
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html {
  scroll-behavior: smooth;
}
#app {
  font-family: 'Montserrat' ,Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #000;
  @media (max-width:1024px) {
    overflow-x: hidden;    
  }
}
h1 {
  font-family: 'Roboto' ,Avenir, Helvetica, Arial, sans-serif;
}
h2 {
  font-family: 'Oswald' ,Avenir, Helvetica, Arial, sans-serif;
}
h3, h4, h5, h6 {
  font-family: 'Montserrat' ,Avenir, Helvetica, Arial, sans-serif;
}
.bgafter {
  &:after {
    content: "";
    position: absolute;
    inset: 0;
    height: 100%;
    width: 300px;
    background-color: #0369a1;
    z-index: -1;
    margin-left: auto;
    margin-right: auto;
    @media (min-width: 1024px) {
      transform: translateX(-15rem);
    }
  }
}
form > input, textarea {
  background-color: #292E33;
  border-bottom: 1px solid white;
  width: 100%;
}
</style>