<template>
    <!-- hero -->
    <section class="mb-52 md:mb-80">
        <div>
            <div class="flex flex-wrap items-center mx-auto max-w-7xl">
                <div class="w-full lg:max-w-lg lg:w-1/2 rounded-xl">
                    <div>
                        <div class="relative w-full max-w-lg">
                            <div
                                class="absolute top-0 rounded-full bg-violet-300 -left-4 w-72 h-72 mix-blend-multiply filter blur-xl opacity-70 animate-blob">
                            </div>

                            <div
                                class="absolute rounded-full bg-fuchsia-300 -bottom-24 right-20 w-72 h-72 mix-blend-multiply filter blur-xl opacity-70 animate-blob animation-delay-4000">
                            </div>
                            <div class="relative">
                                <!-- <img class="object-cover object-center mx-auto rounded-lg shadow-2xl" alt="hero"
                                    src="/assets/images/placeholders/squareCard.png"> -->
                            </div>
                        </div>
                    </div>
                </div>
                <div
                    class="flex flex-col items-start mt-12 mb-16 text-left lg:flex-grow lg:w-1/2 lg:pl-6 xl:pl-24 md:mb-0 xl:mt-0">
                    <span class="mb-8 text-xs font-bold tracking-widest text-blue-600 uppercase"> Hi, I'm Romeo </span>
                    <h1
                        class="mb-8 text-4xl font-bold leading-none tracking-tighter text-neutral-600 md:text-7xl lg:text-5xl">
                        Front End Web &amp; Mobile Engineer</h1>
                    <p class="mb-8 text-base leading-relaxed text-left text-gray-500">Based in the <b>Philippines</b>
                        who's an
                        enthusiast of building a better web and mobile experience.
                    </p>
                    <button class="btn btn-primary  text-white">Notify Me!</button>
                </div>
            </div>
        </div>
    </section>

    <!-- career timeline -->
    <div class="flex flex-col items-start md:items-center">
        <div />
        <h1 class="mb-2 text-4xl font-bold leading-none tracking-tighter text-neutral-600 md:text-7xl lg:text-5xl">
            Career Timeline</h1>

        <p class="mb-8 text-base leading-relaxed text-left text-gray-500">I've been writing code for over 5 years and
            it's been a blast!</p>

        <div class="container">
            <div class="flex flex-col md:grid grid-cols-9 mx-auto p-2 text-blue-50">
                <!-- left -->
                <div class="flex flex-row-reverse md:contents">
                    <div class="bg-indigo-400 col-start-1 col-end-5 p-4 rounded-xl my-4 ml-auto shadow-md">
                        <h3 class="font-semibold text-lg mb-1">Company Name</h3>
                        <p class="leading-tight text-justify">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi,
                            quaerat?
                        </p>
                    </div>
                    <div class="col-start-5 col-end-6 md:mx-auto relative mr-10">
                        <div class="h-full w-6 flex items-center justify-center">
                            <div class="h-full w-1 bg-blue-800 pointer-events-none"></div>
                        </div>
                        <div class="w-6 h-6 absolute top-1/2 -mt-3 rounded-full bg-indigo-400 shadow"></div>
                    </div>
                </div>
                <!-- right -->
                <div class="flex md:contents">
                    <div class="col-start-5 col-end-6 mr-10 md:mx-auto relative">
                        <div class="h-full w-6 flex items-center justify-center">
                            <div class="h-full w-1 bg-blue-800 pointer-events-none"></div>
                        </div>
                        <div class="w-6 h-6 absolute top-1/2 -mt-3 rounded-full bg-indigo-400 shadow"></div>
                    </div>
                    <div class="bg-indigo-400 col-start-6 col-end-10 p-4 rounded-xl my-4 mr-auto shadow-md">
                        <h3 class="font-semibold text-lg mb-1">Lorem ipsum</h3>
                        <p class="leading-tight text-justify">
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                            Vitae, facilis.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

definePageMeta({
    layout: 'default'
})
</script>