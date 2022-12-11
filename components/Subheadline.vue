<template>
    <div class="title">
        <h2>
            {{ title }}
            <span class="subtitle position-relative">                
                {{ titleStyle }}
                <img :src="ornaments" alt="Header Style" class="position-absolute">
            </span>             
        </h2>        
    </div>
</template>

<script>

import subheaderFontStyle from '~/assets/svg/subheader-font-style.svg';

export default {
    name: 'Subheadline',
    props: {
        title: {
            type: String,
            required: false,
            default: () => ""            
        },
        ornaments: {
            type: String,
            required: false,
            default: () => subheaderFontStyle
        },
        titleStyle: {
            type: String,
            required: false,
            default: () => ""
        }
    }
}
</script>

<style lang="scss" scoped>

@import '../assets/scss/style.scss';
.title {
    h2 {
        @include font($base-font,$heading-2,$font-weight-3,$line-height-2);
        color: $black-1000;
        margin-bottom: 10px !important;
        .subtitle {
            img {
                left: 0;
                bottom: 8px;
            }            
        }
    }    
}

</style>