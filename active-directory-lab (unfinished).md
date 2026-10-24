<h1>Active Directory</h1>

<h2>Goal:</h2> Explore Active Directory fundamentals and acquire hands-on exposure. Serveracademy.com offers a free, browser-lab based simulation, making downloading a Virtual Machine with Microsoft Server installed unnecessary.

<h2>What is Active Directory?</h2>

To understand Active Directory, one must first learn what a <b>directory service</b> is. A directory service is a system that keeps track of users, computers and groups, and unique characteristics concerning those objects such as the permissions they enjoy. This allows <b>centralized management over a domain and its contents.</b> Active Directory is Microsoft's proprietary directory service. 

<img width="600" height="400" alt="Screenshot 2026-10-24 154755" src="https://github.com/user-attachments/assets/b52fdadd-5693-4bd0-bf2c-299c1910d943" />


<h2>How do you create a user in Active Directory?</h2>

First, a location for a directory to create users must be designated, preferably within <b>a domain that includes both users and computers</b> for simplicity's sake. After establishing such a directory:

- Right click either the empty tab on the right, or the users directory itself
- Click "New", then fill out the user's information according to policy (Many organizations prefer a <b>standardized format</b>, such as the person's first name initial + their last name (i.e. msarhan).
- The <b>"User logon name"</b> is what users will use to log into the domain. Initials can be left blank unless required by organization's policy.

<img width="450" height="400" alt="Screenshot 2026-10-24 154919" src="https://github.com/user-attachments/assets/e04893cf-df75-4a23-ba3d-71b7439531f6" /> <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/975e87b5-07d6-4dfc-adcd-0910f4d1eecc" />

In the pop-up window, you will be able to set and confirm the user's password. The password may be required to follow certain rules depending on the organization's policy.

The same pop-up window also allows the configuration of four check-box settings:

<b>1. "User must change password at next logon".</b> This setting is checked when the circumstances demand the user choose a new password upon their next log-in attempt. This is commonly done when the user had forgotten their password or if there is reason to suspect it has been compromised, or when onboarding a new hire.

<b>2. "User cannot change password".</b> This setting prevents the user from changing their own password. It may be checked if the account is shared between users, or if IT prefers to manage the password centrally.

<b>3. "Password never expires".</b> This setting ensures a user's password never expires. An example of its usage is a domain policy that requires password resets after a set period of time. Checking the setting ensures the password never expires for a specific account.

<b>4. "Account is disabled".</b> This setting disables the account, which prevents sign-ins. An example of when this setting may be checked is offboarding. IT may not immediately delete the account because of retention or audit requirements, among other things.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/6f83587c-eae7-4ecd-8dee-18811751f924" />


After clicking "Next >", you will be shown a final confirmation pop-up window. It will include the user's full name, their user logon name, and the checkbox settings you enabled. Verify the information, then click "Finish".


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/124a3870-bbb3-4613-ad52-2d060621c5fc" />

You have now created a new user account within your domain.

<h2>How do you reset a user's password in Active Directory?</h2>

First, find the user's account in the appropriate Organizational Unit (OU). Right-click the account and select "Reset Password...". Enter and confirm the new password, then select "User must change password at next logon" if required by your organization's policy. Click "OK" to complete the reset. Active Directory will display a confirmation message when the reset is successful.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/f288400a-953e-46cd-82d6-da34bfac566d" />

<h2>How do you add a user to a group in Active Directory?</h2>

Find the user's account and open "Properties". Click the "Member Of" tab, then click "Add...". Enter the group name, click "Check Names" to verify it, then click "OK". Check the "Member Of" tab to confirm the group appears.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/9c222ac9-dfc3-49c6-9f3c-20e4f732b25b" />


