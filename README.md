<h1> Secure Identity and Access with Microsoft Entra </h1>

<h2> 1. Create a free Azure Trial account</h1>
In order to create a free Azure trial account, a microsoft account must be created:  

1. Navigate to www.account.microsoft.com to create a microsoft account
2. Go the the bottom of the page and click on create account 
3. Create an email and password for the microsoft account 
4. Follow the instructions to complete the account creation
   
Follow the steps below to create an free Azure trial account 

1. Navigate to wwww.azure.com/free
3. Select the start free option 
4. Sign in the credentials that were just created
5. Navitage to www.portal.azure.com
6. Sign in on more time with the credentials you just created
 
![Screenshot 2024-02-28 11 14 45 AM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/64e24a6e-040d-4838-a590-d91af2052580)
The screeshot above displays the home page of the Azure account. 

<h2> 2. Add Azure Active Directory Premium P2 trial lincenses</h2>

1. Nativate to www.entra.microsoft.com
2. Go to the left menu and expand 'Identity" and click on show more 
3. Expand "Billing" and proceed to click on "Licenses"
4. Go to the right side of the page and select "get free trial" under quick 

![Screenshot 2024-02-28 11 38 42 AM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/a098723d-b293-4641-8a13-56b6cb34cb89)
Microsoft Entra ID P2 is needed to gain access to advanced security features, richer reports and rule based assignments to applications. 

<h2> 3. Create users and groups</h2>

1. Navitage to www.entra.microsoft.com and log in with credentials created on step 1
2. Go to the left side menu and expand to identity. 
3. Expand on the menu option users and proceed to select "all users" 
4. Select "New user" on the command bar and create new user (see below)

![Screenshot 2024-02-28 11 58 26 AM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/0df43a4b-a553-4167-ba92-0656f2d25aeb)

5. Fill out information regarding the new user (Project User 1) 

![Screenshot 2024-02-28 12 13 50 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/418a760e-6b9f-4442-a14b-279c329c21a6)

6. Proceed to Properties that are normally used to identify a group of user for access. A common property used is department

![Screenshot 2024-02-28 12 22 04 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/fe890648-4430-4ea3-8c6c-484a3a27faee)

7. Proceed to assigments (Assinments are normally used to add users to a group). Select "add role " and include "aplication Admistrator"
![Screenshot 2024-02-28 12 24 47 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/1346dca7-0579-49f8-9748-851e13a42359)

8. Proceed to review and create. Review all the information for the new user and click on create user (see below) 
   
![Screenshot 2024-02-28 12 30 54 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/53de6d19-2675-4639-921c-2120f2e87867)

9. Repeat all the steps above to create a second user ( Project User 2) and assign the role of "Application Developer"

![Screenshot 2024-02-28 12 39 59 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/84809f25-bcc4-4567-8a00-777ea84b89be)

10. Test the user account created by signing in: 

![Screenshot 2024-02-28 12 46 24 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/c783b127-8cdf-4255-b091-8a48680f3e45)

    
![Screenshot 2024-02-28 12 48 01 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/0baf9a30-8015-4140-9a3f-551ceda5b5dc)

 
<h2> 4. Assign users to groups </h2>

1. Go to www.entra.microsoft.com and log in with admin credentials
2. Go to the left isde menu and expand on the "Identity" menu
3. Expand on the option Groups and select "All groups"
4. Create a new group and fill our necessary information
5. Proceed to add members and add the users Project User 1 and Project User 2 (see below)

![Screenshot 2024-02-28 1 01 37 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/ab5bac61-ab0c-4ea0-acbe-784782321bc1)

6. Click on Create to succescully finish the task of creating the "Project Secuirty Group" (See below) 

![Screenshot 2024-02-28 1 03 31 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/5d6eaa8e-ff62-4a16-bee0-e620ec564e46)

7. Repeat all the steps above to  create a group named "Project Microsoft365 Group" and add Project User 1 & 2 to the newly created group. 

![Screenshot 2024-02-28 1 08 56 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/b51e8e55-1644-4013-8fca-eb283443ef07)

