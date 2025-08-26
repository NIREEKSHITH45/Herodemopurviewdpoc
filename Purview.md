## Azure Purview Setup

1. From **Azure Portal**, search for **purview** in the resource group and click on the resource.

   ![](./media/purview-1.png)

2. The Azure Purview resource window will open, **click** on Open Azure Purview Studio and the Azure Purview Studio will open in a new window.
  
   ![](./media/purview-2.png)

3. In Azure Purview Portal, go to **Data Map**, choose **Data Sources**, and then click **Register** to add a new data source.

   ![](./media/gd20.png)

4. Select **Azure SQL Database** and then click **Continue**.

   ![](./media/image2.png)

5. On the Register data source page,provide the **data source name** select the required **subscription**, choose the **SQL Server** you want to connect to, accept the default endpoint, and then click **Register**.

   ![](./media/image3.png)

6. Click **Register** to add a new data source, select **Fabric**, and then choose **Continue**.

   ![](./media/image5.png)

7. On the Register data source page, enter the data source name and click **Register**.

   ![](./media/image6.png)

8. You can follow the same steps to add any other data sources you need.

   ![](./media/image7.png)

## Adding the Governance domains

1. From the left navigation menu, go to **Solutions** and then select **Unity Catalog**.

    ![](./media/gd1.png)

2. Expand **Catalog Management**, select **Governance Domains**, and then click **+ New Governance Domain**.

    ![](./media/gd2.png)

3. Enter the required **Name** and **Description**, select the Type, and then click **Next**.

    ![](./media/gd3.png)

4.  On the Custom Attributes page, accept the default settings and click **Create** to finish creating the governance domain.

    ![](./media/gd4.png)

5. To assign permissions for a governance domain, select the domain, open Roles, click Add, and select **Governance Domain Owner**.

    ![](./media/gd5.png)

## Creating the Sensitivity label

1. From the left navigation menu, go to **Solutions** and then select **Information Protection**.

    ![](./media/gd6.png)

2. From the left navigation, select **Sensitivity Labels** and click **+ Create a label**.

    ![](./media/gd7.png)

3. On the Label Details page, enter the required information such as **Name**, **Display Name**, and **Description**, then click **Next**.

    ![](./media/gd8.png)

4. In the **Scope** section, select the required scope where the sensitivity label should be enabled

    ![](./media/gd9.png)

5. In the **Items** section, select Control access and click **Next**.

    ![](./media/gd10.png)

6. In the Access control section, select Configure access control, assign permissions to the sensitivity label by choosing the required users, and then click **Next**.

    ![](./media/gd11.png)

7. Review the settings, then click **Create label** to finalize.

    ![](./media/gd12.png)

8. After creating the sensitivity label, create a policy label on top of it.

    ![](./media/gd13.png)

9. m 

    ![](./media/gd14.png)

10. m

    ![](./media/gd15.png)

11. m

    ![](./media/gd16.png)

12. m

    ![](./media/gd17.png)

13. m

    ![](./media/gd18.png)

14. m 

    ![](./media/gd19.png)

    