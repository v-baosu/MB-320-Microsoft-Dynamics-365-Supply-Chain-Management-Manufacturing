---
lab:
    title: 'Case study 1A Discrete, Process and Lean manufacturing features'
    module: 'Module 2 Manage manufacturing processes'
---

# Module 2 Manage manufacturing processes

## Case study 1A Discrete, Process and Lean manufacturing features

### Exercise \#1: Update the production control parameters

When you are starting to use the Production control module, you are required to
do some configurations that will help the system operate according to your
design and process design

The Operations manager at USMF,  wants to make some changes to the policies so
everything runs more efficiently. He wants to be sure routes are not allowed to
be modified or have their approvals removed. In order to accomplish this, a new
route operation should be created, and the effective dates updated.

Can you help the operation manager to perform this?

You will have to do the following:

- Update the production control parameters

#### Steps

1. Go to **Production control \> Setup \> Production control parameters**.

2. Set the **Block removal of approval** slider to **Yes** under the **Routes** group.

3. Set the **Block editing** slider to **Yes** under the **Routes** group.

4. Select **Save**.

5. **Close** all pages.

### Exercise \#2: Create new production pools

USFM has been getting reports from the customers that orders are not arriving on
time and that some of the delivered orders are missing pieces. One of the
supervisor wants you to determine what is causing these problems so the company
can find a solution.

You decide that you want more visibility into production orders that are
delayed, and you want to track subcontracted production orders that are missing
deliveries, production orders with missing materials and orders that are delayed
due to machine failures.

How would you perform this?

You will have to do the following:

- Production pool for Delayed sub contracted work

- Production pool for missing materials

- Production pool for machine failures

#### Steps

#### **Create a production pool for delayed subcontracted work**

1. Open **Production control \> Setup \> Production \> Production pools**.

2. Select **New** to create a new pool.

3. Enter or select **Delay-Sub** in the **Pool** field.

4. Enter or select **Subcontracted Work Delayed** in the **Name** field.

#### **Create a production pool for missing materials**

1. Select **New** to create a new pool.

2. Enter or select **MATMISSING** in the **Pool** field.

3. Enter or select **Materials Missing** in the **Name** field.

#### **Create a production pool for machine failures**

1. Select **New** to create a new pool.

2. Enter or select **MACHFAIL** in the **Pool** field.

3. Enter or select **Machine Failure** in the **Name** field.

4. Select **Save**.

5. Close all pages.

### Exercise #3: Create and manage resources

Company USMF has bought a new packing robot that will reduce the need for manual
labor in the speaker packing workshop.

Workers from this group can therefore be reassigned to perform other work as the
new robot becomes fully operational.

You were asked to add the robot as a resource

How would you perform this?

You will have to do the following:

- Create capabilities

- Assign resource to capabilities

- Assign capabilities to a resource

#### Steps

#### **Create capabilities**

1. Go to **Organization administration \> Resources \> Resource capabilities**.

2. Select **New** from the Navigation bar.

3. Enter or select **GTL-Assembly** in the **Capability** field and **Assembly** in the
    **Description** field.

4. Select **New**.

5. Enter or select **GTL-Packing** in the **Capability** field and **Packing** in the
    **Description** field.

6. Close the **Resource capabilities** page.

#### **Assign resources to capability**

1. Go to **Organization administration \> Resources \> Resource capabilities**.

2. Select **GTL-Assembly** from the list of capabilities.

3. Select **Add** from the toolbar.

4. Select **5110**, Assembly worker 1, in the **Resource** field.

5. Accept the default **Expiration** date of **Never**.

6. Enter or select **1** in the **Priority** field.

7. Accept the default **Level** of 0.00.

8. Repeat steps 3 to 7, for the resource 5111.

9. Close the **Resource capabilities** page.

#### **Assign capabilities to a resource**

1. Go to **Organization administration \> Resources \> Resources**.

2. Select resource 5111 in the grid.

3. Expand the **Capabilities** FastTab.

4. Select **View \> All** from the toolbar.

5. Select **Add** from the toolbar.

6. Enter or select GTL-Packing in the **Capability** field.

7. Accept the default **Effective** date of today's date.

8. Accept the default **Expiration** date of **Never**.

9. Accept the default **Level** of 0.00.

10. Enter or select **2** in the **Priority** field

11. Close the **Resources** page.

### Exercise \#4: Create an operation, assign relations and create a route

The company you are consulting has decided to produce a series of ebooks for a
client.

The production manager at USMF, wants to create an operation for the finished
good, assign relations, and create a route

Can you help the production manager?

You will have to do the following:

- Create and configure an operation

#### Steps

1. Go to **Production control \> Operations \> All routes**.

2. Select **New**.

3. In the **Name** field, enter or select **eBook route**.

4. In the **Item group** field, enter or select **TV&Video**.

5. Select **Save**.

6. Select **Route** on the Action Pane then in the **Maintain** group, select **Route details**.

7. Select **New**.

8. In the **Operation** field, enter or select **Assembly**.

9. In the **Next** field, enter **20**.

10. In the **Link type** field, select **Soft**.

11. Select **New**.

12. In the **Oper. No.** field, enter **20**.

13. In the **Operation** field, enter or select **Padding**.

14. In the **Next** field, enter **30**.

15. In the **Link type** field, select **Hard**.

16. Select **New**.

17. In the **Oper. No**. field, enter **30**.

18. In the **Priority** field, select **Primary**.

19. In the **Operation** field, enter or select **Packing**.

20. Refresh the page.

21. Select **Save**.

22. **Close** all pages.

    > **NOTE** The message bar may appear with a message that states, "*There exist no relation for operation Padding.*" The route contains the order of operations and the assignment of operations will occur in the next steps.

23. Go to **Production control \> Setup \> Routes \> Operations**.

24. Select **New**.

25. In the **Operation** field, enter or select **eBook**.

26. In the **Name** field, enter or select **eBook assembly**.

27. Select **Relations**.

28. Select **New**.

29. In the **Route group** field, enter or select **Discrete**.

30. Expand the **Setup** section.

31. In the **Formula** field, select **Capacity**.

32. In the **Costing resource** field, enter or select **1211**. A dialogue box appears informing that the default time and cost values from the costing resource will be inserted. Select **Yes** to continue.

33. In the **Route relation** field, enter or select **eBook route** created in previous steps and **Route code** should be set to **Route**.

34. Select **Save**.

35. Close all pages.

### Exercise \#5: Create a simple BOM without a version

You have been asked to assist the product designer at USMF and show her how to
create a simple BOM for a new light cabinet.

You will approve the BOM using employee 000020, Julia Funderburk.

You will use the parameters on the right

- Name: Light Cabinet

- Item group: Audio

- Site: 1

- Item:

- M0005 Enclosure

- M0006 Binding posts

- P0002 Speaker Damping Foam

- Quantity for each item: 1

You will have to do the following:

- Create a simple BOM

#### Steps

1. Go to **Product information management \> Bills of materials and formulas \>
    Bills of materials**.

2. Select **New**.

3. In the **Name** field, enter or select **Light Cabinet**.

4. In the **Site** field, enter or select **1**.

5. In the **Item group** field, enter or select **Audio**.

6. Select **Save**.

7. In the **Bill of materials lines** section, select **New**.

8. In the **Item number** field, enter or select **M0005**.

9. Select **New**.

10. In the **Item number** field, enter or select **M0006**.

11. Select **New**.

12. In the **Item number** field, enter or select **P0002**.

13. Select **Bill of materials** on the Action Pane then in the **Maintain** group, Select **Approval** and choose **000020, Julia Funderburk**.

14. Select **OK**.

15. Select **Save**.

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

- 1 qty of M0008/High End Cabinet/Black

- 2 qty of M0002/Mid-Range Speaker Unit

- 1 qty of M0009/Protective Corners

You will have to do the following:

- Create a BOM in the BOM designer

#### Steps

1. Go to **Product information management** \> **Bills of materials and formulas** \>
    **Bills of materials**.

2. Select **New**.

3. In the **Name** field, enter or select **High Quality Speaker**.

4. In the **Site** field, enter or select **1**.

5. In the **Item group** field, enter or select **Audio**.

6. Select **Bill of materials** on the Action Pane then in the **Maintain** group, select **Designer**.

7. Select **Formula lines** on the Action Pane.

8. Select **Add to component BOM**.

9. In the list, find and select **M0008 / High End Cabinet / Black**.

10. Select **OK**.

11. Select **Formula lines**.

12. Select **Add after line.**

13. In the list, find and select **M0009 / Protective Corners**.

14. Select **OK**.

15. Select **Forumla lines**.

16. Select **Add before line**.

17. In the list, find and select **M0002 / Mid-Range Speaker Unit**.

18. Select **OK**.

19. Close the **Designer** page.

20. Refresh the **Bill of materials** page. This will populate the previously created BOM formula lines.

21. In the list of Bill of materials lines, find and select the row for **M0002
    / Mid-Range Speaker Unit**.

22. Set **Quantity** to **2.0000**.

23. In the Action pane, select **Approval** in the **Maintain** group in the **Bill of materials** tab.

24. Select **000020**, Julia Funderburk.

25. Select **OK**.

26. Close all pages.

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

- Item number: 72708

- Item name: High Quality Speaker Rosewood

- Item group: Audio

- Item model group: FIFO

- Storage Dimension group: SiteWH

- Tracking Dimension group: None

- Warehouse 11

- Approved by: 000020, Julia Funderburk

You will have to do the following:

- Create a BOM with a version

#### Steps

1. Go to **Product information management \> Products \> Released products.**

2. Select **New**.

3. In the **Product number** field, enter or select **72708**.

4. In the **Product name** field, enter or select **High Quality Speaker Red**.

5. In the **Item model group** field, enter or select **FIFO**.

6. In the **Item group** field, enter or select **Audio**.

7. In the **Storage dimension group** field, enter or select **SiteWH**.

8. In the **Tracking dimension group** field, enter or select **None**.

9. Select **OK**.

10. On the Action Pane, select **Manage inventory**.

11. Select **Default order settings**.

12. In the **Default order type** field, select **Production**.

13. Under the **Inventory** FastTab, In the **Default warehouse** field, enter or select **11**.

14. Close the page.

15. On the Action Pane, select **Engineer**.

16. Select **Designer**.

17. Select **BOM**.

18. Select **Create version**.

19. In the **Name** field, enter or select **High Quality Speaker Rosewood**.

20. Select **Yes** in the **Copy** field.

21. In the **Site** field, enter or select **1**.

22. Select **OK**.

23. In the **Item number** field, enter or select **D0004**.

24. Select **OK**.

25. In the tree, select **Item number: 72708\\M0008 / High End Cabinet**.

26. Select **BOM lines**.

27. Select **Delete**.

28. Select **BOM lines**.

29. Select **Add before line**.

30. In the list, find and select **M0008 / High End Cabinet / Rosewood**.

31. Select **OK**.

32. In the tree, select **Item number: 72708**.

33. Select **BOM**.

34. Select **BOM versions**.

35. Select **Approval**. Select **000020**, Julia Funderburk.

36. Select **Yes** in the **Do you also want to approve the bill of materials?**
    field.

37. Select **OK**.

38. Close all pages.

### Exercise \#8: Create a production order

The minimum information required to create a production order is an active bill
of materials.

Create a new production order to test the previously created BOM

You will have to do the following:

- Create a new production order

#### Steps

1. Go to **Production control \> Production orders \> All production orders**.

2. Select **New production order**.

3. In the **Item number** field, enter or select **72708**.

4. Set **Quantity** to **10.00**.

5. In the **Time** field, enter **10:15 AM**.

6. Select **Create**.

7. Select the **Production order** tab in the Action Pane, then in the **Process** group, select **Estimate**.

8. Select **OK**.

9. Select **Release**.

10. Select **OK**.

11. Select **Start**.

12. Select **OK**.

13. Select **Report as finished**.

14. Select **OK**.

15. Select **End**.

16. Select **OK**.

17. **Close** all pages.

