# OCDS Extension for Taiwan

Open Contracting Data Standard ([OCDS](https://standard.open-contracting.org/latest/en/))
defines a common data model for all stages of a contracting process.
OCDS also supports adding extensions to cover fields that are not common or
predefined in the existing schema.

This OCDS extension captures some information that are tailored to Taiwan's
procurement process.

## Examples

- 本採購是否屬「具敏感性或國安(含資安)疑慮之業務範疇」採購"
```
{
  "tender": {
    "additionalProperties": {
      "involveInfoSecurityOrNationalSecurity": true,
    }
  }
}
```
- 是否含特別預算
```
{
  "tender": {
    "additionalProperties": {
      "withSpecialBudget": true,
    }
  }
}
```
