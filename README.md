# Comfyui-Server-API
Comfyui's web server。can be used as a backend for servers, supporting any workflow, multi GPU scheduling, automatic load balancing, and database management

base: Java+SpringBoot+Mysql

系统功能
1. 根据 comfyui GPU 地址及权重参数自动任务负载均衡
2. 可随时增加或减少 GPU 数量
3. comfyui 根据任务自动队列任务请求
4. 代码根据 requestid 自动追踪批量任务
5. 使用 rabbitMQ 处理消息队列
6. 任务失败自动重发机制
7. 使用 mysql 存储数据库
8. 使用OSS 存储图片
9. 使用配方表管理多业务多工作流参数状态
10. 使用主题排序表管理多业务分类
11. 自带用户鉴权模式，可通过拦截器开关
12. 支持拓展配方表加入更多参数控制逻辑


system function
1. Automatic task load balancing based on Comfyui GPU address and weight parameters
2. The number of GPUs can be increased or decreased at any time
3. Comfyui automatically queues task requests based on tasks
4. The code automatically tracks batch tasks based on the requestid
5. Use RabbitMQ to process message queues
6. Automatic resend mechanism for failed tasks
7. Use MySQL to store the database
8. Use Alibaba Cloud OSS to store images
9. Use a recipe table to manage the status of multiple business and workflow parameters
10. Use a topic sorting table to manage multiple business categories
11. Comes with user authentication mode, which can be activated through an interceptor switch
12. Support expanding the formula table to include more parameter control logic

API
1. Topic Sorting API
2. Formula Table API
3. Workflow/Template/Function Query API
4. comfyui task API
5. Task Query API


case
![fc34240d1b7bfc848358af2fb73879e](https://github.com/user-attachments/assets/80a2d600-4889-4fc5-b01e-6272ee5dfd84)
![4f6413b42f45faf89ab90f4fc9238b9](https://github.com/user-attachments/assets/90f06015-6267-42ed-87da-07d53101ad38)
![ca96b8455f90a3d4d45f39604a96f60](https://github.com/user-attachments/assets/df8f9112-ca30-4bef-996a-2b05a9e27264)
![107f3e62c1eadfbf8ab10e611d24b92](https://github.com/user-attachments/assets/6b4f9ceb-740a-4663-bc88-30e4c1606c7d)


get me
vx: beyond091710
![ea963bc67a919899e467f2ba1d4e734](https://github.com/user-attachments/assets/fac7f239-a75d-4816-97d7-52d1eea95f24)





