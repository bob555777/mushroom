🍄 智能多培养室蘑菇种植系统 (Smart Multi-Chamber Mushroom Cultivation System)
✨ 项目简介
本项目是一套基于 ESP32 的智能多培养室蘑菇种植与环境控制系统。它集成了高精度环境传感器、AI 视觉识别技术和灵活的智能控制策略，旨在为用户提供一个精准、高效且自动化的蘑菇生长环境管理解决方案。从温度、湿度、CO₂的精准控制到蘑菇生长阶段的智能识别，全面提升种植的成功率和便利性。

🚀 核心功能特性
🎯 多培养室监控 (Multi-Chamber Monitoring)
三培养室独立监控： 可同时监控和管理三个独立的蘑菇培养室环境。

高精度传感器集成：

温湿度 & CO₂： 每个培养室均配备 SCD30 传感器，提供高精度的温湿度及 CO₂ 数据。

土壤湿度监测： 培养室 1 额外配备土壤湿度传感器，满足特定蘑菇品种的需求。

🌡️ 智能环境控制 (Intelligent Environmental Control)
实现对关键环境参数的精细化、自动化调控。

双通风新风系统： 根据湿度阈值自动控制双通风风扇，集成活性炭和 PM2.5 过滤，确保空气质量。

智能制冷系统： 当温度超过自定义阈值时自动启动制冷。

自动照明控制： 精确实现 12 小时光照 / 12 小时黑暗的周期循环。

雾化加湿系统： 自动调节以维持最佳的湿度环境。

自定义策略系统： 用户可一键设置环境阈值和设备执行策略，实现灵活的自动化管理。

🤖 AI 视觉识别 (AI Vision Recognition)
通过无线摄像头模块实现蘑菇生长状态的实时智能分析。

ESP-NOW 无线通信： 与 ESP32-CAM 进行高效、低功耗的数据交换。

蘑菇生长阶段识别： 自动识别关键阶段，如孢子萌发和结实诱导。

健康状况分析： 实时监测并评估蘑菇的生长状态和健康情况。

置信度评估： 为每次识别结果提供可靠性指标 (Confidence Score)。

⚙️ 智能策略与设备管理 (Smart Strategy & Device Management)
可配置控制策略： 支持基于温度、湿度、CO₂、时间等多种条件的触发规则。

灵活动作执行： 精确控制风扇、制冷、照明、雾化器等所有执行设备。

手动/自动模式： 支持用户手动干预，或切换至全自动策略运行。

时间保护机制：

防频繁切换保护： 设置设备最小运行/停止时间，防止继电器和设备频繁启停。

最大运行时间： 避免设备长时间连续运行导致的损耗。

💻 软件与通信特性
🌐 Web API 接口 (RESTful API)
提供强大的数据访问和远程控制能力。

数据获取： 实时传感器数据、设备状态、历史记录和趋势分析。

设备控制： 手动/自动模式切换、设备开关状态控制。

策略管理： 策略的配置、启用/禁用以及触发记录查询。

CORS 支持： 允许跨域访问，便于前端和移动应用集成。

热点自建： WiFi 断开连接时，系统自动创建热点，确保设备的本地可访问性。

📡 ESP-NOW 通信 (Low-Power Protocol)
低功耗通信： 确保与 ESP32-CAM 的高效数据同步，延长摄像头模块的待机时间。

实时数据更新： 实时传输蘑菇生长状态、健康状况和设备状态。
🛠️ 技术栈 (Tech Stack)
硬件平台: ESP32 (Main Controller), ESP32-CAM (AI Vision)

传感器: SCD30 (CO₂, Temp, Hum), 土壤湿度传感器

无线协议: ESP-NOW, WiFi

软件接口: RESTful Web API
<img width="619" height="687" alt="image" src="https://github.com/user-attachments/assets/2edb0fa3-f661-44e7-84ef-0b3069f4e21c" />
<img width="792" height="482" alt="image" src="https://github.com/user-attachments/assets/dcbed4f8-d2f9-45f2-abee-caee90a8155b" />
<img width="533" height="619" alt="image" src="https://github.com/user-attachments/assets/7e73debe-0224-4ba1-9d60-5e310a17f34f" />
<img width="782" height="461" alt="image" src="https://github.com/user-attachments/assets/5000eb1d-66df-4db2-8e9f-6a3fe00297e3" />

![a](https://github.com/user-attachments/assets/868ee2a4-4c71-4250-8542-767f4a3d4759)
![b](https://github.com/user-attachments/assets/546ee916-0401-4166-b055-f98147d6435b)

![c](https://github.com/user-attachments/assets/a14beb83-1c79-4600-bc67-d527bd2087cf)

![d](https://github.com/user-attachments/assets/f9318efa-c8d8-4728-950c-39645d6ee442)
<img width="1466" height="1107" alt="e" src="https://github.com/user-attachments/assets/6ad15762-6b9a-4e5e-acf2-2525c13a5316" />
