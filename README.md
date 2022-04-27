# C-ASP.NET-Web-Form-project-bank-account-management
AccountManage.aspx page’s code behind AccountManage.aspx.cs such that when user accesses this page via the top menu Account Manage, it has the following elements:
 Customer Name. A textbox for entering the name of the account’s owner
 Initial Deposit. A textbox for entering the initial deposit amount.
 Account Type. A dropdown list for selecting to create a new checking account or saving account.
 A table showing the information of all accounts currently in the system. If no account in the system yet, it should show a message "no account in system yet".
After the user entered account owner’s name, initial deposit amount, selected an account type, and clicked Add Account button, the application should have the following behaviors:
 The application adds either a new Checking Account or a new Saving Account, depending on the selection of the Account Type dropdown list, respectively, to the system and update the account information table on the page.
 To prevent double adding the same account when user accidently clicks the Add Account button again, the application empties the Customer Name and Initial Deposit textbox fields and reset the Account Type selection to initial prompt Select …
FundWithdraw.aspx page’s code behind FundWithdraw.aspx.cs such that when user accesses this page via the top menu item Fund Withdraw, the page has the following elements and behaviors:
 If currently there is no account in the system, the application redirects the user back to the AccountManage.aspx page. Otherwise, the application displays the page which has the following web controls:
   Account – A dropdown list letting the user to select one account from the existing accounts in the system. The display text of the dropdown list options should be in the format of Account Number – Owner Name (Account Type)
   Current Balance – A read-only textbox to show the selected account’s current balance
   Withdraw Amount – A text box letting the user to enter the withdraw amount.
   Withdraw – A button letting the user to submit the withdraw request.
