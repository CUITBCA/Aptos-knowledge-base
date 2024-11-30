
## Move 开发者资料 

- [开发者文档中文版](https://aptos.dev/zh)  
- [开发者文档英文版](https://aptos.dev/en)  
- [开发者文档官方代码库](https://github.com/aptos-labs/aptos-core)
  
## Move语言简介

Move 是一种专注于安全性和灵活性的智能合约编程语言，最初为 Libra（后更名为 Diem）设计，借鉴了 Rust 的线性类型，**明确数据的所有权**，确保存储和访问的安全。
Aptos团队进一步增强了Move，支持更广泛的web3用例。正如后面在第5.5节中提到的，Aptos区块链支持精确的资源控制。这不仅支持并行处理交易，而且还实现了访问和修改数据的成本基本固定。
此外，Aptos区块链提供了建立在精确存储之上的用例支持，这允许在单个帐户中使用大规模的数据集(例如，大量的nft集合)。此外，Aptos支持完全在链上表示的共享或自治帐户。这允许复杂的分散式自治组织(DAOs)协作地共享帐户，并将这些帐户用作异构资源集合的容器。

## Move语言特点

### 安全性与灵活性：
- 对象模型：Aptos 使用 Move 的对象模型表示分类帐状态，并通过 Move 模块定义状态转换规则。
- 资源管理：强调资源的稀缺性和所有权，确保资源不可无故生成、重复使用或丢失。

### 工具生态：
包含编译器、虚拟机和开发工具。
提供字节码验证器，确保类型和内存安全。
Move 验证器支持形式化验证，确保程序功能的正确性。

### 链上功能：
- 模块可升级性：支持对区块链本身和链上配置（如验证节点、质押资产等）的动态调整。
- 资源控制：实现交易并行处理，数据修改成本低，支持大规模数据集和共享账户。

## Move On Aptos 相关共学资料

- [残酷共学]:(https://github.com/ALCOVE-LAB/intensive-colearning-aptos)<br>

  仓库下的Readme有关于Move语言从入门到高阶的资料和项目实践，同时仓库中还有其他学员在学习过程中输出的学习笔记

- Move On Aptos 春季共学营

  - [Notion资料]:()(https://alcove-pro.notion.site/Move-on-Aptos-alcove-bc0e60f57caa4f2195e06f89bfaedf8e?pvs=4) 这个资料包括了新手入门的了解和各种文档，以及课程的代码
  - [Google 云盘共学视频]:(https://drive.google.com/drive/folders/1-EmZXvuPuVH60XmbmFxUg1jDm6-uDDG2) 视频包括了Move语法的学习和实战，节奏很慢，适合学习



