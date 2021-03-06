# ConvertTo-LTSecurity
## SYNOPSIS
This function encodes a value compatible with LT operations.
## SYNTAX
```powershell
ConvertTo-LTSecurity [-InputString] <String> [[-Key] <Object>] [<CommonParameters>]
```
## DESCRIPTION
This function encodes the provided string using the specified or default key.
## PARAMETERS
### -InputString &lt;String&gt;
This is the string to be encoded.
```
Required                    true
Position                    1
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Key &lt;Object&gt;
This is the key used for encoding. If not provided, a default value will be used.
```
Required                    false
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## NOTES
Version:        1.1

Author:         Darren White

Creation Date:  1/25/2018

Purpose/Change: Initial function development 
