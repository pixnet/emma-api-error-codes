#
API Error Codes

## 認證錯誤

| 分類 | 子分類 | Error Code | HTTP Status Code | 訊息 | 說明 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 認證錯誤 | Token | 1000 | 401 | Invalid / expired Token | Token 過期，請重新要求新的 Token |
| 認證錯誤 | Token | 1001 | 401 | 錯誤：此APIkey已被停權 | API Key 被停權，請洽站方 |
| 認證錯誤 | Token | 1002 | 401 | Without Consumer Key | 沒有 Consumer Key |
| 認證錯誤 | Token | 1003 | 401 | You have to be authorized to post here. | 需要認證，請帶入 Access Token |
| 認證錯誤 | Token | 1004 | 401 | The developer account for this API Key requires cell phone number verification. | 這個 API Key 的開發者帳號需要通過手機號碼認證 |
| 認證錯誤 | Token | 1099 | 401 | \(其他 Token 錯誤\) | \(其他 Token 錯誤 |
| 認證錯誤 | 網路 | 1100 | 401 | IP Regex failed | 您的 IP 位址不被允許使用此 API |
| 認證錯誤 | 網路 | 1101 | 403 | Wrong Protocol, Please use HTTPS | 請使用 HTTPS 連接 API |
| 認證錯誤 | 網路 | 1102 | 403 | Wrong HTTP Method, requires \(GET/POST\) | 錯誤的 HTTP 方法，請確認說明文件 |
| 認證錯誤 | OAuth | 1200 | 401 | OAuth 錯誤 | OAuth 內部錯誤 |
| 認證錯誤 | OAuth | 1201 | 404 | OAuth token is not found | 找不到 OAuth Token |
| 認證錯誤 | OAuth | 1202 | 401 | 錯誤：您的請求已經過期或失效，請回到原網站重新申請 | 請求過期，請重新申請 |
| 認證錯誤 | OAuth | 1203 | 401 | Please Login first | 請登入 |
| 認證錯誤 | OAuth | 1204 | 401 | Redirect URI isn't match configuration. | 指定的 Redirect URI 與設定不符合 |
| 認證錯誤 | OAuth | 1205 | 401 | 「APP為部落格功能服務，請先啟用部落格」，開啟連至帳號中心/啟用服務頁 [https://pixnetid.pixnet.cc/\#/service](https://pixnetid.pixnet.cc/#/service) | member level 小於 4 |
| 認證錯誤 | Rate | 1300 | 403 | Exceed AccessToken Rate Limit | 超過此 Access Token 允許的呼叫頻率限制 |
| 認證錯誤 | Rate | 1301 | 403 | Exceed App Rate Limit | 超過此 App 允許的呼叫頻率限制 |
| 認證錯誤 | Rate | 1302 | 403 | Exceed Anonymous Rate Limit | 超過未認證 App 允許的呼叫頻率限制 |

## 找不到東西

| 分類 | 子分類 | Error Code | HTTP Status Code | 訊息 | 說明 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 找不到東西 | 使用者 | 2000 | 404 | User not found | 找不到 User |
| 找不到東西 | 部落格 | 2100 | 404 | Blog is not activated | 使用者尚未開啟 Blog |
| 找不到東西 | 部落格 | 2101 | 404 | Article is not found | 找不到文章 |
| 找不到東西 | 部落格 | 2102 | 404 | Comment is not found | 找不到文章留言 |
| 找不到東西 | 部落格 | 2103 | 404 | Category is not found. | 找不到部落格分類 |
| 找不到東西 | 部落格 | 2104 | 404 | Custom Sidecolumn is not found. | 找不到部落格側欄 |
| 找不到東西 | 相簿 | 2200 | 404 | 使用者尚未開啟 Album / Album is not found | 使用者尚未開啟相簿 |
| 找不到東西 | 相簿 | 2201 | 404 | Album element is not found | 找不到相片/影音 |
| 找不到東西 | 相簿 | 2202 | 404 | Album set is not found | 找不到相簿 |
| 找不到東西 | 相簿 | 2203 | 404 | Album folder is not found | 找不到相簿資料夾 |
| 找不到東西 | 相簿 | 2204 | 404 | Face not found | 找不到相片人臉 |
| 找不到東西 | 相簿 | 2205 | 404 | Albumset comment is not found | 找不到相簿留言 |
| 找不到東西 | 相簿 | 2206 | 404 | Albumelement comment is not found | 找不到相片留言 |
| 找不到東西 | 好友 | 2300 | 404 | Friendship is not found | 找不到好友關係 |
| 找不到東西 | 好友 | 2301 | 404 | Friend group is not found. | 找不到好友群組 |
| 找不到東西 | 好友 | 2302 | 404 | Subscription is not found. | 找不到訂閱資料 |
| 找不到東西 | 好友 | 2303 | 404 | Notify is not found. | 找不到通知 |
| 找不到東西 | 好友 | 2304 | 404 | Message is not found. | 找不到短訊 |
| 找不到東西 | 好友 | 2305 | 404 | Subscription group is not found. | 找不到訂閱群組 |
| 找不到東西 | 留言板 | 2400 | 404 | Guestbook is not activated | 使用者尚未開啟留言板 |
| 找不到東西 | 留言板 | 2401 | 404 | Guestbook article is not found. | 找不到留言板留言 |
| 找不到東西 | MIB | 2500 | 404 | MIB services is not applied | 使用者尚未開啟 MIB |
| 找不到東西 | 其他 | 2901 | 404 | Gritter Message is not found. | 找不到 Gritter Message |
| 找不到東西 | 其他 | 2902 | 404 | URL not found | 找不到這個網址 |

## 權限

| 分類 | 子分類 | Error Code | HTTP Status Code | 訊息 | 說明 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 權限 | 部落格 | 3100 | 403 | The article is not allowed to post comment | 此文章禁止留言 |
| 權限 | 部落格 | 3101 | 403 | The comment is locked by system. | 此留言被系統鎖定 |
| 權限 | 部落格 | 3102 | 403 | Delete article is locked | 欲刪除的文章被系統鎖定 |
| 權限 | 部落格 | 3103 | 403 | Delete article contains locked comments | 欲刪除的文章含有被鎖定的留言 |
| 權限 | 相簿 | 3200 | 403 | You have no permission to comment here. | 沒有權限在此篇文章留言 |
| 權限 | 相簿 | 3201 | 403 | 相簿已被系統鎖住 | 此相簿已被系統鎖定 |
| 權限 | 相簿 | 3202 | 403 | The comment is locked by system | 此留言被系統鎖定 |
| 權限 | 相簿 | 3203 | 403 | 相片留言已被系統鎖住 | |
| 權限 | 相簿 | 3204 | 403 | This album set contains locked comments | |
| 權限 | 相簿 | 3205 | 403 | The albumset comment is locked by system. | |
| 權限 | 留言板 | 3300 | 403 | You have no permission to post here | |
| 權限 | 其他 | 3900 | 403 | Permission Denied | |
| 權限 | 其他 | 3901 | 403 | VIP only feature | |
| 權限 | 其他 | 3902 | 403 | Password required | |
| 權限 | 其他 | 3903 | 403 | Permission denied, Friend only | |
| 權限 | 其他 | 3904 | 403 | Incorrect Password | |

## 輸入錯誤

| 分類 | 子分類 | Error Code | HTTP Status Code | 訊息 | 說明 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 輸入錯誤 | 缺少參數 | 4000 | 400 | User required | |
| 輸入錯誤 | 缺少參數 | 4001 | 400 | URL 中缺少必要參數 %s | |
| 輸入錯誤 | 缺少參數 | 4002 | 400 | Must specify the query string | |
| 輸入錯誤 | 缺少欄位 | 4100 | 400 | Payload 中缺少必要欄位 | |
| 輸入錯誤 | 缺少欄位 | 4101 | 400 | 請填入部落格ID欄位 | |
| 輸入錯誤 | 缺少欄位 | 4102 | 400 | Error, Params id\_image\_front or id\_image\_back not found | |
| 輸入錯誤 | 缺少欄位 | 4103 | 400 | upload file is missing | |
| 輸入錯誤 | 缺少欄位 | 4104 | 400 | 請輸入文章標題與內文 | |
| 輸入錯誤 | 缺少欄位 | 4105 | 400 | 請輸入作者欄位 | |
| 輸入錯誤 | 缺少欄位 | 4106 | 400 | 請輸入留言內容 | |
| 輸入錯誤 | 缺少欄位 | 4107 | 400 | 請輸入標題 | |
| 輸入錯誤 | 缺少欄位 | 4108 | 400 | 請填入訂閱群組 ID | |
| 輸入錯誤 | 缺少欄位 | 4109 | 400 | 請填入訂閱群組名稱 | |
| 輸入錯誤 | 缺少欄位 | 4109 | 400 | Missing cellphone or calling\_code | |
| 輸入錯誤 | 狀態不符合 | 4200 | 400 | User %s exists | |
| 輸入錯誤 | 狀態不符合 | 4201 | 404 | User is not in your block list. | |
| 輸入錯誤 | 狀態不符合 | 4202 | 400 | User is already in subscriptions. | |
| 輸入錯誤 | 狀態不符合 | 4203 | 400 | Upload MIB advertisement info failed, this user has been applied MIB. | |
| 輸入錯誤 | 狀態不符合 | 4204 | 403 | 不允許上傳至相簿資料夾 | |
| 輸入錯誤 | 狀態不符合 | 4205 | 400 | Maximum 20 tags are allowed | 最大僅允許20個tag |
| 輸入錯誤 | 狀態不符合 | 4206 | 403 | 系統相簿不能被修改 | |
| 輸入錯誤 | 狀態不符合 | 4207 | 403 | Invalid media | |
| 輸入錯誤 | 狀態不符合 | 4208 | 402 | Storage Quota Exceeded | |
| 輸入錯誤 | 狀態不符合 | 4209 | 402 | Monthly Uploading Quota Exceeded | |
| 輸入錯誤 | 狀態不符合 | 4210 | 400 | Face was deleted | |
| 輸入錯誤 | 狀態不符合 | 4211 | 400 | Out of Range | |
| 輸入錯誤 | 狀態不符合 | 4212 | 400 | Payment in progress | 已申請出帳，系統處理中 |
| 輸入錯誤 | 狀態不符合 | 4213 | 400 | Has asked for payment this month | 已申請出帳，系統處理中 |
| 輸入錯誤 | 狀態不符合 | 4214 | 400 | Remains less than threshold | 餘額未達申請條件 |
| 輸入錯誤 | 狀態不符合 | 4215 | 400 | Scheduled payment | 已排程出帳 |
| 輸入錯誤 | Rate | 4300 | 403 | User is posting comments too fast. | |
| 輸入錯誤 | Rate | 4301 | 403 | User is posting guestbook articles too fast. | |

## 輸入欄位驗證錯誤

| 分類 | 子分類 | Error Code | HTTP Status Code | 訊息 | 說明 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 輸入欄位驗證錯誤 | 使用者 | 5001 | 400 | Incorrect Verification Code | |
| 輸入欄位驗證錯誤 | 使用者 | 5002 | 400 | Invalid password, please use a longer password | |
| 輸入欄位驗證錯誤 | 使用者 | 5003 | 400 | Param user\_displayname is invalid | |
| 輸入欄位驗證錯誤 | 使用者 | 5004 | 400 | Param user\_displayname length is too long | |
| 輸入欄位驗證錯誤 | 使用者 | 5005 | 400 | Param birth is invalid | |
| 輸入欄位驗證錯誤 | 使用者 | 5006 | 400 | Param email is invalid | |
| 輸入欄位驗證錯誤 | 使用者 | 5007 | 400 | Invalid gender type | |
| 輸入欄位驗證錯誤 | 使用者 | 5008 | 400 | The cellphone number has been verified. | |
| 輸入欄位驗證錯誤 | 使用者 | 5009 | 400 | Duplicate Verification of cellphone number in 30 minutes. | |
| 輸入欄位驗證錯誤 | 使用者 | 5010 | 400 | Param co_email is invalid | |
| 輸入欄位驗證錯誤 | 使用者 | 5011 | 400 | Param fb_page is invalid | |
| 輸入欄位驗證錯誤 | 使用者 | 5012 | 400 | Param instagram is invalid | |
| 輸入欄位驗證錯誤 | 使用者 | 5013 | 400 | Param youtube is invalid | |
| 輸入欄位驗證錯誤 | 使用者 | 5014 | 400 | Param hourmaster is invalid | |
| 輸入欄位驗證錯誤 | 部落格 | 5101 | 400 | 請填入作者 | |
| 輸入欄位驗證錯誤 | 部落格 | 5102 | 400 | 請填入留言內容 | |
| 輸入欄位驗證錯誤 | 部落格 | 5103 | 400 | Param blog\_name length is too long | |
| 輸入欄位驗證錯誤 | 部落格 | 5104 | 400 | Param blog\_keyword length is too long | |
| 輸入欄位驗證錯誤 | 部落格 | 5105 | 400 | Invalid article status | |
| 輸入欄位驗證錯誤 | 相簿 | 5200 | 400 | Coordinates must be a positive number | |
| 輸入欄位驗證錯誤 | 相簿 | 5201 | 400 | Position座標已超出中縮圖大小 | |
| 輸入欄位驗證錯誤 | 相簿 | 5202 | 400 | Invalid media | |
| 輸入欄位驗證錯誤 | 相簿 | 5203 | 400 | Invalid face\_id | |
| 輸入欄位驗證錯誤 | 相簿 | 5204 | 400 | Latitude is not specified | |
| 輸入欄位驗證錯誤 | 相簿 | 5205 | 400 | Specified latitude is out of range. | |
| 輸入欄位驗證錯誤 | 相簿 | 5206 | 400 | Longtitude is not specified. | |
| 輸入欄位驗證錯誤 | 相簿 | 5207 | 400 | Specified longtitude is out of range. | |
| 輸入欄位驗證錯誤 | MIB | 5500 | 400 | Error, Param email is invalid. | |
| 輸入欄位驗證錯誤 | MIB | 5501 | 400 | Error, Param cellphone is invalid | |
| 輸入欄位驗證錯誤 | MIB | 5502 | 400 | Error, Param telephone is invalid. | |
| 輸入欄位驗證錯誤 | MIB | 5503 | 400 | Params fixed\_ad\_box or enabled error. | |
| 輸入欄位驗證錯誤 | MIB | 5504 | 400 | id\_image\_front file error, please register again. | |
| 輸入欄位驗證錯誤 | MIB | 5505 | 400 | id\_image\_back file error, please register again. | |
| 輸入欄位驗證錯誤 | MIB | 5506 | 400 | this email has been registered by another user. | |
| 輸入欄位驗證錯誤 | MIB | 5507 | 400 | id\_number is too long. | 身份證號過長 |

## 內部錯誤

| 分類 | 子分類 | Error Code | HTTP Status Code | 訊息 | 說明 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 內部錯誤 | 部落格 | 8100 | 500 | Create article failed | |
| 內部錯誤 | 部落格 | 8101 | 500 | Update article failed | |
| 內部錯誤 | 部落格 | 8102 | 500 | Delete article failed | |
| 內部錯誤 | 部落格 | 8103 | 500 | Show related articles failed | |
| 內部錯誤 | 部落格 | 8104 | 500 | Create comment failed. | |
| 內部錯誤 | 部落格 | 8105 | 500 | Reply comment failed | |
| 內部錯誤 | 部落格 | 8106 | 500 | Create category failed | |
| 內部錯誤 | 部落格 | 8107 | 500 | Update category failed | |
| 內部錯誤 | 部落格 | 8108 | 500 | Delete category failed | |
| 內部錯誤 | 相簿 | 8200 | 500 | uploaded failed | |
| 內部錯誤 | 相簿 | 8201 | 500 | Album element updated failed. | |
| 內部錯誤 | 相簿 | 8202 | 500 | Delete Album element failed. | |
| 內部錯誤 | 相簿 | 8203 | 500 | Create album set failed | |
| 內部錯誤 | 相簿 | 8204 | 500 | Update album set failed | |
| 內部錯誤 | 相簿 | 8205 | 500 | Delete album set failed | |
| 內部錯誤 | 相簿 | 8206 | 500 | Create album folder failed | |
| 內部錯誤 | 相簿 | 8207 | 500 | Update album folder failed | |
| 內部錯誤 | 相簿 | 8208 | 500 | Delete album folder failed | |
| 內部錯誤 | 相簿 | 8209 | 500 | 建立人臉記錄失敗 | |
| 內部錯誤 | 相簿 | 8210 | 500 | Create albumset comment failed. | |
| 內部錯誤 | 相簿 | 8211 | 500 | Create albumelement comment failed | |
| 內部錯誤 | 好友 | 8300 | 500 | Can\'t block this user | |
| 內部錯誤 | 好友 | 8301 | 500 | Update friend group failed | |
| 內部錯誤 | 好友 | 8302 | 500 | Create subscription group failed | |
| 內部錯誤 | 好友 | 8303 | 500 | Delete friend group failed | |
| 內部錯誤 | 好友 | 8304 | 500 | Update subscription group failed | |
| 內部錯誤 | 好友 | 8305 | 500 | Leave subscription group failed. | |
| 內部錯誤 | 好友 | 8306 | 500 | Join subscription group failed. | |
| 內部錯誤 | 留言板 | 8400 | 500 | Create guestbook comment failed | |
| 內部錯誤 | 留言板 | 8401 | 500 | Reply article failed | |
| 內部錯誤 | MIB | 8500 | 500 | Register MIB advertisement info failed, please try again later. | |
| 內部錯誤 | MIB | 8501 | 500 | MIB system is busy | |
| 內部錯誤 | MIB | 8502 | 500 | Update MIB advertisement position failed. | |
| 內部錯誤 | 其他 | 8900 | 500 | Internal application error | |



