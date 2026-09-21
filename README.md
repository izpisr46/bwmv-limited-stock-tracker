# 搬瓦工限量版库存：限量套餐什么时候补货，怎么第一时间蹲到现货（附全套餐最新价格表）

搜“搬瓦工限量版库存”的人，基本是被同一件事卡住的：看中某个限量版套餐，点进去发现 "out of stock"，然后不知道该等、该抢，还是干脆换个套餐。这篇文章把三件事说清楚：截至目前的限量版在售状态、限量版为什么老缺货、以及怎么在补货的第一时间下单。文末附上搬瓦工目前官网在售的全套餐价格表，等不及限量版的可以直接看替代方案。

## 先说结论：限量版现在的库存状态

搬瓦工的套餐分两大类：常规套餐（长期在售，随时能买）和限量版套餐（限量发售、售完即止、补货不定期）。两类的价格差距很大，同样的 CN2 GIA 线路，限量版能做到常规套餐三四折的价格，这就是限量版抢手的原因。

按第三方库存监控站点的实时数据，目前各限量版套餐的状态是这样的：

| 限量版套餐 | 配置 | 历史售价 | 当前状态 |
| --- | --- | --- | --- |
| PowerBox 限量版 | 1核 / 1536MB / 30GB / 1500GB / 2.5Gbps | $45.00/年 | 下架 |
| SakuraBox 限量版 | 1核 / 1024MB / 30GB / 500GB / 1Gbps | $79.00/年 | 下架 |
| BiggerBox Pro 限量版 | 1核 / 1024MB / 20GB / 1000GB / 2.5Gbps | $39.00/年 | 下架 |
| MegaBox Pro 限量版 | 2核 / 2048MB / 40GB / 2000GB / 2.5Gbps | $49.00/年 | 下架 |

THE PLAN、THE CHICKEN、MINICHICKEN 这几个知名限量版目前也不在可购买列表里。也就是说，**截至本文写作时，限量版全线缺货，常规套餐全部有货**。

这个状态随时会变。限量版的补货从来不会提前预告，上次 THE PLAN 回归时，官方只是在页面挂出套餐，然后卖完就把页面撤下。所以要抢，靠的是监控和信息源，不是手速 alone。

## 限量版为什么总是缺货

原因官方没有正式解释过，但从售卖模式能看出来：限量版本质是用较低的 CPU 占用来换低价格。搬瓦工在服务条款里明确写了各套餐的平均 CPU 限制——传统限量版套餐是单核的 30%，THE PLAN 是 45%，而常规 KVM 套餐能达到 50% 到 75%。

换句话说，一个节点上能塞多少台限量版 VPS，取决于这台机器的计算资源。低价限量版把成本压得很狠，利润薄，官方的策略就是小批量放货、卖完即止，宁可让用户排队等，也不放量发。

补货时间也没有规律可循。翻一下近几年的补货记录：DC9 CN2 GIA $39.99 方案补过多次货，CN2 GIA-E 40G 限量版曾在降价 10 美元后以 $89.90/年的价格回归，THE PLAN 在 2023 年初首发、之后又在 2024 年原价回归过一次（季付 $29、年付 $99，配置 2核/2GB/40GB，可选机房一度增加到 18 个）。这些补货分散在不同的月份，没有固定周期。

## 怎么第一时间知道补货

想抢限量版，先把自己接到信息源上。目前可用的渠道有这几类：

1. **库存监控网站**。第三方维护的监控页会实时抓取官方数据，比如按套餐列出“有货 / 缺货”状态的监控站，几分钟刷新一次。发现目标套餐变绿，直接点过去下单。
2. **官方 Telegram 频道和 QQ 补货群**。搬瓦工有官方的新闻频道，中文社区也有专门的补货通知群，平时禁言，只在补货时发消息，不会被聊天刷屏干扰。
3. **邮件订阅**。部分监控站提供邮件提醒，适合不方便挂 TG 的场景，但邮件延迟通常比即时消息大，适合做兜底。

三个渠道里，监控网站加 TG 频道的组合最实用。补货高峰期（比如双十一、黑五前后）限量版放货概率明显更高，这两个节点前几天可以把监控盯紧一点。

## 补货出现后，怎么把套餐抢到手

限量版补货的存活时间经常以分钟计，热门款（THE PLAN、香港系列限量版）可能十几分钟就没了。下单流程本身不长，但有几个地方值得提前准备：

