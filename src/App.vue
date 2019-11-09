<template>
  <div id="app">
    <div class="resume">
      <div class="left">
        <Brief></Brief>
        <ContextList title="CONTACT" :icon="require('@/assets/title-contact.png')">
          <ListItemInfo title="18827334492"
                        :image="require('@/assets/contact-phone.png')"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title="1418556630@qq.com"
                        :image="require('@/assets/contact-mail.png')"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title=Z先生
                        :image="require('@/assets/social-wechat.png')"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title="1418556630"
                        :image="require('@/assets/social-qq.png')"
                        slot="listItem">
          </ListItemInfo>
        </ContextList>
        <ContextList title="SOCIAL" :icon="require('@/assets/title-contact.png')">
          <ListItemInfo title="ivuex.gitee.io"
                        :image="require('@/assets/social-github.png')"
                        slot="listItem">
          </ListItemInfo>
          
          
         
          
        </ContextList>
        <ContextList title="QUOTATION" :icon="require('@/assets/title-contact.png')">
          <ListItemInfo title="真正的程序员认为自己比用户更明白用户需要什么。"
                        :showIcon="false"
                        slot="listItem"
          >
          </ListItemInfo>
          <ListItemInfo title="看再多的书是学不全脚本的，要多实践。"
                        :showIcon="false"
                        slot="listItem"
                        >
          </ListItemInfo>
          <ListItemInfo title="Vue很简单。"
                        :showIcon="false"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title="一个好汉三个帮，程序员同样如此。"
                        :showIcon="false"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title="信念和目标必须永远洋溢在程序员内心。"
                        :showIcon="false"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title="看得懂的书，请仔细看；看不懂的书，请硬着头皮看。"
                        :showIcon="false"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title="软件在能够复用前必须先能用。"
                        :showIcon="false"
                        slot="listItem">
          </ListItemInfo>
          <ListItemInfo title="记录下在和别人交流时发现的自己忽视或不理解的知识点。"
                        :showIcon="false"
                        slot="listItem">
          </ListItemInfo>
        </ContextList>
      </div>
      <div class="right">
        <ContextList class="context-list" title="关于我">
          <ListItemAbout slot="listItem"></ListItemAbout>
        </ContextList>
        <ContextList title="技能">
          <ListItemSkill slot="listItem" title="JavaScript" :percent="80"></ListItemSkill>
          <ListItemSkill slot="listItem" title="Html5 + css3" :percent="60"></ListItemSkill>
          <ListItemSkill slot="listItem" title="Vue" :percent="70"></ListItemSkill>
          <ListItemSkill slot="listItem" title="React" :percent="60"></ListItemSkill>
          <ListItemSkill slot="listItem" title="Linux" :percent="70"></ListItemSkill>
        </ContextList>
        <ContextList title="教育经历">
          <ListItemEducation slot="listItem" school="武昌工学院" major="本科" date="2018年毕业"></ListItemEducation>
          
        </ContextList>
        <ContextList title="工作经验">
          <ListItemExperience slot="listItem" company="广州景天通讯科技公司" job="前端开发工程师" date="2017.09 — 至今">
            主要负责商城模块的功能和效果的开发，更新。
            细分为：
            1、参与小组会议，根据需求讨论解决方案;
            2、根据设计图进行网页排版;
            3、与后台人员协商，并完成数据存取和绑定;
            4、js动态效果制作;
            5、单元测试代码的编写;
            6、验收测试代码的编写;
            7、兼容性优化;
            8、性能调优;
          </ListItemExperience>
          <ListItemExperience slot="listItem" company="京东集团商城研发部" job="前端开发工程师" date="2015.02 — 2016.09">
            主要负责商城模块的功能和效果的开发，更新。
            细分为：
            1、根据设计图进行网页排版;
            2、数据存取和绑定;
            3、js动态效果制作;
            4、兼容性优化;
          </ListItemExperience>
          <ListItemExperience slot="listItem" company="搜狐集团" job="linux运维工程师" date="2012.02 — 2014.06">
            主要职责:
            1、负责运维工作的规划、部署、日志分析、故障排除、监控、数据备份、容灾备份、数据迁移等工作；
            2、负责客户私有云平台的规划、搭建工作；
            3、协助业务部门完成线上系统的部署实施、性能调优、数据库调优工作；
            4、负责基于容器化的管理平台，完成各应用的日常部署、管理、运维等工作；
            5、完善应用系统架构、绘制拓扑图、日常运维等相关文档。
          </ListItemExperience>
          <ListItemExperience slot="listItem" company="重庆熙焰科技有限公司" job="网络设备及pc维护人员" date="2009.03 — 2011.06">
            主要职责:
            1、确保交换机，路由器正常运行;
            2、负责公司所有电脑进行杀毒，备份，还原，系统更新;
            3、对公司其他设备进行维护，送修;
            4、负责公司专有软件安装，调试;
          </ListItemExperience>
          <ListItemExperience slot="listItem" company="重庆网尔科技有限公司" job="技术支持" date="2007.08 — 2009.02">
            主要职责:
            1、PC硬件和软件安装维护;
            2、其它任务，弱电系统包括：应急服务、常驻服务、巡检服务;
            3、与人沟通能力强，能吃苦耐劳，勇于承担压力;
            4、完成上级领导和业主交办的其他工作任务;
          </ListItemExperience>
        </ContextList>
      </div>
    </div>
    <!--<div class="guide">-->
      <!--<ul>-->
        <!--<li>-->
          <!--<img src="./assets/guide_click_left.png" height="60" width="60" alt="">-->
          <!--<div class="desc">-->
            <!--<h3>Click On Content</h3>-->
            <!--<p>To edit text or image</p>-->
          <!--</div>-->
        <!--</li>-->
        <!--<li>-->
          <!--<img src="./assets/guide_click_right.png" height="60" width="60" alt="">-->
          <!--<div class="desc">-->
            <!--<h3>Right Click On Item</h3>-->
            <!--<p>To delete item</p>-->
          <!--</div>-->
        <!--</li>-->
        <!--<li>-->
          <!--<img src="./assets/guide_add.png" height="60" width="60" alt="">-->
          <!--<div class="desc">-->
            <!--<h3>Click Add Button</h3>-->
            <!--<p>To add item</p>-->
          <!--</div>-->
        <!--</li>-->
        <!--<li>-->
          <!--<img src="./assets/guide_sai.png" alt="">-->
          <!--<div class="desc">-->
            <!--<h3>Click Save Button</h3>-->
            <!--<p>To download resume as image</p>-->
          <!--</div>-->
        <!--</li>-->
      <!--</ul>-->
    <!--</div>-->
    <!--<button class="sap" @click="saveAsImage">Save as Image</button>-->
    <!--<div class="footer">-->
      <!--<a href="https://github.com/luosijie/vue-resume" target="_blank">-->
        <!--<img src="./assets/social-github.png" height="36" width="36" alt="">-->
      <!--</a>-->
      <!--vue-resume designed by <a href="https://github.com/luosijie">Jesse Luo</a>-->
    <!--</div>-->
  </div>
