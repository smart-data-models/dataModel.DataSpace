<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entität: VocabularyService  
==========================<!-- /10-Header -->  
<!-- 15-License -->  
[Offene Lizenz](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/VocabularyService/LICENSE.md)  
[Dokument automatisch generiert](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Globale Beschreibung: **Ein Datenmodell für ein Vokabeldienst-Tool. Dieser Dienst verwaltet und hostet Datenmodelle wie Vokabulare, Ontologien und Schemata. Er erweitert das ToolInformation-Basismodell.**  
Version: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Liste der Eigenschaften  

<sup><sub>[*] Wenn es für ein Attribut keinen Typ gibt, liegt das daran, dass es mehrere Typen oder unterschiedliche Formate/Muster haben kann</sub></sup>.  
- `additionalBuildingBlock[*]`: Zusätzliche Bausteinfunktionen, die von diesem Werkzeug angeboten werden. Entspricht tcat:additionalBuildingBlock  - `additionalBuildingBlockDescription[*]`: Textliche Beschreibung zusätzlicher Funktionalitäten. Entspricht der tcat:additionalBuildingBlockDescription  - `businessOfferings[*]`: Beschreibung von Geschäftsangeboten wie Managed Services, SaaS oder Support. Entspricht tcat:businessOfferings  - `dataModelDomain[*]`: Beschreibt die Themenbereiche oder Geschäftsbereiche der vom Dienst verwalteten Datenmodelle. Entspricht dcterms:subject.  - `dataModelSpecificationType[string]`: Die Art der unterstützten Datenmodellspezifikation (z. B. Ontologie, Datenschema).  - `dataModelVersioning[string]`: Der für die Versionierung des Datenmodells verwendete Ansatz. Entspricht schema:version.  - `dataspaceBuildingBlock[*]`: Der/die Datenraumbaustein(e), auf den/die sich dieses Werkzeug bezieht. Entspricht tcat:dataspaceBuildingBlock  - `dataspaceProductPurpose[string]`: Beschreibung, wie die Implementierung zur Erreichung der Ziele des DSSC beiträgt. Entspricht tcat:dataspaceProductPurpose  - `dataspaceService[*]`: Der/die spezifische(n) Datenraumdienst(e), den/die dieses Werkzeug implementiert. Entspricht tcat:dataspaceService  - `dataspaceServiceCategory[string]`: Die Kategorie des Datenraumdienstes. Entspricht tcat:dataspaceServiceCategory  - `dependencies[*]`: Abhängigkeiten oder Voraussetzungen von anderen Tools oder Komponenten  - `deploymentsInOperation[*]`: Übersicht oder Links zur Verwendung/Einführung des Tools im Betrieb. Entspricht tcat:existingDeployments  - `description[string]`: Ein kurzer Überblick über den Hauptschwerpunkt und die wichtigsten Merkmale der Implementierung. Entspricht dc:description  - `documentation[*]`: Direkte Links zu relevanten Dokumenten (Produktseite, Software-Repository, API-Spezifikation usw.). Entspricht schema:documentation  - `domain[*]`: Bereich(e), Sektor(en) oder Branche(n), für die das Instrument relevant ist  - `exportFormats[*]`: Datenformate, in denen der Dienst Datenmodelle exportieren kann (Liste der MIME-Typen). Entspricht dcat:mediaType.  - `functionalApplicationArea[*]`: Die Anwendungen, für die das Werkzeug bestimmt ist  - `geographicalApplicationArea[*]`: Die geografische Region, für die das Instrument bestimmt ist (z. B. weltweit, Europa)  - `governanceFeatures[string]`: Governance-Funktionen, wie rollenbasierte Zugriffskontrolle und Workflow-Management.  - `hasVersion[string]`: Die Versionen der Implementierung. Die Werte müssen sich an SemVer 2.0 halten. Entspricht dc:hasVersion  - `id[*]`: Eindeutiger Bezeichner der Entität  - `image[*]`: Relevante Bilder oder Screenshots von der Benutzeroberfläche des Tools. Entspricht schema:image  - `importFormats[*]`: Datenformate, die der Dienst zur Erstellung eines Datenmodells importieren kann (Liste der MIME-Typen). Entspricht dcat:mediatype.  - `keywords[*]`: Schlüsselwörter, die das Werkzeug kategorisieren, vorzugsweise aus einem kontrollierten Vokabular. Entspricht schema:keywords  - `license[*]`: Links zu den Lizenzdetails für den Zugriff und die Verwendung des Tools. Entspricht schema:license  - `licenseDeclared[*]`: Der maschinell durchsuchbare Lizenztyp. Der Wert muss mit der SPDX-Lizenzliste übereinstimmen (https://spdx.org/licenses/). Entspricht spdx.org:licenseDeclared  - `maintainer[object]`: Die Organisation, die die Implementierung pflegt. Entspricht schema:maintainer  	- `logo[uri]`: URL des Logos der Organisation. Entspricht schema:logo    
	- `name[string]`: Name der Organisation    
	- `url[uri]`: URL der Website der Organisation    
- `mappingFunctionalities[string]`: Beschreibt, ob der Dienst Funktionen für das Mapping zwischen verschiedenen Datenmodellen bietet.  - `publicationAccessibility[*]`: Methoden zur Veröffentlichung und Zugänglichmachung von Vokabularen (z. B. SPARQL-Endpunkt). Entspricht dcat:accessService.  - `referenceDatasetManagement[string]`: Beschreibt, wie der Dienst Referenzdatensätze (Codelisten) verwaltet.  - `similarTools[*]`: Eine Liste ähnlicher oder konkurrierender Tools  - `supportedStandards[*]`: Liste spezifischer formaler oder industrieller Standards, die der Dienst unterstützt. Entspricht dcterms:conformsTo.  - `supportedSyntaxes[*]`: Datenmodellsyntaxen, die der Dienst verarbeiten kann (z. B. OWL, JSON Schema). Entspricht dc:format.  - `supportingAttachments[array]`: Zusätzliche Anhänge oder Links für weitere Informationen  - `technologyReadinessLevel[number]`: Der Technology Readiness Level (TRL) des Werkzeugs. Entspricht tcat:technologyReadiness  - `title[string]`: Der Name des Werkzeugs/der Implementierung. Entspricht dc:title  - `trlJustification[string]`: Begründung für die angegebene TRL. Entspricht der tcat:technologyReadinessDescription  - `type[string]`: NGSI-Entitätstyp. Es muss VocabularyService sein.  - `url[uri]`: Eine URL zu einer Webseite mit weiteren Informationen über das Werkzeug. Entspricht foaf:homepage oder schema:url  - `validationCapabilities[*]`: Gibt an, ob der Dienst die Validierung von Dateninstanzen anhand von Datenmodellen anbietet.  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Erforderliche Eigenschaften  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## Datenmodell Beschreibung der Eigenschaften  
Alphabetisch sortiert (für Details anklicken)  
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
## Beispiel-Nutzlasten  
#### VocabularyService NGSI-v2 Schlüsselwerte Beispiel  
Hier ist ein Beispiel für einen VocabularyService im JSON-LD Format als Key-Values. Dies ist kompatibel mit NGSI-v2 bei Verwendung von `options=keyValues` und liefert die Kontextdaten einer einzelnen Entität.  
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
#### VocabularyService NGSI-v2 normalisiert Beispiel  
Hier ist ein Beispiel für einen VocabularyService im JSON-LD-Format in normalisierter Form. Dies ist kompatibel mit NGSI-v2, wenn keine Optionen verwendet werden und liefert die Kontextdaten einer einzelnen Entität.  
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
#### VocabularyService NGSI-LD Schlüsselwerte Beispiel  
Hier ist ein Beispiel für einen VocabularyService im JSON-LD Format als Key-Values. Dies ist kompatibel mit NGSI-LD bei Verwendung von `options=keyValues` und liefert die Kontextdaten einer einzelnen Entität.  
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
#### VocabularyService NGSI-LD normalisiert Beispiel  
Hier ist ein Beispiel für einen VocabularyService im JSON-LD-Format in normalisierter Form. Dies ist kompatibel mit NGSI-LD, wenn keine Optionen verwendet werden und liefert die Kontextdaten einer einzelnen Entität.  
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
Siehe [FAQ 10] (https://smartdatamodels.org/index.php/faqs/), um eine Antwort auf die Frage zu erhalten, wie man mit Größeneinheiten umgeht  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
