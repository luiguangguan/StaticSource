***下载setup.exe以及configuration.xml<br>***
***使用一下命令执行Office的部署,具体版本需要修改configuration.xml文件中的配置***

`setup.exe /configure installconfig.xml`

**其中**

`<Add OfficeClientEdition="64" Channel="PerpetualVL2019">`

> OfficeClientEdition表示Office的位数(这里是64位)

> Channel表示Office的使用频道

`<Product ID="ProPlus2019Volume">`

> 表示Office版本,这里是专业增强版(支持Volume表示支持批量kms激活)

`<Language ID="zh-cn" />`

> 表示Office的语言(版本)

`<ExcludeApp ID="Access" />`

> 表示要排除的套件(这里表示不安装`Access`)
