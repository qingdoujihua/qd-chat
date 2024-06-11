# 青豆chat(qd-chat)
这是一个由青豆计划和华中师范大学心理学院共同参与研究的心理学问答AI大模型



<p align="center">
    <a href="support os"><img src="https://img.shields.io/badge/os-linux%2C%20win%2C%20mac-pink.svg"></a>
    <a href=""><img src="https://img.shields.io/badge/python-3.8+-aff.svg"></a>
    <a href="https://github.com/scutcyr/SoulChat/graphs/contributors"><img src="https://img.shields.io/github/contributors/scutcyr/SoulChat?color=9ea"></a>
    <a href="https://github.com/scutcyr/SoulChat/commits"><img src="https://img.shields.io/github/commit-activity/m/scutcyr/SoulChat?color=3af"></a>
</p>

青豆计划与华中师范大学心理学院开源了中文领域心理健康大模型底座qd-chat，是具有十万规模心理咨询领域中文长文本指令与多轮共情对话数据联合指令微调的[心理健康大模型青豆chat（qd-chat）](https://github.com/qingdoujihua/qd-ai.git)   

我们期望，qd-chat可以帮助学术界加速大模型在心理咨询领域的研究与应用。


## 最近更新
-   2023.12.09：qd-chat对外发布并使用！



## 简介
  

## 使用方法
* 克隆本项目
```bash
cd ~
git clone https://github.com/qingdoujihua/qd-chat.git
```


* 启动服务   

本项目提供了[qd_app.py](./qd_app.py)作为qd-chat模型的使用示例，通过以下命令即可开启服务，然后，通过https://<your_ip>:9026访问。
```bash
python startup.py -a
```

## 示例
* 样例1：情绪管理

<p align="center">
    <img src="./img/emo.png" width=600px/>
</p>




## 声明
* 本项目使用了ChatGLM3-6B 模型的权重，需要遵循其[MODEL_LICENSE](https://github.com/THUDM/ChatGLM3/blob/main/MODEL_LICENSE)，因此在使用本项目时请遵守其开源协议规定。
* 本项目提供qd-chat模型致力于提升大模型的情感分析能力和共情应答能力，但由于现有模型的回答具有一定随机性，我们希望您在使用qd-chat模型时应知悉，其不能替代医生、心理医生等专业人士，不应过度依赖，服从模型的回答，不能长期沉迷于与qd-chat模型聊天。同时，我们不建议将qd-chat模型的回答用来完全替代心理医生的诊断和治疗，我们也无法保证模型的输出完全会符合使用者的需求，因此，在使用本模型时您需要自行承担其带来的所有风险！
* 您不得在未获取青豆计划授权的情况下使用qd-chat模型的全部或者部分代码。
* 您不得利用qd-ai模型从事违法国家法律法规、危害社会公共利益、侵犯他人人身权益的行为。

## 致谢
本项目由[青豆计划](https://qing-dou.com)[华中师范大学心理学院]([https://www2.scut.edu.cn/ft/main.htm](https://psych.ccnu.edu.cn/)) 共同参与发起，得到了华中师范大学心理学院田媛教授及其团队的支撑，在此特别鸣谢！


* 公众号
  [青豆计划]([https://mp.weixin.qq.com/s/gemlKfLg8c-AtjiV7uTUTQ](https://mp.weixin.qq.com/mp/homepage?__biz=MzkyODU3MDQ3Ng==&hid=1&sn=54fdb6d8e8e69846bd49b09e7beff741&scene=18#wechat_redirect))




