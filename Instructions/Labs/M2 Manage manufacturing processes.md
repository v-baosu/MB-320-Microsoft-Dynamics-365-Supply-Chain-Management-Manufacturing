Module 2 Manage manufacturing processes
---------------------------------------

Case study 1A Discrete, Process and Lean manufacturing features
---------------------------------------------------------------

### Exercise \#1: Update the production control parameters

When you are starting to use the Production control module, you are required to
do some configurations that will help the system operate according to your
design and process design

The Operations manager at USMF,  wants to make some changes to the policies so
everything runs more efficiently. He wants to be sure routes are not allowed to
be modified or have their approvals removed. In order to accomplish this, a new
route operation should be created, and the effective dates updated

Can you help the operation manager to perform this?

You will have to do the following:

-   Update the production control parameters

#### Steps

-   Go to **Production control \> Setup \> Production control parameters**.

-   Set the **Block removal of approval** slider to **Yes** under
    the **Routes** group.

-   Set the **Block editing** slider to **Yes** under the **Routes** group.

-   Click **Save**.

-   Close all pages.

### Exercise \#2: Create new production pools

USFM has been getting reports from the customers that orders are not arriving on
time and that some of the delivered orders are missing pieces. One of the
supervisor wants you to determine what is causing these problems so the company
can find a solution.

You decide that you want more visibility into production orders that are
delayed, and you want to track subcontracted production orders that are missing
deliveries, production orders with missing materials and orders that are delayed
due to machine failures

How would you perform this?

You will have to do the following:

-   Production pool for Delayed sub contracted work

-   Production pool for missing materials

-   Production pool for machine failures

#### Steps

**Create a production pool for delayed subcontracted work**

1.  Open **Production control \> Setup \> Production \> Production pools**

2.  Click **New** to create a new pool.

3.  Type **Delay-Sub** in the **Pool** field.

4.  Type **Subcontracted Work Delayed** in the **Name** field.

**Create a production pool for missing materials**

1.  Click **New** to create a new pool.

2.  Type **MATMISSING** in the **Pool** field.

3.  Type **Materials Missing** in the **Name** field.

**Create a production pool for machine failures**

1.  Click **New** to create a new pool.

2.  Type **MACHFAIL** in the **Pool** field.

3.  Type **Machine Failure** in the **Name** field.

### Exercise \#3: Create and manage resources

Company USMF has bought a new packing robot that will reduce the need for manual
labor in the speaker packing workshop.

Workers from this group can therefore be reassigned to perform other work as the
new robot becomes fully operational.

You were asked to add the robot as a resource

How would you perform this?

You will have to do the following:

-   Create capabilities

-   Assign resource to capabilities

-   Assign capabilities to a resource

#### Steps

**Create capabilities**

1.  Go to **Organization administration \> Resources \> Resource capabilities**.

2.  Click **New**.

3.  Type **GTL-Assembly** in the **Capability** field and **Assembly** in the
    **Description** field.

4.  Click **New**.

5.  Type **GTL- Packing** in the **Capability** field and **Packing** in the
    **Description** field.

6.  Close the **Resource capabilities** page.

**Assign resources to capability**

1.  Go to **Organization administration \> Resources \> Resource capabilities**.

2.  Select **GTL-Assembly** from the list of capabilities.

3.  Click **Add** from the Action Pane.

4.  Select **5110**, Assembly worker 1, in the **Resource** field.

5.  Accept the default **Expiration** date of **Never**.

6.  Type **1** in the **Priority** field.

7.  Accept the default **Level** of 0.00.

8.  Repeat steps 3 to 7, for the resource 5111.

9.  Close the **Resource capabilities** page.

**Assign capabilities to a resource**

1.  Go to **Organization administration \> Resources \> Resources**.

2.  Select resource 5111 in the grid.

3.  Expand the **Capabilities** FastTab.

4.  Select **View \> All** from the Action Pane.

5.  Click **Add** from the Action Pane.

6.  Type GTL-Packing in the **Capability** field.

7.  Accept the default **Effective** date of today's date.

8.  Accept the default **Expiration** date of **Never**.

9.  Accept the default **Level** of 0.00.

10. Type **2** in the **Priority** field

11. Close the **Resources** page.

### Exercise \#4: Create an operation, assign relations and create a route

The company you are consulting has decided to produce a series of ebooks for a
client.

The production manager at USMF, wants to create an operation for the finished
good, assign relations, and create a route

Can you help the production manager?

You will have to do the following:

-   Create and configure an operation

#### Steps

1.  Go to **Production control \> Setup \> Routes \> Operations**.

2.  Click **New**.

3.  In the **Operation** field, type **eBook**.

4.  In the **Name** field, type **eBook assembly**.

5.  Click **Relations**.

6.  Click **New**.

7.  In the **Route group** field, enter or select **Discrete**.

8.  Expand the **Setup** section.

9.  In the **Formula** field, select **Capacity**.

10. In the **Costing resource** field, enter or select **1211**.

11. Click **Save**.

12. Close all pages.

13. Go to **Production control \> All routes**.

14. Click **New**.

15. In the **Name** field, type **eBook route**.

16. In the **Item group** field, enter or select **TV&Video**.

17. Click **Save**.

18. Click **Route details**.

19. Click **New**.

20. In the **Operation** field, enter or select **eBook**.

21. In the **Next** field, enter **20**.

22. In the **Link type** field, select **Soft**.

23. Click **New**.

24. In the **Oper. No.** field, enter **20**.

25. In the **Operation** field, enter or select **Padding**.

26. In the **Next** field, enter **30**.

27. In the **Link type** field, select **Hard**.

28. Click **New**.

29. In the **Oper. No**. field, enter **30**.

30. In the **Priority** field, select **Secondary 1**.

31. In the **Operation** field, enter or select **Packing**.

32. Refresh the page.

33. Click **Save**.

34. Close all pages.

### Exercise \#5: Create a simple BOM without a version

You have been asked to assist the product designer at USMF and show her how to
create a simple BOM for a new light cabinet. 

You will approve the BOM using employee 000020, Julia Funderburk.

You will use the parameters on the right

-   Name: Light Cabinet

-   Item group: Audio

-   Site: 1

-   Item:

-   M0005 Enclosure

-   M0006 Binding posts

-   P0002 Speaker Damping Foam

-   Quantity for each item: 1

You will have to do the following:

-   Create a simple BOM

#### Steps

1.  Go to **Product information management \> Bills of materials and formulas \>
    Bills of materials**.

2.  Click **New**.

3.  In the **Name** field, type **Light Cabinet**.

4.  In the **Site** field, enter or select **1**.

5.  In the **Item group** field, enter or select **Audio**.

6.  Click **Save**.

7.  In the **Bill of materials lines** section, click **New**.

8.  In the **Item number** field, type **M0005**.

9.  Click **New**.

10. In the **Item number** field, type **M0006**.

11. Click **New**.

12. In the **Item number** field, type **P0002**.

13. In the action pane, click **Approval**. Select **000020**, Julia Funderburk.

14. Click **OK**.

15. Click **Save**.

16. Close all pages.

### Exercise \#6: Create a BOM in the BOM designer (Bonus)

The new product designer at USMF has received a new specification for the
enclosure side of a cabinet.

She has requested your assistance.

You see that an item is not set up for this specification, so you only need to
create a simple BOM with component lines. 

Use employee 000020, Julia Funderburk, to approve the BOM.

Create a BOM titled “High Quality Speaker” and assign it to the Audio item group
at site 1. Use the BOM designer to add items with warehouse 11 and the following
quantities:

-   1 qty of M0008/High End Cabinet/Black

-   2 qty of M0002/Mid-Range Speaker Unit

-   1 qty of M0009/Protective Corners

You will have to do the following:

-   Create a BOM in the BOM designer

#### Steps

1.  Go to **Product information management \> Bills of materials and formulas \>
    Bills of materials**.

2.  Click **New**.

3.  In the **Name** field, type **High Quality Speaker**.

4.  In the **Site** field, type **1**.

5.  In the **Item group** field, enter or select **Audio**.

6.  Click **Designer**.

7.  Click **BOM lines**.

8.  Click **Add to component BOM**.

9.  In the list, find and select **M0008 / High End Cabinet / Black** (the
    checkbox on the left should be checked).

10. Click **OK**.

11. Click **BOM lines**.

12. Click **Add after line.**

13. In the list, find and select **M0009 / Protective Corners**.

14. Click **OK**.

15. Click **BOM lines**.

16. Click **Add before line**.

17. In the list, find and select **M0002 / Mid-Range Speaker Unit**.

18. Click **OK**.

19. Close the page.

20. Refresh the page.

21. In the list of Bill of materials lines, find and select the row for **M0002
    / Mid-Range Speaker Unit**.

22. Set **Quantity** to **2.0000**.

23. Click **Approval at the top**. Select **000020**, Julia Funderburk.

24. Click **OK**.

25. Close all pages.

### Exercise \#7: Create a BOM with a version

The sales department has reported that there is a high demand for
rosewood colored speakers instead of the traditional black. 

You are asked to prepare for the manufacture of more
rosewood colored speakers by creating a version, making a copy of the existing
BOM, removing item M0008/High End Cabinet/ Black and add item M0008/High End
Cabinet/Red for a quantity of 1.

Employee 000020, Julia Funderburk must approve the version.

Do not activate the BOM because the item is not ready for use yet.

Use the specifications given at right

-   Item number: 72708

-   Item name: High Quality Speaker Rosewood

-   Item group: Audio

-   Item model group: FIFO

-   Storage Dimension group: SiteWH

-   Tracking Dimension group: None

-   Warehouse 11

-   Approved by: 000020, Julia Funderburk

You will have to do the following:

-   Create a BOM with a version

#### Steps

1.  Go to **Product information management \> Products \> Released products.**

2.  Click **New**.

3.  In the **Product number** field, type **72708**.

4.  In the **Product name** field, type **High Quality Speaker Red**.

5.  In the **Item model group** field, enter or select **FIFO**.

6.  In the **Item group** field, enter or select **Audio**.

7.  In the **Storage dimension** group field, enter or select **SiteWH**.

8.  In the **Tracking dimension** group field, enter or select **None**.

9.  Click **OK**.

10. On the Action Pane, click **Manage inventory**.

11. Click **Default order settings**.

12. In the **Default order type** field, select **Production**.

13. Under the **Inventory** FastTab, In the **Default warehouse** field, type
    **11**.

14. Close the page.

15. On the Action Pane, click **Engineer**.

16. Click **Designer**.

17. Click **BOM**.

18. Click **Create version**.

19. In the **Name** field, type **High Quality Speaker Rosewood**.

20. Select **Yes** in the **Copy** field.

21. In the **Site** field, type **1**.

22. Click **OK**.

23. In the **Item number** field, enter or select **D0004**.

24. Click **OK**.

25. In the tree, select **Item number: 72708\\M0008 / High End Cabinet**.

26. Click **BOM lines**.

27. Click **Delete**.

28. Click **BOM lines**.

29. Click **Add before line**.

30. In the list, find and select **M0008 / High End Cabinet / Rosewood**.

31. Click **OK**.

32. In the tree, select **Item number: 72708**.

33. Click **BOM**.

34. Click **BOM versions**.

35. Click **Approve**. Select **000020**, Julia Funderburk.

36. Select **Yes** in the **Do you also want to approve the bill of materials?**
    field.

37. Click **OK**.

38. Close all pages.

### Exercise \#8: Create a production order

The minimum information required to create a production order is an active bill
of materials.

Create a new production order to test the previously created BOM

You will have to do the following:

-   Create a new production order

#### Steps

1.  Go to **Production control \> Production orders \> All production orders**.

2.  Click **New production order**.

3.  In the **Item number** field, enter or select **72708**.

4.  Set **Quantity** to **10.00**.

5.  In the **Time** field, enter **10:15 AM**.

6.  Click **Create**.

7.  Click **Estimate**.

8.  Click **OK**.

9.  Click **Release**.

10. Click **OK**.

11. Click **Start**.

12. Click **OK**.

13. Click **Report as finished**.

14. Click **OK**.

15. Click **End**.

16. Click **OK**.

17. Close all pages.

### Exercise \#9: Start a discrete production order (Bonus)

You can get production orders either manually created or firmed from the Master
planning with status “Scheduled”

The production of the ash enclosure back sides of the speakers is ready to be
started.

The production supervisor wants to use the start form and select a production
order with status of “Scheduled” to start.

Can you help the production manager to perform this?

