Sample JSON schema for IAM assume-role policy documents
=======================================================

This repository contains a JSON schema that could be used to
validate AWS account IDs used in assume-role policy documents.
Note particularly the .definitions.accounts.anyOf property, which
contains a list of valid ARN patterns.

You can validate any policy document against this schema by running a JSON
schema validator.  I've tested it with
[ajv-cli](https://github.com/jessedc/ajv-cli) but others should work.

LICENSE
-------
This example is in the public domain.
