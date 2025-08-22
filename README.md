# Automating ConfigCat Resources with Terraform

**[Read the blog post here](https://configcat.com/blog/automating-configcat-resources-with-terraform)**

A companion sample app demonstrating how to automate [ConfigCat feature flags](https://configcat.com) resources using the [ConfigCat Feature Flags Provider](https://registry.terraform.io/providers/configcat/configcat/latest/docs).

## Build & Run

Instructions on how to build and run the application locally.

### Prerequisites

- [Install Terraform](https://developer.hashicorp.com/terraform/install)
- [ConfigCat API credentials](https://app.configcat.com/my-account/public-api-credentials)

### Steps

1. Open this repository in your terminal.

2. Add your [ConfigCat API credentials](https://app.configcat.com/my-account/public-api-credentials) to the `variables.tf` file.

3. Initialize Terraform with the following command:

```bash
terraform init
```

4. Plan and apply the ConfigCat resources:

```bash
terraform plan

terraform apply
```

## Learn more

Useful links to technical resources.

- [ConfigCat Feature Flags Provider documentation](https://registry.terraform.io/providers/configcat/configcat/latest/docs).

[**ConfigCat**](https://configcat.com) supports many other frameworks and languages. Check out the [full list of supported SDKs](https://configcat.com/docs/sdk-reference/overview/).

You can also explore other code samples for various languages, frameworks, and topics in [ConfigCat labs](https://github.com/configcat-labs) on GitHub.

Keep up with ConfigCat on [X](https://x.com/configcat), [Facebook](https://www.facebook.com/configcat), [LinkedIn](https://www.linkedin.com/company/configcat/), and [GitHub](https://github.com/configcat).

## Author

[Chavez Harris](https://github.com/codedbychavez)

## Contributions

Contributions are welcome!
