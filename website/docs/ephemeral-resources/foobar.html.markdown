---
layout: "legacy"
page_title: "Legacy: legacy_foobar ephemeral resource"
sidebar_current: "docs-legacy-foobar"
description: |-
  Misc
---

# legacy_foobar

Lorem ipsum dolor sit amet, soleat conceptam cum eu. Duo ne causae meliore antiopam. Sit dolor dolores eu. In eos elitr theophrastus. Inani legimus eu has, sit ex facete vituperata.

No eam labitur eligendi, oratio luptatum contentiones ut cum, has cu utinam aeterno. Mel populo labore pertinacia in. Eos labore scribentur ei, prima docendi pericula eos ne. Eu pri zril pertinacia. Eos ea harum inermis disputationi.

## Example Usage

```hcl
ephemeral "legacy_foobar" "test" {
  type = "test"
}
```

## Argument Reference
The following arguments are supported:

* `type` - (Optional) The type of the ephemeral resource.

## Attributes Reference
The following computed attributes are exported:

* `created_at` - The time the ephemeral resource was created in RFC3339 text format.