</template>

<script>
  import ContextList from '@/components/context-list'
  import ListItemAbout from '@/components/list-item-about'
  import ListItemSkill from '@/components/list-item-skill'
  import ListItemEducation from '@/components/list-item-education'
  import ListItemExperience from '@/components/list-item-experience'
  import ListItemInfo from '@/components/list-item-info'
  import html2canvas from '@/assets/js/html2canvas.js'
  import FileSaver from 'file-saver'
  import Brief from '@/components/brief'

  export default {
    name: 'app',
    components: {
      ContextList,
      ListItemAbout,
      ListItemSkill,
      ListItemEducation,
      ListItemExperience,
      ListItemInfo,
      Brief
    },
    methods: {
      saveAsImage: function () {
        let resume = document.querySelector('.resume')
        html2canvas(resume).then(function (canvas) {
          canvas.toBlob(function (blob) {
            FileSaver.saveAs(blob, 'Resume.png')
          })
        })
      }
    }
  }
</script>

<style lang="less">
  body {
    padding: 0;
    margin: 0;
  }

  ul {
    padding: 0;
    margin: 0;
    li {
      list-style: none;
    }
  }

  p {
    margin: 0 0 12px 0;
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: left;
    color: #2c3e50;
    background-color: white;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 40px 0;
    .resume {
      width: 1247px;
      /*height: 1754px;*/
      border: 1px solid #dad8d7;
      background-color: white;
      overflow: hidden;
      .left {
        width: 380px;
        height: 100%;
        box-sizing: border-box;
        float: left;
        background-color: #fdfefe;
        .brief {
          height: 630px;
          background-color: #f6f7f7;
          .avatar {
            height: 500px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            & > .img {
              margin-bottom: 45px;
            }
            .name {
              font-size: 32px;
              margin-bottom: 14px;
            }
            .job {
              font-size: 24px;
              color: #555;
              margin-bottom: 16px;
            }
            .location {
              display: flex;
              align-itmes: center;
              .location-name {
                font-size: 20px;
                font-weight: bold;
                margin-left: 10px;
              }
            }
          }
          .info {
            height: 128px;
            ul {
              height: 100%;
              display: flex;
              border-top: 1px solid #dad8d7;
              border-bottom: 1px solid #dad8d7;
              li:not(:last-child) {
                border-right: 1px solid #dad8d7;
              }
              li {
                width: 33.3333333%;
                display: flex;
                flex-direction: column;
                justify-content: center;
                text-align: center;
                .value {
                  margin-bottom: 10px;
                  font-size: 24px;
                  font-weight: bold;
                }
                .key {
                  font-size: 16px;
                  font-weight: bold;
                  color: #555;
                }
              }
            }
          }
        }
      }
      .right {
        box-sizing: border-box;
        width: 867px;
        float: left;
        padding: 50px 40px;
        /*overflow-y: scroll;*/
        p {
          font-size: 20px;
          line-height: 32px;
          color: #555;
          text-align: justify;
        }
      }

    }
    button.sap {
      position: absolute;
      top: 65px;
      left: 50%;
      margin-left: 478px;
      background-color: white;
      border: 1px solid #dad8d7;
      cursor: pointer;
      padding: 5px 8px;
      border-radius: 4px;
      &:hover {
        background-color: #f8f8f8;
      }
    }
    .guide {
      border: 1px solid #dad8d7;
      width: 1247px;
      margin-top: 15px;
      height: 120px;
      ul {
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: space-around;
        align-items: center;
        li {
          display: flex;
          align-items: center;
          /*white-space: pre-wrap;*/
          img {
            margin: 0 10px;
          }
          h3 {
            margin: 0 0 6px 0;
          }
          p {
            margin: 0;
            font-size: 16px;
          }
        }
      }
    }
    .footer {
      line-height: 50px;
      a {
        text-decoration: none;
        color: #4aa74f;
        &:first-child {
          display: block;
          text-align: center;
          line-height: 0;
          margin-top: 15px;
        }
      }
    }
    .context-list {
      font-size: 18px;
    }
  }

</style>
