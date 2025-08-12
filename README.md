## 图书馆资源管理系统2

> [点我下载源码或在线试用](https://www.notmaker.com/detail/b3f32dbb42f54c159dbc6dfdbf9453ad/ghb20250812) 

> 支持定制、讲解、修改、远程调试

### 一、相关技术
- 后端：`Java`、`JavaWeb` / `Springboot`。
- 前端：`HTML` / `CSS` / `Javascript` 等。
- 数据库：`MySQL`

### 二、相关软件
- `IDEA`
- `Navicat`


### 三、功能描述
系统分为（身份）：读者、管理员。

**读者功能：**
1. 登录
2. 图书查询：根据书名或者分类进行查询
3. 个人信息：查看个人详细信息：读者号、姓名、用户名、性别、生日、地址、电话、角色
4. 我想还书：显示所有未还图书以及图书状态，如果图书超期或者到应还日期前15天，才能进行续借
5. 借还记录：显示所有已还图书和用户丢失图书进行赔偿的图书借还日志
6. 图书挂失：显示读者所有未还图书，附带挂失按钮，点击挂失 解挂：解挂 赔偿
7. 修改密码：对自己的登录密码进行修改，修改成功后退出系统到login页面 

**管理员功能：**
1. 登录
2. 图书管理：

添加图书：书名、作者、出版社、ISBM、简介、价格、出版日期、分类、数量

查询图书：根据书名或分类查询

删除图书：点击删除按钮即可

修改图书：点击修改按钮即进入修改界面

3. 用户管理：

添加用户：根据角色添加用户或者管理员

用户管理：对存在的用户或管理员进行删除，修改，查询

借还管理：用户借还书自动添加信息，如果超过指定日期，会显示催还按钮

修改密码：对自己的登录密码进行修改，修改成功后退出系统到login页面 

### 四、功能图（部分）

#### 读者端功能：
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:46:05_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:46:31_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:46:36_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:46:44_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:46:50_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:46:55_image.png)
#### 管理员端功能：
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:48:53_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:48:59_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:49:04_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:49:10_image.png)
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:49:15_image.png)

### 五、数据库展示
![image.png](https://store.ptcc9.top/notmaker/user_upload/02dab151e8504d5890fa01c3c12255bd/2025-02-22%2022:49:53_image.png)

### 六、源码附件

