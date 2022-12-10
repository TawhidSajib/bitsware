<template>
    <section class="header position-relative">
            <img src="~/assets/svg/header-ornament-1.svg" alt="Header Ornament" class="position-absolute header__top--1">
            <img src="~/assets/svg/header-ornament-1.svg" alt="Header Ornament" class="position-absolute header__bottom--1">
            <img src="~/assets/svg/header-ornament-2.svg" alt="Header Ornament" class="position-absolute header__bottom--2">
        <div class="container">
            <div class="row">
                <div class="col-lg-7">
                    <h2>Build your</h2>
                    <h1>
                        <span class="position-relative">
                            <img src="~/assets/svg/header-font-style.svg" alt="Header Font" class="position-absolute start-0 bottom-0">
                            Offshorey
                        </span> Team
                    </h1>
                    <h3>First &amp; Reasonable Price</h3>
                    <p>Bitsware is a leading design agency based in USA. We help startups &amp; Fortune 30+ companies delight humans on the other side of the screen.</p>
                    <NuxtLink to="/" class="btn-blue">
                        <div class="d-flex align-items-center">
                            View Project<img src="~/assets/svg/arrow-circle-right.svg" alt="">
                        </div>
                    </NuxtLink>
                </div>
                <div class="col-lg-5 d-flex">
                    <img src="~/assets/svg/header-banner.svg" alt="Header Banner" class="d-block mx-auto img-fluid">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Header'
}
</script>