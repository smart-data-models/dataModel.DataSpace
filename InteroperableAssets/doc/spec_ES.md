<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entidad: InteroperableAssets  
============================<!-- /10-Header -->  
<!-- 15-License -->  
[Licencia abierta](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/InteroperableAssets/LICENSE.md)  
[documento generado automáticamente](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Descripción global: **Lista de los activos interoperables que un espacio de datos divulga a otro espacio de datos para permitir la federación o interconexión**.  
versión: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Lista de propiedades  

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>.  
- `address[object]`: La dirección postal  . Model: [https://schema.org/address](https://schema.org/address)	- `addressCountry[string]`: El país. Por ejemplo, España  . Model: [https://schema.org/addressCountry](https://schema.org/addressCountry)  
	- `addressLocality[string]`: La localidad en la que se encuentra la dirección postal, y que está en la región  . Model: [https://schema.org/addressLocality](https://schema.org/addressLocality)  
	- `addressRegion[string]`: La región en la que se encuentra la localidad, y que está en el país  . Model: [https://schema.org/addressRegion](https://schema.org/addressRegion)  
	- `district[string]`: Un distrito es un tipo de división administrativa que, en algunos países, gestiona el gobierno local    
	- `postOfficeBoxNumber[string]`: El número del apartado de correos para las direcciones de apartados postales. Por ejemplo, 03578  . Model: [https://schema.org/postOfficeBoxNumber](https://schema.org/postOfficeBoxNumber)  
	- `postalCode[string]`: El código postal. Por ejemplo, 24004  . Model: [https://schema.org/https://schema.org/postalCode](https://schema.org/https://schema.org/postalCode)  
	- `streetAddress[string]`: La dirección  . Model: [https://schema.org/streetAddress](https://schema.org/streetAddress)  
	- `streetNr[string]`: Número que identifica una propiedad específica en una vía pública    
- `alternateName[string]`: Un nombre alternativo para este artículo  - `areaServed[string]`: La zona geográfica en la que se presta un servicio o se ofrece un artículo  . Model: [https://schema.org/Text](https://schema.org/Text)- `dataExchangeProtocols[array]`: Lista de los protocolos de intercambio de datos habilitados por el espacio de datos que se utilizarán en la conexión con otros participantes.  - `dataModelSources[array]`: Lista de las fuentes de datos semánticos potencialmente utilizadas por los activos de datos en el espacio de datos  - `dataProvider[string]`: Una secuencia de caracteres que identifica al proveedor de la entidad de datos armonizada  - `dataSpaceIdentifier[string]`: Identificador único del espacio de datos. Enum:'AD4GD, AgDataValue, AgriDataSpace, AI4EOSC, AI4Europeana, AquaINFRA, B-Cubed, Blue-Cloud2026, CrackSense, CRAFT-OA, DataCellar, DataSpace4.0, DATES, DE-BIAS, deployEMDS, Divine, DS4SSCC, DS4SSCC-DEP, EDDIE, EOSC4Cancer, EOSC-ENTRUST, EOSCBeyond, EOSCFocus, EuroScienceGateway, Eureka3D, EVERSE, FAIR-EASE, FAIR-IMPACT, FAIRCORE4EOSC, FAIRiCUBE, GDI, GraspOS, GREAT, IntNET, OMEGA-X, OSCARS, OSTrails, PrepDSpace4Mobility, RAISE, RDATIGER, ScaleAgData, SciLake, Skills4EOSC, SM4RTENANCE, SIESTA, Synergies, TITAN, UNDERPIN, USAGE".  - `dateCreated[date-time]`: Fecha de creación de la entidad. Normalmente será asignada por la plataforma de almacenamiento  - `dateModified[date-time]`: Marca de tiempo de la última modificación de la entidad. Suele ser asignada por la plataforma de almacenamiento  - `description[string]`: Descripción de este artículo  - `id[*]`: Identificador único de la entidad  - `location[*]`: Referencia Geojson al elemento. Puede ser Point, LineString, Polygon, MultiPoint, MultiLineString o MultiPolygon.  - `name[string]`: El nombre de este artículo  - `owner[array]`: Una lista que contiene una secuencia de caracteres codificada en JSON que hace referencia a los identificadores únicos de los propietarios.  - `seeAlso[*]`: lista de uri que apuntan a recursos adicionales sobre el artículo  - `source[string]`: Secuencia de caracteres que indica la fuente original de los datos de la entidad en forma de URL. Se recomienda que sea el nombre de dominio completo del proveedor de origen o la URL del objeto de origen.  - `type[string]`: Debe ser igual a InteroperableAssets.  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Propiedades requeridas  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
Creado para el Centro de Apoyo de Data Spaces  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## Descripción de las propiedades del modelo de datos  
Ordenados alfabéticamente (pulse para más detalles)  
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
## Ejemplo de carga útil  
#### InteroperableAssets NGSI-v2 key-values Ejemplo  
He aquí un ejemplo de un InteroperableAssets en formato JSON-LD como key-values. Esto es compatible con NGSI-v2 cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
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
#### InteroperableAssets NGSI-v2 normalizado Ejemplo  
He aquí un ejemplo de InteroperableAssets en formato JSON-LD normalizado. Esto es compatible con NGSI-v2 cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
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
#### InteroperableAssets NGSI-LD key-values Ejemplo  
He aquí un ejemplo de un InteroperableAssets en formato JSON-LD como key-values. Esto es compatible con NGSI-LD cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
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
#### InteroperableAssets NGSI-LD normalizado Ejemplo  
He aquí un ejemplo de InteroperableAssets en formato JSON-LD normalizado. Esto es compatible con NGSI-LD cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
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
Consulte [FAQ 10](https://smartdatamodels.org/index.php/faqs/) para obtener una respuesta sobre cómo tratar las unidades de magnitud.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
