# Managing work devices

Everyone receives a new Mac [when they join 37signals](https://basecamp.com/handbook/08-getting-started#your-first-few-days). We centrally manage and secure these devices with [Kandji](https://kandji.com/) which reduces our exposure to security incidents. Kandji applies a standard configuration to every device (e.g. enable disk encryption, firewall, password rules), it installs essential apps (e.g. EncryptMe), and it will ensure the apps have the latest security updates applied. Kandji also allows us to remotely wipe devices should they be lost, or when an employee leaves the company.

This doesn’t mean you are being monitored or tracked! Kandji is a configuration management system, not a panopticon.

## Access to code and secrets

Knowing our devices are safe and secure allows us to entrust our work computers with access to sensitive systems like Queenbee, Dash, our internal VPN and remote servers. This means installing the VPN, checking out 37signals code, storing secrets, and connecting to the 37signals 1Password account must only be done on a managed work device, not a personal device.

## Personal data on a work device

It's best to avoid mixing business with pleasure, so you must separate personal and work computer usage. Firstly, 37signals should not have access to your family photos, email, messages and personal files. Secondly, one high-profile hack after another is due to commingling personal and work use on a laptop that has access to sensitive systems. There are also hazards of exposing work to your personal data:

* If we need to wipe a laptop remotely, there should be no risk of destruction of your personal data.
* If there's a hack and we need to do forensics or take a device snapshot, employees shouldn't be saddled with sifting through someone else's highly personal data.
* If we do malware or secrets scanning, we shouldn't have to look at employee bank account details, government ID numbers and such that turn up in personal documents interspersed with work documents.

Ultimately, work computers are for work, so please make sure personal data and personal computer usage is kept to your own device.

## Mobile devices, Windows and Linux

Devices running Android, iOS/iPadOS, Windows or Linux are currently unmanaged. It’s fine to install our BC4 and HEY apps on these devices to access work projects and email, but since they’re unmanaged – and therefore ‘untrusted’ – it’s not fine to store 37signals code or secrets on them. If you're coding or accessing secure systems, you should be doing so on a Kandji-managed Mac.
