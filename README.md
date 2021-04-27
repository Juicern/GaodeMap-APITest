# GaodeMap-APITest
 ## 主要功能

1. 註冊時賬號透過正則表示式判斷是否為正確的手機號
2. 密碼必須為6位以上的數字或字母組合
3. 註冊後跳回登陸介面，賬號密碼自動填寫
4. 若選中“記住賬號密碼”框，則會將密碼計入快取，下次開啟App時會自動填入（賬號填入為預設操作）
5. 登入後顯示地圖，點選“開始”按鈕可啟動小車，移動到地圖上其他位置時，點選“繼續”，則會返回小車執行的介面
6. 點選定位按鈕，會定位到當前位置（需給APP定位許可權）
7. 地圖縮放和旋轉正常，指南針也一切正常

## 注意事項

使用前需在高德開發者控制檯建立應用，獲取應用的key值

![](https://github.com/Ricky-Chu/GaodeMap-APITest/blob/main/GaoDe-key.png)

將此key值填入AndroidManifest.xml檔案meta-data下，具體路徑和位置如下：

![](https://github.com/Ricky-Chu/GaodeMap-APITest/blob/main/AndroidManifest-path.png)
