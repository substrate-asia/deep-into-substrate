# Outline - substrate交易相关组织逻辑

## Transaction, extrinsic 定义
  ### 3种extrinsic
  ### 交易的作用
  
## Substrate中交易的格式

## 客户端通过rpc发交易的验证
    ### subxt
    ### polkadotjs

## 交易池
    ### substrate中的交易池实现
    ### 校验规则
    ### Runtime参与的部分
    ### SignedExtensions

## 交易的广播

## 交易入块
    ### 块头的结构
    ### 交易在块中的组织
    ### tx merkle root
    ### 如何验证一个交易在块中
    ### 出块节点交易的执行，执行后的状态
    ### 块打包并广播

## 块导入时的工作
    ### 块导入时的校验
    ### 块导入时交易的执行
    ### 全局状态更新
    
## 交易的生命期总结

## Runtime中有关交易的几个Pallet
    ### System
    ### im
    ### transaction-payment
    ### ...

## 其它一些专题问题
    ### 如何创建不在网络上传播的交易
    ### OCW如何创建交易
