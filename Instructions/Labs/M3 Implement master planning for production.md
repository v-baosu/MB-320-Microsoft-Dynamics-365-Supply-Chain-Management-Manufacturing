Module 3 Implement master planning
==================================

Case study 2 Master planning
----------------------------

### Exercise \#1: Firm a planned order and change the order type

The Planning Manager at USMF, wants to know how to setup, manage and use the
master planning module and be able to process planned orders

He is aware that he should have a source of demand in the system for the items,
so that when master planning is run it can provide some planned orders.

Sources of demand can be sales orders, sales forecasts, safety stock, scheduled
Kanbans, production orders, and others

This manager asked you to help him to test this out.

Would you be able to help?

You will have to do the following:

-   Create and confirm a sales order

-   Run master planning

-   Firm a planned order

-   Review the purchase order

-   Change a planned order type

-   Review the planned order and verify the change

#### Steps

**Create and confirm a sales order**

1.  Open Sales and marketing \> Sales orders \> All Sales orders.

2.  Click New.

3.  Type US-013 for customer Pelican Wholesales in the Customer account field.

4.  Accept the default settings in all other fields. Click OK.

5.  In the Sales order form, open the Sales order Lines FastTab.

6.  TypeD0003 in the Item number field.

7.  Type 12 in the Quantity field.

8.  Accept the default values for the remaining fields.

9.  Click Save.

10. Click Confirm sales order from the Sell tab in the action pane.

11. Accept all the default settings in the Confirm sales order form.

12. Click OK.

13. Click OK.

14. Close all pages.

**Run master planning**

1.  Open Master Planning \> Master Planning \> Run \> Master Planning.

2.  In the Master plan field, select StaticPlan.

3.  Click OK.

** Firm a planned order**

1.  Open Master planning \> Master planning \> Planned orders.

2.  In the Planned orders page, select the line for order number 004261.

3.  Click the Firm button in the action pane.

4.  In the Firming page, in the Update marking field, select Standard.

5.  Click OK.

**Review the purchase order**

1.  Open Procurement and sourcing \> Purchase orders \> All purchase orders.

2.  In the All purchase orders page, sort the list by the Delivery date field.

3.  Verify the firmed order is now listed with a status of Open order.

4.  Close the pages.

**Change a planned order type**

1.  Open Master planning \> Master planning \> Planned orders.

2.  In the Planned orders page, select the line for order number 004262.

3.  Select the Planned order tab in the action pane.

4.  Click the Change to drop-down arrow in the Maintain area.

5.  Select Planned production order.

6.  In the Change to planned production order page, click OK.

**Review the planned order and verify the change**

1.  In the Planned orders list page, verify that the Reference field has been
    updated to Planned production orders for order number 004262.

2.  Close the pages.

### Exercise \#2: Create an intercompany planning group and assign an item allocation key

The materials and production scheduling manager, wants to develop a new
intercompany planning group.

Assemblies are shipped from DEMF to USMF. While at USMF they are painted and
finished with the North American logo.

Then they are transferred to the USRT operation for sale.

She wants to use plans 20, DynPlan, and MasterPlan respectively to accomplish
this goal

She asked for your help.

You will need to validate the intercompany master planning parameters and
perform some setups before running the intercompany master plan. You will also
need to run the intercompany plan using the intercompany planning  
group that you created and view the results in the intercompany supply and
demand form

Can you help?

You will have to do the following:

-   Create an intercompany planning group

-   Assign an item allocation key

-   Run an intercompany  
    master plan

#### Steps

**Create an intercompany planning group**

1.  In the USMF Company, click **Show navigation pane**.

2.  Open **Master planning \> Setup \> Intercompany planning groups**.

3.  Click **New** in the Action pane.

4.  Enter **Intercompany Extended Group** in the **Name** field.

5.  Click **Save**.

6.  Click **New** on the tool bar for **Intercompany planning group members**
    tab.

7.  Select **DEMF** in the **Legal entity** field.

8.  Enter **0** in the **Scheduling sequence** field.

