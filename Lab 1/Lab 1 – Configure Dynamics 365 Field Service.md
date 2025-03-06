# Lab 1 – Configure Dynamic 365 Field Service

### Estimate Time: 45 mins

## Introduction

In this lab, you will configure **Microsoft Dynamics 365 Field
Service**, enabling efficient resource scheduling, work order
management, and service automation. You will begin by signing up for a
trial, configuring essential settings such as Bing Maps, resource
scheduling, and work order types. Additionally, you will create and
manage customer accounts, bookable resources, and install the **Field
Service Outlook Add-in with Copilot** to enhance productivity. By
completing this lab, you will gain hands-on experience in setting up and
managing **Field Service operations** within **Dynamics 365**.

## Exercise 1: Sign up in the Microsoft Field Service

1.  Open the Edge browser and navigate to **Microsoft Dynamics 365** by
    visiting +++https://www.microsoft.com/en-in/dynamics-365/+++

    ![](./media/image1.png)

2.  On the middle of the screen click on the **Try for free.**

    ![](./media/image2.png)

3.  Locate **Dynamics 365 Field Service** and click on the **"Try for
    free"** button.

    ![](./media/image3.png)

4.  In the *Let's get started* screen, enter the **M365 tenant** that
    were provided to you -as part of your lab environment. Accept the
    license agreement. (If you are prompted to enter a phone number, you
    can enter 0123456789.)

5.  Select **Start your free trial**. (If prompted, select **Launch
    Trial** in the pop-up.)

    ![](./media/image4.png)

6.  Enter the **M365 password** in the password field and
    click on the **Sign in** button. Your trial will launch. It may take
    a few minutes for your environment to open.

    ![](./media/image5.png)

7.  Click on the **Cross** icon to close the what’s new window.

    ![](./media/image6.png)

## Exercise 2 - Configure Dynamics 365 Field Service

### Task 1 - Enable Bing Maps to use with Resource Scheduling

1.  In the Dynamics 365 Field Service app, click the **Service** from
    the bottom-left of the sitemap and select **Resource** to change the
    area, and under the **Administration** group select **Scheduling
    Parameters**.

     ![](./media/image7.png)

     ![](./media/image8.png)

2.  Click on the **Resource Scheduling** record.

     ![](./media/image9.png)

3.  Locate the **Connect to Maps** field. This should be set to **Yes**.

4.  If Connect to Maps is set to No, set it to **Yes** and
    click **OK** from the popup.

5.  Click **Save and Close**.

     ![](./media/image10.png)

### Task 2 – Configure the Categories

1.  Click on the **Categories** under **Resources** and then click on
    the **+ New** button from top bar.

    ![](./media/image11.png)

2.  In the name field, enter +++**Air Conditioner Service**+++ in the field.
    Click on the **Save and Close** button from top bar.

    ![](./media/image12.png)

### Task 3 – Configure the Work Order Type

1.  Click on the **Resource** from the bottom left corner and select **Setting**
    area.

    ![](./media/image13.png)

2.  In the Field service setting area, click on the **Work Order Type**,
    then click on the **+ New.**

    ![](./media/image14.png)

3.  In the Name field enter +++**AC Repair and Maintenance**+++ and then click
    on the **Save and close.**

    ![](./media/image15.png)

### Task 5 – Configure the Incident Type 

1.  In the Field service setting area, click on the **Incident Types**
    and then click on the **+ New.**

    ![](./media/image16.png)

2.  In the Name field enter +++**Cooling Issue**+++

    ![](./media/image17.png)

3.  Click on the **Detail**, In **Estimate Duration Field** and select
    **2 hours.**

    ![](./media/image18.png)

4.  From the top bar click on the **Save and Close**.

    ![](./media/image19.png)

### Task 6 - Enable an entity for scheduling

1.  Click on the **Field service app** and select the **Resource scheduling**
    app.

     ![](./media/image20.png)

     ![](./media/image21.png)

2.  In Resource Scheduling, from bottom left corner, change area as
    **Settings area**. Under **Scheduling**, select **Administration**.
    Select **Enable Resource Scheduling for Entities.**

     ![](./media/image22.png)

     ![](./media/image23.png)

3.  In the **Enable New Entity** section, under Add Entity, Enter
    +++**Contact**+++ in the field and select **Contact** from the result.

     ![](./media/image24.png)