You will have to do the following:

-   Start a discrete production order

#### Steps

1.  Click **Production control \> All Production orders**.

2.  Select any production order with the production order status set to
    **Scheduled** (for example, P000171).

3.  On the **Production order** action pane, click **Start**.

4.  On the **Overview** tab, in the **Quantity** field, enter the quantity
    **2.00** of the production order to produce.

5.  In the **Date** field, enter today’s date for the date that the production
    starts.

6.  Select the **Start production** check box.

7.  Click **OK**.

### Exercise \#10: Run a resource schedule

The Production Manager wants to use a newly purchased assembly robot to increase
flexibility in production.

In the past, when she designed the production process (route) for a product, she
had to specify where each operation was to be performed.

Now, she want to defer the allocation of where and by whom an operation is
performed until the production is scheduled, and to use excess capacity in other
workshops to eliminate bottlenecks in heavily loaded workshops.

She is not sure how to do so and asked for your help.

Can you help?

You will have to do the following:

-   Create capabilities and resources

-   Identify the resources applicable for the operation

-   Add requirements for a capability to an operation

#### Steps

**Create capabilities and resources**

1.  Navigate to **Organization administration \> Resources \> Resource
    capabilities**.

2.  Click **New**.

3.  Type **20** in the **Capability** field and **Assembly** in the
    **Description** field.

4.  Click **New**.

5.  Type **30** in the **Capability** field and **Packing** in the
    **Description** field.

6.  Expand the **Resources** FastTab.

7.  Click **Add**.

8.  Select **1222** (Speaker packing worker 1) in the **Resource** field.

9.  Accept the default expiration date of **Never**.

10. Accept the default **Level** of 0.00.

11. Type **1** in the **Priority** field.

12. Close the **Resource capabilities** form.

13. Open **Organization administration \> Resources \> Resources**.

14. Click **New**.

15. Type **000727** in the **Resource** field.

16. Type **Assembly robot** in the **Description** field.

17. Accept the default of **Machine** in the **Type** field.

18. Open the **Capabilities** FastTab.

19. Click **Add**.

20. Select 20 in the **Capability** field.

21. Accept the default expiration date of **Never**.

22. Accept the default **Level** of 0.00.

23. Type **1** in the **Priority** field.

24. Expand the **Resource groups** FastTab.

25. Click **View \> All**.

26. Click **Add**.

27. Type **1210** in the **Resource group** field, type the next working day in
    the **Effective** field, and then accept the default expiration date of
    **Never**.

28. Accept the default **Input warehouse**.

29. Accept the default **Input location**.

30. Scroll up, expand **Calendars** tab, and click **Add**.

31. Select **24hr** in the **Calendar** field.

32. Close the **Resources** form.

**Identify resources applicable for the operation**

1.  Navigate to **Production control \> Operations \> All routes**

2.  Select route **000002** (STANDARD SPEAKER - D0003) by clicking on the link
    for 000002.

3.  Click **Route** \> **Route details**.

4.  Verify operation 10 is selected in the grid of the **Route** form.

5.  Click **Applicable Resources**.

6.  Notice that all the resources from the 1210 resource group are listed.

7.  Click Scroll one day forward by clicking the **Next day** button or choose
    the date picker field.

8.  Click **OK**.

9.  Close the **Applicable resources** form.

**To add requirements for a capability to an operation, follow these steps:**

1.  In the **Route details** form for route 000002, with operation 10 selected
    in the grid, select the **Resource requirements** tab.

2.  In the Resource requirements grid, select the line where **Requirement
    type** is Capability and **Requirement** is Assembly.

3.  Click **Delete**, and then click **Yes** to delete the record.

4.  Click **Maintain resource requirements.** This starts the wizard.

5.  On the welcome screen, click **Next**.

6.  On the search criteria screen, select **Capability** in the **Requirement
    type** field.

7.  Type **20** in the **Requirement** field.

8.  Click Next.

9.  On the action screen, leave the defaults and click Next.

10. On the New resource requirements screen, set **Requirement type** to
    **Capability**, **Requirement** to **20**, and check the **Operation
    scheduling** and **Job scheduling** check boxes.

11. Click **Next**.

12. On the summary screen, review your options and click **Finish**.

13. Close all pages.

### Exercise \#12: Configure costing policies

At USMF, you need to set profit-settings to help sales personnel calculate an
accurate sales price after considering all costs for cabinet item D0002.

You should also be able to view the costing sheet to analyze the cost breakdown

Can you help the sales personnel?

You will have to do the following:

-   Update the profit settings on the item

-   Review the costing sheet setup

-   View the calculation details on the item

#### Steps

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the **Quick Filter** to filter on the **Item number** field with a value
    of **D0002**.

3.  In the list, click **D0002** to open the details page.

4.  Expand the **Manage costs** FastTab.

5.  Click **M9 cost group** to open the cost group details page.

6.  Click **Edit**.

7.  Set **Profit percentage** to **40.00**.

8.  Click **Add**.

9.  In the **Profit-setting** field, select **Profit 1**.

10. Set **Profit percentage** to **70.00**.

11. Click **Save**.

12. Close the page.

13. On the Action Pane, click **Engineer**.

14. Click **BOM versions**.

15. Under the Bill of materials lines, click **M0005** to open the **Product
    information** dialog box.

16. Click **M0005** item number (not product number) to open the **Product
    details** page.

17. Click Cost group **M2** in the Manage costs FastTab to open the **Cost group
    details** page.

18. Click **Edit**.

19. Set **Profit percentage** to **30.00**.

20. Click **Add**.

21. In the **Profit-setting** field, select **Profit 1**.

22. Set **Profit percentage** to **60.00**.

23. Close the page.

24. Close all pages.

25. Go to **Cost management \> Indirect cost accounting policies setup \>
    Costing sheets**.

26. In the tree, select **Root\\Cost of Conversion\\COC-Material\\COC - M2 -
    Cabinets comp**.

27. Review the structure of the costing sheet.

28. In the tree, select **Root\\Cost of Conversion\\Overhead on Conversion\\COC
    - OVH4 - Labor overhead\\Indirect labor cost - Rate per process time**.

29. Review the **Absorption basis**, and **Rate** FastTabs values.

30. In the tree, select **Root\\Cost of Conversion\\Overhead on Conversion\\COC
    - OVH4 - Labor overhead**.

31. Click on **OVH4**

32. Set **Profit percentage** to **80.00**.

33. Close all pages.

34. Go to **Product information management** \> **Products** \> **Released
    products**.

35. Use the **Quick Filter** to filter on the **Item number** field with a value
    of **D0002**.

36. Click the **D0002** link to open the product details screen.

37. On the Action Pane, click **Manage costs**.

38. Click **Item price**.

39. Click the **Pending prices** tab.

40. Click **Calculate item cost**.

41. In the **Costing version** field, enter or select **10**.

42. Click **OK**.

43. Click **View calculation details.**

44. Click the **Costing sheet** tab.

45. Analyze the cost breakdown for the cabinet **D0002**.

46. Close all pages.

### Exercise \#13: Configure manufacturing execution (Bonus)

The Production Manager, determined that the best way to post picking lists is to
use the operation quantity feedback (backflush on operations) method.

If the actual consumption on BOM items differs from the estimated consumption,
the employee can enter the actual item consumption when providing quantity
feedback

The production manager not sure how to perform this and asked for your help.

Can you help?

You will have to do the following:

-   Update the parameters under manufacturing execution production order default
    parameters

#### Steps

1.  Open **Production control \> Setup \> Manufacturing execution \> Production
    order defaults**.

2.  On the **Start** tab, select **Status** in the **Update start on-line**
    field.

3.  In the **Automatic BOM consumption** field, select **Never**.

4.  Click the **Operations** tab.

5.  Set the **Setup** option to **No**.

6.  In the **Automatic BOM consumption** field, select **Always**.

7.  Click the **Report as finished** tab.

8.  In the **Update finished report on-line** field, select **Quantity**.

9.  In the **Automatic BOM consumption** field, select **Never**.

10. Close the **Production order defaults** form.

### Exercise \#14: Configure automatic route consumption on setup jobs (Bonus)

Your estimation on operation setup has proven accurate, so the Production
Manager decided that it is not necessary for employees to register on setup
jobs.

The time consumption on setup jobs must be posted automatically

How would you automate this posting?

You will have to do the following:

-   Update routing groups.

-   Update the routing group on the MES production order defaults

#### Steps

1.  Open **Production control \> Setup \> Routes \> Route groups**.

2.  From the list, select **Sfc Shop Floor Control Routing Group**.

3.  Click **Edit**.

4.  On the **General** FastTab, in the **Automatic route consumption** group,
    enable the **Setup time** field.

5.  Close the **Route groups** form.

6.  Open **Production control \> Setup \> Manufacturing execution \> Production
    order defaults**.

7.  On the **Start** tab, in the **Automatic route consumption** field, select
    **Route group dependent**.

8.  Enable the **Post route card now** field.

9.  Close the **Production order defaults** form.

### Exercise \#15: Use manufacturing execution (Bonus)

To proceed with testing the manufacturing execution, you need to enable time
registration for Shannon, the machine operator in USMF.

Shannon needs to use the job card terminal to control the execution of the
production order

Can you enable the time registration? How?

You will have to do the following:

-   Enable time registration for the machine operator

#### Steps

1.  Go to **Human resources \> Workers \> Employees**.

2.  Use the **Quick Filter** to filter on the **Name** field with a value of
    **SHANNON**.

3.  Click **Activate on registration terminals** in the **Time** tab of the
    action pane.

4.  In the **Calculation group** field, enter or select **Man**.

5.  In the **Default calculation group** field, enter or select **Man**.

6.  In the **Approval group** field, enter or select **AdmMan**.

7.  In the **Standard profile** field, enter or select **Standard**.

8.  In the **Profile group** field, enter or select **Man**.

9.  Select **Yes** in the **Use timecard** field.

10. In the **Configuration** field, enter or select **Production**.

11. Select **Yes** in the **Supervisor options** field.

12. Click **OK**.

13. In the list, click on the **Shannon** link id to get to the detail page.

14. Click the **Time registration** tab.

15. Click **Edit**.

16. In the **Identification** field, type **069**.

17. In the **Badge ID** field, type **069**.

18. Click **Save**.

19. Close the page.

20. Go to **Production control \> Manufacturing execution \> Job card device**.

21. In the **Personnel number** field, type **069**.

22. Click **Log in**.

23. Click **Start job**.

24. Set **Quantity to start** to **1.00**.

25. Click **OK**.

26. Click **Report progress**.

27. Set **Error quantity** to **1.00**.

28. In the **Error cause** field, enter **Material**.

29. Click **OK**.

30. Click **Break**.

31. In the list, select **break from work**

32. Click **OK**.

33. Click **Stop break**.

34. Click **Activity**.

35. In the list, find and select E**quipment repair**

36. Click **OK**.

37. Click **OK**.

38. Set **Error quantity** to **2.00**.

39. In the **Error cause** field, enter **Machine**.

40. Click **OK**.

41. Click **Close**.

42. Click **Next job**.

43. Click **Previous job**.

44. Click **Report progress**.

45. Set **Good quantity** to **5.00**.

46. In the **Job status** field, enter **Completed**.

47. Click **OK**.

48. Close the page.

Case study 1B Discrete, Process and Lean manufacturing features
---------------------------------------------------------------

### Exercise \#1: Create an approved vendor list and setting method to Warning Only (Bonus)

Contoso Orange Juice USP2 has determined that approved vendor control shall be
placed on item M7001 with the approved vendor being US-113, and they have
assigned the task to you

Can you perform this task?

You will have to do the following:

-   Set up the approved vendor or default vendor

-   Set vendor check method to Warning Only

#### Steps

**Set up the approved vendor or default vendor**

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **M7001**.

3.  Click the item number to get from the grid to the details page.

4.  On the Action Pane, click **Purchase**.

5.  Click **Setup**.

6.  Click **Add**.

7.  In the **Vendor** field, type **US-113**.

8.  Click **Save**.

9.  Close the page.

**Set the vendor check method to Warning Only**

1.  Click **Edit**.

2.  In the **Approved vendor check method** field in the Purchase Fast Tab,
    select **Warning Only**.

3.  Click **Save**.

4.  Close the page.

### Exercise \#2: Create items with different production types

Contoso Process Company (USPI) has purchased a small oil refinery and will start
to manufacture gasoline from a stream of crude oil.

