# WebEngine -- *东半球第二好用的CMS系统*

![Show](https://github.com/Yanvalue/WebEngine/blob/master/other/show.png)

***

### 目录结构  
WebEngine  
├─admin                 // 管理控制台项目  
│  ├─cache              // CI 缓存  
│  ├─config             // CI 配置文件  
│  ├─controllers        // CI 控制器  
│  ├─core               // CI 扩展类  
│  ├─helpers            // CI 辅助函数  
│  ├─hooks              // CI 钩子  
│  ├─language           // CI 语言类  
│  ├─libraries          // CI 自定义函数
│  ├─logs               // CI 日志  
│  ├─models             // CI 模型  
│  ├─third_party        // 第三方插件  
│  └─views              // CI 视图文件  
├─install               // 安装程序  
├─mobile                // 移动端  
├─system                // 核心  
├─upload                // 文件上传目录  
│  └─images  
├─user_guide            // 用户手册  
└─web                   // 前端页面  
***
### 安装说明  
***
1.解压项目包；  
2.将项目文件夹及里面的文件上传到服务器，`index.php`文件将位于网站的根目录；  
3.打开`application/config/config.php`文件设置你网站的根URL，设置好 `$system_path`、`$application_folder `和 `$view_folder `三个变量的值，最好设置成绝对路径，例如：`/www/MyUser/system`。   
4.使用数据库，打开`application/config/database.php`文件设置数据库参数，  

***
### Design by Yanvalue  
***
