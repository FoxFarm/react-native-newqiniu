# react-native-newqiniu
#React Native的七牛的库

#我们可以使用的一个简便的RN七牛库

#-------------------------------------------

#可以使用这个 npm i react-native-newqiniu 下载

#安装后：

import uploadFile from 'react-native-newqiniu'

 let formInput = {
       key: name,
       // formInput对象如何配置请参考七牛官方文档“直传文件”一节
   }
   uploadFile(files, uptoken, formInput, (success) => { successBack(success) }, 
  (failure) => { failureBack(failure) }, (progress) => { progressBack(progress) });
    

#其中的key是服务端发送的一个key：name
