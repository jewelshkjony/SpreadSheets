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
* **
Using this blocks you can get all rows from your sheet.

![image](https://user-images.githubusercontent.com/75406851/218042929-6a996ed9-6550-411d-bc40-224d299abfbb.png)

![image](https://user-images.githubusercontent.com/75406851/218042947-fecaa7c2-70c0-4f9b-a247-2ff0b23e8f21.png)

`totalRow` - It's return the total number of rows.
`totalColumn` - It's return the total number of columns.
`loadTime` - It's return the milliseconds of loading time.
`response Content` - It's return the Json string.

## ⬇️ Get Column
* **
Using this blocks you can get any column from your sheet. Set 0 on max to get all values from column.

![image|285x83](upload://A7G3nI5gAiXmNakEyDjJPmSBk0j.png)

`column Name` - Enter column name.
`max` - Enter limit to get values.

![image|288x94](upload://2xzOUyOoDQogTBQ1jZGWIBfDWdC.png)

`column Name` - It's return the name of column.
`values` - It's return the list of values.
`length` - It's return the length of given column.

## ⬇️ Get Cell
* **
Using this blocks you can get single cell from your sheet.

![image|262x85](upload://pXvE1nBi42mK9mi52evVVtnicIo.png)

`columnName` - Enter column name.
`row Number` - Enter row number.

![image|312x93](upload://vaAfBLyWvJW7ZT4y84jRUHhJTPH.png)

`column Name` - It's return given column name.
`row Number` - It's return given row number.
`value` - It's return cell value.

## 🔎 Search
* **
Using this blocks you can get single column by filtering.

![image|257x87](upload://aKZFeDOFYItelsQOrc4xfSSSDWs.png)

`column Name` - Enter Column name to search data.
`keyword` - Enter search text to filter data.

![image|441x94](upload://ytXuQSCTs31B8o9NlGPdDREc7kL.png)

`column Name` - It's return the given column name.
`keyword` - It's return the given keyword.
`values` - It's return the list of matching value.
`positions` - It's return the positions of filtered data.
`length` - It's return the length of filtered list.

## 🔎 Advance Search
* **
Using this blocks you can get filtered data by search from two columns.

![image|312x110](upload://aOSeLE3W8Q3Ltbs52G3eil8hHpi.png)

`byColumn` - Enter column name to search.
`keyword` - Enter search text.
`fromColumn` - Enter column name to fetch data.

![image|518x92](upload://7Xi060ic0bQV1m7kVM5zWwtbUJF.png)

`byColumn` - It's return byColumn name.
`keyword` - It's return search text.
`fromColumn` - It's return fromColumn name.
`values` - It's return the list of matching value.
`positions` - It's return the positions of filtered data.
`length` - It's return the length of filtered list.

## ⬇️ Get Row
* **
Using this blocks you can get values of any row.

![image|267x60](upload://ajNS60ymQLkAJ5fyMUGIcvsHZzM.png)

`row Number` - Enter row number to get values.

![image|329x96](upload://gRnJx8lENe6w7Iz53V2Il6O9yjG.png)

`row Number` - It's return the row number.
`values` - It's return the list of values.
`column Names` - It's return the list of column names.

## ⬇️ Get Sheet Names
* **
Using this blocks you can get list of your sheets.

![image|313x37](upload://ptorD0HY5E1EMwHoBr0KEb9HRhY.png)

![image|320x96](upload://sCDrk8IWpKYJpONLWNetA3BMHmn.png)

`sheetNames` - It's return the list of sheet names.
`gidIds` - It's return the list of gid ids.
`length` - It's return the length of sheet list.

## ⬇️ Get Column Names
* **
Using this blocks you can get names of all columns.

![image|324x39](upload://2cMWpbkma6rGRnsq5c7Jzuwzdxm.png)

![image|330x93](upload://gLmUQxWs05PzypTaqseotVE35Fy.png)

`column Names` - It's return the list of column names.
`length` - It's return the length of list.

## ⬇️ Get Spreadsheet Name
* **
Using this blocks you can get your spreadsheet project name.

![image|341x32](upload://9sMlOtbZMT780zUx91otWY4wmmn.png)

![image|355x95](upload://mSHStPYEt8bgsbRMdsDbpjJIrVc.png)

`spreadsheetName` - It's return the name of your spreadsheet project.

## ⬇️ Total Rows
* **
Using this block you can get total number of all rows.

<img src="upload://tb5qKdHZTSfrkaUgO3ju2mOMVa3.png">

## ➕ Create Column
* **
Using this blocks you can create new column in your sheet.

![image|295x57](upload://zMVjXCzoqqHVDUtR2w6H6HPQsgN.png)

`column Name` - Enter new name to create column.

![image|311x91](upload://MbkSjBn5zP8GsSlBgJ410NI4Oo.png)

`column Name` - It's return the new name.
`columnPosition` - It's return the position of new column.

## ➕ Create Row
* **
Using this blocks you can create single cell in you sheet.

![image|281x82](upload://m8ayKdW42qd9DZWPaO8CqpYfIsi.png)

`column Name` - Enter the column name where need to create row.
`value` - Enter cell value to create row.

![image|311x91](upload://lRrPVR4v3wsw0sjFGDwfRTrlcWR.png)

`row Number` - It's return the number of row.
`column Name` - It's return the name of column.
`value` - It's return the value.

## ➕ Create Rows
* **
Using this blocks you can create new row with multiple cells.

![image|288x61](upload://gbD70LGcFwQo4oflegDQH4iJ2Us.png)

`values` - Enter values as list to create new row.

![image|299x94](upload://vEO2mkd1mEFuzdMZOZYHALSvl7P.png)

`response` - It's return the response string.

## ➕ Create Sheet
* **
Using this blocks you can create new sheet in your spreadsheet project.

![image|290x61](upload://n6zXOX9ch1UA1WluxJSb0ukq651.png)

`sheetName` - Enter new sheet name.

![image|303x95](upload://dVQ5o3h6GTWVildAJPju3wkSsYN.png)

`sheetName` - It's return the name of sheet.

## ⤴️ Update Cell
* **
Using this blocks you can update any cell.

![image|278x108](upload://bPQbxZwuV29jofT3za8GdOI13Nj.png)

`column Name` - Enter column name.
`row Number` - Enter row number.
`value` - Enter new value.

![image|312x94](upload://2f5LbLMoXfohIYDG4lFrha1TmyH.png)

`column Name` - It's return the name of column.
`row Number` - It's return the row number.
`value` - It's return the value.

## ⤴️ Update Rows
* **
Using this blocks you can update any row values.

![image|292x111](upload://g8cVPmiSacBx4LKTaHlX22hqfi0.png)

`row Number` - Enter row number.
`column Names` - Enter column names as list..
`values` - Enter values as list.

![image|302x93](upload://ny8rDGH2EfSXYHXV2DeZhehwk1x.png)

`row Number` - It's return the number of row.

## ✂️ Delete Row
* **
Using this blocks you can delete any row by row number.

![image|279x58](upload://3gPX4VeGIGPjCA0ERnmuhrvz7vO.png)

`row Number` - Enter row number.

![image|291x93](upload://2WAS9ZejveuPt4VDuVwjOoML397.png)

`row Number` - It's return the number of row.

## ✂️ Delete Column
* **
Using this blocks you can delete any column from your sheet.

![image|301x63](upload://6SWaxp921uqVdCcL1FRndamjIon.png)

`column Name` - Enter column name to delete.

![image|312x91](upload://vpNdL8Tna4V8fMqV0o7f5MAQOyt.png)

`column Name` - It's return the name of column.
`position` - It's return the position of column.

## ✂️ Delete Sheet
* **
Using this blocks you can delete any sheet from your spreadsheet project.

![image|283x61](upload://ap7Ps9rECIYDJq9bebxENfhSzgX.png)

`sheetName` -  Enter sheet name to delete.

![image|297x96](upload://8sxNws9T4MYlCHlqvKKM6oztgkA.png)

`sheetName` - It's return the name of sheet.

## ✍️ Rename Sheet
* **
Using this blocks you can rename any sheet from your project.

![image|300x89](upload://8lqu6l1ILQw3WSCyPc3FV90TlQg.png)

`oldName` - Enter old name of sheet.
`new Name` - Enter new name to rename sheet.

![image|314x95](upload://ymSPBwXuxcXNif5UQuZvxNwPde8.png)

`new Name` - It's return the new name of sheet.
`oldName` - It's return the old name.

## ✍️ Rename Spreadsheet
* **
Using this blocks you can rename your project name.

![image|345x65](upload://zIxdcNKDBqUfBLqhcc09rc2f308.png)

`name` -  Enter new name to rename spreadsheet project name.

![image|360x98](upload://dwit7VTtWrA51Nm3xw9YWg4M50p.png)

`name` - It's return the new name of your project.

## 🔁 Replace All
* **
Using this function you can replace all matching text from active sheet with new value.

![image|275x89](upload://jysZQl6LAG7lCzqI0aaKpk0Z7fW.png)

`text` - Enter text to replace with new value.
`replaceWith` - Enter new value to replace with old value.

![image|299x96](upload://gnUioipu0l75E0ybo1KNotoE5AZ.png)

`text` - It's return the old value.
`replaceWith` - It's return the new value.

## 🔁 Replace By Column
Using this function you can replace all matching text from column with new value.

![image|329x113](upload://bc1qugrtknpjz52vc4m559q7zumkc4268kp7skrsee.png)

`columnName` - Enter column name where you want to replace values.
`text` - Enter text to replace with new value.
`replaceWith` - Enter new value to replace with old value.

![image|342x95](upload://bS5283dFAuyepaXjhKjZ9573Ts9.png)

`columnName` - It's return the column name.
`text` - It's return the old value.
`replaceWith` - It's return the new value.

## 🔁 Replace By Row
Using this function you can replace all matching text from row with new value.

![image|311x110](upload://5lKbcnV3k49u3XWqjB8e9KgygGK.png)

`rowNumber` - Enter row number where you want to replace values.
`text` - Enter text to replace with new value.
`replaceWith` - Enter new value to replace with old value.

![image|316x93](upload://krR5fxOwdZaiAXeaay9czDmGCKV.png)

`rowNumber` - It's return the row number.
`text` - It's return the old value.
`replaceWith` - It's return the new value.

## 🔁 Replace For All Sheets
Using this function you can replace all matching text from all sheets with new value.

![image|341x86](upload://a7Zp6ccQW6TdA3v1qCDOmNBlwP8.png)

`text` - Enter text to replace with new value.
`replaceWith` - Enter new value to replace with old value.

![image|358x95](upload://woynUYubFw1tbUXfLt8hXyDbr5a.png)

`text` - It's return the old value.
`replaceWith` - It's return the new value.

## 🔃 Refresh Data
* **
Using this blocks you can refresh data manually if you disabled Auto Refresh. Otherwise no need to refresh data manually.

![image|280x38](upload://gey2aJUlenukv9jn3T6O4VZLEfZ.png)

![image|557x93](upload://50J5lx7ncRBFy1igE8Z4vCXlZ9H.png)

`function Name` - It's return the function name which function refresh data automatically.
`totalRow` - It's return the total number of rows.
`totalColumn` - It's return the total number of columns.
`loadTime` - It's return the milliseconds of loading time.
`response Content` - It's return the Json string.

## ⚠ Failed
* **
It's rises when the extension got any error.

![image|268x94](upload://caGxGYTeiIjFydAg3Bzm0nEo3re.png)

`function Name` - It's return the function name which function got error.
`error Message` - It's return the error message as string.

## 🔐 Encode & Decode
* **
Using this blocks you can protect your sheet ids and sheet name etc. Set level (1-100) and password length must be 5 or more.

![image|263x109](upload://fAWAwOE20HXCsDn8eU8NxDfiENg.png)

![image|264x113](upload://fRtWDqPsN9NlqeszhCHCfB1IblL.png)
***


## 📝 Release Notes ↷
* **
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
* **

[![Spreadsheet](http://img.youtube.com/vi/mnqTLrMAXps/0.jpg)](https://www.youtube.com/watch?v=mnqTLrMAXps)

## Implementation Guide Video **↓**

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
