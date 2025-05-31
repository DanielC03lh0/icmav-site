<template>
    <div class="flex flex-wrap justify-center gap-6 px-6 md:px-10 lg:px-20" data-aos="fade-up" data-aos-delay="100">
        <!-- MB WAY (using a generic mobile phone icon) -->
        <a href="#mbway"
            class="btn btn-success btn-lg rounded-full btn-xl flex items-center space-x-3 px-8 py-4 transition-transform hover:scale-105">
            <!-- “fa-mobile-alt” is a close stand-in for MB WAY -->
            <i class="fas fa-mobile-alt text-2xl"></i>
            <span class="text-lg font-semibold">MB WAY</span>
        </a>

        <!-- IBAN Transfer (using a “bank/university” icon as a stand-in for IBAN) -->
        <a href="#iban"
            class="btn btn-secondary btn-lg flex rounded-full btn-xl items-center space-x-3 px-8 py-4 transition-transform hover:scale-105">
            <i class="fas fa-university text-2xl"></i>
            <span class="text-lg font-semibold">Transferência (IBAN)</span>
        </a>

        <!-- PayPal (official PayPal brand icon) -->
        <a href="https://paypal.me/icmav" target="_blank"
            class="btn btn-primary btn-lg flex rounded-full btn-xl items-center space-x-3 px-8 py-4 transition-transform hover:scale-105">
            <i class="fab fa-paypal text-2xl"></i>
            <span class="text-lg font-semibold">PayPal</span>
        </a>

    </div>
</template>