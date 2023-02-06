# SpreadsheetPlus Extension
An awesome extension to read data from Spreadsheet by lightning speed ⚡

![Spreadsheet Plus](https://user-images.githubusercontent.com/75406851/216776569-d045850f-64f4-4aa2-9534-8ecebe614059.jpg)

Spreadsheet Plus, this is an extended version of <a href="https://github.com/jewelshkjony/SpreadSheets">Spreadsheet Extension</a>. Using this extension you can get all of sheets values in a single click. This is not matter how many sheets have in your Spreadsheet project. This extension can get all values in few seconds, then you can call data by using extension functions even no internet. This extension also provide you offline support. Watch tutorial 📹 videos for better understand it's uses.

## Extension Properties
Set your spreadsheet project id before using this extension. You can get `SheetId` from url. Watch tutorial 📹 videos for better understanding.

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/75406851/216776950-b80809d1-2513-4860-8bc7-9753fe42e23d.png"/></td>
    <td><img src="https://user-images.githubusercontent.com/75406851/216776967-7f04ec20-ae48-454c-945f-ce0ffb5e311c.png"/></td>
  </tr>
</table>

## ⬇️ Get All Sheets
⚠ This is mandatory to `GetAllSheets` before using any other functions.\
When `GotAllSheets` event will be triggered it's means the extension is ready to work.

![image](https://user-images.githubusercontent.com/75406851/216777432-3136b9ce-5393-4bfa-9df0-a61b1c82f343.png)

`sheetNames` it's return the list of sheet names.\
`gidIds` it's return the list of gid ids.\
`length` it's return the size of sheet names list.\
`loadTime` it's return the data loading ⌚ time in milliseconds.

## ⬇️ Total Rows
Use this function to know how many rows has in a sheet.

![image](https://user-images.githubusercontent.com/75406851/216777727-e7f19e6d-df52-4e59-9a4e-be0384b54a06.png)

Enter `SheetName` to get the total rows number.

## ⬇️ Get Column
Using this function you can get column values from any specific sheet.

![image](https://user-images.githubusercontent.com/75406851/216778177-f6533abd-0316-49af-9138-03860f4f4eab.png)

`sheetName` Enter the name of sheet from where you want to get data.\
`columnName`  Enter the name of column to get values.\
`max` Enter `0` to get all vaules from column. If you want limited values, so enter limit as integer number.

![image](https://user-images.githubusercontent.com/75406851/216778386-d357cb4c-f51b-486b-876e-dca3c08026e2.png)

`sheetName` it's return the given name of sheet.\
`columnName` it's return the given name of column.\
`values` it's return the values as list from given column.\
`length` it's return the values size as integer.

## ⬇️ Get Cell
Using this function you can get cell value from any specific sheet.

![image](https://user-images.githubusercontent.com/75406851/216778616-2944b435-1680-458d-993c-3eee9806e989.png)

`sheetName` Enter the name of sheet from where you want to get data.\
`columnName`  Enter the name of column to get value.\
`rowNumber` Enter the row number to get value.

![image](https://user-images.githubusercontent.com/75406851/216778686-29e46966-15ad-4169-a172-012917605c43.png)

`sheetName` it's return the given name of sheet.\
`columnName` it's return the given name of column.\
`rowNumber` it's return the given row number.\
`value` it's return the value of cell.

## ⬇️ Get Row
Using this function you can get row values from any specific sheet.

![image](https://user-images.githubusercontent.com/75406851/216778769-b8ea2d2d-8e4f-4216-9a61-f716f4e8c99e.png)

`sheetName` Enter the name of sheet from where you want to get data.\
`rowNumber` Enter the row number to get values.

![image](https://user-images.githubusercontent.com/75406851/216778824-ca84589a-2260-4376-842d-620f30ef77b4.png)

`sheetName` it's return the given name of sheet.\
`rowNumber` it's return the given row number.\
`values` it's return the values from row.\
`columnNames` it's return the column names for row values.

## 🔎 Search
Using this function you can get filtered column values from any specific sheet.

![image](https://user-images.githubusercontent.com/75406851/216778947-b79939a7-e5ce-4680-aa09-0ff13331adce.png)

`sheetName` Enter the name of sheet from where you want to get data.\
`columnName`  Enter the name of column to get values.\
`keyword` Enter keyword to 🔎 search in given column.

![image](https://user-images.githubusercontent.com/75406851/216779059-1a11c20a-1fe1-4c05-ba73-194541d0ce1a.png)

`sheetName` it's return the given name of sheet.\
`columnName` it's return the given name of column.\
`keyword` it's return the given keyword.\
`values` it's return the filtered values as list.\
`positions` it's the original positions of filtered values.\
`length` it's return the size of values as integer.

## 🔎 Advance Search
Using this function you can get filtered values from one specific column by other column. Watch tutorial 📹 videos for better understanding.

![image](https://user-images.githubusercontent.com/75406851/216779233-8932a635-cc27-4986-a839-01b76d0ddfd4.png)

`sheetName` Enter the name of sheet from where you want to get data.\
`byColumn` Enter that column name where you want to make 🔎 search.\
`keyword` Enter keyword to 🔎 search in given column.\
`fromColumn` Enter that column name from where you want to pick values during search.

![image](https://user-images.githubusercontent.com/75406851/216779431-e19269c2-91f8-42d9-bbe5-d01acfbc5d46.png)

`sheetName` it's return the given name of sheet.\
`byColumn` it's return that given by column name.\
`keyword` it's return the given keyword.\
`fromColumn` it's return that given from column name.\
`values` it's return the filtered values as list.\
`positions` it's the original positions of filtered values.\
`length` it's return the size of values as integer.

## ⬇️ Get Column Names
Using this function you can get all column names from any specific sheet.

![image](https://user-images.githubusercontent.com/75406851/216779573-fe850f4b-e08e-4227-986f-5cdf9e1654ee.png)

`sheetName` Enter the name of sheet from where you want to get data.

![image](https://user-images.githubusercontent.com/75406851/216779622-59e1d3c1-dbab-438f-b1ca-bdc3650b6805.png)

`sheetName` it's return the given name of sheet.\
`columnNames` it's return the column names as list.\
`length` it's return the size of column names as integer.

## ⚠️ Failed

It’s rises when the extension got any error.\
Use function name variable to handle user activities.\
And read error message for understanding the error reason.

![image](https://user-images.githubusercontent.com/75406851/216978425-786f5732-1594-4f92-bdf9-c9f1c290aa90.png)

`functionName` it’s return the name of function where got error.\
`errorMessage` it’s return the error message as string.

## 📹 Tutorial Videos ↓

[![SpreadsheetPlus](http://img.youtube.com/vi/46Fe2-Z6TzM/0.jpg)](http://www.youtube.com/watch?v=46Fe2-Z6TzM)

## More extensions

<a href="https://github.com/jewelshkjony?tab=repositories">See more extensions</a>

## Extension specifications:
<img src="https://github.com/jewelshkjony/SpreadSheets/raw/main/images/download.png"/> <a href="https://t.me/jewelshkjony">com.jewel.spreadsheetplus.aix</a> (51.4 KB) \
<b>Version:</b> 1.0.0\
<b>Price:</b> $15 USD <sub>(Fast Edition) - [Available to receive minor updates only.]</sub> \
<b>Price:</b> $25 USD <sub>(Lighting Edition) - [Feel the⚡lightning speed when data is loading. Available to receive minor and major updates.]</sub> \
<b>Price:</b> $35 USD <sub>(Custom Edition) - [More 🔐 secure and you can order me to customize the extension for your need.]</sub> \
<b>Last amendment:</b> 04 February 2023\
<b>Supported builder:</b> <a href="https://www.kodular.io/">Kodular</a>, <a href="https://niotron.com/">Niotron</a>, <a href="https://appzard.com/">AppZard</a>, <a href="https://androidbuilder.in/">AndroidBuilder</a>, <a href="http://ai2.appinventor.mit.edu/">App Inventor</a> and it's other distributions.

## 📫 How to reach me -

<a href="https://t.me/jewelshkjony">Telegram</a> | <a href="https://wa.me/8801775668913">WhatsApp</a> | <a href="https://fb.com/jewelshkjony">Facebook</a> | <a href="https://m.me/jewelshkjony">Messenger</a> | <a href="https://m.youtube.com/c/JewelShikderJony">Youtube</a>

## 💲 Payment Methods ↓

❏ <a href="https://www.xoom.com/bangladesh/send-money" target="_blank">Xoom</a> | <a href="https://wise.com/?sourceCurrency=USD&targetCurrency=BDT&sourceAmount=20" target="_blank">Wise</a> | <a href="https://www.skrill.com/en/">Skrill</a> | <a href="https://www.binance.me/en/activity/referral-entry/CPA?fromActivityPage=true&ref=CPA_0068YL77KV" target="_blank">Binance</a> | <a href="https://play.google.com/store/apps/details?id=com.jewelshkjony.pay2me">Pay2Me</a> | <a href="https://www.paypal.com/">Paypal</a>  (Global)

❏ <a href="https://bka.sh/next?c=signup&uuid=C1CC9JVT1" target="_blank">bkash</a> | <a href="https://play.google.com/store/apps/details?id=com.konasl.nagad">Nagad</a> | <a href="https://play.google.com/store/apps/details?id=com.dbbl.mbs.apps.main">Rocket</a> (Bangladesh)
