<template>
    <div class=" grid grid-cols-1 gap-x-4 gap-y-3 sm:grid-cols-2 m-6">
        <div
            class="bg-[#00E0FF3D] rounded-lg w-full sm:max-w-[18rem] flex flex-col items-center gap-2 text-center px-[1rem] py-[0.5rem] pb-[1rem]">
            <img :src="medicineImage" alt="The medicine image" class="max-w-[150px]" />
            <h2 class="text-[#00588A] font-bold text-2xl">Medicines</h2>
            <p class="text-[#233E60] text-xs">Welcome to Heal Hub, where wellness meets convenience on your terms...</p>
            <button class="text-white font-bold bg-[#00588A] px-5 pb-2 pt-3 text-xs leading-none rounded-full">Visit
                Page</button>
        </div>
        <div
            class="bg-[#FFC7005E]  rounded-lg w-full sm:max-w-[18rem] flex flex-col items-center gap-2 text-center px-[1rem] py-[0.5rem] pb-[1rem]">
            <img :src="dineEaseImage" alt="The dine ease image" class="max-w-[150px]" />
            <h2 class="text-[#00000099] font-bold text-2xl">Dine Ease</h2>
            <p class="text-[#742D06] text-xs">Dine Ease, ultimate and best destination, Ease brings you your favorite
                flavors...</p>
            <button class="text-white font-bold bg-[#665E40] px-5 pb-2 pt-3 text-xs leading-none rounded-full">Visit
                Page</button>
        </div>
        <div
            class="bg-[#FF7A0078] rounded-lg w-full sm:max-w-[18rem] flex flex-col items-center gap-2 text-center px-[1rem] py-[0.5rem] pb-[1rem]">
            <img :src="findCarsImage" alt="The find cars image" class="max-w-[150px]" />
            <h2 class="text-[#00000099] font-bold text-2xl">Find Cars</h2>
            <p class="text-[#742D06] text-xs">AutoCrafters, where is Care. We take pride in delivering smooth care for
                your vehicle...</p>
            <button class="text-white font-bold bg-[#664D36] px-5 pb-2 pt-3 text-xs leading-none rounded-full">Visit
                Page</button>
        </div>
        <div
            class="bg-[#42FF005E]  rounded-lg w-full sm:max-w-[18rem] flex flex-col items-center gap-2 text-center px-[1rem] py-[0.5rem] pb-[1rem]">
            <img :src="electronicsImage" alt="The electronics image" class="max-w-[150px]" />
            <h2 class="text-[#00000099] font-bold text-2xl">Electronics</h2>
            <p class="text-[#742D06] text-xs">ElectroSwift brings you the latest gadgets at your fingertips, seamless
                tech experience.</p>
            <button class="text-white font-bold bg-[#4A6640] px-5 pb-2 pt-3 text-xs leading-none rounded-full">Visit
                Page</button>
        </div>
    </div>
</template>

<script setup>
import medicineImage from '@/images/medicine.png'
import electronicsImage from '@/images/electronics.png'
import findCarsImage from '@/images/find-cars.png'
import dineEaseImage from '@/images/dine-ease.png'
</script>