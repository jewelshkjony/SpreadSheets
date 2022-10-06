# SpreadSheets Extension
An awesome extension to work with google spreadsheet. You can read, write and modify data from your sheets.

<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/Google%20Spreadsheet%20Logo.png"/>

Google Spreadsheets Extension - Free & Fastest Database - Scriptless extension. It's 5x Faster Than Airtable. It also give you offline support once data is loaded. It's very secure to protect your data from hackers. It can load huge amount of data. It's very simple and easy to integrate this extension into your application.

## Extension Properties

<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/aix.png"/>

<table>
  <tr>
    <td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/property-1.png"/></td>
    <td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/property-2.png"/></td>
  </tr>
</table>

<details>
  <summary>Total Functions & Events</summary>
  
Totally 30 functions and 22 events are available now.

<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/all-methods.png"/>

<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/all-events.png"/>
</details>

<details>
  <summary>Requirements</summary>
  
  <img src="https://user-images.githubusercontent.com/75406851/187043159-c690c634-aabb-47c5-a41d-5f48837bf3d2.png"/>
  <img src="https://user-images.githubusercontent.com/75406851/187043176-61695d3f-844f-421e-aa3f-ebd035421a2c.png"/>
  <img src="https://user-images.githubusercontent.com/75406851/187043193-62cf7ff2-5ef0-4063-a10a-aac6c77d04a5.png"/>

</details>
  
## Get All Rows
Using this blocks you can get all rows from your sheet. This method is mandatory before using any other blocks. You can use it in your splash screen then enjoy it's features. No more need to use it again.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/get-all-rows.png"/></td>
<td>
<b>totalRow</b> - It's return the total number of rows.

<b>totalColumn</b> - It's return the total number of columns.

<b>loadTime</b> - It's return the milliseconds of loading time.

<b>responseContent</b> - It's return the json string.

<b>contentSize</b> - It's return the size of your data.
</td>
</tr>
</table>

## Get Cell
Using this blocks you can get single cell from your sheet.

<table>
<tr>
<td><img src="https://user-images.githubusercontent.com/75406851/187042618-4fd9db30-5bd1-4bd7-aec4-01e5ca647c3a.png"/></td>
<td>
<b>column</b> - It's return the name of column.
  
<b>row</b> - It's return the number of row.
  
<b>value</b> - It's return the value of given cell.
</td>
</tr>
</table>

## Get Column
Using this blocks you can get any column from your sheet. Set 0 on max to get all values from column.

<table>
<tr>
<td><img src="https://user-images.githubusercontent.com/75406851/187042677-9076f3e2-f946-4d0d-ab1c-d0af2820475c.png"/></td>
<td>
<b>column</b> - It's return the name of column.
  
<b>values</b> - It's return the list of values.
  
<b>length</b> - It's return the length of given column.
</td>
</tr>
</table>

## Searching List
Using this blocks you can get single column by filtering.

<table>
<tr>
<td><img src="https://user-images.githubusercontent.com/75406851/187042704-903f0c71-cf49-45ae-a57d-d0e57c68c0f2.png"/></td>
<td>
<b>column</b> - It's return the name of column.
  
<b>search</b> - It's return the search text.
  
<b>values</b> - It's return the list of matching value.
  
<b>length</b> - It's return the length of filtered list.

</td>
</tr>
</table>

## Get Row
Using this blocks you can get values of any row.

<table>
<tr>
<td><img src="https://user-images.githubusercontent.com/75406851/187042729-277858fd-1c4b-4f00-a652-86d09a1ffc21.png"/></td>
<td>
<b>row</b> - It's return the number of row.
  
<b>values</b> - It's return the list of values.
  
<b>columns</b> - It's return the list of columns.
</td>
</tr>
</table>

## Get Sheet Names
Using this blocks you can get list of your sheets.

<table>
<tr>
<td><img src="https://user-images.githubusercontent.com/75406851/187042754-e48e1c87-9109-4059-9ec8-9bf5798ba757.png"/></td>
<td>
<b>sheetNames</b> - It's return the list of sheet names.
  
<b>gridIds</b> - It's return the list of gid ids.
  
<b>length</b> - It's return the length of sheet list.
</td>
</tr>
</table>

## Get Column Names
Using this blocks you can get names of all columns.

<table>
<tr>
<td><img src="https://user-images.githubusercontent.com/75406851/187042777-f259750d-e669-4245-a0ee-81370b8c35d3.png"/></td>
<td>
<b>columns</b> - It's return the list of names.
  
<b>length</b> - It's return the length of list.
</td>
</tr>
</table>

## Get Spreadsheet Name
Using this blocks you can get your spreadsheet project name.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/get-spreadsheet-name.png"/></td>
<td>
<b>name</b> - It's return the name of your spreadsheet project.
</td>
</tr>
</table>

## Total Rows
Using this block you can get total number of all rows.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/total-rows.png"/></td>
<td>
  <b>It's return the total number of loaded row.</b>
</td>
</tr>
</table>

## Create Column
Using this blocks you can create new column in your sheet.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/create-cloumn.png"/></td>
<td>
<b>columnName</b> - It's return the name of column.
  
<b>columnPosition</b> - It's return the position of new column.
</td>
</tr>
</table>

## Create Row
Using this blocks you can create single cell in you sheet.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/create-row.png"/></td>
<td>
<b>row</b> - It's return the number of row.
  
<b>column</b> - It's return the name of column.
  
<b>value</b> - It's return the value.
</td>
</tr>
</table>

## Create Rows
Using this blocks you can create new row with multiple cells.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/create-rows.png"/></td>
<td>
<b>response</b> - It's return the response string.
</td>
</tr>
</table>

