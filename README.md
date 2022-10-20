WeHelp Boot Camp <Week 5>
-----------
<br/>
> WeHelp Boot Camp Week 4 Mission: MySQL
> 為求方便觀看，故將圖中的錯誤語法蓋住。
<br/>
##要求⼆：建立資料庫和資料表
<br/>
![Q2](https://user-images.githubusercontent.com/111497136/196937797-c19b51e1-3796-42c0-8f6b-04eea9ec0f2e.PNG)

##要求三：SQL CRUD
<br/>

1. 使⽤INSERT指令新增⼀筆資料到member資料表中，這筆資料的username和password欄位必須是test。接著繼續新增⾄少4筆隨意的資料。
2. 使⽤SELECT指令取得所有在member資料表中的會員資料。
3. <br/>
![Q3-1~3-2](https://user-images.githubusercontent.com/111497136/196937814-84fa99ae-fe11-4daa-9b78-fb71e40db842.png)

3. 使⽤SELECT指令取得所有在member資料表中的會員資料，並按照time欄位，由近到遠排序。
4. <br/>
![Q3-3](https://user-images.githubusercontent.com/111497136/196937839-70ae9a2f-0268-454c-a9de-a874e0b08dbf.png)

4. 使⽤SELECT指令取得member資料表中第2~4共三筆資料，並按照time欄位，由近到遠排序。
![Q3-4](https://user-images.githubusercontent.com/111497136/196937846-ea827b23-73f2-47aa-b160-eca39c569a07.PNG)

5. 使⽤SELECT指令取得欄位username是test的會員資料。
![Q3-5](https://user-images.githubusercontent.com/111497136/196937861-636dd7f5-6a1b-4531-ad4b-04799f70d77a.PNG)

6. 使⽤SELECT指令取得欄位username是test、且欄位password也是test的資料。
![Q3-6](https://user-images.githubusercontent.com/111497136/196937898-545f7fbb-8759-4dfe-bdc3-e7bfa10cdf69.PNG)

7. 使⽤UPDATE指令更新欄位username是test的會員資料，將資料中的name欄位改成test2。
![Q3-7](https://user-images.githubusercontent.com/111497136/196937909-8f65bf71-97e9-4717-9b51-0fbdac338e77.PNG)

##要求四：SQL Aggregate Functions
1. 取得member資料表中，總共有幾筆資料(幾位會員)。
2. 取得member資料表中，所有會員follower_count欄位的總和。
3. 取得member資料表中，所有會員follower_count欄位的平均數。
![Q4](https://user-images.githubusercontent.com/111497136/196937924-d569ae09-2681-4579-89a5-d9d81a28eeae.png)

##要求五：SQL JOIN (Optional)

1. 在資料庫中，建立新資料表紀錄留⾔資訊，取名字為message。
![Q5-1](https://user-images.githubusercontent.com/111497136/196938026-724e244c-73a8-4546-a26e-983a62e57f16.png)

2. 使⽤SELECT搭配JOIN語法，取得所有留⾔，結果須包含留⾔者會員的姓名。
![Q5-2](https://user-images.githubusercontent.com/111497136/196938036-ff7b18fc-1676-476f-8fb6-901fbaf6038d.PNG)
![Q5-2-2](https://user-images.githubusercontent.com/111497136/196938060-553824d2-4369-4d3a-a003-a2c663466686.PNG)

3. 使⽤SELECT搭配JOIN語法，取得member資料表中欄位username是test的所有留⾔，資料中須包含留⾔者會員的姓名。
![Q5-3](https://user-images.githubusercontent.com/111497136/196938081-7b557dca-a60e-462e-a025-7ffff383ac6b.PNG)

4. 使⽤SELECT、SQL Aggregate Functions搭配JOIN語法，取得member資料表中欄位username是test的所有留⾔平均按讚數。
![Q5-4](https://user-images.githubusercontent.com/111497136/196938091-4a909279-a2df-4c4a-be4d-c56b49206408.PNG)

##轉檔語法
![Q6](https://user-images.githubusercontent.com/111497136/196938103-3dc19034-e031-4710-8f70-430e1d40d325.PNG)



