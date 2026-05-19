# 优豆：一款干净的拼豆图纸生成器


一键将图片（jpg,jepg,png）转化为拼豆！给您最简便，最快捷的拼豆体验：

* 可调节图纸大小
* 可简化色彩，使用更少的色号完成图纸

## 项目简介
 
基于HTML+JavaScript构建的静态网站

## 实现流程

1. 像素化图片
2. 色域统一转换为rgb色彩
3. 将rgb色彩映射到色号中，MARD_RGBmap.csv中有 色号->rgb 的映射，我们要通过聚类分析构建逆映射
https://blog.csdn.net/weixin_41566313/article/details/157097969
1. 