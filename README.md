<h1 align="center" >
<font color=orange>🏵️ okjiasu_action</font>
</h1>

<p align="center">
<font color=Peru>基于github工作流的okjiasu.com签到脚本。可白嫖流量！</font>

</p>

<div align="center">

![008hT4DMly1gwphdd018zg306y068axz.gif](https://p3-passport.byteimg.com/img/user-avatar/82ba4927bd1b67655c30daf0a25d4c16~180x180.awebp)

</div>

## 服务支持

- [x] github actions
- [x] 本地运行

## 注册

- 邀请注册 [h7ml](https://o.okjiasu.com/auth/register?code=AyLB)
- 直接注册 [无邀请码](https://okjiasu.com/auth/register)

## 功能说明

**每日定时签到,白嫖机场流量**

## 使用 github workflows 进行托管

[h7ml/okjiasu_action](https://github.com/h7ml/okjiasu_action.git)
**大约在每天的北京时间 8：00 左右执行**

1. Fork 仓库

2. 在仓库 `Settings->Secrets->Actions`中添加如下几个变量：

   | NAME        | VALUE              |
   | ----------- | ------------------ |
   | EMAIL_USER  | 发送邮件的邮箱账号 |
   | EMAIL_PASS  | 发送邮件的授权码   |
   | USER_EMAIL  | 接收通知的邮箱账号 |
   | OK_USER     | okjiasu - 账号     |
   | OK_PASSWORD | okjiasu - 密码     |

3. 在 `Settings->Actions`确保 actions 是开启状态

4. 关于发送邮件通知，本项目通知使用的是 qq 邮箱，如果你想使用其他邮件服务商进行推送，记得在`config.js`的`email.provider`选项中进行配置修改

- [QQ 邮箱-POP3/SMTP/IMAP](hhttps://service.mail.qq.com/cgi-bin/help?id=28&no=167&subtype=1)
- [nodemailer 参考手册](https://www.npmjs.com/package/nodemailer)

## 本地运行

1. clone 本仓库
   ```bash
   git clone https://github.com/h7ml/okjiasu_action.git
   ```
2. 进入项目

   ```bash
   cd okjiasu_action
   ```

3. 安装依赖

   ```bash
   yarn install
   ```

4. 在项目根目录新建 `.env` 文件，内容如下：

   ```
   # 发送邮件的邮箱账号
   EMAIL_USER=""

   # 发送邮件的授权码
   EMAIL_PASS=""

   # 接收通知的邮箱账号
   USER_EMAIL=""

   # okjiasu - 账号
   OK_USER=""

   # okjiasu - 密码
   OK_PASSWORD=""
   ```

5. `yarn install` 安装完依赖后，执行 `yarn run serve` 即可

6. 在`index.js` 中 配置 `headless:false` 可显示浏览器界面(部署时记得改为 true) ![screenshot](./package/okjiasu/screenshot.gif)
</div>

## 今日免费节点
### 采集时间: 2022-11-19 12:10:34 
| 节点名称 | 节点链接 | 节点二维码 |
| :---: | :---: | :---: |
| 【A】新加坡3 | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="【A】新加坡3">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-47.png) |
| 【A】日本 | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="【A】日本">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-48.png) |
| A如无法使用请更新订阅 | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="A如无法使用请更新订阅">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-49.png) |
| 台湾NF(倍率1.5） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="台湾NF(倍率1.5）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-50.png) |
| 德国2NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="德国2NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-51.png) |
| 新加坡1OracleNF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="新加坡1OracleNF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-53.png) |
| 新加坡2OracleNF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="新加坡2OracleNF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-54.png) |
| 新加坡（倍率0.1） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="新加坡（倍率0.1）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-55.png) |
| 海南-香港（倍率2） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="海南-香港（倍率2）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-56.png) |
| 美国加州 | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="美国加州">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-57.png) |
| 迪拜1NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="迪拜1NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-09-59.png) |
| 迪拜2NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="迪拜2NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-00.png) |
| 【A】韩国（倍率0.1） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="【A】韩国（倍率0.1）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-01.png) |
| 【A】香港1微软（电信起飞） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="【A】香港1微软（电信起飞）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-02.png) |
| 加拿大（倍率0.1）NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="加拿大（倍率0.1）NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-03.png) |
| 加拿大）NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="加拿大）NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-05.png) |
| 春川2NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="春川2NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-06.png) |
| 【A】日本（倍率2） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="【A】日本（倍率2）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-07.png) |
| 【A】日本大阪（倍率2） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="【A】日本大阪（倍率2）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-08.png) |
| 广港（倍率2） | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="广港（倍率2）">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-09.png) |
| 德国1NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="德国1NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-11.png) |
| 春川1NF | <details><summary><a href="vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=" title="春川1NF">点击导入</a></summary>vmess://eyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiJrcjEuc3VyZmh1Yi5uZXQiLCJwb3J0IjoxMjM0NSwiYWlkIjoxLCJuZXQiOiJ0Y3AiLCJoZWFkZXJUeXBlIjoibm9uZSIsInNlcnZpY2VuYW1lIjoiIiwiZW5hYmxlX3h0bHMiOiIiLCJmbG93IjoieHRscy1ycHJ4LWRpcmVjdCIsInZ0eXBlIjoidm1lc3M6Ly8iLCJzbmkiOiIiLCJ2IjoiMiIsInR5cGUiOiJ2bWVzcyIsInBzIjoi5pil5bedIDEgfE5GIiwicmVtYXJrIjoi5pil5bedIDEgfE5GIiwiaWQiOiJmZmUyNDc1OS1mZDQxLTMzNGMtOTJhNC04OWZjYzQ3ZWY0OTMiLCJjbGFzcyI6Mn0=</details> | ![二维码](https://raw.iqiq.io/h7ml/okjiasu_action/main/package/okjiasu/free/2022-11-19/2022-11-19-12-10-12.png) |