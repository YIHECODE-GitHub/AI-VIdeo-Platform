# yihecode-server


## 一、简介<br>
<br>
AI视频监控平台, 是一款功能强大且简单易用的实时算法视频监控系统。愿景在最底层打通各大芯片厂商相互间的壁垒，省去繁琐重复的适配流程，实现芯片、算法、应用的全流程组合，减少企业级应用约 95%的开发成本，用户仅需在界面上简单操作，即可实现全视频的接入及布控。<br><br>

 **联系方式** 
手机号、微信号：+86-15901018349
我们的官网 [http://www.yihecode.com/](http://www.yihecode.com/)查看最新动态
我们的bilibili官方地址：https://space.bilibili.com/1139333378 <br><br>


<img src="https://gitee.com/moo3108661550/yihecode-server/raw/master/src/main/resources/static/admin/images/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20240614193133.png" />

<img src="https://gitee.com/moo3108661550/yihecode-server/raw/master/src/main/resources/static/admin/images/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20240614193142.png" />

<video width="800" height="450" controls>
  <source src="https://yihecode-selfweb.oss-cn-beijing.aliyuncs.com/software/tutorial-videos/%E5%A6%82%E4%BD%95%E5%85%B3%E8%81%94%E6%91%84%E5%83%8F%E5%A4%B4%E4%B8%8E%E7%AE%97%E6%B3%95%EF%BC%9F.mp4" type="video/mp4">
</video>

系统根据客户环境目前共分为三种形态：分别为<br>

**集群版-AIBox**<br>

支持大量边缘盒子集中管理调度，平台实现多个盒子的控制管理，报警推送消息升级。
基于多个边缘盒子部署的综合视频安防系统，多用于布置大量摄像头的场景，如仓库、物流园区、学校、医院、工厂、交通枢纽等<br>

**单机版-SingleBox**<br>
应用单个边缘盒子，可关联少量摄像头、算法，在客户现场可快速落地体验。<br>

**服务器版-Master**<br>
适用于拥有 GPU显卡的企业用户。
基于服务器部署的综合视频安防系统，多用于布置大量摄像头的场景。<br>
项目公开演示链接：[http://39.164.53.248:33089/](http://39.164.53.248:33089/)<br>

#### 系列项目Gitee链接<br>
请分别前往每个版本对应的两个项目同步代码。<br>

**1.集群版-AIBOX**
<br>
|名称|描述|备注|
|----|--————--|----|
|AIBOX-Server|后端项目|需付费|
|AIBOX-VUE|前端项目||
<br>

**2. 服务器版-Master**
<br>
|名称|描述|备注|
|----|---————-|----|
|Master-Server|后端项目|镜像开源|
|Master-VUE|前端项目||
<br>

**3.单机版-SIngleBOX**
<br>
|名称|描述|备注|
|----|---————-|----|
|SingleBox-Server|后端项目|需付费|
|SingleBox-VUE|前端项目||
<br>

## 二、项目特点<br>
- 集成化：视频监控、计算机视觉计算、告警通知 一体的视频安防平台<br>
- 支持RTSP/RTMP 推流拉流形式<br>
- 支持x86、arm等指令集平台部署<br>
- 支持H265/H264/GB28181/的视频格式<br>
- 支持添加客户自己训练的模型<br>
- 支持多路多算法的实时AI计算<br>
- 全方面告警通知，支持语音电话、短信、企业微信、钉钉、APP、第三方接口、音柱<br>
- 高性能，支持多路多算法实时监控与AI计算，及时返回告警结果<br>

## 三、项目定位<br>
- 跨平台视觉安防解决方案<br>
- 二次开发项目服务<br>
- 商用级机器视觉平台<br>

## 四、功能清单<br>
- 算法商城<br>
- 视频管理<br>
- 推送管理<br>
- 告警管理<br>
- AI 监控大屏<br>
- AI 3D监控<br>
- 系统管理<br>
- 人脸识别<br>
- 人流监测<br>
- 标注平台<br>
- 国标28181管理<br>


## 五、软件架构<br>
基于springboot2.7.4+mybatisplus+vue2+mysql5.7开发

## 六、更新记录<br>
### 版本号 1.1
更新日期 2024年6月21日

| 序号  | 功能模块 | 更新描述                                                               | 更新支持平台                           |
| --- | ---- | ------------------------------------------------------------------ | -------------------------------- |
| 1   | 算法商城 | 1.  新增算法功能更新，支持临时新增算法卡片功能。                                         | Master服务器版、AIBox集群版、SingleBox单机版 |
| 2   | 边缘平台 | 1.  性能优化<br>2.  视频预览中，更新提交摄像头方式（异步）                                | SingleBox单机版                     |
| 3   | 告警管理 | 1.新增浏览器快速清空告警记录功能                                                  | AIBox集群版、SingleBox单机版            |
| 4   | 推送管理 | 1.新增"IP音柱"推送形式，需根据不同品牌单独适配                                         | AIBox集群版、SingleBox单机版            |
| 5   | 人脸布控 | 1.  新增支持边缘盒子使用人脸布控系统<br><br>·支持实时流人脸识别，4-6路人脸识别极限<br>·支持手动上传图片识别比较 | SingleBox单机版                     |


### 版本号 1.06
更新日期 2024年6月5日

| 序号  | 功能模块 | 更新描述                                   | 更新支持平台                           |
| --- | ----   | -------------------------------------- | -------------------------------- |
| 1   | 算法商城 | 1.  调整了算法商城交互方式，包括下载、编辑、版本管理、卸载、删除算法卡片 | Master服务器版、AIBox集群版、SingleBox单机版 |
| 2   | 推送管理 | 1.优化了语音电话推送功能                          | Master服务器版、AIBox集群版、SingleBox单机版 |


### 版本号 1.05
更新日期 2024年5月29日

| 序号  | 功能模块 | 更新描述                                                                   | 更新支持平台                           |
| --- | ---- | ---------------------------------------------------------------------- | -------------------------------- |
| 1   | 算法商城 | 1.  优化了存储数据方式，提升下载稳定性，需外网才可下载                            | Master服务器版、AIBox集群版、SingleBox单机版 |
| 2   | 边缘平台 | 1.  修改了告警弹窗交互形式                                                  | AIBox集群版、SingleBox单机版            |
| 3   | 告警管理 | 1.更改的新的UI形式，提升了查看告警记录的易用性                                    | Master服务器版、AIBox集群版、SingleBox单机版 |
| 4   | 视频预览 | 1.  优化了合成流性能<br>2.  用户可通过代码，自主开启合成流功能。并可配置合成流参数。 码率、采样帧率、计算帧率、是否开启合成流。 | AIBox集群版、SingleBox单机版            |
