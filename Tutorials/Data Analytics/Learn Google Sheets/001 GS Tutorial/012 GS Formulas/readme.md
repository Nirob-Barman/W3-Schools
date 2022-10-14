Google Sheets Formulas
---

Formulas
---
A formula in Google Sheets is used to do mathematical calculations. Formulas always start with the equal sign (=) typed in the cell, followed by your calculation.

Formulas can be used for calculations such as:

1. `=1+1`
2. `=2*2`
3. `=4/2=2`

formulas can take cells as input.

Let's have a look at an example.

Type or copy the following values:

![img_google_sheets_formulas_1](https://user-images.githubusercontent.com/47166768/191952822-d26c6062-36a9-4af0-9834-78b4f7632109.png)



Now we want to do a calculation with those values.

Step by step:

1. Select `C1` and type (`=`)
2. Select `A1`
3. Type (`+`)
4. Select `A2`
5. Press enter

![img_google_sheets_formulas_2](https://user-images.githubusercontent.com/47166768/191952952-6dcd2bec-14e1-4493-b2a9-3b2487a1396a.png)


![img_google_sheets_formulas_3](https://user-images.githubusercontent.com/47166768/191952964-1b0a42c8-4f60-4670-877b-cdddd26d7808.png)

**You got it!** You have successfully calculated `A1(2) + A2(4) = C1(6)`.

**Note:** Using cells to make calculations is an important part of Google Sheets and you will use this a lot as you learn.


Lets change from addition to multiplication, by replacing the (`+`) with a (`*`). It should now be `=A1*A2`, press enter to see what happens.

![img_google_sheets_formulas_4](https://user-images.githubusercontent.com/47166768/191953331-b8464eb3-45fa-421c-ab55-58d3cf4c4e60.png)

You got `C1(8)`, right? **Well done!**

![img_google_sheets_formulas_5](https://user-images.githubusercontent.com/47166768/191953401-d74b8759-4768-49ae-853e-a4cefad47d90.png)


Google Sheets is great in this way. It allows you to add values to cells and do calculations on them.

Now, try to change the multiplication (`*`) to subtraction (`-`) and dividing (`/`).

Delete all values in the sheet after you have tried the different combinations.

Let's add new data for the next example, where we will help the Pokemon trainers to count their Pokeballs.

Type or copy the following values:

![img_google_sheets_formulas_6](https://user-images.githubusercontent.com/47166768/191953513-4a7ebfdf-0954-4e04-927c-e3ac4fbcbc92.png)



The data explained:

- Column `A`: Pokemon Trainers
- Row `1`: Types of Pokeballs
- Range `B2:D4`: Amount of Pokeballs, Great balls and Ultra balls


**Note:** It is important to practice reading data to understand its context. In this example you should focus on the trainers and their Pokeballs, which have three different types: Pokeball, Great ball and Ultra ball.

Let's help Iva to count her Pokeballs. You find Iva in `A2(Iva)`. The values in `row 2 B2(2), C2(3), D2(1)` belong to her.

Count the Pokeballs, step by step:

1. Select cell `E2` and type (`=`)
2. Select `B2`
3. Type (`+`)
4. Select `C2`
5. Type (`+`)
6. Select `D2`
7. Hit enter


![img_google_sheets_formulas_7](https://user-images.githubusercontent.com/47166768/191953975-08bbf037-34e3-413f-a3f9-e5a1a239bce8.png)

![img_google_sheets_formulas_8](https://user-images.githubusercontent.com/47166768/191954009-94f75c8b-a360-45bf-9fb5-bdc4cb19022e.png)


Did you get the value `E2(6)`? **Good job!** You have helped Iva to count her Pokeballs.

Now, let's help Liam and Adora with counting theirs.

Do you remember the fill function that we learned about earlier? It can be used to continue calculations sidewards, downwards and upwards. Let's try it!

Lets use the fill function to continue the formula, step by step:

1. Select E2
2. Fill E2:E4


![img_google_sheets_formulas_9](https://user-images.githubusercontent.com/47166768/191954401-a9738943-b2ff-4fe7-abec-2b61de0bad21.png)


**That is cool, right?** The fill function continued the calculation that you used for Iva and was able to understand that you wanted to count the cells in the next rows as well.

Now we have counted the Pokeballs for all the trainers; Iva(`6`), Liam(`12`) and Adora(`15`).

Let's see how many Pokeballs Iva, Liam and Adora have in total.

The total is called **SUM** in Google Sheets.

There are two ways to calculate the **SUM**.

- Adding cells
- SUM function

Google Sheets has many pre-made functions available for you to use. The SUM function is one of the most used ones. You will learn more about functions in a later chapter.

Let's try both approaches.



**Note:** You can navigate to the cells with your keyboard arrows instead of right clicking them. Try it!

Sum by adding cells, step by step:

1. Select cell E5, and type `=`
2. Select `E2`
3. Type (`+`)
4. Select `E3`
5. Type (`+`)
6. Select `E4`
7. Hit enter

![img_google_sheets_formulas_10](https://user-images.githubusercontent.com/47166768/191955077-dfbdac4b-cfd1-4d5c-9e43-df67d92a3eac.png)


![img_google_sheets_formulas_11](https://user-images.githubusercontent.com/47166768/191955087-c04d8544-69de-43ec-a29b-bb91b4f9c935.png)


The result is `E5(33)`.

Let's try the **SUM** function.

Remember to delete the values that you currently have in E5.

**SUM** function, step by step:

1. Type `E5(=)`
2. Write **SUM**
3. Double click **SUM** in the menu
4. Mark the range `E2:E4`
5. Hit enter

![img_google_sheets_formulas_12](https://user-images.githubusercontent.com/47166768/191955497-133cc00d-39e6-4d73-b554-67da5def872e.png)


![img_google_sheets_formulas_13](https://user-images.githubusercontent.com/47166768/191955532-32880429-d516-4dfc-b742-b0aa678e865e.png)


![img_google_sheets_formulas_14](https://user-images.githubusercontent.com/47166768/191955952-be993f67-2692-43ff-9169-848446909b93.png)



**Great job!** You have successfully calculated the **SUM** using the **SUM** function.

Iva, Liam and Adora have `33` Pokeballs in total.

Let's change a value to see what happens. Type `B2(7)`:

![img_google_sheets_formulas_15](https://user-images.githubusercontent.com/47166768/191956063-9fbe0ac7-fbfc-4c73-bcd9-4b9752f97fd0.png)

The value in cell `B2` was changed from `2` to `7`. Notice that the formulas are doing calculations when we change the value in the cells, and the **SUM** is updated from `33` to `38`. It allows us to change values that are used by the formulas, and the calculations remain.



Chapter Summary
---
Values used in formulas can be typed directly and by using cells. The formula updates the result if you change the value of cells, which is used in the formula. The fill function can be used to continue your formulas upwards, downwards and sidewards. Google Sheets has pre-built functions, such as **SUM**.

In the next chapter you will learn about relative and absolute references.

