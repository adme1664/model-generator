# AgreementBundleResourceApi

All URIs are relative to *http://localhost:9091*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**createAgreementBundle**](AgreementBundleResourceApi.md#createAgreementBundle) | **POST** /api/v1/agreements/bundle |  |
| [**purgeAgreementBundle**](AgreementBundleResourceApi.md#purgeAgreementBundle) | **DELETE** /api/v1/agreements/bundle |  |
| [**updateAgreementBundle**](AgreementBundleResourceApi.md#updateAgreementBundle) | **PUT** /api/v1/agreements/bundle |  |


<a id="createAgreementBundle"></a>
# **createAgreementBundle**
> createAgreementBundle(agreementBundleDTO)



### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.AgreementBundleResourceApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost:9091");

    AgreementBundleResourceApi apiInstance = new AgreementBundleResourceApi(defaultClient);
    AgreementBundleDTO agreementBundleDTO = new AgreementBundleDTO(); // AgreementBundleDTO | 
    try {
      apiInstance.createAgreementBundle(agreementBundleDTO);
    } catch (ApiException e) {
      System.err.println("Exception when calling AgreementBundleResourceApi#createAgreementBundle");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **agreementBundleDTO** | [**AgreementBundleDTO**](AgreementBundleDTO.md)|  | |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

<a id="purgeAgreementBundle"></a>
# **purgeAgreementBundle**
> purgeAgreementBundle(agreementBundleDTO)



### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.AgreementBundleResourceApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost:9091");

    AgreementBundleResourceApi apiInstance = new AgreementBundleResourceApi(defaultClient);
    AgreementBundleDTO agreementBundleDTO = new AgreementBundleDTO(); // AgreementBundleDTO | 
    try {
      apiInstance.purgeAgreementBundle(agreementBundleDTO);
    } catch (ApiException e) {
      System.err.println("Exception when calling AgreementBundleResourceApi#purgeAgreementBundle");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **agreementBundleDTO** | [**AgreementBundleDTO**](AgreementBundleDTO.md)|  | |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

<a id="updateAgreementBundle"></a>
# **updateAgreementBundle**
> updateAgreementBundle(agreementBundleDTO)



### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.AgreementBundleResourceApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("http://localhost:9091");

    AgreementBundleResourceApi apiInstance = new AgreementBundleResourceApi(defaultClient);
    AgreementBundleDTO agreementBundleDTO = new AgreementBundleDTO(); // AgreementBundleDTO | 
    try {
      apiInstance.updateAgreementBundle(agreementBundleDTO);
    } catch (ApiException e) {
      System.err.println("Exception when calling AgreementBundleResourceApi#updateAgreementBundle");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **agreementBundleDTO** | [**AgreementBundleDTO**](AgreementBundleDTO.md)|  | |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

