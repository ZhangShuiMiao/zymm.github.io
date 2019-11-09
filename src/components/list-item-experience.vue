<template>
  <ListItem class="list-item-experience">
    <div class="heading">
      <span class="company" contenteditable="true">{{ company }}</span>
      <span class="job" contenteditable="true">{{ job }}</span>
      <span class="date" contenteditable="true">{{ date }}</span>
    </div>
    <div style="white-space: pre-wrap">
      <slot>
        <pre contenteditable="true">
        主要负责商城模块的功能和效果的开发，更新。
        细分为：
        1.参与小组会议，根据需求讨论解决方案;
        2.根据设计图进行网页排版;
        3.与后台人员协商，并完成数据存取和绑定;
        4.js动态效果制作;
        5.单元测试代码的编写;
        6.验收测试代码的编写;
        7.兼容性优化;
        8.性能调优;
        </pre>
      </slot>
    </div>
  </ListItem>
</template>
<script>
  import ListItem from '@/components/list-item'

  export default {
    name: 'ListItemExperience',
    components: {
      ListItem
    },
    props: {
      company: {
        type: String,
        default: '知乎'
      },
      job: {
        type: String,
        default: '北京爱奇艺科技有限公司'
      },
      date: {
        type: String,
        default: '2016.09 — 2018.01'
      }
    }
  }
</script>
<style lang="less">
  .list-item-experience {
    .heading {
      font-size: 18px;
      font-weight: bold;
      display: flex;
      justify-content: space-between;
      margin-top: 12px;
      white-space: pre-wrap;
      .company {
        width: 40%
      }
      .job {
        width: 35%;
      }
      .date {
        width: 25%;
        text-align: right;
      }
    }
  }
</style>
