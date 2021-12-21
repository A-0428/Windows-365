# Windows 365 Business 啟用流程 
當您已經有購買了Windows 365 Business授權後會需要指定一個User，指定User授權要先登入**Microsoft 365 admin center** <br>
1. 使用全域管理員登入**Microsoft 365 admin center**介面 <br>
2. 選擇您要授權 Windows 365 的帳號(這邊範例是使用**user3@csi760.com.tw**此帳號) <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image1.jpg) <br>
3. 點選該帳號後再點擊"**授權與APP**" <br>
4. 再來就選擇我們要授權的Windows 365 Business License (範例中授權的規格為:**Windows 365 Business 1 vCPU, 2 GB , 64 GB**) <br>
5. 點選儲存變更 <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image2.jpg) <br>
前往Windows 365登入網站 : https://windows365.microsoft.com/ <br>
進入後要輸入您授權使用者的帳號以及密碼，輸入完成登入之後就會看到歡迎的畫面，請點選"**Next**" <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image7.jpg) <br>
看到**What's a Cloud PC?**，請點選"**Next**" <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image8.jpg) <br>
看到**What can I do with a Cloud PC ?**，請點選"**Next**" <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image9.jpg) <br>
看到**Your Cloud PC is getting ready**，請點選"**Get started**" <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image10.jpg) <br>
在正常情況下應該會看到"**Setting up Cloud PC**"的畫面 <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image16.jpg) <br>
但如果你出現錯誤訊息 <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image11.jpg) <br>
這時您就要確認一下該錯誤訊息是屬於什麼問題，以範例中為例是我User3帳號未開啟MFA驗證所導致此錯誤發生 <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image12.jpg) <br>
回到我們**Microsoft 365 admin center**介面，選擇我們User3帳號，點選"**多重要素驗證**" <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image5.jpg) <br>
將User3的**MFA狀態**調整成"**強制**" <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image6.jpg) <br>
設定完成後回到我們Wimdows 365平台，點擊齒輪符號、點選Restart <br>
![GITHUB](https://github.com/A-0428/Windows-365/blob/main/Windows365/image14.jpg) <br>