### Exercise \#9: Start a discrete production order (Bonus)

You can get production orders either manually created or firmed from the Master
planning with status “Scheduled”

The production of the ash enclosure back sides of the speakers is ready to be
started.

The production supervisor wants to use the start form and select a production
order with status of “Scheduled” to start.

Can you help the production manager to perform this?

You will have to do the following:

- Start a discrete production order

#### Steps

1. Select **Production control \> Production orders \> All production orders**.

2. Select any production order with the production order status set to
    **Scheduled** (for example, P000171).

3. On the **Production order** Action Pane, select **Start**.

4. On the **Overview** tab, in the **Quantity** field, enter the quantity
    **2.00** of the production order to produce.

5. In the **Date** field, enter today’s date for the date that the production
    starts.

6. Select the **Start production** check box.

7. Select **OK**.

8. **Close** all pages.

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

- Create capabilities and resources

- Identify the resources applicable for the operation

- Add requirements for a capability to an operation

#### Steps

**Create capabilities and resources**

1. Navigate to **Organization administration \> Resources \> Resource
    capabilities**.

2. Select **New**.

3. Enter or select **20** in the **Capability** field and **Assembly** in the
    **Description** field.

4. Select **New**.

5. Enter or select **30** in the **Capability** field and **Packing** in the
    **Description** field.

6. In the **Resources** FastTab, select **Add**.

7. Select **1222** (Speaker packing worker 1) in the **Resource** field.

8. Accept the default expiration date of **Never**.

9. Accept the default **Level** of 0.00.

10. Enter or select **1** in the **Priority** field.

11. Close the **Resource capabilities** form.

12. Open **Organization administration \> Resources \> Resources**.

13. Select **New**.

14. Enter or select **000727** in the **Resource** field.

15. Enter or select **Assembly robot** in the **Description** field.

16. Accept the default of **Machine** in the **Type** field.

17. In the **Capabilities** FastTab, select **Add**.

18. Select 20 in the **Capability** field.

19. Accept the default expiration date of **Never**.

20. Accept the default **Level** of 0.00.

21. Enter or select **1** in the **Priority** field.

22. Expand the **Resource groups** FastTab.

23. Select **View \> All**.

24. Select **Add**.

25. Enter or select **1210** in the **Resource group** field, enter or select the next working day in
    the **Effective** field, and then accept the default expiration date of **Never**.

26. Accept the default **Input warehouse**.

27. Accept the default **Input location**.

28. Scroll up, expand the **Calendars** tab, and select **Add**.

29. Select **24hr** in the **Calendar** field and then accept the default expiration date of **Never**.

30. Close the **Resources** form.

#### **Identify resources applicable for the operation**

1. Navigate to **Production control \> Operations \> All routes**

2. Select route **000002** (STANDARD SPEAKER - D0003) by selecting on the link
    for 000002.

3. Select the **Route** tab in the Action pane, then in the **Maintain** group, select **Route details**.

4. Verify operation 10 is selected in the top grid of the **Route** form.

5. In the bottom grid, select **Applicable Resources**.

6. Notice that all the resources from the 1210 resource group are listed.

7. Scroll one day forward by selecting the **Next day** button or choose
    the date picker field.

8. Select **OK**. This closes the **Applicable resources** form.

#### **To add requirements for a capability to an operation, follow these steps:**

1. In the **Route details** form for route 000002, with operation 10 selected
    in the top grid, select the **Resource requirements** tab on the bottom grid.

2. In the Resource requirements grid, select the line where **Requirement type** is **Capability** and **Requirement** is **Assembly**.

3. Select **Delete**.

    > **NOTE** A message box will appear to confirm the action. Choose **Yes** to delete the record.

4. Select **Maintain resource requirements.** This starts the wizard.

5. On the Welcome screen, select **Next**.

6. On the Search criteria screen, select **Capability** in the **Requirement type** field.

7. Enter or select **20** in the **Requirement** field.

8. Accept the default option for resource requirements on activity.

9. Select **Next**.

10. On the Action screen, leave the defaults and select **Next**.

11. On the New resource requirements screen, set **Requirement type** to
    **Capability**, **Requirement** to **20**, and check the **Operation scheduling** and **Job scheduling** check boxes.

12. Select **Next**.

13. On the summary screen, review your options and choose **Finish**.

14. Close all pages.

### Exercise \#12: Configure costing policies

At USMF, you need to set profit-settings to help sales personnel calculate an
accurate sales price after considering all costs for cabinet item D0002.

You should also be able to view the costing sheet to analyze the cost breakdown

Can you help the sales personnel?

You will have to do the following:

- Update the profit settings on the item

- Review the costing sheet setup

- View the calculation details on the item

#### Steps

1. Go to **Product information management \> Products \> Released products**.

2. Use the **Quick Filter** to filter on the **Item number** field with a value
    of **D0002**.

3. In the list, select **D0002** to open the details page.

4. Expand the **Manage costs** FastTab.

5. Select **M9 cost group** to open the cost group details page.

6. Select **Edit**.

7. Set **Profit percentage** to **40.00**.

8. Select **Add**.

9. In the **Profit-setting** field, select **Profit 1**.

10. Set **Profit percentage** to **70.00**.

11. Select **Save**.

12. Close the page.

13. On the Action Pane, select the **Engineer** tab.

14. In the **BOM** group, select **BOM versions**.

15. Under the Bill of materials lines, select **M0005** to open the **Product
    information** dialog.

16. Select **M0005** item number (not product number) to open the **Released product details** page.

17. Select Cost group **M2** in the **Manage costs** FastTab to open the **Cost group
    details** page.

18. Select **Edit**.

19. Set **Profit percentage** to **30.00**.

20. Select **Add**.

21. In the **Profit-setting** field, select **Profit 1**.

22. Set **Profit percentage** to **60.00**.

24. **Close** all pages.

25. Go to **Cost management \> Indirect cost accounting policies setup \> Costing sheets**.

26. In the tree, select **Root\\Cost of Conversion\\COC-Material\\COC - M2 -
    Cabinets comp**.

27. Review the structure of the costing sheet.

28. In the tree, select **Root\\Cost of Conversion\\Overhead on Conversion\\COC - OVH4 - Labor overhead\\Indirect labor cost - Rate per process time**.

29. Review the **Absorption basis**, and **Rate** FastTabs values.

30. In the tree, select **Root\\Cost of Conversion\\Overhead on Conversion\\COC - OVH4 - Labor overhead**.

31. Select **OVH4**.

32. Set **Profit percentage** to **80.00**.

33. Close all pages.

34. Go to **Product information management** \> **Products** \> **Released products**.

35. Use the **Quick Filter** to filter on the **Item number** field with a value
    of **D0002**.

36. Select the **D0002** link to open the **Released product details** page.

37. On the Action Pane, select the **Manage costs** tab.

38. In the **Set up** group, choose **Item price**.

39. Select the **Pending prices** tab.

40. Select **Calculate item cost**.

41. In the **Costing version** field, enter or select **10**.

42. Select **OK**.

43. Select **View calculation details**.

44. Select the **Costing sheet** tab.

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

- Update the parameters under manufacturing execution production order default
    parameters

#### Steps

1. Open **Production control \> Setup \> Manufacturing execution \> Production
    order defaults**.

2. On the **Start** tab, select **Status** in the **Update start on-line**
    field.

3. In the **Automatic BOM consumption** field, select **Never**.

4. Select the **Operations** tab.

5. Set the **Setup** option to **No**.

6. In the **Automatic BOM consumption** field, select **Always**.

7. Select the **Report as finished** tab.

8. In the **Update finished report on-line** field, select **Quantity**.

9. In the **Automatic BOM consumption** field, select **Never**.

10. Close the **Production order defaults** form.

### Exercise \#14: Configure automatic route consumption on setup jobs (Bonus)

Your estimation on operation setup has proven accurate, so the Production
Manager decided that it is not necessary for employees to register on setup
jobs.

The time consumption on setup jobs must be posted automatically

How would you automate this posting?

You will have to do the following:

- Update routing groups.

- Update the routing group on the MES production order defaults

#### Steps

1. Open **Production control \> Setup \> Routes \> Route groups**.

2. From the list, select **Sfc Shop Floor Control Routing Group**.

3. Select **Edit**.

4. On the **General** FastTab, in the **Automatic route consumption** group,
    enable the **Setup time** field.

5. Close the **Route groups** form.

6. Open **Production control \> Setup \> Manufacturing execution \> Production
    order defaults**.

7. On the **Start** tab, in the **Automatic route consumption** field, select
    **Route group dependent**.

8. Enable the **Post route card now** field.

9. Close the **Production order defaults** form.

### Exercise \#15: Use manufacturing execution (Bonus)

To proceed with testing the manufacturing execution, you need to enable time
registration for Shannon, the machine operator in USMF.

Shannon needs to use the job card terminal to control the execution of the
production order

Can you enable the time registration? How?

You will have to do the following:

- Enable time registration for the machine operator

#### Steps

1. Go to **Human resources \> Workers \> Employees**.

2. Use the **Quick Filter** to filter on the **Name** field with a value of
    **Shannon**.

3. Select **Activate on registration terminals** in the **Time** tab of the
    action pane.

4. In the **Calculation group** field, enter or select **Man**.

5. In the **Default calculation group** field, enter or select **Man**.

6. In the **Approval group** field, enter or select **AdmMan**.

7. In the **Standard profile** field, enter or select **Standard**.

8. In the **Profile group** field, enter or select **Man**.

9. Select **Yes** in the **Use timecard** field.

10. In the **Configuration** field, enter or select **Production**.

11. Select **Yes** in the **Supervisor options** field.

12. Select **OK**.

13. In the list, select **Shannon Dascher** to view the **Employees details** page.

14. Select the **Time registration** tab.

15. Select **Edit**.

16. In the **Identification** field, enter or select **069**.

17. In the **Badge ID** field, enter or select **069**.

18. Select **Save**.

19. Close the page.

20. Go to **Production control \> Manufacturing execution \> Job card device**.

    > **NOTE** Please do not use the **Setup** group from the previous excercise. Use the search box on the navigation bar to locate the Job card device form.

21. In the **Personnel number** field, enter or select **069**.

22. Select **Log in**.

23. Select **Start job**.

24. Set **Quantity to start** to **1.00**.

25. Select **OK**.

26. Select **Report progress**.

27. Set **Error quantity** to **1.00**.

28. In the **Error cause** field, select **Material**.

29. Select **Complete**.

30. Select **Break**.

31. In the list, select **break from work**

32. Select **OK**.

33. Select **Stop break**.

34. Select **Activity**.

35. In the list, find and select **Equipment repair**

36. Select **OK**.

37. Select **OK**.

38. Set **Error quantity** to **2.00**.

39. In the **Error cause** field, enter **Machine**.

40. Select **Complete**.

41. In the **Job status** field, select **Stopped**.

41. Select **Close**.

42. Select **Next job**.

43. Select **Previous job**.

44. Select **Report progress**.

45. Set **Good quantity** to **5.00**.

46. In the **Job status** field, enter **Completed**.

47. Select **Complete**.

48. **Close** the page.

Case study 1B Discrete, Process and Lean manufacturing features
---------------------------------------------------------------

### Exercise \#1: Create an approved vendor list and setting method to Warning Only (Bonus)

Contoso Orange Juice USP2 has determined that approved vendor control shall be
placed on item M7001 with the approved vendor being US-113, and they have
assigned the task to you

Can you perform this task?

You will have to do the following:

- Set up the approved vendor or default vendor

- Set vendor check method to Warning Only

#### Steps

#### **Set up the approved vendor or default vendor**

1. In **USP2** (Navigate to upper right corner of window and change company from USMF to USP2), Go to **Product information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **M7001**.

3. In the list, select the item number **M7001** to view the **Released product details** page.

4. On the Action Pane, select **Purchase**.

5. In Approved vendor group, select **Setup**.

6. Select **Add**.

7. In the **Vendor** field, enter or select **US-113**.

8. Select **Save**.

9. Close the page.