This process produces kerosene and diesel fuel as co-products and wastewater as
a by-product.

You will help the product designer to create the items listed here within
finance and operations using different production types to assist in the
creation of formulas or recipes

-   Product Number: P15000

    -   Product Name: Gasoline

    -   Production Type: Formula

-   Product Number: P16000

    -   Product Name: Kerosene

    -   Production Type: Co-Product

-   Product Number: P17000

    -   Product Name: Diesel Fuel

    -   Production Type: Co-Product

-   Product Number: B18000

    -   Product Name: Waste Water

    -   Production Type: By-Product

-   Product Number: M12000

    -   Product Name: Crude Oil

    -   Production Type: None

You will have to do the following:

-   Create a new formula product

-   Create the new  
    co-products

-   Create the new byproducts

-   Create the new raw material

#### Steps

**Create a new formula product**

1.  Go to **Product information management\>Products\>Released products**.

2.  Click **New**.

3.  In the **Product number** field, type P15000.

4.  In the **Product name** field, type Gasoline.

5.  In the **Item model group** field, enter or select a value.

6.  In the **Item group** field, enter or select a value.

7.  In the **Storage dimension group** field, enter or select a value.

8.  In the **Tracking dimension group** field, enter or select a value.

9.  In the I**nventory unit** field, type **gal**.

10. In the **Purchase unit** field, type **gal**.

11. In the **Sales unit** field, type **gal**.

12. In the **BOM unit** field, type **gal**.

13. Click **OK**.

14. In the **Production type** field in the Engineer Fast Tab, select Formula.

15. In the **Shelf life period in days** field in the **Manage inventory** Fast
    Tab, enter **365**.

16. Click **Save**.

17. Close the page.

 

**Create the new co-products**

1.  Click **New**.

2.  In the **Product number** field, type **P16000**.

3.  In the **Product name** field, type **Kerosene**.

4.  In the **Item model group** field, enter or select a value.

5.  In the **Item group** field, enter or select a value.

6.  In the **Storage dimension group** field, enter or select a value.

7.  In the **Tracking dimension group** field, enter or select a value.

8.  In the **Inventory unit** field, type **gal**.

9.  In the **Purchase unit** field, type **gal**.

10. In the **Sales unit** field, type **gal**.

11. In the **BOM unit** field, type **gal**.

12. Click **OK**.

13. In the **Shelf life period in days** field in the **Manage inventory** Fast
    Tab, enter **365**.

14. In the **Production type** field in the **Engineer** Fast Tab, select
    **Co-product**.

15. In the **Planning formula** field, enter **P15000**.

16. Click **Save**.

17. Close the page.

18. Click **New**.

19. In the **Product number** field, type **P17000**.

20. In the **Product name** field, type **Diesel Fuel**.

21. In the **Item model group** field, enter or select a value.

22. In the **Item group** field, enter or select a value.

23. In the **Storage dimension group** field, enter or select a value.

24. In the **Tracking dimension group** field, enter or select a value.

25. In the **Inventory unit** field, type **gal**.

26. In the **Purchase unit** field, type **gal**.

27. In the **Sales unit** field, type **gal**.

28. In the **BOM unit** field, type **gal**.

29. Click **OK**.

30. In the **Production type** field in the **Engineer** Fast Tab, select
    **Co-product**.

31. In the **Planning formula** field, enter **P15000**.

32. Click **Save**.

33. Close the page.

 

**Create the new by-products**

1.  Click New.

2.  In the **Product number** field, type **B18000**.

3.  In the **Product name** field, type **Waste Water**.

4.  In the **Item model** group field, enter or select a value.

5.  In the **Item group** field, enter or select a value.

6.  In the **Storage dimension group** field, enter or select a value.

7.  In the **Tracking dimension group** field, enter or select a value.

8.  In the **Inventory unit** field, type **gal**.

9.  In the **Purchase unit** field, type **gal**.

10. In the **Sales unit** field, type **gal**.

11. In the **BOM unit** field, type **gal**.

12. Click **OK**.

13. In the **Shelf life period in days** field in the **Manage inventory** Fast
    Tab, enter **365**.

14. In the **Production type** field, select **By-product**.

15. Click **Save**.

16. Close the page.

**Create the new raw material**

1.  Click **New**.

2.  In the **Product number** field, type **M12000**.

3.  In the **Product name** field, type **Crude Oil**.

4.  In the **Item model group** field, enter or select a value.

5.  In the **Item group** field, enter or select a value.

6.  In the **Storage dimension group** field, enter or select a value.

7.  In the **Tracking dimension group** field, enter or select a value.

8.  In the **Inventory unit** field, type **gal**.

9.  In the **Purchase unit** field, type **gal**.

10. In the **Sales unit** field, type **gal**.

11. In the **BOM unit** field, type **gal**.

12. Click **OK**.

13. In the **Production type** field, select None.

14. Click **Save**.

15. Close all pages.

### Exercise \#3: Create and activate a formula using different product types

The engineering department has finished the review of the data in the new
refinery and determined the formula should be as specified here.

The product definition employee wants to create the formula and assign the
co-products and by-products to the formula and cost allocation.

He asked for your help. Can you help?

-   Product Number: P15000

-   Product Name: Gasoline

-   Formula Size: 500 gal

-   Formula Line: M12000 (Crude Oil), QTY 1000 gal

-   Formula Line: M2001 (DI Water), QTY 600 gal

-   Co-Product Line: P16000 (Kerosene), QTY 50 gal 10% cost allocation

-   Co-Product Line: P17000 (Diesel Fuel), QTY 350 gal 32% cost allocation

-   By-Product Line: B18000 (Waste Water), QTY 600 gal, 5% cost allocation

-   Approved by: Glen John

You will have to do the following:

-   Create a formula

-   Add formula lines to the formula

-   Add co-products and by-products with cost allocation

-   Approve and activate the formula

#### Steps

**Create a formula for part P15000**

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to find records. For example, filter on the Item number
    field with a value of **p15000**. Note the lowercase – it is not case
    sensitive.

3.  Click the ellipsis, if needed, to get to the **Engineer** tab on the action
    pane.

4.  Click **Formula versions**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type **GAS001**.

8.  In the **Name** field, type **Gasoline**.

9.  In the **Site** field, enter or select **1**.

10. Click **OK**.

11. In the **Lines** or **header** field, select **Header**.

12. In the version, set **Formula size** to **500**.

13. Click **Save**.

 

 

**Add Formula Lines to Formula**

1.  In the **Lines** or **header** field, select **Lines**.

2.  Click **New**.

3.  In the **Item number** field, type **M12000**.

4.  In the **Warehouse** field, enter or select a value.

5.  Set **Quantity** to **1000**.

6.  Click **New**.

7.  In the **Item number** field, type **M2001**.

8.  Set **Quantity** to **600**.

9.  Click **Save**.

10. Close the page.

**Add Co-Products and By-Products with Cost Allocation**

1.  Click **Co-products**.

2.  Click **New**.

3.  In the **Item number** field, type **P16000**.

4.  In the **Warehouse** field, enter or select a value.

5.  Set **Quantity** to **50**.

6.  In the **Co-product cost allocation** field, select **Manual**.

7.  Set **Cost allocation percent** to **10**.

8.  Click **Save**.

9.  Click **New**.

10. In the **Item number** field, type **P17000**.

11. In the **Warehouse** field, type **11**.

12. Set **Quantity** to 350.

13. In the **By-product cost allocation** field, select Percent .

14. Set **Cost allocation percent** to **32**.

15. Click **Save**.

16. Click **New**.

17. In the **Item number** field, type **B18000**.

18. In the **Warehouse** field, type a value.

19. Set **Quantity** to **600**.

20. In the **By-product cost allocation** field, select **Percent**.

21. Set **By-product burden amount** to **5**.

22. Click **Save**.

23. Close the page.

**Approve and activate the formula**

1.  Click **Approve**.

2.  In the **Approved by** field, enter or select **000528** for Glen John.

3.  Select the **Do you also want to approve the formula?** check box.

4.  Click **OK**.

5.  Click **Activate**.

6.  Close the page.

### Exercise \#4: Create a new formula with a version from the released products form (Bonus)

The marketing department at USP2 Contoso Orange Juice factory has determined the
need for production of a new product for Frozen Apple Juice Concentrate.

The product designer asked you to help create a formula version with the
following details

Can you do so?

-   Product Number: P7100

-   Product Name: Frozen Apple Juice Concentrate

-   Formula Size: 1000 gal

-   Formula Line: M9103 (Apples), QTY 800

-   Formula Line: M8001 (Asorbic Acid),  
    QTY 660

-   Formula Line: M8003 (Vitamin A), QTY 40

-   Formula Line: M8004 (Vitamin C), QTY 18

-   Formula Line: M7003 (Sucrose), QTY 33

-   Formula Line: M8008 (Can), QTY 2400

-   Approved by: Glen John

You will have to do the following:

-   Create a new product.

-   Create a formula.

-   Create formula lines.

-   Approve and activate the formula

#### Steps

**Create a new product**

1.  In the **USP2** company go to **Product information
    management\>Products\>Released products**

2.  Click **New**.

3.  In the **Product number** field, type **P7100**.

4.  In the **Product name** field, type **Frozen Apple Juice Concentrate**.

5.  In the **Search name** field, type **FrozenAppleJuice**.

6.  In the **Item model group** field, enter or select a value.

7.  In the **Item group** field, enter or select a value.

8.  In the **Storage dimension group** field, enter or select a value.

9.  In the **Tracking dimension group** field, enter or select a value.

10. In the **Inventory unit** field, enter **lb**.

11. In the **Purchase unit** field, type **lb**.

12. In the **Sales unit** field, type **lb**.

13. In the **BOM unit** field, type **lb**.

14. Click **OK**.

15. In the **Production type** field in the Engineer Fast Tab, select
    **Formula**.

16. In the **Shelf life period in days** field in the Manage inventory Fast Tab,
    type **180**.

17. Click **Save**.

 

**Create a formula**

1.  Click **Formula versions** in the Engineer tab in the action pane.

2.  Click **New**.

3.  Click **Formula and formula version**.

4.  In the **Formula** number field, type **FOR-7100**.

5.  In the **Name** field, type **For making Frozen Apple Juice Concentrate**.

6.  In the **Site** field, enter or select **1**.

7.  Click **OK**.

**Create formula lines**

1.  In the **Lines** or **header** field, select **Header**.

2.  Set **Formula size** to 1000.

3.  Set **From formula size** in the Formula versions Fast Tab to **1000**.

4.  In the **Lines** or **header** field, select **Lines**.

5.  In the Formula lines fast tab, click **New**.

6.  In the **Item number** field, type **M9103**.

7.  Set **Quantity** to **800**.

8.  Click **New**.

9.  In the **Item number** field, type **M8001**.

10. Set **Quantity** to **660**.

11. Click **New**.

12. In the **Item number** field, type **M8003**.

13. Set **Quantity** to **40**.

14. Click **New**.

15. In the **Item number** field, type **M8004**.

16. Set **Quantity** to **18**.

17. Click **New**.

18. In the **Item number** field, type **M7003**.

19. Set **Quantity** to **33**.

20. Click **New**.

21. In the **Item number** field, type **M8008**.

22. Set **Quantity** to **2400**.

23. Click **Save**.

**Approve and activate the formula**

1.  Click **Approve formula**.

2.  In the **Approved by** field, enter or select **000528** for Glen John.

3.  Click **OK**.

4.  In the **Lines** or **header** field, select **Header**.

5.  Click **Approve** in the versions section.

6.  In the **Approved b**y field, enter or select a value.

7.  Click **OK**.

8.  Click **Activate**.

9.  Close the page.

### Exercise \#5: Revise, update and activate a formula (Bonus)

Analysis of the production orders for P8000 in company USP2 has shown that the
scrap factors and consumption amount of part P6000 need to be updated.

You want to formula revise, update, approve, and activate the formula with an
effective date of 12/15/2020

You will have to do the following:

-   Copy the existing formula

-   Update line

-   Date out the old version and date in the new version

-   Approve and activate the formula

#### Steps

**Copy the existing formula**

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **P8000**.

3.  In the list, click the link in the selected row.

4.  Click **Formula versions in the Engineer tab on the action pane**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type **F01**.

8.  In the **Name** field, type **V01**.

9.  Set the **Copy** to **Yes**.

10. In the **Site** field, enter or select **1**.

11. Click **OK**.

12. In the **Formula version** field, select the previous formula version
    **For-00002**.

