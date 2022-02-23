+++
title = "LegacyYumCookbookRecipes"

+++

<!-- This content is automatically generated. See https://github.com/chef/chef-web-docs/blob/main/generated/README.md -->

The department is: `LegacyYumCookbookRecipes`

The full name of the cop is: `Chef/Deprecations/LegacyYumCookbookRecipes`

| Enabled by default | Supports autocorrection | Target Chef Version |
| --- | --- | --- |
| Enabled | No | All Versions |

## Examples


#### incorrect

```ruby
include_recipe 'yum::elrepo'
include_recipe 'yum::epel'
include_recipe 'yum::ius'
include_recipe 'yum::remi'
include_recipe 'yum::repoforge'
include_recipe 'yum::yum'
```

## Configurable attributes

<table>
<tbody><tr>
<th>Name</th>
<th>Default value</th>
<th>Configurable values</th>
</tr>
<tr>
<td style="text-align:center">Version Added</td>
<td style="text-align:center">5.4.0</td>
<td style="text-align:center">String</td>
</tr>
<tr><td style="text-align:center">Include</td>
<td style="text-align:center"><ul>
</ul>
</td>
<td style="text-align:center">Array</td>
</tr></tbody></table>