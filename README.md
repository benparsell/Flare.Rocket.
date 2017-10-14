# Flare.Rocket.
A brief overview of Inveigle's Flare.Rocket. application (https://flarerocketdev.inveiglecorp.com)

## About Flare.Rocket.
Flare.Rocket. is an application originally developed to work perfectly with the contracting workflow that Inveigle uses. With solutions for time tracking, invoicing, quotations, and collecting payments, Flare.Rocket. helps automate processes to save both Inveigle and its client's time.

## Features
Flare.Rocket. was originally thought of in ~ August 2016, and has been pivoted on multiple times throughout the sole-development process from myself. I had originally set out to build a full-scale entrepreneurship application and had pitched that idea at business plan pitch compeitions, and quickly realized I needed an MVP of a much smaller scale. I decided to build these core features to use for my software contracting.

### Quotations
If Inveigle receives an RFQ or has an initial consultation with a client, we will create a Quote through Flare.Rocket. that will automatically be emailed out to said client, and tied to their customer account on our end in the system. If accepted, a project will be created.

### Projects
A project is essentially an abstract class/model that "holds" many other things, such as quotes, invoices, a client, and time charged to that project. Projects are created after a quote is accepted, and closed after the balance of the project invoice is marked paid. 

### Time Tracking
Part of my initial problem with contracting was using a tool called Toggl. While a great tool to use to track how much time I was allocating to different projects, it made the rest of my process a mess when I needed to go back and categorize everything for an invoice. Time Tracking allows me to categorize and charge time directly to a project, which will be reflected as soon as I create an invoice for that project.

### Invocing
An invoice is created at the end of a project, currently. I do have plans to add the option of multiple invoices being sent out, but for my current process I usually bill in full at the end of a project. The invoice will be emailed to the client with an option to pay right then and there using Stripe, which would close out that project automatically if accepted. 

## Future plans
I've always loved the idea of having powerful dashboards. With this initial foundation, I do still want to build this out to cover many aspects of Inveigle, such as online marketing metrics, sales, etc. I also still have a SaaS backbone built from my initial development efforts (pre-pivot), so that could also be an option to open this up as a SaaS application.