13. Click **OK**.

**Update the line**

1.  In the list, find and select the record for **P6000**.

2.  Set **Quantity** to **0.35**.

3.  Click the **Setup** tab.

4.  In the **Variable scrap** field, enter a number.

5.  Click **Save**.

6.  Close the page.

**Date out the old version and date in the new version**

1.  In the list, find and select the original formula version **For-00002**.

2.  In the **To date** field, set the date to **12/14/2020**.

3.  Click **Save**.

4.  In the list, find and select the new formula version **F01**.

5.  In the **From date** field, set the date to **12/15/2020**.

6.  Click **Save**.

**Approve and activate the formula**

1.  Click **Formulas** \> **Formula**.

2.  Click **Approve formula**.

3.  In the **Approved by** field, enter or select a value.

4.  Close the screen to go back to the Formula versions screen.

5.  Click **Formula version** \> **Approve**.

6.  In the **Approved by** field, enter or select a value.

7.  Click **OK**.

8.  Click **Activate**.

9.  Close the page.

### Exercise \#6: Use the scalability feature to create a new formula

Your manufacturing plant in company USP2 has obtained a new mixer that is 1.5
times the size of the current mixer used to make part P9500.

Engineering has determined that the vitamin compounds do not need to increase in
quantity, but the other ingredients do.

Use the formula scalability feature to create a new formula for the larger size
based on the existing formula for the part

You will have to do the following:

-   Copy the existing formula

-   Verify the lines are flagged as scalable for P9500 (except for the vitamin
    compounds)

-   Update the formula size

-   Approve and activate the formula

#### Steps

**Copy the existing formula**

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **P9500**.

3.  In the list, click the link in the selected row.

4.  Click **Formula versions in the Engineer tab in the action pane**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type **P9500V0**.

8.  In the **Name** field, type **V0**.

9.  Select the **Copy** option.

10. In the **Site** field, enter or select **1**.

11. Click **OK**.

12. In the **Formula version** field, select the current version.

13. Click **OK**.

**Verify the lines are flagged as scalable for P9500 (except for the vitamin
compounds)**

1.  In the lines, find the vitamin compounds.

2.  Select or clear the **Scalable** check boxes.

3.  Click **Save**.

 

**Update the formula size**

1.  In the **Lines or header** field, select **header**.

2.  Set **Formula size** to **1500**.

3.  Set **From formula size** to **1500**.

4.  Click **Save**.

**Approve and activate the formula**

1.  In the Lines or header field, select **lines**.

2.  Click **Save**.

3.  Click **Approve formula**.

4.  In the **Approved by** field, enter or select a value.

5.  Click **OK**.

6.  In the **Lines or header** field, select **header**.

7.  Click **Approve** in the **Versions** grid.

8.  In the **Approved by** field, enter or select a value.

9.  Click **OK**.

10. Click **Activate**.

11. Close the page.

### Exercise \#7: Create and activate a percentage-based formula (Bonus)

Company USP2 has been contracted to make a new orange juice with the following
volume percentages for the final mixture.

The mixture should also have vitamin C and vitamin A added per the mixing
instructions given here.

The volume batch size is to be 1500 gallons

You were asked to use this info to create the formula. Can you help?

| Ingredient | Recipe percent/         |
|            | quantity                |
|------------|-------------------------|
| P9500      | 5%                      |
| M9001      | 92%                     |
| M7004      | 3%                      |
| M8004      | 1.33 lb/1500 gal.       |
| M8003      | 1.1 LB/1500 gal.        |

You will have to do the following:

-   Create a new release product

-   Copy the existing formula for P9500

-   Verify the lines are flagged as scalable for P9500 (except the vitamin
    compound)

-   Update the formula size

-   Approve and activate the formula

#### Steps

**Create a new released product**

1.  In the **USP2** company go to **Product information
    management\>Products\>Released products**.

2.  Click **New**.

3.  In the **Product number** field, type **'P6100'**.

4.  In the **Product name** field, type ‘**Orange Juice'**.

5.  In the **Search name** field, type **'Orange Juice'**.

6.  In the **Search name** field, type **'Orange Juice'**.

7.  In the **Item model group** field, enter or select a value.

8.  In the **Item group field**, enter or select a value.

9.  In the **Storage dimension group** field, enter or select a value.

10. In the **Tracking dimension group** field, enter or select a value.

11. In the **Inventory unit** field, type **gal**.

12. In the **Purchase unit** field, type **gal**.

13. In the **Sales unit** field, type **gal**.

14. In the **BOM unit** field, type **gal**.

15. Click **OK**.

16. In the **Production type** field in the Engineer Fast Tab, select
    **'Formula'**.

17. In the **Shelf life period in days** field in the Manage inventory Fast Tab,
    enter 180.

18. Click **Save**.

 

**Copy the existing formula for P9500**

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **'P9500'**.

3.  In the list, click the link in the selected row.

4.  Click **Formula versions** in the Engineer tab in the action pane.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type a value.

8.  In the **Name** field, type a value.

9.  Select the **Copy** option.

10. In the **Site** field, enter or select **1**.

11. Click **OK**.

12. In the **Formula version** field, select the current version.

13. Click **OK**.

**Verify the lines are flagged as scalable for P9500 (except for the vitamin
compounds)**

1.  In the lines, find the vitamin **compounds**.

2.  Select or clear the **Scalable** check boxes.

3.  Click **Save**.

**Update the formula size**

1.  In the Lines or header field, select **header**.

2.  Set the version’s **Formula size** to **'1500'**.

3.  Set the version’s **From formula size** to **'1500'**.

4.  Click **Save**.

**Approve and activate the formula**

1.  In the Lines or header field, select **lines**.

2.  Click **Save**.

3.  Click **Approve formula**.

4.  In the **Approved by** field, enter or select a value.

5.  Click **OK**.

6.  In the Lines or header field, select **header**.

7.  Click **Approve** in the **Versions** grid.

8.  In the **Approved by** field, enter or select a value.

9.  Click **OK**.

10. Click **Activate**.

11. Close all pages.

### Exercise \#8: Change a linear consumption to a step-wise consumption

In company USP2, the formula for product P9500 should be updated.

Formula line M9003 needs to be changed from a linear consumption to a step-wise
consumption

The consumption on the line shall be:

-   0-1400: 5.5

-   1400-2400: 10.6

-   2400+: 15.8

The company employee not sure how to do so and asked for your help. Can you
help?

You will have to do the following:

-   Copy the existing formula  
    for P9500

-   Set the line for M9003 in the new formula to step-wise consumption and set
    the  
    step levels

-   Date out the old formula and date in the new one

-   Approve and activate the formula

#### Steps

**Copy the existing formula for P9500**

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **P9500**.

3.  In the list, click the link in the selected row for **P9500**.

4.  Click **Engineer** \> **Formula** \> **Formula versions**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Formula number** field, type **P9500V1**.

8.  In the **Name** field, type **V1**.

9.  Select the **Copy** option.

10. In the **Site** field, enter or select 1.

11. Click **OK**.

12. In the **Formula version** field, select the current version

13. Click **OK**. 

**Set the line for M9003 in the new formula to step-wise consumption and set the
step levels**

1.  In the lines, find the line for **M9003**.

2.  Click the **Setup** tab in line details.

3.  In the **Formula** field, select **Step**.

4.  Click the **Step consumption** tab.

5.  Set **Quantity** to **5.5**.

6.  Click **New**.

7.  Set **From series** to **1400**.

8.  Set **Quantity** to **10.6**.

9.  Click **New**.

10. Set **From series** to **2400**.

11. Set **Quantity** to **15.8**.

12. Click **Save**.

13. Close all pages.

**Date out the old formula and date in the new one**

1.  Go to **Product information management\>Products\>Released products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **P9500**.

3.  In the list, click the link in the selected row for **P9500**.

4.  Click Engineer \> Formula \> **Formula versions**.

5.  In the list, find and select the old formula.

6.  Click **Edit**.

7.  In the **To date** field, set the date to **12/27/2016**.

8.  Click **Save**.

9.  In the list, find and select the new formula.

10. In the **From date** field, set the date to **12/28/2016**.

11. Click **Save**.

**Approve and activate the formula**

1.  Click **Approve**.

2.  In the **Approved by** field, enter or select an employee.

3.  Select the **Do you also want to approve the formula?** option.

4.  Click **OK**.

5.  Click **Activate**.

### Exercise \#9: Set up commodity pricing (Bonus)

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples.

The sales price of the Apple Pie, part P9300, manufactured from this sugar
should be based on a margin of 45 percent and a cost multiple of 1.25 for all
quantities.

The pricing employee wants to set up the cost basis and pricing template for
this scenario. She is not quite sure how to do so and asked for your help.

Can you help?

You will have to do the following:

-   Configure item P9100

-   Create a cost basis

-   Create a pricing template

-   Create a quantity and margin template

-   Complete the inventory parameter setup

-   Set up pricing calculation

#### Steps

**Configure an item**

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the **Quick Filter** to filter on the **Item number** field with a value
    of **P9100**.

3.  On the Action Pane, select **Manage inventory**.

4.  Select **Default order settings**.

5.  Select **Edit**.

6.  In the **Default order type** field, select **Production**.

7.  Select **Save**.

8.  Close all pages.

**Create a cost basis**

1.  Go to **Inventory management \> Setup \> Commodity pricing \> Cost basis
    type.**

2.  Click **New** if necessary.

3.  In the **Cost** basis type field, type **NYMEX**.

4.  In the **Description** field, type **New York Mercantile Exchange**.

5.  Click **Save**.

6.  Close the page.

 

**Create a pricing template**

1.  Go to **Inventory management \> Setup \> Commodity pricing \> Pricing
    template**.

2.  Click **New**.

3.  In the **Pricing template** field, type **Apples**.

4.  In the **Description** field, type **Apples**.

5.  Click **Save**.

 

**Create a quantity and margin template**

1.  Click **Quantity and margin template**.

2.  Click **New**.

3.  In the **Item relation** field, type **P9100**.

4.  In the **Site** field, type **1**.

5.  Set **Cost multiplier** to **1.25**.

6.  Set **Margin percentage** to **45**.

7.  In the **Warehouse** field, type **12**. If its not visible, find it in the
    Dimension fast tab.

8.  Click **Save**.

9.  Close the page.

**Complete the inventory parameter setup**

1.  Go to **Inventory management \> Setup \> Inventory and warehouse management
    parameters**.

2.  Click the **Commodity pricing** tab.

3.  In the **Dimension set** field, enter or select **MA+BU**.

4.  In the **Cost basis type** field, enter or select **NYMEX**.

5.  Select **Yes** in the **Keep BOM/Formula calculations** field.

6.  Right click **Trade agreement** and view details.

7.  Click **New**.

8.  In the **Name** field, type **Price_S**.

9.  In the **Description** field, type **Sales Price Adjustment Journal**.

10. In the **Relation** field, select **Price (sales)**.

11. Click **Save**.

12. Close the page.

13. In the **Trade agreement** field, enter or select **Price_S**.

14. Click **Save**.

15. Close the page.

**Set up pricing calculation**

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Pricing calculation.**

2.  Click **New**.

3.  Note that the **Cost basis type** field is set to **NYMEX**.

4.  In the **Run effective date** field, enter todays date.

5.  In the **Run expiry date** field, enter a date in the future.

6.  Click **Save**.

7.  Close the page.

### Exercise \#10: Change a price calculation and update trade agreements

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples.

The sales price of the applesauce manufactured from the apples is to be based
upon the fluctuations in the pricing of the apples from 2/20/20 to 2/27/20

You will have to do the following:

-   Complete the price calculation

-   Review the price calculation data and create trade agreements

-   Post the trade agreements that are created

#### Steps

**Complete the price calculation**

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Create price and margin data**.

2.  In the Pricing calculation field, enter or select **000001** for NYMEX.

3.  In the Pricing template field, enter or select **Apples**.

4.  Click **OK**.

**Review the price calculation data and create trade agreements**

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \> Price
    margin update**.

2.  If the price calculations completed successfully, you will see your new
    pricing. Click **Lines**.

3.  Click **Update trade agreements**.

4.  Click **OK**.

5.  Close the page.

6.  In the list, find and select the desired record.

7.  Click **Lines**.

8.  Click **Update trade agreements**.

9.  Click **OK**.

10. Close the page.

**Post the trade agreements**

1.  Go to **Sales and marketing \> Prices and discounts \> Trade agreement
    journals**.

