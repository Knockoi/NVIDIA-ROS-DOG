# NVIDIA Isaac Sim 安裝    
## Linux版本:
## 安裝Nvidia驅動器  
先檢查是否有Nvidia驅動程序  
### 1.開啟設定  
### 2.開啟NVIDIA Omniverse Launcher，並點擊EXCHANG開啟商店  
### 3.開啟NVIDIA Omniverse Launcher，並點擊EXCHANG開啟商店  

安裝



## NVIDIA Omniverse 部署啟動器  
若要在 Linux（Ubuntu 20.04 和 22.04）上安裝 IT Managed Launcher，請執行下列步驟：  
透過在使用者工作站本地啟動從許可證入口網站下載的 AppImage 來執行 IT 託管啟動器。  
在 Linux 上，您首先需要將 AppImage 設定為可執行程式並啟動它，而不是執行 IT Managed Launcher 安裝程式。  
這會將應用程式註冊omniverse-launcher://為本文檔其他地方描述的自訂 URL 的預設處理程序，該處理程序自行安裝應用程式。  
對於 Ubuntu 用戶，請確保您已完成以下操作，以便 AppImage 能夠啟動。  
從終端，首先運作：  
```bash
> sudo apt install libfuse2
```
然後確保檢查下載的 AppImage 檔案的權限，以驗證它是否可以作為程式運行。
使用 UI，右鍵單擊 AppImage 並選擇“屬性”。轉到“權限”部分並確保選中“允許將檔案作為程式執行”複選框。
或者，從終端，在保存 AppImage 的目錄中：
```bash
> chmod +x omniverse-launcher-linux-enterprise.AppImage
```
完成這些項目後，您應該能夠雙擊 AppImage 套件並運行它。或者，從終端運行它：
```bash
> ./omniverse-launcher-linux-enterprise.AppImage
```


## 安裝NVIDIA Omniverse Launcher  
安裝路徑: NVIDIA Omniverse Launcher > EXCHANGE > INSTALL > 在Library中啟用   
### 1.開啟NVIDIA Omniverse Launcher，並點擊EXCHANG開啟商店  
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/1.png)  
### 2.在EXCHANG中點擊NVIDIA Isaac Sim開啟安裝介面
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/2.png)  
### 3.點擊INSTALL進行安裝
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/3.png)  
### 4.確認開始進行安裝
![image](https://github.com/Knockoi/NVIDIA-ROS-DOG/blob/main/%E5%8F%83%E8%80%83%E5%9C%96%E7%89%87/4.png)  

