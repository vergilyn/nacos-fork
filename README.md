# nacos-fork

- nacos: <https://github.com/alibaba/nacos>
- nacos-group: <https://github.com/>
- nacos-spring-boot-project: <https://github.com/nacos-group/nacos-spring-boot-project>
- nacos-examples: <https://github.com/nacos-group/nacos-examples>

## 源码启动
1. `nacos-console | com.alibaba.nacos.Nacos`

2. 修改配置：`distribution | conf | application.properties`


3. 启动参数设置(VM options)
```
-Dnacos.standalone=true -Dnacos.home="D:\VergiLyn\Workspace Git\nacos-fork\distribution"
```
（因为路径中存在**空格**，所以用**双引号**包含）

4. 访问：http://127.0.0.1:8848/nacos

通过启动信息可知，logs/conf/data 保存的目录即`nacos.home`指定的目录：
- D:\VergiLyn\Workspace Git\nacos-fork\distribution\logs
- D:\VergiLyn\Workspace Git\nacos-fork\distribution\conf
- D:\VergiLyn\Workspace Git\nacos-fork\distribution\data
