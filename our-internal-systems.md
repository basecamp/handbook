# Our Internal Systems

Besides the customer-facing applications, like the different versions of Basecamp, we have a number of internal systems that help us support, report, and operate the company. They are as follows:

### Dash

Dash is the main hub for everything that has to do with logging (like finding why a request is slow or whether an email has been delivered), reporting (everything from number of support cases handled to split of devices used to access Basecamp), application health (response times, job queue exceptions etc).

[dash.37signals.com](https://dash.37signals.com)

### Queenbee

Queenbee is our invoice, accounting, and identity system. Here you can look up any customer account, see whether they are comped, refund an invoice, or even login as a customer.

That’s an immense amount of power and we take its use very seriously. We only ever login as a customer after having been given explicit permission to do so, never preemptively. Our customers expect that their information is confidential, even from us, and we intend to honor that expectation at all times.

[billing.37signals.com](https://billing.37signals.com)

### The 37 command

This is perhaps less of a system and more of an interface to all our other systems. The 37 command gives easy access to the production consoles for all the applications, which is often needed when diagnosing or fixing custom issues. It also allows you to directly grep and tail log files for live debugging, amongst other things.

[github.com/basecamp/37](https://github.com/basecamp/37)

### Sentry

We track programming exceptions on Sentry. When a customer hits a “Oops, something went wrong!” screen, that means there’ll be an entry in Sentry explaining to programmers why they saw that screen. Keeping the exceptions under control and monitored is primarily the responsibility of SIP and Jim via on-call.

[getsentry.com](https://getsentry.com)

### Shipshape

Shipshape is how we make sure our work computers are up to our strict security protocol. When you’re given access to the company’s GitHub account, you can run Shipshape to be sure you’re up to code. Shipshape will also test your machine periodically to let you know (and our SIP team know) if your machine springs a leak and needs bailing out.

[github.com/basecamp/shipshape](https://github.com/basecamp/shipshape)
