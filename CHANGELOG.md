<!-- markdownlint-disable MD024 -->
# Change Log

All notable changes to the "mrheine-snippets" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## 0.0.11 - preview

### Changed

- Added more roles to role assignment snippet.

## 0.0.10 - preview

### Fixed

- Correct scope on snippet snippets.
- Correct scope in project file on github action workflow snippets.

### Changed

- Upgraded checkout action to v4 on github actions snippets.

## 0.0.9 - preview

### Added

- Terraform snippet for MS SQL server auditing.
- Terraform local snippet for Azure Service Bus Namespace naming.

### Fixed

- Missing backslash in email validation regex.
- Typo in comment on MS SQL terraform snippet.

### Changed

- Service bus options for RBAC role assignment snippet.
- Github actions snippets changed to `github-actions-workflow` scope, to function better with [Github Actions](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions) extension.

## 0.0.8 - preview

### Added

- Terraform snippet for Azure MS SQL server.
- Terraform snippet for Azure Storage Account.
- Container registry naming local snippet for Terraform.

### Changed

- Added more allowed characters in email verification block.
- Added more options for RBAC role assignment snippet.

## 0.0.7 - preview

### Added

- Snippets for terraform email variable input.

## 0.0.6 - preview

### Added

- Github workflow snippets
  - Add new job
  - Add run action
  - Github checkout action step
- Github composite action snippets
  - Composite action file boilerplate
  - Input object
- Snippet input variable and choose inputs wrappers for selected text.

### Changed

- Terraform replace snippet will now autofill selected text.
- Terraform format snippets will now ask for the correct number of inputs for the format string.

### Fixed

- Correct path to general snippets in project manifest.

## 0.0.5 - preview

### Fixed

- Add new testing snippets to project manifest.

## 0.0.4 - preview

### Added

- Terraform test assertion snippet
  - Resource block
  - Equals block
  - Check block

## 0.0.3 - preview

### Added

- Terraform snippets
  - Environment variable
  - `moved` block
  - replace of special chars
  - format functions with `%s`
- Snippets object snippet
- General snippets
  - uuid
  - unix time
  - datetime
  - format strings
- Azure Terraform snippets
  - AzureRM provider with wise defaults
  - User assigned identity resource with wise defaults
  - App service plan resource with wise defaults
  - Linux web app with wise defaults
  - Role assignments with wise defaults
  - User assigned identity reference for app services
  - Application Insights reference for app services app settings
- Azure naming standard locals snippets
  - App service plan
  - Function app
  - Log analytics
  - MSSQL database
  - MSSQL server
  - Storage account
