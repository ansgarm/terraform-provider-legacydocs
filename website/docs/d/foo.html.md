---
layout: "legacy"
page_title: "Legacy: legacy_foo data source"
sidebar_current: "docs-legacy-datasource-foo"
description: |-
  Foo
---

# legacy_foo

Lorem ipsum dolor sit amet, soleat conceptam cum eu. Duo ne causae meliore antiopam. Sit dolor dolores eu. In eos elitr theophrastus. Inani legimus eu has, sit ex facete vituperata.

No eam labitur eligendi, oratio luptatum contentiones ut cum, has cu utinam aeterno. Mel populo labore pertinacia in. Eos labore scribentur ei, prima docendi pericula eos ne. Eu pri zril pertinacia. Eos ea harum inermis disputationi.

Et eum noluisse luptatum, cum ea omnes feugiat scripserit. In nemore noluisse tacimates eam, eum et senserit adipiscing, eos choro postea ne. No suas agam quo, has ex hinc volumus, erat discere epicurei pro in. Eu erant habemus usu, quo eu gubergren scriptorem, sit ne placerat contentiones. Duo saperet omnesque percipit eu, id sanctus patrioque signiferumque vis.

## Example Usage

```hcl
data "legacy_foo" "test" {
  type = "test"
}
```

## Argument Reference
The following arguments are supported:

* `type` - (Optional) The type of the resource.

## Attributes Reference
The following computed attributes are exported:

* `created_at` - The timestamp resource was created in RFC3339 text format.
