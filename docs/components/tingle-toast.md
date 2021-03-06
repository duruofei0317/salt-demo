# tingle-toast

## Toast 浮层

目前包括 success/error/fail/loading/text 类型

![image](http://aligitlab.oss-cn-hangzhou-zmf.aliyuncs.com/uploads/tingle-ui/tingle-toast/0d001c10ad2af65005cc88dcd4d0c5a9/image.png)

## Simple Usage

```
Toast.show({
  type: 'success',
  content: '提交成功',
  onDidHide() {
      console.log('success tip is hidden');
  }
});
```

## APIs

### show(options)

#### options

type

* 描述：内置的集中类型，包括success，error，fail，loading.
* 类型：String
* 默认：''
* 必填：否

content

* 描述：提示文字
* 类型：String
* 默认：''
* 必填：否

autoHide

* 描述：是否自动隐藏
* 类型：Boolean
* 默认：true
* 必填：否

icon

* 描述：自动已的icon
* 类型：String
* 默认：''
* 必填：否

duration

* 描述：自动关闭的时间，单位ms
* 类型：Number
* 默认：1500
* 必填：否

onDidHide

* 描述：关闭后的回调函数
* 类型：Function
* 默认：noop
* 必填：否

width

* 描述：宽度
* 类型：String，Number
* 默认：'auto'
* 必填：否

height

* 描述：高度
* 类型：String，Number
* 默认：'auto'
* 必填：否

#### hide(onDidHide)

onDidHide

* 描述：关闭后的回调函数
* 类型：Function
* 默认：noop
* 必填：否

hasMask

* 描述：是有遮罩层
* 类型：boolean
* 默认：false
* 必填：否

## Links

- [Issues](https://github.com/salt-ui/saltui/issues/new)