1. **提前注册并登录账号**。新账号注册要过邮箱验证，这一步如果留在补货时做，基本等于放弃。
2. **提前决定购买周期并试走一遍结算**。限量版通常只开季付和年付，年付单价更低。结算页就几步：选周期、填优惠码、选支付宝或付款方式、确认。可以在常规套餐的购物车里把整个流程走一遍，熟悉每个按钮的位置。
3. **优惠码提前查好**。搬瓦工的优惠码是循环折扣码，常年有效的力度在 6% 上下，旧码失效后会有新码接替。目前中文资讯站挂出的循环码是 **BWHCGLUKKB**，结账时填进优惠码输入框试一下即可，生效会在订单金额里直接体现。历史上还出现过 NODESEEK2026 这类短期大力度码，但那批码上线两天就失效了，等抢购时再临时找码不现实，提前把循环码存好就行。
4. **付款方式留好余额**。支付宝扫码付款没问题，但如果卡在支付环节，热门套餐不会等你想清楚。

另外一个容易踩的坑：限量版套餐对机房有限制。早年 DC9 的 $39.99 限量版就不能选 DC6 CN2 GIA-E 机房和香港机房，下单前看清楚可选机房列表，别抢到了发现不是自己要的线路。

## 等不到限量版，常规套餐怎么选

限量版缺货不是世界末日。常规 CN2 GIA-E 系列长期有货，线路质量和限量版同级别（洛杉矶 DC6 CN2 GIA-E、DC9 CN2 GIA 都可选），差的主要是价格和 CPU 限制。如果预算在每年一百美元上下，**CN2 GIA-E 1GB 套餐（2核 / 1GB / 20GB SSD / 1TB 月流量 / 2.5Gbps，季付 $49.99，年付 $169.99）是目前最接近限量版体验的在售方案**。

下面是目前官网在售的全套餐价格表，数据与官方页面和库存监控站交叉核对过，价格均为美元。

**KVM 常规系列（多机房可选）**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| KVM 1GB | 2核 | 1GB | 20GB | 1TB | 1Gbps | $49.99/年 | [ 查看 KVM 1GB](https://bandwagonhost.com/aff.php?aff=79616&pid=44) |
| KVM 2GB | 3核 | 2GB | 40GB | 2TB | 1Gbps | $52.99/半年，$99.99/年 | [ 查看 KVM 2GB](https://bandwagonhost.com/aff.php?aff=79616&pid=45) |
| KVM 4GB | 4核 | 4GB | 80GB | 3TB | 1Gbps | $19.99/月，$199.99/年 | [ 查看 KVM 4GB](https://bandwagonhost.com/aff.php?aff=79616&pid=46) |
| KVM 8GB | 5核 | 8GB | 160GB | 4TB | 1Gbps | $39.99/月，$399.99/年 | [ 查看 KVM 8GB](https://bandwagonhost.com/aff.php?aff=79616&pid=47) |
| KVM 16GB | 6核 | 16GB | 320GB | 5TB | 1Gbps | $79.99/月，$799.99/年 | [ 查看 KVM 16GB](https://bandwagonhost.com/aff.php?aff=79616&pid=48) |
| KVM 24GB | 7核 | 24GB | 480GB | 6TB | 1Gbps | $119.99/月，$1199.99/年 | [ 查看 KVM 24GB](https://bandwagonhost.com/aff.php?aff=79616&pid=49) |

**CN2 GIA-E 电商系列（建站推荐，含 DC6 / DC9 等机房）**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CN2 GIA-E 1GB | 2核 | 1GB | 20GB | 1TB | 2.5Gbps | $49.99/季，$169.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=87) |
| CN2 GIA-E 2GB | 3核 | 2GB | 40GB | 2TB | 2.5Gbps | $89.99/季，$299.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=88) |
| CN2 GIA-E 4GB | 4核 | 4GB | 80GB | 3TB | 2.5Gbps | $56.99/月，$549.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=89) |
| CN2 GIA-E 8GB | 6核 | 8GB | 160GB | 5TB | 5Gbps | $86.99/月，$879.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=90) |
| CN2 GIA-E 16GB | 8核 | 16GB | 320GB | 8TB | 5Gbps | $159.99/月，$1599.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=91) |
| CN2 GIA-E 32GB | 10核 | 32GB | 640GB | 10TB | 10Gbps | $289.99/月，$2759.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=92) |
| CN2 GIA-E 64GB | 12核 | 64GB | 1280GB | 12TB | 10Gbps | $549.99/月，$5499.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=93) |
| CN2 GIA-E 64GB（高CPU） | 24核 | 64GB | 1280GB | 12TB | 10Gbps | $7599.00/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=148) |
| CN2 GIA-E 64GB（大流量） | 12核 | 64GB | 1280GB | 15TB | 10Gbps | $679.00/月，$6790.00/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=160) |
| CN2 GIA-E 64GB（大流量） | 12核 | 64GB | 1280GB | 20TB | 10Gbps | $899.00/月，$8999.00/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=161) |

