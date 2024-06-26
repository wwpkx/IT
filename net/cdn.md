---
mindmap-plugin: basic
---

# CDN
## 定义
- 内容分发网络（Content Delivery Network）
- CDN = 静态资源缓存 + 负载技术
- 目的: 提高访问速度，解决网络拥塞

## 理念
- **静态资源的就近访问**
    - **将内容缓存在终端用户附近**。比如，北京的访问北京的节点，上海的访问上海的节点
    - 更多的**缓存服务器（CDN边缘节点）**，布放在访问相对集中的地区或网络中
    - 多级缓存
- **全局负载技术**
    - 将用户指向最近的缓存服务器上响应用户请求

## 原理分析
- 打开网页
- DNS解析主机的IP地址
    - 应用CDN后，返回一个CNAME(Canonical Name) 别名记录，指向CDN的全局负载均衡
    - 得到**缓存服务器（CDN边缘节点）**ip地址
- 展示网页

## 衡量CDN服务质量的指标
- 命中率：用户访问的资源恰好在缓存系统里，可以直接返回给用户，命中次数与所有访问次数之比
- 回源率：缓存里没有，**必须用代理的方式回源站取**，回源次数与所有访问次数之比

## 能缓存的内容为静态内容
- 视频
- 网站的静态资源（例如各类型图片、html、css、js等）
- 移动应用APP的静态内容（例如安装包apk文件、APP内的图片视频等）

## 缺点
- **缓存机制可能导致内容不一致**
- CDN网络黑匣子分析不便
- CDN自身的潜在安全威胁

## 和镜像服务器的区别
- 镜像服务器是源内容服务器的完整复制。而CDN，是部分内容的缓存，智能程度更高。

## 和全站加速的区别
- https://www.elecfans.com/d/1909338.html


