其实模糊的主要原因是`translate3d`, 如果仅仅使用`translateY(-50%) | top:50%` 这样是不会出现模糊的

再就是即便是用translate3d想不模糊也是有办法的, 就是元素的`盒模型的宽度不能是奇数`(宽度包含padding), 这么一来垂直居中模糊就解决了
