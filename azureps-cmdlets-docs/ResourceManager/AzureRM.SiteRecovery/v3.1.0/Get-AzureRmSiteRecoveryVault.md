---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 96C228C5-C3CB-4E5C-8C68-8D893BCE7711
---

# Get-AzureRmSiteRecoveryVault

## SYNOPSIS
Gets Site Recovery vaults from the current subscription.

## SYNTAX

```
Get-AzureRmSiteRecoveryVault [-ResourceGroupName <String>] [-Name <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSiteRecoveryVault** cmdlet gets a list of Azure Site Recovery vaults or a specific Site Recovery vault from the current subscription.

## EXAMPLES


## PARAMETERS

### -ResourceGroupName
Specifies the name of the Azure resource group from which to get the recovery services object.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Specifies the name of the vault.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[New-AzureRmSiteRecoveryVault](./New-AzureRmSiteRecoveryVault.md)

[Remove-AzureRmSiteRecoveryVault](./Remove-AzureRmSiteRecoveryVault.md)
