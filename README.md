<!--
 * @Author: ravanla 1285644869@qq.com
 * @Date: 2024-09-02 21:19:28
 * @LastEditors: ravanla 1285644869@qq.com
 * @LastEditTime: 2024-09-03 15:07:18
 * @FilePath: \blog\README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# blog

### 安装hexo
安装前遇到的问题，遇到github连接问题，[解决方法](https://cloud.tencent.com/developer/article/2108855)
vpn的端口号没有设置正确，在代理设置中
export https_proxy=http://127.0.0.1:33210 http_proxy=http://127.0.0.1:33210 all_proxy=socks5://127.0.0.1:33211

环境
nvm use 20.17.0
npm --version
10.8.2

```
npm install -g hexo-cli
```

git clone 下来的项目要先 hexo init 目录，而这个目录要为空才能够初始化

```
PS D:\gitclone\blog> hexo init
FATAL D:\gitclone\blog not empty, please run `hexo init` on an empty folder and then copy your files into it
FATAL Something's wrong. Maybe you can find the solution here: https://hexo.io/docs/troubleshooting.html
Error: target not empty
```

我们可以把这里面的内容复制到另一个文件，然后再粘贴回来

