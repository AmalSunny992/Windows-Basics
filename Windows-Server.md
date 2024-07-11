# Day 15: Introduction to Windows Server

## Windows Server Basics
Windows Server is a group of operating systems designed by Microsoft that supports enterprise-level management, data storage, applications, and communications. 

Key features include:
- Active Directory
- Server Manager
- Windows Admin Center
- Hyper-V
- Failover Clustering

## Installing and Configuring Windows IIS
Internet Information Services (IIS) is a flexible, secure, and manageable Web server for hosting anything on the Web. To install and configure IIS on Windows Server:

### Installation Steps
1. **Open Server Manager**: Launch Server Manager from the Start menu.
2. **Add Roles and Features**: Navigate to the "Manage" menu and select "Add Roles and Features."
3. **Role-based or Feature-based Installation**: Choose "Role-based or Feature-based Installation" and click Next.
4. **Select Server**: Select the server you wish to install IIS on and click Next.
5. **Select Server Roles**: Check "Web Server (IIS)" and add required features if prompted.
6. **Features**: You can skip the features page unless additional features are needed.
7. **Web Server Role (IIS)**: Review and click Next.
8. **Role Services**: Select the desired role services for your web server (Common options include HTTP Redirection, WebDAV Publishing, Application Development features, etc.).
9. **Confirmation**: Confirm selections and click Install.

### Configuration Steps
1. **Open IIS Manager**: Once installed, you can manage IIS via the Internet Information Services (IIS) Manager, available in the Tools menu of Server Manager.
2. **Add a Website**:
    - In IIS Manager, right-click on "Sites" and select "Add Website."
    - Fill in the required fields such as Site Name, Physical Path, and Binding information.
    - Click OK to create the website.
3. **Configure Site Bindings**: You can configure bindings (such as host names and SSL settings) by selecting your site and clicking on "Bindings" in the Actions pane.
4. **Test the Setup**: Navigate to the server’s IP address or domain name in a web browser to verify that the IIS is working.

## Conclusion
By following these steps, you can successfully install and configure IIS on Windows Server, enabling you to host and manage web applications effectively.

