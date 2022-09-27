Google Sheets Sort Range
---
Sort Range
---
The **Sort Range** command in Google Sheets allows for more complex sorting of data.

For example it can work with data which has headers or have multiple sort rules.

Handling Data with Headers
---
Sort range makes it very easy to sort data with headers.

Example
Sort the Pokemon in the range `A2:A21` by their **Total stats**, ascending from smallest to largest (A-Z).

Copy the values to follow along.

![img_google_sheets_sort_by_range_9](https://user-images.githubusercontent.com/47166768/192560146-f7322182-3434-4498-9213-554ca9098a50.png)

Sort range, step by step:

1. Select all the data, range `A2:B21`

![img_google_sheets_sort_range_1](https://user-images.githubusercontent.com/47166768/192560468-36cf1f02-1e29-4f12-a450-cef45c91ede8.png)

2. Click on the **Data** menu and find **Sort range**

![img_google_sheets_sort_range_2](https://user-images.githubusercontent.com/47166768/192560792-97a8bde5-5691-4c5a-9b55-39a124379ce5.png)

3. Click on **Sort range**

![img_google_sheets_sort_range_3](https://user-images.githubusercontent.com/47166768/192561113-c10e1332-c7a6-4921-8527-675b0c556086.png)

4. Select **Data has header row**

![img_google_sheets_sort_range_4](https://user-images.githubusercontent.com/47166768/192561213-9f982cee-aa18-4803-988b-9a1596f12d58.png)

5. Select **Total stats** which is the header for column `B`

![img_google_sheets_sort_range_5](https://user-images.githubusercontent.com/47166768/192561394-db2d7c48-c74f-4c98-b3d9-e37b899d2dd1.png)

6. Click **Sort**

![img_google_sheets_sort_range_6](https://user-images.githubusercontent.com/47166768/192561505-0b635376-dadd-4a29-a674-a9beb55f0ce6.png)

**Well Done!** You have successfully sorted the Pokemon by their total stats.




Multi-Level Sorting
---


Google Sheets lets you sort your data in multiple levels.

Sort the Pokemon in the range `A2:A21` by their **Total stats**, ascending from smallest to largest (A-Z) and then sort the results based on their **Name**.

Multi-level sort range, step by step:

1. Select all the data, range `A2:B21`

![img_google_sheets_sort_range_1](https://user-images.githubusercontent.com/47166768/192562272-86861f1a-7d72-4c75-9cca-fe37ae128aa5.png)

2. Click on the **Data** menu and find **Sort range**

![img_google_sheets_sort_range_2](https://user-images.githubusercontent.com/47166768/192562382-cddea99d-fd33-48b2-a32e-5c3a877e3861.png)

3. Click on **Sort range**

![img_google_sheets_sort_range_3](https://user-images.githubusercontent.com/47166768/192562493-68e8aed0-e177-4c3b-91b8-d7d89a114faf.png)

4. Select **Data has header row**

![img_google_sheets_sort_range_4](https://user-images.githubusercontent.com/47166768/192562579-55965b40-f826-4795-a53d-b6d6e0f40a44.png)

5. Select **Total stats** which is the header for column `B`

![img_google_sheets_sort_range_5](https://user-images.githubusercontent.com/47166768/192562674-8b665557-a22d-4cce-9664-d5652efeb9b0.png)

6. Click on **Add another sort column**

![img_google_sheets_sort_range_7](https://user-images.githubusercontent.com/47166768/192562881-b95c43db-fab7-42d1-8536-0c52071bbc35.png)

7. Select **Name** which is the header for column `A`

![img_google_sheets_sort_range_8](https://user-images.githubusercontent.com/47166768/192562994-dd3c47a1-d83e-41af-9b4e-48e3ea0d58c1.png)

8. Click **Sort**

![img_google_sheets_sort_range_9](https://user-images.githubusercontent.com/47166768/192563083-d5fe6b39-0c2f-44c8-832e-5b1a751608b3.png)



Let's compare the results of this example with the previous example:

![img_google_sheets_sort_range_10](https://user-images.githubusercontent.com/47166768/192563238-2c8874e8-be06-4e49-99f1-366205a6b74e.png)         ![img_google_sheets_sort_range_11](https://user-images.githubusercontent.com/47166768/192563556-cd5dfb13-0571-400b-9854-25b8d0704e17.png)




The image with the **blue** rectangle is the result of the first example and the image with the **green** rectangle is the result of the second example.

Look at rows `14:16`.

The order of Pokemon has changed. In the second example they are also sorted alphabetically.

This is because we added an additional sort rule to **Sort range**.