## Update Cell
Using this blocks you can update any cell.
  
<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/update-cell.png"/></td>
<td>
<b>column</b> - It's return the name of column.
  
<b>row</b> - It's return the row number.
  
<b>value</b> - It's return the value.
</td>
</tr>
</table>

## Update Rows
Using this blocks you can update any row values.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/update-rows.png"/></td>
<td>
<b>row</b> - It's return the number of row.
</td>
</tr>
</table>

## Delete Row
Using this blocks you can delete any row by row number.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/delete-row.png"/></td>
<td>
<b>row</b> - It's return the number of row.
</td>
</tr>
</table>

## Delete Column
Using this blocks you can delete any column from your sheet.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/delete-column.png"/></td>
<td>
<b>column</b> - It's return the name of column.
  
<b>position</b> - It's return the position of column.
</td>
</tr>
</table>

## Create Sheet
Using this blocks you can create new sheet in your spreadsheet project.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/create-sheet.png"/></td>
<td>
<b>sheetName</b> - It's return the name of sheet.
</td>
</tr>
</table>

## Delete Sheet
Using this blocks you can delete any sheet from your spreadsheet project.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/delete-sheet.png"/></td>
<td>
<b>sheetName</b> - It's return the name of sheet.
</td>
</tr>
</table>

## Rename Sheet
Using this blocks you can rename any sheet from your project.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/rename-sheet.png"/></td>
<td>
<b>newName</b> - It's return the new name of sheet.
</td>
</tr>
</table>

## Rename Spreadsheet
Using this blocks you can rename your project name.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/rename-spreadsheet.png"/></td>
<td>
<b>name</b> - It's return the new name of your project.
</td>
</tr>
</table>

## Refresh Data
Using this blocks you can refresh data manually if you disabled Auto Refresh. Otherwise no need to refresh data manually.

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/refresh-data.png"/></td>
<td>
<b>functionName</b> - It's return the function name, which is performed before data refreshed.
  
<b>totalRow</b> - It's return the total number of rows.
  
<b>totalColumn</b> - It's return the total number of columns.
  
<b>loadTime</b> - It's return the milliseconds of loading time.
  
<b>responseContent</b> - It's return the json string.
  
<b>contentSize</b> - It's return the size of your data.
</td>
</tr>
</table>

## Failed
It's rises when this extension got or faced any error!

<table>
<tr>
<td><img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/failed.png"/></td>
<td>
<b>functionName</b> - It's return the function name which function got or faced error.
  
<b>error</b> - It's return the error string.
</td>
</tr>
</table>

## Encode Decode
Using this blocks you can protect your sheet ids and sheet name etc. Set level (1-100) and password length must be 5 or more.

<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/encode-decode.png" />

## More extensions

<a href="https://github.com/jewelshkjony?tab=repositories">See more extensions</a>

## Extension specifications:
<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/download.png"/> <a href="https://t.me/jewelshkjony">com.jewel.spreadsheets.aix</a> (106 KB) \
<b>Version:</b> 9.1.0\
<b>Price:</b> $5 USD <sub>(Standard Edition) - [Speed, validity and some functions are limited. Also you'll not get any future updates for free.]</sub> \
<b>Price:</b> $10 USD <sub>(Premium Edition) - [Speed and validity is encreased. Unlocked all of functions but plan upgrade limitation remain. Recommend for mid budget users.]</sub> \
<b>Price:</b> $15 USD <sub>(Platinum Edition) - [Speed and validity is more extended. Remain upgrade limitation. Recommend for all.]</sub> \
<b>Price:</b> $20 USD <sub>(Flash Edition) - [More validity and no speed limitations & updates are totally free! Tested with 1M rows! Recommend for higher end budget only.]</sub> \
<b>Price:</b> $25 USD <sub>(Speedster Edition) - [Everything is unlocked and premium. No limitations & lifetime support! Tested with 2M rows! Recommend for higher end budget only.]</sub> \
<b>Last amendment:</b> 05 October 2022\
<b>Supported builder:</b> <a href="https://www.kodular.io/">Kodular</a>, <a href="https://niotron.com/">Niotron</a>, <a href="https://appzard.com/">AppZard</a>, <a href="https://androidbuilder.in/">AndroidBuilder</a>, <a href="http://ai2.appinventor.mit.edu/">App Inventor</a> and it's other distributions.

## 📫 How to reach me -

<a href="https://t.me/jewelshkjony">Telegram</a> | <a href="https://wa.me/8801775668913">WhatsApp</a> | <a href="https://fb.com/jewelshkjony">Facebook</a> | <a href="https://m.me/jewelshkjony">Messenger</a> | <a href="https://m.youtube.com/c/JewelShikderJony">Youtube</a>

## 💲 Payment Methods ↓

❏ <a href="https://www.xoom.com/bangladesh/send-money" target="_blank">Xoom</a> | <a href="https://wise.com/?sourceCurrency=USD&targetCurrency=BDT&sourceAmount=20" target="_blank">Wise</a> | <a href="https://www.skrill.com/en/">Skrill</a> | <a href="https://www.binance.me/en/activity/referral-entry/CPA?fromActivityPage=true&ref=CPA_0068YL77KV" target="_blank">Binance</a> | <a href="https://play.google.com/store/apps/details?id=com.jewelshkjony.pay2me">Pay2Me</a> (Global)

❏ <a href="https://bka.sh/next?c=signup&uuid=C1CC9JVT1" target="_blank">bkash</a> | <a href="https://play.google.com/store/apps/details?id=com.konasl.nagad">Nagad</a> | <a href="https://play.google.com/store/apps/details?id=com.dbbl.mbs.apps.main">Rocket</a> (Bangladesh)
