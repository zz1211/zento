# Zento

#### zento -> bento【盒饭】

Zento is a configuration-based solution to form.

## TODO

* [x] 表单配置化生成
* [ ] 支持表单联动配置
* [ ] 支持更细粒度的表单元素的动态控制

## Background

做了一个新员工入职的系统，该系统主要的部分是员工信息的收集，会有一个要收集很多的字段的表单。恩~，但是在这个时候：

* 设计师说：没时间，给的设计稿是参考作用的粗糙版本...
* 产品说：需求方不能够确定要收集的字段以及字段的信息聚合的方式，并且之后可能会要增删改的...
* 后端说：不做动态的成本太高，咱们这次做成写死的吧...

作为负责前端的开发的我表示：

<p align="center">
  <img width="400px" src="./godie.gif" />
</p>

对这种不稳定需求，浪费生命在无限的改动上面是对时间的极大的不尊重...所以配置化的生成表单是一定要做了的...zento是一个简单的基于配置的表单生成器，目前的主要价值就是解决了这次的这个不稳定需求。

【TBD】