2.  Click **Lines**.

3.  Click **Post**.

4.  Click **OK.**

5.  Click **Lines**.

6.  Click **Post**.

7.  Click **OK**.

8.  Close the page.

### Exercise \#11: Setting up a commodity price calculation

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples. The sales price of the
applesauce manufactured from the apples is to be based upon the fluctuations in
the pricing of the apples. The weekly pricing for the week of 02/20/20 and
02/27/20 has been received as 0.14/lb. and 0.15/lb., respectively

You will have to do the following:

-   Create a pricing calculation

-   Enter commodity pricing data

-   Create a pricing calculation

-   Enter commodity pricing data

#### Steps

**Create a pricing calculation**

1.  Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Pricing calculation**.

2.  Click **New**.

3.  In the Cost basis type field, enter or select **NYMEX**.

4.  In the Site field, type **1**.

5.  In the Run effective date field, set the date to **2020-02-20** or your
    local equivalent.

6.  In the **Run expiry date** field, set the date to **2020-02-26** or your
    local equivalent.

7.  Click **Save**.

**Enter commodity pricing data**

1.  Click **Commodity pricing**.

2.  Click **New**.

3.  In the Item number field, type **M9103**.

4.  In the **Warehouse** field, enter or select a value.

5.  Set **New cost** to **0.14**.

6.  Click **Save**.

7.  Close the page.

**Create a pricing calculation**

1.  Click **New**.

2.  In the Cost basis type field, enter or select **NYMEX**.

3.  In the Site field, type **1**.

4.  In the **Run effective date** field, set the date to **2020-02-27.**

5.  In the **Run expiry date** field, set the date to **2020-03-05**.

6.  In the **Previous run** field, enter or select a value.

**Enter commodity pricing data**

1.  Click **Commodity pricing**.

2.  Click **New**.

3.  In the **Item number** field, type **M9103**.

4.  In the **Warehouse** field, enter or select a value.

5.  Set New cost to **0.15**.

6.  Click **Save**.

7.  Close the page.]

### Exercise \#12: Creating PSDS lists, records and file uploads for product compliance

In company USP2, product M7001, sulfur dioxide, has been setup as a regulated
and restricted product. A new PSDS has been obtained from the vendor and must be
attached to the item. Using the attached file, create the PSDS record and
activate it based upon an effective date range of 6/1/2020to 5/31/2020

You will have to do the following:

-   Create a PSDS list

-   Create a PSDS record

-   Upload a PSDS file

#### Steps

**Create a PSDS list**

1.  Go to **Inventory management \> Setup \> Product compliance \> Product
    safety data sheet**.

2.  Click **New**.

3.  In the Country/region field, type **USA**.

4.  Click **Save**.

5.  Close the page.

 

**Create a PSDS record**

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **M7001**.

3.  On the Action Pane, click **Manage inventory**.

4.  Click **Safety data sheet**.

5.  Click **New**.

6.  In the **Document Name** field, type a value.

7.  Select **Yes** in the **Active** field.

8.  In the **Country/region** field, type a value.

9.  In the **Approval** source field, enter or select a value.

10. In the **Major version** field, enter a number.

11. In the **Approval date** field, set the date to **2020-06-01** or your local
    equivalent.

12. In the **Effective date** field, set the date to **2020-06-01**.

13. In the **Expiry date** field, set the date to **2022-05-31**.

14. Click **Save**.

**Upload a PSDS file**

1.  Click **Attach** (the paper clip near the top right).

2.  Click **New**.

3.  Click **File**.

4.  Click **Browse**

5.  Select the MSDS file, or any file to act as it.

6.  In the Restriction field, select **External**.

7.  Click **Save**.

8.  Close the page.

9.  Refresh the page.

10. Click **Open** document.

11. Close the page.

### Exercise \#13: Add reporting details for an item

The product safety manager wants to add reporting details for product M7001, Set
the OSHA Product Name to “Sulfur Dioxide”, and give it a threshold quantity of
5, an EHS reportable quantity of 500, and a TPQ of 500. The CAS number should be
set to 7446-09-5.

The annual usage quantity must also be updated for reporting

You were asked to show the safety manager how to do that.

Can you help?

You will have to do the following:

-   Enter product reporting details

-   Enter the CAS number

-   Update annual usage quantities

#### Steps

**Enter product reporting details**

1.  Go to **Product information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **m7001**.

3.  On the Action Pane, click **Manage inventory**.

4.  Click **Reporting details**.

5.  Click **Edit**.

6.  In the **OSHA product name** field, type **Sulfur Dioxide**.

7.  Set the OSHA threshold quantity to **5**.

8.  Set the EHS reportable quantity to **500**.

9.  Set the EHS threshold planning quantity to **500**.

10. Click **Save**.

**Enter the CAS number**

1.  Click **Item CAS relations**.

2.  In the **CAS number** field, type **7446-09-5**.

3.  In the **CAS name** field, type **Sulfur Dioxide**.

4.  Click **Save**.

5.  Close the page.

**Update annual usage quantities**

1.  Click **Update quantities**.

2.  Close the page.

### Exercise \#14: Create a sales order and printing a PSDS

Product M7001, sulfur dioxide, has been setup as a regulated and restricted
product.

A new request for 100 oz of M7001 from customer US-031 on April 4, 2020 has been
received.

The sales representative wants to enter the sales order and make a note of the
messages received.

Ship the material and verify that the valid PSDS is printed upon posting of the
packing list.

The sales manager is confused about how to do that.

You were asked to help.

Can you help?

You will have to do the following:

-   Create a sales order for item M7001

-   Complete the reservation

-   Post the packing slip and print the PSDS

#### Steps

**Create a sales order**

1.  Go to **Accounts receivable \> Orders \> All sales orders**.

2.  Click **New**.

3.  In the **Customer account** field, type **us-031.**

4.  In the **Warehouse** field (General section), type **11**.

5.  In the **Requested receipt date** field, set the date to a near future date.

6.  Click **OK**.

7.  In the Item number field, type **m7001**.

8.  Set Quantity to **100**.

9.  In the **Unit price** field, enter a number.

10. Click **Save**.

**Complete the reservation**

1.  Click **Inventory**.

2.  Click **Reservation**.

3.  Click **Reserve lot**.

4.  Close the page.

**Post the packing slip and print the PSDS**

1.  Click **Pick and pack \> Post packing slip**.

2.  Click **OK**.

3.  Click **OK**.

4.  Verify that the PSDS was printed if that option was desired.

5.  Close the page.

### Exercise \#15: Create and associate a batch attribute

Company USPI has a new requirement for part P4000, polypropylene pellets, to
test and record the melting point for each batch is needed.

The product definition employee wants to create a batch attribute for the
melting point as an integer attribute with a min of 0 and max of 500

The item specific requirements are 130 – 171° C. Customer  
US-024 requires a melting point of 135 – 165° C for use in their manufacturing
processes.

The product definition employee wants to associate the batch attribute with the
item and the customer with the correct attribute ranges

You were called to help. Can you help the product definition employee?

You will have to do the following:

-   Create a new batch attribute

-   Set the attribute minimum and maximum

-   Associate the batch attribute with  
    the item

-   Set the item attribute minimum and maximum

-   Assign financial dimensions to the item

-   Associate the batch attribute with the customer

-   Set the customer attribute minimum and maximum

#### Steps

**Create a new batch attribute**

1.  Go to **Inventory Management** \> **Setup** \> **Batch** \> **Batch
    attributes**.

2.  Click **New**.

3.  In the **Attribute** field, type **MeltingPoint**.

4.  In the **Description** field, type **Melting Point (C)**.

5.  In the **Attribute** type field, select **Integer**.

**Set the attribute minimum and maximum**

1.  In the **Minimum** field, type **0**.

2.  In the **Maximum** field, type **500**.

3.  In the **Increment** field, type **1**.

4.  Click **Save**.

5.  Close the page.

 

**Associate the batch attribute with the item**

1.  Go to **Product Information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **p4000**.

3.  Click **Product specific** in the Batch Attributes group on the **Manage
    Inventory** tab.

4.  Click **New**.

5.  In the Attribute relation field, select **Melting Point**.

**Set the item attribute minimum and maximum**

1.  In the **Tolerance action** field, select **Not allowed**.

2.  Set **Minimum** to **130**.

3.  Set **Maximum** to **171**.

4.  In the **Target** field, type **150**.

5.  Click **Save**.

6.  Close the page.

**Assign the default financial dimension to the item**

1.  Go to **Product Information management \> Products \> Released products**.

2.  Use the **Quick Filter** to filter on the **Item number** field with a value
    of **M2005**.

3.  Click the link for M2005 to go to the details page.

4.  Click **Edit**.

5.  Expand **Financial dimensions** fasttab, select a product group for the
    **ProductGroup** financial dimension.

6.  Click **Save**.

7.  Close all pages. 

**Associate the batch attribute with the customer**

1.  Go to **Product Information management \> Products \> Released products**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **p4000**.

3.  Click **Customer specific** in the Batch Attributes group on the **Manage
    Inventory** tab.

4.  Click **New**.

5.  In the **Attribute relation** field, enter or select **Melting Point**.

6.  In the **Account selection** field, type **US-024**.

**Set the customer attribute minimum and maximum**

1.  Set **Minimum** to **135**.

2.  Set **Maximum** to **165**.

3.  Click Save.

4.  Close the page.

### Exercise \#16: Create a new batch number and manually record the batch attribute

The inventory manager for company USPI wants to create a new batch number for
part P4000.

He is not sure where to start or what to do.

Can you help?

You will have to do the following:

-   Create a new batch number

-   Manually record the batch attribute data

#### Steps

**Create a new batch number**

1.  Go to **Warehouse management \> Setup \> Inventory \> Batches**.

2.  Click **New**.

3.  In the **Batch number** field, type **GTL0001**.

4.  In the **Item number** field, type **PW4000**.

5.  In the **Manufacturing date** field, enter today’s date.

6.  Click **Save**.

**Manually record the batch attribute data**

1.  On the Action Pane, click **View**.

2.  Click **Inventory batch attributes**.

3.  Click **Load item attributes**.

4.  In the **Attribute value** field, type **163**.

5.  Click **Save**.

6.  Close all pages.

### Exercise \#17: Create quality orders and verify batch attributes

At company USPI, item M2005 is set to have a quality order created upon the
purchase order product receipt.

They would like to:

create a new PO for 500 pounds of material, receive the material, and enter the
information in the quality order that is created.

Verify that the batch attribute data was updated upon completion of the quality
order

They are not sure how to perform this transaction and asked for your help.

Can you help?

You will have to do the following:

-   Create a new purchase order for item M2005

-   Receive the purchase order

-   Complete the quality order

-   Verify the batch attribute data

#### Steps

**Create a new purchase order**

1.  Go to **Procurement and sourcing \> Purchase orders \> All purchase
    orders.**

2.  Click **New**.

3.  In the **Vendor account** field, enter or select **US-102**.

4.  Click **OK**.

5.  In the **Item number** field, type **m2005**.

6.  Set **Quantity** to **500**.

7.  Set the **Unit** price to **6.99**.

8.  Click **Save**.

9.  On the Action Pane, click **Purchase**.

10. Click **Confirm**.

11. Note the purchase order number.

12. Close the page.

 

**Receive the purchase order**

1.  Go to **Inventory management \> Inbound orders \> Arrival overview**.

2.  Expand **Arrival query details**.

3.  Set the value of **Restrict to site** to **1**.

4.  Click **Update**.

5.  In the **Arrival overview profile name** field, enter or select a value.

6.  Click **Update**.

7.  Search for the purchase order created and select the record.

8.  Click **Start arrival** in the **Receipts** FastTab.

9.  Re-select your PO.

10. Click **Journals**.

11. Click **Show arrivals from lines**.

12. Click **Inventory**.

13. Click **Display dimensions**.

14. Select the **Site** check box.

15. Select the **Warehouse** check box.

16. Select the **Batch number** check box.

17. Click **OK**.

18. Right click and view details on the **Batch number** field.

19. Click **New**.

20. In the **Batch number** field, type **GTLB001**.

21. In the **Manufacturing date** field, enter today’s date.

22. Click **Save**.

23. Close the page.

24. Close the **Batches** page.

25. In the **Batch number** field, click on the pencil then enter or select the
    batch that was created (GTLB001).

26. Click **Post**.

27. Click **OK**.

28. Click **Functions**.

29. Click **Product receipt**.

