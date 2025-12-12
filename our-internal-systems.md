# Our Internal Systems

Besides the customer-facing applications, like the different versions of Basecamp, we have a number of internal systems that help us support, report, and operate the company. They are as follows:

## Queenbee

Queenbee is our invoice, accounting, and identity system. Here you can look up any customer account, see whether they are comped, refund an invoice, or even login as a customer.

That’s an immense amount of power and we take its use very seriously. We only ever login as a customer after having been given explicit permission to do so, never preemptively. Our customers expect that their information is confidential, even from us, and we intend to honor that expectation at all times.

[billing.37signals.com 🔒](https://billing.37signals.com)

## Sentry

We track programming exceptions on Sentry. When a customer hits a “Oops, something went wrong!” screen, that means there’ll be an entry in Sentry explaining to programmers why they saw that screen. Keeping the exceptions under control and monitored is primarily the responsibility of SIP and Jim via on-call.

[getsentry.com](https://getsentry.com)

## Grafana

We monitor our systems and their health through Grafana. Here you'll find dashboards and alerting rules. It is our go-to for diagnosing performance issues, outages, and any other form for operational insight.

[grafana.37signals.com 🔒](https://grafana.37signals.com/)

## Dash

Dash is the main hub for everything that has to do with logging (like finding why a request is slow or whether an email has been delivered), reporting (everything from number of support cases handled to split of devices used to access Basecamp), application health (response times, job queue exceptions etc).

[dash.37signals.com 🔒](https://dash.37signals.com)

## Omarchy

[Omarchy](https://omarchy.org) is our new Linux distribution that everyone on Ops, SIP, and Ruby programmers on Product are moving to. We developed it in-house and continue to lead the development.

## Kandji

[Kandji](https://kandji.io) is how we make sure all work Mac laptops are securely configured and running the latest software updates. It helps us reduce our exposure to security incidents. You can read more about this in [Managing work devices](https://github.com/basecamp/handbook/blob/master/managing-work-devices.md).

## Shipshape

Shipshape is the OG in-house tool for ensuring your work Mac laptop is safe and secure. We still run it, but it's gradually being superceded by Kandji. When you’re given access to the company’s GitHub account, you can run Shipshape to be sure you’re up to code. Shipshape will also test your machine periodically to let you know (and our SIP team know) if your machine springs a leak and needs bailing out.

[github.com/basecamp/shipshape 🔒](https://github.com/basecamp/shipshape)