The screenshot below displays and validates that both "Project Security Groups" and "Project Microsoft Group" have been created: 

![Screenshot 2024-02-28 1 10 37 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/331e1d28-8b49-4508-8dfc-e800fb3140cf)

<h2> 5. Configure Self-Service Password reset (SSPR) </h2>
The Self service password reset allows users to reset their password wihtout having to contact an admin desk: 

1. Go to www.entra.microsoft.com and log in with the admin credentials created on step 1 of this project 
2. Create a group that will have SSPR enabled and add the users previously created.
   
![Screenshot 2024-02-28 1 22 31 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/bd4b304f-ee1e-4ef5-93c2-5a410484e4e0)

3. Proceed to the main menu and expand users submenu. Then, click on "users settings"
4. Select "password reset" under Manage and add Project SSSPR group 
5. Check authentication methods for the users created to ensure that email and mobile phone are selected: 

![Screenshot 2024-02-28 1 36 30 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/d0e61dc1-4184-4c43-b3cf-1c2745e08d24)

<h2> 6. Configure Conditional Access </h2>
1. Go to www.entra.microsoft.com and log in with the admin credentials 
2. Go to the left side menu and expand the Protection submenu 
3. Select Conditional Access and create a new policy. Ensure that the security default are disable and select the option that lists that this organization is using conditional access 

![Screenshot 2024-02-28 1 53 57 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/7870920e-ae23-4344-8520-66590b869e55)

4. Assign Project User 2 to the Project Conditional Access
5. Add Microsoft Azure Managament under target resources
6. Proceed to Acces control, select block access under "Grant" access option
7. Enable the policy before creating
8. The screenshot below validates the creation of the conditional access policy. Now, Project user 2 should not have access to the account: 

![Screenshot 2024-02-28 2 01 15 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/8fe853b2-7d85-41dc-91f8-420b5019913d)


<h2> 7. Configure Privilege Identity Management (PIM) </h2>

1. Go to www.entra.microsoft.com and log in with the admin credentials

Before we get started with, with privileged identity
management, we have to assign our P two licenses to our users
select identit: 

2. Go to the left side menu and expand the Identity submenu 
3. Expand Billing and select linceses
4. Select current P2 licenses and assign admin user to it


1. Go to the left side menu and expand the Identity Governance submenu 
2. Select Privilage Indentity Management
3. Go to Azure AD roles and select settings
4. Search for Azure DevOps Adminitrator and add it 
![Screenshot 2024-02-28 2 26 04 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/e21bf537-aff1-48f9-93ae-4ed7148da500)

5. Esure to edit the settings and select the "require approval to activate". Proceed to add admin user 

![Screenshot 2024-02-28 2 34 48 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/1747eecc-479d-4d4d-bc93-6e2ef03b85dc)

6. Go to the manage section and select roles to add the Azure DevOps Administrator (Project User 1) 
7. Go the Project User 1 account to validate the steps above and active Azure DevOps Administrator 

![Screenshot 2024-02-28 2 55 36 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/41c99303-b6a6-4df8-815e-e39d00fa30ad)

8. Go back to the admin account
9. Scroll throuh the main menu and expand the identity governance submenu
10. Select the Privilege Identiy menu (PIM)
11. Select approved requests and approve the request from Project User 1

<h2> Monitor Identity Secure Score</h2>

1. Go to www.entra.microsoft.com and log in with the admin credentials
2. Go to the main menu and expand the protection submenu
3. Click on show more and proceed to click Identity secure score

![Screenshot 2024-02-28 3 06 11 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/f3882190-5b31-47c5-a5de-23aba25a645f)

The screenshot above displays the overrall score along with recommendations actions to improve it 

<h2>Remove Created Users</h2>

1. Go to www.entra.microsoft.com and log in with the admin credentials
2. Go to the main menu and expand on the identity submenu 
3. Expand users and select all users 
4. Select both Project User 1 & 2 and delete them 

![Screenshot 2024-02-28 3 11 37 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/309278a9-9473-41e5-9905-2e157fe0091b)

