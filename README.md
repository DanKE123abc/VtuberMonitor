# VtuberMonitor

### **这是一个很渣很渣很渣的项目，纯粹是为了方便自己看虚拟主播**

![示例图片](https://raw.githubusercontent.com/DanKE123abc/VtuberMonitoring/main/example.png)本网站为静态网站，无需配置，开箱即用！

使用<iframe>标签转接bilibili直播，估计不懂编程的同学也看得懂

------



### #添加虚拟主播

###### 1. 打开/foot.html

###### 2. 在如下代码中添加自己爱看的虚拟主播

```
<select name="zhubo" id="zhubo" onchange="change()">
            <!--
                这里是蛋壳爱看的虚拟主播，你可以根据你的爱好自行修改
                格式：
                <option value="直播间号">主播名称</option>
            -->
            <option value="null">请选择直播间</option>
            <option value="2233">这里是一个直播间示例</option>
        </select>
```

