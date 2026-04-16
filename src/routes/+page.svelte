<script lang="ts">
    import '../app.css'
    const GitHub = '/images/icons/github-mark.svg'
    const Discord = '/images/icons/Discord.svg'
    const gnupg = '/images/icons/GnuPG.webp'
    const aether = '/images/aether.webp'
    const cfrf = '/images/cfrf.webp'
    const onpsWiki = '/images/onpsWiki.avif'
    const scatterbox = '/images/scatterbox.webp'
    const RHDR = '/images/RHDR.webp'
</script>

<svelte:head>
    <title>portfolio</title>
</svelte:head>

<main>
    <div class="hero min-h-screen text-center">
        <h1 class="text-5xl font-bold">Hi there! <span class="wave">👋</span>
            <div>
            <span class="text-2xl" >I'm felixq and I'm a
                <span class="text-rotate">
                    <span>
                        <span>minecraft plugin developer.</span>
                        <span>discord bot developer.</span>
                        <span>back-end developer.</span>
                    </span>
                </span>
            </span>
            <br/>
            <span class="text-2xl" > With 5 years of experience and I want to help you build amazing things!</span>
            </div>
            <div class="justify-center gap-4 mt-8 flex">
            <a href="https://github.com/felixqx1" target="_blank" rel="noopener noreferrer">
                <img src={GitHub} alt="GitHub" class="w-8 h-8" />
            </a>
            <a href="./gpg.asc" target="_blank" rel="noopener noreferrer">
                <img src={gnupg} alt="GitHub" class="w-8 h-8" />
            </a>
            <a href="https://discord.com/users/975744322551054346" target="_blank" rel="noopener noreferrer">
                <img src={Discord} alt="Discord" class="w-8 h-8" />
            </a>
            </div>
        </h1>
        <div class="absolute bottom-0 mb-5" >
            <span class="font-bold text-xl" >scroll down</span>
            <span class="transition-transform duration-500 ease-in-out w-screen flex justify-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true" data-slot="icon" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5">
                        
                    </path>
                </svg>
            </span>
        </div>
    </div>
    <div class="bg-base-300 flex flex-col items-center justify-center rounded-lg p-10 mx-5 mb-10">
        <h2 class="text-3xl font-bold mb-4">Experience:</h2>
        <div class="grid lg:grid-cols-3 sm:grid-cols-1 gap-6">
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
                    src={onpsWiki}
                    alt="onpsWiki" />
                </figure>
                <div class="card-body">
                    <a class="card-title underline" href="https://wiki.koyot.digital/" target="_blank" rel="noopener noreferrer">
                    ONPS wiki
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
            <div class="card bg-base-200 shadow-sm">
                <figure>
                    <img
                    src={RHDR}
                    alt="RHDR" />
                </figure>
                <div class="card-body">
                    <a class="card-title underline" href="https://realistic-hydroelectric-simulator.github.io/RHES_Wiki/" target="_blank" rel="noopener noreferrer">
                    Realistic Hydroelectric Simulator Wiki
                    </a>
                    <p></p>
                    <div class="card-actions justify-end">
                    </div>
                </div>
            </div>
        </div>
        <h2 class="text-3xl font-bold mt-10 mb-4">Hosting:</h2>
        <div class="grid justify-center grid-cols-1 gap-6">
            <div class="card bg-base-200 card-md shadow-sm">
                <div class="card-body">
                    <h2 class="card-title justify-center pb-1">what i can host:</h2>
                    <div class="overflow-x-auto">
                        <table class="table text-center">
                            <tbody>
                            <tr>
                                <td>discord bots</td>
                            </tr>
                            <tr>
                                <td>websites with or without a backend</td>
                            </tr>
                            <tr>
                                <td>game servers</td>
                            </tr>
                            <tr>
                                <td>and more!</td>
                            </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        <h2 class="text-3xl font-bold mt-10 mb-4">Contact me:</h2>
        <div class="grid justify-center lg:grid-cols-2 sm:grid-cols-1 gap-6">
            <div class="card bg-base-200 card-md shadow-sm">
                <div class="card-body">
                    <h2 class="card-title justify-center">For hosting:</h2>
                    <div class="flex w-full flex-col">
                        <div class="card bg-base-300 rounded-box grid place-items-center">
                            <p class="p-7">send me an email at <a href="mailto:hosting@scatterbox.dev" class="link" target="_blank" rel="noopener noreferrer">hosting@scatterbox.dev</a></p>
                        </div>
                    <div class="divider">OR</div>
                        <div class="card bg-base-300 rounded-box grid place-items-center">
                            <p class="p-7">message me on <a href="https://discord.com/users/975744322551054346" class="link" target="_blank" rel="noopener noreferrer">discord</a></p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card bg-base-200 card-md shadow-sm">
                <div class="card-body">
                    <h2 class="card-title justify-center"> Hire me:</h2>
                    <div class="flex w-full flex-col">
                        <div class="card bg-base-300 rounded-box grid place-items-center">
                            <p class="p-7">send me an email at <a href="mailto:contact@scatterbox.dev" class="link" target="_blank" rel="noopener noreferrer">contact@scatterbox.dev</a></p>
                        </div>
                    <div class="divider">OR</div>
                        <div class="card bg-base-300 rounded-box grid  place-items-center">
                            <p class="p-7">message me on <a href="https://discord.com/users/975744322551054346" class="link" target="_blank" rel="noopener noreferrer">discord</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

<footer class="footer footer-horizontal footer-center bg-base-100 text-primary-content p-10">
  <aside>
    <img
        src={scatterbox}
        alt="scatterbox logo"
        class="w-12 h-12 rounded-full mb-2"
    />
    <p class="font-bold">
      scatterbox inc.
      <br />
    </p>
    <p>Copyright © {new Date().getFullYear()} - All right reserved</p>
  </aside>
</footer>

</main>