**电商 SLA 系列（99.99% SLA 保证）**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SLA 1GB | 2核 | 1GB ECC | 20GB | 1TB | 2.5Gbps | $65.89/季，$239.99/年 | [ 查看 SLA 1GB](https://bandwagonhost.com/aff.php?aff=79616&pid=164) |
| SLA 2GB | 3核 | 2GB ECC | 40GB | 2TB | 2.5Gbps | $116.99/季，$399.99/年 | [ 查看 SLA 2GB](https://bandwagonhost.com/aff.php?aff=79616&pid=165) |
| SLA 4GB | 4核 | 4GB ECC | 80GB | 3TB | 2.5Gbps | $69.99/月，$699.99/年 | [ 查看 SLA 4GB](https://bandwagonhost.com/aff.php?aff=79616&pid=166) |
| SLA 8GB | 6核 | 8GB ECC | 160GB | 5TB | 5Gbps | $109.99/月，$1099.99/年 | [ 查看 SLA 8GB](https://bandwagonhost.com/aff.php?aff=79616&pid=167) |
| SLA 16GB | 8核 | 16GB ECC | 320GB | 8TB | 5Gbps | $199.99/月，$1999.99/年 | [ 查看 SLA 16GB](https://bandwagonhost.com/aff.php?aff=79616&pid=168) |
| SLA 32GB | 10核 | 32GB ECC | 640GB | 10TB | 10Gbps | $369.99/月，$3699.99/年 | [ 查看 SLA 32GB](https://bandwagonhost.com/aff.php?aff=79616&pid=169) |
| SLA 64GB | 12核 | 64GB ECC | 1280GB | 12TB | 10Gbps | $699.99/月，$6999.99/年 | [ 查看 SLA 64GB](https://bandwagonhost.com/aff.php?aff=79616&pid=170) |
| SLA 64GB（大流量） | 12核 | 64GB ECC | 1280GB | 15TB | 10Gbps | $879.99/月，$8799.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=171) |
| SLA 64GB（大流量） | 12核 | 64GB ECC | 1280GB | 20TB | 10Gbps | $1159.99/月，$11598.99/年 | [ 查看库存与价格](https://bandwagonhost.com/aff.php?aff=79616&pid=172) |

**香港 CN2 GIA 系列（高端低延迟）**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 香港 2GB | 2核 | 2GB | 40GB | 500GB | 1Gbps | $89.99/月，$899.99/年 | [ 查看香港套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=95) |
| 香港 4GB | 4核 | 4GB | 80GB | 1TB | 1Gbps | $155.99/月，$1559.99/年 | [ 查看香港套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=96) |
| 香港 8GB | 6核 | 8GB | 160GB | 2TB | 1Gbps | $299.99/月，$2999.99/年 | [ 查看香港套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=97) |
| 香港 16GB | 8核 | 16GB | 320GB | 4TB | 1Gbps | $589.99/月，$5899.99/年 | [ 查看香港套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=98) |
| 香港 32GB | 10核 | 32GB | 640GB | 6TB | 1Gbps | $989.99/月，$9989.99/年 | [ 查看香港套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=122) |
| 香港 64GB | 12核 | 64GB | 1280GB | 8TB | 1Gbps | $1889.99/月，$18989.99/年 | [ 查看香港套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=124) |

**日本 CN2 GIA 系列（东京线路）**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 东京 2GB | 2核 | 2GB | 40GB | 500GB | 1.2Gbps | $89.99/月，$899.99/年 | [ 查看东京套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=108) |
| 东京 4GB | 4核 | 4GB | 80GB | 1TB | 1.2Gbps | $155.99/月，$1559.99/年 | [ 查看东京套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=109) |
| 东京 8GB | 6核 | 8GB | 160GB | 2TB | 1.2Gbps | $299.99/月，$2999.99/年 | [ 查看东京套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=110) |
| 东京 16GB | 8核 | 16GB | 320GB | 4TB | 1.2Gbps | $589.99/月，$5899.99/年 | [ 查看东京套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=111) |
| 东京 32GB | 10核 | 32GB | 640GB | 6TB | 1.2Gbps | $989.99/月，$9989.99/年 | [ 查看东京套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=123) |
| 东京 64GB | 12核 | 64GB | 1280GB | 8TB | 1.2Gbps | $1889.99/月，$18989.99/年 | [ 查看东京套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=125) |

**日本大阪 CN2 GIA 系列**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 大阪 2GB | 2核 | 2GB | 40GB | 500GB | 1.5Gbps | $49.99/月，$499.99/年 | [ 查看大阪套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=134) |
| 大阪 4GB | 4核 | 4GB | 80GB | 1TB | 1.5Gbps | $86.99/月，$869.99/年 | [ 查看大阪套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=135) |
| 大阪 8GB | 6核 | 8GB | 160GB | 2TB | 1.5Gbps | $165.99/月，$1665.99/年 | [ 查看大阪套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=136) |
| 大阪 16GB | 8核 | 16GB | 320GB | 4TB | 1.5Gbps | $329.99/月，$3199.00/年 | [ 查看大阪套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=137) |
| 大阪 32GB | 10核 | 32GB | 640GB | 6TB | 1.5Gbps | $549.99/月，$5549.99/年 | [ 查看大阪套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=138) |
| 大阪 64GB | 12核 | 64GB | 1280GB | 8TB | 1.5Gbps | $1059.99/月，$10559.99/年 | [ 查看大阪套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=139) |

**迪拜 ECOMMERCE 系列**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 迪拜 1GB | 2核 | 1GB | 20GB | 500GB | 1Gbps | $19.99/月，$169.99/年 | [ 查看迪拜套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=114) |
| 迪拜 2GB | 3核 | 2GB | 40GB | 1TB | 1Gbps | $32.99/月，$299.99/年 | [ 查看迪拜套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=115) |
| 迪拜 4GB | 4核 | 4GB | 80GB | 2TB | 1Gbps | $56.99/月，$549.99/年 | [ 查看迪拜套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=116) |
| 迪拜 8GB | 6核 | 8GB | 160GB | 3TB | 1Gbps | $86.99/月，$879.99/年 | [ 查看迪拜套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=117) |
| 迪拜 16GB | 8核 | 16GB | 320GB | 4TB | 1Gbps | $159.99/月，$1599.99/年 | [ 查看迪拜套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=118) |
| 迪拜 32GB | 10核 | 32GB | 640GB | 5TB | 1Gbps | $289.99/月，$2759.99/年 | [ 查看迪拜套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=119) |
| 迪拜 64GB | 12核 | 64GB | 1280GB | 6TB | 1Gbps | $549.99/月，$5399.99/年 | [ 查看迪拜套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=120) |

如果只看性价比，值得单独说的有两个：**迪拜 1GB（$169.99/年）在同系列里最便宜，月付只要 $19.99**，适合想低门槛上车 CN2 GIA-E 级别线路的用户；**CN2 GIA-E 1GB 是建站取向的经典款**，2.5Gbps 带宽加 1TB 月流量，年付 $169.99，比同配置香港、东京方案便宜一大截。想直接对比所有在售套餐的当前库存，可以点这里：[👉 查看搬瓦工全套餐最新库存与价格](https://bit.ly/BandwagonHost)。

## 买限量版之前，这几件事先确认

**CPU 限制。**限量版的平均 CPU 占用限制是实打实写进服务条款的：传统限量版 30% 单核，THE PLAN 45% 单核。峰值可以跑满标称核数，但长期平均超过限制可能被暂停。跑静态站、代理、轻量服务没问题，跑持续高负载的任务要掂量一下。

**退款政策。**搬瓦工官方提供 30 天退款保证，条件是符合服务条款（通常要求是新订单、在 30 天内申请）。这意味着如果抢到的限量版实测线路不理想，还有一个相对低风险的退出通道。具体条款以官方退款页面为准。

**流量和带宽是硬指标。**限量版套餐的流量一般比同价位常规套餐少（比如 The Chicken 类套餐月流量只有 300GB 的档位），买之前对一下自己的月用量，超流量后的处理方式并不愉快。

**库存状态变化很快。**本文的库存状态基于写作时的监控数据，读到这里时可能已经变了。最终以监控站和官方页面的实时状态为准，这也是为什么前面建议把信息源接好——限量版抢购这件事，信息差就是全部。
