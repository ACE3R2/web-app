<script setup>
import ListItem from "./ListItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
import { useI18n } from 'vue-i18n'
const { t } = useI18n({
  //inheritLocale: true,
  //useScope: 'local'
})
</script>

<template>
  <ListItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>  {{t('member_page.Chris_general')}}</template>
    <!-- {{t('member_page.Eric_detail')}} -->
  </ListItem>

  <ListItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>{{t('member_page.Simon_general')}}</template>
    <!-- {{t('member_page.Anthony_detail')}} -->
  </ListItem>

  <ListItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>{{t('member_page.Benjamin_general')}}</template>
    <!-- {{t('member_page.Amaan_detail')}} -->
  </ListItem>

  <ListItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>{{t('member_page.Alice_general')}}</template>
    <!-- {{t('member_page.Dylan_detail')}} -->
  </ListItem>

  <ListItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>{{t('member_page.Aidan_general')}}</template>
    <!-- {{t('member_page.Sam_detail')}} -->
  </ListItem>

  <ListItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>{{t('member_page.Aaron_general')}}</template>
   <!-- {{t('member_page.Yuk_Ting_detail')}} -->
  </ListItem>
</template>
