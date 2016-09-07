# PHP开发人员必须收集的常用代码(持续更新中)
常用工具类文件
### 目录如下

- CheckCode.class.php  验证码类

- 数据库操作→DAOMySQLI.class.php
  - 查询一个字段 fetchOne
  - 查询所有字段 fetchAll
  - 增删改操作 myQuery
- PDO数据库接口→I_DAO.interface.php
- PDO数据库类→DAOPDO.class.php  
  - 查询所有数据 getAll
  - 查询一条数据 getRow
  - 查询一个字段的值 getOne
  - 增删改操作 exec
  - 查询受影响的记录数resultRows
  - 查询执行插入操作返回的主键的值lastInserId
  - pdo_statement对象 query
  - 转义引号 escapeDate
- 单例模式→Singleton.class.php
- 删除给定目录→DeleteDir.class.php
- 文件上传类→Upload.class.php
- FTP管理工具→FTP.php
- 图片处理→Image.class.php
  - 缩略,裁剪,圆角,倾斜
- 图片处理工具Image.php
  - 缩略图 thumb
  - 截取图片 crop
- 图像压缩 ImageThumb.class.php
- 图片处理(全)Thumb.class.php
  - 文字水印setMaskWord
  - 图片水印setMaskImg
  - 缩略图边框setDstImgBorder
  - 水平翻转 flipH
  - 垂直翻转flipV
  - 图片剪切 setRectangleCut
- 二维码 PHPQRcode.class.php
- 发邮件 Smtp.class.php
- 日期时间 DateTime.class.php
  - 获取时间戳getUnixTime
  - 获取简短的日期显示getShortDate
- 运行时间和内存Runtime.class.php
- 验证码 Captcha.class.php
- 验证码 CheckCode.class.php
- 验证信息(简单)Verify.class.php
- 通用验证 Validator.class.php
  - 邮件地址checkEmail
  - 检查字符串checkStr
  - 检查整数checkInt
  - 检查使用HTTP协议的网址checkHttpUrl
  - 电话号码checkTel
  - 检查手机号码 checkMobile
  - 检查邮编 checkZipCode
  - 检查身份证号码checkIdNum
  - 检查日期是否正确checkDate
  - 检查开始日期是否小于结束日期checkDateRange
  - 检查是否为合法金额checkMoney
  - 检查是否为一个合法的日期格式isDate
  - 检查是否为一个合法的时间格式isDatetime
  - 检测一个宽松的日期格式 checkLooseDate
  - 判断是否是浮点数checkFloat
- 压缩文档Zip.class.php
- 字符串处理String.class.php
  - 过滤非法字符filter
  - 获取UTF-8格式的字符串长度strlenUtf8
  - 获取一个随机字符串randStr
  - 以UTF-8格式截取字符串substrUtf8
  - 移除所有不可见字符trimInvisible
  - 替换字符串 replace
- URL工具Url.class.php
  - 进行URL编码encode
  - 进行URL解码decode
- Json工具Json.class.php
  - 数据编译为json字符串 encode
  - json字符串解码为数组 decode
- Page.class.php  分页类
- Upload.class.php  文件上传类
- Thumb.class.php  图片处理类
