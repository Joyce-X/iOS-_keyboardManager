 在AppDelegate中导入头文件  `#import "IQKeyboardManager.h"`
在didFinishLaunch中进行全局设置:    

```  
//!< set keyboard
    [IQKeyboardManager sharedManager].enable = YES;
    
    [IQKeyboardManager sharedManager].shouldResignOnTouchOutside = YES;  
      
```   

在整个项目中就不用再担心键盘遮挡的问题了.