

# AgreementDTO


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**agreementNo** | **String** |  |  [optional] |
|**creditFacilityNo** | **String** |  |  [optional] |
|**agreementType** | **String** |  |  [optional] |
|**productCode** | **String** |  |  [optional] |
|**statusCodeSource** | **String** |  |  [optional] |
|**statusCode** | [**StatusCodeEnum**](#StatusCodeEnum) |  |  [optional] |
|**unbankLetterIssuerIndicator** | **Boolean** |  |  [optional] |
|**originalAmount** | **BigDecimal** |  |  [optional] |
|**effectiveDate** | **LocalDate** |  |  [optional] |
|**expiryDate** | **LocalDate** |  |  [optional] |
|**maturityDate** | **LocalDate** |  |  [optional] |
|**currency** | **String** |  |  [optional] |
|**sourceSystem** | **String** |  |  [optional] |
|**deletedIndicator** | **Boolean** |  |  [optional] |



## Enum: StatusCodeEnum

| Name | Value |
|---- | -----|
| EN_ATTENTE | &quot;EN_ATTENTE&quot; |
| OUVERT | &quot;OUVERT&quot; |
| SUSPENDU | &quot;SUSPENDU&quot; |
| FERME | &quot;FERME&quot; |



