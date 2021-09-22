<script>
	// Setting the document title
    document.title = "InstaType"

    // importing components
    // Navbar
    import Navbar from "./components/Navbar.svelte"
    // Input
    import Input from "./components/Input.svelte";
   // Footer
   import Footer from "./components/Footer.svelte";
    
</script>

<main>
    <Navbar />
    <Input/>
    <Footer/>
</main>

<style>  
 /* // Importing fonts */
 @import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200;0,300;0,400;0,700;0,800;0,900;1,200;1,300;1,400;1,700;1,900&display=swap');
:global(body) {
		background-color: #2E3440;
	}
</style>