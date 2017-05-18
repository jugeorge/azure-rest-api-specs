# Billing
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Billing.



---
## Getting Started 
To build the SDK for Billing, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration for generating APIs


---
#### Basic Information 
These are the global settings for the Billing API.

``` yaml
# common 
title: Billing
description: Billing Client
api-version: 2017-04-24-preview

```


# API Version: 2017-04-24-preview

These settings apply only when `--api-version=2017-04-24-preview` is specified on the command line.

``` yaml $(api-version) == '2017-04-24-preview'
input-file:
- Microsoft.Billing/2017-04-24-preview/billing.json

```
 
# API Version: 2017-02-27-preview

These settings apply only when `--api-version=2017-02-27-preview` is specified on the command line.

``` yaml $(api-version) == '2017-02-27-preview'
input-file:
- Microsoft.Billing/2017-02-27-preview/billing.json

```


---
#### Language-specific settings: CSharp

These settings apply only when `--csharp` is specified on the command line.

``` yaml $(csharp)
csharp:
  # override the default output folder
  output-folder: $(output-folder)/csharp
```
