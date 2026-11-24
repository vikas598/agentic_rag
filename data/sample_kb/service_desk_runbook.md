# IT Service Desk Runbook


## 1. Ticket Intake and Initial Assessment

Before troubleshooting, establish what is affected and how broadly the
issue is occurring.

### 1.1 Information to collect

Record:

-   The user's name or approved account identifier.
-   The affected device, application, or service.
-   The time the issue began.
-   The exact error message or observed behavior.
-   Whether the issue affects one user, a team, or the wider company.
-   Whether the issue is continuous or intermittent.
-   Any troubleshooting already performed.

Ask for screenshots when they help clarify the issue. Remind users not
to include passwords, MFA codes, or other authentication secrets.

### 1.2 Determine the scope

First determine whether the problem is isolated or widespread.

-   **Single-user issue:** Investigate the user's account, device,
    application, and network connection.
-   **Team or multi-user issue:** Check for a shared service, network,
    or configuration problem.
-   **Company-wide issue:** Check the service status dashboard and
    assess whether an incident escalation is required.

Do not ask every user to repeat individual troubleshooting steps when
evidence points to a widespread service incident.

## 2. Email Troubleshooting

Use this procedure when a user cannot send or receive email.

### 2.1 Establish the impact

1.  Ask whether the issue affects sending, receiving, or both.
2.  Determine whether one user or multiple users are affected.
3.  Ask when the issue started and whether an error message appears.
4.  Check network connectivity.
5.  Check the service status dashboard for a known email incident.

### 2.2 Single-user troubleshooting

If only one user is affected:

1.  Ask the user to sign out of the email application and sign back in.
2.  Verify whether the mailbox has reached its quota.
3.  Ask the user to test email through the web client.
4.  Record any error message and whether the web client behaves
    differently.
5.  Escalate if the issue remains unresolved after these checks.

The web-client test helps distinguish an issue limited to a local
application from a problem that also affects access through the web.

### 2.3 Widespread email incidents

If multiple users or teams are affected:

1.  Check the service status dashboard.
2.  Record the affected user groups and observed symptoms.
3.  Identify whether the symptoms are consistent across users.
4.  Escalate the suspected service incident through the appropriate IT
    process.

Do not ask each affected user to reinstall email software when the
evidence suggests a widespread service issue.

### 2.4 Information to include in escalation

Include the start time, scope, affected functions (sending, receiving,
or both), relevant error messages, service-dashboard observations, and
checks already completed.

## 3. Laptop Performance Troubleshooting

Use this procedure when a laptop is slow, unresponsive, or performing
below expectations.

### 3.1 Initial checks

Check the following areas:

1.  **CPU usage:** Look for processes consuming unusually high
    processing resources.
2.  **Memory usage:** Check whether available memory is low or
    applications are using excessive memory.
3.  **Storage space:** Check the amount of free storage space.
4.  **Startup applications:** Review applications configured to launch
    at startup.
5.  **Operating system updates:** Check whether updates are pending or
    an update process is running.
6.  **Endpoint security scan status:** Check whether a security scan is
    running or reporting an issue.

Record relevant observations before making changes.

### 3.2 Basic remediation

Based on the findings:

-   Close unnecessary applications that the user does not need.
-   Review unnecessary startup applications using approved
    operating-system controls.
-   Check whether pending operating-system updates need to complete.
-   Allow endpoint security scans to operate according to company
    policy.
-   Reassess performance after an approved remediation step.

Do not disable security agents as a troubleshooting shortcut.

### 3.3 Escalation conditions

Escalate when hardware diagnostics report failure or repeated shutdowns
continue after software remediation.

Include the diagnostic result, frequency of shutdowns, observed
performance symptoms, and remediation already attempted.

## 4. Ticket Priority

Use the following priority definitions when classifying tickets.

  -----------------------------------------------------------------------
  Priority                Definition              Example
  ----------------------- ----------------------- -----------------------
  P1                      Company-wide outage or  A company-wide service
                          critical security       outage or a critical
                          incident                security incident

  P2                      Major team blocked with A major team cannot
                          no workaround           perform its work and
                                                  has no workaround

  P3                      Individual user blocked One employee is unable
                          or degraded with        to use a required
                          limited workaround      function or has
                                                  significantly degraded
                                                  service

  P4                      Standard request,       A routine information
                          information request, or request or standard
                          low-impact issue        service request
  -----------------------------------------------------------------------

### 4.1 Applying priority consistently

-   Assess business impact and the number of affected users.
-   Consider whether a usable workaround exists.
-   Treat a critical security incident as P1 under this priority
    definition.
-   Do not classify an issue as P1 merely because a user describes it as
    urgent; assess the actual impact.
-   Reassess priority if the scope or impact changes.

These definitions do not specify response-time or resolution-time
targets. Do not promise a particular service level unless it is defined
in an approved company policy.

## 5. Escalation and Handover

Escalate when the issue meets a documented escalation condition, cannot
be resolved through the applicable checks, or appears to involve a wider
service incident or security concern.

### 5.1 Handover checklist

A useful handover includes:

-   Ticket summary and current priority.
-   Affected users, teams, devices, or services.
-   Start time and observed frequency.
-   Error messages and relevant screenshots.
-   Checks performed and their results.
-   Actions taken and current status.
-   Reason for escalation.

A handover should distinguish confirmed facts from suspected causes.

### 5.2 Security-related concerns

Do not ask users to disable endpoint security or disclose passwords or
MFA codes. If a report indicates a possible critical security incident,
classify it according to the P1 definition and follow the appropriate
Security escalation process.

## 6. Troubleshooting Record Quality

A good ticket record allows another support technician to continue the
investigation without repeating completed work.

Record observations precisely. For example, write "the web client also
fails to load" rather than "email is broken." Include timestamps where
available and identify whether a check succeeded or failed.

Avoid recording secrets or unnecessary personal information. Screenshots
should be reviewed for exposed credentials or authentication codes
before they are attached.

## 7. Related Policy References

The **NovaRetail Internal IT Support Handbook** defines employee-facing
requirements and policies for:

-   VPN access and approved connection troubleshooting.
-   Password length and account recovery.
-   Approved MFA methods.
-   Software installation and approval.
-   Lost or stolen company laptops.
-   General security practices.

Use the handbook when a ticket raises a question about what an employee
is permitted or required to do. Use this runbook for the Service Desk's
operational troubleshooting and ticket-priority guidance.
