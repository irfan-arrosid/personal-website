<template>
    <section
        class="header bg-[conic-gradient(at_bottom_right,_var(--tw-gradient-stops))] from-blue-700 via-blue-800 to-gray-900 px-2.5 sm:px-5 lg:px-10">
        <div class="container mx-auto relative">
            <Navbar />
        </div>
        <div class="container mx-auto relative">
            <div class="flex flex-col justify-center" style="height: 500px">
                <h1 class="text-white font-bold text-7xl tracking-wide w-full py-1">Irfan Arrosid</h1>
                <p class="text-white text-2xl w-full py-1">Full-Stack Developer from Indonesia</p>
                <div class="flex flex-wrap gap-6 mt-8">
                    <a class="bg-white px-5 py-2 rounded-lg" href="#">LinkedIn</a>
                    <a class="border-solid border-2 border-white text-white px-5 py-2 rounded-lg" href="#">About</a>
                </div>
            </div>
        </div>
    </section>
    <section class="projects bg-[#272829] py-10 px-2.5 sm:px-5 lg:px-10">
        <div class="container mx-auto relative">
            <h1 class="text-white font-bold text-3xl pb-7">Projects</h1>
            <div class="card grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
                <div class="border-solid border-[1px] border-[#7c8297] px-5 py-5 rounded-lg w-full">
                    <div class="text-white font-bold text-lg pb-2 hover:underline"><a
                            href="https://github.com/irfan-arrosid/startup-aid">Start-Up Aid</a></div>
                    <div class="text-[#7c8297] pb-2">Crowdfunding website built with Golang and NuxtJS</div>
                    <div class="tech-stack flex gap-4">
                        <div class="tech flex items-center gap-2">
                            <div class="h-[14px] w-[14px] bg-[#41b883] rounded-[50%]"></div>
                            <div class="text-[#7c8297] text-sm">Vue.js</div>
                        </div>
                        <div class="tech flex items-center gap-2">
                            <div class="h-[14px] w-[14px] bg-[#00ADD8] rounded-[50%]"></div>
                            <div class="text-[#7c8297] text-sm">Go</div>
                        </div>
                    </div>
                </div>
                <div class="border-solid border-[1px] border-[#7c8297] px-5 py-5 rounded-lg w-full">
                    <div class="text-white font-bold text-lg pb-2 hover:underline"><a
                            href="https://github.com/irfan-arrosid/goshop-api">GoShop API</a></div>
                    <div class="text-[#7c8297] pb-2">A Backend Developer's Final Project of Virtual Internship Experience by
                        Evermos x Rakamin</div>
                    <div class="tech-stack flex gap-4">
                        <div class="tech flex items-center gap-2">
                            <div class="h-[14px] w-[14px] bg-[#00ADD8] rounded-[50%]"></div>
                            <div class="text-[#7c8297] text-sm">Go</div>
                        </div>
                    </div>
                </div>
                <div class="border-solid border-[1px] border-[#7c8297] px-5 py-5 rounded-lg w-full">
                    <div class="text-white font-bold text-lg pb-2 hover:underline"><a
                            href="https://github.com/irfan-arrosid/vehicle-rest-api">Vehicle API</a></div>
                    <div class="text-[#7c8297] pb-2">Vehicle API using REST</div>
                    <div class="tech-stack flex gap-4">
                        <div class="tech flex items-center gap-2">
                            <div class="h-[14px] w-[14px] bg-[#026e00] rounded-[50%]"></div>
                            <div class="text-[#7c8297] text-sm">Node.js</div>
                        </div>
                    </div>
                </div>
                <div class="border-solid border-[1px] border-[#7c8297] px-5 py-5 rounded-lg w-full">
                    <div class="text-white font-bold text-lg pb-2 hover:underline"><a
                            href="https://github.com/irfan-arrosid/imagen-ai">Imagen AI</a></div>
                    <div class="text-[#7c8297] pb-2">Image generator website (Dall-E Clone) built with MERN stack</div>
                    <div class="tech-stack flex gap-4">
                        <div class="tech flex items-center gap-2">
                            <div class="h-[14px] w-[14px] bg-[#149eca] rounded-[50%]"></div>
                            <div class="text-[#7c8297] text-sm">React.js</div>
                        </div>
                        <div class="tech flex items-center gap-2">
                            <div class="h-[14px] w-[14px] bg-[#026e00] rounded-[50%]"></div>
                            <div class="text-[#7c8297] text-sm">Node.js</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>