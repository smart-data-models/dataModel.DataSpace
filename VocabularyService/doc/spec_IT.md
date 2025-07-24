<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entità: VocabolarioServizio  
===========================<!-- /10-Header -->  
<!-- 15-License -->  
[Licenza aperta](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/VocabularyService/LICENSE.md)  
[documento generato automaticamente](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Descrizione globale: **Un modello di dati per uno strumento di servizio di vocabolario. Questo servizio gestisce e ospita modelli di dati come vocabolari, ontologie e schemi. Estende il modello di base ToolInformation.**  
versione: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Elenco delle proprietà  

<sup><sub>[*] Se non c'è un tipo in un attributo è perché potrebbe avere diversi tipi o diversi formati/modelli</sub></sup>.  
- `additionalBuildingBlock[*]`: Funzioni aggiuntive dei blocchi di costruzione offerte da questo strumento. Corrisponde a tcat:additionalBuildingBlock  - `additionalBuildingBlockDescription[*]`: Descrizione testuale delle funzionalità aggiuntive. Corrisponde a tcat:additionalBuildingBlockDescription  - `businessOfferings[*]`: Descrizione delle offerte aziendali, come servizi gestiti, SaaS o assistenza. Corrisponde a tcat:businessOfferings  - `dataModelDomain[*]`: Descrive le aree tematiche o i domini aziendali dei modelli di dati gestiti dal servizio. Corrisponde a dcterms:subject.  - `dataModelSpecificationType[string]`: Il tipo di specifica del modello di dati supportato (ad esempio, ontologia, schema di dati).  - `dataModelVersioning[string]`: L'approccio utilizzato per il versionamento dei modelli di dati. Corrisponde a schema:version.  - `dataspaceBuildingBlock[*]`: Il blocco o i blocchi dello spazio dati a cui è collegato questo strumento. Corrisponde a tcat:dataspaceBuildingBlock  - `dataspaceProductPurpose[string]`: Descrizione di come l'implementazione contribuisce agli obiettivi del DSSC. Corrisponde a tcat:dataspaceProductPurpose  - `dataspaceService[*]`: Il servizio specifico di spazio dati che questo strumento implementa. Corrisponde a tcat:dataspaceService  - `dataspaceServiceCategory[string]`: La categoria del servizio di spazio dati. Corrisponde a tcat:dataspaceServiceCategory  - `dependencies[*]`: Dipendenze o prerequisiti da altri strumenti o componenti  - `deploymentsInOperation[*]`: Panoramica o link all'uso/dispiegamento dello strumento nelle operazioni. Corrisponde a tcat:existingDeployments  - `description[string]`: Una breve panoramica dell'obiettivo principale e delle caratteristiche principali dell'implementazione. Corrisponde a dc:description  - `documentation[*]`: Collegamenti diretti ai documenti pertinenti (pagina del prodotto, repository del software, specifiche API, ecc.) Corrisponde a schema:documentation  - `domain[*]`: Il/i dominio/i, il/i settore/i o l'industria/le industrie per cui lo strumento è rilevante  - `exportFormats[*]`: Formati di dati in cui il servizio può esportare i modelli di dati (elenco di tipi MIME). Corrisponde a dcat:mediaType.  - `functionalApplicationArea[*]`: Le applicazioni a cui è destinato lo strumento  - `geographicalApplicationArea[*]`: L'area geografica a cui lo strumento è destinato (ad esempio, globale, Europa).  - `governanceFeatures[string]`: Funzionalità di governance, come il controllo degli accessi basato sui ruoli e la gestione dei flussi di lavoro.  - `hasVersion[string]`: Le versioni dell'implementazione. I valori devono essere conformi a SemVer 2.0. Corrisponde a dc:hasVersion  - `id[*]`: Identificatore univoco dell'entità  - `image[*]`: Immagini o schermate rilevanti dell'interfaccia utente dello strumento. Corrisponde a schema:image  - `importFormats[*]`: Formati di dati che il servizio può importare per creare un modello di dati (elenco di tipi MIME). Corrisponde a dcat:mediatype.  - `keywords[*]`: Parole chiave che categorizzano lo strumento, preferibilmente da un vocabolario controllato. Corrisponde a schema:keywords  - `license[*]`: Collegamenti ai dettagli della licenza per l'accesso e l'uso dello strumento. Corrisponde a schema:licenza  - `licenseDeclared[*]`: Il tipo di licenza ricercabile meccanicamente. Il valore deve essere conforme all'elenco delle licenze SPDX (https://spdx.org/licenses/). Corrisponde a spdx.org:licenseDeclared  - `maintainer[object]`: L'organizzazione che mantiene l'implementazione. Corrisponde a schema:maintainer  	- `logo[uri]`: URL del logo dell'organizzazione. Corrisponde a schema:logo    
	- `name[string]`: Nome dell'organizzazione    
	- `url[uri]`: URL del sito web dell'organizzazione    
- `mappingFunctionalities[string]`: Descrive se il servizio fornisce funzionalità di mappatura tra diversi modelli di dati.  - `publicationAccessibility[*]`: Metodi utilizzati per pubblicare e rendere accessibili i vocabolari (ad esempio, endpoint SPARQL). Corrisponde a dcat:accessService.  - `referenceDatasetManagement[string]`: Descrive come il servizio gestisce i set di dati di riferimento (liste di codici).  - `similarTools[*]`: Un elenco di strumenti simili o concorrenti  - `supportedStandards[*]`: Elenco di standard formali o industriali specifici che il servizio supporta. Corrisponde a dcterms:conformsTo.  - `supportedSyntaxes[*]`: Sintassi del modello di dati che il servizio può elaborare (ad esempio, OWL, JSON Schema). Corrisponde a dc:format.  - `supportingAttachments[array]`: Ulteriori allegati o link per ulteriori informazioni  - `technologyReadinessLevel[number]`: Il livello di preparazione tecnologica (TRL) dello strumento. Corrisponde a tcat:technologyReadiness  - `title[string]`: Il nome dello strumento/implementazione. Corrisponde a dc:title  - `trlJustification[string]`: Giustificazione del TRL dichiarato. Corrisponde a tcat:technologyReadinessDescription  - `type[string]`: Tipo di entità NGSI. Deve essere VocabularyService.  - `url[uri]`: Un URL a una pagina web con maggiori informazioni sullo strumento. Corrisponde a foaf:homepage o schema:url  - `validationCapabilities[*]`: Specifica se il servizio offre la convalida delle istanze di dati rispetto ai modelli di dati.  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Proprietà richieste  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## Modello di dati descrizione delle proprietà  
Ordinati in ordine alfabetico (clicca per i dettagli)  
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
## Esempi di payload  
#### VocabularyService NGSI-v2 valori-chiave Esempio  
Ecco un esempio di VocabularyService in formato JSON-LD come valori-chiave. Questo è compatibile con NGSI-v2 quando si usa `options=keyValues` e restituisce i dati di contesto di una singola entità.  
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
#### VocabolarioServizio NGSI-v2 normalizzato Esempio  
Ecco un esempio di VocabularyService in formato JSON-LD normalizzato. Questo è compatibile con NGSI-v2 quando non si utilizzano opzioni e restituisce i dati di contesto di una singola entità.  
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
#### VocabularyService Valori chiave NGSI-LD Esempio  
Ecco un esempio di VocabularyService in formato JSON-LD come valori-chiave. Questo è compatibile con NGSI-LD quando si usa `options=keyValues` e restituisce i dati di contesto di una singola entità.  
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
#### VocabularyService NGSI-LD normalizzato Esempio  
Ecco un esempio di VocabularyService in formato JSON-LD normalizzato. Questo è compatibile con NGSI-LD quando non si utilizzano opzioni e restituisce i dati di contesto di una singola entità.  
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
Vedere [FAQ 10](https://smartdatamodels.org/index.php/faqs/) per ottenere una risposta su come gestire le unità di grandezza.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
