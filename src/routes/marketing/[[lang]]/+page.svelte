<script>
    import { page } from "$app/stores";
    const greetings = {
      en: "hello",
      es: "Hola",
      fn: "bounjuor"
    };
    const { lang  = 'en'} = $page.params;
    const greeting = greetings[lang];
  </script>
  
  <p>{greeting}</p>  <!-- Added this line to display the greeting -->