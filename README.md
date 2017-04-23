# animateDemo
> 封装了常用的app页面跳转动画,喜欢的话就带走吧

**效果如下：**

![animation](https://ww3.sinaimg.cn/large/006tNc79gy1fewqe9soppg308k0fwn5a.gif)



> 使用方法如下  

  ```
  FirstViewController *first =[[FirstViewController alloc]init];
  [self.navigationController pushViewController:first animated:NO];
  CATransition *animate =[MMAnimate getAnimation:1];//此处的1 可以换成任何你想要的效果编号
  [self.navigationController.view.layer addAnimation:animate forKey:nil];

  ```

