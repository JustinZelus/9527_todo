# 9527 jobs

# ICS

## iOS修改日誌
| Date       | Author | Ver   | Description                                                                                                                                                                                                                                                                                                                                                                       |
| ---------- | -----: | ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2019/05/26 |     JZ | 1.7.5| 1. [Bug] 修復之前動態切換tableView或collection會造成所有view位置上移問題。♪～(￣ε￣)  |
| 2019/05/23 |     JZ | 1.7.4| 1. 新增新版登入頁面。|
| 2019/05/22 |     JZ | 1.7.3| 1. 重構登入頁面流程(配合後端api)。|
| 2019/05/21 |     JZ | 1.7.2| 1. 帳密、fb、google登入流程(結合後端api)。<br>2. UserItem模組修改。<br>3. WebApi新增接口。<br>4. 推播改送加密過後SN。<br>4. 註冊頁面&註冊功能。|
| 2019/05/16 |     JZ | 1.7.1| 1. BaseTabBarController動態加入ViewController。<br>2.新增查詢服務頁面。|
| 2019/05/15 |     JZ | 1.7.0| 1. BaseCollectionFlowLayout新增調整cell細項的建構子。 <br>2.修改線上申辦-業務分類cell樣式。 |
| 2019/05/14 |     JZ | 1.6.9| 1. Bug修復 - collection滑動導致上方的view被上推。<br>2. 修改NavigationBar title顏色 |
| 2019/05/10 |     JZ | 1.6.8| 1. 新增google登入。|
| 2019/05/08 |     JZ | 1.6.7| 1. 新增登出功能。(僅FB)|
| 2019/05/03 |     JZ | 1.6.6| 1. 新增業務分類model。<br>2. 撰寫線上申辦頁面流程。|
| 2019/05/02 |     JZ | 1.6.5| 1. 新增線上申辦api及DB相關類別。<br>2. 新增版型View未來當作Library。(未完成)|
| 2019/04/29 |     JZ | 1.6.5| 1. 登入頁面流程實作。(未完成)|
| 2019/04/29 |     JZ | 1.6.4| 1. 新增導覽頁。|
| 2019/04/27 |     JZ | 1.6.2| 1. 隱藏‘查詢','線上申辦','線上繳費'。<br>2.  新增線上申辦頁面。|
| 2019/04/25 |     JZ | 1.6.1| 1. 新增導覽頁。 |
| 2019/04/24 |     JZ | 1.6.0| 1. UI框架變更 - 新增TabBar。 <br> 2. 九宮格menu間距調整。 |
| 2019/04/19 |     JZ | 1.5.9| 1. 個人編輯頁面統一改成pickerView。(未完成) |
| 2019/04/17 |     JZ | 1.5.9| 1. 新增cookie - appMode。 |
| 2019/04/16 |     JZ | 1.5.8| 1. 呼叫LinkList api時夾參數SN。(city) |
| 2019/04/11 |     JZ | 1.5.7| 1. 更換主題色。<br>。2. 選多城市造成menu重複修復。|
| 2019/04/08 |     JZ | 1.5.4| 1. App啟動時即化呼叫個人福利Api，並將資料寫入DB。(完成，待改善)<br>2. DataSource現在一律要餵TotalCount。<br>3. ‘已收藏’閉包移至controller。<br>4. person新增欄位 - favoritesWelfare。<br>5. PersonManager新增接口 - refreshPersonCount。<br>6. ‘符合’取消點擊功能。<br>7.  新增單一程式&多城市旗標。<br>8. PersonWelfareManager類程式碼重構。|
| 2019/04/07 |     JZ | 1.5.4| 1. App啟動時即化呼叫個人福利Api，並將資料寫入DB。(未完)|
| 2019/04/03 |     JZ | 1.5.4| 1. App啟動時即化呼叫個人福利Api，並將資料寫入DB。(未完)|
| 2019/04/02 |     JZ | 1.5.4| 1. 變更Menu頁佈局。|
| 2019/04/01 |     JZ | 1.5.4| 1. 新增Demo用的Api - CityListDemo。|
| 2019/03/29 |     JZ | 1.5.3| 1. 增加使用者體驗 - 個人福利頁面若資料未下載，table的cell上需出現indicator。<br> 2. Menu九宮格新增陰影，後台可以調顏色、圖片。|
| 2019/03/28 |     JZ | 1.5.2| 1. 修復鈴鐺沒有出現推播的數字問題。<br>2. DataSource新增infinite接口。<br>3. 更改個人福利資料讀取機制。現在不經過DB，改存記憶體，爾後有變動都直接更新記憶體。<br>4. 個人福利新增prefetching機制。|
| 2019/03/27 |     JZ | 1.5.1| 1. 雖已加入新圖，但會因為iphone底層cashe問題而導致依然讀取舊圖。需刪除app並關機再重新啟動。<br>2. 個人福利新增loading動畫。|
| 2019/03/26 |     JZ | 1.5.0| 1. 更名為城鄉服務。|
| 2019/03/22 |     JZ | 1.4.9| 1. 移除postNew，查詢福利之前會去Menu頁面拿縣市並存在RequestModel。|
| 2019/03/19 |     JZ | 1.4.9| 1. 新增backround mode - remote notification。<br>2. 新增LocalAuthentication - TouchID用。<br>3. 前景模式接收到推播時鈴鐺更新<br>4. 背景模式接收到推波後返回前景時鈴鐺更新。|
| 2019/03/18 |     JZ | 1.4.8| 1. count 沒有更新 - 查api。<br>2. 返回未讀沒有更新為已讀。<br>3. app icon的badge。<br>4. 第一次FB登入後，count沒出現|
| 2019/03/17 |     JZ | 1.4.7 | 1. badge icon。<br> 2. 推播頁面點擊Event。|
| 2019/03/15 |     JZ | 1.4.7 | 1. 推播頁面。<br> 2. 推播內容頁。 <br> 3. API - 更新是否已讀。|
| 2019/03/14 |     JZ | 1.4.6 | 1. 符合幾筆 & 收藏 -> 點選 -> 各進不同畫面。<br>2. menu頁新增鈴鐺功能  
| 2019/03/13 |     JZ | 1.4.5 | 1. 編輯個人資料頁面返回時，送出MyInfo。                                                                                                                                                                                                                                                                                                                          |
| 2019/03/12 |     JZ | 1.4.5 | 1. Bug #3.                                                                                                                                                                                                                                                                                                                          |
| 2019/03/11 |     JZ | 1.4.4 | 1. Bug #2.<br> 2. WelfareContent右上顯示資料來源。<br> 3. FB按鈕自定義。<br> 4. FB登入後取得大頭照、email。<br> 5. 滾輪全中文化。<br> 6. FB按鈕加大。                                                                                                                                                                                                                                                                                                                                           |
| 2019/03/08 |     JZ | 1.4.3 | 1. FB登入功能。<br>2. Bug ＃1.<br>3. 變更教育滾輪順序。<br> 4. 新增長按FB登出功能。(未完成)                                                                                                                                                                                                                                                                                                                                              |
| 2019/03/06 |     JZ | 1.4.0 | 1. 顏色調整。<br>2. Menu頁面九個icon的順序與圖片改與美工同。(僅api變更)<br>3. 隱藏詢問小幅。<br> 4. 推播功能(Token尚未綁定帳號)。<br>5. 收到推播點進去App後消除badge。<br> 6. 更新api - CityList & LinkList。(by 紹軒)<br> 7. webview夾帶cookie。(user個人資料)<br>8. 新增通訊地址欄位。<br>9. 新增函式date ToString()、jsonToString()。<br>10. 隱藏GuideVC。(isNotRemind=flase)。<br>11. 新增登入頁面。(功能未寫)                                                                                                                                                                                                                                                                                                                                                |
| 2019/03/04 |     JZ | 1.3.9 | 1.用戶編輯新增email欄位。<br>2.身分證 -> 身分證統一編號。住址 -> 戶籍地。                                                                                                                                                                                                                                                                                                                                                    |
| 2019/03/04 |     JZ | 1.3.9 | 1.修改Api路徑，回傳資料格式不變。(by 君品) <br> 2.底層NetworkService新增postNew測試。<br> 3.WelfareContentManage接收到的data，Json改成小寫。<br>4.福利查詢頁面scrollTottom暫時取消loadData。                                                                                                                                                                                                                                                                                                  |



