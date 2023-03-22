---
### Title the install tools article with the name of the tool to be installed
### Include vendor name where appropriate
title: Azure

### Optional additional search terms (one per line) to assist in finding the article
additional_search_terms:

### Estimated completion time in minutes (please use integer multiple of 5)
minutes_to_complete: 10

### Link to official documentation
official_docs: https://learn.microsoft.com/en-us/cli/azure/reference-index?view=azure-cli-latest#az-login

### PAGE SETUP
weight: 1                       # Defines page ordering. Must be 1 for first (or only) page.
tool_install: true              # Set to true to be listed in main selection page, else false
multi_install: false            # Set to true if first page of multi-page article, else false
multitool_install_part: false   # Set to true if a sub-page of a multi-page article, else false
layout: installtoolsall         # DO NOT MODIFY. Always true for tool install articles
---

The installation of Terraform on your Desktop/Laptop needs to communicate with Azure. Thus, Terraform needs to be authenticated.

This section provides answers to the most frequently asked azure authentication questions.

Feel free to seek out additional azure authentication tutorials or add more information to this page. 

## Sign in interactively
 
The Azure CLI's default authentication method for logins uses a web browser and access token to sign in. Run the below command for login.

```console
az login
```

The output will be similar as shown below.

```output
asdfgb
```

Open the link in a browser and enter the code that you receive in the above message. Then login into azure account. After you log in, You will see below details in command line:

```output
asdfgb
```
