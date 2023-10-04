# AAA-Framework
<h1>Description</h1>

In this task, my objective will be to evaluate the access management measures employed by a company. My task will involve an examination of their existing procedures, the identification of any shortcomings, and the provision of suggestions for enhancing their security protocols.

As I recalled my lessons, access controls encompass security mechanisms that oversee the management of access, authorization, and the traceability of information. Authentication controls serve the purpose of confirming an individual's identity, while authorization controls are responsible for granting users specific permissions and imposing constraints on their actions. When implemented effectively, access controls serve as a crucial factor in reducing the probability of encountering security threats.

- <a> Required Documents from Botium Toys </a>
  - [Accounting Log](https://github.com/malikaii99/AAA-Framework/blob/2fba09b7db1f883c24cf827ae20c14f68da6a75b/Accounting%20Log.xlsx)
    
<h2>Scenario</h2>

Review the scenario below.

You’re the first cybersecurity professional hired by a growing business.

Recently, a deposit was made from the business to an unknown bank account. The finance manager says they didn’t make a mistake. Fortunately, they were able to stop the payment. The owner has asked you to investigate what happened to prevent any future incidents.

To do this, you’ll need to do some accounting on the incident to better understand what happened. First, you will review the access log of the incident. Next, you will take notes that can help you identify a possible threat actor. Then, you will spot issues with the access controls that were exploited by the user. Finally, you will recommend mitigations that can improve the business' access controls and reduce the likelihood that this incident reoccurs.

<h3>Report</h3>

On the morning of October 3rd, 2023, precisely at 8:29 AM, a user wielding Legal/Administrator logged in to the company database to access a file from a computer uniquely identified by the IP address 152.207.255.255.

Upon meticulous scrutiny of the employee logs, it becomes apparent that the event log corresponds with the record of Mr. Robert Taylor Jr., an individual holding administrative access. This raises concerns as Mr. Taylor's contract expired in 2019, but his account accessed payroll systems in 2023, rendering his current access status unauthorized.

<a> To prevent former employees from accessing company files, businesses can implement the following recommendations:
  - Terminate Access Quickly: Ensure a swift and comprehensive offboarding process. As soon as an employee leaves the company, user accounts should expire after 30 days, including all access privileges, including access to computer systems, email accounts, and shared drives.
  - Implement Role-Based Access Control (RBAC): Implement RBAC to manage access to company resources. Assign access permissions based on job roles and responsibilities rather than individual user accounts.
