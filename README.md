###存储方式
分内存，磁盘两种方式，前者本次程序有效，后者其实采用归档方式，删除app前有效

###时效
分永久 和  定时两种， 支持时效存储（比如5分钟之内有效）

###支持类型
NSString, NSURL, NSData, NSNumber, NSDictionary, NSArray, NSNull, 自定义实体类（NSObject
）
###加密 
区别于NSUserDefault的存储方式，存储磁盘的所有数据都是AES加密，使用默认密匙

###快速缓存
缓存过一次的对象会自动加载到内存中，再次读取会直接从内存获取对象，减少文件消耗

###安全性
默认同步执行，线程安全，放心使用
