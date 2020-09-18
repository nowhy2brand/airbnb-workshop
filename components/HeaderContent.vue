<template>
    <div class="h-full w-screen">
        <div class="relative">
            <img :srcset="imgURL" class="w-full h-screen object-cover"/>
            <div class="absolute top-0 h-full">
                <div class="flex h-full pl-16">
                    <div class="my-auto w-96">
                        <div class="text-5xl text-white font-poppins tracking-wide font-medium">
                            {{heading1}}
                        </div>
                        <div class="text-xl text-white font-poppins tracking-wide font-thin mt-6">
                            {{heading2}}
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    props: {
        imgURL: {
            type: String,
            default:''
        },
        heading1: {
            type: String,
            default: 'Heading Content'
        },
        heading2 : {
            type: String,
            default: 'Heading 2 Content'
        }
    }
}
</script>