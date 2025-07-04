学习JavaScript数据结构与算法
====================================

[![构建状态](https://travis-ci.org/loiane/javascript-datastructures-algorithms.svg?branch=master)](https://travis-ci.org/loiane/javascript-datastructures-algorithms)
[![代码覆盖率](https://codecov.io/gh/loiane/javascript-datastructures-algorithms/branch/master/graph/badge.svg)](https://codecov.io/gh/loiane/javascript-datastructures-algorithms)
[![开发依赖状态](https://david-dm.org/loiane/javascript-datastructures-algorithms/dev-status.svg)](https://david-dm.org/loiane/javascript-datastructures-algorithms?type=dev)
[![依赖状态](https://david-dm.org/loiane/javascript-datastructures-algorithms/status.svg)](https://david-dm.org/loiane/javascript-datastructures-algorithms)
[![Greenkeeper badge](https://badges.greenkeeper.io/loiane/javascript-datastructures-algorithms.svg)](https://greenkeeper.io/)

《**学习JavaScript数据结构与算法**》第三版书籍源代码。

## 可用章节列表：

* 01: [JavaScript 快速概览](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter01_02)
* 02: [ECMAScript 和 TypeScript 介绍](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter01_02)
* 03: [数组](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter03)
* 04: [栈](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter04)
* 05: [队列和双端队列](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter05)
* 06: [链表](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter06)
* 07: [集合](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter07)
* 08: [字典和散列表](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter08)
* 09: [递归](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter09)
* 10: [树](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter10)
* 11: [堆](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter11)
* 12: [图](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter12)
* 13: [排序和搜索算法](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter13)
* 14: [算法设计与技巧](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter14)
* 15: [算法复杂度](https://github.com/loiane/javascript-datastructures-algorithms/tree/third-edition/examples/chapter15)

### 第三版更新内容

* 使用 ES2015+ (ES6+) 的算法实现
* 新的数据结构和算法
* 所有章节都经过重写和审查
* 新增三 (3) 个章节
* 创建了一个可在浏览器或 Node.js 中使用的数据结构和算法库
* 使用 Mocha + Chai 测试算法（测试代码在 `test` 目录中）
* 包含源代码的 **TypeScript** 版本（包括库和测试）

## 项目结构

`src/js/index.js` 文件包含按章节列出的所有数据结构和算法。

```
|_examples (如何使用每个数据结构和算法，按章节组织)
|_src 
|___js (源代码：JavaScript 版本)
|_____data-structures (数据结构)
|_______models (数据结构使用的类：Node、ValuePair 等)
|_____others (其他算法，如回文检查器、汉诺塔)
|___ts (源代码：TypeScript 版本)
|_____data-structures (数据结构)
|_______models (模型)
|_____others (其他算法)
|_test (使用 Mocha 和 Chai 对 src 进行单元测试)
|___js (JavaScript 代码测试)
|___ts (TypeScript 代码测试)
```

## 使用 Node.js 安装和运行书籍示例

* 安装 [Node](https://nodejs.org)
* 打开终端/命令提示符，切换到项目文件夹目录：`cd /Users/.../javascript-datastructures-algorithms` (Linux/Mac) 或 `cd C:/.../javascript-datastructures-algorithms` (Windows)
* 运行 `npm install` 安装所有依赖
* 要查看示例，运行 `http-server html` 或 `npm run serve`。在浏览器中打开 `http:\\localhost:8080` 查看书籍示例
* 或者 `cd html/chapter01` 并使用 node 运行每个 JavaScript 文件：`node 02-Variables`

## 在浏览器中运行示例

* 右键点击您想要查看示例的 HTML 文件，右键选择 "使用 Chrome（或任何其他浏览器）打开"

* 或者打开 `examples/index.html` 文件以轻松浏览所有示例：

* 在线演示：[https://javascript-ds-algorithms-book.firebaseapp.com](https://javascript-ds-algorithms-book.firebaseapp.com)

<img src="examples/examples-screenshot.png">

编程愉快！

## 其他版本

| 第一版   | 第二版   | 第三版   | 
| ------------- |:-------------:|:-------------:| 
| ![第一版](https://images-na.ssl-images-amazon.com/images/I/51xXGv7QlBL._SX403_BO1,204,203,200_.jpg)      | ![第二版](https://images-na.ssl-images-amazon.com/images/I/51PWJ%2BoKc2L._SX403_BO1,204,203,200_.jpg) | ![第三版](https://images-na.ssl-images-amazon.com/images/I/41oSXp3VztL._SX404_BO1,204,203,200_.jpg) |
| [书籍链接](http://amzn.to/1Y1OWPx)| [书籍链接](http://amzn.to/1TSkcA1)| [书籍链接](http://a.co/cbMlYmJ)|

第一版书籍链接：
  - [Packt](https://www.packtpub.com/application-development/learning-javascript-data-structures-and-algorithms)
  - [Amazon](http://amzn.to/1Y1OWPx)
  - [中文版](http://www.ituring.com.cn/book/1613)
  - [韩文版](http://www.acornpub.co.kr/book/javascript-data-structure)

第二版书籍链接：
 - [Packt](https://www.packtpub.com/web-development/learning-javascript-data-structures-and-algorithms-second-edition)
 - [Amazon](http://amzn.to/1TSkcA1)
 - [中文版](http://www.ituring.com.cn/book/2029)
 - [巴西葡萄牙语版](https://novatec.com.br/livros/estruturas-de-dados-algoritmos-em-javascript/)

第三版书籍链接：
 - [Packt](https://www.packtpub.com/en-us/product/learning-javascript-data-structures-and-algorithms-9781788624947)
 - [Amazon](http://a.co/cbMlYmJ)
 - [中文版](http://www.ituring.com.cn/book/2653)
 - [巴西葡萄牙语版](https://novatec.com.br/livros/estruturas-de-dados-algoritmos-em-javascript-2ed/)

### 发现问题或有疑问？

请创建一个 [Issue](https://github.com/loiane/javascript-datastructures-algorithms/issues) 或 [Pull Request](https://github.com/loiane/javascript-datastructures-algorithms/pulls) 