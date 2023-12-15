<template>
    <div>
            <header class="bg-[#000036]">
                <nav class="mx-auto flex max-w-7xl items-center justify-between p-6 lg:px-8" aria-label="Global">
                    <div class="flex lg:flex-1">
                    <a href="#" class="-m-1.5 p-1.5">
                        <span class="text-3xl font-bold text-slate-400">Rendi Firman Syah</span>
                    </a>
                    </div>
                    <div class="flex lg:hidden">
                    <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-slate-400">
                        <span class="sr-only">Open main menu</span>
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                        </svg>
                    </button>
                    </div>
                    <div class="hidden lg:flex lg:gap-x-12">
                        <a href="#profile" class="text-sm font-bold leading-6 text-slate-400">My Profile</a>
                        <a href="#skill" class="text-sm font-bold leading-6 text-slate-400">About Me</a>
                        <a href="#project" class="text-sm font-bold leading-6 text-slate-400">My Project</a>
                    </div>
                </nav>
            <!-- Mobile menu, show/hide based on menu open state. -->
            
            </header>

    </div>
</template>
<script>
    export default {
        name : 'NavbarUtama',
    }
</script>