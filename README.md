# OPEN-SOURCE-EX-6
# NAME:SOUNDARYA J
# REG NO:212223220108
# Aim

To create a user account in Red Hat Enterprise Linux with a specific User ID (UID) of 1326 and the username “alies”.

# Algorithm
<h2>Step 1:</h2>
Start the Terminal as Root.
Switch to the root user or use administrative privileges to perform user management tasks.
<h2>Step 2:</h2>
Create the User Account.
Create a new user with the username alies and assign the User ID (UID) as 1326.
<h2>Step 3:</h2>
Set the User Password.
Assign a password for the user alies to enable login access.
<h2>Step 4:</h2>
Verify the User Account.
Display the user details using the id command to confirm the assigned UID and groups.
<h2>Step 5:</h2>
Check the User Information in the System File.
View the /etc/passwd file entry to verify that the user alies has been created with the correct UID and shell path.

# Steps Involved
```
STEP 1 : sudo -i
STEP 2 : useradd -u 1326 alies
STEP 3 : passwd alies
STEP 4 : id alies
STEP 5 : grep alies /etc/passwd
```

# Output

<img width="948" height="382" alt="image" src="https://github.com/user-attachments/assets/427eaad8-cec0-4f5f-8798-f9e6a97f4129" />


# Result

Thus, the user account alies with User ID 1326 was successfully created and verified in Red Hat Enterprise Linux (RHEL).
