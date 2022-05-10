# ZXingProject    
简介：条形码、二维码解析工具类    

核心功能：    
1.提供一维码（条形码）和二维码的生成    
2.提供一维码（条形码）和二维码的解析操作    
3.依赖于Zxing的基础服务，在此基础上进行封装和处理，方便直接使用    
4.附带单元测试，可自行替换条码生成路径来校验效果    
5.图片角度翻转功能    
6.图片放大缩小功能    
7.Bitmap、byt、Image之间的转化    
8.生成一维码（条形码）-GetBarCode    
9.生成二维码-GetQrCode    
10.解析条码（一维、二维通用）-Decode    
11.图片角度转换-ImageRotate    
12.按比例缩放图片-ZoomPicture、GetThumbnail    
13.重试并将图片按比例放大 - RetryCount （解析失败后重试）    
