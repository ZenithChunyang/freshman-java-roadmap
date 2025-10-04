阶段一、java基础
# Java 后端学习路线图 · 35 天打卡记录

&gt; 零基础 → Spring Boot 入门前的主线日程  
&gt; 状态标签：  
&gt; - `✅ 已完成`  
&gt; - `🔁 学习中`  
&gt; - `⏸️ 跳过/暂缓`  
&gt; - `📎 笔记/代码链接`  

| Day | 主题 | 状态 | 备注/仓库链接 |
|----:|:----|:-----|:--------------|
| 01 | Java 入门 | ✅ | 环境搭建 + HelloWorld |
| 02 | Java 基础概念 | ✅ | 注释、关键字、变量 |
| 03 | 运算符 | ✅ | 算术、逻辑、三目 |
| 04 | 判断和循环 | ✅ | if / switch / for |
| 05 | 循环高级 + 数组 | ✅ | 二维数组、增强 for |
| 06 | 方法 | ✅ | 重载、递归 |
| 07 | 综合练习 | ✅ | 小案例合集 |
| 08 | 面向对象 | ✅ | 类、对象、封装 |
| 09 | 面向对象综合训练 | ✅ | 学生类、汽车类 |
| 10 | 字符串 | ✅ | String 常用 API |
| 11 | 集合 & 学生管理系统 | ✅ | ArrayList 实战 |
| 12 | 学生管理系统升级版 | ✅ | 集合嵌套 |
| 13 | static & 继承 | ✅ | 内存图、super |
| 14 | 多态 & 包 & final & 权限修饰符 & 代码块 | ✅ | 多态三道题 |
| 15 | 抽象类 & 接口 & 内部类 | ✅ | 重点：接口默认方法 |
| 16 | 面向对象综合练习（上）- 拼图游戏 GUI | ⏸️ | 仅提取切图算法，[代码📎](src/split/PuzzleUtil.java) |
| 17 | 面向对象综合练习（下）- 拼图游戏 GUI | ⏸️ | 跳过 GUI，见 Day-16 备注 |
| 18 | API（常见 API + 对象克隆） | 🔁 | Objects、Math、System |
| 19 | API（正则表达式） | 🔁 | 记住 `\d \w ? * +` |
| 20 | API（时间 + 包装类） | 🔁 | LocalDateTime、Integer 缓存 |
| 21 | API（算法 + Lambda） | 🔁 | Stream 预热 |
| 22 | List 集合 | 🔁 | ArrayList 源码 |
| 23 | 泛型 & Set & 数据结构 | 🔁 | HashSet 去重原理 |
| 24 | Map & 可变参数 & 工具类 | 🔁 | HashMap 链表→红黑树 |
| 25 | 阶段项目 - 斗地主游戏（GUI） | ⏸️ | 仅保留洗牌算法 |
| 26 | Stream 流 + 方法引用 | 🔁 | 链式练习 10 题 |
| 27 | IO（异常 + File） | 🔁 | Files.walk、递归删除 |
| 28 | IO（字节流 + 字符流） | 🔁 | try-with-resources |
| 29 | IO（其他流） | 🔁 | 缓冲流、对象流 |
| 30 | 阶段综合 - 带权重随机 & 日记本（GUI） | ⏸️ | 权重算法已提取，[笔记📎](docs/weight_random.md) |
| 31 | 多线程基础 | 🔁 | Thread、Runnable、synchronized |
| 32 | JUC 高级并发 | 🔁 | 线程池、CAS、ConcurrentHashMap |
| 33 | 网络编程 | 🔁 | TCP 三次握手代码验证 |
| 34 | 阶段项目 - 聊天室（GUI+Socket） | ⏸️ | 只保留多线程收发逻辑 |
| 35 | 反射 + 动态代理 | 🔁 | 手写 JDK 动态代理 |
| 36 | 日志 + 注解 + 单元测试 + XML | 🔁 | JUnit5、Slf4j、自定义注解 |

---

## 下一阶段计划（Day37 起）

| 板块 | 目标 | 预计天数 |
|:-----|:-----|:---------|
| Maven & Git 进阶 | 多模块、分支管理、标签 | 2 d |
| Spring Boot 入门 | REST + MyBatis + MySQL | 5 d |
| 小项目实战 | 控制台/REST 拼图双版本 | 3 d |
| 并发文件下载器 | 线程池 + NIO | 2 d |
|  Redis 排行榜 | 拼图最佳时间排行 | 2 d |

&gt; 全部进度会更新在 [`issues`](../../issues) 每月里程碑。

---

## 使用方式

1. 复制本文件到仓库根目录 `README.md`  
2. 每天 push 代码后顺手改状态 + 加链接  
3. 用 GitHub Projects 看板拖动卡片，可视化进度 👉 [Projects](../../projects)

---

**今日打卡格式示例（复制到 issue 即可）：**  
```text
Day-18 ✅ 
笔记：https://github.com/yourname/java-roadmap/issues/18