30. In the **Product receipt** field, type a value.

31. Click **OK**.

32. Close the page.

 

**Complete the quality order**

1.  Go to **Inventory Management \> Periodic tasks \> Quality Management \>
    Quality orders**.

2.  Click **Results**.

3.  Click **Edit**.

4.  Set Result quantity to **5**.

5.  Set Test result to **15.4**.

6.  Click **Save**.

7.  Close the page.

8.  Click **Validate**.

9.  In the **Validated by** field, enter or select a value.

10. Click **OK**.

**Verify the batch attribute data**

1.  Click the **Inventory dimensions** tab.

2.  Click to follow the link in the **Batch number** field.

3.  On the Action Pane, click **View**.

4.  Click **Inventory batch attributes**.

5.  Close the page.

### Exercise \#18: Complete a batch reservation using an attribute requirement

At company USPI, part P5000 is set up with internal requirements for batch
attributes.

The operations manager wants to enter the batch order, manufacture the material,
and record the test results.

Then the shipping operator will use the batch reservation form to reserve a
batch based upon the customer testing requirements

They both know that a new customer requirement for customer US-026 must be
created.

A new batch order of 500,000 pounds of material shall be created to meet the
requirements of a sales order from customer US-026.

They called you as the MFG functional consultant to help them achieve this. Can
you help?

You will have to do the following:

-   Create a customer attribute requirement

-   Create a new batch order

-   Process the batch order

-   Complete the quality order

-   Create a sales order

-   Complete the batch reservation and shipment

#### Steps

**Create a customer attribute requirement**

1.  Go to **Released products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **p5000**.

3.  Click **Customer specific**.

4.  Click **New**.

5.  In the **Attribute relation** field, enter or select a value.

6.  In the **Account selection** field, type **us-026**.

7.  Set **Minimum** to **98**.

8.  Click Save.

9.  Close the page.

**Create a new batch order**

1.  Go to **All production orders**.

2.  Click **New batch order**.

3.  In the **Item number** field, type **p5000**.

4.  In the **Delivery** field, enter a date.

5.  Click **Create**.

**Process the batch order**

1.  On the Action Pane, click **Production order**.

2.  Click **Estimate**.

3.  Click **OK**.

4.  Click **Start**.

5.  Click **OK**.

6.  On the Action Pane, click **View**.

7.  Click **Picking list**.

8.  In the list, click the link in the selected row.

9.  In the journal lines, select each row and complete the batch reservation.

10. Click **Inventory**.

11. Click **Reservation**.

12. Click **Reserve lot**.

13. Close the page.

14. Click **Post**.

15. Click **OK**.

16. Close the page.

17. Close the page.

18. On the Action Pane, click **Production order**.

19. Click **Report as finished**.

20. Click **OK**.

**Complete the quality order**

1.  On the Action Pane, click **View**.

2.  Click **Quality orders**.

3.  Click **Results**.

4.  Click **Edit**.

5.  Set Result quantity to **5000**.

6.  Set Test result to **98.5**.

7.  Click **Save**.

8.  Close the page.

9.  Click **Validate**.

10. In the **Validated by** field, enter or select a value.

11. Click **OK**.

12. Close the page.

**Create a sales order**

1.  Go to **All sales orders**.

2.  Click **New**.

3.  In the **Customer account** field, type **us-026**.

4.  Click OK.

5.  In the **Item number** field, type **p5000**.

6.  Set **Quantity** to **500000**.

7.  Click **Save**.

**Complete the batch reservation and shipment**

1.  Click **Inventory**.

2.  Click **Batch reservation**.

3.  Click **Batch attribute search**.

4.  Click **Customer attributes**.

5.  Click **OK**.

6.  Click **Reserve lot**.

7.  Refresh the page.

8.  Close the page.

9.  Click **Post packing slip**.

10. Click **OK**.

11. Close the page.

### Exercise \#19: Set a partial visibility catch weight item

At company USP2, a new catch weight item for sugar in  
20-pound bags must be created as item M7010.

The inventory manager is struggling to do the following:

-   Create the new released product as a partial visibility catch weight item.

-   After creating the item, create a new purchase order for 15 bags.

-   The bags are to be received using the arrival overview process, and the
    total weight for the 15 bags of sugar should be specified

You are the MFG functional consultant and they asked you to help. Can you help?

You will have to do the following:

-   Create the released product and set catch weight conversions

-   Create purchase order for  
    15 bags of item M7010

-   Create and post an arrival journal for the purchase order

#### Steps

**Create the released product and set catch weight conversions**

1.  Go to **Product information management** \> **Products** \> **Released
    products**.

2.  Click **New**.

3.  In the Product number field, type **M7010**.

4.  In the Product name field, type **Sugar in 20 lb. bags**.

5.  In the **Catch weight** field, select **Yes**.

6.  In the **Item model group** field, enter or select a value.

7.  In the **Item group** field, enter or select a value.

8.  In the **Storage dimension** group field, enter or select a value.

9.  In the **Tracking dimension** group field, enter or select a value.

10. In the **Inventory unit** field, type **lb**.

11. In the **Purchase unit** field, type **lb**.

12. In the **Sales unit** field, type **lb**.

13. In the **BOM unit** field, type **lb**.

14. Click **OK**.

15. Click **Unit conversions**.

16. Click the **Inter-class conversions** tab.

17. Click **New** to open the drop dialog.

18. Set **Factor** to **20**.

19. In the **To** unit field, type **lb**.

20. In the **From** unit field, type **bag**.

21. Click **OK**.

22. Close the page.

23. In the **Purchase Unit** field, type **bag**.

24. In the **Price** field, enter a number.

25. In the **CW unit** field, type **bag**.

26. Set the **Minimum** quantity to **19**.

27. Set the **Maximum** quantity to **21**.

28. Click **Save**.

29. Close the page.

**Create a purchase order for 15 bags of item M7010**

1.  Go to **Procurement and sourcing** \> **Purchase orders** \> **All purchase
    orders**.

2.  Click **New**.

3.  In the **Vendor account** field, enter or select a value.

4.  Click **OK**.

5.  In the **Item number** field, type **m7010**.

6.  Set CW quantity to **15**.

7.  On the Action Pane, click **Purchase**.

8.  Click **Confirm**.

9.  Close the page.

**Create and post an arrival journal for the purchase order**

1.  Go to **Inventory management** \> **Inbound orders** \> **Arrival
    overview**.

2.  In the **Arrival overview** profile name field, enter or select a value.

3.  Expand the **Arrival query details** section.

4.  Select **No** in the **Production orders** field.

5.  Select **No** in the **Transfer orders** field.

6.  Select **No** in the **Quarantine orders** field.

7.  Click **Update**.

8.  In the list, find and select the desired record.

9.  Select the **Select for arrival** check box.

10. Click **Start arrival**.

11. Click **Journals**.

12. In the list, find and select the desired record.

13. Click **Journals**.

14. Click **Show arrivals from lines**.

15. Click the **Dimension** tab.

16. Click **Edit**.

17. Click to follow the link in the **Batch number** field.

18. Click **New**.

19. In the **Batch number** field, type a value.

20. In the **Manufacturing** date field, enter a date.

21. In the **Expiration date** field, enter a date.

22. Click **Save**.

23. Close the page.

24. In the **Batch number** field, enter or select a value.

25. Set **Quantity** to **295**.

26. Click **Save**.

27. Click **Post**.

28. Click **OK**.

29. Post Product Receipt and review Inventory 

30. Click **Functions**.

31. Click **Product receipt**.

32. In the **Product receipt** field, type a value.

33. Click **OK**.

### Exercise \#20: Use catch weight items in a purchase trade agreement

At company USP2, item number M9401, Cheese, requires a new purchase trade
agreement to be set up for \$175/tray.

The team wants to enter a new demand forecast for 25 trays of cheese to be sold.

After entering the trade agreement and demand forecast, they want to enter and
confirm a new purchase order for 15 trays.

Finally, master planning should be run and reviewed to determine if additional
trays should be purchased

The team is not sure how to do that. They asked for your help. Can you help?

You will have to do the following:

-   Create a purchase trade agreement

-   Create a demand forecast

-   Create a purchase order for  
    15 trays of item M9401

-   Run net requirements and review the output

#### Steps

**Create a purchase trade agreement**

1.  Go to **Product information management** \> **Products** \> **Released
    products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **m9401**.

3.  On the Action Pane, click **Purchase**.

4.  Click **Create trade agreements**.

5.  Click **Edit**.

6.  In the **Name** field, enter or select a value.

7.  Click **Lines**.

8.  In the **Item relation** field, type **M9401**.

9.  In the **Site** field, type **1**.

10. In the Warehouse field, type **11**.

11. Set **Amount in currency** to **175**.

12. Click **Post**.

13. Click **OK**.

14. Close the page.

**Create a demand forecast**

1.  On the Action Pane, click **Plan**.

2.  Click **Demand forecast**.

3.  Click **New**.

4.  In the **Model** field, enter or select a value.

5.  In the **Date** field, enter a date.

6.  In the **Site** field, type **1**.

7.  In the Warehouse field, type **11**.

8.  Set **CW quantity** to **25**.

9.  Click **Save**.

10. Close the page.

**Create a purchase order for 15 trays of item M9401**

1.  Go to **Procurement and sourcing** \> **Purchase orders** \> **All purchase
    orders**.

2.  Click **New**.

3.  In the **Vendor** account field, enter or select a value.

4.  Click **OK**.

5.  In the **Item number** field, type **m9401**.

6.  Set **CW quantity** to **15**.

7.  Click **Confirm**.

**Run net requirements and review the output**

1.  Click **Product and supply**.

2.  Click **Net requirements**.

3.  Click **Update**.

4.  Click **Master planning**.

5.  Click **OK**.

### Exercise \#21: Create a batch attribute for a potency item

At company USPI, part number M2004, ETDA, must be designated a
potency-controlled item for the Acidity batch attribute.

The target value for Acidity should be 1.7. Set up the batch attribute, assign
it to the product, and designate the product as a potency item.

The product manager is not sure how to configure the system to do that.

You were called as the MFG functional consultant to help.

Can you help?

You will have to do the following:

-   Create a batch attribute

-   Assign the attribute to  
    the item

-   Assign potency information

#### Steps

**Create a batch attribute**

1.  Go to **Inventory management** \> **Setup** \> **Batch** \> **Batch
    attributes**.

2.  Click **New**.

3.  In the **Attribute** field, type **Acidity**.

4.  In the **Description** field, type **Acidity**.

5.  In the **Attribute** type field, select **Fraction**.

6.  In the **Maximum** field, type **10**.

7.  In the **Increment** field, type **.01**.

8.  Click **Save**.

9.  Close the page.

**Assign the attribute to the item**

1.  Go to **Product information management** \> **Products** \> **Released
    products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **M2004**.

3.  On the Action Pane, click **Manage inventory**.

4.  Click **Product specific**.

5.  Click **New**.

6.  In the **Attribute relation** field, select **Acidity**.

7.  Set **Minimum** to **1**.

8.  Set **Maximum** to **3**.

9.  In the **Target** field, type **1.7**.

10. Click **Save**.

11. Close the page.

**Assign potency information**

1.  Click **Edit**.

2.  Click **Save**.

3.  In the **Base attribute** field, enter or select a value.

4.  Click **Save**.

### Exercise \#22: Modify and activate a copy of a potency item formula

At company USPI, were reviewing al their items and they found out that part
M2004 has been determined to be a potency-controlled item.

The formula for item P2000 needs to be adjusted to set M2004 as an active
potency item.

The formula for P2000 should be modified to indicate the change, and item M2007
should be set as a compensating material for part M2004 with a compensation
factor of 1

They are not sure how to reflect this in the system and they called you to help.

Can you help?

You will have to do the following:

-   Copy the formula for item P2000

-   Modify the M2004 and  
    M2007 lines

-   Approve and activate the formula

#### Steps

 

**Copy the formula for item P2000**

1.  Go to **Product information management** \> **Products** \> **Released
    products**.

2.  Use the Quick Filter to filter on the **Item number field** with a value of
    **'p2000'**.

3.  On the Action Pane, click **Engineer**.

4.  Click **Formula versions**.

5.  Click **New**.

6.  Click **Formula and formula version**.

7.  In the **Name** field, type a value.

8.  Select **Yes** in the **Copy** field.

9.  In the **Site** field, enter or select a value.

10. Click **OK**.

11. In the **Formula version** field, enter or select a value.

12. Click **OK**.

