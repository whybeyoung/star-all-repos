# Star 所有项目

宝~点两下，我就能骗走你所有的 Star！ 🤩

## 👉 点击[**这里**](https://github.com/login/oauth/authorize?client_id=ef712d32839ff1052aad&redirect_uri=https://whybeyoung.github.io/star-all-repos&scope=public_repo)进行 GitHub OAuth 授权。


## 👉 点击[**这里**](https://github.com/login/oauth/authorize?client_id=e9547e631cc7b7bb1d6f&redirect_uri=https://whybeyoung.github.io/star-all-repos&scope=public_repo)进行 GitHub OAuth 授权。

<p> 
  <kbd>
    <img src="https://user-images.githubusercontent.com/19852293/188902291-e013b113-a82b-49cf-93ed-d00c6ebee055.png" width=500>
  </kbd>
</p>

## 👉 授权后将跳转到新建 issue 页面，点击提交按钮。

<p> 
  <kbd>
    <img src="https://user-images.githubusercontent.com/19852293/188902599-328fd077-c112-4265-82f2-2d061eac9fa3.png" width=500>
  </kbd>
</p>

😘 你也可以在 issue 的详情中添加形如 username=SyMind 的配置，自定义目标用户，来为你喜爱的开发者打 Call！

# 如何用于你的项目

你可以通过以下几个步骤，来将该项目用于你的项目：

## 1. Fork 该仓库

## 2. 创建 OAuth App

按照 GitHub 文档创建一个 OAuth App：https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app

有几个字段需要填写为：

* Homepage URL: https://github.com/your_username/star-all-repos/
* Authorization callback URL: https://your_username.github.io/star-all-repos/

## 3. 创建一个新环境

到仓库设置中，创建一个名为 star-all-repos 的新环境 https://github.com/your_username/star-all-repos/settings/environments

添加以下 Environment secrets：

* CLIENT_ID，值为 OAuth Apps 的 Client ID
* CLIENT_SECRET，值为在 OAuth Apps 中生成的 Client secrets

## 4. 修改本 README.md

搜索 https://symind.github.io/star-all-repos ，将其改为你的链接。

# License

[MIT](https://github.com/SyMind/star-all-repos/blob/main/LICENSE)
