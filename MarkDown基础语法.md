# MarkDown语法
## 标题
换行  末尾两个空格  
*斜体文本*  
**粗体文本**
<!-- *** 分割线 -->
***
~~删除线~~  
<u>下划线</u>  
后缀[^脚注]  
+ 第一条
- 第二条
* 第三条  
1. 第一条
    + 子列
    + 子列
2. 第二条  
> 区块  
>> 区块第二层  

`printf()` 函数 反引号 
    
    四个空格 代码块
    public static void main(){
      System.out.println();
    }

```java
// 三个反引号指定语言
public static void main(){
      System.out.println();
    }
```
[链接](https://www.baidu.com)   
![图片](https://www.baidu.com/img/dong_8f1d47bcb77d74a1e029d8cbb3b33854.gif)  

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |  

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

<!-- 不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写 -->
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

**文本加粗**  
\*\* 正常显示星号 \*\*  

```mermaid
        gantt
        dateFormat  YYYY-MM-DD
        title 软件开发甘特图
        section 设计
        需求                      :done,    des1, 2014-01-06,2014-01-08
        原型                      :active,  des2, 2014-01-09, 3d
        UI设计                     :         des3, after des2, 5d
    未来任务                     :         des4, after des3, 5d
        section 开发
        学习准备理解需求                      :crit, done, 2014-01-06,24h
        设计框架                             :crit, done, after des2, 2d
        开发                                 :crit, active, 3d
        未来任务                              :crit, 5d
        耍                                   :2d
        section 测试
        功能测试                              :active, a1, after des3, 3d
        压力测试                               :after a1  , 20h
        测试报告                               : 48h
```  

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$

```mermaid
graph LR;
　　Portal-->|发布/更新配置|Apollo配置中心;
　　Apollo配置中心-->|实时推送|App;
　　App-->|实时查询|Apollo配置中心;
```