**Modify the M2004 and M2007 lines**

1.  In the list, select row M2004.

2.  In the Ingredient type field, select **'Active'**.

3.  In the list, select row M2007.

4.  In the Ingredient type field, select **'Compensating'**.

5.  Click **Save**.

6.  Click **Ingredients**.

7.  Click **Compensation principle**.

8.  In the Active ingredient field, select **M2004**.

9.  Click **OK**.

10. Close the page.

**Approve and activate the formula**

1.  In the list, select the old formula version.

2.  In the **To date** field, enter a date.

3.  In the list, select the new formula version.

4.  In the **From date** field, enter a date.

5.  Click **Approve**.

6.  In the **Approved by** field, enter or select a value.

7.  Click **Select**.

8.  Select **Yes** in the **Do you also want to approve the formula?** field.

9.  Click **OK**.

10. Click **Activate**.

 

### Exercise \#23: Set up pricing based on an item’s attribute (Bonus)

At company USPI, part M2004 has been determined to be a potency-controlled item.

The pricing of part M2004 shall be based upon the acidity level, where the ratio
of the actual acidity level against the target is multiplied by the based price
of \$4.70 and a constant of 1.5 to determine the purchase price of the batch.

the purchase agent, want to setup the pricing for  
the item and couldn’t.

The support team asked you to help the purchase agent.

Can you help?

You will have to do the following:

-   Create an attribute pricing expression

-   Complete and post the trade agreement

#### <br> Steps

**Create an attribute pricing expression**

1.  Go to **Procurement and sourcing** \> **Setup** \> **Prices and discounts**
    \> **Attribute-based pricing details**.

2.  Click **New**.

3.  In the **Name** field, type a value.

4.  In the **Description** field, type a value.

5.  Click **Add variable**.

6.  In the **Equation element type** field, select **Unit price**.

7.  Click **Add variable**.

8.  In the **Equation element type** field, select **Constant**.

9.  Set **Constant** to **1.5**.

10. Click **Add variable**.

11. In the **Equation element type** field, select **Batch attribute - Target**.

12. In the **Attribute** field, select **Acidity**.

13. Click **Add variable**.

14. In the **Equation element type** field, select **Batch attribute - Actual**.

15. In the **Attribute** field, select Acidity.

16. In the **Equation** field, type **AB(D/C)**.

17. Click **Validate equation**.

18. Close the page.

 

**Complete and post trade agreement**

1.  Go to **Product information management** \> **Products** \> **Released
    products**.

2.  Use the Quick Filter to filter on the **Item number** field with a value of
    **m2004**.

3.  On the Action Pane, click **Purchase**.

4.  Click **Create trade agreements**.

5.  Click **Edit**.

6.  In the **Name** field, select **Price**.

7.  Click **Lines**.

8.  In the **Item relation** field, type **M2004**.

9.  In the **Site** field, type **1**.

10. In the **Warehouse** field, type **11**.

11. Set **Amount in currency** to **4.7**.

12. In the **Attribute-based pricing ID** field, enter the pricing ID just
    created.

13. Click **Save**.

14. Click **Post**.

15. Click **OK**.

16. Close the page.

### Exercise \#24: Record a potency attribute upon receipt (Bonus)

A new batch of item M2004 is to be purchased into inventory and received, with
the batch attribute result being entered upon receipt.

You were asked to review the pricing of M2004 to verify that the calculation
meets the requirements of the attribute-based pricing

Can you perform this task?

You will have to do the following:

-   Create a purchase order for item M2004

-   Receive and enter a batch attribute value

-   Invoice and review pricing

#### Steps

**Create a purchase order**

1.  Go to **Procurement and sourcing** \> **Purchase orders** \> **All purchase
    orders**.

2.  Click **New**.

3.  In the **Vendor account** field, enter or select a value.

4.  In the **Warehouse** field, select **13**.

5.  Click **OK**.

6.  In the **Item number** field, type **m2004**.

7.  Set **Quantity** to **800**.

8.  On the Action Pane, click **Purchase**.

9.  Click **Confirm**.

 

**Receive and enter a batch attribute value**

1.  On the Action Pane, click **Receive**.

2.  Click **Product receipt**.

3.  In the **Product receipt** field, type a value.

4.  Click **Update line**.

5.  Click **Registration**.

6.  Click **Add registration line**.

7.  Click to follow the link in the **Batch number** field.

8.  Click **New**.

9.  In the **Batch number** field, type a value.

10. Click **Save**.

11. Close the page.

12. In the **Batch number** field, select the batch created.

13. In the **Actual value** field, type a value.

14. Click **Confirm registration**.

15. Click **Save**.

16. Close the page.

**Invoice and review pricing**

1.  In the **Quantity** field, select **Registered quantity**.

2.  Click **OK**.

3.  On the Action Pane, click **Invoice**.

4.  Click **Invoice**.

5.  In the **Number** field, type a value.

6.  In the **Invoice date** field, enter a date.

7.  Click **Update match status**.

8.  Click **Post**.

9.  Click **Inventory**.

10. Click **Transactions**.

### Exercise \#25: Reporting and balancing batch orders (Bonus)

A new batch order is to be created for part P2000, including reserving batches
of the active ingredients, performing batch balancing, and posting the picking
list.

The production manager wants to create a production order and process the order
for a new batch of part P2000

The production manager is new to the system and wants you help.

Can you help?

You will have to do the following:

-   Create a batch order for part P2000 and process the batch order through
    Start

-   Complete batch reservation and balancing for active ingredients

-   Post the picking list and report as a finished batch order

#### Steps

**Create a batch order for part P2000 and process the batch order through
Start**

1.  Go to **Production control** \> **Production orders** \> **All production
    orders**.

2.  Click **New batch order**.

3.  In the **Item number** field, type **p2000**.

4.  Click **Create**.

5.  On the Action Pane, click **Production order**.

6.  Click **Estimate**.

7.  Click **OK**.

8.  Click **Start**.

9.  Click **OK**.

**Complete Batch Reservation and Balancing for active ingredients**

1.  Click **Batch balancing**.

2.  In the list, select row 2.

3.  Select the **Marked** check box.

4.  In the list, select row 4.

5.  Select the **Marked** check box.

6.  In the list, select row 5.

7.  Select the **Marked** check box.

8.  Click **Balance batch ingredients**.

9.  Click **Confirm the formula**.

10. Click **OK**.

**Post the picking list and report as a finished batch order**

1.  On the Action Pane, click **View**.

2.  Click **Picking list**.

3.  In the list, click the link for the picking list.

4.  Click **Post**.

5.  Click **OK**.

6.  Close the page.

7.  Close the page.

8.  On the Action Pane, click **Production order**.

9.  Click **Report as finished**.

10. Click to follow the link in the **Batch number** field.

11. Click **New**.

12. In the **Batch number** field, type a value.

13. In the **Manufacturing date** field, enter a date.

14. Click **Save**.

15. Close the page.

16. In the **Batch number** field, select the created batch number.

17. Click **OK**.

Case study 1C Lean manufacturing
--------------------------------

### Exercise \#1: Create value streams

After defining and mapping the lean manufacturing value stream for USMF, you are
told to act as the value stream manager. You must create the value stream within
Microsoft Dynamics 365 Supply Chain Management

Can you do that?

You will have to do the following:

-   Create a value stream

#### Steps

1.  Go to **Production control \> Setup \> Lean production flow \> Value
    streams**.

2.  Click **New** to create a new value stream.

3.  Enter the following details for the new value stream:

4.  Name: **SeaLeanVS**

5.  Search Name: **SeaLean**

6.  Manager: **Jodi Christiansen**

7.  Click **Save**.

### Exercise \#2 create a new production flow model

As the production (shop) floor supervisor at USMF,  
you have a logical grouping of work cell capacity with similar behavior in
capacity load for the work cells used to model the car speaker production flow

You must create a new production flow (SeaPFModel) to model the process of
painting the covers for the car speakers. The capacity and load of the
production flow will be measured in quantities of product that are produced
(Throughput)

The Cycle for this production flow will define 1 day as the number of days used
in automatic planning (i.e., EPE cycle is 1 day). The Add method of Kanban
scheduling will be used if there is no capacity available during the required
periods; the planning period type is Day and the planning time fence is 10. To
the right are more details you will need for this task

-   Name: eBookProdFlow

-   Description: eBook Production Flow

-   Legal entity: USMF

-   Value stream: SeaLeanVS

-   Production group: 10

-   Per cycle unit of measure: pcs

-   Quantity per cycle: 1

-   Average takt time: 1

-   Minimum takt time: 1

-   Maximum takt time: 2

-   Period for actual cycle time (days): 1

You will have to do the following:

-   Create a production flow model for SeaPFModel

-   Create a production flow version for the USMF eBook production flow

-   Set up the Takt and cycle times

#### Steps

**Create a production flow model**

1.  Go to **Production control \> Setup \> Lean production flow \> Production
    flow models.**

2.  Click **New**.

3.  In the **Production flow model** field enter **SeaPFModel**.

4.  In the **Model type** field enter **Throughput**.

5.  In the **EPE Cycle in days** field enter **1**.

6.  In the **Capacity shortage reaction** field enter **Add**.

7.  In the **Planning period type** field enter **Day**.

8.  In the **Planning time fence** field enter **10**.

9.  In the **Capacity shortage reaction** drop down select **Postpone**.

10. Click **Save**.

**Create a production flow version**

1.  Navigate to **Production control \> Setup \> Lean production flow \>
    Production flows**.

2.  Click **New** on the action pane. A new production flow record is created.

3.  In the **Name** field, enter **eBookProdFlow**.

4.  In the **Description** field, enter **eBook Production Flow**.

5.  In the **Legal entity** field, select **USMF**.

6.  In the **Value stream** field, select **LeanProduction**.

7.  In the **Production group** field, select **10**.

8.  Click **Save**.

9.  On the **Versions** FastTab, click **Add**.

10. Click **OK**.

**Set up the takt and cycle times**

1.  Expand the **Versions** and **Version details** FastTabs.

2.  In the **Per cycle unit of measure** field, select **pcs**.

3.  In the **Quantity per cycle** field, enter **1**.

4.  In the **Average takt time** field, enter **1**.

5.  In the **Minimum takt time** field, enter **1**.

6.  In the **Maximum takt time** field, enter **2**.

7.  In the **Period for actual cycle time** (**days**) field, enter **1**.

8.  Click **Save** in the action pane.

9.  Note the **Plan status** field for the version is set to **Draft**.

10. Close all forms.

### Exercise \#3: Create a process activity

A new eBook stylus is being developed to compliment the eBook kits that are sold
at USMF.

The stylus is purchased from an outside vendor and configured at USMF.

A process activity is needed to configure the stylus and place it in stock for
use elsewhere.

Here are the details for the process activity:

-   Name: Transfer Activity

-   Process quantity: 10 pcs

-   Operating unit: Lean Production

-   Work cell: 1260

The company is not sure how to configure this and you were called as the MFG
functional consultant to help.

Can you help?

You will have to do the following:

-   Create a process activity

#### Steps

1.  Navigate to **Production Control \> Setup \> Lean Production Flows \>
    Production flows**.

2.  Open the **Mid Range Speaker 2PF** production flow.

3.  On the **Versions** FastTab, click the **Activities** button.

4.  Click **Create new plan activity** button.

5.  Click **Next**.

6.  Enter **Transfer Activity** in the **Name** field.

7.  Enter **10** in the **Process quantity** field.

8.  In the **Unit** drop-down list, select **pcs**.

9.  In the **Operating unit** drop-down list, select **LeanProduction**.

10. Click **Next**.

11. In the **Work cell** replenished drop-down list, select **1260**.

12. Set the **Update on hand on receipt** option to **Yes**.

13. Click **Next**.

14. Select **1260** in the **Replenishing** field.

15. Select **Finished product** in the **Product type** field.

16. Click **Next.**

17. Select Warehouse **13** in the **Transfer from location – warehouse** field.

18. Select location **13** in the **Transfer from location – location** field.

19. For the transfer to location:

20. Select **22** in the **Warehouse** field.

21. Select location **01-01-2-1** in the **Location** field.

22. Select **Shipper** in the **Freighted by** field.

23. Click **Next.**

24. Select **Queue time after** record.

25. Enter **4** in **time** field.

26. Select **hr** in the **time unit** field.

27. Enter **10** in **per quantity** field.

28. Select the **Runtime** record.

29. Enter **2** in **time** field.

