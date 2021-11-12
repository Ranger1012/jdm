# JustDeleteMe
针对中国网络服务注销的指南，也收录常用国外网站。项目为[Justdeleteme](https://github.com/jdm-contrib/jdm)的分支。
部分条目取自[Justdeleteme.CN](https://github.com/qiwihui/justdeleteme.CN)。
## 贡献
如果你想帮助添加未被收录的条目,条目信息收录在`jdm/_data/sites.json`中。添加条目需要增加如下信息:
- `name`：服务的名称。
- `url`：帐户删除页面的URL。如果不存在此类页面，则该URL应为联系人或删除帐户的帮助页面。
- `difficulty`：帐户删除的难度：
  - `easy`：流程简单，如基本只需要按下注销账户按钮；
  - `medium`：允许删除帐户但需要额外的步骤；
  - `hard`：要求你联系客服或或注销流程十分冗杂帐户的网站；
  - `impossible`：就算联系客服也不可能删除帐户的网站；
- `notes`：(可选）当鼠标悬停在该服务上时，将显示注释。注释可能包含你删除帐户可能需要的其- 他信息（例如Skype）或删除帐户（例如iTunes）的后果。
- `email`：(可选）如果你必须向公司发送电子邮件以注销你的帐户，请在此处添加电子邮件地址。
- `domains`: (可选) 供Chrome extension使用。
  
如需要更详细的说明可参考`CONTRIBUTING.md`

## 协议

Project licensed under the [MIT License](LICENSE) (MIT). This is a detached
fork of the [original repo](https://github.com/justdeleteme/justdelete.me)
that intends to keep the project alive, as the original one was abandoned.

Flags modified from [gosquared/flags](https://github.com/gosquared/flags),
MIT licensed, Copyright (c) 2017 Go Squared Ltd.

Search functionality modified from [DevCenter.me](https://github.com/stevestreza/DevCenter.me),
MIT licensed, Copyright (c) 2013 Steve Streza.
