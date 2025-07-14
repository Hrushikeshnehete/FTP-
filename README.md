# FTP-

# Setting Up an FTP Server on Windows Server 2022

This guide provides step-by-step instructions for installing and configuring an FTP server on Windows Server 2022. The process includes installing the FTP server role, configuring the FTP site, and setting up user permissions for secure file transfers.

## Prerequisites
- Windows Server 2022 installed and configured.
- Administrator access to the server.

## Steps
 --1. Install FTP Server Role
1. Open Server Manager.
2. Navigate to Manage > Add Roles and Features.
3. Select FTP Server under the Web Server (IIS) role.
4. Complete the installation wizard.

 --2. Configure FTP Site
1. Open IIS Manager.
2. Right-click on Sites and select **Add FTP Site.
3. Specify the site name and physical path for the FTP directory.
4. Configure binding (IP address, port, and SSL settings).
5. Set authentication and authorization rules.

 --3. Create FTP User and Permissions
1. Open Computer Management and navigate to Local Users and Groups.
2. Create a new user account for FTP access.
3. Assign the user permissions to the FTP directory (Read/Write as needed).
4. Configure the FTP site in IIS to use the new user for authentication.



