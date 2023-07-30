<script>
  import "../app.css";
</script>

<div class="w-screen h-screen flex justify-center items-center bg-slate-950 p-3 text-slate-50">
    <div class="border-[12px] border-slate-700 w-full h-full max-w-7xl px-16 py-12">
        <header class="flex justify-between w-full">
            <div class="">Logo</div>
            <a href="#">Reserve username</a>
        </header>
        <slot />
        <footer>
            <div class="">Logo</div>
            <h3>Built for the Builders</h3>
        </footer>
    </div> 
</div>