#### **Set the vendor check method to Warning Only**

1. On the **Released product details** page, select **Edit**.

2. Expand the **Purchase** FastTab, set the **Approved vendor check method** field from **No check** to **Warning only**.

3. Select **Save**.

4. **Close** the page.

### Exercise \#2: Create items with different production types

Contoso Process Company (USPI) has purchased a small oil refinery and will start
to manufacture gasoline from a stream of crude oil.

This process produces kerosene and diesel fuel as co-products and wastewater as
a by-product.

You will help the product designer to create the items listed here within
finance and operations using different production types to assist in the
creation of formulas or recipes

- Product Number: P15000

  - Product Name: Gasoline

  - Production Type: Formula

- Product Number: P16000

  - Product Name: Kerosene

  - Production Type: Co-Product

- Product Number: P17000

  - Product Name: Diesel Fuel

  - Production Type: Co-Product

- Product Number: P18000

  - Product Name: Waste Water

  - Production Type: By-Product

- Product Number: M12000

  - Product Name: Crude Oil

  - Production Type: None

You will have to do the following:

- Create a new formula product

- Create the new  
    co-products

- Create the new byproducts

- Create the new raw material

#### Steps

#### **Create a new formula product**

1. In **USPI**, go to **Product information management \> Products \> Released products**.

2. Select **New**.

3. In the **Product number** field, enter or select P15000.

4. In the **Product name** field, enter or select Gasoline.

5. In the **Item model group** field, enter or select a value.

    > **NOTE** For prioritized consumption on limited shelf life, FEFO is recommended.

6. In the **Item group** field, enter or select a value.

7. In the **Storage dimension group** field, enter or select a value.

8. In the **Tracking dimension group** field, enter or select a value.

    > **NOTE** To use the shelf-life settings on the released products details page on the General FastTab, set the **Tracking dimension group** field to a tracking dimension group that is set up to track the batch dimension. You can set this field only when you're first creating a product.  If the dimension value is set to **None**, the option to edit the shelf life field will be disabled. You can't change the value for existing products.

9. In the **Inventory unit** field, enter or select **gal**.

10. In the **Purchase unit** field, enter or select **gal**.

    > **NOTE** You may need to change the dropdown in the selection menu to **All** for this step and the following two steps to get the proper conversion.

11. In the **Sales unit** field, enter or select **gal**.

12. In the **BOM unit** field, enter or select **gal**.

13. Select **OK**.

14. Expand the **Engineer** FastTab and select **Formula** in the **Production type** field.

15. Expand the **Manage inventory** FastTab and enter **365** in the **Shelf life period in days** field.

16. Select **Save**.

17. Close the page.

#### **Create the new co-products**

1. Select **New**.

2. In the **Product number** field, enter **P16000**.

3. In the **Product name** field, enter **Kerosene**.

4. In the **Item model group** field, enter or select a value.

5. In the **Item group** field, enter or select a value.

6. In the **Storage dimension group** field, enter or select a value.

7. In the **Tracking dimension group** field, enter or select a value.

8. In the **Inventory unit** field, enter or select **gal**.

9. In the **Purchase unit** field, enter or select **gal**.

10. In the **Sales unit** field, enter or select **gal**.

11. In the **BOM unit** field, enter or select **gal**.

12. Select **OK**.

13. Expand the **Manage inventory** FastTab and enter **365** in the **Shelf life period in days** field.

14. Expand the **Engineer** FastTab and select **Co-product** in the **Production type** field.

15. In the **Planning formula** field, enter **P15000**.

16. Select **Save**.

17. Close the page.

18. Select **New**.

18. Select **New**.

19. In the **Product number** field, enter or select **P17000**.

20. In the **Product name** field, enter or select **Diesel Fuel**.

21. In the **Item model group** field, enter or select a value.

22. In the **Item group** field, enter or select a value.

23. In the **Storage dimension group** field, enter or select a value.

24. In the **Tracking dimension group** field, enter or select a value.

25. In the **Inventory unit** field, enter or select **gal**.

26. In the **Purchase unit** field, enter or select **gal**.

27. In the **Sales unit** field, enter or select **gal**.

28. In the **BOM unit** field, enter or select **gal**.

29. Select **OK**.

30. Expand the **Manage inventory** FastTab and enter **365** in the **Shelf life period in days** field.

31. Expand the **Engineer** FastTab and select **Co-product** in the **Production type** field.

32. In the **Planning formula** field, enter **P15000**.

33. Select **Save**.

34. Close the page.

#### **Create the new by-products**

1. Select New.

2. In the **Product number** field, enter or select **P18000**.

3. In the **Product name** field, enter or select **Waste Water**.

4. In the **Item model** group field, enter or select a value.

5. In the **Item group** field, enter or select a value.

6. In the **Storage dimension group** field, enter or select a value.

7. In the **Tracking dimension group** field, enter or select a value.

8. In the **Inventory unit** field, enter or select **gal**.

9. In the **Purchase unit** field, enter or select **gal**.

10. In the **Sales unit** field, enter or select **gal**.

11. In the **BOM unit** field, enter or select **gal**.

12. Select **OK**.

13. Expand the **Manage inventory** FastTab and enter **365** in the **Shelf life period in days** field.

14. Expand the **Engineer** FastTab and select **By-product** in the **Production type** field.

15. Select **Save**.

16. Close the page.

#### **Create the new raw material**

1. Select **New**.

2. In the **Product number** field, enter or select **M12000**.

3. In the **Product name** field, enter or select **Crude Oil**.

4. In the **Item model group** field, enter or select a value.

5. In the **Item group** field, enter or select a value.

6. In the **Storage dimension group** field, enter or select a value.

7. In the **Tracking dimension group** field, enter or select a value.

8. In the **Inventory unit** field, enter or select **gal**.

9. In the **Purchase unit** field, enter or select **gal**.

10. In the **Sales unit** field, enter or select **gal**.

11. In the **BOM unit** field, enter or select **gal**.

12. Select **OK**.

13. Expand the **Manage inventory** FastTab and enter **365** in the **Shelf life period in days** field.

14. Expand the **Engineer** FastTab and for the **Production type** field, select **None**.

15. Select **Save**.

16. Close all pages.

### Exercise \#3: Create and activate a formula using different product types

The engineering department has finished the review of the data in the new
refinery and determined the formula should be as specified here.

The product definition employee wants to create the formula and assign the
co-products and by-products to the formula and cost allocation.

He asked for your help. Can you help?

- Product Number: P15000

- Product Name: Gasoline

- Formula Size: 500 gal

- Formula Line: M12000 (Crude Oil), QTY 1000 gal

- Formula Line: M2001 (DI Water), QTY 600 gal

- Co-Product Line: P16000 (Kerosene), QTY 50 gal 10% cost allocation

- Co-Product Line: P17000 (Diesel Fuel), QTY 350 gal 32% cost allocation

- By-Product Line: P18000 (Waste Water), QTY 600 gal, 5% cost allocation

- Approved by: Glen John

You will have to do the following:

- Create a formula

- Add formula lines to the formula

- Add co-products and by-products with cost allocation

- Approve and activate the formula

#### Steps

#### **Create a formula for part P15000**

1. Go to **Product information management \> Products \> Released products**.

2. Use the Quick Filter to find records. For example, filter on the Item number field with a value of **p15000**.

    > **NOTE** The value is provided value in lowercase but it is not case
    sensitive.

3. Select the ellipsis, if needed, to get to the **Engineer** tab on the action
    pane.

4. Select **Formula versions**.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **GAS001**.

8. In the **Name** field, enter or select **Gasoline**.

9. In the **Site** field, enter or select **1**.

10. Select **OK**.

11. In the **Lines** or **Header** field, select **Header**.

12. In the **Formula versions** grid, set the **Formula size** field to **500.00**.

13. Select **Save**.

#### **Add Formula Lines to Formula**

1. In the **Lines** or **Header** field, select **Lines**.

2. Select **New**.

3. In the **Item number** field, enter or select **M12000**.

    > **NOTE** When you select **New**, you may need to change the dropdown in the selection menu to **Other**.

4. In the **Warehouse** field, enter or select a value.

5. Set **Quantity** to **1000**.

6. Select **New**.

7. In the **Item number** field, enter or select **M2001**.

    > **NOTE** When you select **New**, you may need to change the dropdown in the selection menu to **Other**.

8. Set **Quantity** to **600**.

9. Select **Save**.

10. **Close** the page.

#### **Add Co-Products and By-Products with Cost Allocation**

1. In the Action bar, select **Formula version* and then select **Co-products**.

2. Select **New**.

3. In the **Item number** field, enter or select **P16000**.

4. In the **Warehouse** field, enter or select a value.

5. Set **Quantity** to **50**.

6. In the **Co-product cost allocation** field, select **Manual**.

7. Set **Cost allocation percent** to **10**.

8. Select **Save**.

9. Select **New**.

10. In the **Product enter or select** dropdown, select **By-product**. In the **Item number** field, enter or select **P17000**.

11. In the **Warehouse** field, enter or select **11**.

12. Set **Quantity** to 350.

13. In the **By-product cost allocation** field, select **Percent**.

14. Set **Cost allocation percent** to **32**.

15. Select **Save**.

16. Select **New**.

17. In the **Item number** field, enter or select **P18000**.

18. In the **Warehouse** field, enter or select a value.

19. Set **Quantity** to **600.0000**.

20. In the **By-product cost allocation** field, select **Percent**.

21. Set **By-product burden amount** to **5**.

22. Select **Save**.

23. **Close** the page.

#### **Approve and activate the formula**

1. Select **Formula version** and then select **Approval**.

2. In the **Approved by** field, enter or select **000528** for Glen John.

3. Slide the toggle button to **Yes** for **Do you also want to approve the formula?** option.

4. Select **OK**.

5. Select **Activate**.

6. **Close** the page.

### Exercise \#4: Create a new formula with a version from the released products form (Bonus)

The marketing department at USP2 Contoso Orange Juice factory has determined the
need for production of a new product for Frozen Apple Juice Concentrate.

The product designer asked you to help create a formula version with the
following details

Can you do so?

- Product Number: P7100

- Product Name: Frozen Apple Juice Concentrate

- Formula Size: 1000 gal

- Formula Line: M9103 (Apples), QTY 800

- Formula Line: M8001 (Asorbic Acid),  
    QTY 660

- Formula Line: M8003 (Vitamin A), QTY 40

- Formula Line: M8004 (Vitamin C), QTY 18

- Formula Line: M7003 (Sucrose), QTY 33

- Formula Line: M8008 (Can), QTY 2400

- Approved by: Glen John

You will have to do the following:

- Create a new product.

- Create a formula.

- Create formula lines.

- Approve and activate the formula

#### Steps

#### **Create a new product**

1. In the **USP2** company, go to **Product information
    management\>Products\>Released products**

2. Select **New**.

3. In the **Product number** field, enter or select **P7100**.

4. In the **Product name** field, enter or select **Frozen Apple Juice Concentrate**.

5. In the **Search name** field, enter or select **FrozenAppleJuice**.

6. In the **Item model group** field, enter or select a value.

7. In the **Item group** field, enter or select a value.

8. In the **Storage dimension group** field, enter or select a value.

9. In the **Tracking dimension group** field, enter or select a value.

10. In the **Inventory unit** field, enter **lb**.

11. In the **Purchase unit** field, enter or select **lb**.

12. In the **Sales unit** field, enter or select **lb**.

13. In the **BOM unit** field, enter or select **lb**.

14. Select **OK**.

15. On the **Engineer** FastTab, for the **Production type** field, select **Formula**.

16. In the **Shelf life period in days** field in the Manage inventory FastTab, enter or select **180**.

17. Select **Save**.

#### **Create a formula**

1. Select **Formula versions** in the Engineer tab in the action pane.

2. Select **New**.

3. Select **Formula and formula version**.

4. In the **Formula** number field, enter or select **FOR-7100**.

5. In the **Name** field, enter or select **For making Frozen Apple Juice Concentrate**.

6. In the **Site** field, enter or select **1**.

