### Google Sheets Double Click to Fill

#

### Double Click to Fill

The fill function can be double clicked to complete formulas in a range:

![img_google_sheets_dc_fill_1](https://user-images.githubusercontent.com/47166768/191946948-d2d38758-35c2-4b45-bbb6-0d0f131e1924.png)


**Note:** For the double click to work it has to see a recognizable pattern.

For example: by using headers, or with the formulas in the columns or rows next to the data.




### Double Click to Fill Example

Let's use the Double click fill function to calculate the Attack `B2:B20` + Defense `C2:C20` for the Pokemons in the range `D2:D20`.

1. Select `D2`
2. Type `=`

![img_google_sheets_dc_fill_2](https://user-images.githubusercontent.com/47166768/191947117-87fb9fe0-3fed-4042-b942-29ae28cbe5d6.png)

3. Select `B2`
4. Type `+`
5. Select `C2`

![img_google_sheets_dc_fill_3](https://user-images.githubusercontent.com/47166768/191947486-afe4bf32-e099-4308-97ff-82bdd748b6ce.png)

6. Hit enter

![img_google_sheets_dc_fill_4](https://user-images.githubusercontent.com/47166768/191947513-cd183104-b14e-45eb-a97b-b7af9af4256b.png)

7. Double click the fill function highlighted by the black rectangle

![img_google_sheets_dc_fill_5](https://user-images.githubusercontent.com/47166768/191947575-cefe3f75-2713-4d0f-a6c6-6bb314417427.png)





**Way to go!** The function understands the pattern and completes the calculation for `D2:D20`. Note that it stops when there is no more data to calculate, at row **20**.

<pre>
<b>Note:</b> The Fill uses the data in nearby columns. If there is an empty column between the data and the destination range, the fill 
function might not work properly.
</pre>