4.  Click on the **Book Relationship** and **Requirement Relationship**
    fields and select **Create New Relationship.**

    ![](./media/image25.png)

5.  Select **Publish** **Customization**.

     ![](./media/image26.png)

## Exercise 3 - Create and Manage Customer Accounts

1.  Click on the **Resource Scheduling app** from top and select **Field Service app** from the app option.

     ![](./media/image27.png)

     ![](./media/image28.png)

2.  In Field Service, under **Customers**, select **Accounts**, and then
    select **+New**.

    ![](./media/image29.png)

3.  Enter the **Account Name** as +++**Contoso Retail**+++ in the field.

     ![](./media/image30.png)

4.  Click on the Servicing, click on Price List section, press enter and select **Default USD**

    ![](./media/image31a.png)

5.  Select **Geo Code** at the top of the form.

     ![](./media/image32.png)

6.  Click on the **Pencil icon** next to address and enter +++**Stratton Common**+++ in the Street 1 field.

7.  In **City** Field Enter +++**Fremont**+++

8.  In the **State/Province** field enter +++**CA**+++

9.  In **Zip/Post Code** field enter +++**34567**+++

10. In the **Country/region** field enter +++**United States**+++

11. After entering address click on the **Done** button.

    ![](./media/image33.png)

    ![](./media/image34.png)

12. Click on the **OK** button to configure the Geocode Address.

    ![](./media/image35.png)

13. Click on the **Save and Close** to complete the process.

    ![](./media/image36.png)

14. Click on the **Contoso Retail** check box, then click on the
    **Activate** button form top bar. Again, click on the **Activate**
    button.

    ![](./media/image37.png)

    ![](./media/image38.png)

## Exercise 4 - Create a work order

1.  In the Scheduling section, select **Work Orders** and then
    select **New**.

     ![](./media/image39.png)

2.  At a minimum, enter information in the following required fields.

    1.  **Status** – Select Unscheduled

    2.  **Priority** – Select Normal

    3.  **Service Account** – Click on the Service account field. Enter
        +++**Contoso Retail**+++ in the field and select the result.

    4.  **Work order type** - Click on the Work order type field. Enter
        +++**AC Repair and Maintenance**+++ in the field and select the
        result.

    5.  **Incident type** - Click on the Incident type field. Enter
        +++**Cooling Issue**+++ in the field and select the result.

    6.  **Agreement** - Click on the Agreement field. Press enter and
        select the +++**sample agreement**+++ from the result.

3.  Select **Save and close** from top.

     ![](./media/image40.png)

## Exercise 5 – Create Contact and Setup Bookable Resource

### Task 1 – Create Contact in Microsoft Field Service

1.  In the Service area, click on the **Contacts** and then click on **+ New.**

    ![](./media/image41.png)

2.  Enter the given below details in the respected fields:

    1.  Click on the First Name field and enter +++**Mark**+++ as name.

    2.  Click on the Last Name Field and enter +++**Brown**+++ as last name.

    3.  Click on the Job title field and enter +++**Field Engineer**+++ in the
        field.

    4.  Click on the Account name field and enter +++**Contoso Retail**+++ in
        the field and select the appearing result.

     ![](./media/image42.png)

3.  Click on the **Save and close** button from the top bar.

    ![](./media/image43.png)

### Task 2 - Create other bookable resources

1.  In Field Service, change to the **Resources** area from bottom left
    side and go to **Resource** --> **Resources** and select **New**.

     ![](./media/image44.png)

     ![](./media/image45.png)

2.  In the Resource type field, select **Contact**. In the Contact Field
    select **Mark Brown**. In the time zone field, select **(GMT) Coordinate Universal Type.**

    ![](./media/image46.png)

3.  Click on the **Save and Close** from the top bar.

    ![](./media/image47.png)

### Task 3 – Configure the Working Hours

1.  Go to **Resource** --> **Resources** and open Mark Brown resource. In
    Mark brown resource click on the **Work Hours.**

     ![](./media/image48.png)

     ![](./media/image49.png)

2.  Click on the Working hour on the calendar and then select **Edit --> All events in the series.**

    ![](./media/image50.png)

3.  On the weekdays, deselect the **Sunday and Saturday**. Set start
    time as **10 AM** and End time as **06 PM** and then click on the **Save**
    button.