9.  Click **New** on the tool bar for Intercompany planning group members tab.

10. Select **Legal entity - DEMF**, **Scheduling sequence - 0, Master plan –
    20.**

11. Leave the **Automatic Copy to Static Plan** and **Automatic Copy to Dynamic
    Plan** checkboxes blank.

12. Click **Save.**

**Assign an item allocation key**

1.  Select **Master Planning \> Demand Forecasting \> Item Allocation Keys**.

2.  Select **Wizard**.

3.  Select **Apples** from **Item Group** drop-down menu.

4.  Type **Apples Group** in **Name** box.

5.  Click **Next.**

6.  Click **Next** on the **Overview** page after verifying the information is
    correct.

7.  Click **Finish** on the **Completed** page after verifying the information
    is correct.

8.  Select **Demand Forecasting \> Intercompany Planning Groups**.

9.  Select **Item Allocation Keys.**

10. Select **Apples** under the **Unassigned Item Allocation Keys** box, then
    select **\>** to move it to the **Assigned Allocation Keys** box.

**Run an intercompany master plan**

1.  In the USMF company, click **Show navigation pane**.

2.  Open **Master planning** \> **Run** \> **Intercompany master planning**.

3.  Select **60** for **Intercompany planning group**.

4.  Select **2** for **Number of intercompany planning iterations**.

5.  Select **Regeneration** for **First iteration**.

6.  Select **Net change** for **Subsequent iteration**.

7.  Select **Track processing time** setting slider to **No**.

8.  Set **Number of threads** to **0**.

9.  Click **Run in the background**.

10. Click **OK**.

11. Open **Master planning \> Inquiries and reports \> Intercompany master
    planning \> Intercompany supply and demand**.

### Exercise \#3: Plan a production schedule from a master planning run (Bonus)

USMF has decided to plan the L0025 WLAN Radio software installed product from a
production schedule that results from a master planning run

They are not sure how to do so and asked you to help.

Can you help?

You will have to do the following:

-   Configure item coverage

-   Create a scheduled  
    Kanban rule

-   Run master planning

#### Steps

**Configure item coverage:**

1.  Go to **Master planning \> Setup \> Item coverage**.

2.  Use the Quick Filter to filter on the Item number field with a value of
    **L0025**.

3.  Click **Item coverage**.

4.  Click **New**.

5.  Set **Minimum** to **150.00**.

6.  In the **Warehouse** field, enter or select **13**.

7.  Click the **General** tab.

8.  Select the **Override time fences** check box.

9.  In the **Automatic firming time fence (days)** field, enter **1**.

10. Click the **Lead time** tab.

11. Select the **Production** check box.

12. In the **Production time** field, enter **1**.

13. Select **Yes** in the **Working days** field.

14. Click **Save**.

15. Close all forms.

**Create scheduled kanban rule**

1.  Go to **Product information management \> Lean manufacturing \> Kanban
    rules**.

2.  Click **New**.

3.  In the **Replenishment strategy** field, select **Scheduled**.

4.  In the **First plan activity** field, enter or select **Final assembly**

5.  Collapse the **Kanban rule** section.

6.  Expand the **Details** section.

7.  In the **Product** field, enter or select **L0025**.

8.  In the **Configuration** field, enter or select **01**.

9.  Click Save.

10. Close the page.

**Run master planning**

1.  Go to **Master planning \> Master planning \> Run \> Master planning**.

2.  In the **Master plan** field, enter or select **DynPlan**.

3.  Expand the **Records to include** to include section.

4.  Click **Filter**.

5.  In the Criteria field, type **L0025**.

6.  Click **OK**.

7.  Click **OK**.

**View results**

1.  Go to **Master planning \> Master planning \> Planned orders**

2.  Use the Quick Filter to filter on the Item number field with a value of
    **L0025** and press **Enter**.

3.  Review planned kanbans for **L0025**.

4.  Select the line with quantity of 150.

5.  Click **Supply schedule** in the view tab on the action pane.

6.  Verify the results. As you have learned, the kanbans were generated by
    Master planning.
