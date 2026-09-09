# 让海报上的二维码有内容可看

二维码指向：https://github.com/xiaoyanwu2024/cogmap-ssd

只需要一件事：把 `README.md` 放进这个仓库的根目录。GitHub 会把 README 直接
渲染在仓库首页上，扫码的人一进来就看到两篇文章的标题、一句话简介和链接，
自己点想看的那篇。

    # 如果仓库还没建，先在 github.com 上新建一个 public 仓库 cogmap-ssd
    git clone https://github.com/xiaoyanwu2024/cogmap-ssd.git
    cd cogmap-ssd
    cp <这个文件夹>/README.md .
    git add README.md && git commit -m "Add ECNP poster landing page" && git push

两点要注意：
- 仓库必须是 **public**，private 的话扫码的人会看到 404
- 仓库名 `cogmap-ssd` 的拼写和大小写不能改，否则二维码就对不上了

推上去之后打开那个地址确认一下，再拿手机扫一次海报上的二维码。
换地址的话告诉我，我重新生成二维码。

（原来准备的 GitHub Pages 版 index.html 已经用不上了，留在 unused/ 里。）
