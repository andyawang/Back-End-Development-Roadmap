# Back-End-Development-Roadmap
后台开发技术图谱，后台开发成长Roadmap

## 题记
从2013年毕业加入鹅厂，不知不觉已然过去10年。期间团队一直有同学反馈，有时对个人成长有些迷茫，缺少一个后台开发的全景技术图谱，来建立起体系化的知识结构。这里结合自己的后台研发经验，把实战中觉得重要的技能点，整理一个后台开发的成长RoadMap，希望最后给大家的成长一些参考和帮助

简单把成长RoadMap分成4个阶段：
1. 后台基础（初级）：掌握牢固的后台基础（go、os、tcpip...）并能熟练运用，为后面的发展打下地基
2. 工程素养（中级）：写出一手好代码，有扎实的微服务工程能力，运用好云原生和DevOps持续提升工程效率
3. 项目架构（高级）：有扎实严谨的系统架构设计能力，独立主导大中型项目落地，一切尽在掌握中
4. 综合素养（专家）：技术更多是工具，掌握管理、产品、商业、高效沟通协作等多维度能力，帮助业务创造价值

当然，研发是个非常重实践的活，快速过遍RoadMap有体系化的认识，重点还是日常工作的不断实践和精进。时间较仓促赶的初稿，后续持续更新并补些参考材料和书籍，如果内容有错误和疏漏，帮忙多评论指正

## 后台基础篇（初级）

### 编程语言
- 语法：数据类型、流程控制 if/for/switch、函数 func（闭包问题）
- 变量：声明var/短变量声明:=/重声明、指针（自动推导？）、作用域、类型推断 type
- 赋值：深拷贝和浅拷贝区别
- 类型转换：类型断言表达式x.(T)，使用泛型Any
- 容器：array/slice/set/map/sync.map，各容器的底层结构/操作性能/扩容策略/并发安全
- 数据结构和算法：queue/stack/heap、sort、使用gods库
- 面向对象OOP：struct/interface，组合的优缺点，值方法和指针方法区别
- 并发：goroutine/channels（源码走读），协程生命周期，无锁FIFO实现
- 协程调度器：GMP模型，MP数量和调度关系，抢占式调度策略
- 内存管理：内存分配器/垃圾回收器，GC/STW/三色标记法，栈空间/逃逸分析优化
- 并发控制：sync.WaitGroup/sync.Once，主协程等待子协程方法
- 上下文：context.Context，层级关系，取消信号context.WithCancel
- 同步机制：sync.Mutex/sync.RWMutex/sync.Cond/sync.atomic，各类的使用场景
- 网络：net net.Dial、rpc socket、http net.http，高性能golang服务器实现
- 缓冲区操作：strings.Builder/bytes.Buffer，io.Reader/io.Writer，性能对比和适用场景
- 对象池：sync.Pool，性能优化原理
- 文件：os.File，各类文件操作 os.OpenFile/os.Create
- 常用第三方库：gin/grpc-go（学习源码），protobuf/go-redis/gorm/kafka，看实际业务场景
- 错误处理：errors、panic/defer/recover、链式错误码Wrapping
- 测试：go test，单元测试Test（testing/assert）、性能测试Benchmark
- 调试分析：net/http/pprof、火焰图go-torch
- 包管理：Go Modules、版本管理、路径管理 GOPATH（src/bin/pkg）、package
### 数据结构和算法
### 操作系统
### 计算机网络

## 工程素养篇（中级）

### 编码能力
### 微服务架构
### 中间件
### 云原生&DevOps

## 系统架构篇（高级）

### 高性能
### 高可用
### 可扩展
### 系统安全
### 典型业务系统
### 项目实战 

## 综合素质篇（专家）

### 管理
### 产品
### 商业
### 软技能




