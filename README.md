# OCDS Extension for Taiwan

Open Contracting Data Standard ([OCDS](https://standard.open-contracting.org/latest/en/))
defines a common data model for all stages of a contracting process.
OCDS also supports adding extensions to cover fields that are not common or
predefined in the existing schema.

This OCDS extension captures some information that are tailored to Taiwan's
procurement process.

## Examples

```
{
  "tender": {
    "additionalProperties": {
      "involveInfoSecurityOrNationalSecurity": true,
    }
  }
}
```
