<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.13 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_openstack"></a> [openstack](#provider\_openstack) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [openstack_images_image_v2.debian_10](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/images_image_v2) | resource |
| [openstack_images_image_v2.debian_11_man](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/images_image_v2) | resource |
| [openstack_images_image_v2.debian_9](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/images_image_v2) | resource |
| [openstack_images_image_v2.focal](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/images_image_v2) | resource |
| [openstack_images_image_v2.kali](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/images_image_v2) | resource |
| [openstack_images_image_v2.preinstalled_debian_11_man](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/images_image_v2) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_kali"></a> [kali](#input\_kali) | Import Kali image | `bool` | `true` | no |
| <a name="input_preinstalled_man"></a> [preinstalled\_man](#input\_preinstalled\_man) | Import preinstalled man image | `bool` | `true` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_focal_name"></a> [focal\_name](#output\_focal\_name) | Name of Ubuntu Focal image |
<!-- END_TF_DOCS -->
