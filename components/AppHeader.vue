<template>
    <div>
        <nav class="bg-teal-900 p-2 mt-0 w-full">
            <div class="container mx-auto flex flex-wrap items-center">
                <div
                    class="flex w-full md:w-1/2 justify-center md:justify-start text-white font-extrabold"
                >
                    <a
                        class="text-white no-underline hover:text-white hover:no-underline"
                        href="#"
                    >
                        <svg
                            class="w-12 h-12 text-white"
                            viewBox="0 0 480 480"
                            xmlns="http://www.w3.org/2000/svg"
                            stroke="currentColor"
                        >
                            <path
                                fill="#fff"
                                d="M16 48H0v384h48V315.312l16-16V104c0-25.896-20.968-56-48-56zm32 244.688l-16 16V416H16V64c17.232 0 32 22 32 40v188.688zM472 48a8 8 0 00-8 8v72h-16V56a8 8 0 00-16 0v72h-16V56a8 8 0 00-16 0v136h16v240h48V192h16V56a8 8 0 00-8-8zm-8 128h-16v240h-16V176h-16v-32h48v32zM240 80c-88.366 0-160 71.634-160 160s71.634 160 160 160 160-71.634 160-160c-.101-88.324-71.676-159.899-160-160zm0 304c-79.529 0-144-64.471-144-144S160.471 96 240 96s144 64.471 144 144c-.093 79.491-64.509 143.907-144 144z"
                            />
                            <path
                                fill="#fff"
                                d="M240 143.72c-53.174 0-96.28 43.106-96.28 96.28s43.106 96.28 96.28 96.28 96.28-43.106 96.28-96.28c-.062-53.148-43.132-96.218-96.28-96.28zm0 176.56c-44.337 0-80.28-35.943-80.28-80.28s35.943-80.28 80.28-80.28 80.28 35.943 80.28 80.28c-.053 44.315-35.965 80.227-80.28 80.28z"
                            />
                        </svg>
                    </a>
                </div>
                <div
                    class="flex w-full pt-2 content-center justify-between md:w-1/2 md:justify-end"
                >
                    <ul
                        class="list-reset flex justify-between flex-1 md:flex-none items-center"
                    >
                        <li class="mr-3">
                            <a
                                class="inline-block py-2 px-4 text-white no-underline"
                                href="#"
                                >Order</a
                            >
                        </li>
                        <li class="mr-3">
                            <a
                                class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:text-underline py-2 px-4"
                                href="#"
                                >Login</a
                            >
                        </li>
                        <li class=" md:mr-0  mr-3 ">
                            <a
                                class="bg-white rounded-md inline-block text-gray-600 no-underline hover:text-gray-200 hover:text-underline py-2 px-4"
                                href="#"
                                >Sign up</a
                            >
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <div class="hero">
            <div
                class="container mx-auto flex flex-col md:flex-row items-center  md:my-0"
            >
                <!--Left Col-->
                <div
                    class="mt-10 flex flex-col w-full justify-center items-start pt-12 sm:pt-0 px-6 pb-24 md:px-2 "
                >
                    <p class="uppercase tracking-loose text-gray-400">Foodie</p>
                    <h1 class="font-bold text-3xl my-4 text-white">
                        My online restaurant
                    </h1>
                    <p class="leading-normal mb-4 text-teal-600 hidden">
                        Order food from favorite restaurants near you.
                    </p>
                    <button
                        class="bg-teal-700 hover:bg-teal-800 text-gray-100 hover:text-white rounded-md shadow hover:shadow-lg py-2 px-20 font-light  border-none border-gray-900 hover:border-transparent text-xl outline-none focus:outline-none"
                    >
                        Find a restaurant
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style scoped>
.hero {
    width: 100%;
    height: 80vh;
    padding: 40px;
    margin-bottom: 60px;
    overflow: hidden;
    background-size: cover !important;
    background: radial-gradient(
            ellipse at center,
            rgba(0, 0, 0, 0) 0%,
            rgba(0, 0, 0, 0) 37%,
            rgba(0, 0, 0, 0.65) 100%
        ),
        url(~assets/headerimg.jpg) no-repeat center center scroll;
}
.nav-color {
    background: #082c40;
}
</style>
