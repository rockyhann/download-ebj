# download-ebj
非原创，只是精简版通俗用法
打开ebj漫画阅读，打开开发者工具（我用的chrome）                                                               
打开console选项                                                                                
将老么长的那个代码上一页readme下面的那个js，复制到空白中，回车，显示成功                                                 
输入downloader.getHeight() 回车                                                    
输入downloader.getWidth() 回车                                                                   
【注】上两步是截取图片的宽和高，请务必将屏幕处于横屏（就是一屏能有左右两页）的状态。括号中要填数字，我阅读的漫画来自双叶社，高填1200，宽填844，如果你不知道一页的宽高是多少，可以先设个稍微大点的数，之后抓取之后，多出的部分会变成空白画布，通过ps可以截掉，然后就知道实际的大小了                          
输入downloader.start() 回车，【括号中是开始下载的页数，首页是0】然后就开始下载了，                                               
【记得把浏览器设置每次下载询问关掉，默认下载路径也记得改】                                                            
【操作的时候不要刷新界面，断网或刷新之后需要重新打开开发者工具，从头开始】                                                
【下载开始之后，会一直下到最后，但完事之后不会自己停，会重复下最后一页，所以记得盯着点，下完了就刷新一边，要不就会一直下】                               
