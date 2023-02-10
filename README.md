# Spreadsheets Extension - Read, write & modify data from sheets ⚡
An awesome extension to work with google spreadsheet. You can read, write and modify data from your sheets.
* **

![image](https://user-images.githubusercontent.com/75406851/218042378-ade70b3c-819c-43ea-96b1-0f97cf8126ad.png)

Google Spreadsheets Extension | Free & Fastest Database | Script-less extension. It's 5x Faster Than Airtable. It also give you offline support once data is loaded. It's very secure to protect your data from hackers. It can load huge amount of data. It's very simple and easy to integrate this extension into your application. Read release notes for knowing about new features.

## ⬇️ Extension Properties

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/75406851/218042497-2811c53d-7738-4207-97ee-eaf460aa5448.png"></td>
    <td><img src="https://user-images.githubusercontent.com/75406851/218042548-2b7f2245-01fe-4476-aede-3d99340dce3e.png"></td>
  </tr>
</table>

<br>

<details>
<summary><b>Requirements  </b></summary>
<br>
<img src="https://user-images.githubusercontent.com/75406851/218042696-4d94aae7-73a5-4948-a858-97733dc214e6.png">
<img src="https://user-images.githubusercontent.com/75406851/218042758-9b21c2da-fda0-4924-875d-1692145a3d54.png">
</details>

* **

## ⬇️ Get All Rows
Using this blocks you can get all rows from your sheet.

![image](https://user-images.githubusercontent.com/75406851/218042929-6a996ed9-6550-411d-bc40-224d299abfbb.png)

![image](https://user-images.githubusercontent.com/75406851/218042947-fecaa7c2-70c0-4f9b-a247-2ff0b23e8f21.png)

`totalRow` - It's return the total number of rows.\
`totalColumn` - It's return the total number of columns.\
`loadTime` - It's return the milliseconds of loading time.\
`response Content` - It's return the Json string.

## ⬇️ Get Column
Using this blocks you can get any column from your sheet. Set 0 on max to get all values from column.

![image](https://user-images.githubusercontent.com/75406851/218043814-dd422c6b-5155-411d-a399-8482d4fe18c6.png)

`column Name` - Enter column name.\
`max` - Enter limit to get values.

![image](https://user-images.githubusercontent.com/75406851/218043843-53c059ff-aa4b-4614-871e-5b076eeffdca.png)

`column Name` - It's return the name of column.\
`values` - It's return the list of values.\
`length` - It's return the length of given column.

## ⬇️ Get Cell
Using this blocks you can get single cell from your sheet.

![image](https://user-images.githubusercontent.com/75406851/218043945-d83bb983-8732-4100-ba16-ad60834663e0.png)

`columnName` - Enter column name.\
`row Number` - Enter row number.

![image](https://user-images.githubusercontent.com/75406851/218043979-00c465a7-7712-421f-abc9-d2fe52796f63.png)

`column Name` - It's return given column name.\
`row Number` - It's return given row number.\
`value` - It's return cell value.

## 🔎 Search
Using this blocks you can get single column by filtering.

![image](https://user-images.githubusercontent.com/75406851/218044031-04618d1b-9cf0-4618-b911-92570ee8de72.png)

`column Name` - Enter Column name to search data.\
`keyword` - Enter search text to filter data.

![image](https://user-images.githubusercontent.com/75406851/218044052-bebb7d0c-bd25-4c84-a1da-c56d9bdaa530.png)

`column Name` - It's return the given column name.\
`keyword` - It's return the given keyword.\
`values` - It's return the list of matching value.\
`positions` - It's return the positions of filtered data.\
`length` - It's return the length of filtered list.

## 🔎 Advance Search
Using this blocks you can get filtered data by search from two columns.

![image](https://user-images.githubusercontent.com/75406851/218044109-4dbfe6b5-746c-4e36-a457-1e792a6f34d5.png)

`byColumn` - Enter column name to search.\
`keyword` - Enter search text.\
`fromColumn` - Enter column name to fetch data.

![image](https://user-images.githubusercontent.com/75406851/218044159-eb818910-002a-460d-86bd-44aafe6e2f94.png)

`byColumn` - It's return byColumn name.\
`keyword` - It's return search text.\
`fromColumn` - It's return fromColumn name.\
`values` - It's return the list of matching value.\
`positions` - It's return the positions of filtered data.\
`length` - It's return the length of filtered list.

## ⬇️ Get Row
Using this blocks you can get values of any row.

![image](https://user-images.githubusercontent.com/75406851/218044287-e4a9c816-6189-477e-b116-38cd14bf904d.png)

`row Number` - Enter row number to get values.

![image](https://user-images.githubusercontent.com/75406851/218044313-7ffb8b36-cb3b-4572-a707-11afa81fefc6.png)

`row Number` - It's return the row number.\
`values` - It's return the list of values.\
`column Names` - It's return the list of column names.

## ⬇️ Get Sheet Names
Using this blocks you can get list of your sheets.

![image](https://user-images.githubusercontent.com/75406851/218044348-8e7f70f6-f9b4-4285-b361-8f99a9f29990.png)

![image](https://user-images.githubusercontent.com/75406851/218044364-6a29fec0-8a40-4880-bece-0534955d7577.png)

`sheetNames` - It's return the list of sheet names.\
`gidIds` - It's return the list of gid ids.\
`length` - It's return the length of sheet list.

## ⬇️ Get Column Names
Using this blocks you can get names of all columns.

![image](https://user-images.githubusercontent.com/75406851/218044439-230c63d6-3d5e-48cd-a104-a5ae8f2867a5.png)

![image](https://user-images.githubusercontent.com/75406851/218044454-0d8de339-5fe8-47f8-9a93-e9d2d27f138a.png)

`column Names` - It's return the list of column names.\
`length` - It's return the length of list.

## ⬇️ Get Spreadsheet Name
Using this blocks you can get your spreadsheet project name.

![image](https://user-images.githubusercontent.com/75406851/218044486-02eeccc5-d74d-432f-b805-a7dd797deac4.png)

![image](https://user-images.githubusercontent.com/75406851/218047525-9f61c1dd-e019-4e9a-9f80-33f4f7f3d9e0.png)

`spreadsheetName` - It's return the name of your spreadsheet project.

## ⬇️ Total Rows
Using this block you can get total number of all rows.

![image](https://user-images.githubusercontent.com/75406851/218044533-ec5049e5-39c3-440a-a516-be4852785a32.png)

## ➕ Create Column
Using this blocks you can create new column in your sheet.

![image](https://user-images.githubusercontent.com/75406851/218044577-447d4235-042f-47ce-88db-339fc99aab35.png)

`column Name` - Enter new name to create column.

![image](https://user-images.githubusercontent.com/75406851/218044595-632226bf-96a7-442f-a806-f2b44156d293.png)

`column Name` - It's return the new name.\
`columnPosition` - It's return the position of new column.

## ➕ Create Row
Using this blocks you can create single cell in you sheet.

![image](https://user-images.githubusercontent.com/75406851/218044643-31ca0ca7-97a4-4ca0-942c-7f36dc49b58e.png)

`column Name` - Enter the column name where need to create row.\
`value` - Enter cell value to create row.

![image](https://user-images.githubusercontent.com/75406851/218044653-d6afd326-24f1-4f2e-983e-a49435675976.png)

`row Number` - It's return the number of row.
`column Name` - It's return the name of column.
`value` - It's return the value.

## ➕ Create Rows
Using this blocks you can create new row with multiple cells.

![image](https://user-images.githubusercontent.com/75406851/218044696-1334e837-7e70-471e-9d4f-cf1997bbfc8d.png)

`values` - Enter values as list to create new row.

![image](https://user-images.githubusercontent.com/75406851/218044713-4c37463c-6d2d-42f6-ad8f-7b2c298a8a67.png)

`response` - It's return the response string.

## ➕ Create Sheet
Using this blocks you can create new sheet in your spreadsheet project.

![image](https://user-images.githubusercontent.com/75406851/218044740-a393990b-2575-4369-b590-ac1ef1b45e2c.png)

`sheetName` - Enter new sheet name.

![image](https://user-images.githubusercontent.com/75406851/218044789-44dcdef9-510e-487f-aa45-52b8e307ae4c.png)

`sheetName` - It's return the name of sheet.

## ⤴️ Update Cell
Using this blocks you can update any cell.

![image](https://user-images.githubusercontent.com/75406851/218044826-6afd0410-922e-4f10-89d9-179732f71a6c.png)

`column Name` - Enter column name.\
`row Number` - Enter row number.\
`value` - Enter new value.

![image](https://user-images.githubusercontent.com/75406851/218044847-d5837e27-01ec-4f4a-b5a5-d24fca13ebd9.png)

`column Name` - It's return the name of column.\
`row Number` - It's return the row number.\
`value` - It's return the value.

## ⤴️ Update Rows
Using this blocks you can update any row values.

![image](https://user-images.githubusercontent.com/75406851/218044873-a5462576-9eaa-4adf-b50b-1ca1455a5983.png)

`row Number` - Enter row number.\
`column Names` - Enter column names as list.\
`values` - Enter values as list.

![image](https://user-images.githubusercontent.com/75406851/218044888-2c4f7a60-8089-4ff2-b2f4-49f964918429.png)

`row Number` - It's return the number of row.

## ✂️ Delete Row
Using this blocks you can delete any row by row number.

![image](https://user-images.githubusercontent.com/75406851/218044919-c59134a6-9b4a-41c3-a3be-155eb486f991.png)

`row Number` - Enter row number.

![image](https://user-images.githubusercontent.com/75406851/218044945-7a80d559-6643-4340-a30b-4168b191a706.png)

`row Number` - It's return the number of row.

## ✂️ Delete Column
Using this blocks you can delete any column from your sheet.

![image](https://user-images.githubusercontent.com/75406851/218044970-2fa32135-5047-4fa9-a679-c23ca4b45a06.png)

`column Name` - Enter column name to delete.

![image](https://user-images.githubusercontent.com/75406851/218044987-74929026-0d70-4a5a-afae-6e631cf2cf07.png)

`column Name` - It's return the name of column.\
`position` - It's return the position of column.

## ✂️ Delete Sheet
Using this blocks you can delete any sheet from your spreadsheet project.

![image](https://user-images.githubusercontent.com/75406851/218045047-31766464-6508-41a5-b465-6f69084275cd.png)

`sheetName` -  Enter sheet name to delete.

![image](https://user-images.githubusercontent.com/75406851/218045059-7c2fd2ff-8145-412d-b348-e7c7e8c0cdd6.png)

`sheetName` - It's return the name of sheet.

## ✍️ Rename Sheet
Using this blocks you can rename any sheet from your project.

![image](https://user-images.githubusercontent.com/75406851/218045086-9f192b7d-5a8e-4e16-8005-c494465be18e.png)

`oldName` - Enter old name of sheet.\
`new Name` - Enter new name to rename sheet.

![image](https://user-images.githubusercontent.com/75406851/218045100-8254b93a-743e-4c1a-9e1f-905a75136365.png)

`new Name` - It's return the new name of sheet.\
`oldName` - It's return the old name.

## ✍️ Rename Spreadsheet
Using this blocks you can rename your project name.

![image](https://user-images.githubusercontent.com/75406851/218045127-05ec9403-38d2-41d9-b627-65231accaad4.png)

`name` -  Enter new name to rename spreadsheet project name.

![image](https://user-images.githubusercontent.com/75406851/218045138-d4d95769-d307-4c92-be5b-b8c046d006d3.png)

`name` - It's return the new name of your project.

## 🔁 Replace All
Using this function you can replace all matching text from active sheet with new value.

![image](https://user-images.githubusercontent.com/75406851/218045164-4baff55e-4e35-4f16-9574-c04d9f6c1b5a.png)

`text` - Enter text to replace with new value.\
`replaceWith` - Enter new value to replace with old value.

![image](https://user-images.githubusercontent.com/75406851/218045185-2aec60a2-c943-45fd-8e16-61fa326c08b6.png)

`text` - It's return the old value.\
`replaceWith` - It's return the new value.

## 🔁 Replace By Column
Using this function you can replace all matching text from column with new value.

![image](https://user-images.githubusercontent.com/75406851/218045219-fc81237c-5b57-4dd5-a1e9-04bdeeea176d.png)

`columnName` - Enter column name where you want to replace values.\
`text` - Enter text to replace with new value.\
`replaceWith` - Enter new value to replace with old value.

![image](https://user-images.githubusercontent.com/75406851/218045236-d852f7a3-8c11-4895-a3a8-a65c092b9279.png)

`columnName` - It's return the column name.\
`text` - It's return the old value.\
`replaceWith` - It's return the new value.

## 🔁 Replace By Row
Using this function you can replace all matching text from row with new value.

![image](https://user-images.githubusercontent.com/75406851/218045272-49d32857-e9fc-4516-a3d5-46d3c5c55745.png)

`rowNumber` - Enter row number where you want to replace values.\
`text` - Enter text to replace with new value.\
`replaceWith` - Enter new value to replace with old value.

![image](https://user-images.githubusercontent.com/75406851/218045291-30c9a0c5-b465-4577-86f4-2b3fec251854.png)

`rowNumber` - It's return the row number.\
`text` - It's return the old value.\
`replaceWith` - It's return the new value.

## 🔁 Replace For All Sheets
Using this function you can replace all matching text from all sheets with new value.

![image](https://user-images.githubusercontent.com/75406851/218045329-617b3979-0bc7-4672-aa1a-a97bd9b56cd2.png)

`text` - Enter text to replace with new value.\
`replaceWith` - Enter new value to replace with old value.

![image](https://user-images.githubusercontent.com/75406851/218045353-f4dbbed5-7b10-471e-b0fe-57cc18c7211e.png)

`text` - It's return the old value.\
`replaceWith` - It's return the new value.

## 🔃 Refresh Data
Using this blocks you can refresh data manually if you disabled Auto Refresh. Otherwise no need to refresh data manually.

![image](https://user-images.githubusercontent.com/75406851/218045394-0c2475a3-1810-4d9a-820d-29603e0b2dba.png)

![image](https://user-images.githubusercontent.com/75406851/218045415-e78c1814-84bb-47c8-9660-8720b633af0b.png)

`function Name` - It's return the function name which function refresh data automatically.\
`totalRow` - It's return the total number of rows.\
`totalColumn` - It's return the total number of columns.\
`loadTime` - It's return the milliseconds of loading time.\
`response Content` - It's return the Json string.

## ⚠ Failed
It's rises when the extension got any error.

![image](https://user-images.githubusercontent.com/75406851/218045441-752d24ec-4dab-435c-99a5-8abd348eb137.png)

`function Name` - It's return the function name which function got error.\
`error Message` - It's return the error message as string.

## 🔐 Encode & Decode
Using this blocks you can protect your sheet ids and sheet name etc. Set level (1-100) and password length must be 5 or more.

![image](https://user-images.githubusercontent.com/75406851/218045467-0c6dbd07-494d-417e-979d-330be3e2aed2.png)

![image](https://user-images.githubusercontent.com/75406851/218045479-632a5a2d-1fa2-4c4e-a2b3-0ff5c05b2137.png)
***


## 📝 Release Notes ↷
<li> <b>10.0.1:</b> Changed some blocks names.
<li> <b>10.0.0:</b> Added 3 new functions <small>(ReplaceByColumn, ReplaceByRow, ReplaceForAllSheets)</small>.
<li> <b>9.6.0:</b> Added new <b>ReplaceAll</b> function.
<li> <b>9.5.3:</b> Now you can get positions of filtered data.
<li> <b>9.5.2:</b> Crash issue fixed for Android 8 & lower version.
<li> <b>9.5.1:</b> Fixed an issue & optimize offline / online mode.
<li> <b>9.4.0:</b> Removed <b>NameSpace</b> from designer section.
<li> <b>9.3.0:</b> Bugs fix for offline mode turn off/on option .
<li> <b>9.2.0:</b> Now you can turn off/on offline mode manually.
<li> <b>9.1.2:</b> Support automatically data loading feature.
<li> <b>9.1.0:</b> Smooth experience for loading huge data.
<li> <b>9.0.0:</b> Extension size compressed to 106 KB.

* **

## 📺 Testing Video ↓

[![Spreadsheet](http://img.youtube.com/vi/mnqTLrMAXps/0.jpg)](https://www.youtube.com/watch?v=mnqTLrMAXps)

## 📺 Implementation Guide Video **↓**

[![Spreadsheet](http://img.youtube.com/vi/VGuE-DOU9ds/0.jpg)](https://www.youtube.com/watch?v=VGuE-DOU9ds&list=PLczFHGJFYQrkl9EhbkeMiaGXMDQfw61dZ)

## ⬇️ More extensions

<a href="https://github.com/jewelshkjony?tab=repositories">See more extensions</a>

## 📑 Extension Specifications:
<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/download.png"/> <a href="https://t.me/jewelshkjony">com.jewel.spreadsheets.aix</a> (123 KB) \
<b>Version:</b> 10.0.1\
<b>Price:</b> $5 USD <sub>(Standard Edition) - [Speed, validity and some functions are limited. Also you'll not get any future updates for free.]</sub> \
<b>Price:</b> $10 USD <sub>(Premium Edition) - [Speed and validity is encreased. Unlocked all of functions but plan upgrade limitation remain. Recommend for mid budget users.]</sub> \
<b>Price:</b> $15 USD <sub>(Platinum Edition) - [Speed and validity is more extended. Remain upgrade limitation. Recommend for all.]</sub> \
<b>Price:</b> $20 USD <sub>(Flash Edition) - [More validity and no speed limitations & updates are totally free! Tested with 1M rows! Recommend for higher end budget only.]</sub> \
<b>Price:</b> $25 USD <sub>(Speedster Edition) - [Everything is unlocked and premium. No limitations & lifetime support! Tested with 2M rows! Recommend for higher end budget only.]</sub> \
<b>Last amendment:</b> 09 February 2023\
<b>Supported builder:</b> <a href="https://www.kodular.io/">Kodular</a>, <a href="https://niotron.com/">Niotron</a>, <a href="https://appzard.com/">AppZard</a>, <a href="https://androidbuilder.in/">AndroidBuilder</a>, <a href="http://ai2.appinventor.mit.edu/">App Inventor</a> and it's other distributions.

## 📫 How to reach me -
<a href="https://t.me/jewelshkjony">Telegram</a> | <a href="https://wa.me/8801775668913">WhatsApp</a> | <a href="https://fb.com/jewelshkjony">Facebook</a> | <a href="https://m.me/jewelshkjony">Messenger</a> | <a href="https://m.youtube.com/c/JewelShikderJony">Youtube</a>

## 💲 Payment Methods ↓
❏ <a href="https://www.xoom.com/bangladesh/send-money" target="_blank">Xoom</a> | <a href="https://wise.com/?sourceCurrency=USD&targetCurrency=BDT&sourceAmount=20" target="_blank">Wise</a> | <a href="https://www.skrill.com/en/">Skrill</a> | <a href="https://www.binance.me/en/activity/referral-entry/CPA?fromActivityPage=true&ref=CPA_0068YL77KV" target="_blank">Binance</a> | <a href="https://play.google.com/store/apps/details?id=com.jewelshkjony.pay2me">Pay2Me</a> | <a href="https://www.paypal.com/">Paypal</a>  (Global)

❏ <a href="https://bka.sh/next?c=signup&uuid=C1CC9JVT1" target="_blank">bkash</a> | <a href="https://play.google.com/store/apps/details?id=com.konasl.nagad">Nagad</a> | <a href="https://play.google.com/store/apps/details?id=com.dbbl.mbs.apps.main">Rocket</a> (Bangladesh)
