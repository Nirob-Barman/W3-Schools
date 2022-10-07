Google Sheets AND Function
---

AND Function
---
The **AND** function is a premade function in Google Sheets, which returns **TRUE** or **FALSE** based on two or more conditions.

It is typed `=AND` and takes two or more conditions.

<pre>
    =AND(<b>[logical_expression1], [logical_expression2, ...]</b>)
</pre>


The conditions are referred to as `[logical_expression1]`, `[logical_expression2]`, and so on.

The conditions can check things like:

If a number is **greater than** another number `>`
If a number is **smaller than** another number `<`
If a number or text is **equal** to something `=`


<pre>
<b>Note</b>: The AND function is often used together with the IF function.
</pre>



Example AND Function
---
Check if the Pokemon type is fire **and** has speed **greater than** 70:

The function returns "TRUE" or "FALSE".

![img_google_sheets_and](https://user-images.githubusercontent.com/47166768/194596672-ea4bdaa2-8d7d-4076-99c6-c8176f0694af.png)


Example **AND** function, step by step:

1. Select the cell `D2`
2. Type `=AND`
3. Click the **AND** command


![img_google_sheets_and2](https://user-images.githubusercontent.com/47166768/194596897-2053d26f-1e30-4af3-ac9d-444d9d40f8d1.png)

4. Specify the first condition `B2="Fire"`
5. Type `,`
6. Specify the second condition `C2>70`
7. Hit enter








