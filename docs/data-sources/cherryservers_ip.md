---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "cherryservers_ip Data Source - cherryterraform"
subcategory: ""
description: |-
  
---

# cherryservers_ip (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `ip_address` (String) The IPv4 address
- `ip_id` (String) The IP address in canonical format used in the reverse DNS record

### Read-Only

- `a_record` (String) Relative DNS name for the IP address. Resulting FQDN will be '<relative-dns-name>.cloud.cherryservers.net' and must be globally unique
- `address` (String) The IP address in canonical format used in the reverse DNS record
- `address_family` (Number) IP address family IPv4 or IPv6
- `cidr` (String) The CIDR block of the IP
- `ddos_scrubbing` (Boolean) If True, DDOS scrubbing protection will be applied in real-time
- `gateway` (String) The gateway IP address
- `id` (String) The ID of this resource.
- `project_id` (String) ID of the project you are working on
- `ptr_record` (String) Reverse DNS name for the IP address
- `region` (String) Slug of the region. Example: eu_nord_1 [See List Regions](https://api.cherryservers.com/doc/#tag/Regions/operation/get-regions)
- `tags` (Map of String) Key/value metadata for server tagging
- `target_hostname` (String) The hostname of the server to assign the created IP to
- `target_id` (Number) The ID of the server to assign the created IP to
- `target_ip_id` (String) Subnet or primary-ip type IP ID to route the created IP to
- `type` (String) The type of IP address

