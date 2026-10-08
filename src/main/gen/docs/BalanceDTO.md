

# BalanceDTO


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**balanceId** | **UUID** |  |  [optional] |
|**agreementId** | **UUID** |  |  [optional] |
|**balanceType** | [**BalanceTypeEnum**](#BalanceTypeEnum) |  |  [optional] |
|**creditAmount** | **BigDecimal** |  |  [optional] |
|**debitAmount** | **BigDecimal** |  |  [optional] |
|**netBalance** | **BigDecimal** |  |  [optional] |
|**balanceDate** | **LocalDate** |  |  [optional] |



## Enum: BalanceTypeEnum

| Name | Value |
|---- | -----|
| DAILY | &quot;ACCRUED_INT_DAILY&quot; |
| CUMULATED | &quot;ACCRUED_INT_CUMULATED&quot; |



