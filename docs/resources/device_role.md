---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "netbox_device_role Resource - terraform-provider-netbox"
subcategory: ""
description: |-
  
---

# netbox_device_role (Resource)



## Example Usage

```terraform
resource "netbox_device_role" "core_sw" {
  color_hex = "FF00FF"
  name      = "core-sw"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `color_hex` (String)
- `name` (String)

### Optional

- `slug` (String)
- `vm_role` (Boolean)

### Read-Only

- `id` (String) The ID of this resource.

