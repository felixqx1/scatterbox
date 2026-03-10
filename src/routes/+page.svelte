<script lang="ts">
    import '../app.css'
    const GitHub = '/images/icons/github-mark.svg'
    const Discord = '/images/icons/Discord.svg'
    const aether = '/images/aether.webp'
    const cfrf = '/images/cfrf.webp'
</script>

<main>
    <div class="hero min-h-screen text-center">
        <h1 class="text-5xl font-bold">Hi there! <span class="wave">👋</span>
            <div>
            <br />
            <span class="text-2xl" >I'm felixq and I'm a
                <span class="text-rotate">
                    <span>
                        <span class="px-2">roblox developer.</span>
                        <span class="px-2">discord bot developer.</span>
                        <span class="px-2">back-end developer.</span>
                    </span>
                </span>
            </span>
            <br />
            <span class="text-2xl" > With 5 years of experience and I want to help you build amazing things!</span>
            </div>
            <div class="justify-center gap-4 mt-8 flex">
            <a href="https://github.com/felixqx1" target="_blank" rel="noopener noreferrer">
                <img src={GitHub} alt="GitHub" class="w-8 h-8" />
            </a>

            <a href="https://discord.com/users/975744322551054346" target="_blank" rel="noopener noreferrer">
                <img src={Discord} alt="Discord" class="w-8 h-8" />
            </a>
            </div>
        </h1>
    </div>
    <div class="bg-base-300 flex flex-col items-center justify-center rounded-lg p-10 mx-5 mb-10">
        <h2 class="text-3xl font-bold mb-4">Experience:</h2>
        <div class="grid grid-cols-3 gap-6">
            <div class="card bg-base-200 shadow-sm">
                <figure>
                    <img
                    src={aether}
                    alt="site aether" />
                </figure>
                <div class="card-body">
                    <a class="card-title underline" href="https://www.roblox.com/games/74117404713109/Site-Aether" target="_blank" rel="noopener noreferrer">
                    [SCP:F] Site Aether
                    </a>
                    <p></p>
                    <div class="card-actions justify-end">
                    </div>
                </div>
            </div>
            <div class="card bg-base-200 shadow-sm">
                <figure>
                    <img
                    src={cfrf}
                    alt="cfrf" />
                </figure>
                <div class="card-body">
                    <a class="card-title underline" href="https://www.roblox.com/games/131556520562288/Classified-Fusion-Reactor-Facility" target="_blank" rel="noopener noreferrer">
                    Classified Fusion Reactor Facility
                    </a>
                    <p></p>
                    <div class="card-actions justify-end">
                    </div>
                </div>
            </div>
        </div>
    </div>
</main>