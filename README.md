# Books-Recycling-wechat-applet-旧书回收微信小程序
Recycling旧书回收微信小程序，让大学生们可以线上预约回收旧书，通过约定特定的地点和时间，等待志愿者上门回收，以此提高学生捐书积极性。学生们也可以通过该小程序的公示信息，了解校内投书点以及各种注意事项，实现自助投书。志愿者回收的旧书将被回收或者捐赠给山区，特定的书籍将存放在特定地点供下一届学生循环使用，以此达到公益环保的目的。
## 软件功能结构图
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/9f59163f-d8cd-47be-96d1-a49b642398e9)
## 功能概述
（1）首页  

用户进入小程序之后，进入首页。该页面由旧书回收轮播海报，投物规则，投递点，公益捐赠，志愿组织，预约模块组成。 
（2）投物规则页面
点击首页投物规则按钮，跳转至投物规则的详情页面。页面介绍了自助回收和上门回收投书的规则，包括可投物品类型和不可投物品类型。
（3）投递点页面
点击首页投递点按钮，跳转至投递点的详情页面。页面介绍了校内自助投书箱分布地点。
（4）公益捐赠页面
点击首页公益捐赠按钮，跳转至公益捐赠的详情页面。页面介绍了捐赠的书籍用处。
（5）志愿组织页面
点击首页志愿组织按钮，跳转至志愿组织的详情页面。页面介绍了校内志愿者所属组织。
（6）预约页面
点击首页“点击参与旧书回收”按钮，跳转至预约详情页面。页面要求学生填写回收旧书及个人的基本信息，包括姓名，手机号码，回收地址，回收日期，回收时间段，旧书数量。用户需要填写全部信息，否则会提示要求填写所有信息。填写完成后点击“点击预约回收”按钮，即成功提交预约订单。
（7）订单页面
点击小程序底部“订单”按钮，跳转至订单详情页面。显示所有订单，预约中订单，进行中订单，已完成订单信息。用户点击顶部不同类型订单按钮，查看相应的订单信息及状态。
（8）我的页面
点击小程序底部“我的”按钮，跳转至“我的”详情页面。页面包括该该用户头像，昵称展示，志愿者管理员登录，信息反馈，在线客服功能。若用户从未登陆过，页面下部将显示登录按钮，用户点击进行登录即可。登录后显示用户头像和昵称以及底部的注销按钮，用户点击注销按钮即可退出登录。
（9）志愿者管理员登录
点击“我的”页面志愿者管理员登录，跳转管理员登录界面，用户输入正确的用户名密码跳转至订单信息管理页面。不成功显示用户名密码错误信息。
（10）订单信息管理页面
进入到订单信息管理页面，显示预约中订单，进行中订单，已完成订单信息，每一个订单下面有一个确认预约或确认完成按钮。志愿者点击顶部不同类型订单按钮，查看并操作相应的订单，收到预约信息后点击确认预约，完成活动后点击确认完成按钮实现订单状态的更改。
（11）联系客服
点击我的页面里的联系客服，即可咨询在线客服。
（12）意见反馈
点击我的页面里的意见反馈，跳转至意见反馈页面，填写意见反馈，提交给客服。
## 功能概述
用户包括学生，志愿者，后台管理人员三个角色。
学生角色：
1）查看旧书回收信息：学生可查看投物规则，投递点，公益捐赠，志愿组织信息。
2）查看订单信息：学生可查看所有订单，预约中订单，进行中订单，已完成订单信息，以及订单具体信息：订单编号，回收人，联系方式，联系地址，回收重量，回收日期，状态。
志愿者角色：
1）	查看和修改订单状态信息：志愿者登录系统后可查看和修改订单信息。
学生角色和志愿者角色：
2）	联系客服：咨询在线客服。
3）	信息反馈：填写意见反馈，提交给客服。
4）	登录：获取用户头像及昵称
后台管理人员角色：
管理员可以管理学生、管理员账号信息。
## 示例
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/c47164eb-5d7f-41ea-a203-66f54c2d4329)
### 首页页面
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/d2ead0c7-fa3d-4ed7-8af4-4298acd3273e)
### 投物规则页面
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/3fe2c5b7-0d5c-408d-9679-5d8ed81e1bb0)

### 预约页面
点击首页“点击参与旧书回收”按钮，跳转至预约详情页面，如图8所示.学生填写回收旧书及个人的基本信息，包括姓名，手机号码，回收地址，回收日期，回收时间段，旧书数量。用户需要填写全部信息，否则会提示要求填写所有信息, 如图9所示,填写完成后点击“点击预约回收”按钮，即成功提交预约订单
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/2f7da859-9429-4fa8-a3c8-76ed90d694c3)
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/f2a3778e-7f9b-4cf2-bc58-b8dce7817ffc)
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/2b6479bf-fdcb-4cad-940f-a20ee85f2de9)

### 订单页面
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/e2ba0358-4a4a-4fbe-a59b-0d210e2ab603)

### 我的页面
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/16394768-264d-4066-8ebf-f6d5f7459f2f)
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/ad9f65b1-9c1e-47ff-8982-1daee5ec866b)

### 志愿者管理员登录页面
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/5ad2f6b2-5f73-4f22-b4b3-864faef0ffe2)
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/dfbcd30e-8203-4c15-988e-44e483310f53)
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/1e242b91-1265-469e-8b66-c379536b5609)

### 意见反馈页面
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/59b63ff6-7da6-41bc-a9af-27240918ab99)

### 联系客服页面
![image](https://github.com/IVYEVOL/Books-Recycling-wechat-applet-/assets/52659747/0db8514a-e8ef-40c2-8267-46b28f4bb5d0)




