# Red/System语言规范
**Red/System Language Specification 中文翻译计划**

原文地址：http://static.red-lang.org/red-system-specs-light.html

### 翻译流程
1. 克隆仓库到本地
2. 编辑README.md，在要翻译的章节后写上自己的名字并提交，以便让他人知道此章已有人在翻译
3. 在本地进行翻译
4. 翻译好后在章节前打钩，再提交PR即可

**由于没有原始文档，因此所有内容都是在HTML内编辑的**

### 翻译进度(打勾表示已翻译)

- [x] 1. 概要([Xuehua Cai][pixcai])

- [x] 2. 语法([Xuehua Cai][pixcai])

  - [x] 2.1 分隔符([Xuehua Cai][pixcai])
  - [x] 2.2 范式无关语法([Xuehua Cai][pixcai])
  - [x] 2.3 注释([Xuehua Cai][pixcai])

- [ ] 3. 变量

  - [ ] 3.1 设置值
  - [ ] 3.2 获取值
  - [ ] 3.3 类型声明 

- [ ] 4. 数据类型
  
  - [ ] 4.1 整数
  - [ ] 4.2 字节
  - [ ] 4.3 浮点数
  - [ ] 4.4 32位浮点数
  - [ ] 4.5 逻辑值
  - [ ] 4.6 C语言字符串
  - [ ] 4.7 结构体
  - [ ] 4.8 指针
  - [ ] 4.9 类型转换
  - [ ] 4.10 大小

- [x] 5. 表达式([Xuehua Cai][pixcai])

  - [x] 5.1 一般性规则([Xuehua Cai][pixcai])
  - [x] 5.2 执行顺序规则([Xuehua Cai][pixcai])

- [ ] 6. 函数

  - [ ] 6.1 声明
  - [ ] 6.2 返回值
  - [ ] 6.3 属性
  - [ ] 6.4 类型推断
  - [ ] 6.5 函数调用
  - [ ] 6.6 函数指针
  - [ ] 6.7 提前退出

- [ ] 7. 作用域

  - [ ] 7.1 全局上下文
  - [ ] 7.2 函数上下文
  - [ ] 7.3 命名空间

- [ ] 8. 中缀操作符

  - [ ] 8.1 数学操作符
  - [ ] 8.2 移位操作符
  - [ ] 8.3 位操作符
  - [ ] 8.4 比较操作符

- [ ] 9. 控制流函数

  - [ ] 9.1 if
  - [ ] 9.2 either
  - [ ] 9.3 loop
  - [ ] 9.4 until
  - [ ] 9.5 while
  - [ ] 9.6 break
  - [ ] 9.7 continue
  - [ ] 9.8 any
  - [ ] 9.9 all
  - [ ] 9.10 case
  - [ ] 9.11 switch

- [ ] 10. 异常

  - [ ] 10.1 throw
  - [ ] 10.2 catch
  - [ ] 10.3 异常值

- [ ] 11. 栈函数

  - [ ] 11.1 push
  - [ ] 11.2 pop

- [x] 12. 调试函数([Xuehua Cai][pixcai])

  - [x] 12.1 assert([Xuehua Cai][pixcai])

- [ ] 13. 系统结构体

  - [ ] 13.1 args-count
  - [ ] 13.2 args-list
  - [ ] 13.3 env-vars
  - [ ] 13.4 stack/top
  - [ ] 13.5 stack/frame
  - [ ] 13.6 stack/align
  - [ ] 13.7 stack/allocate
  - [ ] 13.8 stack/free
  - [ ] 13.9 pc
  - [ ] 13.10 cpu
  - [ ] 13.11 cpu/overflow?
  - [ ] 13.12 fpu/type
  - [ ] 13.13 fpu/option
  - [ ] 13.14 fpu/mask
  - [ ] 13.15 fpu/control-word
  - [ ] 13.16 fpu/epsilon
  - [ ] 13.17 fpu/update
  - [ ] 13.18 fpu/init
  - [ ] 13.19 alias

- [ ] 14. 编译器指令

- [ ] 15. 导入外部库

  - [ ] 15.1 #import
  - [ ] 15.2 #syscall

- [ ] 16. 预处理指令

  - [ ] 16.1 #define
  - [ ] 16.2 #enum
  - [ ] 16.3 #include
  - [ ] 16.4 #if
  - [ ] 16.5 #either
  - [ ] 16.6 #switch
  - [ ] 16.7 #verbose
  - [ ] 16.8 #call
  - [ ] 16.9 #export
  - [ ] 16.10 #u16

- [ ] 17. 代码组织

  - [ ] 17.1 源文件后缀
  - [ ] 17.2 文件头
  - [ ] 17.3 代码布局
  - [ ] 17.4 编码指南
  - [ ] 17.5 共享库程序
  - [ ] 17.6 驱动程序

- [x] 18. 保留关键字([Xuehua Cai][pixcai])

- [ ] 19. 未来的改进

  - [ ] 19.1 变量
  - [ ] 19.2 指针
  - [ ] 19.3 结构体
  - [ ] 19.4 C语言字符串
  - [ ] 19.5 逻辑值
  - [ ] 19.6 整数
  - [ ] 19.7 函数
  - [ ] 19.8 新的数据类型
  - [ ] 19.9 新的函数
  - [ ] 19.10 其它

- [ ] 20. 文档历史记录

[pixcai]: https://github.com/pixcai
