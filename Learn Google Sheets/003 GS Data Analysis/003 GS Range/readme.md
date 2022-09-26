Google Sheets Sort Range By Column
---



Sort Range By Column
---
Google sheet lets you sort data in a range by columns

It is possible to sort data in a sheet by range.

**Note:** To sort a range that has more than one column, the whole range of data has to be selected. Sorting just one can breaks the relationship between columns.

This is shown in an example later in this chapter.

The sort commands can be found in the **Data** menu.

![img_google_sheets_sort_1](https://user-images.githubusercontent.com/47166768/192151866-93c451d1-2ac5-49df-bcfa-82413df3dcd2.png)




Example (Sort Text)
---
Sort the Pokemon in the range `A2:A21` by their Name, ascending from smallest to largest (A-Z).

Copy the values to follow along.

![img_google_sheets_sort_by_range_1](https://user-images.githubusercontent.com/47166768/192152026-5867c43a-babf-4bde-9bd9-e870157cb471.png)

1. Select the range `A2:A21`


**Note:** A1 is not included as it is the header for the column. This is the row that is dedicated to the filter. Including it will blend it with the rest.

![img_google_sheets_sort_by_range_2](https://user-images.githubusercontent.com/47166768/192152100-7a528e2d-2bad-4dad-bb8c-7ebc199d2b8d.png)


2. Click on the **Data** menu and select **Sort range by column A, A → Z**

![img_google_sheets_sort_by_range_3](https://user-images.githubusercontent.com/47166768/192152129-ab3af1dc-b431-4ea6-b959-aba2b046aabc.png)


This is the result:

![img_google_sheets_sort_by_range_4](https://user-images.githubusercontent.com/47166768/192152136-2e82b836-ddc5-4bc7-9bff-1c8a8e0e0ad6.png)


Try again, this time with **Sort range by column A, Z → A** to see what that looks like!





Example (Sort Numbers)
---
Sort the Pokemon ascending by their **Total stats** from smallest to largest.

Copy the values to follow along.

![img_google_sheets_sort_by_range_5](https://user-images.githubusercontent.com/47166768/192152224-5e68d56c-816f-4989-9f34-3d1253e19c53.png)



1. Select the range `A2:A21`

![img_google_sheets_sort_by_range_6](https://user-images.githubusercontent.com/47166768/192152331-8e554698-f789-4080-af9d-b70e93f8aa33.png)


2. Click on the **Data** menu and select **Sort range by column A, A → Z**

![img_google_sheets_sort_by_range_7](https://user-images.githubusercontent.com/47166768/192152340-e21242c6-66f4-4ada-9c35-b2038e192e15.png)


This is the result:

![img_google_sheets_sort_by_range_8](https://user-images.githubusercontent.com/47166768/192152380-a9b7347b-f098-4ee8-8420-168bdb2cbd99.png)

**Great!** The Pokemon were successfully sorted by their **Total stats** from smallest to largest. The sort commands work for both text and numbers.

A Non-Working Example (Sorting One Column In A Range)
---
This example shows how sorting column by range can break the relationship between multiple data columns.

In this example we have two columns with related data. Column `A` is the Pokemon **Names** and Column `B` is their **Total stats**. Try sorting just one of the columns (`A2:A21`) ascending by their **Names**.

Copy the values to follow along.

![img_google_sheets_sort_by_range_9](https://user-images.githubusercontent.com/47166768/192152620-a6a16274-13d7-453a-b16a-e9a4b512cc6a.png)

1. Select the range `A2:A21`


2. Click on the **Data** menu and select **Sort range by column A, A → Z**

![img_google_sheets_sort_by_range_11](https://user-images.githubusercontent.com/47166768/192152688-a517d5f7-55a5-45b1-a08b-29ba925b4116.png)

This is the result:

![img_google_sheets_sort_by_range_12](https://user-images.githubusercontent.com/47166768/192152706-ab378a11-0ae7-4c78-90f0-9f5c37fc5e8f.png)

The image above shows that the relationship between column `A` and `B` is broken. The Pokemon now have wrong Total stats.