7. Select **OK**.

#### **Create formula lines**

1. In the **Lines** or **Header** field, select **Header**.

2. On the **Formula versions** grid, set **Formula size** field to **1000**.

3. Set the **From formula size** field to **1000**.

4. In the **Lines** or **Header** field, select **Lines**.

5. In the **Formula lines** grid, select **New**.

6. In the **Item number** field, enter or select **M9103**.

    > **NOTE** When you select **New**, you may need to change the dropdown in the selection menu to **Other**.

7. Set **Quantity** to **800**.

8. Select **New**.

9. In the **Item number** field, enter or select **M8001**.

10. Set **Quantity** to **660**.

11. Select **New**.

12. In the **Item number** field, enter or select **M8003**.

13. Set **Quantity** to **40**.

14. Select **New**.

15. In the **Item number** field, enter or select **M8004**.

16. Set **Quantity** to **18**.

17. Select **New**.

18. In the **Item number** field, enter or select **M7003**.

19. Set **Quantity** to **33**.

20. Select **New**.

21. In the **Item number** field, enter or select **M8008**.

22. Set **Quantity** to **2400**.

23. Select **Save**.

#### **Approve and activate the formula**

1. Select **Formula** and then select **Approve formula**.

2. In the **Approved by** field, enter or select **000528** for Glen John.

3. Select **OK**.

4. In the **Lines** or **Header** field, select **Header**.

5. On the **Formula versions** grid, select **Approval** from the toolbar.

6. In the **Approved by** field, enter or select **000528** for Glen John.

7. Select **OK**.

8. Select **Activate** from the toolbar.

9. **Close** the page.

### Exercise \#5: Revise, update and activate a formula (Bonus)

Analysis of the production orders for P8000 in company USP2 has shown that the
scrap factors and consumption amount of part P6000 need to be updated.

You want to formula revise, update, approve, and activate the formula with an
effective date of 12/15/2020

You will have to do the following:

- Copy the existing formula

- Update line

- Date out the old version and date in the new version

- Approve and activate the formula

#### Steps

#### **Copy the existing formula**

1. In the **USP2** company, go to **Product information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the Item number field with a value of
    **P8000**.

3. In the list, select the link in the selected row.

4. Select **Formula versions** in the Engineer tab on the action pane.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **F01**.

8. In the **Name** field, enter or select **V01**.

9. Set the **Copy** to **Yes**.

10. In the **Site** field, enter or select **1**.

11. Select **OK**.

12. In the **Formula version** field, select the existing formula version
    **For-00002**.

13. Select **OK**.

#### **Update the line**

1. In the list, find and select the record for **P6000**.

2. Set **Quantity** to **0.35**.

3. Expand the **Line details** FastTab then select the **Setup** tab.

4. In the **Variable scrap** field, enter a number.

5. Select **Save**.

6. **Close** the page.

#### **Date out the old version and date in the new version**

1. In the list, find and select the original formula version **For-00002**.

2. In the **To date** field, set the date to **12/14/2020**.

3. Select **Save**.

4. In the list, find and select the new formula version **F01**.

5. In the **From date** field, set the date to **12/15/2020**.

6. Select **Save**.

#### **Approve and activate formula**

1. Select the **Formulas** tab from the Action Pane, then select **Formula** in the **Maintain formula** group.

2. Select **Approve formula**.

3. In the **Approved by** field, enter or select a value.

4. **Close** the screen to go back to the **Formula versions** screen.

5. Select **Formula version** \> **Approval**.

6. In the **Approved by** field, enter or select a value.

7. Select **OK**.

8. Select **Activate**.

### Exercise \#6: Use the scalability feature to create a new formula

Your manufacturing plant in company USP2 has obtained a new mixer that is 1.5
times the size of the current mixer used to make part P9500.

Engineering has determined that the vitamin compounds do not need to increase in
quantity, but the other ingredients do.

Use the formula scalability feature to create a new formula for the larger size
based on the existing formula for the part

You will have to do the following:

- Copy the existing formula

- Verify the lines are flagged as scalable for P9500 (except for the vitamin
    compounds)

- Update the formula size

- Approve and activate the formula

#### Steps

#### **Copy existing formula**

1. In **USP2** company go to **Product information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **P9500**.

3. In the list, select the link in the selected row.

4. Select **Formula versions** in the Engineer tab in the action pane.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **P9500V0**.

8. In the **Name** field, enter or select **V0**.

9. Select the **Copy** option.

10. In the **Site** field, enter or select **1**.

11. Select **OK**.

12. In the **Formula version** field, select the current version.

13. Select **OK**.

#### **Verify the lines are flagged as scalable for P9500 (except for the vitamin compounds)**

1. On the **Lines** tab, find the vitamin compounds.

2. Select or clear the **Scalable** check boxes.

3. Select **Save**.

#### **Update the formula size**

1. On the **Lines** or **Header** field, select **Header**.

2. Set **Formula size** to **1500**.

3. Set **From formula size** to **1500**.

4. Select **Save**.

#### **Approve and activate the formula**

1. In the Lines or header field, select **lines**.

2. Select **Save**.

3. Select **Approve formula**.

4. In the **Approved by** field, enter or select a value.

5. Select **OK**.

6. In the **Lines or Header** field, select **Header**.

7. Select **Approval** from the toolbar on the **Formula versions** grid.

8. In the **Approved by** field, enter or select a value.

9. Select **OK**.

10. Select **Activate**.

### Exercise \#7: Create and activate a percentage-based formula (Bonus)

Company USP2 has been contracted to make a new orange juice with the following
volume percentages for the final mixture.

The mixture should also have vitamin C and vitamin A added per the mixing
instructions given here.

The volume batch size is to be 1500 gallons

You were asked to use this info to create the formula. Can you help?

| Ingredient | Recipe percent\/quantity |
|------------|--------------------------|
| P9500      | 5%                       |
| M9001      | 92%                      |
| M7004      | 3%                       |
| M8004      | 1.33 lb/1500 gal.        |
| M8003      | 1.1 LB/1500 gal.         |

You will have to do the following:

- Create a new release product

- Copy the existing formula for P9500

- Verify the lines are flagged as scalable for P9500 (except the vitamin
    compound)

- Update the formula size

- Approve and activate the formula

#### Steps

#### **Create a new released product**

1. In the **USP2** company go to **Product information
    management \> Products \> Released products**.

2. Select **New**.

3. In the **Product number** field, enter or select **'P6100'**.

4. In the **Product name** field, enter or select ‘**Orange Juice'**.

5. In the **Search name** field, enter or select **'Orange Juice'**.

6. In the **Item model group** field, enter or select a value.

7. In the **Item group field**, enter or select a value.

8. In the **Storage dimension group** field, enter or select a value.

9. In the **Tracking dimension group** field, enter or select a value.

10. In the **Inventory unit** field, enter or select **gal**.

11. In the **Purchase unit** field, enter or select **gal**.

12. In the **Sales unit** field, enter or select **gal**.

13. In the **BOM unit** field, enter or select **gal**.

14. Select **OK**.

15. In the **Production type** field in the Engineer FastTab, select
    **'Formula'**.

16. In the **Shelf life period in days** field in the Manage inventory Fast Tab,
    enter **180**.

17. Select **Save**.

#### **Copy the existing formula for P9500**

1. Go to **Product information management\>Products\>Released products**.

2. Use the Quick Filter to filter on the Item number field with a value of
    **'P9500'**.

3. In the list, select the link in the selected row.

4. Select **Formula versions** in the Engineer tab in the action pane.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select a value.

8. In the **Name** field, enter or select a value.

9. Select the **Copy** option.

10. In the **Site** field, enter or select **1**.

11. Select **OK**.

12. In the **Formula version** field, select the current version.

13. Select **OK**.

#### **Verify that the lines are flagged as scalable for P9500 (except for the vitamin compounds)**

1. In the lines, find the vitamin **compounds**.

2. Select or clear the **Scalable** check boxes.

3. Select **Save**.

#### **Update the formula size**

1. In the Lines or header field, select **header**.

2. Set the version’s **Formula size** to **'1500'**.

3. Set the version’s **From formula size** to **'1500'**.

4. Select **Save**.

#### **Approve and activate the formula**

1. In the Lines or header field, select **lines**.

2. Select **Save**.

3. Select **Approve formula**.

4. In the **Approved by** field, enter or select a value.

5. Select **OK**.

6. In the Lines or header field, select **header**.

7. Select **Approve** in the **Versions** grid.

8. In the **Approved by** field, enter or select a value.

9. Select **OK**.

10. Select **Activate**.

11. Close all pages.

### Exercise \#8: Change a linear consumption to a step-wise consumption

In company USP2, the formula for product P9500 should be updated.

Formula line M9003 needs to be changed from a linear consumption to a step-wise
consumption

The consumption on the line shall be:

- 0-1400: 5.5

- 1400-2400: 10.6

- 2400+: 15.8

The company employee not sure how to do so and asked for your help. Can you
help?

You will have to do the following:

- Copy the existing formula  
    for P9500

- Set the line for M9003 in the new formula to step-wise consumption and set
    the  
    step levels

- Date out the old formula and date in the new one

- Approve and activate the formula

#### Steps

#### **Copy the existing formula for P9500**

1. Go to **Product information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **P9500**.

3. In the list, select the link in the selected row for **P9500**.

4. Select **Engineer** \> **Formula** \> **Formula versions**.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select **P9500V1**.

8. In the **Name** field, enter or select **V1**.

9. Select the **Copy** option.

10. In the **Site** field, enter or select 1.

11. Select **OK**.

12. In the **Formula version** field, select the current version

13. Select **OK**.

#### **Set the line for M9003 in the new formula to step-wise consumption and set the step levels**

1. In the lines, find the line for **M9003**.

2. Select the **Setup** tab in line details.

3. In the **Formula** field, select **Step**.

4. Select the **Step consumption** tab.

5. Set **Quantity** to **5.5**.

6. Select **New**.

7. Set **From series** to **1400**.

8. Set **Quantity** to **10.6**.

9. Select **New**.

10. Set **From series** to **2400**.

11. Set **Quantity** to **15.8**.

12. Select **Save**.

13. Close all pages.

#### **Date out the old formula and date in the new one**

1. Go to **Product information management\>Products\>Released products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **P9500**.

3. In the list, select the link in the selected row for **P9500**.

4. Select Engineer \> Formula \> **Formula versions**.

5. In the list, find and select the old formula.

6. Select **Edit**.

7. In the **To date** field, set the date to **12/27/2016**.

8. Select **Save**.

9. In the list, find and select the new formula.

10. In the **From date** field, set the date to **12/28/2016**.

11. Select **Save**.

#### **Approve and activate the formula**

1. Select **Approve**.

2. In the **Approved by** field, enter or select an employee.

3. Select the **Do you also want to approve the formula?** option.

4. Select **OK**.

5. Select **Activate**.

### Exercise \#9: Set up commodity pricing

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples.

The sales price of the Apple Pie, part P9300, manufactured from this sugar
should be based on a margin of 45 percent and a cost multiple of 1.25 for all
quantities.

The pricing employee wants to set up the cost basis and pricing template for
this scenario. She is not quite sure how to do so and asked for your help.

Can you help?

You will have to do the following:

- Configure item P9100

- Create a cost basis

- Create a pricing template

- Create a quantity and margin template

- Complete the inventory parameter setup

- Set up pricing calculation

#### Steps

#### **Configure an item**

1. Go to **Product information management \> Products \> Released products**.

2. Use the **Quick Filter** to filter on the **Item number** field with a value
    of **P9100**.

3. On the Action Pane, select **Manage inventory**.

4. Select **Default order settings**.

5. Select **Edit**.

6. In the **Default order enter** field, select **Production**.

7. Select **Save**.

8. Close all pages.

#### **Create a cost basis**

1. Go to **Inventory management \> Setup \> Commodity pricing \> Cost basis
    type.**

2. Select **New** if necessary.

3. In the **Cost basis type** field, enter **NYMEX**.

