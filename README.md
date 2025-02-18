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

```
/Kicad_Library/
  ├── Symbols/                      # 电子元件符号库
  │     ├── EXT_Passive.kicad_sym        # 被动元件：电阻、电容、电感、二极管等
  │     ├── EXT_ICs.kicad_sym            # IC类：MCU、逻辑IC、运放、存储器、电源管理等
  │     ├── EXT_Connectors.kicad_sym     # 连接器、开关、继电器、按钮
  │     ├── EXT_Modules.kicad_sym        # 模块：屏幕、无线、传感器、继电器等
  │     ├── EXT_Other.kicad_sym          # 其他元件：晶振、LED、保险丝、散热器等
  │
  ├── Footprints/                   # 封装库
  │     ├── EXT_Passive_THT.pretty        # 插件式被动元件
  │     ├── EXT_Passive_SMD.pretty        # 贴片式被动元件
  │     ├── EXT_IC_THT.pretty             # 插件式IC
  │     ├── EXT_IC_SMD.pretty             # 贴片式IC（QFP/QFN/SOIC等）
  │     ├── EXT_Connectors_THT.pretty     # 插件式连接器（PinHeader、RJ45、USB等）
  │     ├── EXT_Connectors_SMD.pretty     # 贴片式连接器
  │     ├── EXT_Modules.pretty            # 模块封装（屏幕、无线模块、传感器）
  │     ├── EXT_Other.pretty              # 其他封装，如晶振、散热片、继电器等
  │
  ├── 3DModels/                     # 3D模型库
  │     ├── EXT_Passive_THT.3dshapes      # 插件式被动元件3D模型
  │     ├── EXT_Passive_SMD.3dshapes      # 贴片式被动元件3D模型
  │     ├── EXT_IC_THT.3dshapes           # 插件式IC 3D模型
  │     ├── EXT_IC_SMD.3dshapes           # 贴片式IC 3D模型（QFP/QFN/SOIC等）
  │     ├── EXT_Connectors_THT.3dshapes   # 插件式连接器3D模型（PinHeader、RJ45、USB等）
  │     ├── EXT_Connectors_SMD.3dshapes   # 贴片式连接器3D模型
  │     ├── EXT_Modules.3dshapes          # 模块3D模型（屏幕、无线模块、传感器等）
  │     ├── EXT_Other.3dshapes            # 其他3D模型（晶振、散热片、继电器等）
```



参考： [嘉立创EDA封装库命名参考规范.pdf](./Docs/嘉立创EDA封装库命名参考规范.pdf) 









## 参考:

1. https://github.com/zhbi98/kicad-libs
