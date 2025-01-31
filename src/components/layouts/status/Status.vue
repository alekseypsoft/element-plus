<script setup lang="ts">

</script>

<template>
  <el-row>
    <el-col>
      <el-input
          v-model="input4"
          style="width: 240px"
          placeholder="Type something"
      >
        <template #prefix>
          <img src="../../../assets/status/search.svg" alt=""/>
        </template>
      </el-input>
    </el-col>
  </el-row>
  <el-row>
    <el-col :span="6">
      <el-row>
        <el-button><img src="../../../assets/status/play.svg" alt=""/>Telegram-бот</el-button>
      </el-row>
      <el-row><span>Запущен</span></el-row>
    </el-col>
    <el-col :span="6">
      <el-button><img src="../../../assets/status/left-icon.svg" alt=""/></el-button>
    </el-col>
  </el-row>
  <el-row>
    <el-col :span="6">
      <el-row>
        <el-row>
          <el-button><img src="../../../assets/status/folder.svg" alt=""/>Сайт</el-button>
        </el-row>
        <el-row><span>Запущен</span></el-row>
      </el-row>
    </el-col>
    <el-col :span="6">
      <el-button><img src="../../../assets/status/left-icon.svg" alt=""/></el-button>
    </el-col>
  </el-row>
  <el-row>
    <el-col :span="6">
      <el-row>
        <el-row>
          <el-button><img src="../../../assets/status/play.svg" alt=""/>Новый сценарий</el-button>
        </el-row>
        <el-row><span>Запущен</span></el-row>
      </el-row>
    </el-col>
    <el-col :span="6">
      <el-button><img src="../../../assets/status/left-icon.svg" alt=""/></el-button>
    </el-col>
  </el-row>
  <el-row>
    <el-col :span="6">
      <el-row>
        <el-row>
          <el-button><img src="../../../assets/status/play.svg" alt=""/>Регистрация</el-button>
        </el-row>
        <el-row><span>Запущен</span></el-row>
      </el-row>
    </el-col>
    <el-col :span="6">
      <el-button><img src="../../../assets/status/left-icon.svg" alt=""/></el-button>
    </el-col>
  </el-row>
  <el-row>
    <el-col :span="6">
      <el-row>
        <el-row>
          <el-button><img src="../../../assets/status/play.svg" alt=""/>API: Список объявлений</el-button>
        </el-row>
        <el-row><span>Запущен</span></el-row>
      </el-row>
    </el-col>
    <el-col :span="6">
      <el-button><img src="../../../assets/status/left-icon.svg" alt=""/></el-button>
    </el-col>
  </el-row>

</template>

<style scoped>

</style>
<script lang="ts" setup></script>