4. In the **Description** field, enter **New York Mercantile Exchange**.

5. Select **Save**.

6. Close the page.

#### **Create a pricing template**

1. Go to **Inventory management \> Setup \> Commodity pricing \> Pricing
    template**.

2. Select **New**.

3. In the **Pricing template** field, enter **Apples**.

4. In the **Description** field, enter **Apples**.

5. Select **Save**.

#### **Create a quantity and margin template**

1. Select **Quantity and margin template**.

2. Select **New**.

3. In the **Item relation** field, enter **P9100**.

4. In the **Site** field, enter **1**.

5. Set **Cost multiplier** to **1.25**.

6. Set **Margin percentage** to **45**.

7. In the **Warehouse** field, enter **12**. If its not visible, find it in the
    Dimension fast tab.

8. Select **Save**.

9. Close the page.

#### **Complete the inventory parameter setup**

1. Go to **Inventory management \> Setup \> Inventory and warehouse management
    parameters**.

2. Select the **Commodity pricing** tab.

3. In the **Dimension set** field, enter or select **MA+BU**.

4. In the **Cost basis type** field, enter or select **NYMEX**.

5. Select **Yes** in the **Keep BOM/Formula calculations** field.

6. Right-click **Trade agreement** and view details.

7. Select **New**.

8. In the **Name** field, enter **Price_S**.

9. In the **Description** field, enter **Sales Price Adjustment Journal**.

10. In the **Relation** field, select **Price (sales)**.

11. Select **Save**.

12. Close the page.

13. In the **Trade agreement** field, enter or select **Price_S**.

14. Select **Save**.

15. Close the page.

#### **Set up pricing calculation**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Pricing calculation.**

2. Select **New**.

3. Note that the **Cost basis type** field is set to **NYMEX**.

4. In the **Run effective date** field, enter todays date.

5. In the **Run expiry date** field, enter a date in the future.

6. Select **Save**.

7. Close the page.

### Exercise \#10: Change a price calculation and update trade agreements

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples.

The sales price of the applesauce manufactured from the apples is to be based
upon the fluctuations in the pricing of the apples from 2/20/20 to 2/27/20

You will have to do the following:

- Complete the price calculation

- Review the price calculation data and create trade agreements

- Post the trade agreements that are created

#### Steps

#### **Complete the price calculation**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Create price and margin data**.

2. In the Pricing calculation field, enter or select **000001** for NYMEX.

3. In the Pricing template field, enter or select **Apples**.

4. Select **OK**.

#### **Review the price calculation data and create trade agreements**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing \> Price
    margin update**.

2. If the price calculations completed successfully, you will see your new
    pricing. Select **Lines**.

3. Select **Update trade agreements**.

4. Select **OK**.

5. Close the page.

6. In the list, find and select the desired record.

7. Select **Lines**.

8. Select **Update trade agreements**.

9. Select **OK**.

10. Close the page.

#### **Post the trade agreements**

1. Go to **Sales and marketing \> Prices and discounts \> Trade agreement
    journals**.

2. Select **Lines**.

3. Select **Post**.

4. Select **OK.**

5. Select **Lines**.

6. Select **Post**.

7. Select **OK**.

8. Close the page.

### Exercise \#11: Setting up a commodity price calculation

In company USP2, the price of apples, part M9103, is to be tracked based upon
the NYMEX commodity exchange pricing of apples. The sales price of the
applesauce manufactured from the apples is to be based upon the fluctuations in
the pricing of the apples. The weekly pricing for the week of 02/20/20 and
02/27/20 has been received as 0.14/lb. and 0.15/lb., respectively

You will have to do the following:

- Create a pricing calculation

- Enter commodity pricing data

- Create a pricing calculation

- Enter commodity pricing data

#### Steps

#### **Create a pricing calculation**

1. Go to **Inventory management \> Periodic tasks \> Commodity pricing \>
    Pricing calculation**.

2. Select **New**.

3. In the **Cost basis type** field, enter or select **NYMEX**.

4. In the **Site** field, enter **1**.

5. In the Run effective date field, set the date to **2020-02-20** or your
    local equivalent.

6. In the **Run expiry date** field, set the date to **2020-02-26** or your
    local equivalent.

7. Select **Save**.

#### **Enter commodity pricing data**

1. Select **Commodity pricing**.

2. Select **New**.

3. In the Item number field, enter **M9103**.

4. In the **Warehouse** field, enter or select a value.

5. Set **New cost** to **0.14**.

6. Select **Save**.

7. Close the page.

#### **Create a pricing calculation**

1. Select **New**.

2. In the **Cost basis type** field, enter or select **NYMEX**.

3. In the **Site** field, enter **1**.

4. In the **Run effective date** field, set the date to **2020-02-27.**

5. In the **Run expiry date** field, set the date to **2020-03-05**.

6. In the **Previous run** field, enter or select a value.

#### **Enter commodity pricing data**

1. Select **Commodity pricing**.

2. Select **New**.

3. In the **Item number** field, enter **M9103**.

4. In the **Warehouse** field, enter or select a value.

5. Set New cost to **0.15**.

6. Select **Save**.

7. Close the page.

### Exercise \#12: Creating PSDS lists, records and file uploads for product compliance

In company USP2, product M7001, sulfur dioxide, has been setup as a regulated
and restricted product. A new Product Data Safety Sheet (PSDS) has been obtained
from the vendor and must be attached to the item. Using the attached file, create
the PSDS record and activate it based upon an effective date range of 6/1/2020 to 5/31/2022

You will have to do the following:

- Create a PSDS list

- Create a PSDS record

- Upload a PSDS file

#### Steps

#### **Create a PSDS list**

1. Go to **Inventory management \> Setup \> Product compliance \> Product
    safety data sheet validity**.

2. Select **New**.

3. In the Country/region field, enter **USA**.

4. Select **Save**.

5. Close the page.

#### **Create a PSDS record**

1. Go to **Product information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the Item number field with a value of
    **M7001**.

3. On the Action Pane, select **Manage inventory**.

4. Select **Safety data sheet**.

5. Select **New**.

6. In the **Document Name** field, enter or select a value.

7. Select **Yes** in the **Active** field.

8. In the **Country/region** field, enter or select a value.

9. In the **Approval source** field, enter or select a value.

10. In the **Major version** field, enter a number.

11. In the **Approval date** field, set the date to **2020-06-01** or your local
    equivalent.

12. In the **Effective date** field, set the date to **2020-06-01**.

13. In the **Expiry date** field, set the date to **2022-05-31**.

14. Select **Save**.

#### **Upload a PSDS file**

1. Select **Attach** (the paper clip near the top right).

2. Select **New**.

3. Select **File**.

4. Select **Browse**

5. Select the PSDS file, or any file to act as it.

6. In the Restriction field, select **External**.

7. Select **Save**.

8. Close the page.

9. Refresh the page.

10. Select **Open** document.

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

- Enter product reporting details

- Enter the CAS number

- Update annual usage quantities

#### Steps

#### **Enter product reporting details**

1. Go to **Product information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the Item number field with a value of
    **m7001**.

3. On the Action Pane, select **Manage inventory**.

4. In the **Compliance** group, select **Reporting details**.

5. Select **Edit**.

6. In the **OSHA product name** field, enter or select **Sulfur Dioxide**.

7. Set the OSHA threshold quantity to **5**.

8. Set the EHS reportable quantity to **500**.

9. Set the EHS threshold planning quantity to **500**.

10. Select **Save**.

#### **Enter the CAS number**

1. Select **Item CAS relations**.

2. In the **CAS number** field, enter or select **7446-09-5**.

3. In the **CAS name** field, enter or select **Sulfur Dioxide**.

4. Select **Save**.

5. Close the page.

#### **Update annual usage quantities**

1. Select **Update quantities**.

2. Close the page.

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

- Create a sales order for item M7001

- Complete the reservation

- Post the packing slip and print the PSDS

#### Steps

#### **Create a sales order**

1. Go to **Accounts receivable \> Orders \> All sales orders**.

2. Select **New**.

3. In the **Customer account** field, enter or select **us-031.**

4. In the **Warehouse** field (General section), enter or select **11**.

5. Expand the **Delivery** section and in the **Requested receipt date** field, set the date to a near future date.

6. Select **OK**.

7. In the Item number field, enter or select **m7001**.

8. Set Quantity to **100**.

9. In the **Unit price** field, enter a number.

10. Select **Save**.

#### **Complete the reservation**

1. Select **Inventory**.

2. Select **Reservation**.

3. Select **Reserve lot**.

4. Close the page.

#### **Post the packing slip and print the PSDS**

1. Select **Pick and pack \> Post packing slip**.

2. Select **OK**.

3. Select **OK**.

4. Verify that the PSDS was printed if that option was desired.

5. Close the page.

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

- Create a new batch attribute

- Set the attribute minimum and maximum

- Associate the batch attribute with  
    the item

- Set the item attribute minimum and maximum

- Assign financial dimensions to the item

- Associate the batch attribute with the customer

- Set the customer attribute minimum and maximum

#### Steps

#### **Create a new batch attribute**

1. In **USPI** company go to **Inventory Management** \> **Setup** \> **Batch** \> **Batch
    attributes**.

2. Select **New**.

3. In the **Attribute** field, enter or select **MeltingPoint**.

4. In the **Description** field, enter or select **Melting Point (C)**.

5. In the **Attribute type** field, select **Integer**.

#### **Set the attribute minimum and maximum**

1. In the **Minimum** field, enter or select **0**.

2. In the **Maximum** field, enter or select **500**.

3. In the **Increment** field, enter or select **1**.

4. Select **Save**.

5. Close the page.

#### **Associate the batch attribute with the item**

1. Go to **Product Information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the Item number field with a value of
    **p4000**.

3. On the **Manage Inventory** tab, in the **Batch Attributes** group, select **Product specific**.

4. Select **New**.

5. In the **Attribute relation** field, select **Melting Point**.

#### **Set the item attribute minimum and maximum**

1. In the **Tolerance action** field, select **Not allowed**.

2. Set **Minimum** to **130**.

3. Set **Maximum** to **171**.

4. In the **Target** field, enter or select **150**.

5. Select **Save**.

6. Close the page.

#### **Assign the default financial dimension to the item**

1. Go to **Product Information management \> Products \> Released products**.

2. Use the **Quick Filter** to filter on the **Item number** field with a value
    of **P4000**.

3. Select the link for P4000 to open the **Released product details** page.

4. Select **Edit**.

5. Expand **Financial dimensions** FastTab, select a product group for the
    **ProductGroup** financial dimension.

6. Select **Save**.

#### **Associate the batch attribute with the customer**

1. Go to **Product Information management \> Products \> Released products**.

2. Use the Quick Filter to filter on the Item number field with a value of
    **p4000**.

3. Select **Customer specific** in the Batch Attributes group on the **Manage
    Inventory** tab.

4. Select **New**.

5. In the **Attribute relation** field, enter or select **Melting Point**.

6. In the **Account selection** field, enter or select **US-024**.

#### **Set the customer attribute minimum and maximum**

1. Set **Minimum** to **135**.

2. Set **Maximum** to **165**.

3. Select **Save**.

### Exercise \#16: Create a new batch number and manually record the batch attribute

The inventory manager for company USPI wants to create a new batch number for
part P4000.

He is not sure where to start or what to do.

Can you help?

You will have to do the following:

- Create a new batch number

- Manually record the batch attribute data

#### Steps

#### **Create a new batch number**

1. Go to **Warehouse management \> Setup \> Inventory \> Batches**.

2. Select **New**.

3. In the **Batch number** field, enter or select **GTL0001**.

4. In the **Item number** field, enter or select **P4000**.

5. Expand the **Properties** FastTab and in the **Manufacturing date** field, enter today’s date.

6. Select **Save**.

#### **Manually record the batch attribute data**

1. On the Action Pane, select **View**.

2. Select **Inventory batch attributes**.

3. Select **Load item attributes**.

4. In the **Attribute value** field, enter or select **163**.

5. Select **Save**.

