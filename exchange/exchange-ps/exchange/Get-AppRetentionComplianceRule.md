---
external help file: Microsoft.Exchange.TransportMailflow-Help.xml
online version: https://docs.microsoft.com/powershell/module/exchange/get-appretentioncompliancerule
applicable: Security & Compliance Center
title: Get-AppRetentionComplianceRule
schema: 2.0.0
author: chrisda
ms.author: chrisda
ms.reviewer:
---

# Get-AppRetentionComplianceRule

## SYNOPSIS
This cmdlet is available only in Security & Compliance Center PowerShell. For more information, see [Security & Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/scc-powershell).

Use the Get-AppRetentionComplianceRule to view app retention compliance rules.

For information about the parameter sets in the Syntax section below, see [Exchange cmdlet syntax](https://docs.microsoft.com/powershell/exchange/exchange-cmdlet-syntax).

## SYNTAX

```
Get-AppRetentionComplianceRule [[-Identity] <ComplianceRuleIdParameter>] [-Policy <PolicyIdParameter>] [<CommonParameters>]
```

## DESCRIPTION
To use this cmdlet in Security & Compliance Center PowerShell, you need to be assigned permissions. For more information, see [Permissions in the Microsoft 365 compliance center](https://docs.microsoft.com/microsoft-365/compliance/microsoft-365-compliance-center-permissions).

## EXAMPLES

### Example 1
```powershell
Get-AppRetentionComplianceRule | Format-Table Name,Policy
```

This example returns a summary list of all app retention compliance rules.

### Example 1
```powershell
Get-AppRetentionComplianceRule -Identity "Contoso Yammer"
```

This example returns detailed information for the app retention compliance rule named Contoso Yammer.

## PARAMETERS

### -Identity
The Identity parameter specifies the app retention compliance rule that you want to view. You can use any value that uniquely identifies the policy. For example:

- Name
- Distinguished name (DN)
- GUID

```yaml
Type: ComplianceRuleIdParameter
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Policy
The Policy parameter filters the app retention compliance rule results by the associated app retention compliance policy. You can use any value that uniquely identifies the policy. For example:

- Name
- Distinguished name (DN)
- GUID

```yaml
Type: PolicyIdParameter
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

###  

## OUTPUTS

###  

## NOTES

## RELATED LINKS
