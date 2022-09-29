<template>
  <div>
    <img class="avatar" :src="avatar"/>
    <img class="avatar" :src="avatarRelative"/>
  </div>
</template>

<script setup>
import avatar from "@/assets/avatar.jpg";
import avatarRelative from "../assets/avatar.jpg";
</script>

<style>
.avatar {
  width: 100px;
}
</style>