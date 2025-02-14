<!--Generated by WRITEME on 2023-03-27 23:24:34.051920 (UTC)-->
# Secrets Manager code examples for the SDK for Python

## Overview

Shows how to use the AWS SDK for Python (Boto3) to work with AWS Secrets Manager.

<!--custom.overview.start-->
<!--custom.overview.end-->

*Secrets Manager helps you to securely encrypt, store, and retrieve credentials for your databases and other services.*

## ⚠ Important

* Running this code might result in charges to your AWS account.
* Running the tests might result in charges to your AWS account.
* We recommend that you grant your code least privilege. At most, grant only the minimum permissions required to perform the task. For more information, see [Grant least privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).
* This code is not tested in every AWS Region. For more information, see [AWS Regional Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services).

<!--custom.important.start-->
<!--custom.important.end-->

## Code examples
### Single actions

Code excerpts that show you how to call individual service functions.

* [Create a secret](secretsmanager_basics.py#L38) (`CreateSecret`)
* [Delete a secret](secretsmanager_basics.py#L195) (`DeleteSecret`)
* [Describe a secret](secretsmanager_basics.py#L64) (`DescribeSecret`)
* [Get a random password](secretsmanager_basics.py#L116) (`GetRandomPassword`)
* [Get a secret value](secretsmanager_basics.py#L89) (`GetSecretValue`)
* [List secrets](secretsmanager_basics.py#L218) (`ListSecrets`)
* [Put a value in a secret](secretsmanager_basics.py#L136) (`PutSecretValue`)
* [Update the stage of a secret version](secretsmanager_basics.py#L169) (`UpdateSecretVersionStage`)

### Scenarios

Code examples that show you how to accomplish a specific task by calling multiple
functions within the same service.

* [Create and manage a secret](secretsmanager_basics.py) 

### Cross-service examples

Sample applications that work across multiple AWS services.

* [Create a lending library REST API](../../cross_service/aurora_rest_lending_library) 

## Run the examples

### Prerequisites


For prerequisites, see the [README](../../README.md#Prerequisites) in the `python` folder.


Install the packages required by these examples by running the following in a virtual environment:

```
python -m pip install -r requirements.txt
```


<!--custom.prerequisites.start-->
<!--custom.prerequisites.end-->

### Instructions


<!--custom.instructions.start-->
<!--custom.instructions.end-->


#### Create and manage a secret

This example shows you how to do the following:

* Create a Secrets Manager secret.
* Generate a random password and update a secret.
* Get current and previous values of a secret.
* Store binary data in a secret, then clean up resources.

Start the example by running the following at a command prompt:

```
python secretsmanager_basics.py
```

<!--custom.scenarios.secrets-manager_Scenario_CreateManageSecret.start-->
<!--custom.scenarios.secrets-manager_Scenario_CreateManageSecret.end-->

### Tests

⚠ Running tests might result in charges to your AWS account.


To find instructions for running these tests, see the [README](../../README.md#Tests)
in the `python` folder.



<!--custom.tests.start-->
<!--custom.tests.end-->

## Additional resources

* [Secrets Manager User Guide](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)
* [Secrets Manager API Reference](https://docs.aws.amazon.com/secretsmanager/latest/apireference/Welcome.html)
* [SDK for Python Secrets Manager reference](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html)

<!--custom.resources.start-->
<!--custom.resources.end-->

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: Apache-2.0