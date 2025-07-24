<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
엔티티: 어휘 서비스  
===========<!-- /10-Header -->  
<!-- 15-License -->  
[오픈 라이선스](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/VocabularyService/LICENSE.md)  
[문서 자동 생성](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
글로벌 설명: **어휘 서비스 도구의 데이터 모델입니다. 이 서비스는 어휘, 온톨로지 및 스키마와 같은 데이터 모델을 관리하고 호스팅합니다. 기본 ToolInformation 모델을 확장합니다.**  
버전: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 속성 목록  

<sup><sub>[*] 속성에 유형이 없는 것은 여러 유형 또는 다른 형식/패턴을 가질 수 있기 때문입니다</sub></sup>.  
- `additionalBuildingBlock[*]`: 이 도구에서 제공하는 추가 빌딩 블록 기능입니다. tcat:additionalBuildingBlock에 해당합니다.  - `additionalBuildingBlockDescription[*]`: 추가 기능에 대한 텍스트 설명입니다. tcat:추가 건물 블록 설명에 해당합니다.  - `businessOfferings[*]`: 관리형 서비스, SaaS 또는 지원과 같은 비즈니스 오퍼링에 대한 설명입니다. tcat:비즈니스 오퍼링에 해당함  - `dataModelDomain[*]`: 서비스에서 관리하는 데이터 모델의 주제 영역 또는 비즈니스 도메인을 설명합니다. dcterms:subject에 해당합니다.  - `dataModelSpecificationType[string]`: 지원되는 데이터 모델 사양의 유형(예: 온톨로지, 데이터 스키마).  - `dataModelVersioning[string]`: 데이터 모델 버전 관리에 사용되는 접근 방식입니다. 스키마:버전에 해당합니다.  - `dataspaceBuildingBlock[*]`: 이 도구와 관련된 데이터 공간 빌딩 블록입니다. tcat:dataspaceBuildingBlock에 해당합니다.  - `dataspaceProductPurpose[string]`: 구현이 DSSC의 목표에 어떻게 기여하는지에 대한 설명입니다. tcat:dataspaceProductPurpose에 해당합니다.  - `dataspaceService[*]`: 이 도구가 구현하는 특정 데이터 공간 서비스입니다. tcat:dataspaceService에 해당합니다.  - `dataspaceServiceCategory[string]`: 데이터 스페이스 서비스의 카테고리입니다. tcat:dataspaceServiceCategory에 해당합니다.  - `dependencies[*]`: 다른 도구 또는 구성 요소에 대한 종속성 또는 전제 조건  - `deploymentsInOperation[*]`: 운영에서 도구의 사용/배포에 대한 개요 또는 링크입니다. tcat:existingDeployments에 해당합니다.  - `description[string]`: 구현의 주요 초점과 주요 기능에 대한 간략한 개요입니다. dc:설명에 해당  - `documentation[*]`: 관련 문서(제품 페이지, 소프트웨어 리포지토리, API 사양 등)로 직접 연결되는 링크입니다. 스키마:문서에 해당  - `domain[*]`: 해당 도구가 관련된 도메인, 섹터 또는 산업 분야  - `exportFormats[*]`: 서비스가 데이터 모델을 내보낼 수 있는 데이터 형식(MIME 유형 목록)입니다. dcat:mediaType에 해당합니다.  - `functionalApplicationArea[*]`: 도구의 용도가 되는 애플리케이션  - `geographicalApplicationArea[*]`: 도구의 대상 지역(예: 글로벌, 유럽)  - `governanceFeatures[string]`: 역할 기반 액세스 제어 및 워크플로 관리와 같은 거버넌스 기능.  - `hasVersion[string]`: 구현 버전입니다. 값은 SemVer 2.0을 준수해야 합니다. dc:hasVersion에 해당합니다.  - `id[*]`: 엔티티의 고유 식별자  - `image[*]`: 도구의 사용자 인터페이스 관련 사진 또는 스크린샷. 스키마:이미지에 해당  - `importFormats[*]`: 서비스에서 데이터 모델을 생성하기 위해 가져올 수 있는 데이터 형식(MIME 유형 목록)입니다. dcat:mediatype에 해당합니다.  - `keywords[*]`: 도구를 분류하는 키워드, 가급적이면 제어된 어휘로 분류합니다. 스키마:키워드에 해당  - `license[*]`: 도구에 액세스하고 사용하기 위한 라이선스 세부 정보에 대한 링크입니다. 스키마:라이선스에 해당  - `licenseDeclared[*]`: 컴퓨터에서 검색 가능한 라이선스 유형입니다. 값은 SPDX 라이선스 목록(https://spdx.org/licenses/)을 준수해야 합니다. spdx.org:licenseDeclared에 해당합니다.  - `maintainer[object]`: 구현을 유지 관리하는 조직입니다. 스키마:유지 관리자에 해당  	- `logo[uri]`: 조직 로고의 URL입니다. 스키마:로고에 해당    
	- `name[string]`: 조직 이름    
	- `url[uri]`: 조직 웹사이트의 URL    
- `mappingFunctionalities[string]`: 서비스가 서로 다른 데이터 모델 간의 매핑 기능을 제공하는지 여부를 설명합니다.  - `publicationAccessibility[*]`: 어휘를 게시하고 액세스 가능하게 만드는 데 사용되는 메서드(예: SPARQL 엔드포인트). dcat:accessService에 해당합니다.  - `referenceDatasetManagement[string]`: 서비스에서 참조 데이터세트(코델리스트)를 관리하는 방법을 설명합니다.  - `similarTools[*]`: 유사하거나 경쟁하는 도구 목록  - `supportedStandards[*]`: 서비스가 지원하는 특정 공식 또는 업계 표준 목록입니다. dcterms:준수에 해당합니다.  - `supportedSyntaxes[*]`: 서비스에서 처리할 수 있는 데이터 모델 구문(예: OWL, JSON 스키마). dc:format에 해당합니다.  - `supportingAttachments[array]`: 자세한 정보를 위한 추가 첨부 파일 또는 링크  - `technologyReadinessLevel[number]`: 도구의 기술 준비 수준(TRL)입니다. tcat:technologyReadiness에 해당합니다.  - `title[string]`: 도구/구현의 이름입니다. dc:title에 해당  - `trlJustification[string]`: 선언된 TRL에 대한 정당성. tcat:technologyReadinessDescription에 해당합니다.  - `type[string]`: NGSI 엔티티 유형. VocabularyService여야 합니다.  - `url[uri]`: 도구에 대한 자세한 정보가 있는 웹페이지의 URL입니다. foaf:홈페이지 또는 스키마:url에 해당합니다.  - `validationCapabilities[*]`: 서비스에서 데이터 모델에 대한 데이터 인스턴스의 유효성 검사를 제공할지 여부를 지정합니다.  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
필수 속성  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## 속성에 대한 데이터 모델 설명  
알파벳순으로 정렬(자세한 내용을 보려면 클릭)  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
VocabularyService:    
  description: A data model for a Vocabulary Service tool. This service manages and hosts data models like vocabularies, ontologies, and schemas. It extends the base ToolInformation model.    
  properties:    
    additionalBuildingBlock:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Additional building blocks functions offered by this tool. Corresponds to tcat:additionalBuildingBlock    
      x-ngsi:    
        type: Property    
    additionalBuildingBlockDescription:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Textual description of additional functionalities. Corresponds to tcat:additionalBuildingBlockDescription    
      x-ngsi:    
        type: Property    
    businessOfferings:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Description of business offerings like managed services, SaaS, or support. Corresponds to tcat:businessOfferings    
      x-ngsi:    
        type: Property    
    dataModelDomain:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Describes the subject areas or business domains of the data models managed by the service. Corresponds to dcterms:subject.    
      minItems: 1    
      x-ngsi:    
        type: Property    
    dataModelSpecificationType:    
      description: The type of data model specification supported (e.g., Ontology, Data Schema).    
      enum:    
        - Vocabulary    
        - Ontology    
        - Application Profile    
        - Data Schema    
      type: string    
      x-ngsi:    
        type: Property    
    dataModelVersioning:    
      description: The approach used for data model versioning. Corresponds to schema:version.    
      enum:    
        - Semantic Versioning    
        - Full History    
        - None    
      type: string    
      x-ngsi:    
        type: Property    
    dataspaceBuildingBlock:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: The data space building block(s) this tool is related to. Corresponds to tcat:dataspaceBuildingBlock    
      minItems: 1    
      x-ngsi:    
        type: Property    
    dataspaceProductPurpose:    
      description: Description of how the implementation contributes to DSSC's objectives. Corresponds to tcat:dataspaceProductPurpose    
      type: string    
      x-ngsi:    
        type: Property    
    dataspaceService:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: The specific data space service(s) this tool implements. Corresponds to tcat:dataspaceService    
      minItems: 1    
      x-ngsi:    
        type: Property    
    dataspaceServiceCategory:    
      description: The category of the data space service. Corresponds to tcat:dataspaceServiceCategory    
      enum:    
        - Federation services    
        - Participant Agent services    
        - Value Creation services    
      type: string    
      x-ngsi:    
        type: Property    
    dependencies:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Dependencies or prerequisites on other tools or components    
      x-ngsi:    
        type: Property    
    deploymentsInOperation:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Overview or links to usage/deployments of the tool in operations. Corresponds to tcat:existingDeployments    
      x-ngsi:    
        type: Property    
    description:    
      description: A brief overview of the primary focus and key features of the implementation. Corresponds to dc:description    
      type: string    
      x-ngsi:    
        type: Property    
    documentation:    
      anyOf:    
        - items:    
            format: uri    
            type: string    
          type: array    
        - format: uri    
          type: string    
      description: Direct links to relevant documents (product page, software repository, API spec, etc.). Corresponds to schema:documentation    
      minItems: 1    
      x-ngsi:    
        type: Property    
    domain:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: The domain(s), sector(s), or industry/ies for which the tool is relevant    
      x-ngsi:    
        type: Property    
    exportFormats:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Data formats in which the service can export data models (list of MIME types). Corresponds to dcat:mediaType.    
      minItems: 1    
      x-ngsi:    
        type: Property    
    functionalApplicationArea:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: The applications for which the tool is intended    
      x-ngsi:    
        type: Property    
    geographicalApplicationArea:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: The geographical region for which the tool is intended (e.g., global, Europe)    
      x-ngsi:    
        type: Property    
    governanceFeatures:    
      description: Governance functionalities, such as role-based access control and workflow management.    
      type: string    
      x-ngsi:    
        type: Property    
    hasVersion:    
      description: The versions of the implementation. Values must adhere to SemVer 2.0. Corresponds to dc:hasVersion    
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
    image:    
      anyOf:    
        - items:    
            format: uri    
            type: string    
          type: array    
        - format: uri    
          type: string    
      description: Relevant pictures or screenshots of the tool’s user interface. Corresponds to schema:image    
      x-ngsi:    
        type: Property    
    importFormats:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Data formats the service can import for creating a data model (list of MIME types). Corresponds to dcat:mediatype.    
      minItems: 1    
      x-ngsi:    
        type: Property    
    keywords:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Keywords that categorize the tool, preferably from a controlled vocabulary. Corresponds to schema:keywords    
      x-ngsi:    
        type: Property    
    license:    
      anyOf:    
        - items:    
            format: uri    
            type: string    
          type: array    
        - format: uri    
          type: string    
      description: Links to the license details for accessing and using the tool. Corresponds to schema:license    
      minItems: 1    
      x-ngsi:    
        type: Property    
    licenseDeclared:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: The machine-searchable license type. Value must adhere to SPDX license list (https://spdx.org/licenses/). Corresponds to spdx.org:licenseDeclared    
      minItems: 1    
      x-ngsi:    
        type: Property    
    maintainer:    
      description: The organization that maintains the implementation. Corresponds to schema:maintainer    
      properties:    
        logo:    
          description: URL of the organization's logo. Corresponds to schema:logo    
          format: uri    
          type: string    
          x-ngsi:    
            type: Property    
        name:    
          description: Name of the organization    
          type: string    
          x-ngsi:    
            type: Property    
        url:    
          description: URL of the organization's website    
          format: uri    
          type: string    
          x-ngsi:    
            type: Property    
      required:    
        - name    
      type: object    
      x-ngsi:    
        type: Property    
    mappingFunctionalities:    
      description: Describes if the service provides functionalities for mapping between different data models.    
      type: string    
      x-ngsi:    
        type: Property    
    publicationAccessibility:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Methods used to publish and make vocabularies accessible (e.g., SPARQL endpoint). Corresponds to dcat:accessService.    
      minItems: 1    
      x-ngsi:    
        type: Property    
    referenceDatasetManagement:    
      description: Describes how the service manages reference datasets (codelists).    
      type: string    
      x-ngsi:    
        type: Property    
    similarTools:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: A list of similar or competing tools    
      x-ngsi:    
        type: Property    
    supportedStandards:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: List of specific formal or industry standards that the service supports. Corresponds to dcterms:conformsTo.    
      minItems: 1    
      x-ngsi:    
        type: Property    
    supportedSyntaxes:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: Data model syntaxes the service can process (e.g., OWL, JSON Schema). Corresponds to dc:format.    
      minItems: 1    
      x-ngsi:    
        type: Property    
    supportingAttachments:    
      description: Additional attachments or links for more information    
      items:    
        description: Additional attachments or links for more information    
        format: uri    
        type: string    
        x-ngsi:    
          type: Property    
      type: array    
      x-ngsi:    
        type: Property    
    technologyReadinessLevel:    
      description: The Technology Readiness Level (TRL) of the tool. Corresponds to tcat:technologyReadiness    
      maximum: 9    
      minimum: 1    
      type: number    
      x-ngsi:    
        type: Property    
    title:    
      description: The name of the tool/implementation. Corresponds to dc:title    
      type: string    
      x-ngsi:    
        type: Property    
    trlJustification:    
      description: Justification for the declared TRL. Corresponds to tcat:technologyReadinessDescription    
      type: string    
      x-ngsi:    
        type: Property    
    type:    
      description: NGSI entity type. It has to be VocabularyService.    
      enum:    
        - VocabularyService    
      type: string    
      x-ngsi:    
        type: Property    
    url:    
      description: A URL to a webpage with more information about the tool. Corresponds to foaf:homepage or schema:url    
      format: uri    
      type: string    
      x-ngsi:    
        type: Property    
    validationCapabilities:    
      anyOf:    
        - items:    
            enum:    
              - JSON validator    
              - XML validator    
              - SHACL validator    
            type: string    
          type: array    
        - enum:    
            - JSON validator    
            - XML validator    
            - SHACL validator    
          type: string    
      description: Specifies if the service offers validation of data instances against data models.    
      minItems: 1    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
  type: object    
  x-derived-from: ''    
  x-disclaimer: Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2025 Contributors to Smart Data Models Program    
  x-license-url: https://github.com/smart-data-models/dataModel.DataSpace/blob/master/VocabularyService/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.DataSpace/VocabularyService/schema.json    
  x-model-tags: ''    
  x-version: 0.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## 페이로드 예시  
#### 어휘 서비스 NGSI-v2 키 값 예제  
다음은 키 값으로 JSON-LD 형식의 VocabularyService의 예입니다. 이는 `옵션=키값`을 사용할 때 NGSI-v2와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:VocabularyService:VocabServ-001",  
  "type": "VocabularyService",  
  "title": "OntoManager Pro",  
  "description": "A professional service for managing and publishing enterprise ontologies and data schemas.",  
  "url": "https://example.com/ontomanager",  
  "hasVersion": "2.5.0",  
  "maintainer": {  
    "name": "Semantic Solutions Inc.",  
    "url": "https://semanticsol.com"  
  },  
  "dataspaceProductPurpose": "To provide a centralized, governed repository for data models, ensuring semantic interoperability across the data space.",  
  "documentation": [  
    "https://docs.semanticsol.com/ontomanager"  
  ],  
  "license": [  
    "https://example.com/licenses/commercial-eula"  
  ],  
  "licenseDeclared": [  
    "UNLICENSED"  
  ],  
  "dataspaceServiceCategory": "Federation services",  
  "dataspaceService": [  
    "Vocabulary Services"  
  ],  
  "dataspaceBuildingBlock": [  
    "Semantic Interoperability"  
  ],  
  "technologyReadinessLevel": 9,  
  "dataModelDomain": [  
    "Healthcare",  
    "Finance"  
  ],  
  "dataModelSpecificationType": "Ontology",  
  "supportedSyntaxes": [  
    "OWL",  
    "RDFS",  
    "SKOS",  
    "SHACL"  
  ],  
  "importFormats": [  
    "application/rdf+xml",  
    "text/turtle",  
    "application/vnd.ms-excel"  
  ],  
  "exportFormats": [  
    "application/json",  
    "application/rdf+xml",  
    "text/turtle"  
  ],  
  "dataModelVersioning": "Full History",  
  "governanceFeatures": "Role-based access control, working groups workflows, change request management.",  
  "publicationAccessibility": [  
    "Persistent URIs",  
    "SPARQL endpoint",  
    "Web Portal"  
  ],  
  "validationCapabilities": [  
    "SHACL validator"  
  ],  
  "supportedStandards": [  
    "ISO 15926"  
  ],  
  "mappingFunctionalities": "Provides a graphical interface for creating and managing mappings between different ontologies."  
}  
```  
</details>  
#### 어휘 서비스 NGSI-v2 정규화 예제  
다음은 정규화된 JSON-LD 형식의 VocabularyService의 예입니다. 이는 옵션을 사용하지 않을 때 NGSI-v2와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:VocabularyService:VocabServ-001",  
  "type": "VocabularyService",  
  "title": {  
    "type": "Text",  
    "value": "OntoManager Pro"  
  },  
  "description": {  
    "type": "Text",  
    "value": "A professional service for managing and publishing enterprise ontologies and data schemas."  
  },  
  "url": {  
    "type": "URL",  
    "value": "https://example.com/ontomanager"  
  },  
  "hasVersion": {  
    "type": "Text",  
    "value": "2.5.0"  
  },  
  "maintainer": {  
    "type": "StructuredValue",  
    "value": {  
      "name": "Semantic Solutions Inc.",  
      "url": "https://semanticsol.com"  
    }  
  },  
  "dataspaceProductPurpose": {  
    "type": "Text",  
    "value": "To provide a centralized, governed repository for data models, ensuring semantic interoperability across the data space."  
  },  
  "documentation": {  
    "type": "URL",  
    "value": "https://docs.semanticsol.com/ontomanager"  
  },  
  "license": {  
    "type": "URL",  
    "value": "https://example.com/licenses/commercial-eula"  
  },  
  "licenseDeclared": {  
    "type": "Text",  
    "value": "UNLICENSED"  
  },  
  "dataspaceServiceCategory": {  
    "type": "Text",  
    "value": "Federation services"  
  },  
  "dataspaceService": {  
    "type": "Property",  
    "value": "Vocabulary Services"  
  },  
  "dataspaceBuildingBlock": {  
    "type": "Property",  
    "value": "Semantic Interoperability"  
  },  
  "technologyReadinessLevel": {  
    "type": "Number",  
    "value": 9  
  },  
  "dataModelDomain": {  
    "type": "array",  
    "value": [  
      "Healthcare",  
      "Finance"  
    ]  
  },  
  "dataModelSpecificationType": {  
    "type": "Text",  
    "value": "Ontology"  
  },  
  "supportedSyntaxes": {  
    "type": "Property",  
    "value": [  
      "OWL",  
      "RDFS",  
      "SKOS",  
      "SHACL"  
    ]  
  },  
  "importFormats": {  
    "type": "array",  
    "value": [  
      "application/rdf+xml",  
      "text/turtle",  
      "application/vnd.ms-excel"  
    ]  
  },  
  "exportFormats": {  
    "type": "array",  
    "value": [  
      "application/json",  
      "application/rdf+xml",  
      "text/turtle"  
    ]  
  },  
  "dataModelVersioning": {  
    "type": "Text",  
    "value": "Full History"  
  },  
  "governanceFeatures": {  
    "type": "Text",  
    "value": "Role-based access control, working groups workflows, change request management."  
  },  
  "publicationAccessibility": {  
    "type": "array",  
    "value": [  
      "Persistent URIs",  
      "SPARQL endpoint",  
      "Web Portal"  
    ]  
  },  
  "validationCapabilities": {  
    "type": "Text",  
    "value": "SHACL validator"  
  },  
  "supportedStandards": {  
    "type": "Text",  
    "value": "ISO 15926"  
  },  
  "mappingFunctionalities": {  
    "type": "Text",  
    "value": "Provides a graphical interface for creating and managing mappings between different ontologies."  
  }  
}  
```  
</details>  
#### 어휘 서비스 NGSI-LD 키 값 예제  
다음은 키 값으로 JSON-LD 형식의 VocabularyService의 예입니다. 이는 `옵션=키값`을 사용할 때 NGSI-LD와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:VocabularyService:VocabServ-001",  
  "type": "VocabularyService",  
  "title": "OntoManager Pro",  
  "description": "A professional service for managing and publishing enterprise ontologies and data schemas.",  
  "url": "https://example.com/ontomanager",  
  "hasVersion": "2.5.0",  
  "maintainer": {  
    "name": "Semantic Solutions Inc.",  
    "url": "https://semanticsol.com"  
  },  
  "dataspaceProductPurpose": "To provide a centralized, governed repository for data models, ensuring semantic interoperability across the data space.",  
  "documentation": [  
    "https://docs.semanticsol.com/ontomanager"  
  ],  
  "license": [  
    "https://example.com/licenses/commercial-eula"  
  ],  
  "licenseDeclared": [  
    "UNLICENSED"  
  ],  
  "dataspaceServiceCategory": "Federation services",  
  "dataspaceService": [  
    "Vocabulary Services"  
  ],  
  "dataspaceBuildingBlock": [  
    "Semantic Interoperability"  
  ],  
  "technologyReadinessLevel": 9,  
  "dataModelDomain": [  
    "Healthcare",  
    "Finance"  
  ],  
  "dataModelSpecificationType": "Ontology",  
  "supportedSyntaxes": [  
    "OWL",  
    "RDFS",  
    "SKOS",  
    "SHACL"  
  ],  
  "importFormats": [  
    "application/rdf+xml",  
    "text/turtle",  
    "application/vnd.ms-excel"  
  ],  
  "exportFormats": [  
    "application/json",  
    "application/rdf+xml",  
    "text/turtle"  
  ],  
  "dataModelVersioning": "Full History",  
  "governanceFeatures": "Role-based access control, working groups workflows, change request management.",  
  "publicationAccessibility": [  
    "Persistent URIs",  
    "SPARQL endpoint",  
    "Web Portal"  
  ],  
  "validationCapabilities": [  
    "SHACL validator"  
  ],  
  "supportedStandards": [  
    "ISO 15926"  
  ],  
  "mappingFunctionalities": "Provides a graphical interface for creating and managing mappings between different ontologies.",  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.Dataspace/master/context.jsonld"  
  ]  
}  
```  
</details>  
#### 어휘 서비스 NGSI-LD 정규화 예제  
다음은 정규화된 JSON-LD 형식의 VocabularyService의 예입니다. 이는 옵션을 사용하지 않을 때 NGSI-LD와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:VocabularyService:VocabServ-001",  
  "type": "VocabularyService",  
  "title": {  
    "type": "Property",  
    "value": "OntoManager Pro"  
  },  
  "description": {  
    "type": "Property",  
    "value": "A professional service for managing and publishing enterprise ontologies and data schemas."  
  },  
  "url": {  
    "type": "Property",  
    "value": "https://example.com/ontomanager"  
  },  
  "hasVersion": {  
    "type": "Property",  
    "value": "2.5.0"  
  },  
  "maintainer": {  
    "type": "Property",  
    "value": {  
      "name": "Semantic Solutions Inc.",  
      "url": "https://semanticsol.com"  
    }  
  },  
  "dataspaceProductPurpose": {  
    "type": "Property",  
    "value": "To provide a centralized, governed repository for data models, ensuring semantic interoperability across the data space."  
  },  
  "documentation": {  
    "type": "Property",  
    "value": "https://docs.semanticsol.com/ontomanager"  
  },  
  "license": {  
    "type": "Property",  
    "value": "https://example.com/licenses/commercial-eula"  
  },  
  "licenseDeclared": {  
    "type": "Property",  
    "value": "UNLICENSED"  
  },  
  "dataspaceServiceCategory": {  
    "type": "Property",  
    "value": "Federation services"  
  },  
  "dataspaceService": {  
    "type": "Property",  
    "value": "Vocabulary Services"  
  },  
  "dataspaceBuildingBlock": {  
    "type": "Property",  
    "value": "Semantic Interoperability"  
  },  
  "technologyReadinessLevel": {  
    "type": "Property",  
    "value": 9  
  },  
  "dataModelDomain": {  
    "type": "Property",  
    "value": [  
      "Healthcare",  
      "Finance"  
    ]  
  },  
  "dataModelSpecificationType": {  
    "type": "Property",  
    "value": "Ontology"  
  },  
  "supportedSyntaxes": {  
    "type": "Property",  
    "value": [  
      "OWL",  
      "RDFS",  
      "SKOS",  
      "SHACL"  
    ]  
  },  
  "importFormats": {  
    "type": "Property",  
    "value": [  
      "application/rdf+xml",  
      "text/turtle",  
      "application/vnd.ms-excel"  
    ]  
  },  
  "exportFormats": {  
    "type": "Property",  
    "value": [  
      "application/json",  
      "application/rdf+xml",  
      "text/turtle"  
    ]  
  },  
  "dataModelVersioning": {  
    "type": "Property",  
    "value": "Full History"  
  },  
  "governanceFeatures": {  
    "type": "Property",  
    "value": "Role-based access control, working groups workflows, change request management."  
  },  
  "publicationAccessibility": {  
    "type": "Property",  
    "value": [  
      "Persistent URIs",  
      "SPARQL endpoint",  
      "Web Portal"  
    ]  
  },  
  "validationCapabilities": {  
    "type": "Property",  
    "value": "SHACL validator"  
  },  
  "supportedStandards": {  
    "type": "Property",  
    "value": "ISO 15926"  
  },  
  "mappingFunctionalities": {  
    "type": "Property",  
    "value": "Provides a graphical interface for creating and managing mappings between different ontologies."  
  },   
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.Dataspace/master/context.jsonld"  
  ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
규모 단위를 다루는 방법에 대한 답변은 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)을 참조하세요.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
