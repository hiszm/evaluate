# evaluate

# 使用说明

1. 将这个 [https://hiszm.gitee.io/evaluate/](https://hiszm.gitee.io/evaluate/) 打开我的网站 拖拉到书签栏

或者这个[https://hiszm.github.io/evaluate/](https://hiszm.github.io/evaluate/)

2. 然后到学校教务系统 打开评价页面点击 书签栏的 一键脚本 即可



# 动图演示


![一键评教.gif](https://upload-images.jianshu.io/upload_images/5130027-e8db35fe8acf8abb.gif?imageMogr2/auto-orient/strip)

# 代码详解

```htlm
javascript:(
    function()
    {
        for (var i=1;i<=10;i++)
            {
                  document.getElementById("option_"+i+"_0").checked=true;//循环遍历整个页面中"优"选项并选中
  
            }
            var j=Math.floor(Math.random()*10+1);//随机出1-10个数字
            document.getElementById("option_"+j+"_1").checked=true;//为了防止全部优秀 提交不通过 所以9个优秀 随机一个良好
    }
)()
```



![希望对你有帮助](https://upload-images.jianshu.io/upload_images/5130027-4b83034bae462a23.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)






