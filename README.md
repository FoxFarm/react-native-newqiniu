# react-native-newqiniu
#React Native的七牛的库

#我们可以使用的一个简便的RN七牛库

#-------------------------------------------

#建议直接引入里面的code文件夹的文件

#安装后：

import uploadFile from 'XXXX路径'

 let formInput = {
       key: name,
       // formInput对象如何配置请参考七牛官方文档“直传文件”一节
   }
   uploadFile(files, uptoken, formInput, (success) => { successBack(success) }, 
  (failure) => { failureBack(failure) }, (progress) => { progressBack(progress) });
    

#其中的key是服务端发送的一个key：name
备注：
  不准备维护qiniu这个了
