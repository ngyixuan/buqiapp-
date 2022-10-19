<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="h-20 w-full nav-bg flex align-middle justify-center">
    <div class="flex justify-center items-center font-bold">
      <div class="cursor-pointer text-white" href="">首页</div>
      <div class="cursor-pointer pl-28 text-white" href="">产品服务</div>
      <div class="cursor-pointer pl-28 text-white" href="">关于我们</div>
    </div>
  </div>
  <div class="relative w-full content-bg-1 flex justify-center items-center">
    <div class="flex flex-col">
      <div class="text-left">
        <div class="text-white text-6xl pb-6 font-bold">让有趣的灵魂都能</div>
        <div class="text-white text-6xl font-bold">不期而遇</div>
      </div>
      <div class="pt-6 text-white text-left" :style="{ width: 530 + 'px' }">
        不期APP是一款剧本杀社交APP，是以Web3.0概念为出发点，基于兴趣社交核心，以剧本杀多人扮演类社交活动为初始板块，设计开发的一款线下兴趣内容社交APP
      </div>
      <div class="rounded-full bg-white w-24 mt-6 py-2 cursor-pointer">
        立即下载
      </div>
      <div class="flex mt-6">
        <img class="pr-6" src="../assets/app-store.png" alt="" />
        <img src="../assets/googlePlay.png" alt="" />
      </div>
    </div>
    <div>
      <img src="../assets/content.png" alt="" />
    </div>
  </div>
  <div class="content-bg-2 flex flex-col mt-24 items-center">
    <div class="text-5xl font-bold">精准、高效、多元、专业</div>
    <div class="text-base font-bold mx-96 pt-16">
      以Web3.0概念为出发点，基于兴趣社交核心，以剧本杀多人扮演类社交活动为初始板块，设计开发的一款线下兴趣内容社交APP以剧本杀为着力点提出了：Web3.0社交体验，精准圈选人群，高效剧本组局三大功能核心点旨在为玩家带来优质的组局体验，为商家带来稳定的客户来源，为行业输送优质的DM人才，创造社交新模式
    </div>
    <div class="flex items-start mt-16">
      <div
        class="box-shadow p-4 flex mr-10 justify-start items-center flex-col h-72 w-72 bg-white box-shadow"
      >
        <div><img src="../assets/hand.png" alt="" /></div>
        <div class="py-4 text-2xl">内容玩法</div>
        <div class="">
          利用虚拟形象为基础，支持用户打造专属的剧本杀角色；创建虚拟形象的IP玩法，支持用户创建个人数字藏品，形成优质兴趣形象；引入文旅IP形成数字藏品解锁沉浸式体验玩法
        </div>
      </div>
      <div
        class="box-shadow p-4 flex mr-10 justify-start items-center flex-col h-72 w-72 bg-white box-shadow"
      >
        <div><img src="../assets/hand.png" alt="" /></div>
        <div class="py-4 text-2xl">匹配精准</div>
        <div class="">
          搭建用户标签体系，采用阶梯式推荐方式为商家圈选目标玩家进行推送，千人千面完成商家和玩家的精准匹配
        </div>
      </div>
      <div
        class="box-shadow p-4 flex mr-10 justify-start items-center flex-col h-72 w-72 bg-white box-shadow"
      >
        <div><img src="../assets/hand.png" alt="" /></div>
        <div class="py-4 text-2xl">专业垂直</div>
        <div class="">
          搭建商家评估体系和DM评估体系，形成行业专业化评估模式，提高玩家体验
        </div>
      </div>
      <div
        class="box-shadow p-4 flex justify-start items-center flex-col h-72 w-72 bg-white box-shadow"
      >
        <div><img src="../assets/hand.png" alt="" /></div>
        <div class="py-4 text-2xl">轻兴趣+重社交</div>
        <div class="">
          APP内创建兴趣群组，线上对话对线下兴趣活动起到支持作用，提高玩家间共鸣
        </div>
      </div>
    </div>
  </div>
  <div class="flex flex flex-row mt-52 items-start justify-center">
    <div class="flex flex-col pr-36">
      <div class="text-left">
        <div class="text-6xl pb-6 font-bold">多元话题</div>
        <div class="text-6xl font-bold">社区打造</div>
      </div>
      <div class="relative pt-6 text-left" :style="{ width: 300 + 'px' }">
        建立剧本杀讨论社区，引导用户剧本杀话题分享和玩本体验分享；玩家可自由选择关注DM及其他玩家，寻找志同道合，兴趣相投的玩家
        <div class="w-330 absolute top-28 left-0">
          <img src="../assets/shadow-box-1.png" alt="" />
        </div>
        <div class="w-330 absolute top-200px left-32">
          <img src="../assets/shadow-box-2.png" alt="" />
        </div>
        <div class="w-330 absolute top-250px left-0">
          <img class="" src="../assets/shadow-box-3.png" alt="" />
        </div>
      </div>
    </div>
    <div>
      <img class="pl-32" src="../assets/community.png" alt="" />
    </div>
  </div>
  <div class="flex flex flex-row mt-52 items-center justify-center">
    <div class="">
      <img src="../assets/content3.png" alt="" />
    </div>
    <div class="flex flex-col pr-36">
      <div class="text-left">
        <div class="text-6xl pb-6 font-bold">优质功能</div>
        <div class="text-6xl font-bold">技术支撑</div>
        <div class="pt-4" :style="{ width: 430 + 'px' }">
          通过交叉聚合形成不期专属兴趣标签人群包，为商家进行营销策略的圈选推荐。不期计划从剧本杀领域拓展到线下户外娱乐活动，为不同圈层的用户提供活动聚会入口和发声平台
        </div>
      </div>
    </div>
  </div>
  <div class="content-bg-3 flex flex-col justify-center items-center">
    <div class="text-base pb-6 text-white font-bold">你还在犹豫什么?</div>
    <div class="text-6xl pb-6 text-white font-bold">马上下载</div>
    <div class="flex mt-6">
      <img class="pr-6" src="../assets/app-store.png" alt="" />
      <img src="../assets/googlePlay.png" alt="" />
    </div>
  </div>
  <div class="mx-96 content-bg-4 flex justify-between items-center">
    <div class="text-left flex flex-col">
      <div class="font-bold text-xs py-2">产品</div>
      <div class="text-gray text-xs py-2">产品介绍</div>
      <div class="text-gray text-xs py-2">产品服务</div>
      <div class="text-gray text-xs py-2">用户政策</div>
    </div>
    <div class="flex flex-col text-left">
      <div class="pb-2">北京中嘉互娱科技有限公司</div>
      <div class="text-gray text-xs py-2">电话：13718603177</div>
      <div class="text-gray text-xs py-2">邮箱：13718603177@163.com</div>
    </div>
  </div>
  <div class="m-0 pb-12 text-gray text-xs">© 2021 - 2022 buqi. 版权所有</div>
</template>

<style scoped>
.nav-bg {
  background-color: #33c914;
}
.content-bg-1 {
  height: 1050px;
  background-color: #31c313;
}
.content-bg-2 {
  /* height: 1050px; */
}
.content-bg-3 {
  height: 436px;
  background-color: #31c313;
}
.content-bg-4 {
  height: 440px;
}
.box-shadow {
  box-shadow: 0px 5px 20px 0px rgba(69, 158, 255, 0.11);
}
.w-330 {
  width: 330px;
}
.top-200px {
  top: 200px;
}
.top-250px {
  top: 290px;
}
</style>
