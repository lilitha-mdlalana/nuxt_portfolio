<template>
    <section class="blog-image">
        <div class="m-auto">
            <ContentSlot :use="$slots.default" />
        </div>
    </section>
</template>

<style>
.blog-image :deep(img){
    max-height: 250px;
}
</style>
