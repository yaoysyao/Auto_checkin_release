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

# Auto_CheckIn 多平台自动签到

- 支持多用户签到
- 支持推送消息到pushplus平台(server酱和pushplus选择一个就好，也可以同时推送，如果不配置则不进行推送)
- 支持推送消息到server酱(server酱和pushplus选择一个就好，也可以同时推送，如果不配置则不进行推送)

## 已打包文件地址，可直接下载解压使用，配置Config.json即可，进入AutoCheckin找到exe点击启动，地址： https://www.aliyundrive.com/s/AdFLyhZ88MN  提取码: 22oh

## 最新版本为v0.1.2

## 目前支持签到平台

- [GLaDOS平台](https://glados.rocks/)
- [天翼云盘](https://cloud.189.cn/web/login.html)
- [bilibili直播](https://live.bilibili.com)
- [科研通签到](https://www.ablesci.com/)
- [谷粉学术签到](http://bbs.99lb.net/)
- [阿里云盘](https://www.aliyundrive.com/)

## 当前需求或BUG(欢迎随时提出issues)

[Issues.md](Issues.md)

## 签到列表

🟢: 正常运行 🔴: 脚本暂不可用 🔵: 可以执行(需更新)

| 状态  | 类别  | 终端  | 任务名称        | 名称                           | Cookie 时长 | 检查日期       | 备注                     |
|-----|-----|-----|-------------|------------------------------|-----------|------------|------------------------|
| 🟢️ | 签到  | WEB | GLADOS      | https://glados.rocks/        | 待测试       | 2023-5-13  | 每日签到获取时长,需要开通会员才可以获取时长 |
| 🟢️ | 签到  | WEB | BILIBILI    | https://www.bilibili.com/    | 待测试       | 2023-02-21 | 直播签到，获取硬币              |
| 🟢️ | 签到  | WEB | CLOUD189    | https://cloud.189.cn/        | 永久        | 2023-02-21 | 每日签到 +2次抽奖获得空间奖励       |
| 🟢️ | 签到  | WEB | AbleSci     | https://www.ablesci.com/     | 待测试       | 2023-5-13  | 科研通平台每日签到获取积分          |
| 🟢️ | 签到  | WEB | gufenxueshu | http://bbs.99lb.net/         | 待测试       | 2023-5-13  | 谷粉学术每日签到获取积分           |
| 🟢️ | 签到  | WEB | Aliyunpan   | https://www.aliyundrive.com/ | 待测试       | 2023-5-13  | 阿里云盘每日签到               |

## 支持的通知列表

server 酱（微信）

pushplus（微信）

## 更新日志

- 2023-5-21 (v0.1.3版本,正在测试中)
    1. 配置文件新增了是否是定时任务配置，如果是定时任务则按照定时任务每日执行，否则只执行一次
    2. 新增签到任务可以设置为服务，可以设置服务启动时执行一次或者每日定时执行(通过设置 **"is_scheduler": true/false**
       实现)
       具体如何设置为Windows的服务，请参考本文档''如何设置为Winodws服务''下的内容,**目前只支持Windows**
    3. 推送消息新增任务总数，成功数量，失败数量等信息

- 2023-5-14
    1. 修复glados平台多账号签到错误
- 2023-5-13

    1. 修复天翼云盘登陆失败的问题
    2. 发布0.1.2版本
    3. **签到不再依赖谷歌浏览器，无需谷歌浏览器也可以执行签到(重要)**
    4. config.json文件进行修改，请参考最新版配置文件
    5. 解决[Issues.md](Issues.md)文件中0.1.2版本的需求&BUG

- 2023-4-9 修复BUG

- 2023-3-28 增加阿里云盘签到

## 使用教程

- 在本项目的相同等级的文件夹中建立名为 `config` 的文件夹，将[Config.json](Config.json)
  放入其中,并将对应平台的cookie写入配置文件中，消息推送使用的为token，如图所示

<p align="center">
  <img src="images/checkin_config.png" />
</p>

### 各平台签到教程

#### cookie或者登录信息填写格式请参考[Config_解释说明.json](Config_解释说明.json)中的注释

#### 1. glados签到教程

##### 1.1 添加 COOKIE 至 配置文件 config/Config.json->glados

- 登陆[GLaDOS](https://glados.rocks/)后，F12打开开发者工具。
- 刷新网页，并在浏览器中提取复制`Cookie`值，注意不要把`Cookie:`前缀加入进来！！！！！

<p align="center">
  <img src="images/Step1.png" />
</p>

#### 2 天翼云盘签到教程

##### 2.1 添加 天翼云盘登录信息 至 配置文件 config/Config.json->cloud189

- 在配置文件中写入登录用户名和密码

#### 3 bilibili直播和硬币签到教程

##### 3.1 添加 bilibili直播和硬币cookie 至 配置文件 config/Config.json->bilibili_live，->bilibili_icon

- 同方法1.1

#### 4 科研通签到教程

##### 4.1 添加 科研通cookie 至 配置文件 config/Config.json->able_sci

- 同方法1.1

#### 5 谷粉学术签到教程

##### 5.1 添加 cookie 至 配置文件 config/Config.json->gu_fen_xue_shu

- 同方法1.1

#### 6 阿里云盘签到教程

##### 6.1 添加 refresh_token 至 配置文件 config/Config.json->aliyunpan

###### refresh_token获取方法:

1. 自动获取: 网站登录阿里云盘后，控制台粘贴 JSON.parse(localStorage.token).refresh_token
2. 手动获取: 网站登录阿里云盘后，可以在开发者工具 -> Application -> Local Storage 中的 token 字段中找到。

### 消息推送配置教程(可选,不配置则不进行推送)

#### 添加 PUSHPLUS的token值 至 配置文件 config/CookieConfig.ini

- 登陆[pushplus](http://www.pushplus.plus/)
- 将token写入config文件中

<p align="center">
  <img src="images/pushplus_token.png" />
</p>

#### 如果使用[server酱](https://sct.ftqq.com/)，请添加 SERVER_TOKEN 至 Secrets,如果不想推送通知可以不填写此项

- 将token写入config文件中

### 请注意，如果两个推送平台均配置，则会同时推送至两个平台，建议只配置一个就好

### 推送消息时，所有的签到只推送一条通知，如下所示

<p align="center">
  <img src="images/checkin_info.png" />
</p>