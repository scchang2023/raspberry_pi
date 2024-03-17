# raspberry_pi

## 在 raspberry pi 上安裝作業系統

- 到官網下載OS，下載完成後會產生一個 imager 的執行檔 ： [Raspberry Pi OS](https://www.raspberrypi.com/software/)

  ![alt text](image.png)

- 執行 imager
- 選擇 raspberry pi device：我的是 raspberry pi 4 model B
- 選擇操作系統：目前是設定 raspberry pi OS 64bits
- 選擇儲存卡：SD Card
- 輯輯設定
  - 主機名：raspberrypiSCC.local
  - username：pi
  - password：raspberry
  - WIFI 名稱： LINKOU203-4F-5G
  - WIFI 密碼： xxx
- 開始燒錄
- 燒錄完成後，將SD Card拔除，並插到 raspberry pi 機器上開機即可。
- 確認是否有安裝成功：
  用電腦 ping 機器上的主機名稱，看是否有回應：`ping raspberrypiSCC.local`，如有回應表示已安裝成功。
![alt text](image-1.png)