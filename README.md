# StoreSolidusApp

An online store built on [Solidus](https://solidus.io), the open-source Rails
e-commerce framework. I used it to learn how a full storefront fits
together: catalogue, cart, checkout, accounts and admin.

- Solidus core, backend (admin) and API, with the starter storefront
- PayPal checkout through `solidus_paypal_commerce_platform`
- Custom branding on the storefront
- RSpec, FactoryBot and RuboCop set up for testing and linting

**Stack:** Ruby 2.7, Rails 7.0, Solidus, PostgreSQL

## Run it

```bash
bundle install
bin/rails db:setup
bin/rails server
```

Run `bin/rails solidus:sample:load` if you want demo products.

---

An early learning project from 2023, kept for reference and archived. My current work is on [my profile](https://github.com/gaganggoyal) and at [gagan.indiaoffers.in](https://gagan.indiaoffers.in).
