# blog-imgs 博客图床
## jsDelivr优化加速
* 这里详细说一下设定自定义域名，由于GitHub访问上传速度很慢，所以需要进行优化。
* 设定自定义域名的作用是，在图片上传后，PicGo会按照【自定义域名+储存路径+上传的图片名】的方式生成访问链接，放到粘贴板上
* 这里我们要使用 jsDelivr 加速访问，所以可以设置为`https://cdn.jsdelivr.net/gh/`用户名/图床仓库名 ，上传完毕后，我们就可以通过`https://cdn.jsdelivr.net/gh/<用户名>/<仓库名>/<文件及路径>`加速访问我们的图片了，例如设置为：`https://cdn.jsdelivr.net/gh/fudalijunyi/cdn/img/logo2.jpg`

* Tip：也可以使用版本号的方式，用 @符链接。格式为：`https://cdn.jsdelivr.net/gh/<用户名>/<仓库名>@[分支/版本号]/<文件及路径>`，例如：`https://cdn.jsdelivr.net/gh/fudalijunyi/cdn@1.01/img/logo2.jpg`  采用版本号的好处是无缓存限制，及时更新资源！