6. Close all pages.

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

- Create a new purchase order for item M2005

- Receive the purchase order

- Complete the quality order

- Verify the batch attribute data

#### Steps

#### **Create a new purchase order**

1. Go to **Procurement and sourcing \> Purchase orders \> All purchase
    orders.**

2. Select **New**.

3. In the **Vendor account** field, enter or select **US-102**.

4. Select **OK**.

5. In the **Item number** field, enter or select **m2005**.

6. Set **Quantity** to **500**.

7. Set the **Unit** price to **6.99**.

8. Select **Save**.

9. On the Action Pane, select **Purchase**.

10. In the **Actions** group, select **Confirm**.

11. Note the purchase order number.

12. Close the page.

#### **Receive the purchase order**

1. Go to **Inventory management \> Inbound orders \> Arrival overview**.

2. Expand **Arrival query details**.

3. Set the value of **Restrict to site** to **1**.

4. Select **Update**.

5. In the **Arrival overview profile name** field, enter or select **Inquiry** to view the purchase order in the Receipts grid.

6. Select **Update**.

7. Search for the purchase order created and select the record.

8. Select **Start arrival** in the **Receipts** FastTab. This will update the status on in the Receipt in progress field to Complete.

9. Re-select your PO.

10. Select **Journals**.

11. Select **Show arrivals from lines**.

12. Select **Inventory**.

13. Select **Display dimensions**.

14. Select the **Site** check box.

15. Select the **Warehouse** check box.

16. Select the **Batch number** check box.

17. Select **OK**.

18. Right-click and view details on the **Batch number** field.

19. Select **New**.

20. In the **Batch number** field, enter or select **GTLB001**.

21. Expand **Properties** FastTab and enter in the **Manufacturing date** field.

22. Select **Save**.

23. Close the page.

24. Close the **Batches** page.

25. In the **Batch number** field, enter or select the
    batch that was created (GTLB001).

26. Select **Post**.

27. Select **OK**.

28. Select **Functions**.

29. Select **Product receipt**.

30. In the **Product receipt** field, enter or select a value.

31. Select **OK**.

32. Close the page.

#### **Complete the quality order**

1. Go to **Inventory Management \> Periodic tasks \> Quality Management \>
    Quality orders**.

2. Select **Results**.

3. You may need to select **Reopen Quality Order** and then select **Edit** to update the Quality order line results.

4. Set Result quantity to **5**.

5. Set Test result to **15.4**.

6. Select **Save**.

7. Close the page.

8. Select **Validate**.

9. In the **Validated by** field, enter or select a value.

10. Select **OK**.

#### **Verify the batch attribute data**

1. Select the **Inventory dimensions** tab.

2. Select to follow the link in the **Batch number** field.

3. On the Action Pane, select **View**.

4. Select **Inventory batch attributes**.

5. Close the page.

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

- Create a customer attribute requirement

- Create a new batch order

- Process the batch order

- Complete the quality order

- Create a sales order

- Complete the batch reservation and shipment

#### Steps

#### **Create a customer attribute requirement**

1. In **USPI** go to **Product information management** \> **Products** \> **Released
    products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **p5000**.

3. Select **Customer specific** from the **Manage Inventory** tab.

4. Select **New**.

5. In the **Attribute relation** field, enter or select a value.

6. In the **Account selection** field, enter or select **us-026**.

7. Set **Minimum** to **98**.

8. Select **Save**.

9. Close the page.

#### **Create a new batch order**

1. In **USPI** company go to **Production Control** \> **Production Orders** \> **All Production orders**.

2. Select **New batch order**.

3. In the **Item number** field, enter or select **p5000**.

4. In the **Delivery** field, enter a date.

5. Select **Create**.

#### **Process the batch order**

1. On the Action Pane, select **Production order**.

2. Select **Estimate**.

3. Select **OK**.

4. Select **Start**.

5. Select **OK**.

6. On the Action Pane, select **View**.

7. Select **Picking list**.

8. In the list, select the link in the selected row.

9. In the journal lines, select each row and complete the batch reservation.

10. Select **Inventory**.

11. Select **Reservation**.

12. Select **Reserve lot**.

13. Close the page.

14. Select **Post**.

15. Select **OK**.

16. Close the page.

17. Close the page.

18. On the Action Pane, select **Production order**.

19. Select **Report as finished**.

20. Select **OK**.

#### **Complete the quality order**

1. On the Action Pane, select **View**.

2. Select **Quality orders**.

3. Select **Results**.

4. Select **Edit**.

5. Set Result quantity to **5000**.

6. Set Test result to **98.5**.

7. Select **Save**.

8. Close the page.

9. Select **Validate**.

10. In the **Validated by** field, enter or select a value.

11. Select **OK**.

12. Close the page.

#### **Create a new sales order**

1. Go to **All sales orders**.

2. Select **New**.

3. In the **Customer account** field, enter or select **us-026**.

4. Select OK.

5. In the **Item number** field, enter or select **p5000**.

6. Set **Quantity** to **500000**.

7. Select **Save**.

#### **Complete the batch reservation and shipment**

1. Select **Inventory**.

2. Select **Batch reservation**.

3. Select **Batch attribute search**.

4. Select **Customer attributes**.

5. Select **OK**.

6. Select **Reserve lot**.

7. Refresh the page.

8. Close the page.

9. Select **Post packing slip**.

10. Select **OK**.

11. Close the page.

### Exercise \#19: Set a partial visibility catch weight item

At company USP2, a new catch weight item for sugar in  
20-pound bags must be created as item M7010.

The inventory manager is struggling to do the following:

- Create the new released product as a partial visibility catch weight item.

- After creating the item, create a new purchase order for 15 bags.

- The bags are to be received using the arrival overview process, and the
    total weight for the 15 bags of sugar should be specified

You are the MFG functional consultant and they asked you to help. Can you help?

You will have to do the following:

- Create the released product and set catch weight conversions

- Create purchase order for  
    15 bags of item M7010

- Create and post an arrival journal for the purchase order

#### Steps

#### **Create the released product and set catch weight conversions**

1. Go to **Product information management** \> **Products** \> **Released
    products**.

2. Select **New**.

3. In the Product number field, enter or select **M7010**.

4. In the Product name field, enter or select **Sugar in 20 lb. bags**.

5. In the **Catch weight** field, select **Yes**.

6. In the **Item model group** field, enter or select a value.

7. In the **Item group** field, enter or select a value.

8. In the **Storage dimension** group field, enter or select a value.

9. In the **Tracking dimension** group field, enter or select a value.

10. In the **Inventory unit** field, enter or select **lb**.

11. In the **Purchase unit** field, enter or select **lb**.

12. In the **Sales unit** field, enter or select **lb**.

13. In the **BOM unit** field, enter or select **lb**.

14. Select **OK**.

15. Select **Unit conversions**.

16. Select the **Inter-class conversions** tab.

17. Select **New** to open the drop dialog.

18. Set **Factor** to **20**.

19. In the **To** unit field, enter or select **lb**.

20. In the **From** unit field, enter or select **bag**.

21. Select **OK**.

22. Close the page.

23. In the **Purchase Unit** field, enter or select **bag**.

24. In the **Price** field, enter a number.

25. In the **CW unit** field, enter or select **bag**.

26. Set the **Minimum** quantity to **19**.

27. Set the **Maximum** quantity to **21**.

28. Select **Save**.

#### **Create a purchase order for 15 bags of item M7010**

1. Go to **Procurement and sourcing** \> **Purchase orders** \> **All purchase
    orders**.

2. Select **New**.

3. In the **Vendor account** field, enter or select a value.

4. Select **OK**.

5. In the **Item number** field, enter or select **m7010**.

6. Set CW quantity to **15**.

7. On the Action Pane, select **Purchase**.

8. Select **Confirm**.

9. Close the page.

#### **Create and post an arrival journal for the purchase order**

1. Go to **Inventory management** \> **Inbound orders** \> **Arrival
    overview**.

2. In the **Arrival overview profile name** field, enter or select a value.

3. Expand the **Arrival query details** FastTab.

4. Select **No** in the **Production orders** field.

5. Select **No** in the **Transfer orders** field.

6. Select **No** in the **Quarantine orders** field.

7. Select **Update**.

8. In the list, find and select the desired record.

9. Select the **Select for arrival** check box.

10. Select **Start arrival**.

11. Select **Journals**.

12. Select **Show arrivals from lines**.

13. Select **Journals**.

14. Select **Show arrivals from lines**.

15. Select the **Dimension** tab.

16. Select **Edit**.

17. Select to follow the link in the **Batch number** field.

18. Select **New**.

19. In the **Batch number** field, enter or select a value.

20. Select **Save**.

21. In the **Expiration date** field, enter a date.

22. Select **Save**.

23. Close the page.

22. In the **Batch number** field, enter or select a value.

23. Set **Quantity** to **295**.

24. Select **Save**.

25. Select **Post**.

26. Select **OK**.

27. Post Product Receipt and review Inventory

28. Select **Functions**.

29. Select **Product receipt**.

30. In the **Product receipt** field, enter or select a value.

31. Select **OK**.

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

- Create a purchase trade agreement

- Create a demand forecast

- Create a purchase order for  
    15 trays of item M9401

- Run net requirements and review the output

#### Steps

#### **Create a purchase trade agreement**

1. Go to **Product information management** \> **Products** \> **Released
    products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **m9401**.

3. On the Action Pane, select **Purchase**.

4. Select **Create trade agreements**.

5. Select **Edit**.

6. In the **Name** field, enter or select a value.

7. Select **Lines**.

8. In the **Item relation** field, enter or select **M9401**.

9. In the **Site** field, enter or select **1**.

10. In the Warehouse field, enter or select **11**.

11. Set **Amount in currency** to **175**.

12. Select **Post**.

13. Select **OK**.

14. Close the page.

#### **Create a demand forecast**

1. On the Action Pane, select **Plan**.

2. Select **Demand forecast**.

3. Select **New**.

4. In the **Model** field, enter or select a value.

5. In the **Date** field, enter a date.

6. In the **Site** field, enter or select **1**.

7. In the Warehouse field, enter or select **11**.

8. Set **CW quantity** to **25**.

9. Select **Save**.

10. Close the page.

#### **Create a purchase order for 15 trays of item M9401**

1. Go to **Procurement and sourcing** \> **Purchase orders** \> **All purchase
    orders**.

2. Select **New**.

3. In the **Vendor** account field, enter or select a value.

4. Select **OK**.

5. In the **Item number** field, enter or select **m9401**.

6. Set **CW quantity** to **15**.

7. Select **Confirm**.

#### **Run net requirements and review the output**

1. Select **Product and supply**.

2. Select **Net requirements**.

3. Select **Update**.

4. Select **Master planning**.

5. Select **OK**.

### Exercise \#21: Create a batch attribute for a potency item

At company USPI, part number M2004, ETDA, must be designated a
potency-controlled item for the Acidity batch attribute.

The target value for Acidity should be 1.7. Set up the batch attribute, assign
it to the product, and designate the product as a potency item.

The product manager is not sure how to configure the system to do that.

You were called as the MFG functional consultant to help.

Can you help?

You will have to do the following:

- Create a batch attribute

- Assign the attribute to  
    the item

- Assign potency information

#### Steps

#### **Create a batch attribute**

1. Go to **Inventory management** \> **Setup** \> **Batch** \> **Batch
    attributes**.

2. Select **New**.

3. In the **Attribute** field, enter or select **Acidity**.

4. In the **Description** field, enter or select **Acidity**.

5. In the **Attribute** enter or select field, select **Fraction**.

6. In the **Maximum** field, enter or select **10**.

7. In the **Increment** field, enter or select **.01**.

8. Select **Save**.

9. Close the page.

#### **Assign the attribute to the item**

1. Go to **Product information management** \> **Products** \> **Released
    products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **M2004**.

3. On the Action Pane, select **Manage inventory**.

4. Select **Product specific**.

5. Select **New**.

6. In the **Attribute relation** field, select **Acidity**.

7. Set **Minimum** to **1**.

