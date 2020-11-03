<script>
  import LogoTwitter32 from "carbon-icons-svelte/lib/LogoTwitter32";
  import LogoGithub32 from "carbon-icons-svelte/lib/LogoGithub32";
  import EmailNew32 from "carbon-icons-svelte/lib/EmailNew32";
  import LogoLinkedin32 from "carbon-icons-svelte/lib/LogoLinkedin32";
  import SendAltFilled16 from "carbon-icons-svelte/lib/SendAltFilled16";
</script>

<style global>
  /* purgecss start ignore */
  @tailwind base;
  @tailwind components;
  /* purgecss end ignore */
  @tailwind utilities;
</style>

<main class="flex items-center py-1 justify-center h-screen bg-gray-100">
  <div class="flex flex-col md:flex-row container mx-auto text-gray-800">
    <div
      class="w-full md:w-2/5 border-b-4 border-orange-600 md:border-r-4 md:border-b-0 px-5 md:px-0">
      <h1 class="text-5xl leading-tight">
        Hola! Soy
        <strong class="font-bold">Wilson Naranjo</strong>
      </h1>
      <div class="text-orange-600 mt-3 text-md">
        <div class="py-3">
          <a
            href="https://twitter.com/wanaranjor"
            class="flex items-center py-1"
            target="_blank"
            rel="noopener">
            <LogoTwitter32 />
            <p class="px-3">wanaranjor</p>
          </a>
        </div>
        <div class="flex items-center py-1 py-3">
          <a
            href="https://github.com/wanaranjor"
            class="flex items-center py-1"
            target="_blank"
            rel="noopener">
            <LogoGithub32 />
            <p class="px-3">wanaranjor</p>
          </a>
        </div>
        <div class="flex items-center py-1 py-3">
          <a
            href="https://www.linkedin.com/in/wanaranjor/"
            class="flex items-center py-1"
            target="_blank"
            rel="noopener">
            <LogoLinkedin32 />
            <p class="px-3">wanaranjor</p>
          </a>
        </div>
        <div class="flex items-center py-1 py-3">
          <a
            href="mailto:contacto@wanaranjor.co"
            class="flex items-center py-1"
            target="_blank"
            rel="noopener">
            <EmailNew32 />
            <p class="px-3">contacto@wanaranjor.co</p>
          </a>
        </div>
      </div>
    </div>
    <div class="w-full md:w-3/5 flex flex-col justify-center items-center">
      <p class="w-full px-3 text-xl">
        Desarrollor frontend en constante formación.
      </p>
      <ul class="w-full px-10 py-5">
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">HTML</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">Css</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">JavaScript</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">Svelte</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">Snowpack</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">Firebase</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">Strapi</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">Git/GitHub</span>
        </li>
        <li class="flex items-center py-1">
          <SendAltFilled16 />
          <span class="px-3">Liferay</span>
        </li>
      </ul>
      <p class="w-full px-3 text-xl">
        Especialista en productos HCL Notes/Domino.
      </p>
    </div>
  </div>
</main>
