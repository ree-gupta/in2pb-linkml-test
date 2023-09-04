# Enum: DatasetTypes



URI: [DatasetTypes](DatasetTypes)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| raw | bids:raw | Raw data |
| derived | bids:derivative | Derived data |
| simulated | None | Simulated data |
| mixed | None | Mixed data |




## Slots

| Name | Description |
| ---  | --- |
| [datasetType](datasetType.md) | Type of the dataset |






## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/ree-gupta/in2pb/in2pb-dataset




## LinkML Source

<details>
```yaml
name: DatasetTypes
from_schema: https://w3id.org/ree-gupta/in2pb/in2pb-dataset
rank: 1000
permissible_values:
  raw:
    text: raw
    description: Raw data
    meaning: bids:raw
  derived:
    text: derived
    description: Derived data
    meaning: bids:derivative
  simulated:
    text: simulated
    description: Simulated data
  mixed:
    text: mixed
    description: Mixed data

```
</details>
