# Managing work devices

Everyone receives a new Mac [when they join 37signals](https://github.com/basecamp/handbook/blob/f094e5f8b778515d363d84c9ae139cc006b66f3b/getting-started.md#your-first-few-days). We centrally manage and secure these devices with [Kandji](https://kandji.io/) which reduces our exposure to security incidents. Kandji applies a standard configuration to every device (e.g. enable disk encryption, firewall, password rules), it installs essential apps (e.g. EncryptMe), and it will ensure the apps have the latest security updates applied. Kandji also allows us to remotely wipe devices should they be lost, or when an employee leaves the company.

We mainly use macOS and Linux at 37signals to develop and support our applications.

With macOS, we centrally manage and secure these devices with [Kandji](https://kandji.io/). Kandji applies a standard configuration to every device (e.g. enable disk encryption, firewall, password rules), it installs essential apps, and it will ensure the apps have the latest security updates applied. Kandji also allows us to remotely wipe devices should they be lost, or when an employee leaves the company. (This doesn’t mean you are being monitored or tracked! Kandji is a configuration management system, not a panopticon.)

With Linux, we run [Omarchy](https://omarchy.org), which already comes with the standard configuration needed (full-disk encryption, firewall, etc). Here we lean on 1password to provide the employee onboarding/offboarding of access to credentials and our Tailscale VPN to control access to internal systems. We don't use a managed process like Kandji.

## Access to code and secrets

Knowing our devices are safe and secure allows us to entrust our work computers with access to sensitive systems like Queenbee, and our internal VPN and remote servers. This means installing the VPN, checking out 37signals code, and storing secrets must only be done on a work device, not a personal device.

Please do not keep any personal data on your 37signals-issued computer. You should maintain a separate, personally-owned machine if you need a home computer. The company reserves the right to, and may be required to, seize your computer or its data at any point in response to subpoenas, lawsuits, or security incidents.

## Mobile devices and Windows

Devices running Android, iOS/iPadOS, and Windows are currently unmanaged. It’s fine to install our BC4 and HEY apps on these devices to access work projects and email, but since they’re unmanaged – and therefore ‘untrusted’ – it’s not okay to store 37signals code or secrets on them. If you're coding or accessing secure systems, you should be doing so on a Kandji-managed Mac or an Omarchy Linux machine.

## FAQ

There are many questions that arise from IT policies such as this, so we've written [an FAQ in BC4](https://3.basecamp.com/2914079/buckets/31986799/documents/6044843594) to help answer them.
