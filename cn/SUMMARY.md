# 大纲

这是一本好玩的nutz书

* [简介](README.md)
* [前言](introduction/introduction.md)
	* [为什么写这本书](introduction/whythisbook.md)
	* [这本书怎么用](introduction/howtouse.md)
	* [如何反馈](introduction/howtofeedback.md)
	* [提问的智慧](introduction/askforhelp.md)
	* [关于Maven和MyEclipse的说明](introduction/maven_myeclipse.md)
	* [更新日志](introduction/changelog.md)
	* [致谢](introduction/thankyou.md)
* [基本准备](prepare/prepares.md)
	* [选用工具](prepare/tools.md)
	* [让Eclipse工作在UTF8环境](prepare/eclipse_utf8.md)
	* [Eclipse的自动提示](prepare/auto_complete.md)
	* [配置Server](prepare/server.md)
	* [下载jar包](prepare/jars.md)
	* [数据库准备](prepare/prepare_db.md)
* [30分钟把项目跑起来](setup30mins/setup30mins.md)
	* [新建web项目](setup30mins/new_project.md)
	* [添加jar包](setup30mins/add_jar.md)
	* [添加MainModule](setup30mins/add_mainmodule.md)
	* [配置web.xml](setup30mins/configure_webxml.md)
	* [启动一下这个空项目](setup30mins/start_emtry_webapp.md)
	* [添加dao.js文件](setup30mins/add_daojson.md)
	* [配置IocBy](setup30mins/configure_iocby.md)
	* [新增Pojo](setup30mins/add_pojos.md)
	* [配置SetupBy](setup30mins/setupby.md)
	* [初始化数据](setup30mins/init_datas.md)
	* [第一个模块类UserModule](setup30mins/add_usermodule.md)
	* [登陆方法](setup30mins/add_login_method.md)
	* [登出方法](setup30mins/add_logout_method.md)
	* [登陆登出的JSP页面](setup30mins/login_logout_jsp.md)
	* [运行起来](setup30mins/runit.md)
* [增删改查都要有](do_curd/do_curd.md)
	* [添加一个校验方法](do_curd/do_check.md)
	* [add方法](do_curd/do_add.md)
	* [update方法](do_curd/do_update.md)
	* [delete方法](do_curd/do_delete.md)
	* [query方法](do_curd/do_query.md)
	* [加强安全性](do_curd/do_safe.md)
	* [页面中转方法](do_curd/do_forward.md)
	* [UserModule全貌](do_curd/do_class.md)
	* [列表页](do_curd/list_jsp.md)
* [日志系统](logsystem/logsystem.md)
	* [下载log4j和nutz源码](logsystem/download_log4j.md)
	* [关联nutz源码](logsystem/link_source.md)
	* [配置log4j](logsystem/configure_log4j.md)
	* [日志总览](logsystem/log_overview.md)
	* [资源扫描系统的Log](logsystem/log_scans.md)
	* [容器重要信息的Log](logsystem/log_container.md)
	* [Ioc初始化的Log](logsystem/log_ioc.md)
	* [URL映射关系的Log](logsystem/log_urlmapping.md)
	* [Ioc获取对象的Log](logsystem/log_ioc_get.md)
	* [Dao的日志初探](logsystem/log_dao.md)
	* [其他小Log](logsystem/log_others.md)
* [完善一下基本配置](more_configure/more_configure.md)
	* [默认@Ok](more_configure/ok.md)
	* [默认@Fail](more_configure/fail.md)
	* [配置Localization](more_configure/localization.md)
* [为正式开发做准备](dev_prepare/dev_prepare.md)
	* [下载更多jar包](dev_prepare/more_jars.md)
	* [改进dao.js](dev_prepare/better_dao_js.md)
	* [自定义NutFilter](dev_prepare/custom_nutfilter.md)
	* [配置druid监控](dev_prepare/configure_druid_html.md)
	* [配置动作链](dev_prepare/action_chain.md)
	* [加入Shiro](dev_prepare/add_shiro.md)
	* [加入Quartz](dev_prepare/add_quartz.md)
	* [配置jstl](dev_prepare/add_jstl.md)
	* [新增BasePojo类](dev_prepare/base_pojo.md)
	* [新增BaseModule类](dev_prepare/base_module.md)
	* [新增Toolkit类](dev_prepare/toolkit.md)
	* [本章完成后的压缩包下载](dev_prepare/package_download.md)
* [用户头像上传及显示](user_avatar/user_avatar.md)
	* [新增UserProfile类](user_avatar/add_user_profile_class.md)
	* [建立关联关系](user_avatar/add_one_link.md)
	* [UserProfile改查方法](user_avatar/curd_profile.md)
	* [上传头像的入口方法](user_avatar/upload_avatar_method.md)
	* [图片读取方法](user_avatar/read_avatar.md)
	* [用户详情页](user_avatar/profile_page.md)
	* [页面测试](user_avatar/upload_test.md)
