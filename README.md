# 暂停更新说明
## 由于需要找工作，所以暂停更新，等秋招过去继续更新

# 免责声明

- 本仓库发布的脚本及其中涉及的任何解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。
- 本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。
- 您必须在下载后的24小时内从计算机或手机中完全删除本仓库所有脚本。
- 任何人使用本仓库脚本不得用于非法用途，任何人将本仓库脚本用于非法用途所造成的一切后果由使用者承担。
- 本人无法100%保证使用本项目之后不会造成账号异常问题，若出现任何账号异常问题本人概不负责，请根据情况自行判断再下载执行！否则请勿下载运行！
- 如果任何单位或个人认为该项目的脚本可能涉及侵犯其权利，则应及时通知并提供相关证明，将在收到认证文件后删除相关脚本。
- 任何以任何方式查看此项目的人或直接或间接使用本项目的任何脚本的使用者都应仔细阅读此声明。
- 本人保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或本项目的规则，则视为您已接受此免责声明。
- 您使用或者复制了本仓库且本人制作的任何脚本，则视为 `已接受` 此声明，请仔细阅读

> ***您使用或者复制了本仓库且本人制作的任何脚本，则视为 `已接受` 此声明，请仔细阅读***
> ***本平台不会获取用户的账号密码，不会上传至其他任何地方，如果有所怀疑，请直接删除本程序***

# gitee仓库地址：https://gitee.com/yaoys95/Auto_checkin_release

# 由于有些平台的限制，强烈建议签到时间设置的别太早，最好是早上9：30以后

# 目前已全面支持阿里云盘新版本签到中所有已知的任务，并且自己部署到本地，安全无忧，全网目前唯一的可以部署到自己本地并且支持阿里云盘新版本签到的项目

# Auto_CheckIn 多平台自动签到

- 支持多用户签到
- 支持推送消息到pushplus平台(server酱和pushplus选择一个就好，也可以同时推送，如果不配置则不进行推送)
- 支持推送消息到server酱(server酱和pushplus选择一个就好，也可以同时推送，如果不配置则不进行推送)
- **目前已全面支持阿里云盘新版本签到中所有已知的任务，并且自己部署到本地，安全无忧，全网目前唯一的可以部署到自己本地并且支持阿里云盘新版本签到的项目
  **

## 已打包文件地址，可直接下载解压使用，配置yaoys_checkin_config.json即可，进入AutoCheckin找到exe点击启动

## 阿里云盘文件格式为exe格式，msi名称为安装包，green名称为免安装版

## 选择免安装版和安装版下载后解压exe得到程序或者安装包，阿里云盘地址：https://www.aliyundrive.com/s/ZeotJdW4iuh 提取码: 15oy

## 版本说明

- Windows版本:最新版本为v0.1.16
- 青龙面板版本：最新版本为v0.1.16

