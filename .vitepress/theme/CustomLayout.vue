<template>
    <DefaultTheme.Layout>
        <template #home-features-after>
            <Home />
        </template>
        <template #not-found>
            <NotFound />
        </template>
        <template #doc-before>
            <DocsHeader />
        </template>
    </DefaultTheme.Layout>
</template>

<script setup lang="ts">
import DefaultTheme from 'vitepress/theme'
import NotFound from './layouts/NotFound.vue'
import Home from './layouts/Home.vue'
import DocsHeader from './layouts/DocsHeader.vue'
</script>