![贝壳](mahua-logo.jpg)

## 功能模块

* Orc工具库
    * `GetImageCode` 图片验证码
        
        __参数__
        *  输入 ImagePath(String) :  需要识别的图片路径
        *  输入 Api_Key(String)   :  百度 apikey (不填用默认帐号)
        *  输入 SECRET_KEY(String):  百度 secretkey (不填用默认帐号)
        *  输出 OutputCode(String) : 识别出来的验证码
        *  输出 OutputJSON(String) : 返回的JSON
        *  输出 OutputError(String)：返回的执行状态
        
* 解压缩工具库
     * `unZipFile`解压文件
       
       __参数__
        *    输入 InputFile(String) ：  zip文件路径
        *    输入 OutputFolder(String)：解压路径
        *    输出 OutputMsg(String):    执行状态码
        
     * `ZipFile`压缩文件
       
       __参数__
        *    输入 InputFolder(String) ：需要压缩的文件夹路径
        *    输出 OutputFile(String):   压缩文件保存路径

 * 字符串操作工具库
     *  `RegexSubstring` 字符串头尾截取
        
        __参数__
        *   输入 InputString(String) :  输入的字符串
        *   输入 BeginString(String) ： 开始字符串
        *   输入 EndString(String)   ： 结束字符串
        *   输出 OutputCode(String)  :  截取的字符串


 * Web工具库
     *  `WebService` WebService访问工具
        
        __参数__
        *   输入 Url(String)        :  Webservice 地址
        *   输入 MethodName(String) ： Webservice 方法名称
        *   输入 Argument(Hashtable)   ： 参数 
        *   输出 OutputXml(XmlDocument)  :  得到的XML
        *   输出 Status(String)     :  得到的返回状态  (200成功   400失败)
        
* 常用工具库
     *  `PinYinConverter` 中文转拼音
        
        __参数__
        *   输入 InputString(String)    : 中文字符 
        *   输出 GetFullString(String)  : 拼音字符


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
