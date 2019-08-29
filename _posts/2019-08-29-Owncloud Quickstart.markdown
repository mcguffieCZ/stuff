# Owncloud Quickstart

This Quickstart is intended to help:

- Install and configure an Owncloud server
- Enable user to connect to the server via alternate IP Address/Port
- Add user accounts to the server
- Connect to the server with client application

## Installing and configuring an Owncloud server

Follow these steps:

1. Download an installation package.	
   
	<p>Owncloud server can be run on many flavors of Linux and a number of database servers. </p>
   
- Review [Deployment Considerations](https://doc.owncloud.org/server/10.2/admin_manual/installation/deployment_considerations.html), [Deployment Recommendations](https://doc.owncloud.org/server/10.2/admin_manual/installation/deployment_recommendations.html) and [System Requirements](https://doc.owncloud.org/server/10.2/admin_manual/installation/system_requirements.html).
  
- [Select the package](https://owncloud.org/download/) best suited for your environments and technical ability. 
2. Install the package.

   <p>Follow the instructions specific to your installation package and installation method.</p>

3. Configure Owncloud.

	<p>If you have chosen to use an appliance for the installation, most of these steps are covered for you. If a manual installation has been selected, see [specific instructions](https://doc.owncloud.com/server/10.1/admin_manual/installation/manual_installation.html).</p>

4. Login to the server via a browser to ensure installation is successful.

## Enable user to connect to the server via alternate IP Address/Port

In order to make an alternate address/port available for access (port 8080, for example), a change will need to be made in the webserver settings. See [Apache documentation](https://httpd.apache.org/docs/2.4/) for information on how to change the default port.

## Add user accounts to the Owncloud server

Follow these steps:

1. From the top left menu in the browser, select *Administrator* -> *Users*
   
   <p>Users table is presented.</p>
2. In the *Username* field, provide a name for the new user.
3. In the *E-Mail* field, provide an email for the new user.
   **<p>Note:** If groups have been created, new users can be added to a group by selecting the  group name in the dropdown menu. Groups can also be created and users added using the dropdown menu in the *Groups* column.</p>
4. Click *Create*.
   
   <p>The user is created and visible in the table.</p>

## Connect to the server with client application

For mobile clients, see [download page](https://owncloud.org/download/#owncloud-mobile-apps) for instruction manuals.

Follow these steps:

1. Download and install the required [client application](https://owncloud.org/download/#owncloud-desktop-client).

2. Start the application.
   < p>The *Connection Wizard* opens.</p>

3. Enter Server Address and click *Next*.
*<p>User credential* page opens.</p>
   **Note:** Untrusted Certificate page may open. If certificate is from a trusted source, click the *Trust this certificate anyway* radio button and then the *OK* button.
   
4. Enter Username and Password and click *Next*.
   *<p>Setup local folder options* page opens.</p>

5. Select required options and local folder location. Click *Connect*. 
   
   <p>Application connects to server and synchronizes specified folder.</p>

