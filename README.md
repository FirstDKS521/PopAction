# PopAction

在获取系统的返回按钮时，通过

```
https://github.com/onegray/UIViewController-BackButtonHandler
```
这个第三方库，是能够实现获取点击系统的返回按钮事件，但是此时，通过右划的手势就失败了，我对此进行了一些调整，添加了获取手势的方法；

具体的使用方法，还是和这个库一样，不过手势和点击返回按钮都是用的一个方法，如果用到的话，根据具体的业务进行定制吧！在使用的ViewController中，实现下面的方法：

```
- (BOOL)navigationShouldPopOnBackButton;
```