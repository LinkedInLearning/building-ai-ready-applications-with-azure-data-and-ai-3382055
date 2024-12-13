# Create and Connect to an Azure SQL Database

This section you will be creating and connecting to an Azure SQL Database.

## Azure SQL Database create and connect

### Create a free Azure SQL Database

1. Ensure you have an Azure account to log into the Azure Portal. Need a free account? Sign up for one [here](https://azure.microsoft.com/en-us/free).


1. Navigate to the [Azure Portal](https://portal.azure.com/#home), and in the upper left corner, click the menu button.

1. Then, select **Create a Resource**.

    ![A picture of selecting Create a Resource from the Azure Portal menu](./media/Building%20AI-Ready%20Applications-7.png)

1. In the category menu, select **Databases**.

    ![A picture of selecting Database from the category menu](./media/Building%20AI-Ready%20Applications-8.png)

1. Then click **create** for **SQL Database**.

    ![A picture of selecting create for SQL Database](./media/Building%20AI-Ready%20Applications-9.png)

1. On the **Create SQL Database** page, click the **Apply offer (Preview)** button for the free Azure SQL Database.

    ![A picture of clicking the Apply offer (Preview) button for the free Azure SQL Database on the Create SQL Database page](./media/Building%20AI-Ready%20Applications-10.png)

1. In the **Project details** section of the page, select a subscription and a Resource group if you have an existing one. 

    ![A picture of select a subscription and a Resource group on the Project details section of the page](./media/Building%20AI-Ready%20Applications-11.png)

    Otherwise you can create a Resource group by clicking the **Create new** button.

    ![A picture of creating a Resource group by clicking the **Create new** button](./media/Building%20AI-Ready%20Applications-12.png)

1. Next, in the **Database details** section of the page, name your database with the **Database name** field.

    ![A picture of naming your database with the Database name field in the Database details section of the page](./media/Building%20AI-Ready%20Applications-13.png)

1. For the **Server**, click the **Create new** button.

    ![A picture of naming your database with the Database name field in the Database details section of the page](./media/Building%20AI-Ready%20Applications-14-1.png)

1. On the **Create SQL Database Server** page, enter a **server name** and choose a **Location** using the dropdown menu.

    ![A picture of entering a server name and choosing a Location using the dropdown menu on the Create SQL Database Server page](./media/Building%20AI-Ready%20Applications-14.png)

1. Now, in the **Authentication** section, select the **radio button** for **Use Microsoft Entra-only authentication**.

    ![A picture of selecting the radio button for Use both SQL and Microsoft Entra authentication in the authentication section](./media/Building%20AI-Ready%20Applications-15.png)

1. Click the **Set admin** link in the **Set Microsoft Entra admin** section. 

    ![A picture of clicking the Set admin link in the Set Microsoft Entra admin section](./media/Building%20AI-Ready%20Applications-16.png)

1. Using the **Microsoft Entra ID** blade, find your user account and select it as an admin. Then click the **Select** button on the bottom left.

    ![A picture of select your account as the Entra ID admin](./media/Building%20AI-Ready%20Applications-17.png)

1. Click the **OK** button on the bottom left of the page.

1. Back on the **Create a SQL Database** page, verify the values you entered and that the free database offer has been applied. 

    ![A picture of verifying the values and that the free database offer has been applied](./media/Building%20AI-Ready%20Applications-19.png)

1. On the top of the page, click on the **Additional settings** tab.

    ![A picture of clicking on the Additional settings tab](./media/Building%20AI-Ready%20Applications-20.png)

1. On the Additional settings page, find the **Data source** section on the top.

    ![A picture of the Data source section on the Additional settings page](./media/Building%20AI-Ready%20Applications-21.png)

1. Use the **Use existing data** toggle

    ![A picture of the Use existing data toggle](./media/Building%20AI-Ready%20Applications-22.png)

    to set it to **Sample** by clicking on it.

    ![A picture of clicking on the sample option of the Use existing data toggle](./media/Building%20AI-Ready%20Applications-23.png)

    and in the pop-up dialog, select **OK** for the question **"Do you want to continue"**.

    ![A picture of selecting OK for the question Do you want to continue in the pop-up dialog](./media/Building%20AI-Ready%20Applications-24.png)

1. On the bottom of the page in the lower left, click the **Review + create** blue button.

    ![A picture of clicking the Review + create blue button](./media/Building%20AI-Ready%20Applications-25.png)

1. On the following page, click the **Create** button in the lower left.

    ![A picture of clicking the Create button in the lower left](./media/Building%20AI-Ready%20Applications-26.png)

1. The following page will detail the deployments progress. *(Deployment takes a minute or 2)*

    ![A picture of the database deployment progress page](./media/Building%20AI-Ready%20Applications-27.png)

1. Once the deployment is done, click the blue **Go to resource** button to see your database details.

    ![A picture of clicking the blue Go to resource button to see your database details on the database deployment progress page](./media/Building%20AI-Ready%20Applications-28.png)

#### Network access to the database

1. On the database details page, the right hand side, you will see the **Server name** field with a link the your database server. Click the server name link.

    ![A picture of clicking the server name link on the database details page](./media/Building%20AI-Ready%20Applications-29.png)

1. Click the **Networking** link on the left hand side menu in the **Security** section.

    ![A picture of clicking the Networking link on the left hand side menu in the Security section](./media/Building%20AI-Ready%20Applications-30.png)

1. On the **Networking** page, click the **radio button** next to **Selected networks**.

    ![A picture of clicking the radio button next to Selected networks on the networking page](./media/Building%20AI-Ready%20Applications-31.png)

1. In the **Firewall rules** section, click the button labeled **"Add your client IPv4 address (X.X.X.X)"** to add your local IP address for database access.

    ![A picture of clicking the button labeled "Add your client IPv4 address (X.X.X.X)" to add your local IP address for database access](./media/Building%20AI-Ready%20Applications-32.png)

1. Finally, click the **Save** button in the lower left of the page.

    ![A picture of clicking the save button in the lower left of the page](./media/Building%20AI-Ready%20Applications-33.png)

### Next: [Connect to the free Azure SQL Database](2-connect-azure-sql-db.md)
