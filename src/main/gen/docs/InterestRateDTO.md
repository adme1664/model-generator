

# InterestRateDTO


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**interestRateId** | **UUID** |  |  [optional] |
|**agreementId** | **UUID** |  |  [optional] |
|**interestRateType** | [**InterestRateTypeEnum**](#InterestRateTypeEnum) |  |  [optional] |
|**interestRate** | **BigDecimal** |  |  [optional] |
|**baseRate** | **BigDecimal** |  |  [optional] |
|**spreadRate** | **BigDecimal** |  |  [optional] |
|**effectiveDate** | **LocalDate** |  |  [optional] |
|**effectiveRate** | **BigDecimal** |  |  [optional] |



## Enum: InterestRateTypeEnum

| Name | Value |
|---- | -----|
| FIXED | &quot;FIXED&quot; |
| VARIABLE | &quot;VARIABLE&quot; |



