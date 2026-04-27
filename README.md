# Terraform-AKS-Cluster-Provisioning-Guide
cat &lt;&lt;EOF > provider.tf terraform {   required_providers {     azurerm = {       source  = "hashicorp/azurerm"       version = "~> 3.0"     }   } }  provider "azurerm" {   features {} } EOF
