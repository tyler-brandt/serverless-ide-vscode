# Change log

## v0.4.11
- Update SAM/Cloudformation schema with recent updates
- Small serverless framework schema improvements
- Allow additional properties for serverless framework schema for better plugins support

## v0.4.10
- Turns off schema validation, when `cfn-lint` option is selected

## v0.4.9
- Gracefully handle exceptions when interacting unsupported yaml documents

## v0.4.8
- Rename `org` to `tenant` in serverless framework schema

## v0.4.6
- Workplace capabilities for validation
- Fix runtime handling for serverless framework
- Minor changes and fixes

## v0.4.5
- Quick installation dialog for cfn-lint
- Remove fallback to default schema validation when cfn-lint validation failed

## v0.4.4
- Bug fixes and improvements for Serverless Framework

## v0.4.2
- Go to definition
- References
- Add default SAM resources
- Minor performance improvements

## v0.4.0
- Validation and autocompletion for resources references
- Improved support of AWS Intrinsic Functions
- Basic support for Serverless Framework

## v0.3.8
- Fix SAM schema to support MethodSettings property in AWS::Serverless::Api resource type
- Additional logging around cfn-lint validation

## v0.3.7
- Delete sentry global handlers

## v0.3.6
- less verbose logging
- telemetry and crash reporting

## v0.3.4
- cfn-lint support fix
- update dependencies

## v0.3.2 (May 12, 2019)
- cfn-lint support

## v0.2.1 (March 3, 2019)

- Add support for global SAM configuration (fix [#5](https://github.com/threadheap/serverless-ide-vscode/issues/5))

## v0.2.0 (February 26, 2019)

- Support for CloudFormation templates
- At glance documentation for AWS resources

## 0.3.1 (April 27, 2019)

- Add support of cfn-lint
- Simplified configuration

## 0.3.2 (May 12, 2019)

- Basic telemtry
