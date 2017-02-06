# tdd-demo 


## a react+typescript+tdd demo
### while 'npm run test', our test will run automatically when the test files or project files change

### if the last time test is still running, it will kill the last test process, and run test from the start again.
react+typescript的tdd demo
当测试文件或者项目文件改变并保存是，我们的测试会自动运行。若这时上一次的测试还没有停止，会停掉上一次测试进程，并重新开始测试
 
### 1. cd tdd-demo
### 2. npm install ( install all the dependencies ) 
### 3. npm link typescript （ if you hava typescript in globale enviroment ）
### 4. npm start ( start the project )
### 5. npm run test ( start to run test )


```
说明
[在Penggggg/tdd-demo.git的基础上稍作修改后可以正常运行，原版的编译和运行时都会报错](https://github.com/Penggggg/tdd-demo.git)
1. 目录结构
src --- 组件的源码目录
test --- 项目的测试目录
 ├─business --- 项目业务测试代码
 └─component --- 项目UI组件测
 └─component --- 项目UI组件测试代码试代码
 
2. 运行测试代码
在安装完依赖后，直接gulp即可运行测试任务
```