4.  Click on the **OK** button on the popup window.

    > Note: The start and end time will set automatically according to the
    universal time.

    ![](./media/image51.png)

    ![](./media/image52.png)

5.  Click on the **Save and Close** button from the top bar.

    ![](./media/image53.png)

### Task 4 - Add characteristics, and categories

1.  Click on the **Resource** under Resources and click on the **Mark Brown** source.

    ![](./media/image48.png)

2.  Click on the **Related** option and select **Resource Characteristics.**

    ![](./media/image54.png)

3.  Click on the **+ New Bookable** Resources.

    ![](./media/image55.png)

4.  Click on the Skill Name field and select **+ New Characteristics**.

    ![](./media/image56.png)

5.  In the Name filed enter +++**AC Repair**+++, then click on the **Save and Close.**

    ![](./media/image57.png)

6.  Again, click on the **Save and Close** button.

    ![](./media/image58.png)

7.  Select **Related** --> **Resource Category Assns**.

    ![](./media/image59.png)

8.  Select **New Resource Category Assns**.

     ![](./media/image60.png)

9.  Select **Air Conditioner Service** Category from the lookup. Click
    on the **Save** and then **back** button.

     ![](./media/image61.png)

10. Again, click on the **Save and Close** from the top bar.

    ![](./media/image62.png)

## Exercise 6 – Enable Work order summary report

1.  Navigate back to **Service** **area** in field service. Click on the
    **service** form the bottom left corner and select **Settings**
    area.

![](./media/image63a.png)

2.  A Field Service administrator must **enable** the report in 
    **Analytics and Insight** \> **Settings** \> **Field Service
    historical analytics** \> **Manage**. After enabling click on the
    **Save and Close.**

![](./media/image64a.png)

![](./media/image65a.png)

3.  Navigate back to **service** **area** of field service, and click on
    the **Reports** under Analytics and Insights. It takes up to **24
    hours to setup**. Proceed with next exercise while its creating.

![](./media/image66a.png)

##  Exercise 7 - Install Field Service Outlook Add-in with Copilot 

### Task 1 – Login Into Microsoft Admin Portal

1.  Open the Edge browser and navigate to **Microsoft Admin Portal** by
    visiting +++admin.microsoft.com+++

2.  Enter the **M365 Admin tenant ID** in the Email field and click on the
    **Next** button.

    ![](./media/image63.png)

3.  Enter **Password** in the field and click on the **Sign In** button.

    ![](./media/image64.png)

### Task 2 – Install Field Service Outlook Add-in with Copilot

1.  under **Settings,** click on **Integrated apps**.  

    ![](./media/image65.png) 

2.  Scroll down, click on **Get apps.**

     ![](./media/image66.png) 

3.  In the search box, enter +++**Field service**+++ and then click on **Get it now** under **Dynamics 365 Field Service for Outlook,** and again
    click on **Get it now** to confirm your information.  

     ![](./media/image67.png)

     ![](./media/image68.png)

 

4.  You will be navigated to **Microsoft Admin center--> Integrated Apps**. On the **Assign users** page, select 
    **Entire organization** and then select **Next**. 

     ![](./media/image69.png)


5.  On the **Accept permission requests** page, select **Accept permissions** and re-login on popup window.

     ![A screenshot of a computer Description automatically generated](./media/image70.png)


6.  Sign in with your **Office 365 admin tenant** credentials on the pop-up window. 

     ![A screenshot of a computer Description automatically generated](./media/image71.png)

7.  Select **Next** on the **Accept permission requests** page. 

     ![A screenshot of a computer Description automatically generated](./media/image72.png)


8.  On the **Review and finish deployment** page, select **Finish
    deployment**. 

     ![A screenshot of a computer Description automatically generated](./media/image73.png)

9.  Select **Done** once the deployment is completed. It can take up to six hours for the app to appear in Outlook.

     ![A screenshot of a computer Description automatically generated](./media/image74.png)

## Conclusion

By completing this lab, you have successfully configured Microsoft
Dynamics 365 Field Service for efficient scheduling and resource
management. You have learned how to enable Bing Maps, create work
orders, set up customer accounts, configure bookable resources, and
install the Field Service Outlook Add-in with Copilot. These
configurations enhance service delivery, streamline operations, and
improve customer interactions. You are now equipped with the
foundational skills needed to manage Field Service deployments
effectively.
