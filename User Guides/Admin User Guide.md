---
tags: [Guides]
---

# Admin User Guide

## Introduction
Auto Tup-up provides subscribers with automated airtime and data recharge. It has 3 distinct features; Auto Recharge, Instant Recharge, and Schedule Recharge. It caters for both prepaid and postpaid subscribers. Users can also set up family and friends as beneficiaries for automated recharge.

This User Guide explains the functionalities of the MTN Auto Tup-up Admin Portal, the actions available, how to set up admin user roles and the privileges they can access.


## Getting Started

Auto Tup-up admins have access to an admin portal where based on their privilege they can access different modules. This portal is accessed through any web browser, on launching the web browser, the admin user should navigate to Auto Tup-up Admin URL (insert URL here).

![Landing page](../assets/images/landing-page.png)

### Sign In 
The pre-requisite for an admin to sign in to Auto Tup-up admin portal is that an account must have been created for the admin by a super admin. The created admin account has access to modules that his/her role and privilege allows.

![Sign in](../assets/images/sign-in.png)

## Dashboard

The admin dashboard has statistics of the user’s activities on Auto Tup-up. The dashboard shows different counts and trend of key activities on the user portal.

### Recharge Counts

This category has the following statistics:

- Today’s Recharge: This is the total count of recharge purchased for the day (as at when the dashboard was loaded).
- Recharge for last 7 days: This is a total count of recharge purchased in the last 7 days. 
- Recharge for last 30 days: This is a total count of recharge purchased in the last 30 days. 
- All-Time Recharge: This is the all-time recharge count.

![Recharge Count](../assets/images/topit-count.png)

### Recharge Trend

This category shows a chart of Total Recharge Trend. The chart can be rendered in Year, to achieve this the admin is to select the year from the filter dropdown.

![Recharge Trend](../assets/images/topit-trend.png)

## Finance Report Module

The finance report module contains 2 categories.

### Recharge Reports
This category has the following statistics:
  - Successful Auto Recharge count
  - Non-Activated Accounts count
  - Failed Auto Recharge count
  - Activated Accounts count
  - Churned Accounts count
  - Total Revenue in amount
  - Total Flutterwave charges in amount
  - Profit in amount
  - Retention count

These reports can be rendered by day, past 7-days, past 30-days and year. To achieve this, the admin is to select from the filter dropdown.

![Recharge Reports](../assets/images/Recharge-reports.png)

### Failed Transactions

This section provides charts and reports about failed transactions, prevalent failed reasons and prevalent debit reasons. The reports and statistics in this category can be rendered by day, last 7-days, last 30-days, last 90-days, and year.

![Failed Transactions](../assets/images/failed-transactions.png)

Admins can also click on view more details to get reports for failed transactions. These reports can be rendered by date or specific search parameter. To achieve this, the admin is to do the following:
  - Enter Search Parameter
  - Select Start Date and End Date from the date picker
  - Click on the Search button.

![Failed Activation](../assets/images/failed-activations.png)

## Setup-Management

This module contains a list of settings that can be viewed, updated, deactivated or reactivated. The list of settings is as shown in the figure below:

![Setup Mgt](../assets/images/setup-mgt.png)

## Support-Management

### Subscriber Support
This module contains a log of subscribers details such as; name, email, phone number, payment mode, activation status, date created, last login and card type. Admin users can update or manually activate subscriber. Admins can filter the data based on search parameter, status (Active or Inactive), date created (start and end), last login (start and end). Subscriber support data can also be exported in an excel format.

![Subscriber Support](../assets/images/subscriber-support.png)

### Transaction Support
This module contains a list of subscribers transaction details such as; name, email, phone number, amount, Recharge type and status, debit mode and status. Admins can filter the data based on:
  - Subscriber Phone Number
  - Subscriber Email
  - Type
  - Debit Status
  - Recharge Status  
  - Date From and Date to

![Transaction Support](../assets/images/transaction-support.png)

### Recharge Profile Support
This module contains a list of subscribers Recharge profile details such as; Subscriber name, Recharge profile, phone number, threshold, amount, limit and cycle. Admins can deactivate or reactivate profiles here. Admins can filter the data based on:
  - Specific search parameter
  - Threshold
  - Cycle
  - Amount

![Recharge Profile Support](../assets/images/topit-profile-support.png)

## User Management

This module is where admin groups, admin users, and privileges are managed.

### Privilege Management
This module contains a list of all privilege names and descriptions. Admins can Update, Deactivate, or Reactivate these privileges. Admins can add New Privilege as shown in the figure below:

![Privlege Management](../assets/images/privilege-mgt.png)

### Admin Group Management
This module contains a list of all admin groups, paths and the number of privileges the group could access. Admins can Update, Deactivate, or Reactivate these admin groups. Admins can also create New Admin Group using the following steps:
  - Enter Admin Group Name
  - Enter Group Path
  - Select Group Privilege. Can select as much privilege as necessary.
  - Click on Add button

![Admin Group Mgt](../assets/images/admin-group-mgt.png)

### Admin User Management
This module contains a list of all admin users, email and admin type (group). Admins can Reset Password, Deactivate, or Reactivate these admin users. Admins can also add New Admin User using the following steps:
  - Enter First Name
  - Enter Last Name
  - Enter Email Address
  - Enter Phone Number
  - Assign Admin Type (Group)

![Admin User Mgt](../assets/images/admin-user-mgt.png)

## Wallet Management

### Subscriber Wallet
This module contains a log of subscriber details such as; name, email, phone number, current account mode (card or wallet). Admins can credit or debit a user’s wallet. This log can be filtered based on:
  - Specific Search Parameter
  - Status
  - Date Created (Start and End)
  - Last Login (Start and End)

![Subscriber Wallet](../assets/images/subscriber-wallet.png)