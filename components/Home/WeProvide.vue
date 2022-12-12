<template>
    <section class="weprovide position-relative">
        <img :src="plus_01" alt="Ornaments" class="position-absolute weprovide__ornament1">
        <img :src="plus_02" alt="Ornaments" class="position-absolute weprovide__ornament2">
        <img :src="round_01" alt="Ornaments" class="position-absolute weprovide__ornament3">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <subheadline
                        title="What We"
                        titleStyle="Provide"
                    ></subheadline>
                    <h3>We make the people and interface interaction more intensive and exiting.</h3>
                </div>
            </div>
            <div class="weprovide__services">
                <div class="row">
                    <div class="col-lg-3">
                        <div class="weprovide__services--block text-center">
                            <h4>Offshore Team</h4>
                            <img :src="offshore_team" alt="Offshore Team" class="d-block mx-auto img-fluid">
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed</p>
                            <div class="weprovide__services--btn">
                                <NuxtLink to="/" class="btn-white">
                                    <div class="d-flex align-items-center">
                                        Read More
                                        <span class="weprovide__services--read">
                                            <img :src="read_more" alt="Read more">
                                            <img :src="read_more_hover" alt="Read more">
                                        </span>
                                    </div>
                                </NuxtLink>                                
                            </div>                                
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="weprovide__services--block text-center">
                            <h4>Design &amp; Development</h4>
                            <img :src="design_development" alt="Design and Development" class="d-block mx-auto img-fluid">
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed</p>
                            <div class="weprovide__services--btn">
                                <NuxtLink to="/" class="btn-white">
                                    <div class="d-flex align-items-center">
                                        Read More
                                        <span class="weprovide__services--read">
                                            <img :src="read_more" alt="Read more">
                                            <img :src="read_more_hover" alt="Read more">
                                        </span>                                        
                                    </div>
                                </NuxtLink>                                
                            </div>                                
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="weprovide__services--block text-center">
                            <h4>Software Development</h4>
                            <img :src="software_development" alt="Software Development" class="d-block mx-auto img-fluid">
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed</p>
                            <div class="weprovide__services--btn">
                                <NuxtLink to="/" class="btn-white">
                                    <div class="d-flex align-items-center">
                                        Read More
                                        <span class="weprovide__services--read">
                                            <img :src="read_more" alt="Read more">
                                            <img :src="read_more_hover" alt="Read more">
                                        </span>                                        
                                    </div>
                                </NuxtLink>                                
                            </div>                                
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="weprovide__services--block text-center">
                            <h4>Mobile Application</h4>
                            <img :src="mobile_application" alt="Mobile Application" class="d-block mx-auto img-fluid">
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed</p>
                            <div class="weprovide__services--btn">
                                <NuxtLink to="/" class="btn-white">
                                    <div class="d-flex align-items-center">
                                        Read More
                                        <span class="weprovide__services--read">
                                            <img :src="read_more" alt="Read more">
                                            <img :src="read_more_hover" alt="Read more">
                                        </span>                                        
                                    </div>
                                </NuxtLink>                                
                            </div>                                
                        </div>
                    </div>                                                          
                </div>
            </div>
        </div>
    </section>
</template>

<script>

import offShoreTeam from '~/assets/svg/offshore-team.svg';
import softwareDevelopment from '~/assets/svg/software-development.svg';
import designDevelopment from '~/assets/svg/design-development.svg';
import mobileApplication from '~/assets/svg/mobile-application.svg';
import readMore from '~/assets/svg/read-more.svg';
import readMoreHover from '~/assets/svg/read-more-hover.svg';
import plus01 from '~/assets/svg/plus01.svg';
import plus02 from '~/assets/svg/plus02.svg';
import round01 from '~/assets/svg/round01.svg';

export default {
    name: 'WhatWeProvide',
    components: {
        "subheadline": () => import("@/components/Subheadline"),
    },
    data() {
        return {
            offshore_team: offShoreTeam,
            software_development: softwareDevelopment,
            design_development: designDevelopment,
            mobile_application: mobileApplication,
            read_more: readMore,
            read_more_hover: readMoreHover,
            plus_01: plus01,
            plus_02: plus02,
            round_01: round01
        }
    }
}
</script>