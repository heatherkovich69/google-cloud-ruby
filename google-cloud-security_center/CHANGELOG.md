# Release History

### 0.5.1 / 2020-01-23

#### Bug Fixes

* Add missing require

#### Documentation

* Update copyright year
* Update Status documentation

### 0.5.0 / 2019-12-20

#### Features

* Add attributes to SecurityCenterProperties and ListFindingsResult
  * Add SecurityCenterProperties#resource_display_name
  * Add SecurityCenterProperties#resource_parent_display_name
  * Add SecurityCenterProperties#resource_project_display_name
  * Add ListFindingsResult#resource (Resource)
  * Update network configuration

### 0.4.3 / 2019-12-19

#### Documentation

* Update in-code samples

### 0.4.2 / 2019-11-19

#### Documentation

* Update IAM Policy documentation

### 0.4.1 / 2019-11-06

#### Bug Fixes

* Update minimum runtime dependencies

### 0.4.0 / 2019-10-29

This release requires Ruby 2.4 or later.

#### Documentation

* Clarify which Google Cloud Platform products support auto-discovered credentials

### 0.3.3 / 2019-10-01

#### Documentation

* Fix role string in IAM Policy JSON example
* Update IAM Policy class description and sample code

### 0.3.2 / 2019-09-04

#### Documentation

* Update IAM documentation
  * Update GetPolicyOption#requested_policy_version docs
  * Un-deprecate Policy#version

### 0.3.1 / 2019-08-23

#### Documentation

* Update documentation

### 0.3.0 / 2019-07-08

* Add IAM GetPolicyOptions.
* Support overriding service host and port.
* Explicitly require all protobuf classes.

### 0.2.1 / 2019-06-11

* Update IAM:
  * Deprecate Policy#version
  * Add Binding#condition
  * Add Google::Type::Expr
  * Update documentation
* Add VERSION constant

### 0.2.0 / 2019-05-06

* Update SecurityCenterClient#run_asset_discovery response value.
  * The long running Operation response type has been updated to
    RunAssetDiscoveryResponse instead of Google::Protobuf::Empty.
* Add RunAssetDiscoveryResponse.

### 0.1.1 / 2019-04-29

* Add AUTHENTICATION.md guide.

### 0.1.0 / 2019-04-25

* Initial release.