## 最近更新，更多更新内容请查看[更新日志](更新日志.md)
- 2023-10-28
1. 新增HIFINI网站签到(https://www.hifini.com/),配置文件新增网站相关配置
`"hifini": {
      "is_checkin": true,
      "push_message": true,
      "more_time_sleep": 0,
      "time_sleep": 0,
      "checkin_verification": "单账号配置，直接填写cookie即可，不需要写在json数组中，多账号参考上面"
    },`
2. 修复阿里云盘签到任务的一些问题
3. 版本号更新为v0.1.16
## 目前支持签到平台

- [hifini网站](https://www.hifini.com/)
- [GLaDOS平台](https://glados.rocks/)
- [天翼云盘](https://cloud.189.cn/web/login.html)
- [bilibili直播](https://live.bilibili.com)
- [科研通签到](https://www.ablesci.com/)
- [谷粉学术签到](http://bbs.99lb.net/)
- [阿里云盘](https://www.aliyundrive.com/)
- ~~[Wps会员时长](https://vip.wps.cn/home)(已失效)~~
- [Wps云空间容量](https://zt.wps.cn/spa/2019/vip_mobile_sign_v2/?csource=pc_cloud_membercenter&position=pc_cloud_sign/)
- [百度贴吧](https://tieba.baidu.com/)
- [交易猫](https://www.jiaoyimao.com/)
- [飘云阁](https://www.chinapyg.com/)
- ~~[吾爱破解](https://www.52pojie.cn/portal.php)(已失效)~~

## 阿里云盘不支持的任务：

1. 创建共享相簿邀请成员加入并上传10张照片(无法支持，需要操作多个账号)
2. 开启自动备份并备份10个文件(无法支持)
3. 备份一个新的设备(无法支持)
4. 开启手机自动备份并持续至少一小时(无法支持)

## 当前需求或BUG(欢迎随时提出issues)

[版本需求&问题.md](版本需求&问题.md)

## 签到列表

🟢: 正常运行 🔴: 脚本暂不可用 🔵: 可以执行(需更新) 🟤: 随缘

| 状态  | 类别 | 终端  | 任务名称        | 名称                                                                                                  | Cookie 时长 | 检查日期       | 备注                     |
|-----|----|-----|-------------|-----------------------------------------------------------------------------------------------------|-----------|------------|------------------------|
| 🟢️ | 签到 | WEB | GLADOS      | https://glados.rocks/                                                                               | 待测试       | 2023-5-13  | 每日签到获取时长,需要开通会员才可以获取时长 |
| 🟢️ | 签到 | WEB | BILIBILI    | https://www.bilibili.com/                                                                           | 待测试       | 2023-02-21 | 直播签到，获取硬币              |
| 🟢️ | 签到 | WEB | CLOUD189    | https://cloud.189.cn/                                                                               | 永久        | 2023-02-21 | 每日签到 +2次抽奖获得空间奖励       |
| 🟢️ | 签到 | WEB | AbleSci     | https://www.ablesci.com/                                                                            | 待测试       | 2023-5-13  | 科研通平台每日签到获取积分          |
| 🟢️ | 签到 | WEB | gufenxueshu | http://bbs.99lb.net/                                                                                | 待测试       | 2023-5-13  | 谷粉学术每日签到获取积分           |
| 🟢️ | 签到 | WEB | Aliyunpan   | https://www.aliyundrive.com/                                                                        | 待测试       | 2023-5-13  | 阿里云盘每日签到&各种任务          |
| 🔴  | 签到 | WEB | WPS_Vip     | https://vip.wps.cn/home                                                                             | 待测试       | 2023-5-28  | WPS签到的会员时长，有时会失败，失败请手动 |
| 🟤  | 签到 | WEB | WPS_Cloud   | https://zt.wps.cn/spa/2019/vip_mobile_sign_v2/?csource=pc_cloud_membercenter&position=pc_cloud_sign | 待测试       | 2023-5-28  | Wps签到得空间容量，有时会失败，失败请手动 |
| 🟢️ | 签到 | WEB | tieba       | https://tieba.baidu.com/                                                                            | 待测试       | 2023-6-18  | 百度贴吧签到                 |
| 🟢️ | 签到 | WEB | jiaoyimao   | https://www.jiaoyimao.com/                                                                          | 2天/3天     | 2023-7-5   | 交易猫签到得积分               |
| 🟢️ | 签到 | WEB | piaoyunge   | https://www.chinapyg.com                                                                            | 待测试       | 2023-7-10  | 飘云阁签到得积分               |
| 🔴  | 签到 | WEB | wuaipojie   | https://www.52pojie.cn/portal.php                                                                   | 待测试       | 2023-7-10  | 吾爱破解签到得积分              |
| 🟢️ | 签到 | WEB | hifini      | https://www.hifini.com/                                                                             | 待测试       | 2023-10-29 | hifini网站签到获取金币         |

## 支持的通知列表

server 酱（微信）

pushplus（微信）

## 更新日志

[更新日志.md](更新日志.md)

## 使用教程

参考[使用说明.md](使用说明.md)

## 青龙面板使用请参考[青龙面板配置使用.md](青龙面板配置使用.md)