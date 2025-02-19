<template>
  <div>
    <q-card class="my-card" flat bordered>
      <q-card-section horizontal>
        <q-card-section class="col-4 flex flex-center">
          <q-img class="rounded-borders" src="https://cdn.quasar.dev/img/parallax2.jpg" />
        </q-card-section>
        <q-card-section class="q-pt-xs" horizontal>
          <div class="text-overline">Overline</div>
          <div class="text-h5 q-mt-sm q-mb-xs">Title</div>
          <div class="text-caption text-grey">
            {{ lorem }}
          </div>
        </q-card-section>
      </q-card-section>

      <q-separator />

      <q-card-actions>
        <q-btn flat round :icon="matFavorite" />
      </q-card-actions>
    </q-card>
  </div>
  <!-- <div class="div_14">
    <div class="div_15">
      <div class="div_16">
        <img
          class="svg_5"
          src="https://seal-img.nos-jd.163yun.com/obj/w5rCgMKVw6DCmGzCmsK-/58248204403/6852/2512/d11d/c25b4c23370af1a66134c18f1409dbe3.png"
        />
      </div>
      <div class="div_17">
        <div class="div_18">
          <span class="text_9"> 待办事项 </span
          ><img
            class="svg_6"
            src="https://seal-img.nos-jd.163yun.com/obj/w5rCgMKVw6DCmGzCmsK-/58248202609/5faf/e940/b17d/058bee446499a57a5dbc87830bf99d1f.png"
          />
        </div>
        <span class="text_10"> 您有待办事项需要处理 </span
        ><span class="text_11"> 共计: ¥53.49 </span>
      </div>
    </div>
    <div class="div_19">
      <div class="div_20">
        <img
          class="svg_7"
          src="https://seal-img.nos-jd.163yun.com/obj/w5rCgMKVw6DCmGzCmsK-/58248204445/0223/3a36/d516/4d3a053af5c9213818b3eee47a1fef5b.png"
        />
      </div>
      <div class="div_21">
        <div class="div_22">
          <span class="text_12"> 审批历史 </span
          ><img
            class="svg_8"
            src="https://seal-img.nos-jd.163yun.com/obj/w5rCgMKVw6DCmGzCmsK-/58248202609/5faf/e940/b17d/058bee446499a57a5dbc87830bf99d1f.png"
          />
        </div>
        <span class="text_13"> 审批历史记录查询 </span>
      </div>
    </div>
  </div> -->
</template>

<script setup lang="ts">
import { matFavorite } from '@quasar/extras/material-icons'

// 组件逻辑
const lorem =
  'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'
</script>

<style lang="sass" scoped>
.my-card
  width: 358.40000000000003vw
  max-width: 358.40000000000003px
</style>
