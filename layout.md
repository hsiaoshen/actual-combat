# 实战篇（二）
## 企业网站制作布局

### 基本知识点

1. 使用浮动来进行二栏布局
2. 使用子绝父相合margin来进行三栏布局
3. 可以多层混合布局
4. 在li前面添加箭头之类样式：list-style-image:url()
5. 对于使用图标和字体垂直不居中问题：可以给图片使用定位或者vertical-align:middle
6. 对于a标签的link等属性，必须href有值
7.有些时候可以使用backrgound-image来填充内容

### 第一步

进行网站分析进行布局

原则：自顶向下，从大局到细节

### 第二步：头部

结构：1个大div（top），width为100%；内含一个div（top_content）,width为980px;

### 第二步：内容区域

结构：整体用一个div来包含，设置宽高，margin:0 auto进行居中

#### 导航栏部分

结构：一个整体的nav，包含nav_left,nav_mid,nav_right三部分，nav_mid包含nav_mid_left（无序列表链接）和nav_mid_right（search_text,一个input）

