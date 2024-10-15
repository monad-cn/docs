
# Monad 官网中文版

本项目旨在将 [Monad 的官方网站](https://docs.monad.xyz/)内容翻译成中文，以便更多的中文用户能够更好地理解和使用 Monad 的相关信息。


## 翻译目标

- **翻译内容**：将 Monad 官网的所有相关内容（包括文档、指南、技术细节等）翻译成中文。
- **保持一致性**：确保翻译内容准确、专业，并与原文保持一致。
- **提升可读性**：使用流畅的中文表达，使中文用户能够轻松理解。


## 项目结构

- **readme.md**：项目说明。
- **SUMMARY.md**：gitbook 章节目录。
- **content**：翻译的文章内容。
- **book.json**：gitbook 配置文件。


## 参与贡献

我们欢迎任何对项目感兴趣的开发者、翻译者和技术爱好者参与贡献！如果您想为翻译项目做贡献，请遵循以下步骤：

1. 为避免重复翻译，请先在 [issues](https://github.com/monad-cn/docs/issues) 中认领文章。管理员会对 `issue` 进行分配，得到分配后即确认认领。
2. 认领文章后 `Fork` 仓库，然后创建分支，建议以每一篇文章的翻译建立一个分支(如：`feature/why-blockchain`)。
3. 翻译好后提交 `PR` ，标题应该简洁明了，建议关联 `issue` 编号（如：Fixes #5）; 在 `PR` 描述中可以写一些存在疑问/不会/拿不准的翻译问题。
4. 由社区管理员认领审核或分配审核，对翻译内容进行交叉评审反馈。
5. 根据审核的意见和反馈，修改优化翻译内容并在本分支继续提交。
6. 由审核员和管理员确认无翻译问题后对本次 `PR` 进行合并，由管理员更新 `readme` 文件并关闭 `issue`。

完整的协作流程请参考示例 [issue](https://github.com/monad-cn/docs/issues/5)和 [PR](https://github.com/monad-cn/docs/pull/23)。


## 使用 GitBook 本地启动

可以在本地启动 `gitbook` 检查翻译内容和排版，请按照以下步骤操作：

1. 安装 `gitbook cli`

首先确保您已安装 [Node.js](https://nodejs.org/)。然后，使用以下命令全局安装：

```bash
npm install -g gitbook-cli
```

2. 安装依赖

```bash
gitbook install
```

注意：可以因为有的插件不支持你的`node`版本，如果报错可以切换到`node 10.x`版本后重试。

3. 本地启动

```bash
gitbook build
gitbook serve
```

打开浏览器并访问 http://localhost:4000 查看本地文档。


## Monad 官网

1. [简介](./content/introduction.md) ✅

2. [快速开始](./content/briefings/briefings.md)

   1. [用户使用教程](./content/briefings/monad-for-users.md)

   2. [开发者使用教程](./content/briefings/monad-for-developers.md)

3. [技术讨论](./content/technical-discussion/technical-discussion.md)
   
   1. [基本概念](./content/technical-discussion/concepts/concepts.md)
 
      1. [管道化](./content/technical-discussion/concepts/pipelining.md)
  
      2. [异步I/O](./content/technical-discussion/concepts/asynchronous-i-o.md)
   
   2. [为什么选择区块链](./content/technical-discussion/why-blockchain.md)

   3. [为什么选择Monad：去中心化+性能](./content/technical-discussion/why-monad-decentralization-+-performance.md)

   4. [Monad的共识层](./content/technical-discussion/consensus/consensus.md)
   
      1. [MonadBFT](./content/technical-discussion/consensus/monadbft.md)
   
      2. [共享的mempool](./content/technical-discussion/consensus/shared-mempool.md)
      
      3. [延迟执行](./content/technical-discussion/consensus/deferred-execution.md)
  
      4. [运输费用和储备余额](./content/technical-discussion/consensus/carriage-cost-and-reserve-balance.md)

   5. [Monad的执行层](./content/technical-discussion/execution/execution.md)
         
         1. [并行执行](./content/technical-discussion/execution/parallel-execution.md)
           
         2. [MonadDB](./content/technical-discussion/execution/monaddb.md)
  
   6. [Monad的交易流程](./content/technical-discussion/transaction-lifecycle-in-monad.md)
 
   7. [Monad的其他细节](./content/technical-discussion/other-details.md)

4. [使用Monad](./content/using-monad/using-monad.md)

   1. [运行Monad节点](./content/using-monad/running-a-node/running-a-node.md)
 
      1. [硬件需求](./content/using-monad/running-a-node/hardware-requirements.md)
  
   2. [在Monad上进行开发](./content/using-monad/developing-on-monad/developing-on-monad.md)
 
      1. [推荐阅读](./content/using-monad/developing-on-monad/suggested-resources/suggested-resources.md)
  
         1. [EVM行为](./content/using-monad/developing-on-monad/suggested-resources/evm-behavior.md)
   
         2. [进一步solidity阅读材料](./content/using-monad/developing-on-monad/suggested-resources/further-solidity-resources.md)
   
         3. [链上debugging](./content/using-monad/developing-on-monad/suggested-resources/debugging-on-chain.md)
   
         4. [其他合约语言](./content/using-monad/developing-on-monad/suggested-resources/other-languages/other-languages.md)
   
             1. [Vyper阅读材料](./content/using-monad/developing-on-monad/suggested-resources/other-languages/vyper-resources.md)
    
             2. [Huff阅读材料](./content/using-monad/developing-on-monad/suggested-resources/other-languages/huff-resources.md)

5. [官方链接](./content/official-links.md)

## 联系我们

如果您对本项目有任何问题或建议，请随时联系我(微信: `xxxfu`, 邮箱: `smallfu666@gmail.com`)。感谢您的支持和参与！