___
___



## Bug Issue

1. (done)在user編輯頁面選任一欄位，然後不輸入任何值，按下done，按左上返回即閃退。 
2. (done)我的福利 -> 點選籤編輯 -> 左上返回 -> 我的收藏會消失。
3. (done)符合幾筆未能及時更新。
4. 我的福利 -> 點編輯 -> 改縣市返回 -> 符合幾筆未能即時刷新。
5. 程式碼找出CityName
6. (done)post https://ss.hamastar.com.tw/welfarewebsite/api/welfare/PersonWelfare 未給SN
7. 推播有時候收不到


___
___



## 待完成功能

1. (done)符合幾筆 & 收藏 -> 點選 -> 各進不同畫面。
2. (done)WelfareContent右上顯示資料來源。
3. (done)FB按鈕自定義。
4. (done)FB按鈕加大。
5. (done)FB登入後取得大頭照、email。
6. (done)滾輪全中文化。
7. (done)menu頁新增鈴鐺功能。
8. 點選FB登入 -> 僅出現開啟Safari的選項。
9. FB登入後90天自動登出。
10. 修正PostNew預設嘉義縣程式碼。
11. sendRequestWithCookie,戶籍地址。
12. (done)編輯個人資料頁面返回時，送出MyInfo。
13. (done)Survey TouchID
14. token加密 
15. 後端RegisterMyInfo更新目前無效

___
___



## 其它

1. 公司電腦產出ipa檔問題。
2. app store connect 不能登入問題(已解決)。
3. 憑證即將到期(已解決)。
4. 對外網路api讀取較慢，我的福利明顯(已改善，改成一次讀30筆)。
5. 設計師UIUX https://xd.adobe.com/view/246b111f-7702-4710-43a0-2eb0217c251e-525a/?fullscreen













