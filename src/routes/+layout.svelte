<script>
  import Navbar from "../components/Navbar.svelte";
  import Footer from "../components/Footer.svelte";

  export let data;
</script>

<header>
  <Navbar />
</header>

<main>
  <slot></slot> <!-- This is where child routes will be rendered -->
</main>

<footer>
  <Footer />
</footer>