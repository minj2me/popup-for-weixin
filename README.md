# popup-for-weixin
微信小程序 自定义可交互弹窗

1.引入component/popUp

2.is-show-pop-up="{{isShowModal}}"来控制popUp的弹出和关闭

3.bind:closepopup="modalClosed"方法

```
modalClosed(e){
  if (e.detail.confirm){
    //用户点击确定
  }else{
    //用户点击取消
  }
}
```
