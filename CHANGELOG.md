# CHANGELOG

## version


### 0.0.19

修复 dateView 和 picker 样式冲突问题


### 0.0.17

修复 dateView 和 picker 样式冲突问题

### 0.0.16

新增 dateView

### 0.0.15

修复 confirm 的样式问题 并去除 title dom

### 0.0.14

alert 样式变更

### 0.0.13

datetime picker && popup picker 共同使用 scroll
修复 .scroller-indicator 样式错误

### 0.0.12

datetime picker 样式变更
主题颜色变更 popup-picker 样式变更

### 0.0.11

popup-picker 确认按钮变更 data-test

### 0.0.10

popup-picker 增加 select value 功能

```
  const event = new CustomEvent('selectValue', {
      detail: {
        value: formValue,
      },
    });

    cy.get('[data-test="' + formName + '-popup-picker"]')
      .find('.vux-picker')
      .then(el => {
        el.get(0).dispatchEvent(event);
      });

```

### 0.0.9

date-time 增加 data-test 选择器 命名为 data-test=datetime-\${formName}

### 0.0.8

popup-picker 增加了 column label 用于显示表单名

### 0.0.7

popup-picker 增加完成 id 赋值 用于测试

### 0.0.6

删除 development 时的 warn 警告

### 0.0.5

删除 vux-loader 相关提示

### 0.0.4

修复'../inline-x-switch/style.less' 样式缺失

### 0.0.3

修复 x-input 组件的依赖缺失 vanilla-masker

### 0.0.2

修复 x-input 组件的依赖缺失 validator

### 0.0.1

简化 vux，初始版本
