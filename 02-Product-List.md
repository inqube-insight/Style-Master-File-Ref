# Product List

Product List tab enables to Add / Update / Remove Product IDs.

A Product ID is defined as a unique 'Customer - Season - Style - Version - Garment Color Code - Garment Color Name' combination. Effectively, this the unique Style unit against which a BOM / Cost Sheet is created.

The Product List tab can be used to update the following fields against a Product ID. Additionally to the below listed fields, one can also update the Garment Sizes and Garment Base Sizes against the said Product ID.

Product ID, Customer, Season, Style, Version No, Garment Color Code, Garment Color Name, WFX Color Code, Pack Type, Garments In Pack, Buyer Department, Program, Gender, Article Description, Merchant, Material Type, Product Group, Sub Category, Internal Style Ref, Selling Price, Efficiency, No of Lines, No of Machines, PD Template, Wash Garment, Sub Con Type, Status, Graphic No 1, Outside Operation 1, Op Rate 1, Graphic No 2, Outside Operation 2, Op Rate 2, Graphic No 3, Outside Operation 3, Op Rate 3, Remarks, SMV Level, Creation User, Created Datetime, Last Update User, Updated Datetime, Product Status

## Filters

Product List tab allows the users to filter based on

![](images/Product-List-Filters.png){width="100%"}

1.  Customer
2.  Season
3.  Style
4.  Version
5.  Garment Color
6.  Program

Further to the above mentioned filters, each column of the table can also be filtered. Column filtering works like a search field within the column where one can simply type what they are searching for.

![](images/Product-List-Table-Filter.png){width="100%"}

## Creating Products

To create a new Product ID, one needs to do as follows.

1.  Select a Customer
2.  Click on the 'Download All' or 'Download Selected' button
    -   This will download an Excel file
3.  On the downloaded Excel file, add a new record
    -   Leave the Product ID blank

    -   Customer, Season, Style, Version, Garment Color Code and Garment Color Name are mandatory

    -   All other columns are optional and can be either updated at the time of creation or can also be updated later

    -   If you wish to create multiple new Product IDs, then add multiple new records / rows on the excel file
4.  Once New records have been added to the downloaded Excel file, Save the excel file
5.  Upload the updated Excel file into the Product List tab
    -   Make sure that the correct Customer is selected when uploading
6.  Once the file has been uploaded, press the 'Save' button
    -   This would create N number of Product IDs

Please note: Customer, Season, Style, Version, Garment Color Code and Garment Color Name combination should always be unique for each line. If this is not unique, then new Product IDs will not be created for each row on the Excel file.

## Modifying Products

To Modify data against Product IDs, one needs to do as follows

1.  Select a Customer
2.  Select a Season
    -   All Product IDs against the Customer - Season will be listed on the below table
3.  Apply any further filters as and when necessary
4.  Select the relevant Product ID(s)
5.  Download using the 'Download Selected' button
6.  Modify the columns needed to be modified and Save the Excel file
    -   Do not edit the Product ID column

    -   Key columns Customer, Season, Style, Version, Garment Color Code and Garment Color Name cannot be changed, even if you do it will not change in the system
7.  Upload the modified Excel file
8.  Press the 'Save' button

## Removing Products

To Remove Product ID(s)

1.  Select a Customer
2.  Select a Season
    -   All Product IDs against the Customer - Season will be listed on the below table
3.  Apply any further filters as and when necessary
4.  Select the relevant Product ID(s)
5.  Press the 'Remove' button
6.  A popup message will appear, asking you to confirm
7.  Press the 'Remove' button on the popup to confirm

## Locking / Unlocking Product BOM(s)

Locking of BOM(s) was introduced to stop Development Merchants from making BOM changes after a certain point.

All users who have access as 'Development' merchant or 'Bulk' merchant, can 'Lock' the BOM(s).

For Unlocking, only certain nominated 'Bulk' merchant users are given access to 'Unlock' BOM(s).

To Lock / Unlock BOM(s)

1.  Select a Customer
2.  Select a Season
    -   All Product IDs against the Customer - Season will be listed on the below table
3.  Apply any further filters as and when necessary
4.  Select the relevant Product ID(s)
5.  Press the 'Lock / Unlock' button
    -   If the user has only 'Lock' access, selected BOM(s) will get 'Locked'

    -   If the user has both 'Lock' & 'Unlock' access, the lock status will get toggled such as 'Locked' BOM(s) will get unlocked, while the 'Unlocked' BOM(s) will get locked.

## Opening a Product BOM

To add / update / remove Raw Material items against a Product ID BOM, user needs to open the said BOM.

To open a BOM click on the <i class="fa fa-pencil-square"></i> icon against the said Product ID. This would open a new browser tab, where the BOM can be created / edited for the given Product ID.

Please refer to [Bill of Materials] for the documentation on BOM.

## Downloads

Different types of Excel files can be downloaded from the Product List tab for the select Product IDs.

1.  Product List
    -   Using the 'Download All' or 'Download Selected' buttons, this gives the upload format for Product ID creation or modification
2.  Consol. BOM
    -   This button gives a single excel file combining the BOMs for the selected Product IDs. It is useful if someone wishes to analyse multiple BOMs and needs multiple Style-Color BOMs to be downloaded together
3.  LD Tracker
    -   LD Tracker button is another version of the Consol. BOM, but with limited number of columns. This column format was requested by the Material Development team to help follow up on Lab Dips
4.  COE Excel
    -   COE Excel file the format which is sent to the COE team for updating WFX

    -   Using this button, a 'Zip' file is created with multiple Excel files compressed inside a folder

    -   Each Excel file represents 1 Product ID

    -   This button is a convenient to download multiple COE Excel files without opening each Product BOM one by one

    -   This functionality was requested originally to make it easier for the Lululemon team to send BOMs for the operations in Cambodia
5.  Logs
    -   Select a Customer

    -   Select a Season

    -   Select the relevant Product ID(s)

    -   User must select the type of Log(s) that they wish to download

    -   Click on the <i class = "fa fa-download"></i> button

    -   Logs can be downloaded for

        -   Product List

        -   BOM

        -   Orderbook

        -   Bulk YY - Fabric

        -   Bulk YY - Trims

        -   Thread YY - Lulu

        -   Thread YY - IE

        -   Product ID - Lock / Unlock

        -   YY Confirmation
