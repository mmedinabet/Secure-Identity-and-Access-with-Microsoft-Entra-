<h1> Secure Identity and Access with Microsoft Entra </h1>
This is hands-on guided project created by courseare that empowers students to navigate the intricacies of implementing and managing Microsoft Entra ID effectively. After completing this project, students will know how to : 

- Create users and groups

- Assign users to groups

- Configure Self-Service Password Reset (SSPR)

- Configure and customize Conditional Access and Privilege Identity Management (PIM)

- Monitor Identity Secure Score


<h2> 1. Create a free Azure Trial account</h1>
To initiate your Azure trial account, a Microsoft account is needed:

1. Visit www.account.microsoft.com to create your Microsoft account.
2. Scroll to the bottom of the page and click on "Create Account."
3. Provide your email and password to set up your Microsoft account.
4. Follow the on-screen instructions to finalize the account creation process.

Once your Microsoft account is set up, proceed with the following steps to create your free Azure trial account:

1. Navigate to www.azure.com/free.
2. Choose the "Start Free" option.
3. Sign in using the credentials you just created.
4. Visit www.portal.azure.com and sign in once again with your new credentials.
 
![Screenshot 2024-02-28 11 14 45 AM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/64e24a6e-040d-4838-a590-d91af2052580)
The screeshot above displays the home page of the Azure account. 

<h2> 2. Add Azure Active Directory Premium P2 trial lincenses</h2>
Microsoft Entra ID P2 licence is needed to gain access to advanced security features, enhanced reports and rule based assignments to applications. 

1. Nativate to www.entra.microsoft.com
2. Expand the "Identity" menu on the left and select "Licenses" under "Billing."
3. Click on "Get Free Trial" located on the right side of the page.

![Screenshot 2024-02-28 11 38 42 AM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/a098723d-b293-4641-8a13-56b6cb34cb89)

<h2> 3. Create users and groups</h2>
Managing users and groups is pivotal for efficient access control. Follow these steps:

1. Log in to www.entra.microsoft.com using admin credentials.
2. Navigate to the "Identity" section on the left-hand menu.
3. Under "Users," select "All Users."
4. Click on "New User" to create a new user profile.
   
![Screenshot 2024-02-28 11 58 26 AM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/0df43a4b-a553-4167-ba92-0656f2d25aeb)

5. Fill in the required information for the new user(Project User 1) 

![Screenshot 2024-02-28 12 13 50 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/418a760e-6b9f-4442-a14b-279c329c21a6)

6. Define properties, commonly used for user access identification, such as department

![Screenshot 2024-02-28 12 22 04 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/fe890648-4430-4ea3-8c6c-484a3a27faee)

7. Assign roles to users by selecting "Add Role" and including roles like "Application Administrator."
   
![Screenshot 2024-02-28 12 24 47 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/1346dca7-0579-49f8-9748-851e13a42359)

8. Review and create the user profile. 
   
![Screenshot 2024-02-28 12 30 54 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/53de6d19-2675-4639-921c-2120f2e87867)

9. Repeat the above steps to create additional users and assign appropriate roles.

![Screenshot 2024-02-28 12 39 59 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/84809f25-bcc4-4567-8a00-777ea84b89be)

10. Test the user account created by signing in: 

![Screenshot 2024-02-28 12 46 24 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/c783b127-8cdf-4255-b091-8a48680f3e45)

    
![Screenshot 2024-02-28 12 48 01 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/0baf9a30-8015-4140-9a3f-551ceda5b5dc)

 
<h2> 4. Assign users to groups </h2>
Efficiently manage user access by assigning them to groups: 

1. Log in to www.entra.microsoft.com as an admin.
2. Navigate to the "Identity" menu and select "Groups" under it.
3. Create a new group and add relevant members like Project User 1 and Project User 2.

![Screenshot 2024-02-28 1 01 37 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/ab5bac61-ab0c-4ea0-acbe-784782321bc1)

6. Click "Create" to finalize the creation of the "Project Security Group." 

![Screenshot 2024-02-28 1 03 31 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/5d6eaa8e-ff62-4a16-bee0-e620ec564e46)

7. Repeat these steps to create additional groups and manage user assignments effectively.

![Screenshot 2024-02-28 1 08 56 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/b51e8e55-1644-4013-8fca-eb283443ef07)

The screenshot below displays and validates that both "Project Security Groups" and "Project Microsoft Group" have been created: 

![Screenshot 2024-02-28 1 10 37 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/331e1d28-8b49-4508-8dfc-e800fb3140cf)

<h2> 5. Configure Self-Service Password reset (SSPR) </h2>
Enabling self-service password reset empowers users to regain access to their accounts independently, eliminating the need for admin intervention:

