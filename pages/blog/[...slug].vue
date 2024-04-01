<script setup>
const { slug } = useRoute().params;
</script>

<template>
  <div>
    <ContentDoc :path="`/blog/${slug}`" v-slot="{ doc }">
      <section
        data-bs-version="5.1"
        class="article14 cid-u8fLVv9j0r"
        id="article14-2o"
      >
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-md-12 col-lg-10">
              <h3 class="mbr-section-title mbr-fonts-style display-2">
                <strong>{{ doc.title }}</strong>
              </h3>
              <h5 class="mbr-section-title mbr-fonts-style display-7">
                <strong>{{ doc.date }}</strong>
              </h5>
            </div>
          </div>
        </div>
      </section>
      <section
        data-bs-version="5.1"
        class="image03 cid-u8fMfrcI4v"
        id="image04-2p"
      >
        <div class="m-auto">
          <img :src="doc.thumbnail" :alt="doc.title" />
        </div>
      </section>
      <section
        data-bs-version="5.1"
        class="article12 cid-u8fMpe3KhD"
        id="article12-2q"
      >
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-md-12 col-lg-10">
              <ContentRenderer :value="doc"></ContentRenderer>
            </div>
          </div>
        </div>
      </section>
    </ContentDoc>
  </div>
</template>


