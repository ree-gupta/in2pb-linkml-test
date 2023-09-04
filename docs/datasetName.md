# Slot: datasetName


_"The full name of the dataset."_



URI: [in2pb_dataset:datasetName](https://w3id.org/ree-gupta/in2pb/in2pb-datasetdatasetName)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[In2PrimateBrainsDataset](In2PrimateBrainsDataset.md) | "A complete dataset generated by an In2PrimateBrains project |  no  |







## Properties

* Range: [String](String.md)

* Required: True





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/ree-gupta/in2pb/in2pb-dataset




## LinkML Source

<details>
```yaml
name: datasetName
description: '"The full name of the dataset."'
from_schema: https://w3id.org/ree-gupta/in2pb/in2pb-dataset
close_mappings:
- openminds:fullName
- bids:Name(metadata)
broad_mappings:
- schema:name
rank: 1000
alias: datasetName
domain_of:
- In2PrimateBrainsDataset
range: string
required: true

```
</details>