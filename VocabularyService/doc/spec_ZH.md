<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
实体：词汇服务  
=======<!-- /10-Header -->  
<!-- 15-License -->  
[开放许可](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/VocabularyService/LICENSE.md)  
[文件自动生成](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
全局描述：**词汇表服务工具的数据模型。该服务可管理和托管词汇表、本体和模式等数据模型。它扩展了基础 ToolInformation 模型。  
版本： 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 属性列表  

<sup><sub>[*] 如果属性中没有类型，是因为它可能有多个类型或不同的格式/模式</sub></sup>。  
- `additionalBuildingBlock[*]`: 该工具提供的附加积木功能。对应于 tcat:additionalBuildingBlock  - `additionalBuildingBlockDescription[*]`: 附加功能的文字描述。对应于 tcat:additionalBuildingBlockDescription  - `businessOfferings[*]`: 管理服务、SaaS 或支持等业务产品的描述。对应于 tcat:businessOfferings  - `dataModelDomain[*]`: 描述服务管理的数据模型的主题领域或业务领域。对应于 dcterms:subject。  - `dataModelSpecificationType[string]`: 支持的数据模型规范类型（如本体、数据模式）。  - `dataModelVersioning[string]`: 用于数据模型版本管理的方法。对应于 schema:版本。  - `dataspaceBuildingBlock[*]`: 该工具相关的数据空间构件。对应于 tcat:dataspaceBuildingBlock  - `dataspaceProductPurpose[string]`: 描述实施工作如何有助于实现 DSSC 的目标。对应于 tcat:dataspaceProductPurpose  - `dataspaceService[*]`: 该工具实现的特定数据空间服务。对应于 tcat:dataspaceService  - `dataspaceServiceCategory[string]`: 数据空间服务的类别。对应于 tcat:dataspaceServiceCategory  - `dependencies[*]`: 其他工具或组件的依赖性或先决条件  - `deploymentsInOperation[*]`: 工具使用/部署情况概览或链接。对应 tcat:existingDeployments  - `description[string]`: 简要概述实施工作的主要重点和主要特点。对应 dc:description  - `documentation[*]`: 指向相关文档（产品页面、软件库、API 规范等）的直接链接。对应于 schema:documentation  - `domain[*]`: 与工具相关的领域、部门或行业/实体  - `exportFormats[*]`: 服务可导出数据模型的数据格式（MIME 类型列表）。对应于 dcat:mediaType。  - `functionalApplicationArea[*]`: 工具的用途  - `geographicalApplicationArea[*]`: 工具适用的地理区域（如全球、欧洲）  - `governanceFeatures[string]`: 治理功能，如基于角色的访问控制和工作流程管理。  - `hasVersion[string]`: 实现的版本。值必须符合 SemVer 2.0。对应于 dc:hasVersion  - `id[*]`: 实体的唯一标识符  - `image[*]`: 工具用户界面的相关图片或截图。对应 schema:image  - `importFormats[*]`: 服务可导入用于创建数据模型的数据格式（MIME 类型列表）。对应于 dcat:mediatype。  - `keywords[*]`: 对工具进行分类的关键字，最好来自受控词汇表。对应于 schema:keywords  - `license[*]`: 访问和使用工具的许可证详细信息链接。对应于 schema:license  - `licenseDeclared[*]`: 机器可搜索的许可证类型。值必须符合 SPDX 许可证列表 (https://spdx.org/licenses/)。对应 spdx.org:licenseDeclared  - `maintainer[object]`: 维护实施的机构。对应于 schema:maintainer  	- `logo[uri]`: 机构徽标的 URL。对应于 schema:logo    
	- `name[string]`: 组织名称    
	- `url[uri]`: 组织网站的 URL    
- `mappingFunctionalities[string]`: 描述服务是否提供不同数据模型之间的映射功能。  - `publicationAccessibility[*]`: 用于发布和访问词汇表的方法（如 SPARQL 端点）。对应于 dcat:accessService。  - `referenceDatasetManagement[string]`: 描述服务如何管理参考数据集（代码表）。  - `similarTools[*]`: 类似或竞争工具列表  - `supportedStandards[*]`: 服务支持的特定正式标准或行业标准的列表。与 dcterms:conformsTo 对应。  - `supportedSyntaxes[*]`: 服务可处理的数据模型语法（如 OWL、JSON 模式）。对应于 dc:format。  - `supportingAttachments[array]`: 更多信息的附加附件或链接  - `technologyReadinessLevel[number]`: 工具的技术就绪水平 (TRL)。对应于 tcat:technologyReadiness  - `title[string]`: 工具/实现的名称。对应 dc:title  - `trlJustification[string]`: 声明 TRL 的理由。对应于 tcat:technologyReadinessDescription  - `type[string]`: NGSI 实体类型。它必须是 VocabularyService。  - `url[uri]`: 指向有关该工具更多信息的网页的 URL。对应于 foaf:homepage 或 schema:url  - `validationCapabilities[*]`: 指定服务是否根据数据模型对数据实例进行验证。  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
所需属性  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## 属性的数据模型描述  
按字母顺序排列（点击查看详情）  
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
## 有效载荷示例  
#### 词汇表服务 NGSI-v2 键值示例  
下面是一个以 JSON-LD 格式作为键值的 VocabularyService 示例。当使用 `options=keyValues` 时，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
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
#### VocabularyService NGSI-v2 规范化示例  
下面是一个规范化 JSON-LD 格式的 VocabularyService 示例。在不使用选项的情况下，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
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
#### 词汇表服务 NGSI-LD 键值示例  
下面是一个以 JSON-LD 格式作为键值的 VocabularyService 示例。当使用 `options=keyValues` 时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
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
#### 词汇服务 NGSI-LD 规范化示例  
下面是一个规范化 JSON-LD 格式的 VocabularyService 示例。当不使用选项时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
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
请参阅 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)，获取如何处理幅度单位的答案。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
