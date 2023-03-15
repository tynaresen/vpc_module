# vpc_module_new
Terraform Module VPC

## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >=  1.1.6 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | ~> 4 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | ~> 4 |

## Resources

| Name | Type |
|------|------|
| [aws_vpc.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc) | resource |
| [aws_internet_gateway.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/internet_gateway) | resource |
| [aws_eip.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eip) | resource |
| [aws_nat_gateway.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/nat_gateway) | resource |
| [aws_subnet.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet) | resource |
| [aws_route_table.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table) | resource |
| [aws_route_table_association.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association) | resouce |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_region"></a> [region](#input\_region) | NA | `string` | n/a | yes |
| <a name="input_cidr_block"></a> [cidr\block](#input\_cidr\_block) | NA | `string` | n/a | yes |
| <a name="input_public_subnets_cidr"></a> [public\_subnets\cidr](#input\_public\_subnets\_cidr) | NA | `string` | n/a | yes |
  <a name="input_private_subnets_cidr"></a> [private\_subnets\cidr](#input\_private\_subnets\_cidr) | NA | `string` | n/a | yes | 
  <a name="input_private_subnets"></a> [private\_subnets](#input\_private\_subnets) | NA | `string` | n/a | yes | 
  <a name="input_public_subnets"></a> [public\_subnets](#input\_public\_subnets) | NA | `string` | n/a | yes | 
| <a name="input_availability_zones"></a> [availability\zones](#input\_availability\_zones) | NA | `string` | n/a | yes |
| <a name="input_tags"></a> [tags](#input\_tags) | NA | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="vpc_id"></a> [vpc_id](#output\_vpc\_id) | NA |
| <a name="region"></a> [region](#output\_region) | NA |
