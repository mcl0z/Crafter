# Crafter

## 适配范围

- Windows系统
- Minecraft版本大于1.12

## 使用方法

### 安装

与其他插件安装方式相同

- 高于4.2版本安装Crafter_exr.zip

- 低于4.2版本安装Crafter.zip

---

-*【由于插件中包含C++编译程序，所以报毒是正常现象。不放心可以检查[WorldImporter](https://github.com/BaiGave/WorldImporter)中的代码，编译并替换确认安全性】*

### 导入

## 维护插件注意事项

### 设置与运行

本插件基于由[异次元学者](https://space.bilibili.com/181717176)制作的[Blender插件打包工具](https://github.com/xzhuah/BlenderAddonPackageTool)测试及打包。拉取源码后应当执行如下操作。

#### 1. 设置**main.py**中的路径为您的Blender路径

```python
# The path of the blender executable. Blender2.93 is the minimum version required
# Blender可执行文件的路径，Blender2.93是所需的最低版本
BLENDER_EXE_PATH = "C:/Program Files/Blender Foundation/Blender 4.2/blender.exe"

# Linux example Linux示例
# BLENDER_EXE_PATH = "/usr/local/blender/blender-3.6.0-linux-x64/blender"

# MacOS examplenotice "/Contents/MacOS/Blender" will be appended automatically if you didn't write it explicitly
# MacOS示例 框架会自动附加"/Contents/MacOS/Blender" 所以您不必写出
# BLENDER_EXE_PATH = "/Applications/Blender/blender-3.6.0-macOS/Blender.app"
```

#### 2. 运行**text.py**

#### 3. 修改代码并测试后提交至Crafter库

-*【有关框架的更多功能请访问[插件打包工具文档](https://github.com/xzhuah/BlenderAddonPackageTool?tab=readme-ov-file#blender-插件开发框架及打包工具)】*

## 开发组和鸣谢

### 开发组

#### 白给/BaiGave

[![白给/BaiGave](https://i0.hdslb.com/bfs/face/d7d82f14e8469c3c973cd1d7b981ed275069aa55.jpg@100w_100h_1c_1s.png)](https://space.bilibili.com/3461563635731405)

- 插件的C++部分

---

#### 被盗号的高锰酸钾/MCL0

[![被盗号的高锰酸钾/MCL0](https://i2.hdslb.com/bfs/face/4cc9254634fc212567c7e2286554bf664bfedd92.jpg@100w_100h_1c_1s.png)](https://space.bilibili.com/511403657)

- 世界维度列表读取
- 坐标选择器

---

#### 少年忠城/zhong_cheng

[![少年忠城/zhong_cheng](https://i0.hdslb.com/bfs/face/cca0a2997727b7c9625b6c84b79d75b1d20b0505.jpg@100w_100h_1c_1s.png)](https://space.bilibili.com/455309610)

- python部分的大部分程序
- 默认材质预设制作

---

### 鸣谢

#### 若有来生LS

[![若有来生LS](https://i2.hdslb.com/bfs/face/69caf616d0ec1d734456ba5c3dcfb7228df98dc3.jpg@100w_100h_1c_1s.png)](https://space.bilibili.com/328067113)

- 默认LOD1无LOD方块表整理
- 制作了很好用的材质编辑插件，正在适配本插件

---

#### 异次元学者

[![异次元学者](https://i2.hdslb.com/bfs/face/68a1603186d8655a14d7e7fc920b4c95f23929d4.jpg@100w_100h_1c_1s.png)](https://space.bilibili.com/181717176)

- 插件框架作者

---

#### 像素艺作_VoxelCraft

[![像素艺作_VoxelCraft](https://i2.hdslb.com/bfs/face/1032246c6c38fc376fc6ae29d525edb85bc7da97.jpg@100w_100h_1c_1s.png)](https://space.bilibili.com/26149666)

- 群系着色图像映射
- EEVEE着色器材质解惑
- 动态纹理按序播放思路提供
- 基于传递UV的视差的制作

---

#### -blueish-

[![-blueish-](https://i2.hdslb.com/bfs/face/e7ebd5fd6c2267d6bab44a2e89b9d1671a818f13.jpg@100w_100h_1c_1s.png)](https://space.bilibili.com/3546391456516604)

- 提供了视差节点

---

-*【排名不分先后，按首字母排序】*
