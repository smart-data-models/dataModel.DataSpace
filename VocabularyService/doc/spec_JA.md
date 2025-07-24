<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
エンティティ語彙サービス  
============<!-- /10-Header -->  
<!-- 15-License -->  
[オープン・ライセンス](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/VocabularyService/LICENSE.md)  
[文書が自動的に生成される](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
グローバルな記述：**語彙サービスツールのデータモデル。このサービスはボキャブラリー、オントロジー、スキーマのようなデータモデルを管理し、ホストする。ベースとなるToolInformationモデルを拡張する。  
バージョン: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## プロパティのリスト  

<sup><sub>[*] 属性に型がない場合は、複数の型があるか、異なるフォーマット/パターンがある可能性があるためです</sub></sup>。  
- `additionalBuildingBlock[*]`: このツールが提供する追加のビルディングブロック機能。tcat:additionalBuildingBlockに対応する。  - `additionalBuildingBlockDescription[*]`: 追加機能のテキスト記述。tcat:additionalBuildingBlockDescription に対応する。  - `businessOfferings[*]`: マネージドサービス、SaaS、サポートなどのビジネスオファリングの説明。tcat:businessOfferings に対応します。  - `dataModelDomain[*]`: サービスが管理するデータモデルのサブジェクト領域またはビジネスドメインを記述する。dcterms:subjectに対応する。  - `dataModelSpecificationType[string]`: サポートされるデータモデル仕様のタイプ（オントロジー、データスキーマなど）。  - `dataModelVersioning[string]`: データモデルのバージョン管理に使われるアプローチ。schema:versionに対応します。  - `dataspaceBuildingBlock[*]`: このツールが関連するデータ空間ビルディングブロック。tcat:dataspaceBuildingBlockに対応する。  - `dataspaceProductPurpose[string]`: 実装が DSSC の目的にどのように貢献するかの説明。tcat:dataspaceProductPurpose に対応する。  - `dataspaceService[*]`: このツールが実装する特定のデータスペースサービス。tcat:dataspaceServiceに対応する。  - `dataspaceServiceCategory[string]`: データスペースサービスのカテゴリー。tcat:dataspaceServiceCategoryに対応します。  - `dependencies[*]`: 他のツールやコンポーネントへの依存や前提条件  - `deploymentsInOperation[*]`: 運用中のツールの使用/展開の概要またはリンク。tcat:existingDeploymentsに対応する。  - `description[string]`: 実装の主な焦点と主要な機能の簡単な概要。dc:description に対応する。  - `documentation[*]`: 関連ドキュメント（製品ページ、ソフトウェアリポジトリ、API仕様など）への直接リンク。schema:documentationに対応  - `domain[*]`: そのツールが関連するドメイン、セクター、または産業/ies  - `exportFormats[*]`: サービスがデータモデルをエクスポートできるデータ形式（MIMEタイプのリスト）。dcat:mediaTypeに対応。  - `functionalApplicationArea[*]`: ツールの用途  - `geographicalApplicationArea[*]`: ツールの対象地域（グローバル、ヨーロッパなど）  - `governanceFeatures[string]`: 役割ベースのアクセス制御やワークフロー管理などのガバナンス機能。  - `hasVersion[string]`: 実装のバージョン。値はSemVer 2.0に準拠しなければならない。dc:hasVersionに対応します。  - `id[*]`: エンティティの一意識別子  - `image[*]`: ツールのユーザインタフェースの関連する画像またはスクリーンショット。schema:imageに対応  - `importFormats[*]`: データモデルを作成するためにサービスがインポートできるデータ形式（MIMEタイプのリスト）。dcat:mediatypeに対応。  - `keywords[*]`: ツールを分類するキーワードで、できれば統制された語彙から。schema:keywordsに対応する。  - `license[*]`: ツールにアクセスして使用するためのライセンスの詳細へのリンク。schema:licenseに対応しています。  - `licenseDeclared[*]`: 機械検索可能な ラ イ セ ン ス タ イ プ。値はSPDXライセンスリスト(https://spdx.org/licenses/)に従わなければならない。spdx.org:licenseDeclaredに対応します。  - `maintainer[object]`: 実装をメンテナンスする組織。schema:maintainer に対応します。  	- `logo[uri]`: 組織のロゴのURL。schema:logoに対応しています。    
	- `name[string]`: 団体名    
	- `url[uri]`: 組織のウェブサイトのURL    
- `mappingFunctionalities[string]`: サービスが異なるデータモデル間のマッピングのための機能を提供するかどうかを記述する。  - `publicationAccessibility[*]`: ボキャブラリーを公開し、アクセス可能にするために使用されるメソッド（例：SPARQLエンドポイント）。dcat:accessServiceに対応します。  - `referenceDatasetManagement[string]`: サービスが参照データセット（コードリスト）を管理する方法を説明する。  - `similarTools[*]`: 類似または競合ツールのリスト  - `supportedStandards[*]`: サービスがサポートする特定の公式または業界標準のリスト。dcterms:conformsTo に対応する。  - `supportedSyntaxes[*]`: サービスが処理できるデータモデル構文（OWL、JSON Schemaなど）。dc:formatに対応する。  - `supportingAttachments[array]`: その他の添付ファイルまたはリンク  - `technologyReadinessLevel[number]`: ツールの技術成熟度レベル（TRL）。tcat:technologyReadinessに対応する。  - `title[string]`: ツール/実装の名前。dc:titleに対応する。  - `trlJustification[string]`: 宣言されたTRLの正当性。tcat:technologyReadinessDescription に対応する。  - `type[string]`: NGSIエンティティタイプ。VocabularyServiceでなければならない。  - `url[uri]`: ツールの詳細情報を含むウェブページへのURL。foaf:homepage または schema:url に対応します。  - `validationCapabilities[*]`: サービスがデータモデルに対するデータインスタンスの検証を提供するかどうかを指定します。  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
必須プロパティ  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## プロパティのデータモデル記述  
アルファベット順（クリックで詳細表示）  
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
## ペイロードの例  
#### VocabularyService NGSI-v2 キー値の例  
JSON-LD形式のVocabularyServiceのkey-valuesの例です。options=keyValues`を使うとNGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返す。  
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
#### VocabularyService NGSI-v2 正規化例  
以下は、正規化されたJSON-LD形式のVocabularyServiceの例である。これは、オプションを使用しない場合、NGSI-v2と互換性があり、個々のエンティティのコンテキスト・データを返します。  
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
#### VocabularyService NGSI-LD キー値の例  
JSON-LD形式のVocabularyServiceのkey-valuesの例です。options=keyValues`を使うとNGSI-LDと互換性があり、個々のエンティティのコンテキストデータを返す。  
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
#### VocabularyService NGSI-LD 正規化例  
以下は、正規化されたJSON-LD形式のVocabularyServiceの例である。これは、オプションを使用しない場合はNGSI-LDと互換性があり、個々のエンティティのコンテキスト・データを返します。  
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
マグニチュード単位の扱い方については、[FAQ 10](https://smartdatamodels.org/index.php/faqs/)を参照のこと。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