30. Select **hr** in **time unit** field.

31. Enter **10** in **per quantity** field.

32. Click **Next.**

33. Click **Finish.**

### Exercise \#4 Create a new transfer activity

A new car speaker remote is being developed to complement the car speaker kits
sold at Contoso. The Standard speaker assembly production flow needs to be
amended to include a transfer activity to move the configured remote to the
Electrical Component warehouse

Details for production flow transfer activity are to the right

-   Name: RemoteTransfer

-   Process quantity: 10

-   Operating unit: SeaLeanVS

-   Replenishing resource group: 1250

-   Update on hand on receipt: Yes

-   Update on hand on pick: No

Transfer to warehouse ElComp, location Output

Freighted by shipper

-   Runtime: 1 min per 25 pcs

You will have to do the following:

-   Deactivate the current production flow version

-   Create a new transfer activity

-   Create the predecessor/successor relationship between the process and
    transfer activity with no constraints

#### Steps

**Deactivate the current production flow version**

1.  Navigate to **Production Control \> Setup \> Lean manufacturing \>
    Production flows.**

2.  Open the **CarSpeakProdFlow Standard speaker assembly** production flow.

3.  On the **Versions** FastTab, select Version **1**.

4.  Click **Deactivate**.

5.  Click **OK**.

**Create a new transfer activity**

1.  On the **Versions** FastTab, click **Activities**. The **Production flow
    activities** form opens.

2.  Click **Create new plan activity** in the action pane.

3.  Click **Next**.

4.  Enter **RemoteTransfer** in the **Name** field.

5.  In the **Activity type** drop-down list, select **Transfer**.

6.  Enter **10** in the **Process quantity** field.

7.  In the **Unit** drop-down list, select **pcs**.

8.  In the **Operating unit** drop-down list, select **SeaLeanVS**.

9.  Click **Next**. The **Create transfer activity** page opens.

10. In the **Replenishing** drop-down list, select **1250**.

11. Set the **Update on hand on receipt** check box to **Yes**.

12. Set the **Update on hand on pick** check box to **No**.

13. In the **Product type** field, select **Finished product**.

14. Click **Next**. The **Assign transfer locations** page opens.

15. In the **Transfer to location** group, in the **Warehouse** drop-down list,
    select **ElComp 11**.

16. In the **Location** drop-down list, select **Output 11**.

17. In the **Freighted by** drop-down list, select **Shipper**.

18. Click **Next**. The **Assign** activity **time** page opens.

19. In the **Time** field for the **Runtime** row, enter **1**.

20. In the adjacent **Time unit** drop-down list, select **min**.

21. In the **Per quantity** field, enter **25**.

22. Click **Next**. The **Confirm selection** page opens.

23. Click **Finish**. The wizard closes, and a new production flow activity
    appears in the list.

24. Click **Save** in the action pane.

**Create the predecessor/successor relationship between the process and transfer
activity with no constraints**

1.  Highlight the **RemoteConfig Wiring Process** activity and, on the
    **Successor** tab, click the **Add successor** button.

2.  Select the **Successor Activity** of **RemoteTransfer**.

3.  For Cycle time ration, type 1.

4.  Select the **OK** button.

5.  Activate the production flow version.

6.  Close the **Production** flow activities form.

7.  On the **Versions** tab, click the **Activation \> Activate** menu button.

8.  Click **OK**.

### Exercise \#5: Add a successor to the production flow activity and perform validation and activation

The production Manager wants to revise Mid-Range Speaker 2 PF production flow so
that the Transfer_W12_to_W11 activity is succeeded by the Process_Activity_1
activity.

Here are the details for production flow transfer activity relations:

-   Constraint: 1 hour

-   Cycle time ratio: 2

He is not quite sure how to do this revision and wants your help.

Can you help?

You will have to do the following:

-   Add a successor to the production flow activity

-   Perform validation and activation

#### Steps

**Add a successor to the production flow activity**

1.  Navigate to **Production control** \> **Setup** \> **Lean production flow**
    \> **Production flows**.

2.  Click the name of the Mid-Range Speaker 2 PF production flow.

3.  On the **Versions** FastTab, click **Activities**.

4.  In the list on the left, select the **00074 – Transfer from Warehouse 13 to
    51** activity.

5.  On the **Successors** FastTab, click **Add successor**. The **Create
    activity relation** dialog opens.

6.  In the **Successor** group, in the **Activity** drop-down list, select
    Activity **000082**.

7.  Select the **Constraint** check box.

8.  In the **Constraint value** field, enter **1**.

9.  In the **Units** drop-down list, select **hr**.

10. In the **Cycle time ratio** field, enter **2**.

11. Click **OK**.

12. Click **Save** in the action pane.

13. Close the forms.

**Perform validation and activation**

The Mid-Range Speaker 2 PF production flow, Version 2 must be validated to
confirm that the changes have been correctly implemented.

1.  Navigate to **Production control \> Setup \> Lean production flow \>
    Production flows.** The Production flows form opens.

2.  Click the name of the Mid-Range Speaker 2 PF production flow. The
    **Production Flows** form for the selected production flow opens.

3.  On the **Versions** FastTab, select Version **1**.

4.  Click **Validate**. The **Validate production flow** dialog opens.

5.  Click **OK**.

6.  Click **Save** in the action pane.

7.  Close the forms.

### Exercise \#6: Create Kanban rules and schedule the Kanban job

A new car speaker remote has been developed to complement the car speaker kits
that are sold at USMF. The production flow is already configured with multiple
activities, and now the products and Kanbans required to process the flow must
be created

Products have been set up for the purchased un-programmed remote and for the
remote that will be programmed through the activities of the production flow.

The bill of materials (BOM) has also been created, adding the purchased
unprogrammed remote as a BOM line.

Once the BOM is created, Kanban rules must be set up for the process activity to
program the remote and for the transfer activity to transfer the programmed
remote (now a finished good) to the warehouse and location where it will be
stored until it is sold

When the Kanban jobs are not automatically planned, they must be dragged and
dropped onto the desired period on the Kanban schedule board. You can do that by
using the Kanban board

The company called you to configure the above. Can you help?

You will have to do the following:

-   Create the Kanban rule for the process activity

-   Create the Kanban rule for the transfer activity

-   Plan a Kanban on the Kanban board

#### Steps

**Create the Kanban rule for the process activity**

1.  Navigate to **Product information management \> Lean manufacturing \> Kanban
    rules**.

2.  Click **New**.

3.  Select the **First plan activity** called **SpeakerTestAndPackaging**.

4.  Expand the **Details** FastTab.

5.  In the **Product**, select **L0001**.

6.  Expand the **Quantities** FastTab

7.  Enter a **Default quantity** of **100**.

8.  Enter a **Fixed Kanban quantity** of **4**.

9.  Expand the **Kanban and cards** FastTab.

10. Select the **Circulating cards** check box.

11. Change the **Card assignment** to **Automatic**.

12. Click **Save**.

13. Click the **Create cards** button.

14. Deselect the **Print new cards** box.

15. Click **Create**.

16. Switch to the **Kanbans** FastTab.

17. Click **Add**.

18. Verify that the default number of new Kanbans is 4.

19. Click **Create**.

20. Close all forms.

**Creating the Kanban rule for the transfer activity**

1.  Navigate to **Product information management \> Lean manufacturing \> Kanban
    rules**.

2.  Click **New**.

3.  Change the **Type** to **Withdrawal**.

4.  Update the **First plan activity** to **ReplenishSpeakerComponents**.

5.  Expand the **Details** FastTab.

6.  Enter the **Product L0001**.

7.  Switch to the **Quantities** FastTab.

8.  Enter the **Default quantity** of **10**.

9.  Enter the **Fixed Kanban quantity** of 4**.**

10. Click **Save**.

11. Switch to the **Kanbans** FastTab.

12. Click **Add**.

13. Verify that the number of new Kanbans defaults to 4.

14. Click **Create**.

15. Close all forms.

**Planning a Kanban on the Kanban Board**

1.  Navigate to **Production control \> Kanban \> Kanban job scheduling**.

2.  Change Work cell to **1250**.

3.  In the **Display job status** field select **Not scheduled**.

4.  Select a Kanban job from the unplanned Kanban jobs, and then click the
    **Schedule** button. Repeat for the remaining Kanban jobs of your choice.

### Exercise \#7: Process scheduled Kanbans for process and transfer jobs

After setting up the fixed Kanban rule from the previous exercise, the company
wonders if you can use the Kanban board to start processing scheduled Kanban
jobs.

Can you?

You will have to do the following:

-   Process Kanbans on the Kanban board for process jobs

-   Process Kanbans on the Kanban board for transfer jobs

#### Steps

**Process Kanbans on the Kanban board for process jobs**

The scheduled Kanbans are now ready to be processed. The **Production
control\>Kanban\>Kanban board for process jobs** will be used to prepare, start,
and complete the Kanbans.

1.  Go to **Production control \> Kanban \> Kanban board for process jobs**.

2.  When you open this form for the first time, all jobs from all work cells are
    shown. You can select the **Work cell** to filter the jobs.

3.  Change the **Work cell** to **1250**.

4.  Select the appropriate Kanbans to prepare.

5.  Click **Prepare**.

6.  To start the Kanbans, click **Start** button.

7.  To complete the Kanbans, click **Complete**.

**Process Kanban on the Kanban board for transfer jobs**

The manufactured Kanban is now ready to be transferred to its final location.
The Kanban board for transfer jobs will be used to start and complete the
Kanban.

1.  Go to **Production control \> Kanban \> Kanban board for transfer jobs**.

2.  When entering the board for the first time you see all jobs from all
    production flows. Alternately, you can expand **Filters** FastTab and change
    **Production flow** to only show jobs for a specific production flow, such
    as Mid-Range Speaker 2 PF.

3.  Select the Kanbans of your choice, as long as they have a card number.

4.  To start the transfer, click **Start**.

5.  To complete the transfer, click **Complete**.

### Exercise \#8: Fulfill a sales order by planning a Kanban and produce an item (Bonus)

A sales order has been received for a green speaker set, which triggers event
Kanbans for the speaker set on the packaging work cell and the speaker kits on
the speaker assembly work cell.

The company want to record the production of the speaker kits and speaker set to
fulfil the customer sales order

How would you do that?

You will have to do the following:

-   Create a sales order for the Kanban line event

-   Plan the Kanbans

-   Transfer the speaker set

#### Steps

**Create a sales order**

1.  Navigate to **Sales and marketing \> Sales orders \> All sales orders**.

2.  Click **New**.

3.  Select the **Customer account** as **US-016**.

4.  Click **OK**.

5.  Enter **Item number** of “**L0026**”.

6.  Enter **Quantity** of “**12.00**”.

7.  Click **Update confirmed date**.

8.  Select a **Site** of **1** (scroll or tab right).

9.  Select a **Warehouse** of **13**.

10. Select a **Location** of **13**.

11. If **Location** is not set on the sales order, go to **Sales order line** \>
    **Display** and click the **Dimensions** button. Click on the location and
    configuration.

12. Select Configuration 01.

13. When you save, if the date cannot be promised, select **Update confirmed
    ship date**.

14. Select the **Product and supply \> View pegging tree** menu button to view
    the event Kanbans created for the sales order.

**Plan the Kanbans**

1.  Navigate to **Production control \> Kanban \> Kanban schedule board**.

2.  Change **Work cell** to **1250**.

3.  Plan the Kanban for 1250 by selecting the Kanban job in the board.

4.  Close all forms.

5.  Navigate to **Production control \> Kanban \> Kanban board for process
    jobs**.

6.  Select the Change cell button.

7.  Change **Work cell** to **1250**.

8.  Highlight the desired Kanbans and click **Start**.

9.  Click **Complete**.

10. Select the **Change cell** button.

11. Change **Work cell** to **1250**.

12. Highlight a Kanban and switch to the **Pegging** FastTab on the **Kanban
    board for process jobs** work cell form. View the complete lower level
    speaker set Kanbans on the pegging tree.

13. Click **Start**.

14. Click **Complete**.

**Transfer the speaker set**

1.  Navigate to **Production control \> Kanban \> Kanban board for transfer
    jobs**.

2.  Expand **Filters** FastTab.

3.  Select a **Production Flow**.

4.  Click **Update picking list** on the Transfer tab in the action pane.

5.  Click **Add picking** line.

6.  Click **Confirm** pick all.

7.  Close the form.

8.  Select **Start**.

9.  Select **Complete**.
