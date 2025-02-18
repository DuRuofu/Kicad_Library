# 个人自用kicad库

## 目录结构

```
Kicad_Library/
│── Symbols/                 # 符号库
│── Footprints/              # 封装库
│── 3DModels/                # 3D 模型
│── Templates/               # 项目模板
│── Docs/                    # 其他文档
│── README.md                # 说明文档
```

## 库文件命名检索

```
/Kicad_Library/
  ├── Symbols/                      # 电子元件符号库
  │     ├── EXT_Passive.kicad_sym        # 被动元件：电阻、电容、电感、二极管等
  │     ├── EXT_ICs.kicad_sym            # IC类：MCU、逻辑IC、运放、存储器、电源管理等
  │     ├── EXT_IC_Power.kicad_sym       # IC类：电源
  │     ├── EXT_IC_Other.kicad_sym       # 其他
  │     ├── EXT_Connectors.kicad_sym     # 连接器
  │     ├── EXT_Switch.kicad_sym         # 开关、继电器、按钮
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
  │     ├── EXT_Switch_THT.pretty         # 插件式开关、继电器、按钮
  │     ├── EXT_Switch_SMD.pretty         # 贴片式开关、继电器、按钮
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
  │     ├── EXT_Switch_THT.3dshapes       # 插件式开关、继电器、按钮3D模型
  │     ├── EXT_Switch_SMD.3dshapes       # 贴片式开关、继电器、按钮3D模型
  │     ├── EXT_Modules.3dshapes          # 模块3D模型（屏幕、无线模块、传感器等）
  │     ├── EXT_Other.3dshapes            # 其他3D模型（晶振、散热片、继电器等）
```

## 使用方法

1. 克隆本仓库到本地, 或者下载zip文件解压到本地(放到一个固定的目录下，如`~/Documents/Kicad_Library`)
2. 在设置中添加环境变量`EXT_Kicad_Library`, 值为本地库的路径，如`~/Documents/Kicad_Library`
3. 在KiCad的设置中添加库文件路径.

## 参考

1. <https://github.com/zhbi98/kicad-libs>
