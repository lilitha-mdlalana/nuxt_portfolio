<script setup lang="ts">
import type { QueryBuilderParams } from "@nuxt/content/dist/runtime/types";
const query: QueryBuilderParams = {
  path: "/blog",
  sort: [{ date: -1 }],
};
</script>

<template>
  <section data-bs-version="5.1" class="news08 cid-u8fJMhNm4g" id="news08-2j" data-aos="fade-right"
    data-aos-duration="2000">
    <div class="container">
      <div class="row justify-content-center mb-5">
        <div class="col-12 content-head">
          <div class="mbr-section-head">
            <h4
              class="mbr-section-title mbr-fonts-style align-center mb-0 display-2"
            >
              <strong>My thoughts....</strong>
            </h4>
          </div>
        </div>
      </div>
      <ContentList :query="query" path="/blog" v-slot="{ list }">
        <div class="row">
          <SharedArticleCard
            v-for="post in list"
            :key="post._path"
            :articleTitle="post.title"
            :articleGenre="post.tag"
            :articleImageUrl="post.thumbnail"
            :articleUrl="post.slug"
          />
        </div>
      </ContentList>
    </div>
  </section>

  <SectionContact />
</template>