1. Log in to www.entra.microsoft.com using the admin credentials established in step 1 of this project.
2. Establish a group with SSPR privileges and add previously created users.
   
![Screenshot 2024-02-28 1 22 31 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/bd4b304f-ee1e-4ef5-93c2-5a410484e4e0)

3. Navigate to the main menu, access the users submenu, and select "User Settings."
4. Under "Manage," opt for "Password Reset" and include the Project SSPR group.
5. Review authentication methods for created users, ensuring email and mobile phone options are selected.

![Screenshot 2024-02-28 1 36 30 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/d0e61dc1-4184-4c43-b3cf-1c2745e08d24)

<h2> 6. Configure Conditional Access </h2>

1. Log in to www.entra.microsoft.com with admin credentials.
2. Navigate to the Protection submenu under the left-side menu.
3. Choose Conditional Access and initiate a new policy, ensuring to disable security defaults and affirm organizational use of conditional access.

![Screenshot 2024-02-28 1 53 57 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/7870920e-ae23-4344-8520-66590b869e55)

4. Assign Project User 2 to the Project Conditional Access.
5. Add Microsoft Azure Management as a target resource.
6. Specify access control by selecting "Block Access" under the "Grant" access option.
7. Enable the policy before creation.

The screenshot below validates policy creation; Project User 2 should now be denied access to the account.

![Screenshot 2024-02-28 2 01 15 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/8fe853b2-7d85-41dc-91f8-420b5019913d)


<h2> 7. Configure Privilege Identity Management (PIM) </h2>
PIM enables precise control over privileged access.

1. Sign in to www.entra.microsoft.com using admin credentials.

Before delving into privileged identity management, ensure P2 licenses are assigned to users by navigating to the Identity submenu under the left-side menu and selecting Billing.

1. Within Identity Governance, select Privileged Identity Management.
2. Access Azure AD roles and navigate to settings.
3. Locate Azure DevOps Administrator and add it to the roster.


![Screenshot 2024-02-28 2 26 04 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/e21bf537-aff1-48f9-93ae-4ed7148da500)

5. Edit settings, enabling "Require approval to activate," and add the admin user.

![Screenshot 2024-02-28 2 34 48 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/1747eecc-479d-4d4d-bc93-6e2ef03b85dc)

6.Manage roles by adding the Azure DevOps Administrator (Project User 1).

7. Validate the steps by activating Azure DevOps Administrator for Project User 1.

![Screenshot 2024-02-28 2 55 36 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/41c99303-b6a6-4df8-815e-e39d00fa30ad)

8. Return to the admin account, navigate to Identity Governance, and select Privileged Identity Management.
9. Approve requests from Project User 1 in the approved requests section.

<h2> Monitor Identity Secure Score</h2>

1. Log in to www.entra.microsoft.com using admin credentials.
2. Access the main menu and expand the Protection submenu.
3. Click on "Show More" and proceed to Identity Secure Score.

![Screenshot 2024-02-28 3 06 11 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/f3882190-5b31-47c5-a5de-23aba25a645f)

This screenshot illustrates the overall score alongside recommended actions for enhancement. 

<h2>Remove Created Users</h2>

1. Sign in to www.entra.microsoft.com with admin credentials.
2. Expand the identity submenu from the main menu.
3. Access users and select all users.
4. Delete both Project User 1 & 2.

![Screenshot 2024-02-28 3 11 37 PM](https://github.com/mmedinabet/Secure-Identity-and-Access-with-Microsoft-Entra-/assets/142737434/309278a9-9473-41e5-9905-2e157fe0091b)

<h1>Conclusion</h1>
The "Secure Identity and Access with Microsoft Entra" project provides a comprehensive hands-on experience for mastering the effective implementation and management of Microsoft Entra ID. By completing this project, students gain proficiency in various essential tasks:
- Creating Users and Groups: Learn to create user profiles and groups for streamlined access control.

- Assigning Users to Groups: Understand the importance of group assignment for efficient access management.

- Configuring Self-Service Password Reset (SSPR): Empower users to reset their passwords independently, reducing reliance on admin support.

- Configuring Conditional Access: Implement policies to control access based on specific conditions, enhancing security measures.

- Configuring Privileged Identity Management (PIM): Gain control over privileged access by defining roles and approval processes.

- Monitoring Identity Secure Score: Learn to assess and improve the overall security posture by monitoring Identity Secure Score.

- Removing Created Users: Understand the process of removing users from the system when necessary.

Through guidance and practical exercises, I was able to acquire the skills and knowledge required to effectively manage identity and access in Microsoft Entra, ensuring robust security measures are in place.
