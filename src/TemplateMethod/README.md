# 模板方法模式

## 简介

定义一个操作中的算法骨架，而将一些步骤延迟到子类中。模板方法使得子类可以不改变一个算法的结构而可重新定义该算法的某些特定步骤。

## 使用场景

当我们要完成在某一细节层次一致的一个过程或一系列步骤，但其个别步骤在更详细的层次上实现可能不同时，我们通常考虑用模板方法模式处理。