8. Set **Maximum** to **3**.

9. In the **Target** field, enter or select **1.7**.

10. Select **Save**.

11. Close the page.

**Assign potency information**

1. Select **Edit**.

2. Select **Save**.

3. In the **Base attribute** field, enter or select a value.

4. Select **Save**.

### Exercise \#22: Modify and activate a copy of a potency item formula

At company USPI, they were reviewing all their items and they found out that part
M2004 has been determined to be a potency-controlled item.

The formula for item P2000 needs to be adjusted to set M2004 as an active
potency item.

The formula for P2000 should be modified to indicate the change, and item M2007
should be set as a compensating material for part M2004 with a compensation
factor of 1.

They are not sure how to reflect this in the system and they called you to help.

Can you help?

You will have to do the following:

- Copy the formula for item P2000

- Modify the M2004 and  
    M2007 lines

- Approve and activate the formula

#### Steps

#### **Copy the formula for item P2000**

1. Go to **Product information management** \> **Products** \> **Released
    products**.

2. Use the Quick Filter to filter on the **Item number field** with a value of
    **'p2000'**.

3. On the Action Pane, select **Engineer**.

4. Select **Formula versions**.

5. Select **New**.

6. Select **Formula and formula version**.

7. In the **Formula number** field, enter or select a value.

8. In the **Name** field, enter or select a value.

9. Select **Yes** in the **Copy** field.

10. In the **Site** field, enter or select a value.

11. Select **OK**.

12. In the **Formula version** field, enter or select the existing Formula version.

13. Select **OK**.

#### **Modify the M2004 and M2007 lines**

1. In the list, select row M2004.

2. In the **Ingredient type** field, select **Active**.

3. In the list, select row M2007.

4. In the Ingredient type field, select **Compensating**.

5. Select **Save**.

6. Select **Ingredients**.

7. Select **Compensation principle**.

8. In the **Active ingredient** field, select **M2004**.

9. Select **OK**.

10. Close the page.

#### **Approve and activate the formula**

1. In the list, select the old formula version.

2. In the **To date** field, enter a date.

3. In the list, select the new formula version.

4. In the **From date** field, enter a date.

5. Select **Approval**.

6. In the **Approved by** field, enter or select a value.

7. Select **Select**.

8. Select **Yes** in the **Do you also want to approve the formula?** field.

9. Select **OK**.

10. Select **Activate**.

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

- Create an attribute pricing expression

- Complete and post the trade agreement

####  Steps

#### **Create an attribute pricing expression**

1. Go to **Procurement and sourcing** \> **Setup** \> **Prices and discounts**
    \> **Attribute-based pricing details**.

2. Select **New**.

3. In the **Name** field, enter or select a value.

4. In the **Description** field, enter or select a value.

5. Select **Add variable**.

6. In the **Equation element type** field, select **Unit price**.

7. Select **Add variable**.

8. In the **Equation element type** field, select **Constant**.

9. Set **Constant** to **1.5**.

10. Select **Add variable**.

11. In the **Equation element type** field, select **Batch attribute - Target**.

12. In the **Attribute** field, select **Acidity**.

13. Select **Add variable**.

14. In the **Equation element type** field, select **Batch attribute - Actual**.

15. In the **Attribute** field, select **Acidity**.

16. Expand the **Equation** FastTab and in the **Equation** field, enter **AB(D/C)**.

17. Select **Validate equation**.

18. Close the page.

#### **Complete and post trade agreement**

1. Go to **Product information management** \> **Products** \> **Released
    products**.

2. Use the Quick Filter to filter on the **Item number** field with a value of
    **m2004**.

3. On the Action Pane, select **Purchase**.

4. Select **Create trade agreements**.

5. Select **Edit**.

6. In the **Name** field, select **Price**.

7. Select **Lines**.

8. In the **Item relation** field, enter or select **M2004**.

9. In the **Site** field, enter or select **1**.

10. In the **Warehouse** field, enter or select **11**.

11. Set **Amount in currency** to **4.7**.

12. In the **Attribute-based pricing ID** field, enter the pricing ID just
    created.

13. Select **Save**.

14. Select **Post**.

15. Select **OK**.

16. Close the page.

### Exercise \#24: Record a potency attribute upon receipt (Bonus)

A new batch of item M2004 is to be purchased into inventory and received, with
the batch attribute result being entered upon receipt.

You were asked to review the pricing of M2004 to verify that the calculation
meets the requirements of the attribute-based pricing

Can you perform this task?

You will have to do the following:

- Create a purchase order for item M2004

- Receive and enter a batch attribute value

- Invoice and review pricing

#### Steps

#### **Create a purchase order**

1. Go to **Procurement and sourcing** \> **Purchase orders** \> **All purchase
    orders**.

2. Select **New**.

3. In the **Vendor account** field, enter or select a value.

4. In the **Warehouse** field, select **13**.

5. Select **OK**.

6. In the **Item number** field, enter or select **m2004**.

7. Set **Quantity** to **800**.

8. On the Action Pane, select **Purchase**.

9. Select **Confirm**.

#### **Receive and enter a batch attribute value**

1. On the Action Pane, select **Receive**.

2. Select **Product receipt**.

3. In the **Product receipt** field, enter or select a value.

4. Select **Update line**.

5. Select **Registration**.

6. Select **Add registration line**.

7. Select to follow the link in the **Batch number** field.

8. Select **New**.

9. In the **Batch number** field, enter or select a value.

10. Select **Save**.

11. Close the page.

12. In the **Batch number** field, select the batch created.

13. In the **Actual value** field, enter or select a value.

14. Select **Confirm registration**.

15. Select **Save**.

16. Close the page.

#### **Invoice and review pricing**

1. In the **Parameters** group, for the **Quantity** field, select **Registered quantity**.

2. Select **OK**.

3. On the Action Pane, select **Invoice**.

4. Select **Invoice**.

5. In the **Number** field, enter or select a value.

6. In the **Invoice date** field, enter a date.

7. Select **Update match status**.

8. Select **Post**.

9. Select **Inventory**.

10. Select **Transactions**.

### Exercise \#25: Reporting and balancing batch orders (Bonus)

A new batch order is to be created for part P2000, including reserving batches
of the active ingredients, performing batch balancing, and posting the picking
list.

The production manager wants to create a production order and process the order
for a new batch of part P2000

The production manager is new to the system and wants you help.

Can you help?

You will have to do the following:

- Create a batch order for part P2000 and process the batch order through
    Start

- Complete batch reservation and balancing for active ingredients

- Post the picking list and report as a finished batch order

#### Steps

#### **Create a batch order for part P2000 and process the batch order through Start**

1. Go to **Production control** \> **Production orders** \> **All production
    orders**.

2. Select **New batch order**.

3. In the **Item number** field, enter or select **p2000**.

4. Select **Create**.

5. On the Action Pane, select **Production order**.

6. Select **Estimate**.

7. Select **OK**.

8. Select **Start**.

9. Select **OK**.

#### **Complete Batch Reservation and Balancing for active ingredients**

1. Select **Batch balancing**.

2. In the list, select row 2.

3. Select the **Marked** check box.

4. In the list, select row 4.

5. Select the **Marked** check box.

6. In the list, select row 5.

7. Select the **Marked** check box.

8. Select **Balance batch ingredients**.

9. Select **Confirm the formula**.

10. Select **OK**.

#### **Post the picking list and report as a finished batch order**

1. On the Action Pane, select **View**.

2. Select **Picking list**.

3. In the list, select the link for the picking list.

4. Select **Post**.

5. Select **OK**.

6. Close the page.

7. Close the page.

8. On the Action Pane, select **Production order**.

9. Select **Report as finished**.

10. Select to follow the link in the **Batch number** field.

11. Select **New**.

12. In the **Batch number** field, enter or select a value.

13. In the **Manufacturing date** field, enter a date.

14. Select **Save**.

15. Close the page.

16. In the **Batch number** field, select the created batch number.

17. Select **OK**.

## Case study 1C Lean manufacturing

### Exercise \#1: Create value streams

After defining and mapping the lean manufacturing value stream for USMF, you are
told to act as the value stream manager. You must create the value stream within
Microsoft Dynamics 365 Supply Chain Management

Can you do that?

You will have to do the following:

- Create a value stream

#### Steps

1. In **USMF** company go to **Production control \> Setup \> Lean production flow \> Value
    streams**.

2. Select **New** to create a new value stream.

3. Enter the following details for the new value stream:

4. Name: **SeaLeanVS**

5. Search Name: **SeaLean**

6. Manager: **Jodi Christiansen**

7. Select **Save**.

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

- Name: eBookProdFlow

- Description: eBook Production Flow

- Legal entity: USMF

- Value stream: SeaLeanVS

- Production group: 10

- Per cycle unit of measure: pcs

- Quantity per cycle: 1

- Average takt time: 1

- Minimum takt time: 1

- Maximum takt time: 2

- Period for actual cycle time (days): 1

You will have to do the following:

- Create a production flow model for SeaPFModel

- Create a production flow version for the USMF eBook production flow

- Set up the Takt and cycle times

#### Steps

#### **Create a production flow model**

1. Go to **Production control \> Setup \> Lean production flow \> Production
    flow models.**

2. Select **New**.

3. In the **Production flow model** field enter **SeaPFModel**.

4. In the **Model type** field enter **Throughput**.

5. In the **EPE Cycle in days** field enter **1**.

6. In the **Capacity shortage reaction** field enter **Add**.

7. In the **Planning period type** field enter **Day**.

8. In the **Planning time fence** field enter **10**.

9. In the **Capacity shortage reaction** drop down select **Postpone**.

10. Select **Save**.

#### **Create a production flow version**

1. Navigate to **Production control \> Setup \> Lean production flow \>
    Production flows**.

2. Select **New** on the action pane. A new production flow record is created.

3. In the **Name** field, enter **eBookProdFlow**.

4. In the **Description** field, enter **eBook Production Flow**.

5. In the **Legal entity** field, select **USMF**.

6. In the **Value stream** field, select **LeanProduction**.

7. In the **Production group** field, select **10**.

8. Select **Save**.

9. On the **Versions** FastTab, select **Add**.

10. Select **OK**.

#### **Set up the takt and cycle times**

1. Expand the **Versions** and **Version details** FastTabs.

2. In the **Per cycle unit of measure** field, select **pcs**.

3. In the **Quantity per cycle** field, enter **1**.

4. In the **Average takt time** field, enter **1**.

5. In the **Minimum takt time** field, enter **1**.

6. In the **Maximum takt time** field, enter **2**.

7. In the **Period for actual cycle time** (**days**) field, enter **1**.

8. Select **Save** in the action pane.

9. Note the **Plan status** field for the version is set to **Draft**.

10. Close all forms.

### Exercise \#3: Create a process activity

A new eBook stylus is being developed to compliment the eBook kits that are sold
at USMF.

The stylus is purchased from an outside vendor and configured at USMF.

A process activity is needed to configure the stylus and place it in stock for
use elsewhere.

Here are the details for the process activity:

- Name: Transfer Activity

- Process quantity: 10 pcs

- Operating unit: Lean Production

- Work cell: 1260

The company is not sure how to configure this and you were called as the MFG
functional consultant to help.

Can you help?

You will have to do the following:

- Create a process activity

#### Steps

1. Navigate to **Production Control \> Setup \> Lean Production Flows \>
    Production flows**.

2. Open the **Mid Range Speaker 2PF** production flow.

3. On the **Versions** FastTab, select the **Activities** button.

4. Select **Create new plan activity** button.

5. Select **Next**.

6. Enter **Transfer Activity** in the **Name** field.

7. Enter **10** in the **Process quantity** field.

8. In the **Unit** drop-down list, select **pcs**.

9. In the **Operating unit** drop-down list, select **LeanProduction**.

10. Select **Next**.

11. In the **Work cell** replenished drop-down list, select **1260**.

12. Set the **Update on hand on receipt** option to **Yes**.

13. Select **Next**.

14. Select **1260** in the **Replenishing** field.

