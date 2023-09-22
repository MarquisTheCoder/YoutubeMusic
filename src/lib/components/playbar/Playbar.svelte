


<!-- server side -->
<script lang="js" charset="utf-8">
    import Play from "$lib/components/playbar/Play.svelte";
    import Volume from "$lib/components/playbar/Volume.svelte";
    import Artist from "$lib/components/playbar/Artist.svelte";
</script>

<!-- html -->
<section class="bg-black text-white font-bold px-10 
w-full min-w-full min-h-14 h-20 p-4 items-center
flex flex-row justify-between">

 <div id="artist-song">
    <Artist/>
 </div>
 <div id="play-utility">
    <Play/>
 </div>
 <div id="volume-shuffle">
    <Volume/>
 </div>
</section>

<!-- styling -->
<style type="text/css" media="screen">

</style>
