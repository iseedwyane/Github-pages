# Site settings
title: Sen's Blog
SEOTitle: 李森的博客 |  Sen's Blog
header-img: img/post-bg-coffee.jpg
email: lisen.robotics@gmail.com
description: "Experience more when you are young."
keyword: "Sen, Sen's Blog, 李森的博客, lisen, 李森, robotics"
url: "http://iseedwyane.github.io"          # your host, for absolute URL
baseurl: ""      # for example, '/blog' if your blog hosted on 'host/blog'
github_repo: "https://github.com/iseedwyane/iseedwyane.github.io.git" # you code repository

# Sidebar settings
sidebar: true                           # whether or not using Sidebar.
sidebar-about-description: "Keep driven!"
sidebar-avatar: /img/1.jpeg      # use absolute URL, seeing it's used in both `/` and `/about/`



# SNS settings
RSS: false
# weibo_username:     qiubaiying
zhihu_username:     lianlianbijiben
github_username:    iseedwyane
#facebook_username:  baiying.qiu.7
#jianshu_username:   e71990ada2fd
#twitter_username:   qiubaiying




# Build settings
# from 2016, 'pygments' is unsupported on GitHub Pages. Use 'rouge' for highlighting instead.
permalink: pretty
paginate: 10
exclude: ["less","node_modules","Gruntfile.js","package.json","README.md"]
anchorjs: true                          # if you want to customize anchor. check out line:181 of `post.html`



# Gems
# from PR#40, to support local preview for Jekyll 3.0
gems: [jekyll-paginate]




# Markdown settings
# replace redcarpet to kramdown,
# although redcarpet can auto highlight code, the lack of header-id make the catalog impossible, so I switch to kramdown
# document: http://jekyllrb.com/docs/configuration/#kramdown
markdown: kramdown
highlighter: rouge
kramdown:
  input: GFM                            # use Github Flavored Markdown !important



# 评论系统
# Disqus（https://disqus.com/）
# disqus_username: qiubaiying

# Gitalk
gitalk:
  enable: true    #是否开启Gitalk评论
  clientID: d6a7d82317510f24590d                            #生成的clientID
  clientSecret: c7931d59ea48dceb49e7fe971526053f039bae4c    #生成的clientSecret
  repo: qiubaiying.github.io    #仓库名称
  owner: iseedwyane    #github用户名
  admin: iseedwyane
  distractionFreeMode: true #是否启用类似FB的阴影遮罩


# 统计

# Analytics settings
# Baidu Analytics
ba_track_id: b50bf2b12b5338a1845e33832976fd68

# Google Analytics
ga_track_id: 'UA-90855596-1'            # Format: UA-xxxxxx-xx Q1:没有找到
ga_domain: auto               # 默认的是 auto, 这里我是自定义了的域名，你如果没有自己的域名，需要改成auto





# Featured Tags
featured-tags: true                     # 是否使用首页标签
featured-condition-size: 0              # 相同标签数量大于这个数，才会出现在首页



# Progressive Web Apps
chrome-tab-theme-color: "#000000"
service-worker: true



# Friends
friends: [
    {
        title: "Apple",
        href: "https://apple.com"
    },{
        title: "Apple Developer",
        href: "https://developer.apple.com/"
    }
]
