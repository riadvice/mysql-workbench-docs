# Connect to a Database with MySQL Workbench

MySQL Workbench is a popular graphical tool for working with MySQL databases. This multifunctional tool is compatible
with various platforms, including Windows, Linux, and macOS.

## Download and Install MySQL Workbench

You can obtain MySQL Workbench at no cost directly from
the [MySQL official website](https://www.mysql.com/products/workbench/).

After downloading the appropriate version of MySQL Workbench that corresponds to your operating system, proceed with the
installation by following the guidelines specific to your OS.

### Prerequisites

- Ensure MySQL Workbench is installed on your computer. If not, you can download and install it from
  the [MySQL website](https://www.mysql.com/products/workbench/).
- Have the necessary credentials for the MySQL database you want to connect to obtained from the dedicated project page.

### Steps to Connect to a MySQL Database

#### 1. Open MySQL Workbench

Launch MySQL Workbench on your computer. You will see the home screen.

![Home Screen](./images/home-screen.png)

#### 2. Create a New Connection

- On the home screen, click on the "+" symbol next to "MySQL Connections" to create a new connection.

 ![Connect Button](./images/connect-plus.png)

- This opens the "Setup New Connection" dialog.

#### 3. Configure Connection Settings

In the "Setup New Connection" dialog, enter the following details:

- **Connection Name**: Give a descriptive name to your connection. This can be anything to help you remember which
  database this connection refers to.
- **Connection Method**: Choose "Standard (TCP/IP)" for most cases.
- **Hostname**: Enter the IP address or domain name of your MySQL server. If the server is on your local machine,
  use, it should be something like `mysql-colour.edukiz.com`.
- **Port**: The default MySQL port is `3306`. We will keep it as is.
- **Username**: Enter the username you use to access the database, it is `root` in our case.

![Connection Windows](./images/connection-window.png)

- **Password**: Click on "Store in Vault" and enter your password if you wish to save it. Otherwise, you'll be prompted
  to enter it each time you connect.

![Password Prompt](./images/password-prompt.png)

#### 4. Test the Connection

- Click on the "Test Connection" button to make sure the details are correct and MySQL Workbench can connect to the
  database. If there's an error, it will provide a message, and you'll need to verify your settings. Otherwise you should see
  a prompt with the message "Successfully made the MySQL connection".

![Connection Success](./images/connect-success.png)

#### 5. Connect to the Database

- After a successful test, click "OK" to save the connection.
- Back on the home screen, you will see your new connection listed under "MySQL Connections."

![Connection List](./images/connection-list.png)

- Click on the connection icon to connect to your MySQL database. If you didn't save your password, you'll be prompted
  to enter it now. If it is working you should see a connecting windows like the below screenshot.

![Connection List](./images/connecting.png)


#### 6. Using MySQL Workbench

- Once connected, you can use the Workbench interface to run SQL queries, manage databases, and perform various database
  operations.

![Connected](./images/connected.png)

Well done !