![贝壳](mahua-logo.jpg)

## 功能模块

* Orc工具库
    * `GetImageCode` 图片验证码
        
        __参数__
        *  输入 ImagePath :  需要识别的图片路径
        *  输入 Api_Key   :  百度 apikey (不填用默认帐号)
        *  输入 SECRET_KEY:  百度 secretkey (不填用默认帐号)
        *  输出 OutputCode : 识别出来的验证码
        *  输出 OutputJSON : 返回的JSON
        *  输出 OutputError：返回的执行状态
        
* 解压缩工具库
     * `unZipFile`解压文件
       
       __参数__
        *    输入 InputFile ：  zip文件路径
        *    输入 OutputFolder：解压路径
        *    输出 OutputMsg:    执行状态码
        
     * `ZipFile`压缩文件
       
       __参数__
        *    输入 InputFolder ：需要压缩的文件夹路径
        *    输出 OutputFile:   压缩文件保存路径
        
 * Web工具库
     *  `WebService` WebService访问工具
        
        __参数__
        *   输入 Url        :  Webservice 地址
        *   输入 MethodName ： Webservice 方法名称
        *   输入 Argument   ： 参数 
        *   输出 OutputXml  :  得到的XML
        *   输出 Status     :  得到的返回状态
        
* 常用工具库
     *  `PinYinConverter` 中文转拼音
        
        __参数__
        *   输入 InputString    : 中文字符 
        *   输出 GetFullString  : 拼音字符


## 有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(uipathfans@163.com)
* QQ: 1586826868
* 微信: aliuge2000

## 技术交流Q群
* UiPath粉丝交流群 781374956



## 关于作者
```javascript
  var ihubo = {
    nickName  : "贝壳",
    site : "http://www.uipathfans.com"
  }
```
