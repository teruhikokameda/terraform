<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_oci"></a> [oci](#provider\_oci) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [oci_core_security_list.test_security_list](https://registry.terraform.io/providers/oracle/oci/latest/docs/resources/core_security_list) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_compartment_id"></a> [compartment\_id](#input\_compartment\_id) | Compartment OCID ID | `string` | n/a | yes |
| <a name="input_security_list_egress_security_rules_description"></a> [security\_list\_egress\_security\_rules\_description](#input\_security\_list\_egress\_security\_rules\_description) | Egress: Security List Rule Description | `string` | n/a | yes |
| <a name="input_security_list_egress_security_rules_destination"></a> [security\_list\_egress\_security\_rules\_destination](#input\_security\_list\_egress\_security\_rules\_destination) | Egress: Security List Rule Description | `string` | n/a | yes |
| <a name="input_security_list_egress_security_rules_destination_type"></a> [security\_list\_egress\_security\_rules\_destination\_type](#input\_security\_list\_egress\_security\_rules\_destination\_type) | Egress: Security List Rule Destination Type | `string` | n/a | yes |
| <a name="input_security_list_egress_security_rules_protocol"></a> [security\_list\_egress\_security\_rules\_protocol](#input\_security\_list\_egress\_security\_rules\_protocol) | Egress: Security List Rule Protocol | `string` | n/a | yes |
| <a name="input_security_list_ingress_security_rules_description"></a> [security\_list\_ingress\_security\_rules\_description](#input\_security\_list\_ingress\_security\_rules\_description) | Ingress: Security List Rule Description | `string` | n/a | yes |
| <a name="input_security_list_ingress_security_rules_protocol"></a> [security\_list\_ingress\_security\_rules\_protocol](#input\_security\_list\_ingress\_security\_rules\_protocol) | Egress: Security List Protocol | `string` | n/a | yes |
| <a name="input_security_list_ingress_security_rules_source"></a> [security\_list\_ingress\_security\_rules\_source](#input\_security\_list\_ingress\_security\_rules\_source) | Ingress: Security List Protocol | `string` | n/a | yes |
| <a name="input_security_list_ingress_security_rules_source_type"></a> [security\_list\_ingress\_security\_rules\_source\_type](#input\_security\_list\_ingress\_security\_rules\_source\_type) | Ingress: Security List Rule Source Type | `string` | n/a | yes |
| <a name="input_vcn_id"></a> [vcn\_id](#input\_vcn\_id) | VCN OCID ID | `string` | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->    