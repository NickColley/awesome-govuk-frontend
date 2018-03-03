# Awesome GOV.UK Frontend

(Still a work in progress, but eventually would be good to have as an 'official' [awesome list](https://github.com/sindresorhus/awesome))

Curated list of GOV.UK related frontend ecosystem.

Dependencies on core libraries are marked with angle brackets ([ ])

Have I missed something that should be here? Please let me know or open a pull request!

This list will be pruned over time and should represent active or well maintained projects.

## Core libraries
- [GOV.UK Elements](https://github.com/alphagov/govuk_elements) - GOV.UK Elements form the building blocks from which all pages are made. https://govuk-elements.herokuapp.com/
  - [sass](https://www.npmjs.com/package/govuk-elements-sass)
- [GOV.UK Template](https://github.com/alphagov/govuk_template) - Packaging of a template containing the GOV.UK header and footer, and associated assets. http://alphagov.github.io/govuk_template/
  - [jinja](https://github.com/alphagov/govuk_template_jinja), [ejs](https://github.com/alphagov/govuk_template_ejs), [mustache](https://github.com/alphagov/govuk_template_mustache)
- [GOV.UK Frontend Toolkit](https://github.com/alphagov/govuk_frontend_toolkit) - Generic tools and helpers for building GDS front-end apps
  - [gem](https://github.com/alphagov/govuk_frontend_toolkit_gem), [npm](https://github.com/alphagov/govuk_frontend_toolkit_npm), [composer](https://github.com/PurpleBooth/govuk_frontend_toolkit_composer)

### Future
- [GOV.UK Frontend](https://github.com/alphagov/govuk-frontend) - replacement for govuk_elements, govuk_template, govuk_frontend_toolkit. Private beta only.
- [GOV.UK Design System](https://github.com/alphagov/govuk-design-system) - guidance and examples of components, styles and patterns you can use to design government platforms and services. [govuk-frontend]

## Downstream

### Ports

#### JavaScript (including Node.js)

##### AngularJS
- [Single Page Platform Development Kit (PDK)](https://github.com/CJSCommonPlatform/govuk_single_page_pdk) - This Platform development kit includes and extends the GDS GOV.UK packages for developing citizen and business facing services as a platform. [govuk-elements-sass, govuk_template_mustache]

##### Marko
- [govuk-elements-marko](https://github.com/gunjam/govuk-elements-marko) - A set of Marko components implementing GOV.UK elements.

##### Nunjucks
- [govuk-elements-nunjucks](https://github.com/htmlandbacon/govuk-elements-nunjucks) - This includes a selection form macros from GOV.UK elements, these are using nunjucks.
- [trade-elements](https://github.com/uktrade/trade-elements) - Front end pattern library for Department of International Trade [govuk-elements-sass, govuk_frontend_toolkit]

##### React
- [govuk-starter-kit](https://github.com/gdbarnes/govuk-starter-kit) - React app to generate files and markup to use in govuk applications [govuk-elements-sass, govuk_frontend_toolkit, govuk_template_jinja]
- [govuk-react-components](https://github.com/lennym/govuk-react-components) - A set of react components to build the basic elements described in govuk-elements. [govuk_template_mustache, govuk-elements-sass]
- [govuk-react](https://www.npmjs.com/package/govuk-react) - A port of the govuk-frontend components for React using Glamorous. http://penx.github.io/govuk-react/

#### Python

##### Jinja

- [Digital Marketplace frontend toolkit](https://github.com/alphagov/digitalmarketplace-frontend-toolkit) - Front end toolkit for the Digital Marketplace http://alphagov.github.io/digitalmarketplace-frontend-toolkit/

##### Django
- [Django GOV.UK Template](https://github.com/ministryofjustice/django-govuk-template) - Django app that builds `template` and `elements` components from the Government Digital Services style guide

##### Ruby
- [GOV.UK Publishing Components](https://github.com/alphagov/govuk_publishing_components) - GDS GOV.UK Publishing team (Team that maintains the www.GOV.UK bit of GOV.UK), A gem to document and distribute components in GOV.UK Publishing frontend applications  https://govuk-publishing-components.herokuapp.com/component-guide [govuk_frontend_toolkit]
- [GovukElementsFormBuilder](https://github.com/ministryofjustice/govuk_elements_form_builder) - Form builder helper methods to develop GOV.UK elements styled applications in Ruby on Rails https://govuk-elements-rails-guide.herokuapp.com/ [govuk_elements_rails, govuk_frontend_toolkit]

### Other
- [IPO Assets](https://github.com/intellectual-property-office/Assets) - This project is used to build the UK Intellectual Property Office frontend UI styling. [govuk-elements-sass, govuk_template_ejs]
- [HMRC Assets frontend](https://github.com/hmrc/assets-frontend) - Shared static assets for frontends on the Multichannel Digital Tax Platform http://hmrc.github.io/assets-frontend [govuk-elements-sass, govuk_frontend_toolkit, govuk_template]

## Components
Single purpose components
- [Accessible Autocomplete](https://github.com/alphagov/accessible-autocomplete) - An autocomplete component, built to be accessible. https://alphagov.github.io/accessible-autocomplete/examples

## Prototyping
- [GOV.UK Prototype Kit](https://github.com/alphagov/govuk_prototype_kit) - The prototype kit provides a simple way to make interactive prototypes that look like pages on GOV.UK. [govuk-elements-sass, govuk_frontend_toolkit, govuk_template_jinja]

## User-facing Frontend applications
- [www.GOV.UK (not any service.gov.uk domain pages)](https://docs.publishing.service.gov.uk/#frontend-apps)
- [GOV.UK Verify](https://github.com/alphagov/verify-frontend)
- [GOV.UK Pay](https://github.com/alphagov/pay-frontend)

## Useful tools
- https://libraries.io/search?q=govuk
