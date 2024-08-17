# 书生·浦语大语言模型学习：
# 第一节：

![书生·浦语大模型全链路开源开放体系](https://github.com/user-attachments/assets/d5999d3a-7dc6-4d17-8558-1a9a038b84e9)
# 第二节
创建环境：

<img width="1025" alt="de594944f766ba3dc300f091309ec17" src="https://github.com/user-attachments/assets/6edcaaa3-4e92-48c8-922c-c4231cbfed40">

本地运行：

<img width="804" alt="346446c6220d3a63874466c2e669612" src="https://github.com/user-attachments/assets/922fcace-bc5e-403a-99db-79e905512e55">

端口运行：

![73fb603577aa966a0cf70c2bc8b69121](https://github.com/user-attachments/assets/90c6a042-0c0e-4f42-b7cb-9d7f3dbce4d1)

# 第三节：

窗口运行：

![fa10807864c00a9a208870739e82b35e](https://github.com/user-attachments/assets/4e2d3872-2268-4096-8b97-4ad3c2d42258)

langgpt提示词：

## Role: 数据比较大师

### Profile
- author: LangGPT 
- version: 1.0
- language: {中文/英文}
- description: {给出浮点数，能精确到比较两个浮点数的大小}

### Skills
{给出两个浮点数，精确的比较两个数值的大小}

### Background
在浮点数的比较当中，先比较整数部分的大小，再依次从高位到低位比较每一位的大小，若同一位数字中有一个数较大，则该数较大

![12a08119adbe98b2c2fa5ac4ae71021e](https://github.com/user-attachments/assets/30891409-a19a-439c-b409-1f78a0f6426d)

# 第四节

案例实现：

![a69a4dbf568ef89ad1409d7b317c4789](https://github.com/user-attachments/assets/a9bbe5a3-90a7-4b29-8f05-e4d7eab4ebca)

无RAG，询问MindSearch：

![image](https://github.com/user-attachments/assets/50c09f00-fdac-411c-b4de-bb4ac5f8f21d)

添加MindSearch的RAG 知识库：

![image](https://github.com/user-attachments/assets/2e229504-acc3-4dfa-ac70-531a60a8791d)

回答：

![a69a4dbf568ef89ad1409d7b317c4789](https://github.com/user-attachments/assets/bc6431ff-ac68-4d1b-aaf6-8051544d924a)

# 第五节

微调训练：

![697222bf23583a219462592d820f4ebd](https://github.com/user-attachments/assets/b020fe20-dba2-472e-bc8c-ebd15bf40fa7)

模型合并后，本地运行：

![cb22099334536c5d48f12a488c52d78e](https://github.com/user-attachments/assets/ae8e9dd4-305b-451b-87fe-da3666b2c6dc)
