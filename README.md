# Brand New Congress API

This serves as the API that BNC web properties access for data. Currently being used by https://brandnewcongness.org, which is hosted on SiteTheory.

## Getting Started for Developers

1. Install [Node](https://nodejs.org/en/)
2. Clone this repository
2. Run `npm install`
3. Run `npm run dev`
4. Send requests to `http://localhost:8080` to test different APi endpoints
5. Run `npm run lint` to make sure your coding style is compliant.

## External services

The website interacts with some external APIs.  Instructions for how to test this stuff in dev are below:

### Nationbuilder

The API uses Nationbuilder as its backing CRM.  This is where it posts signups to and event data to. To test out code that hits Nationbuilder, you are free to use our development sandbox (the API token for which is in the .env file).  You can log in to the [admin interface](https://evanowski.nationbuilder.com/admin) with username `eowski@gmail.com` and password `abc123456`.

### Mailgun

The API uses Mailgun to send emails.  In dev, we use a sandbox account that requires you to be added as a verified recipient.  Request permission from @saikat in Slack to test emails.

### Airtable

The API uses Airtable to track candidates and nominations. There is a dev airtable user set up on a test database with username airtabledev@brandnewcongress.org and password ~.3XYY+ocnA7Rr1/f38ZKLNsPGo8L'. Use that to login to airtable to check out the test database and see Airtable API docs [here](https://airtable.com/appKkD926OWgpYF0r/api/docs)

### Maestro

## How to contribute

[Read the overview of how to contribute to BNC tech projects](https://github.com/BrandNewCongress/welcome)
