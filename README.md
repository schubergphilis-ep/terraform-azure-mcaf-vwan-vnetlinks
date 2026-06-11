# terraform-azure-mcaf-vwan-vnetlinks
<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.7 |
| <a name="requirement_azurerm"></a> [azurerm](#requirement\_azurerm) | >= 4 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_azurerm"></a> [azurerm](#provider\_azurerm) | 4.7.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [azurerm_virtual_hub_connection.this](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/virtual_hub_connection) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_virtual_hub_connection"></a> [virtual\_hub\_connection](#input\_virtual\_hub\_connection) | n/a | <pre>map(object({<br/>    vnetlink_name             = string ## name of the virtual network link.<br/>    virtual_hub_id            = string ## Resource ID of the Virtual Hub.<br/>    remote_virtual_network_id = string ## Resource ID of the remote virtual network.<br/>  }))</pre> | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->