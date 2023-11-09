<script>
  import Step from "./Step.svelte";

  import profile from "/assets/images/profile.png";

  let steps = [
    {
      name: "Smoljames Store",
      icon: "fa-solid fa-cart-shopping",
      description:
        "Smoljames Store is a a merchanising store created with Next.js, Commerce.js & Stripe! Commerce.js is a CMS for managing project and Stripe is used for all transaction handling.",
    },
    {
      name: "Utlimate Todos",
      icon: "fa-solid fa-list-check",
      description:
        "Test for model robustness with customized test profiles and receive exhaustive reporting on the performance and potential vulnerabilities of your model.",
    },
    {
      name: "Pokédex",
      icon: "fa-solid fa-diagram-project",
      description:
        "Augment your datasets with our filters and dataset manipulations to ensure your models are trained on the highest quality datasets (coming soon).",
    },
  ];

  let benefits = [
    {
      metric: "10x",
      name: "a self taught developer",
      description:
        "I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programming, design, cloud services and much much more.",
    },
    {
      name: "a product design & UX finatic",
      description:
        "Carefully crafting and designing amazing user experiences allows me to express and experiment with every morsel of creativity I have. I love the challenge of learning new design concepts and enabling users with amazing online experiences.",
    },
    {
      name: "an excellent communicator",
      description:
        "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team.",
    },
  ];
</script>

<main class="flex flex-col flex-1 p-4">
  <section
    id="introPage"
    class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
  >
    <div
      class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
    >
      <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
        Hi! I'm <span class="text-violet-400 poppins">MOHIL</span>
        BANSAL
        <br />Full Stack
        <span class="poppins text-violet-400"> Developer </span>
      </h2>
      <br />
      <p class="text-base sm:text-lg md:text-xl">
        My <span class="text-violet-400 poppins">Favourite tech</span>
        includes App(Flutter) and JavaScript (NEXT.JS or SvelteKit), TailwindCSS,
        Node.js + Express.js and Firebase/Firestore or Appwrite!
      </p>
      <div
        class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950 cursor-pointer"
      >
        <div
          class="absolute w-full top-0 right-full h-full z-[8] bg-violet-400 opacity-20 duration-300 group-hover:translate-x-full"
        />
        <h4 class="flex relative z-[9] gap-4">Get In Touch &rarr;</h4>
      </div>
    </div>
    <div class="relative shadow-2xl grid place-items-center">
      <img
        src={profile}
        alt="Profile Pic"
        class="object-cover z-[2] max-h-[80vh]"
      />
    </div>
  </section>

  <!-- Projects Section -->

  <section id="projects" class="py-20 lg:py-32 gap-24 flex flex-col">
    <div class="flex flex-col gap-2 text-center">
      <h6 class="text-large sm:text-xl md:text-2xl">
        A few of my creative endeavors.
      </h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        Curious to <span class="poppins text-violet-400">see</span> my work?
      </h3>
    </div>
    <a
      href="www.google.com"
      target="_blank"
      class="hover:border-violet-800 hover:text-slate-300 border-solid border-2 rounded-md m-auto flex flex-row items-center border-slate-400 px-4 py-2 space-x-4 -mb-4 sm:-mb-0 -mt-10 duration-200"
      ><i class="fa-regular fa-circle-play" />
      <p>Watch the video</p>
    </a>
  </section>
</main>
