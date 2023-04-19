---
# generated by https://github.com/fbreckle/terraform-plugin-docs
page_title: "netbox_rack_role Resource - terraform-provider-netbox"
subcategory: "Data Center Inventory Management (DCIM)"
description: |-
  From the official documentation https://docs.netbox.dev/en/stable/models/dcim/rackrole/:
  Each rack can optionally be assigned a user-defined functional role. For example, you might designate a rack for compute or storage resources, or to house colocated customer devices.
---

# netbox_rack_role (Resource)

From the [official documentation](https://docs.netbox.dev/en/stable/models/dcim/rackrole/):

> Each rack can optionally be assigned a user-defined functional role. For example, you might designate a rack for compute or storage resources, or to house colocated customer devices.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `color_hex` (String)
- `name` (String)

### Optional

- `description` (String)
- `slug` (String)
- `tags` (Set of String)

### Read-Only

- `id` (String) The ID of this resource.

