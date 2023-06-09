# vscode-snippet-extension

VSCode extension for installing my most used snippets multiple places.

## Features

This extension gives a range of snippets that can be used while developing and make your life more efficient.

### General snippets

**current_datetime** - Inserts current date time in ISO format. - Keywords: "datetime current_time current_date iso_time"

**s_dash_s_dash_s_dash_s_string** - Inserts a string with %s-%s-%s-%s for use with format functions. - Keywords: "s_dash_s_dash_s_dash_s ssss"

**s_dash_s_dash_s_string** - Inserts a string with %s-%s-%s for use with format functions. - Keywords: "s_dash_s_dash_s sss"

**s_dash_s_string_string** - Inserts a string with %s-%s for use with format functions. - Keywords: "s_dash_s ss"

**unixtime** - Inserts current unix timestamp. - Keywords: "unixtime unix_time timestamp"

**UUID** - Generates a new random GUID/UUID. - Keywords: "guid uuid"

### Snippets snippets

**snippet_boiler** - Boilerplate json object for creating a new snippet. - Keywords: "snippet"

**snippet_input_choose** - Inserts an input with default value for snippets body. - Keywords: "choose"

**snippet_input_with_default** - Inserts an input with default value for snippets body. - Keywords: "input"

### Terraform snippets

**tf_email_variable** - Inserts a variable block for an email input. - Keywords: `email_variable`

**tf_environment_name_variable** - Inserts a variable block for an environment runtime name input. - Keywords: "environment_name env_name environment_variable"

**tf_format** - Inserts an already filled format function. - Keywords: "format"

**tf_format_ss** - Inserts an already filled format function with 2 %s. - Keywords: "format_ss"

**tf_format_sss** - Inserts an already filled format function with 3 %s. - Keywords: "format_sss"

**tf_format_ssss** - Inserts an already filled format function with 4 %s. - Keywords: "format_ssss"

**tf_moved** - Inserts ready to use move block. - Keywords: "moved"

**tf_replace_special_chars** - Inserts a replace function, around selected text, that removes all but alphanumeric chars. - Keywords: "replace replace_special_chars text_only tf_replace_special_chars"

### Terraform testing snippets

**tf_test_assertion** - Inserts a test assertion resource for integration testing in Terraform. - Keywords: "test_assertion_tf"

**tf_test_check** - Inserts a check block for use with test assertions resource. - Keywords: "check_test_assertion"

**tf_test_equal** - Inserts a equal block for use with test assertions resource. - Keywords: "equal_test_assertion"

### Azure specific Terraform snippets

**app_settings_appi** - Add application insights settings to an app service app settings. - Keywords: "appi_reference insights_reference appi_app_settings insights_app_settings application insights reference"

**azurerm_app_service_uami_reference** - Inserts a reference to an user assigned identity on an app service. - Keywords: "app_service_uami_reference uami_reference user_assigned_identity_reference"

**azurerm_linux_web_app** - Inserts a linux web app terraform resource with standard settings. - Keywords: "linux_web_app linux_api_app app_service api_app"

**azurerm_provider** - Inserts a standard provider block for azurerm. - Keywords: "azurerm provider"

**azurerm_role_assignment** - Inserts an azure role assignment. - Keywords: "role_assignment"

**azurerm_service_plan** - Inserts a service plan terraform resource with standard settings. - Keywords: "plan app_service_plan service_plan"

**azurerm_uami** - Creates a managed identity terraform resource with standard settings. - Keywords: "user_assigned_identity identity uami msi"

### Azure naming snippets

**azurerm_naming_app_service_plan** - Inserts a local for generating an app service plan name. - Keywords: "app_service_plan_naming asp_naming"

**azurerm_naming_function_app** - Inserts a local for generating a function app name. - Keywords: "function_app_naming func_naming"

**azurerm_naming_log_analytics** - Inserts a local for generating a log analytics name. - Keywords: "log_analytics_naming"

**azurerm_naming_mssql_database** - Inserts a local for generating a MSSql database name. - Keywords: "mssql_database_naming"

**azurerm_naming_mssql_server** - Inserts a local for generating a MSSql server name. - Keywords: "mssql_server_naming"

**azurerm_naming_storage_account** - Inserts a local for generating a storage account name. - Keywords: "storage_account_naming"

### Github Workflow snippets

**gh_action_input** - Inserts a input object for a composite action configuration. - Keywords: "action_input"

**gh_checkout_step** - Inserts a github checkout step. - Keywords: "checkout"

**gh_composite_action** - Inserts a boilerplate for starting a new composite action file. - Keywords: "composite_action"

**gh_run_action** - Inserts a run action step in your github workflow. - Keywords: "run_action"

**gh_workflow_job** - Inserts a job object for use in a github workflow. - Keywords: "job"

## Release Notes

See the release section on Github for latest release notes.
