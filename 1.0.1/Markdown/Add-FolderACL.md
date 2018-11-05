---
external help file: WC-ACLs-help.xml
Module Name: WC-ACLs
online version: 
schema: 2.0.0
---

# Add-FolderACL

## SYNOPSIS
{{Fill in the Synopsis}}

## SYNTAX

```
Add-FolderACL [-Path] <String> [-UserOrGroup] <String> [-InheritanceFlags] <String>
 [-PropagationFlags] <String> [-Rights] <String[]> [-AccessControlType] <String>
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### Example 1
```
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AccessControlType
These are the propagation flags to set.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Accepted values: Allow, Deny

Required: True
Position: 5
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InheritanceFlags
These are the inheritance flags to set.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Accepted values: None, Container, Object, Both

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Path
This is the path to set the ACL on.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PropagationFlags
These are the propagation flags to set.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Accepted values: None, NoPropagateInherit, InheritOnly

Required: True
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Rights
This is allow or deny

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: 

Required: True
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserOrGroup
This is the user or group to modify rights for.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

### None


## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS

