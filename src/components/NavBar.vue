<template>
    <div class="navbar text-xl">
        <div class="navbar-start">
            <div class="dropdown">
                <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h8m-8 6h16" />
                    </svg>
                </div>
                <ul tabindex="0"
                    class="menu menu-sm dropdown-content  rounded-box z-[1] mt-3 w-[13rem] p-2 shadow-xl bg-[#FAFAFA] flex flex-col gap-3">
                    <li><a class="py-2">Home</a></li>
                    <li><a class="py-2">About Us</a></li>
                    <li><a class="py-2">Contact Us</a></li>
                </ul>
            </div>
            <h1 class="btn btn-ghost text-xl cursor-pointer ">
                {{ logo }}
            </h1>
        </div>
        <div class="navbar-center hidden lg:flex">
            <ul class="menu menu-horizontal px-1">
                <li><a>Home</a></li>
                <li><a>About Us</a>
                </li>
                <li><a>Contact Us</a></li>
            </ul>
        </div>
        <div class="navbar-end">
            <button class="rounded-full border-[#444444] py-2 px-4 border-solid border-[2px]">Login</button>
        </div>
    </div>
</template>

<script setup>
defineProps({
    logo: String
})
</script>
