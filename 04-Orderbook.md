# Orderbook

## Filters

Orderbook tab allows the users to filter based on

![](images/paste-8CAB0EEB.png){width="100%"}

1.  Customer
2.  Season
3.  Style
4.  Garment Color

Further to the above mentioned filters, each column of the table can also be filtered. Column filtering works like a search field within the column where one can simply type what they are searching for.

![](images/paste-CFCF783B.png){width="100%"}

## Creating New Orders

To create a new Order, one needs to do as follows.

1\. Select a Customer

2\. Under the Orderbook with Size option, Click on the 'Download' or 'Download Selected' button

-   This will download an Excel file

3\. On the downloaded Excel file, add a new record

-   Leave the Order ID blank to create new Order

-   The combination of Order Type, Buyer PO Number OC, Ship Under PO Ref INQ, Summary Buyer Order Ref CPO, Delivery Buyer Order Ref VPO, Destination, Confirmed Delivery Date To Customer GAC is considered as unique. If the same combination is added in multiple rows, it would get combined into 1 order, adding the quantities of both the rows

-   If you wish to create multiple new Orders, then add multiple new records / rows on the excel file

4\. Once New records have been added to the downloaded Excel file, Save the excel file

5\. Upload the updated Excel file into the Orderbook tab

-   Make sure that the correct Customer & Season are selected when uploading

6\. Once the file has been uploaded, press the 'Save' button

-   This would create N number of Orders IDs

## Modifying Existing Orders

To Modify data against Order IDs, one needs to do as follows

1\. Select a Customer

2\. Select a Season

-   All Orders against the Customer - Season will be listed on the below table

3\. Apply any further filters as and when necessary

4\. Select the relevant Order ID(s)

5\. Download using the 'Download Selected' button

6\. Modify the columns needed to be modified and Save the Excel file

-   Do not edit the Order ID column

7\. Upload the modified Excel file

8\. Press the 'Save' button

## Removing Orders

To Remove Order ID(s)

1\. Select a Customer

2\. Select a Season

-   All Order IDs against the Customer - Season will be listed on the below table

3\. Apply any further filters as and when necessary

4\. Select the relevant Order ID(s)

5\. Press the 'Remove' button

6\. A popup message will appear, asking you to confirm

7\. Press the 'Remove' button on the popup to confirm

## Lululemon Customer Orderbook Format

Specifically for the Lululemon customer account, an additional feature was added to the Orderbook upload.

The Orderbook file sent by the Customer can be uploaded as is into the system to create new orders, by adding & amending a few columns.

Amendments to existing columns

1.  Season - Amend the season to reflect exactly as per the Product ID
2.  Channel - Amend the Channel to reflect the WFX Destination name
3.  Ship Mode - Amend the Ship Mode to reflect the same terminology as WFX
4.  Factory Name - Revise Factory names as per WFX

Additional Columns to be added

1.  Product ID
    -   If left blank, on upload, system will try to guess the Product ID based on Style, Color Code and Season
2.  Buy Type
3.  Order Type
4.  Fulfillment Type
5.  FOB
6.  FOB Upcharge
7.  FOB Discount

## WFX SOT Download

The 'WFX SOT' download button allows the user to download the selected Orders in the WFX SOT upload format. This option is provided to be able to check / review the excel format which is sent to COE from the application as part of the OC Creation job.
