<template>
    <section class="weprovide">
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
        </div>
    </section>
</template>

<script>

export default {
    name: 'WhatWeProvide',
    components: {
        "subheadline": () => import("@/components/Subheadline"),
    }
}
</script>