15. Select **Finished product** in the **Product type** field.

16. Select **Next.**

17. Select Warehouse **13** in the **Transfer from location – warehouse** field.

18. Select location **13** in the **Transfer from location – location** field.

19. For the transfer to location:

20. Select **22** in the **Warehouse** field.

21. Select location **01-01-2-1** in the **Location** field.

22. Select **Shipper** in the **Freighted by** field.

23. Select **Next.**

24. Select **Queue time after** record.

25. Enter **4** in **time** field.

26. Select **hr** in the **time unit** field.

27. Enter **10** in **per quantity** field.

28. Select the **Runtime** record.

29. Enter **2** in **time** field.

30. Select **hr** in **time unit** field.

31. Enter **10** in **per quantity** field.

32. Select **Next.**

33. Select **Finish.**

### Exercise \#4 Create a new transfer activity

A new car speaker remote is being developed to complement the car speaker kits
sold at Contoso. The Standard speaker assembly production flow needs to be
amended to include a transfer activity to move the configured remote to the
Electrical Component warehouse

Details for production flow transfer activity are to the right

- Name: RemoteTransfer

- Process quantity: 10

- Operating unit: SeaLeanVS

- Replenishing resource group: 1250

- Update on hand on receipt: Yes

- Update on hand on pick: No

Transfer to warehouse ElComp, location Output

Freighted by shipper

- Runtime: 1 min per 25 pcs

You will have to do the following:

- Deactivate the current production flow version

- Create a new transfer activity

- Create the predecessor/successor relationship between the process and
    transfer activity with no constraints

#### Steps

#### **Deactivate the current production flow version**

1. Navigate to **Production Control \> Setup \> Lean manufacturing \>
    Production flows.**

2. Open the **CarSpeakProdFlow Standard speaker assembly** production flow.

3. On the **Versions** FastTab, select Version **1**.

4. Select **Deactivate**.

5. Select **OK**.

#### **Create a new transfer activity**

1. On the **Versions** FastTab, select **Activities**. The **Production flow
    activities** form opens.

2. Select **Create new plan activity** in the action pane.

3. Select **Next**.

4. Enter **RemoteTransfer** in the **Name** field.

5. In the **Activity type** drop-down list, select **Transfer**.

6. Enter **10** in the **Process quantity** field.

7. In the **Unit** drop-down list, select **pcs**.

8. In the **Operating unit** drop-down list, select **SeaLeanVS**.

9. Select **Next**. The **Create transfer activity** page opens.

10. In the **Replenishing** drop-down list, select **1250**.

11. Set the **Update on hand on receipt** check box to **Yes**.

12. Set the **Update on hand on pick** check box to **No**.

13. In the **Product type** field, select **Finished product**.

14. Select **Next**. The **Assign transfer locations** page opens.

15. In the **Transfer to location** group, in the **Warehouse** drop-down list,
    select **11**.

16. In the **Location** drop-down list, select **11**.

17. In the **Freighted by** drop-down list, select **Shipper**.

18. Select **Next**. The **Assign** activity **time** page opens.

19. In the **Time** field for the **Runtime** row, enter **1**.

20. In the adjacent **Time unit** drop-down list, select **min**.

21. In the **Per quantity** field, enter **25**.

22. Select **Next**. The **Confirm selection** page opens.

23. Select **Finish**. The wizard closes, and a new production flow activity
    appears in the list.

24. Select **Save** in the action pane.

#### **Create the predecessor/successor relationship between the process and transfer activity with no constraints**

1. Highlight the **Wiring Process** activity and, on the
    **Successor** tab, select the **Add successor** button.

2. Select the **Successor Activity** of **RemoteTransfer**.

3. For Cycle time ration, enter or select 1.

4. Select the **OK** button.

5. Activate the production flow version.

6. Close the **Production** flow activities form.

7. On the **Versions** tab, select the **Activate** menu button.

8. Select **OK**.

### Exercise \#5: Add a successor to the production flow activity and perform validation and activation

The production Manager wants to revise Mid-Range Speaker 2 PF production flow so
that the Transfer_W12_to_W11 activity is succeeded by the Process_Activity_1
activity.

Here are the details for production flow transfer activity relations:

- Constraint: 1 hour

- Cycle time ratio: 2

He is not quite sure how to do this revision and wants your help.

Can you help?

You will have to do the following:

- Add a successor to the production flow activity

- Perform validation and activation

#### Steps

#### **Add a successor to the production flow activity**

1. Navigate to **Production control** \> **Setup** \> **Lean production flow**
    \> **Production flows**.

2. Select the name of the Mid-Range Speaker 2 PF production flow.

3. On the **Versions** FastTab, select **Activities**.

4. In the list on the left, select the **00074 – Transfer from Warehouse 13 to
    51** activity.

5. On the **Successors** FastTab, select **Add successor**. The **Create
    activity relation** dialog opens.

6. In the **Successor** group, in the **Activity** drop-down list, select
    Activity **000082**.

7. Select the **Constraint** check box.

8. In the **Constraint value** field, enter **1**.

9. In the **Units** drop-down list, select **hr**.

10. In the **Cycle time ratio** field, enter **2**.

11. Select **OK**.

12. Select **Save** in the action pane.

13. Close the forms.

#### **Perform validation and activation**

The Mid-Range Speaker 2 PF production flow, Version 2 must be validated to
confirm that the changes have been correctly implemented.

1. Navigate to **Production control \> Setup \> Lean production flow \>
    Production flows.** The Production flows form opens.

2. Select the name of the Mid-Range Speaker 2 PF production flow. The
    **Production Flows** form for the selected production flow opens.

3. On the **Versions** FastTab, select Version **1**.

4. Select **Validate**. The **Validate production flow** dialog opens.

5. Select **OK**.

6. Select **Save** in the action pane.

7. Close the forms.

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

- Create the Kanban rule for the process activity

- Create the Kanban rule for the transfer activity

- Plan a Kanban on the Kanban board

#### Steps

#### **Create the Kanban rule for the process activity**

1. Navigate to **Product information management \> Lean manufacturing \> Kanban
    rules**.

2. Select **New**.

3. Select the **First plan activity** called **SpeakerTestAndPackaging**.

4. Expand the **Details** FastTab.

5. In the **Product**, select **L0001**.

6. Expand the **Quantities** FastTab

7. Enter a **Default quantity** of **100**.

8. Enter a **Fixed Kanban quantity** of **4**.

9. Expand the **Kanban and cards** FastTab.

10. Select the **Circulating cards** check box.

11. Change the **Card assignment** to **Automatic**.

12. Select **Save**.

13. Select the **Create cards** button.

14. Deselect the **Print new cards** box.

15. Select **Create**.

16. Switch to the **Kanbans** FastTab.

17. Select **Add**.

18. Verify that the default number of new Kanbans is 4.

19. Select **Create**.

20. Close all forms.

#### **Creating the Kanban rule for the transfer activity**

1. Navigate to **Product information management \> Lean manufacturing \> Kanban
    rules**.

2. Select **New**.

3. Change the **Type** to **Withdrawal**.

4. Update the **First plan activity** to **ReplenishSpeakerComponents**.

5. Expand the **Details** FastTab.

6. Enter the **Product L0001**.

7. Switch to the **Quantities** FastTab.

8. Enter the **Default quantity** of **10**.

9. Enter the **Fixed Kanban quantity** of 4**.**

10. Select **Save**.

11. Switch to the **Kanbans** FastTab.

12. Select **Add**.

13. Verify that the number of new Kanbans defaults to 4.

14. Select **Create**.

15. Close all forms.

#### **Planning a Kanban on the Kanban Board**

1. Navigate to **Production control \> Kanban \> Kanban job scheduling**.

2. Change Work cell to **1250**.

3. In the **Display job status** field select **Not scheduled**.

4. Select a Kanban job from the unplanned Kanban jobs, and then select the
    **Schedule** button. Repeat for the remaining Kanban jobs of your choice.

### Exercise \#7: Process scheduled Kanbans for process and transfer jobs

After setting up the fixed Kanban rule from the previous exercise, the company
wonders if you can use the Kanban board to start processing scheduled Kanban
jobs.

Can you?

You will have to do the following:

- Process Kanbans on the Kanban board for process jobs

- Process Kanbans on the Kanban board for transfer jobs

#### Steps

#### **Process Kanbans on the Kanban board for process jobs**

The scheduled Kanbans are now ready to be processed. The **Production
control\>Kanban\>Kanban board for process jobs** will be used to prepare, start,
and complete the Kanbans.

1. Go to **Production control \> Kanban \> Kanban board for process jobs**.

2. When you open this form for the first time, all jobs from all work cells are
    shown. You can select the **Work cell** to filter the jobs.

3. Change the **Work cell** to **1250**.

4. Select the appropriate Kanbans to prepare.

5. Select **Prepare**.

6. To start the Kanbans, select the **Start** button.

7. To complete the Kanbans, select **Complete**.

#### **Process Kanban on the Kanban board for transfer jobs**

The manufactured Kanban is now ready to be transferred to its final location.
The Kanban board for transfer jobs will be used to start and complete the
Kanban.

1. Go to **Production control \> Kanban \> Kanban board for transfer jobs**.

2. When entering the board for the first time you see all jobs from all
    production flows. Alternately, you can expand **Filters** FastTab and change
    **Production flow** to only show jobs for a specific production flow, such
    as Mid-Range Speaker 2 PF.

3. Select the Kanbans of your choice, as long as they have a card number.

4. To start the transfer, select **Start**.

5. To complete the transfer, select **Complete**.

### Exercise \#8: Fulfill a sales order by planning a Kanban and produce an item (Bonus)

A sales order has been received for a green speaker set, which triggers event
Kanbans for the speaker set on the packaging work cell and the speaker kits on
the speaker assembly work cell.

The company want to record the production of the speaker kits and speaker set to
fulfil the customer sales order

How would you do that?

You will have to do the following:

- Create a sales order for the Kanban line event

- Plan the Kanbans

- Transfer the speaker set

#### Steps

#### **Create a sales order**

1. Navigate to **Sales and marketing \> Sales orders \> All sales orders**.

2. Select **New**.

3. Select the **Customer account** as **US-016**.

4. Select **OK**.

5. Enter **Item number** of “**L0026**”.

6. Enter **Quantity** of “**12.00**”.

7. Select **Update confirmed date**.

8. Select a **Site** of **1** (scroll or tab right).

9. Select a **Warehouse** of **13**.

10. Select a **Location** of **13**.

11. If **Location** is not set on the sales order, go to **Sales order line** \>
    **Display** and select the **Dimensions** button. Select the location and
    configuration.

12. Select Configuration 01.

13. When you save, if the date cannot be promised, select **Update confirmed
    ship date**.

14. Select the **Product and supply \> View pegging tree** menu button to view
    the event Kanbans created for the sales order.

#### **Plan the Kanbans**

1. Navigate to **Production control \> Kanban \> Kanban schedule board**.

2. Change **Work cell** to **1250**.

3. Plan the Kanban for 1250 by selecting the Kanban job in the board.

4. Close all forms.

5. Navigate to **Production control \> Kanban \> Kanban board for process
    jobs**.

6. Select the Change cell button.

7. Change **Work cell** to **1250**.

8. Highlight the desired Kanbans and select **Start**.

9. Select **Complete**.

10. Select the **Change cell** button.

11. Change **Work cell** to **1250**.

12. Highlight a Kanban and switch to the **Pegging** FastTab on the **Kanban
    board for process jobs** work cell form. View the complete lower level
    speaker set Kanbans on the pegging tree.

13. Select **Start**.

14. Select **Complete**.

#### **Transfer the speaker set**

1. Navigate to **Production control \> Kanban \> Kanban board for transfer
    jobs**.

2. Expand **Filters** FastTab.

3. Select a **Production Flow**.

4. Select **Update picking list** on the Transfer tab in the action pane.

5. Select **Add picking** line.

6. Select **Confirm** pick all.

7. Close the form.

8. Select **Start**.

9. Select **Complete**.
