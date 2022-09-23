Google Sheets Fills
---

Filling
---
Filling makes your life easier and is used to fill ranges with values, so that you do not have to manually type the entries.

Filling can be used for:


- Copying
- Sequences
- Dates
- Functions


**Note:** For now, do not think of functions. We will cover that in a later chapter.


How To Fill
---
Filling is done by selecting a cell, clicking the fill icon and selecting the range using drag and mark while holding the left mouse button down.

The fill icon is found in the button right corner of the cell and has the icon of a small square. Once you hover over it your mouse pointer will change its icon to a thin cross.

![img_google_sheets_fill_1](https://user-images.githubusercontent.com/47166768/191942506-5cbe3a9c-8a46-4e73-8662-10aadf319647.png)

Click the fill icon and hold down the left mouse button, drag and mark the range that you want to cover.

In this example, cell `A1` was selected and the range `A1:A10` was marked.

![img_google_sheets_fill_2](https://user-images.githubusercontent.com/47166768/191942792-59847ac3-b837-413f-a8e6-a8f299dbfd54.png)

Now that we have learned how to fill. Let's look into how to copy with the fill function.



Fill Copies
---
Filling can be used for copying. It can be used for both numbers and words.

Let's have a look at numbers first.

In this example we have typed the value `A1(1)`:

![img_google_sheets_fill_3](https://user-images.githubusercontent.com/47166768/191942890-fcab12aa-935b-44b0-9631-e240b68333fd.png)

Filling the range `A1:A10` creates ten copies of 1:

he same principle goes for text.

In this example we have typed `A1(Hello World)`.

Filling the range `A1:A10` creates ten copies of "Hello World":


![img_google_sheets_fill_5](https://user-images.githubusercontent.com/47166768/191943042-7abd94ce-a14f-4ec8-95d4-eced213e616f.png)

Now you have learned how to fill and to use it for copying both numbers and words. Let's have a look at sequences.



Fill Sequences
---
Filling can be used to create sequences. A sequence is an order or a pattern. We can use the filling function to continue the order that has been set.

Sequences can for example be used on numbers and dates.

Let's start with learning how to count from 1 to 10.

This is different from the last example because this time we do not want to copy, but to count from 1 to 10.

Start with typing `A1(1)`:



![img_google_sheets_fill_6](https://user-images.githubusercontent.com/47166768/191943451-00de4051-3f1a-48a8-94a5-e3945a5e19ef.png)




First we will show an example which does not work, then we will do a working one. Ready?

Lets type the value (`1`) into the cell `A2`, which is what we have in `A1`. Now we have the same values in both `A1` and `A2`.


![img_google_sheets_fill_7](https://user-images.githubusercontent.com/47166768/191943663-bd9521e2-e7d5-452e-9763-ef70b00911e1.png)





Let's use the fill function from `A1:A10` to see what happens. Remember to mark both values before you fill the range.

![img_google_sheets_fill_4](https://user-images.githubusercontent.com/47166768/191943826-25dd9323-442e-4eae-b7b9-795a213c2e56.png)





What happened is that we got the same values as we did with copying. This is because the fill function assumes that we want to create copies as we had two of the same values in both the cells `A1(1)` and `A2(1)`.

Change the value of `A2(1)` to `A2(2)`. We now have two different values in the cells `A1(1)` and `A2(2)`. Now, fill `A1:A10` again. Remember to mark both the values (holding down shift) before you fill the range:

![img_google_sheets_fill_8](https://user-images.githubusercontent.com/47166768/191944014-5735bcb6-02fa-44a0-b9ee-5e54f327eedf.png)




**Congratulations!** You have now counted from 1 to 10.

The fill function understands the pattern typed in the cells and continues it for us.

That is why it created copies when we had entered the value (`1`) in both cells, as it saw no pattern. When we entered (`1`) and (`2`) in the cells it was able to understand the pattern and that the next cell `A3` should be (`3`).

Let's create another sequence. Type `A1(2)` and `A2(4)`:

![img_google_sheets_fill_9](https://user-images.githubusercontent.com/47166768/191944237-3e926dbd-d655-4b9f-a6a6-6d55b5b58c18.png)



Now, fill `A1:A10`:


![img_google_sheets_fill_10](https://user-images.githubusercontent.com/47166768/191944291-0d2fbe59-8107-4f3b-b87b-caec67f05a2b.png)




It counts from `2 to 20` in the range `A1:A10`.

This is because we created an order with `A1(2)` and `A2(4)`.

Then it fills the next cells, `A3(6), A4(8), A5(10)` and so on. The fill function understands the pattern and helps us continue it.








Sequence of Dates
---
The fill function can also be used to fill dates.

Test it by typing `A1(29.07.2021)`:

![img_google_sheets_fill_11](https://user-images.githubusercontent.com/47166768/191945412-5fbe8f99-33a2-41a4-bcaa-00bf519ca1a2.png)





And fill the range A1:A10:

![img_google_sheets_fill_12](https://user-images.githubusercontent.com/47166768/191945435-ab3d19a8-cff6-4aa6-bd94-0f2bc9f8856d.png)






The fill function has filled 10 days from `A1(29.07.2021)` to `A10(07.08.2021)`.

Note that it switched from July to August in cell `A4`. It knows the calendar and will count real dates.

Note: The recognized formats for dates, currencies and functions depends on your Google Sheets location settings.






Combining Words and Letters
---
Words and letters can also be combined.

Type `A1(Hello 1)` and `A2(Hello 2)`:



Next, fill A1:A10 to see what happens:

![img_google_sheets_fill_14](https://user-images.githubusercontent.com/47166768/191946338-dc80e432-e847-4135-b323-220084ec1f2d.png)





The result is that it counts from `A1(Hello 1)` to `A10(Hello 10)`. Only the numbers have changed.

It recognised the pattern of the numbers and continued it for us. Words and numbers can be combined, as long as you use a recognizable pattern for the numbers.

















