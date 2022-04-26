<script>
  import { onMount } from "svelte";

  onMount(async () => {
    //resize screen
    //getResize(".main");

  });

</script>
<style>
     @font-face {
       font-family: "Myriad-Pro-Bold-SemiExtended";
       src: url("./src/components/fonts/Myriad-Pro-Bold-SemiExtended.woff") format("woff"),
         /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
           url("./src/components/fonts/Myriad-Pro-Bold-SemiExtended.ttf") format("truetype"); /* Chrome 4+, Firefox 3.5, Opera 10+, Safari 3—5 */
     }  
     body {
       font-size: 1rem;
     }

     main {
       display: grid;
       place-items: center;
       text-align: center;
     }       
	.head{
    font-family: "Myriad-Pro-Bold-SemiExtended";
    font-size: 128px;
	}
</style>
   <main>
    <div class="main">
      <div class="head">
 		NFTEZOS.ART
      </div>
    </div>
</main>
