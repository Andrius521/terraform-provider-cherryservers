---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "cherryterraform Provider"
subcategory: ""
description: |-
  
---

# cherryterraform Provider



## Example Usage

```terraform
terraform {
  required_providers {
    cherryservers = {
      source = "cherryservers/cherryservers"
    }
  }
}

provider "cherryservers" {
  api_token = "CHEERRY_SERVERS_API_KEY" // API key can be found in Cherry Servers client portal - https://portal.cherryservers.com/settings/api-keys
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `api_key` (String) Cherry Servers [API Token](https://portal.cherryservers.com/settings/api-keys) that allows interactions with the API
