# 菩提树音乐
#### 介绍
菩提树音乐  
ptshu.github.io/y  
#### 文件说明
* 音乐源文件存放目录
  * http://pts.kuaiyunds.com/pts/  
  * 管理地址：https://storage.zzidc.com/storage/storageList/ 
  * 文件名不能有空格和大写，因为kuaiyunds在网页登录后会自动把文件名的空格去掉，大写改成小写。
* index.html
  * 主页  
* list.js
  * 音乐列表  
  注意yy目录和list.js文件要同时修改。


```
域名：www.ptsh.cf

音乐列表
	{
		title : '思念成霜 (DJ沈念版)',
		singer : '阿悠悠',
		cover  : '',
		src    : 'http://www.ptshu.cn/music/mp3/01.mp3'
	},
```

```

git add .
git commit -m “20040626”
git push origin master

git remote -v

git remote set-url origin git@github.com:ptshu/y.git


git add .
git commit -m “第一次上传”
git pull origin master --allow-unrelated-histories
git push origin master

```
