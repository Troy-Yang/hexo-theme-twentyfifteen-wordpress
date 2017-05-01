# hexo-theme-twentyfifteen-wordpress

### Summary
This is a responsive hexo theme inspired by a very popular wordpress theme called [twentyfifeen](https://wordpress.org/themes/twentyfifteen/). Compared with the original theme, I did many enhancements to make it more lightweight and added more custom features like content UI changes, more supports for chinese.

### Online [Demo](http://troyyang.com/)
![image](http://ommnrsgt0.bkt.clouddn.com/hexo-2015-wordpress.jpg)
### Features
* **Responsive Design** - From smartphone, tablet, laptop, to desktop computer.
* **Lightweight** - Minimized the resources and layout.
* **multiple languages** - english, 简体, 繁體 
* **Highlight** - code highlight.
* **Comments** - Disqus, duoshuo, changyuan and so on.
* **Analytics** - Google, Baidu Analytics.
* **Custom Single Page** - Easy to add pages like "About".

### Configuration (_config.yml)

```
# ===========================================
# Site Settings
# ===========================================
# Header
site_title: Troy's Blog
site_description: Focus on Web Development and live in ChengDu. Happy Coding, Happy Life!
menu:
  Home: /
  Archives: /archives
  AboutMe: /about
# display widgets
widgets:
- archives
- recent_posts
- tagcloud
# widget behavior
archive_type: 'monthly'
show_count: true
# Content
excerpt_link: Read More
# favico 
favicon:

# ===========================================
# Miscellaneous Settings
# ===========================================
# Baidu Analytics
baidu_analytics: 
# Google Analytics
google_analytics: 
# Disqus
disqus:
  enable: false
  shortname: 
  count: true
# changyan
changyan:
  enable: false
  appid:
  appkey:
# duoshuo
duoshuo:
  enable: true
  shortname: 
```

### TODO
* Social links.
* Searching.
* photo gallery.
* Reading book Page - I would like to add a custom page to include the books I am reading, and did a comment for the books I read. Just want to leave a note for each book and encourage to consist reading.

### Github is used for programmer social, right? So, any advices would be welcome.