* [用户邮箱验证](user_mail/user_mail.md)
	* [添加mail相关的jar](user_mail/add_jar.md)
	* [配置Mail相关的ioc文件](user_mail/mail_ioc.md)
	* [添加新Service](user_mail/add_mail_service.md)
	* [添加发送验证邮件的方法](user_mail/triggle_mail.md)
	* [添加验证邮件的返回方法](user_mail/callback_method.md)
	* [改造profile.jsp](user_mail/modify_profile.md)
	* [页面测试](user_mail/mail_test.md)
* [定期清理未激活用户](user_clean/user_clean.md)
	* [添加cron任务加载类](user_clean/cron_loader.md)
	* [添加任务类](user_clean/clean_job.md)
	* [在MainSetup中触发](user_clean/mainsetup.md)
	* [检查效果](user_clean/test_cron.md)
* [登陆验证码](login_captcha/login_captcha.md)
	* [添加simplecaptcha](login_captcha/add_simplecaptcha.md)
	* [新增CaptchaModule模块类](login_captcha/add_captcha_module.md)
	* [修改登陆页面](login_captcha/login_page.md)
	* [修改登陆方法](login_captcha/login_method.md)
	* [页面测试](login_captcha/page_test.md)
* [为Shiro做准备](prepare_shiro/prepare_shiro.md)
	* [新增Permission类](prepare_shiro/add_permission.md)
	* [新增Role类](prepare_shiro/add_role.md)
	* [新的User类](prepare_shiro/new_user.md)
	* [新增UserService](prepare_shiro/user_service.md)
	* [修改MainSetup](prepare_shiro/modify_mainsetup.md)
	* [修改UserModule](prepare_shiro/modify_usermodule.md)
	* [重建数据库](prepare_shiro/rebuild_database.md)
	* [修改MainModule](prepare_shiro/modify_mainmodule.md)
	* [页面测试](prepare_shiro/page_test.md)
* [用Shiro做登陆](shiro_login/shiro_login.md)
	* [添加NutDaoRealm](shiro_login/nutdao_realm.md)
	* [修改shiro.ini](shiro_login/shiro_ini.md)
	* [复制登陆页面](shiro_login/login_jsp.md)
	* [添加跳转方法](shiro_login/to_login_jsp.md)
	* [页面测试](shiro_login/page_test.md)
* [入口方法的权限管理](shiro_method/shiro_method.md)
	* [修改动作链](shiro_method/shiro_chain.md)
	* [修改UserModule类](shiro_method/user_module.md)
	* [页面测试](shiro_method/page_test.md)
	* [真实项目的集成步骤](shiro_method/real_project.md)
* [进一步深入的准备](better_dev/better_dev.md)
	* [BaseModule类](better_dev/base_module.md)
	* [添加js库和css库](better_dev/js_css.md)
* [权限管理的页面及入口方法](authority/authority.md)
	* [新增AuthorityService及其实现类](authority/add_service.md)
	* [新增AuthorityModule](authority/add_module.md)
	* [修改UserModule的Shiro注解](authority/user_module_shiro.md)
	* [MainSetup中触发AuthorityService](authority/tigger_service.md)
	* [添加管理页面](authority/page.md)
	* [启动并观察日志](authority/startup_logs.md)
* [集成Ehcache及DaoCache](cache_system/cache_system.md)
	* [添加相关的Jar](cache_system/add_jars.md)
	* [添加ehcache.xml](cache_system/add_ehcache_xml.md)
	* [配置shiro.ini](cache_system/shiro.md)
	* [添加ehcache.js](cache_system/add_ehcache_js.md)
	* [MainSetup关联](cache_system/main_setup.md)
	* [修改BaseModule](cache_system/base_module.md)
	* [改造dao.js](cache_system/dao_js.md)
	* [启动Tomcat观察日志](cache_system/startup_logs.md)
* [集成Redis](redis_basic/redis_basic.md)
  * [启动redis](redis_basic/start_redis.md)
	* [添加相关的jar](redis_basic/add_jars.md)
	* [启用jedis插件](redis_basic/redis_iocby.md)
	* [在MainSetup中添加测试代码](redis_basic/main_setup.md)
	* [再在MainSetup中添加测试代码](redis_basic/main_aop.md)
* [集成模板引擎](templates/templates.md)
	* [集成jetbrick-template-2x](templates/jetbrick-template-2x.md)
	* [集成beetl](templates/beetl.md)
