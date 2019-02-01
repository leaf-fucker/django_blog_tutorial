[![](https://img.shields.io/badge/python-3.7.0-orange.svg)](https://www.python.org/downloads/release/python-370/)
[![](https://img.shields.io/badge/django-2.1-green.svg)](https://docs.djangoproject.com/en/2.1/releases/2.1/)
[![](https://img.shields.io/badge/bootstrap-4.1.3-blue.svg)](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
[![](https://img.shields.io/badge/license-MIT-000000.svg)](https://opensource.org/licenses/MIT)

# Django搭建个人博客教程

这是面向新人的**Django搭建个人博客教程**的项目代码。

**教程为零基础的小白准备，目的是快速搭建一个博客网站。**

教程链接：[Django搭建个人博客](https://www.dusaiphoto.com/article/detail/2/)

## 教程特点
- 零基础、免费、中文、完整项目代码
- 基于最新的Python3.7、Django2.1和Bootstrap4版本
- **博主热情的技术支持！**

## 适合人群
- 拥有一台能开机的电脑
- 有一点点最基础的python编程知识
- 每天能抽出一个小时学习

不要犹豫，现在立刻开始Django的学习吧！

## 教程导航
1. [前言](https://www.dusaiphoto.com/article/detail/2/)
2. [搭建开发环境](https://www.dusaiphoto.com/article/detail/4/)
3. [创建并配置APP功能模块](https://www.dusaiphoto.com/article/detail/6/)
4. [编写博客文章的Model模型](https://www.dusaiphoto.com/article/detail/11/)
5. [View视图初探](https://www.dusaiphoto.com/article/detail/15/)
6. [改写文章View视图](https://www.dusaiphoto.com/article/detail/16/)
7. [使用 Bootstrap 4 改写模板文件](https://www.dusaiphoto.com/article/detail/18/)
8. [文章详情页面](https://www.dusaiphoto.com/article/detail/19/)
9. [使用Markdown语法书写文章](https://www.dusaiphoto.com/article/detail/20/)
10. [使用Form表单类发表新文章](https://www.dusaiphoto.com/article/detail/22/)
11. [删除文章功能](https://www.dusaiphoto.com/article/detail/25/)
12. [修改文章功能](https://www.dusaiphoto.com/article/detail/28/)
13. [用户的登录和登出](https://www.dusaiphoto.com/article/detail/31/)
14. [用户的注册](https://www.dusaiphoto.com/article/detail/32/)
15. [用户的删除](https://www.dusaiphoto.com/article/detail/33/)
16. [重置用户密码](https://www.dusaiphoto.com/article/detail/34/)
17. [扩展用户信息](https://www.dusaiphoto.com/article/detail/37/)
18. [上传头像图片](https://www.dusaiphoto.com/article/detail/38/)
19. [文章分页](https://www.dusaiphoto.com/article/detail/42/)
20. [统计文章浏览量](https://www.dusaiphoto.com/article/detail/45/)
21. [根据浏览量对最热文章排序](https://www.dusaiphoto.com/article/detail/46/)
22. [简单搜索博客文章](https://www.dusaiphoto.com/article/detail/47/)
23. [渲染Markdown文章目录](https://www.dusaiphoto.com/article/detail/48/)
24. [在博文中发表评论](https://www.dusaiphoto.com/article/detail/49/)
25. [结束和开始](https://www.dusaiphoto.com/article/detail/50/)
26. [基于类的视图](https://www.dusaiphoto.com/article/detail/52/)
27. [设置文章的栏目](https://www.dusaiphoto.com/article/detail/55/)

以及：
- [小功能集合](https://www.dusaiphoto.com/article/detail/53/)
- [读者常见问题](https://www.dusaiphoto.com/article/detail/43/)

**章节编号与GitHub仓库分支（Branch）编号是对应的。**

更多章节目前正在撰写中。

## 使用说明
确认你的电脑已经正确安装 Python 3 以上的版本。

下载项目后，在命令行中进入项目目录，并创建**虚拟环境**：

```bash
python -m venv env
```

运行**虚拟环境**（Windows环境）:

```bash
env\Scripts\activate.bat
```

或（Linux环境）：

```bash
source env/bin/activate
```

自动安装所有依赖项：

```bash
pip install -r requirements.txt
```

然后进行数据迁移：
```bash
python manage.py migrate
```

最后运行测试服务器：
```bash
python manage.py runserver
```

项目就运行起来了。

## 联系方式
- 简单问题，请在[杜赛的个人网站](https://www.dusaiphoto.com)留言
- 复杂问题，请Email私信我：dusaiphoto@foxmail.com