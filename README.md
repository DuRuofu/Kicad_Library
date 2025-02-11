# 个人自用kicad库

目录结构：

```
Kicad_Library/
│── Symbols/                 # 符号库
│── Footprints/              # 封装库
│── 3DModels/                # 3D 模型
│── Templates/               # 项目模板
│── Docs/                    # 其他文档
│── README.md                # 说明文档
```

库文件命名检索：

| **类别**                     | **符号库 (.kicad_sym)**            | **封装库 (.pretty)**             | **3D 模型 (.step)**                |
| ---------------------------- | ---------------------------------- | -------------------------------- | ---------------------------------- |
| **电阻 (Resistor)**          | `EXT_Resistor.kicad_sym`           | `EXT_Resistor_THT.pretty`        | `EXT_Resistor_THT.3dshapes`        |
|                              |                                    | `EXT_Resistor_SMD.pretty`        | `EXT_Resistor_SMD.3dshapes`        |
| **电容 (Capacitor)**         | `EXT_Capacitor.kicad_sym`          | `EXT_Capacitor_THT.pretty`       | `EXT_Capacitor_THT.3dshapes`       |
|                              |                                    | `EXT_Capacitor_SMD.pretty`       | `EXT_Capacitor_SMD.3dshapes`       |
| **电感 (Inductor)**          | `EXT_Inductor.kicad_sym`           | `EXT_Inductor_THT.pretty`        | `EXT_Inductor_THT.3dshapes`        |
|                              |                                    | `EXT_Inductor_SMD.pretty`        | `EXT_Inductor_SMD.3dshapes`        |
| **二极管 (Diode)**           | `EXT_Diode.kicad_sym`              | `EXT_Diode_THT.pretty`           | `EXT_Diode_THT.3dshapes`           |
|                              |                                    | `EXT_Diode_SMD.pretty`           | `EXT_Diode_SMD.3dshapes`           |
| **晶体管 (Transistor)**      | `EXT_Transistor.kicad_sym`         | `EXT_Transistor_THT.pretty`      | `EXT_Transistor_THT.3dshapes`      |
|                              |                                    | `EXT_Transistor_SMD.pretty`      | `EXT_Transistor_SMD.3dshapes`      |
| **数字逻辑 IC**              | `EXT_IC_Digital.kicad_sym`         | `EXT_IC_TSSOP.pretty`            | `EXT_IC_TSSOP.3dshapes`            |
| **微控制器 (MCU)**           | `EXT_IC_MCU.kicad_sym`             | `EXT_IC_QFP.pretty`              | `EXT_IC_QFP.3dshapes`              |
|                              |                                    | `EXT_IC_QFN.pretty`              | `EXT_IC_QFN.3dshapes`              |
| **存储器 (Memory)**          | `EXT_IC_Memory.kicad_sym`          | `EXT_IC_TSOP.pretty`             | `EXT_IC_TSOP.3dshapes`             |
| **运算放大器 (Op-Amp)**      | `EXT_IC_Amplifier.kicad_sym`       | `EXT_IC_SOIC.pretty`             | `EXT_IC_SOIC.3dshapes`             |
|                              |                                    | `EXT_IC_MSOP.pretty`             | `EXT_IC_MSOP.3dshapes`             |
| **电源管理 IC**              | `EXT_IC_Power.kicad_sym`           | `EXT_IC_DFN.pretty`              | `EXT_IC_DFN.3dshapes`              |
| **通信 IC**                  | `EXT_IC_Communication.kicad_sym`   | `EXT_IC_LGA.pretty`              | `EXT_IC_LGA.3dshapes`              |
| **传感器接口 IC**            | `EXT_IC_SensorInterface.kicad_sym` | `EXT_IC_QFN.pretty`              | `EXT_IC_QFN.3dshapes`              |
| **模拟开关 (Analog Switch)** | `EXT_IC_AnalogSwitch.kicad_sym`    | `EXT_IC_TSSOP.pretty`            | `EXT_IC_TSSOP.3dshapes`            |
| **时钟 IC**                  | `EXT_IC_Clock.kicad_sym`           | `EXT_IC_MSOP.pretty`             | `EXT_IC_MSOP.3dshapes`             |
| **驱动器 IC**                | `EXT_IC_Driver.kicad_sym`          | `EXT_IC_TSSOP.pretty`            | `EXT_IC_TSSOP.3dshapes`            |
| **开关 (Switch)**            | `EXT_Switch.kicad_sym`             | `EXT_Switch_THT.pretty`          | `EXT_Switch_THT.3dshapes`          |
|                              |                                    | `EXT_Switch_SMD.pretty`          | `EXT_Switch_SMD.3dshapes`          |
| **按钮 (Button)**            | `EXT_Button.kicad_sym`             | `EXT_Button_THT.pretty`          | `EXT_Button_THT.3dshapes`          |
|                              |                                    | `EXT_Button_SMD.pretty`          | `EXT_Button_SMD.3dshapes`          |
| **连接器 (Connector)**       | `EXT_Connector.kicad_sym`          | `EXT_Connector_PinHeader.pretty` | `EXT_Connector_PinHeader.3dshapes` |
|                              |                                    | `EXT_Connector_USB.pretty`       | `EXT_Connector_USB.3dshapes`       |
|                              |                                    | `EXT_Connector_RJ45.pretty`      | `EXT_Connector_RJ45.3dshapes`      |
|                              |                                    | `EXT_Connector_HDMI.pretty`      | `EXT_Connector_HDMI.3dshapes`      |
| **传感器 (Sensor)**          | `EXT_Sensor.kicad_sym`             | `EXT_Sensor_THT.pretty`          | `EXT_Sensor_THT.3dshapes`          |
|                              |                                    | `EXT_Sensor_SMD.pretty`          | `EXT_Sensor_SMD.3dshapes`          |
| **电源 (Power)**             | `EXT_Power.kicad_sym`              | `EXT_Power_Module.pretty`        | `EXT_Power_Module.3dshapes`        |
|                              |                                    | `EXT_Power_Converter.pretty`     | `EXT_Power_Converter.3dshapes`     |
| **继电器 (Relay)**           | `EXT_Relay.kicad_sym`              | `EXT_Relay_THT.pretty`           | `EXT_Relay_THT.3dshapes`           |
|                              |                                    | `EXT_Relay_SMD.pretty`           | `EXT_Relay_SMD.3dshapes`           |
| **晶振 (Crystal)**           | `EXT_Crystal.kicad_sym`            | `EXT_Crystal_THT.pretty`         | `EXT_Crystal_THT.3dshapes`         |
|                              |                                    | `EXT_Crystal_SMD.pretty`         | `EXT_Crystal_SMD.3dshapes`         |
| **LED**                      | `EXT_LED.kicad_sym`                | `EXT_LED_THT.pretty`             | `EXT_LED_THT.3dshapes`             |
|                              |                                    | `EXT_LED_SMD.pretty`             | `EXT_LED_SMD.3dshapes`             |
| **散热器 (Heatsink)**        | `EXT_Heatsink.kicad_sym`           | `EXT_Heatsink.pretty`            | `EXT_Heatsink.3dshapes`            |
| **保险丝 (Fuse)**            | `EXT_Fuse.kicad_sym`               | `EXT_Fuse_THT.pretty`            | `EXT_Fuse_THT.3dshapes`            |
|                              |                                    | `EXT_Fuse_SMD.pretty`            | `EXT_Fuse_SMD.3dshapes`            |
| **变压器 (Transformer)**     | `EXT_Transformer.kicad_sym`        | `EXT_Transformer_THT.pretty`     | `EXT_Transformer_THT.3dshapes`     |
|                              |                                    | `EXT_Transformer_SMD.pretty`     | `EXT_Transformer_SMD.3dshapes`     |





参考： [嘉立创EDA封装库命名参考规范.pdf](./Docs/嘉立创EDA封装库命名参考规范.pdf) 









## 参考:

1. https://github.com/zhbi98/kicad-libs
