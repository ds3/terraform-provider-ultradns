---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "ultradns_tcpool Resource - ica"
subcategory: ""
description: |-
  
---

# ultradns_tcpool (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **description** (String)
- **name** (String)
- **rdata** (Block Set, Min: 1) (see [below for nested schema](#nestedblock--rdata))
- **zone** (String)

### Optional

- **act_on_probes** (Boolean)
- **backup_record_failover_delay** (Number)
- **backup_record_rdata** (String)
- **id** (String) The ID of this resource.
- **max_to_lb** (Number)
- **run_probes** (Boolean)
- **ttl** (Number)

### Read-Only

- **hostname** (String)

<a id="nestedblock--rdata"></a>
### Nested Schema for `rdata`

Required:

- **host** (String)

Optional:

- **failover_delay** (Number)
- **priority** (Number)
- **run_probes** (Boolean)
- **state** (String)
- **threshold** (Number)
- **weight** (Number)

