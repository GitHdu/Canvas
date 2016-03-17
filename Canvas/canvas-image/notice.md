 getImageData on 'CanvasRenderingContext2D': The canvas has been tainted by cross-origin data.
Uncaught SecurityError: Failed to execute 'getImageData' on 'CanvasRenderingContext2D': The canvas has been tainted by cross-origin data.


 getImageData存在跨域问题
 因为本地测试用的图片是文件夹内的，js跨域限制是不能获取非同一域名下的数据的，而本地的位置是没有域名的，所以浏览器都认为你是跨域，导致报错