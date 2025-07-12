# pulumi policy disable

> Disable a Policy Pack for a Pulumi organization.
> More information: <https://www.pulumi.com/docs/iac/cli/commands/pulumi_policy_disable/>.

- Disable a Policy Pack for a Pulumi organization for the current Policy Group (defaults to all versions):

`pulumi policy disable {{organization_name/policy_pack_name}}`

- Disable a Policy Pack for a Pulumi organization for the current Policy Group with a specific version:

`pulumi policy disable {{organization_name/policy_pack_name}} {{--version}} {{version}}`

- Disable a Policy Pack for a Pulumi organization for a specific Policy Group:

`pulumi policy disable {{organization_name/policy_pack_name}} {{--policy-group}} {{policy_group_name}}`

- Display help:

`pulumi policy disable {{[-h|--help]}}`
