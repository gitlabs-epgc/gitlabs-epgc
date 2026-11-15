<h1 align="center">Naushil</h1>

<p align="center">
  <strong>IT Infrastructure &amp; Network Security</strong><br>
  11 years in IT infrastructure · Ahmedabad, Gujarat, India
</p>

I deploy and troubleshoot Windows Server, Active Directory, VMware, and
Linux environments, with a Focus on Network Security and Secure
Administrative Access.

## RiverFront View Labs

### RiverFront View Labs Checkout · Simulated UPI & Jenkins CI/CD

Built a simulated payment checkout with **FastAPI, PostgreSQL, and
Kubernetes**. Tested that invalid webhook signatures were rejected and
that replaying a valid webhook did not create a duplicate receipt.

**Verification** — Jenkins build #2 deployed the API and returned
`CHECKOUT_HEALTH_OK`.

### RiverFront View Labs Employee Portal · Secure Kubernetes Access

Configured an **NGINX reverse proxy with TLS and Basic Auth** and used
**Kubernetes NetworkPolicy** to restrict direct backend access.
Troubleshot `502` and `504` responses through service discovery and
network policy checks.

**Verification** — HTTP returned `403`, HTTPS without credentials
returned `401`, and authenticated HTTPS returned `200`. Direct backend
access was blocked.

### RiverFront View Labs Recovery · Backup & Restore Drill

**In progress.** Documenting backup and restore procedures and an API
smoke test to verify service recovery.

## Technical Focus

| Area | Technologies |
| --- | --- |
| Windows infrastructure | Windows Server, Active Directory, DNS, DHCP, Group Policy |
| Virtualization & Linux | VMware ESXi, vCenter, Linux administration |
| Network security | FortiGate, Palo Alto, IPsec and SSL VPNs |
| Cloud & automation | AWS EC2, Systems Manager Session Manager, Kubernetes, Jenkins |
