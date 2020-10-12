# img-EXIF

手机拍照上传：压缩+修正图片旋转（已处理兼容问题）


### 效果：
chrome、safari浏览器上拍的照片显示是自动修正的、安卓机上，拍的照片显示旋转的

### 操作：
只需将安卓机上的照片代码修正下

### css hack：
image-orientation属性只在chrome、safari上生效。。。

### js检测属性支持
const isSupport = CSS.supports('image-orientation:none')

isSupport为false时，再去修正图片角度
