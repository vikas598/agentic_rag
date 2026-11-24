# NovaRetail Internal IT Support Handbook


## 1. VPN Access

Employees working outside the office must use the company VPN before
accessing internal systems.

### 1.1 Installation and connection

1.  Open the internal Software Portal.
2.  Download and install the NovaSecure VPN client.
3.  Launch the client and sign in with the employee's company email and
    password.
4.  Complete the required multi-factor authentication (MFA) challenge.
5.  Select the closest corporate gateway and connect.
6.  Confirm that the client reports a successful connection before
    accessing internal resources.

Employees should use only the company-provided VPN client and approved
corporate gateways.

### 1.2 Basic troubleshooting

If the VPN connection fails:

1.  Confirm that the device has working internet connectivity.
2.  Close and restart the NovaSecure VPN client.
3.  Sign in again and complete MFA.
4.  Try another corporate gateway.
5.  Record the exact error message and the time the problem occurred.
6.  If the connection still fails, open an IT ticket and attach a
    screenshot of the error.

Do not disable endpoint security, antivirus, or firewall settings to
make the VPN work. Do not install an alternative VPN client to bypass a
connection problem.

### 1.3 When to escalate

Contact the IT Service Desk if the client repeatedly fails to connect,
authentication does not complete, or no approved gateway works. Include
the device name or asset tag if available, the gateway selected, the
error message, and the troubleshooting steps already attempted.

## 2. Password Reset Policy

Company passwords must be at least **14 characters** long.

### 2.1 Normal password resets

Employees should use the self-service identity portal for routine
password resets. Follow the portal's identity-verification instructions
and choose a password that meets the displayed requirements.

After five failed login attempts, an account may be temporarily locked.
Repeatedly trying different passwords can prolong the problem or trigger
additional security checks.

### 2.2 If self-service recovery fails

If the self-service process does not work:

1.  Stop repeated login attempts.
2.  Contact the IT Service Desk through the approved internal support
    channel.
3.  Describe the error and identify the affected account.
4.  Follow the identity-verification process provided by IT.

Support personnel must not ask employees to disclose their current
password or MFA code.

### 2.3 Password handling

-   Never share a password with a colleague, manager, or support agent.
-   Never disclose an MFA code or approve an unexpected MFA prompt.
-   Do not write passwords where other people can see them.
-   Do not reuse a company password for unrelated personal services.
-   If an employee believes a password has been exposed, they should
    report the concern to IT promptly and follow the account-recovery
    instructions.

## 3. Multi-Factor Authentication (MFA)

MFA is mandatory for email, VPN, cloud administration, and other
protected company systems.

### 3.1 Approved methods

The approved MFA methods are:

-   The company authenticator app.
-   Registered hardware security keys.

SMS may only be used when it has explicitly been enabled as a recovery
method. It is not a default replacement for the approved methods.

### 3.2 Sign-in procedure

1.  Enter the company account credentials.
2.  Respond to the MFA prompt using an approved registered method.
3.  Confirm that the sign-in was initiated by the employee.
4.  If the prompt was unexpected, deny it and report the event to IT.

### 3.3 Lost device or authentication problem

If an employee loses access to their authenticator device or security
key, they should contact the IT Service Desk and complete the approved
identity-verification process. Employees must not borrow another
person's security key or share authentication codes.

An unexpected MFA prompt may indicate an attempted sign-in by someone
else. Do not approve it merely to clear the notification.

## 4. Software Installation

Employees should install business software only from the company
Software Portal.

### 4.1 Software available in the portal

Before installing software, employees should:

1.  Search for the application in the Software Portal.
2.  Confirm that it is the intended business application.
3.  Follow the portal's installation instructions.
4.  Restart the application or device if the installation process
    requests it.

### 4.2 Software not listed in the portal

Requests for software that is not listed require manager approval and IT
security review. The request should explain the business purpose and
identify the software being requested.

Administrator access is not granted simply to install unapproved
applications. Employees must not download unapproved installers from
third-party websites or use personal administrator credentials to bypass
company controls.

### 4.3 Installation problems

If an approved application fails to install, record the application
name, the displayed error, and the point at which installation failed.
Contact the IT Service Desk rather than disabling endpoint protection or
changing security settings.

## 5. Lost or Stolen Laptop

Immediately report a lost or stolen company laptop to the IT Service
Desk and the employee's manager.

### 5.1 Information to provide

Provide the following information when available:

-   Device asset tag.
-   Device make or model, if known.
-   Last known location.
-   Approximate time the device was last seen.
-   Whether the device is believed to be lost or stolen.
-   Any other relevant circumstances.

Do not delay reporting simply because the asset tag or exact location is
unavailable.

### 5.2 IT and Security response

IT will initiate device lock/wipe procedures and coordinate with
Security. Employees should follow any instructions provided by IT or
Security.

Employees must not attempt to remotely recover the device themselves,
confront a suspected thief, or use personal tools to access or wipe the
device.

### 5.3 Related account concerns

If the employee also suspects that account credentials or authentication
devices may have been exposed, they should tell the IT Service Desk when
reporting the laptop. IT can then advise on the appropriate
account-protection steps.

## 6. General IT Support and Ticket Information

Employees should report technical problems through the approved IT
support channel. A useful ticket description includes:

-   A short summary of the problem.
-   The affected device, application, or service.
-   When the problem began.
-   Whether one person or multiple people are affected.
-   The exact error message, if one appears.
-   Troubleshooting steps already attempted.
-   A screenshot, where it helps explain the issue and does not expose
    passwords, MFA codes, or other secrets.

Do not include passwords, MFA codes, or other authentication secrets in
a ticket.

For priority definitions and troubleshooting procedures, refer to the
**IT Service Desk Runbook**.

## 7. Security Practices

-   Do not disable endpoint security or firewall settings to resolve an
    IT issue.
-   Do not share passwords, MFA codes, or security keys.
-   Use company-approved software and access methods.
-   Report lost devices and suspicious authentication prompts promptly.
-   Do not attempt workarounds that bypass company security controls.

When a troubleshooting step appears to conflict with a security
requirement, stop and contact the IT Service Desk.
