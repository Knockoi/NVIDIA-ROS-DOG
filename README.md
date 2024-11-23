# 在NVIDIA Omniverse Isaac Lab中模擬ROS機器人方式   
  
## 前言  
[NVIDIA Isaac ROS基礎控制邏輯](https://developer.nvidia.com/isaac/ros)  
  
## NVIDIA Omniverse 功能
#### NVIDIA Omniverse 是 NVIDIA 開發的一個開放式平台，專為 3D 設計和協作而設計。它利用了 NVIDIA RTX 技術來支持實時物理模擬和光線追蹤，並通過 Universal Scene Description (USD) 格式，為設計師、工程師和開發人員提供一個強大的工具集。以下是 Omniverse 的主要功能和應用：  
| 功能  | 描述 |
| ---- | -------- |
| 多用戶即時協作 | 支持多名用戶即時訪問同一 3D 場景，進行同步編輯和設計。消除了設計團隊中傳統的導入和導出工作流的摩擦。|
| 實時物理模擬 | 使用 NVIDIA PhysX 技術模擬真實世界的物理行為，如碰撞、重力和布料運動。|
| 光線追蹤渲染 | 基於 RTX 的實時光線追蹤技術，可生成接近照片品質的渲染效果，適用於產品可視化、建築設計和影片製作。|
| 開放和靈活的架構|支援 USD（Universal Scene Description），這是一種業界標準的場景描述格式，允許與多種 3D 工具和引擎集成，如 Autodesk Maya、3ds Max、Blender 和 Unreal Engine。|
| AI 驅動工作流 | 提供 AI 工具來加速內容創建，比如場景自動生成、3D 物體識別和優化設計工作流。 |  
  
## NVIDIA Omniverse Window版本安裝  
NVIDIA Omniverse Launcher:  
[NVIDIA Omniverse Launcher 安裝地點](https://developer.nvidia.com/omniverse#section-getting-started)  
[NVIDIA Omniverse Launcher Window直接安裝](https://install.launcher.omniverse.nvidia.com/installers/omniverse-launcher-win.exe) 
  
### NVIDIA Isaac SIM:  
需要先安裝NVIDIA Omniverse Launcher  
安裝路徑: NVIDIA Omniverse Launcher > EXCHANGE > INSTALL > 在Library中啟用   
### 1.開啟NVIDIA Omniverse Launcher，並點擊EXCHANG開啟商店  
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/1.png)
### 2.在EXCHANG中點擊NVIDIA Isaac SIM開啟安裝介面
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/2.png)
### 3.點擊INSTALL進行安裝
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/3.png)
### 4.確認開始進行安裝
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/4.png)

## 附件可用外掛:
### 地形檢測  
 [NVBLOX SLAM替代](https://blog.csdn.net/qq_29788741/article/details/134257346)  
 [Nvblox ROS1 安装配置](https://blog.csdn.net/m0_56661101/article/details/135292374)  
 [Nvblox Github](https://github.com/nvidia-isaac/nvblox)  
### 步態控制  
 [SPOT步態控制](https://www.bilibili.com/video/BV1HsSiYNEvZ/?spm_id_from=333.337.search-card.all.click&vd_source=35d2b7cdfe327b9931450d7679316692)  
 [四足步態控制](https://developer.nvidia.com/blog/closing-the-sim-to-real-gap-training-spot-quadruped-locomotion-with-nvidia-isaac-lab/
)  
 

