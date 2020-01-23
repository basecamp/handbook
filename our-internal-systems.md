# Our Internal Systems

Besides the customer-facing applications, like the different versions of Basecamp, we have a number of internal systems that help us support, report, and operate the company. They are as follows:

### Dash

Dash is the main hub for everything that has to do with logging (like finding why a request is slow or whether an email has been delivered), reporting (everything from number of support cases handled to split of devices used to access Basecamp), application health (response times, job queue exceptions etc). Justin is managing this hub.

https://dash.37signals.com/

### Queenbee

Queenbee is our invoice, accounting, and identity system. Here you can look up any customer account, see whether they are comped, refund an invoice, or even login as a customer.

That’s an immense amount of power and we take its use very seriously. We only ever login as a customer after having been given explicit permission to do so, never preemptively. Our customers expect that their information is confidential, even from us, and we intend to honor that expectation at all times.

https://billing.37signals.com

### The 37 command

This is perhaps less of a system and more of an interface to all our other systems. The 37 command gives easy access to the production consoles for all the applications, which is often needed when diagnosing or fixing custom issues. It also allows you to directly grep and tail log files for live debugging, amongst other things.

https://github.com/basecamp/37

### Sentry

We track programming exceptions on Sentry. When a customer hits a "Oops, something went wrong!" screen, that means there'll be an entry in Sentry explaining to programmers why they saw that screen. Keeping the exceptions under control and monitored is primarily the responsibility of SIP and Jim via on-call.

https://getsentry.com/

### Customer.IO

All drip campaigns, welcome emails, and other email marketing campaigns for Basecamp 3 are run through Customer.IO. This allows the marketing team independently tweak and measure the campaigns.

https://customer.io

### Shipshape

Shipshape is how we make sure our work computers are up to Basecamp's strict security protocol. When you're given access to Basecamp's GitHub account, you can run Shipshape to be sure you're up to code. Shipshape will also test your machine periodically to let you know (and our SIP team know) if your machine springs a leak and needs bailing out.

https://github.com/basecamp/shipshape

## Sections
* [Basecamp Is You](https://github.com/basecamp/handbook/blob/master/basecamp-is-you.md)
* [What We Stand For](https://github.com/basecamp/handbook/blob/master/what-we-stand-for.md)
* [What Influenced Us](https://github.com/basecamp/handbook/blob/master/what-influenced-us.md)
* [Vocabulary](https://github.com/basecamp/handbook/blob/master/vocabulary.md)
* [Product Histories](https://github.com/basecamp/handbook/blob/master/product-histories.md)
* [Who Does What?](https://github.com/basecamp/handbook/blob/master/orgchart.md)
* [Where We Work](https://github.com/basecamp/handbook/blob/master/where-we-work.md)
* [Benefits & Perks](https://github.com/basecamp/handbook/blob/master/benefits-and-perks.md)
* [Getting Started](https://github.com/basecamp/handbook/blob/master/getting-started.md)
* [How We Work](https://github.com/basecamp/handbook/blob/master/how-we-work.md)
* [Our Rituals](https://github.com/basecamp/handbook/blob/master/our-rituals.md)
* [Making a Career](https://github.com/basecamp/handbook/blob/master/making-a-career.md)
* [Our Internal Systems](https://github.com/basecamp/handbook/blob/master/our-internal-systems.md)
* [A Note About Moonlighting](https://github.com/basecamp/handbook/blob/master/moonlighting.md)
* [International Travel Guide](https://github.com/basecamp/handbook/blob/master/international-travel-guide.md)
* [FAQ](https://github.com/basecamp/handbook/blob/master/faq.md)
