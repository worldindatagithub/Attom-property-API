# Property API of Attom and how to work with it #
The Attom property API allows developers to retrieve a list of properties in the United States based on specified criteria. This API is useful for anyone looking to gather information about properties within the US, such as real estate professionals or researchers. With this API, developers can easily access detailed information about properties, including their location, value, and ownership status.


[Property API](https://www.worldindata.com/api/Attom-property-api)

The Worldindata API marketplace is a platform that aggregates and index third party APIs in an effort to make data more accessible and user-friendly. By providing a central location for developers to discover and utilize APIs from various sources, the Worldindata API marketplace aims to streamline the process of finding and utilizing valuable data for a variety of purposes.


## Industry, client types, sector for the API ##

**Industry and Sectors**
- Real estate
- Hospitality
- Accommodation
- Property listing
- And more

**Client Types**
- Property listing platforms and websites
- Real estate analysts
- Accommodation services
- And more




## API Parameters, Objects and JSON output ##
The GET /property/id endpoint of the properties API allows users to retrieve detailed information about a specific property based on its unique identifier.


**Filter Parameters**
- Accept
- Geoid
- MinBeds
- MaxBeds
- Orderby


```
{
  "status": {
    "version": "1.0.0",
    "code": 0,
    "msg": "SuccessWithResult",
    "total": 10000,
    "page": 1,
    "pagesize": 10,
    "transactionID": "f51498437329aa40a736a76c696cdb43"
  },
  "property": [
    {
      "identifier": {
        "Id": 51167762,
        "fips": "08031",
        "apn": "02302-37-023-000",
        "attomId": 51167762
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51172099,
        "fips": "08031",
        "apn": "05265-13-006-000",
        "attomId": 51172099
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51172235,
        "fips": "08031",
        "apn": "02322-04-039-000",
        "attomId": 51172235
      },
      "vintage": {
        "lastModified": "2022-06-16",
        "pubDate": "2022-06-16"
      }
    },
    {
      "identifier": {
        "Id": 51174107,
        "fips": "08031",
        "apn": "06054-16-004-000",
        "attomId": 51174107
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51175426,
        "fips": "08031",
        "apn": "06064-08-323-323",
        "attomId": 51175426
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51176103,
        "fips": "08031",
        "apn": "05021-03-027-027",
        "attomId": 51176103
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51176219,
        "fips": "08031",
        "apn": "00182-14-010-000",
        "attomId": 51176219
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51176555,
        "fips": "08031",
        "apn": "05071-35-004-000",
        "attomId": 51176555
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51179623,
        "fips": "08031",
        "apn": "05321-12-024-000",
        "attomId": 51179623
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    },
    {
      "identifier": {
        "Id": 51180149,
        "fips": "08031",
        "apn": "05303-13-007-000",
        "attomId": 51180149
      },
      "vintage": {
        "lastModified": "2022-04-14",
        "pubDate": "2022-04-14"
      }
    }
  ]
}

```
**Objects**
- Property
- Identifier
- Id
- Fips
- Apn
- AttomId
- Vintage
- LastModified
- PubDate

## Software Development Kits ##
Attom's properties data is made available to developers through a variety of Software Development Kits (SDKs) in popular programming languages such as JAVA, PHP, JavaScript, Ruby, and Python. These SDKs make it easy for developers to integrate Attom's property data into their own projects and applications.


### Disclaimer of liability ###
Please note that Worldindata is not the owner of the data found on its platform, but rather a provider of tools that make it easier for developers to access and use data from various sources. While we are big fans of the property API and Attom, we are simply a conduit for connecting developers with data providers. Our goal is to make data more user-friendly and accessible to all.


[Worldindata](https://www.worldindata.com)
