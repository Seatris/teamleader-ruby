# Changelog
All notable changes to this project will be documented in this file.

## [0.8.0] - 2017-11-08
### Added
- Some methods related to invoices: `send_invoice`, `get_invoice_reminder_templates`, `get_invoice_reminder_template_content`, `get_invoice_cloud_url`

## [0.7.0] - 2017-11-08
### Added
- Methods for manipulating Deals

## [0.6.0] - 2017-10-31
### Added
- `get_creditnotes` method

## [0.5.1] - 2017-10-17
### Fixed
- Relax required parameters for `add_ticket` method.

## [0.5.0] - 2017-10-16
### Added
- Add methods for manipulating Tickets

## [0.4.0] - 2017-09-28
### Added
- Add support for getting bookkeeping accounts (cfr `get_bookkeeping_accounts` method)

## [0.3.1] - 2017-05-12
### Fixed
- Parameter check for `link_contact_to_company`

## [0.3.0] - 2017-05-12
### Added
- Methods for Contacts (add, get, update, delete, link to company, search, get contacts from a company, get relationships between contacts and companies)

## [0.2.0] - 2017-05-12
### Added
- Method `link_contact_to_company`
- Methods for Products (add, update, delete, get one, get all)
- Methods for Invoice (add, update payment status, get PDF, get one, get all)
- Update `get_company` to accept an Hash instead of an id as parameter

## [0.1.1] - 2017-05-12
### Changed
- Mark `json` dependency version as `>= 1`

## [0.1.0] - 2017-05-11
### Added
- Initial commit