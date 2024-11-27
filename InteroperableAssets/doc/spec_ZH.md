<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
实体：互操作资产  
========<!-- /10-Header -->  
<!-- 15-License -->  
[开放许可](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/InteroperableAssets/LICENSE.md)  
[文件自动生成](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
全局描述：数据空间为实现联盟或互联而向其他数据空间披露的可互操作资产的**清单**  
版本： 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 属性列表  

<sup><sub>[*] 如果属性中没有类型，是因为它可能有多个类型或不同的格式/模式</sub></sup>。  
- `address[object]`: 邮寄地址  . Model: [https://schema.org/address](https://schema.org/address)	- `addressCountry[string]`: 国家。例如，西班牙  . Model: [https://schema.org/addressCountry](https://schema.org/addressCountry)  
	- `addressLocality[string]`: 街道地址所在的地点，以及该地点所在的区域  . Model: [https://schema.org/addressLocality](https://schema.org/addressLocality)  
	- `addressRegion[string]`: 地点所在的地区，以及该地区位于哪个国家  . Model: [https://schema.org/addressRegion](https://schema.org/addressRegion)  
	- `district[string]`: 地区是一种行政区划，在一些国家由地方政府管理    
	- `postOfficeBoxNumber[string]`: 用于邮政信箱地址的邮政信箱号码。例如：03578  . Model: [https://schema.org/postOfficeBoxNumber](https://schema.org/postOfficeBoxNumber)  
	- `postalCode[string]`: 邮政编码。例如：24004  . Model: [https://schema.org/https://schema.org/postalCode](https://schema.org/https://schema.org/postalCode)  
	- `streetAddress[string]`: 街道地址  . Model: [https://schema.org/streetAddress](https://schema.org/streetAddress)  
	- `streetNr[string]`: 标识公共街道上特定房产的编号    
- `alternateName[string]`: 该项目的替代名称  - `areaServed[string]`: 提供服务或提供物品的地理区域  . Model: [https://schema.org/Text](https://schema.org/Text)- `dataExchangeProtocols[array]`: 数据空间与其他参与方连接时可使用的数据交换协议列表  - `dataModelSources[array]`: 数据空间中的数据资产可能使用的语义数据源列表  - `dataProvider[string]`: 标识统一数据实体提供者的字符序列  - `dataSpaceIdentifier[string]`: 数据空间唯一标识符。Enum:'AD4GD, AgDataValue, AgriDataSpace, AI4EOSC, AI4Europeana, AquaINFRA, B-Cubed, Blue-Cloud2026, CrackSense, CRAFT-OA, DataCellar, DataSpace4.0、DATES、DE-BIAS、deployEMDS、Divine、DS4SSCC、DS4SSCC-DEP、EDDIE、EOSC4Cancer、EOSC-ENTRUST、EOSCBeyond、EOSCFocus、EuroScienceGateway、Eureka3D、EVERSE、FAIR-EASE、FAIR-IMPACT、FAIRCORE4EOSC、FAIRiCUBE, GDI, GraspOS, GREAT, IntNET, OMEGA-X, OSCARS, OSTrails, PrepDSpace4Mobility, RAISE, RDATIGER, ScaleAgData, SciLake, Skills4EOSC, SM4RTENANCE, SIESTA, Synergies, TITAN, UNDERPIN, USAGE' 等。  - `dateCreated[date-time]`: 实体创建时间戳。通常由存储平台分配  - `dateModified[date-time]`: 实体最后一次修改的时间戳。通常由存储平台分配  - `description[string]`: 项目描述  - `id[*]`: 实体的唯一标识符  - `location[*]`: 项目的 Geojson 引用。它可以是点、线条字符串、多边形、多点、多线条字符串或多多边形  - `name[string]`: 该项目的名称  - `owner[array]`: 包含一个 JSON 编码字符序列的列表，其中引用了所有者的唯一 Ids  - `seeAlso[*]`: 指向有关该项目的其他资源的 uri 列表  - `source[string]`: 以 URL 形式给出实体数据原始来源的字符串。建议使用源提供者的完全合格域名或源对象的 URL  - `type[string]`: 它必须等于 InteroperableAssets。  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
所需属性  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
为数据空间支持中心创建  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## 属性的数据模型描述  
按字母顺序排列（点击查看详情）  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
InteroperableAssets:    
  description: List of the interoperable assets that a data space disclose to other data space to enable the federation or interconnection    
  properties:    
    address:    
      description: The mailing address    
      properties:    
        addressCountry:    
          description: 'The country. For example, Spain'    
          type: string    
          x-ngsi:    
            model: https://schema.org/addressCountry    
            type: Property    
        addressLocality:    
          description: 'The locality in which the street address is, and which is in the region'    
          type: string    
          x-ngsi:    
            model: https://schema.org/addressLocality    
            type: Property    
        addressRegion:    
          description: 'The region in which the locality is, and which is in the country'    
          type: string    
          x-ngsi:    
            model: https://schema.org/addressRegion    
            type: Property    
        district:    
          description: 'A district is a type of administrative division that, in some countries, is managed by the local government'    
          type: string    
          x-ngsi:    
            type: Property    
        postOfficeBoxNumber:    
          description: 'The post office box number for PO box addresses. For example, 03578'    
          type: string    
          x-ngsi:    
            model: https://schema.org/postOfficeBoxNumber    
            type: Property    
        postalCode:    
          description: 'The postal code. For example, 24004'    
          type: string    
          x-ngsi:    
            model: https://schema.org/https://schema.org/postalCode    
            type: Property    
        streetAddress:    
          description: The street address    
          type: string    
          x-ngsi:    
            model: https://schema.org/streetAddress    
            type: Property    
        streetNr:    
          description: Number identifying a specific property on a public street    
          type: string    
          x-ngsi:    
            type: Property    
      type: object    
      x-ngsi:    
        model: https://schema.org/address    
        type: Property    
    alternateName:    
      description: An alternative name for this item    
      type: string    
      x-ngsi:    
        type: Property    
    areaServed:    
      description: The geographic area where a service or offered item is provided    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    dataExchangeProtocols:    
      description: List of the data exchange protocols enabled by the data space to be used in the connection with other participants    
      items:    
        description: Description of the individual protocol    
        properties:    
          description:    
            description: Description of the protocol for data exchange    
            type: string    
            x-ngsi:    
              type: Property    
          documentation:    
            description: URIs where more information about the data exchange protocol can be found    
            items:    
              description: Every resource with additional information about the data exchange protocol    
              format: uri    
              type: string    
              x-ngsi:    
                type: Property    
            type: array    
            x-ngsi:    
              type: Property    
          identifier:    
            description: 'Unique identifier of the protocol, it includes the version number. It should nt contain spaces. Enum:''NGSI-LD.1.6, LDES, NGSI-v2.1.0'''    
            enum:    
              - NGSI-LD.1.6    
              - LDES    
              - NGSI-v2.1.0    
            type: string    
            x-ngsi:    
              type: Property    
          name:    
            description: Name of the protocol for data exchange    
            type: string    
            x-ngsi:    
              type: Property    
          version:    
            description: Version of the protocol for data exchange    
            type: string    
            x-ngsi:    
              type: Property    
        type: object    
        x-ngsi:    
          type: Property    
      type: array    
      x-ngsi:    
        type: Property    
    dataModelSources:    
      description: List of the semantic data sources potentially used by the data assets in the data space    
      items:    
        description: Every semantic data sources potentially used by the data assets in the data space    
        properties:    
          description:    
            description: Description of the semantic data source    
            type: string    
            x-ngsi:    
              type: Property    
          documentation:    
            description: URIs where can be found more information about the semantic data source    
            items:    
              description: Every resource with additional information about the semantic data exchange source    
              format: uri    
              type: string    
              x-ngsi:    
                type: Property    
            type: array    
            x-ngsi:    
              type: Property    
          identifier:    
            description: 'Unique identifier of the semantic data source, it includes the version number. Enum:''Smart-Data-Models, SAREF, S4BLDG'''    
            enum:    
              - Smart-Data-Models    
              - SAREF    
              - S4BLDG    
            type: string    
            x-ngsi:    
              type: Property    
          internalIdentifier:    
            description: Internal identifier inside the semantic data source. In example it could be the class name or a specific data model if needed    
            type: string    
            x-ngsi:    
              type: Property    
          name:    
            description: Name of the semantic data source    
            type: string    
            x-ngsi:    
              type: Property    
          version:    
            description: Version of the semantic data source    
            type: string    
            x-ngsi:    
              type: Property    
        type: object    
        x-ngsi:    
          type: Property    
      type: array    
      x-ngsi:    
        type: Property    
    dataProvider:    
      description: A sequence of characters identifying the provider of the harmonised data entity    
      type: string    
      x-ngsi:    
        type: Property    
    dataSpaceIdentifier:    
      description: 'Data space unique identifier. Enum:''AD4GD, AgDataValue, AgriDataSpace, AI4EOSC, AI4Europeana, AquaINFRA, B-Cubed, Blue-Cloud2026, CrackSense, CRAFT-OA, DataCellar, DataSpace4.0, DATES, DE-BIAS, deployEMDS, Divine, DS4SSCC, DS4SSCC-DEP, EDDIE, EOSC4Cancer, EOSC-ENTRUST, EOSCBeyond, EOSCFocus, EuroScienceGateway, Eureka3D, EVERSE, FAIR-EASE, FAIR-IMPACT, FAIRCORE4EOSC, FAIRiCUBE, GDI, GraspOS, GREAT, IntNET, OMEGA-X, OSCARS, OSTrails, PrepDSpace4Mobility, RAISE, RDATIGER, ScaleAgData, SciLake, Skills4EOSC, SM4RTENANCE, SIESTA, Synergies, TITAN, UNDERPIN, USAGE'''    
      enum:    
        - AD4GD    
        - AgDataValue    
        - AgriDataSpace    
        - AI4EOSC    
        - AI4Europeana    
        - AquaINFRA    
        - B-Cubed    
        - Blue-Cloud2026    
        - CrackSense    
        - CRAFT-OA    
        - DataCellar    
        - DataSpace4.0    
        - DATES    
        - DE-BIAS    
        - deployEMDS    
        - Divine    
        - DS4SSCC    
        - DS4SSCC-DEP    
        - EDDI    
        - EOSC4Cancer    
        - EOSC-ENTRUST    
        - EOSCBeyond    
        - EOSCFocus    
        - EuroScienceGateway    
        - Eureka3D    
        - EVERSE    
        - FAIR-EASE    
        - FAIR-IMPACT    
        - FAIRCORE4EOSC    
        - FAIRiCUBE    
        - GDI    
        - GraspOS    
        - GREAT    
        - IntNET    
        - OMEGA-X    
        - OSCARS    
        - OSTrails    
        - PrepDSpace4Mobility    
        - RAISE    
        - RDATIGER    
        - ScaleAgData    
        - SciLake    
        - Skills4EOSC    
        - SM4RTENANCE    
        - SIESTA    
        - Synergies    
        - TITAN    
        - UNDERPIN    
        - USAGE    
      type: string    
      x-ngsi:    
        type: Property    
    dateCreated:    
      description: Entity creation timestamp. This will usually be allocated by the storage platform    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    dateModified:    
      description: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    description:    
      description: A description of this item    
      type: string    
      x-ngsi:    
        type: Property    
    id:    
      anyOf:    
        - description: Identifier format of any NGSI entity    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
          x-ngsi:    
            type: Property    
        - description: Identifier format of any NGSI entity    
          format: uri    
          type: string    
          x-ngsi:    
            type: Property    
      description: Unique identifier of the entity    
      x-ngsi:    
        type: Relationship    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf:    
        - description: Geojson reference to the item. Point    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                type: number    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - Point    
              type: string    
          required:    
            - type    
            - coordinates    
          title: GeoJSON Point    
          type: object    
          x-ngsi:    
            type: GeoProperty    
        - description: Geojson reference to the item. LineString    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - LineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: GeoJSON LineString    
          type: object    
          x-ngsi:    
            type: GeoProperty    
        - description: Geojson reference to the item. Polygon    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 4    
                type: array    
              type: array    
            type:    
              enum:    
                - Polygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: GeoJSON Polygon    
          type: object    
          x-ngsi:    
            type: GeoProperty    
        - description: Geojson reference to the item. MultiPoint    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPoint    
              type: string    
          required:    
            - type    
            - coordinates    
          title: GeoJSON MultiPoint    
          type: object    
          x-ngsi:    
            type: GeoProperty    
        - description: Geojson reference to the item. MultiLineString    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiLineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: GeoJSON MultiLineString    
          type: object    
          x-ngsi:    
            type: GeoProperty    
        - description: Geojson reference to the item. MultiLineString    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    items:    
                      type: number    
                    minItems: 2    
                    type: array    
                  minItems: 4    
                  type: array    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPolygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: GeoJSON MultiPolygon    
          type: object    
          x-ngsi:    
            type: GeoProperty    
      x-ngsi:    
        type: GeoProperty    
    name:    
      description: The name of this item    
      type: string    
      x-ngsi:    
        type: Property    
    owner:    
      description: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)    
      items:    
        anyOf:    
          - description: Identifier format of any NGSI entity    
            maxLength: 256    
            minLength: 1    
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
            type: string    
            x-ngsi:    
              type: Property    
          - description: Identifier format of any NGSI entity    
            format: uri    
            type: string    
            x-ngsi:    
              type: Property    
        description: Unique identifier of the entity    
        x-ngsi:    
          type: Relationship    
      type: array    
      x-ngsi:    
        type: Property    
    seeAlso:    
      description: list of uri pointing to additional resources about the item    
      oneOf:    
        - items:    
            format: uri    
            type: string    
          minItems: 1    
          type: array    
        - format: uri    
          type: string    
      x-ngsi:    
        type: Property    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object'    
      type: string    
      x-ngsi:    
        type: Property    
    type:    
      description: It must be equal to InteroperableAssets.    
      enum:    
        - InteroperableAssets    
      type: string    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2024 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.DataSpace/blob/master/InteroperableAssets/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.DataSpace/InteroperableAssets/schema.json    
  x-model-tags: 'Data Space, '    
  x-version: 0.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## 有效载荷示例  
#### 互操作资产 NGSI-v2 键值示例  
下面是一个以 JSON-LD 格式作为键值的 InteroperableAssets 示例。当使用 `options=keyValues` 时，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:InteroperableAssets:id:WGEQ:22085426",  
  "type": "InteroperableAssets",  
  "dateCreated": "2024-04-22T01:37:25Z",  
  "dateModified": "2024-04-24T17:29:14Z",  
  "source": "Sm4rtenance Project",  
  "name": "",  
  "alternateName": "",  
  "description": "",  
  "dataProvider": "",  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      40.41,  
      3.7033  
    ]  
  },  
  "address": {  
    "streetAddress": "",  
    "addressLocality": "Madrid",  
    "addressRegion": "Madrid",  
    "addressCountry": "Spain",  
    "postalCode": "28050",  
    "postOfficeBoxNumber": "",  
    "streetNr": "",  
    "district": ""  
  },  
  "areaServed": "",  
  "dataSpaceIdentifier": "SM4RTENANCE",  
  "dataExchangeProtocols": [  
    {  
      "name": "Link Data event stream",  
      "description": "A Linked Data Event Stream (LDES) is a technical standard that applies linked data principles to data streams, allowing for the exchange of data between silos in a sustainable and cost-effective manner. It is defined as a collection of immutable objects, called LDES members, described using the Resource Description Framework (RDF). LDES enables data publishers to publish their datasets as append-only collections, allowing consumers to replicate the full dataset and keep it synchronized, while also facilitating real-time updates and improving data usability and findability",  
      "identifier": "LDES",  
      "version": "1.0",  
      "documentation": [  
        "https://semiceu.github.io/LinkedDataEventStreams/"  
      ]  
    },  
    {  
      "name": "NGSI LD",  
      "description": "NGSI-LD is an information model and API for publishing, querying, and subscribing to context information, standardized by ETSI to facilitate open exchange and sharing of structured data across various domains. It represents context information as entities with properties and relationships, using a property graph model with semantics based on RDF and the semantic web framework. NGSI-LD builds upon previous context management frameworks and can be serialized using JSON-LD, making it compatible with linked data principles and allowing for unique IRI identifiers for entities and relationships",  
      "identifier": "NGSI-LD.1.6",  
      "version": "1.6",  
      "documentation": [  
        "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.06.01_60/gs_CIM009v010601p.pdf"  
      ]  
    }  
  ],  
  "dataModelSources": [  
    {  
      "name": "Smart Data Models",  
      "description": "The Smart Data Models initiative is a collaborative effort led by FIWARE Foundation, TM Forum, IUDX, and OASC to create and promote standardized, interoperable data models across multiple sectors. It aims to support a digital marketplace of smart solutions by developing common, royalty-free data models that are publicly available. The initiative focuses on using JSON Schema as a core component, enabling exports in various formats to enhance compatibility with semantic and linked data approaches. By providing these open-licensed, standardized data models, the initiative seeks to combat data silos, improve data sharing, and facilitate application portability across different platforms and sectors, ultimately fostering innovation and interoperability in smart solutions.",  
      "identifier": "Smart-Data-Models",  
      "internalIdentifier": "WeatherObserved",  
      "version": "0.3",  
      "documentation": [  
        "https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/doc/spec.md"  
      ]  
    }  
  ]  
}  
```  
</details>  
#### 互操作资产 NGSI-v2 标准化示例  
下面是一个规范化 JSON-LD 格式的互操作资产（InteroperableAssets）示例。当不使用选项时，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:InteroperableAssets:id:WGEQ:22085426",  
  "type": "InteroperableAssets",  
  "dateCreated": {  
    "type": "DateTime",  
    "value": "2024-04-22T01:37:25Z"  
  },  
  "dateModified": {  
    "type": "DateTime",  
    "value": "2024-04-24T17:29:14Z"  
  },  
  "source": {  
    "type": "Property",  
    "value": "Sm4rtenance Project"  
  },  
  "name": {  
    "type": "Text",  
    "value": ""  
  },  
  "alternateName": {  
    "type": "Text",  
    "value": ""  
  },  
  "description": {  
    "type": "Text",  
    "value": ""  
  },  
  "dataProvider": {  
    "type": "Text",  
    "value": ""  
  },  
  "location": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        40.41,  
        3.7033  
      ]  
    }  
  },  
  "address": {  
    "type": "StructuredValue",  
    "value": {  
      "streetAddress": "",  
      "addressLocality": "Madrid",  
      "addressRegion": "Madrid",  
      "addressCountry": "Spain",  
      "postalCode": "28050",  
      "postOfficeBoxNumber": "",  
      "streetNr": "",  
      "district": ""  
    }  
  },  
  "areaServed": {  
    "type": "Text",  
    "value": ""  
  },  
  "dataSpaceIdentifier": {  
    "type": "Text",  
    "value": "SM4RTENANCE"  
  },  
  "dataExchangeProtocols": {  
    "type": "StructuredValue",  
    "value": [  
      {  
        "name": "Link Data event stream",  
        "description": "A Linked Data Event Stream (LDES) is a technical standard that applies linked data principles to data streams, allowing for the exchange of data between silos in a sustainable and cost-effective manner. It is defined as a collection of immutable objects, called LDES members, described using the Resource Description Framework (RDF). LDES enables data publishers to publish their datasets as append-only collections, allowing consumers to replicate the full dataset and keep it synchronized, while also facilitating real-time updates and improving data usability and findability",  
        "identifier": "LDES",  
        "version": "1.0",  
        "documentation": [  
          "https://semiceu.github.io/LinkedDataEventStreams/"  
        ]  
      },  
      {  
        "name": "NGSI LD",  
        "description": "NGSI-LD is an information model and API for publishing, querying, and subscribing to context information, standardized by ETSI to facilitate open exchange and sharing of structured data across various domains. It represents context information as entities with properties and relationships, using a property graph model with semantics based on RDF and the semantic web framework. NGSI-LD builds upon previous context management frameworks and can be serialized using JSON-LD, making it compatible with linked data principles and allowing for unique IRI identifiers for entities and relationships",  
        "identifier": "NGSI-LD.1.6",  
        "version": "1.6",  
        "documentation": [  
          "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.06.01_60/gs_CIM009v010601p.pdf"  
        ]  
      }  
    ]  
  },  
  "dataModelSources": {  
    "type": "StructuredValue",  
    "value": [  
      {  
        "name": "Smart Data Models",  
        "description": "The Smart Data Models initiative is a collaborative effort led by FIWARE Foundation, TM Forum, IUDX, and OASC to create and promote standardized, interoperable data models across multiple sectors. It aims to support a digital marketplace of smart solutions by developing common, royalty-free data models that are publicly available. The initiative focuses on using JSON Schema as a core component, enabling exports in various formats to enhance compatibility with semantic and linked data approaches. By providing these open-licensed, standardized data models, the initiative seeks to combat data silos, improve data sharing, and facilitate application portability across different platforms and sectors, ultimately fostering innovation and interoperability in smart solutions.",  
        "identifier": "Smart-Data-Models",  
        "internalIdentifier": "WeatherObserved",  
        "version": "0.3",  
        "documentation": [  
          "https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/doc/spec.md"  
        ]  
      }  
    ]  
  }  
}  
```  
</details>  
#### 互操作资产 NGSI-LD 键值示例  
下面是一个以 JSON-LD 格式作为键值的 InteroperableAssets 示例。当使用 `options=keyValues` 时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:InteroperableAssets:id:WGEQ:22085426",  
  "type": "InteroperableAssets",  
  "dateCreated": "2024-04-22T01:37:25Z",  
  "dateModified": "2024-04-24T17:29:14Z",  
  "source": "Sm4rtenance Project",  
  "name": "",  
  "alternateName": "",  
  "description": "",  
  "dataProvider": "",  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      40.41,  
      3.7033  
    ]  
  },  
  "address": {  
    "streetAddress": "",  
    "addressLocality": "Madrid",  
    "addressRegion": "Madrid",  
    "addressCountry": "Spain",  
    "postalCode": "28050",  
    "postOfficeBoxNumber": "",  
    "streetNr": "",  
    "district": ""  
  },  
  "areaServed": "",  
  "dataSpaceIdentifier": "SM4RTENANCE",  
  "dataExchangeProtocols": [  
    {  
      "name": "Link Data event stream",  
      "description": "A Linked Data Event Stream (LDES) is a technical standard that applies linked data principles to data streams, allowing for the exchange of data between silos in a sustainable and cost-effective manner. It is defined as a collection of immutable objects, called LDES members, described using the Resource Description Framework (RDF). LDES enables data publishers to publish their datasets as append-only collections, allowing consumers to replicate the full dataset and keep it synchronized, while also facilitating real-time updates and improving data usability and findability",  
      "identifier": "LDES",  
      "version": "1.0",  
      "documentation": [  
        "https://semiceu.github.io/LinkedDataEventStreams/"  
      ]  
    },  
    {  
      "name": "NGSI LD",  
      "description": "NGSI-LD is an information model and API for publishing, querying, and subscribing to context information, standardized by ETSI to facilitate open exchange and sharing of structured data across various domains. It represents context information as entities with properties and relationships, using a property graph model with semantics based on RDF and the semantic web framework. NGSI-LD builds upon previous context management frameworks and can be serialized using JSON-LD, making it compatible with linked data principles and allowing for unique IRI identifiers for entities and relationships",  
      "identifier": "NGSI-LD.1.6",  
      "version": "1.6",  
      "documentation": [  
        "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.06.01_60/gs_CIM009v010601p.pdf"  
      ]  
    }  
  ],  
  "dataModelSources": [  
    {  
      "name": "Smart Data Models",  
      "description": "The Smart Data Models initiative is a collaborative effort led by FIWARE Foundation, TM Forum, IUDX, and OASC to create and promote standardized, interoperable data models across multiple sectors. It aims to support a digital marketplace of smart solutions by developing common, royalty-free data models that are publicly available. The initiative focuses on using JSON Schema as a core component, enabling exports in various formats to enhance compatibility with semantic and linked data approaches. By providing these open-licensed, standardized data models, the initiative seeks to combat data silos, improve data sharing, and facilitate application portability across different platforms and sectors, ultimately fostering innovation and interoperability in smart solutions.",  
      "identifier": "Smart-Data-Models",  
      "internalIdentifier": "WeatherObserved",  
      "version": "0.3",  
      "documentation": [  
        "https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/doc/spec.md"  
      ]  
    }  
  ],  
  "@context": [  
    "https://smart-data-models.github.io/dataModel.DataSpace/context.jsonld"  
  ]  
}  
```  
</details>  
#### 互操作资产 NGSI-LD 标准化示例  
下面是一个规范化 JSON-LD 格式的互操作资产（InteroperableAssets）示例。当不使用选项时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:InteroperableAssets:id:WGEQ:22085426",  
  "type": "InteroperableAssets",  
  "dateCreated": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2024-04-22T01:37:25Z"  
    }  
  },  
  "dateModified": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2024-04-24T17:29:14Z"  
    }  
  },  
  "source": {  
    "type": "Property",  
    "value": "Sm4rtenance Project"  
  },  
  "name": {  
    "type": "Property",  
    "value": ""  
  },  
  "alternateName": {  
    "type": "Property",  
    "value": ""  
  },  
  "description": {  
    "type": "Property",  
    "value": ""  
  },  
  "dataProvider": {  
    "type": "Property",  
    "value": ""  
  },  
  "location": {  
    "type": "GeoProperty",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        40.41,  
        3.7033  
      ]  
    }  
  },  
  "address": {  
    "type": "Property",  
    "value": {  
      "streetAddress": "",  
      "addressLocality": "Madrid",  
      "addressRegion": "Madrid",  
      "addressCountry": "Spain",  
      "postalCode": "28050",  
      "postOfficeBoxNumber": "",  
      "streetNr": "",  
      "district": ""  
    }  
  },  
  "areaServed": {  
    "type": "Property",  
    "value": ""  
  },  
  "dataSpaceIdentifier": {  
    "type": "Property",  
    "value": "SM4RTENANCE"  
  },  
  "dataExchangeProtocols": {  
    "type": "Property",  
    "value": [  
      {  
        "name": "Link Data event stream",  
        "description": "A Linked Data Event Stream (LDES) is a technical standard that applies linked data principles to data streams, allowing for the exchange of data between silos in a sustainable and cost-effective manner. It is defined as a collection of immutable objects, called LDES members, described using the Resource Description Framework (RDF). LDES enables data publishers to publish their datasets as append-only collections, allowing consumers to replicate the full dataset and keep it synchronized, while also facilitating real-time updates and improving data usability and findability",  
        "identifier": "LDES",  
        "version": "1.0",  
        "documentation": [  
          "https://semiceu.github.io/LinkedDataEventStreams/"  
        ]  
      },  
      {  
        "name": "NGSI LD",  
        "description": "NGSI-LD is an information model and API for publishing, querying, and subscribing to context information, standardized by ETSI to facilitate open exchange and sharing of structured data across various domains. It represents context information as entities with properties and relationships, using a property graph model with semantics based on RDF and the semantic web framework. NGSI-LD builds upon previous context management frameworks and can be serialized using JSON-LD, making it compatible with linked data principles and allowing for unique IRI identifiers for entities and relationships",  
        "identifier": "NGSI-LD.1.6",  
        "version": "1.6",  
        "documentation": [  
          "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.06.01_60/gs_CIM009v010601p.pdf"  
        ]  
      }  
    ]  
  },  
  "dataModelSources": {  
    "type": "Property",  
    "value": [  
      {  
        "name": "Smart Data Models",  
        "description": "The Smart Data Models initiative is a collaborative effort led by FIWARE Foundation, TM Forum, IUDX, and OASC to create and promote standardized, interoperable data models across multiple sectors. It aims to support a digital marketplace of smart solutions by developing common, royalty-free data models that are publicly available. The initiative focuses on using JSON Schema as a core component, enabling exports in various formats to enhance compatibility with semantic and linked data approaches. By providing these open-licensed, standardized data models, the initiative seeks to combat data silos, improve data sharing, and facilitate application portability across different platforms and sectors, ultimately fostering innovation and interoperability in smart solutions.",  
        "identifier": "Smart-Data-Models",  
        "internalIdentifier": "WeatherObserved",  
        "version": "0.3",  
        "documentation": [  
          "https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/doc/spec.md"  
        ]  
      }  
    ]  
  },  
  "@context": [  
    "https://smart-data-models.github.io/dataModel.DataSpace/context.jsonld"  
  ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
请参阅 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)，获取如何处理幅度单位的答案。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
