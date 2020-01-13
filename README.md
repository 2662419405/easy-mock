<div align="center">

#  easy-mock数据接口


> 说明:  由于eask-mock访问量过大,总是出现无法访问或者不安全链接等等神奇的操作,=-=,[原官网](https://www.easy-mock.com/),所以我只好自己踩坑去安装easy-mock数据接口,期间内也是遇到了很多神奇的问题,**!竟然要求node版本是8.^.版本!**,这可是很古老了,然后又去学习和安装了[nvm](https://www.jianshu.com/p/0ffa636a6fe1),反正一大堆坑!!!



**关于如何使用mock数据,请查看 [mockjs](http://mockjs.com/)**



## 自己如何安装?

1. 安装node (版本>11)  参考 -> [菜鸟教程](https://www.runoob.com/nodejs/nodejs-install-setup.html)

2. 安装redis -> [菜鸟教程](https://www.runoob.com/redis/redis-install.html)

3. 安装mongod -> [菜鸟教程](https://www.runoob.com/mongodb/mongodb-tutorial.html)

4. 保证redis和mongod在后台运行中

5. ` git clone https://github.com/2662419405/easy-mock.git `

6. `cd eacy-mock && npm i `

7. `npm run build`

8. 如果没有pm2,需要先安装pm2  ->    `npm i -g pm2`

   `NODE_ENV=production pm2 start app.js`

<img src="https://cdn.jsdelivr.net/gh/2662419405/imgPlus/Snipaste_2020-01-13_14-44-15.png" />

9. 在7300端口上面就可以访问了 -> [本人的Easy-mock](http://shtodream.cn:7300/)

<img src="https://cdn.jsdelivr.net/gh/2662419405/imgPlus/Snipaste_2020-01-13_14-49-55.jpg" />

**有问题欢迎留言**