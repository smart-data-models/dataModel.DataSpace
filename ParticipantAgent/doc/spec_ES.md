<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entidad: ParticipantAgent  
=========================<!-- /10-Header -->  
<!-- 15-License -->  
[Licencia abierta](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/ParticipantAgent/LICENSE.md)  
[documento generado automáticamente](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Descripción global: **Un modelo de datos para una herramienta de Agente Participante (Conector). Esta herramienta puede implementar múltiples servicios como Credential Store, Contract Negotiation, Transfer Process y Data Plane. Amplía el modelo básico ToolInformation.**  
versión: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Lista de propiedades  

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>.  
- `additionalBuildingBlock[*]`: Funciones adicionales de building blocks que ofrece esta herramienta. Corresponde a tcat:additionalBuildingBlock  - `additionalBuildingBlockDescription[*]`: Descripción textual de las funcionalidades adicionales. Corresponde a tcat:additionalBuildingBlockDescription  - `businessOfferings[*]`: Descripción de ofertas de negocio como servicios gestionados, SaaS o soporte. Corresponde a tcat:businessOfferings  - `contractNegotiation[*]`: Detalles de las capacidades de negociación de contratos.  - `credentialStore[object]`: Detalles de las capacidades del almacén de credenciales.  	- `vcDataModel[*]`: Detalles del modelo o modelos de datos utilizados para las credenciales verificables.    
	- `vcIssuanceAPI[*]`: Detalles de la(s) API(s) utilizada(s) para emitir credenciales verificables.    
	- `vcPresentationAPI[*]`: Detalles de la(s) API(s) de datos utilizada(s) para expedir credenciales verificables.    
- `dataPlane[array]`: Detalles de las capacidades del plano de datos, definiendo una o más API de intercambio de datos.  - `dataspaceBuildingBlock[*]`: Bloque o bloques de construcción del espacio de datos con los que está relacionada esta herramienta. Corresponde a tcat:dataspaceBuildingBlock  - `dataspaceProductPurpose[string]`: Descripción de cómo contribuye la aplicación a los objetivos del DSSC. Corresponde a tcat:dataspaceProductPurpose  - `dataspaceService[*]`: Servicio(s) específico(s) del espacio de datos que implementa esta herramienta. Corresponde a tcat:dataspaceService  - `dataspaceServiceCategory[string]`: La categoría del servicio de espacio de datos. Corresponde a tcat:dataspaceServiceCategory  - `dependencies[*]`: Dependencias o requisitos previos de otras herramientas o componentes  - `deploymentsInOperation[*]`: Visión general o enlaces al uso/despliegue de la herramienta en operaciones. Corresponde a tcat:existingDeployments  - `description[string]`: Breve descripción del enfoque principal y las características clave de la aplicación. Corresponde a dc:description  - `documentation[*]`: Enlaces directos a los documentos pertinentes (página del producto, repositorio de software, especificación de la API, etc.). Corresponde a schema:documentation  - `domain[*]`: Ámbito(s), sector(es) o industria(s) para los que es pertinente la herramienta  - `functionalApplicationArea[*]`: Las aplicaciones a las que se destina la herramienta  - `geographicalApplicationArea[*]`: La región geográfica a la que está destinada la herramienta (por ejemplo, mundial, Europa).  - `hasVersion[string]`: Las versiones de la aplicación. Los valores deben ajustarse a SemVer 2.0. Corresponde a dc:hasVersion  - `id[*]`: Identificador único de la entidad  - `image[*]`: Imágenes o capturas de pantalla relevantes de la interfaz de usuario de la herramienta. Corresponde a schema:image  - `keywords[*]`: Palabras clave que categorizan la herramienta, preferiblemente de un vocabulario controlado. Corresponde a schema:keywords  - `license[*]`: Enlaces a los detalles de la licencia para acceder y utilizar la herramienta. Corresponde a schema:license  - `licenseDeclared[*]`: El tipo de licencia de búsqueda automática. El valor debe ajustarse a la lista de licencias SPDX (https://spdx.org/licenses/). Corresponde a spdx.org:licenseDeclared  - `maintainer[object]`: La organización que mantiene la implementación. Corresponde a schema:maintainer  	- `logo[uri]`: URL del logotipo de la organización. Corresponde a schema:logo    
	- `name[string]`: Nombre de la organización    
	- `url[uri]`: URL del sitio web de la organización    
- `similarTools[*]`: Una lista de herramientas similares o competidoras  - `supportingAttachments[array]`: Anexos adicionales o enlaces para más información  - `technologyReadinessLevel[number]`: Nivel de preparación tecnológica (TRL) de la herramienta. Corresponde a tcat:technologyReadiness  - `title[string]`: Nombre de la herramienta/implementación. Corresponde a dc:title  - `transferProcess[object]`: Detalles de las capacidades del proceso de transferencia.  	- `authorization[*]`: Detalles de los mecanismos de autorización utilizados tras el proceso de transferencia.    
	- `protocol[*]`: Detalles del protocolo o protocolos que definen el proceso de transferencia.    
- `trlJustification[string]`: Justificación del TRL declarado. Corresponde a tcat:technologyReadinessDescription  - `type[string]`: Tipo de entidad NGSI. Tiene que ser ParticipantAgent.  - `url[uri]`: URL a una página web con más información sobre la herramienta. Corresponde a foaf:homepage o schema:url  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Propiedades requeridas  
- `id`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-NotesYaml -->  
<!-- /40-NotesYaml -->  
<!-- 50-DataModelHeader -->  
## Descripción de las propiedades del modelo de datos  
Ordenados alfabéticamente (pulse para más detalles)  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
ParticipantAgent:    
  description: A data model for a Participant Agent (Connector) tool. This tool can implement multiple services like Credential Store, Contract Negotiation, Transfer Process, and Data Plane. It extends the base ToolInformation model.    
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
    contractNegotiation:    
      anyOf:    
        - items:    
            properties:    
              conformsTo:    
                description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                items:    
                  type: string    
                type: array    
                x-ngsi:    
                  type: Property    
              homepage:    
                description: Homepage of the specification. Corresponds to foaf:homepage    
                format: uri    
                type: string    
                x-ngsi:    
                  type: Property    
              name:    
                description: Name of the specification or standard. Corresponds to dc:title    
                type: string    
                x-ngsi:    
                  type: Property    
              standardizedBy:    
                description: The standardization body. Corresponds to tcat:standardizedBy    
                type: string    
                x-ngsi:    
                  type: Property    
            type: object    
          type: array    
        - properties:    
            conformsTo:    
              description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
              items:    
                type: string    
              type: array    
              x-ngsi:    
                type: Property    
            homepage:    
              description: Homepage of the specification. Corresponds to foaf:homepage    
              format: uri    
              type: string    
              x-ngsi:    
                type: Property    
            name:    
              description: Name of the specification or standard. Corresponds to dc:title    
              type: string    
              x-ngsi:    
                type: Property    
            standardizedBy:    
              description: The standardization body. Corresponds to tcat:standardizedBy    
              type: string    
              x-ngsi:    
                type: Property    
          type: object    
      description: Details of the contract negotiation capabilities.    
      minItems: 1    
      x-ngsi:    
        type: Property    
    credentialStore:    
      description: Details of the credential store capabilities.    
      properties:    
        vcDataModel:    
          anyOf:    
            - items:    
                properties:    
                  conformsTo:    
                    description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                    items:    
                      type: string    
                    type: array    
                    x-ngsi:    
                      type: Property    
                  homepage:    
                    description: Homepage of the specification. Corresponds to foaf:homepage    
                    format: uri    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  name:    
                    description: Name of the specification or standard. Corresponds to dc:title    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  standardizedBy:    
                    description: The standardization body. Corresponds to tcat:standardizedBy    
                    type: string    
                    x-ngsi:    
                      type: Property    
                type: object    
              type: array    
            - conformsTo:    
                description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                items:    
                  type: string    
                type: array    
                x-ngsi:    
                  type: Property    
              homepage:    
                description: Homepage of the specification. Corresponds to foaf:homepage    
                format: uri    
                type: string    
                x-ngsi:    
                  type: Property    
              name:    
                description: Name of the specification or standard. Corresponds to dc:title    
                type: string    
                x-ngsi:    
                  type: Property    
              standardizedBy:    
                description: The standardization body. Corresponds to tcat:standardizedBy    
                type: string    
                x-ngsi:    
                  type: Property    
          description: Details of data model(s) used for Verifiable Credentials.    
          minItems: 1    
          x-ngsi:    
            type: Property    
        vcIssuanceAPI:    
          anyOf:    
            - items:    
                properties:    
                  conformsTo:    
                    description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                    items:    
                      type: string    
                    type: array    
                    x-ngsi:    
                      type: Property    
                  homepage:    
                    description: Homepage of the specification. Corresponds to foaf:homepage    
                    format: uri    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  name:    
                    description: Name of the specification or standard. Corresponds to dc:title    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  standardizedBy:    
                    description: The standardization body. Corresponds to tcat:standardizedBy    
                    type: string    
                    x-ngsi:    
                      type: Property    
                type: object    
              type: array    
            - conformsTo:    
                description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                items:    
                  type: string    
                type: array    
                x-ngsi:    
                  type: Property    
              homepage:    
                description: Homepage of the specification. Corresponds to foaf:homepage    
                format: uri    
                type: string    
                x-ngsi:    
                  type: Property    
              name:    
                description: Name of the specification or standard. Corresponds to dc:title    
                type: string    
                x-ngsi:    
                  type: Property    
              standardizedBy:    
                description: The standardization body. Corresponds to tcat:standardizedBy    
                type: string    
                x-ngsi:    
                  type: Property    
          description: Details of the API(s) used for issuing Verifiable Credentials.    
          minItems: 1    
          x-ngsi:    
            type: Property    
        vcPresentationAPI:    
          anyOf:    
            - items:    
                properties:    
                  conformsTo:    
                    description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                    items:    
                      type: string    
                    type: array    
                    x-ngsi:    
                      type: Property    
                  homepage:    
                    description: Homepage of the specification. Corresponds to foaf:homepage    
                    format: uri    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  name:    
                    description: Name of the specification or standard. Corresponds to dc:title    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  standardizedBy:    
                    description: The standardization body. Corresponds to tcat:standardizedBy    
                    type: string    
                    x-ngsi:    
                      type: Property    
                type: object    
              type: array    
            - conformsTo:    
                description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                items:    
                  type: string    
                type: array    
                x-ngsi:    
                  type: Property    
              homepage:    
                description: Homepage of the specification. Corresponds to foaf:homepage    
                format: uri    
                type: string    
                x-ngsi:    
                  type: Property    
              name:    
                description: Name of the specification or standard. Corresponds to dc:title    
                type: string    
                x-ngsi:    
                  type: Property    
              standardizedBy:    
                description: The standardization body. Corresponds to tcat:standardizedBy    
                type: string    
                x-ngsi:    
                  type: Property    
          description: Details of data API(s) used for issuing Verifiable Credentials.    
          minItems: 1    
          x-ngsi:    
            type: Property    
      type: object    
      x-ngsi:    
        type: Property    
    dataPlane:    
      description: Details of the data plane capabilities, defining one or more data exchange APIs.    
      items:    
        properties:    
          accepts:    
            anyOf:    
              - items:    
                  type: string    
                type: array    
              - type: string    
            description: List of MIME types the data plane can accept for import. Corresponds to HTTP Accept header.    
            type: array    
            x-ngsi:    
              type: Property    
          apiSpecification:    
            anyOf:    
              - items:    
                  properties:    
                    conformsTo:    
                      description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                      items:    
                        type: string    
                      type: array    
                      x-ngsi:    
                        type: Property    
                    homepage:    
                      description: Homepage of the specification. Corresponds to foaf:homepage    
                      format: uri    
                      type: string    
                      x-ngsi:    
                        type: Property    
                    name:    
                      description: Name of the specification or standard. Corresponds to dc:title    
                      type: string    
                      x-ngsi:    
                        type: Property    
                    standardizedBy:    
                      description: The standardization body. Corresponds to tcat:standardizedBy    
                      type: string    
                      x-ngsi:    
                        type: Property    
                  type: object    
                type: array    
              - properties:    
                  conformsTo:    
                    description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                    items:    
                      type: string    
                    type: array    
                    x-ngsi:    
                      type: Property    
                  homepage:    
                    description: Homepage of the specification. Corresponds to foaf:homepage    
                    format: uri    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  name:    
                    description: Name of the specification or standard. Corresponds to dc:title    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  standardizedBy:    
                    description: The standardization body. Corresponds to tcat:standardizedBy    
                    type: string    
                    x-ngsi:    
                      type: Property    
                type: object    
            description: Details of API specification mechanisms used on the data plane.    
            minItems: 1    
            x-ngsi:    
              type: Property    
          contentType:    
            anyOf:    
              - items:    
                  type: string    
                type: array    
              - type: string    
            description: List of MIME types the data plane can export. Corresponds to HTTP Content-Type header.    
            type: array    
            x-ngsi:    
              type: Property    
          openAPI:    
            anyOf:    
              - items:    
                  format: uri    
                  type: string    
                type: array    
              - format: uri    
                type: string    
            description: Link(s) to a machine-readable interface of the API. Corresponds to tcat:openAPI.    
            type: array    
            x-ngsi:    
              type: Property    
        type: object    
      type: array    
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
    similarTools:    
      anyOf:    
        - items:    
            type: string    
          type: array    
        - type: string    
      description: A list of similar or competing tools    
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
    transferProcess:    
      description: Details of the transfer process capabilities.    
      properties:    
        authorization:    
          anyOf:    
            - items:    
                properties:    
                  conformsTo:    
                    description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                    items:    
                      type: string    
                    type: array    
                    x-ngsi:    
                      type: Property    
                  homepage:    
                    description: Homepage of the specification. Corresponds to foaf:homepage    
                    format: uri    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  name:    
                    description: Name of the specification or standard. Corresponds to dc:title    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  standardizedBy:    
                    description: The standardization body. Corresponds to tcat:standardizedBy    
                    type: string    
                    x-ngsi:    
                      type: Property    
                type: object    
              type: array    
            - conformsTo:    
                description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                items:    
                  type: string    
                type: array    
                x-ngsi:    
                  type: Property    
              homepage:    
                description: Homepage of the specification. Corresponds to foaf:homepage    
                format: uri    
                type: string    
                x-ngsi:    
                  type: Property    
              name:    
                description: Name of the specification or standard. Corresponds to dc:title    
                type: string    
                x-ngsi:    
                  type: Property    
              standardizedBy:    
                description: The standardization body. Corresponds to tcat:standardizedBy    
                type: string    
                x-ngsi:    
                  type: Property    
          description: Details of authorization mechanisms used behind the transfer process.    
          minItems: 1    
          x-ngsi:    
            type: Property    
        protocol:    
          anyOf:    
            - items:    
                properties:    
                  conformsTo:    
                    description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                    items:    
                      type: string    
                    type: array    
                    x-ngsi:    
                      type: Property    
                  homepage:    
                    description: Homepage of the specification. Corresponds to foaf:homepage    
                    format: uri    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  name:    
                    description: Name of the specification or standard. Corresponds to dc:title    
                    type: string    
                    x-ngsi:    
                      type: Property    
                  standardizedBy:    
                    description: The standardization body. Corresponds to tcat:standardizedBy    
                    type: string    
                    x-ngsi:    
                      type: Property    
                type: object    
              type: array    
            - conformsTo:    
                description: Version(s) of the specification it conforms to. Corresponds to dcterms:conformsTo    
                items:    
                  type: string    
                type: array    
                x-ngsi:    
                  type: Property    
              homepage:    
                description: Homepage of the specification. Corresponds to foaf:homepage    
                format: uri    
                type: string    
                x-ngsi:    
                  type: Property    
              name:    
                description: Name of the specification or standard. Corresponds to dc:title    
                type: string    
                x-ngsi:    
                  type: Property    
              standardizedBy:    
                description: The standardization body. Corresponds to tcat:standardizedBy    
                type: string    
                x-ngsi:    
                  type: Property    
          description: Details of protocol(s) defining the transfer process.    
          minItems: 1    
          x-ngsi:    
            type: Property    
      type: object    
      x-ngsi:    
        type: Property    
    trlJustification:    
      description: Justification for the declared TRL. Corresponds to tcat:technologyReadinessDescription    
      type: string    
      x-ngsi:    
        type: Property    
    type:    
      description: NGSI entity type. It has to be ParticipantAgent.    
      enum:    
        - ParticipantAgent    
      type: string    
      x-ngsi:    
        type: Property    
    url:    
      description: A URL to a webpage with more information about the tool. Corresponds to foaf:homepage or schema:url    
      format: uri    
      type: string    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
  type: object    
  x-derived-from: ''    
  x-disclaimer: Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2025 Contributors to Smart Data Models Program    
  x-license-url: https://github.com/smart-data-models/dataModel.DataSpace/blob/master/ParticipantAgent/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.DataSpace/ParticipantAgent/schema.json    
  x-model-tags: ''    
  x-version: 0.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## Ejemplo de carga útil  
#### ParticipantAgent NGSI-v2 key-values Ejemplo  
Aquí hay un ejemplo de un ParticipantAgent en formato JSON-LD como key-values. Esto es compatible con NGSI-v2 cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:ParticipantAgentt:FIWARE-DSC-2.28.0",  
  "type": "ParticipantAgent",  
  "title": "FIWARE Data Space Connector",  
  "description": "An integrated suite of components implementing DSBA recommendations",  
  "url": "https://github.com/FIWARE/data-space-connector",  
  "hasVersion":  "2.28.0",  
  "maintainer": {  
    "name": "FIWARE Foundation"  
  },  
  "dataspaceProductPurpose": "To provide a ready-to-use component for participants to join and interact within a data space.",  
  "documentation": [  
    "https://github.com/FIWARE/data-space-connector/blob/main/README.md"  
  ],  
  "license": [  
    "https://github.com/FIWARE/data-space-connector/blob/main/LICENSE"  
  ],  
  "licenseDeclared": [  
    "MIT"  
  ],  
  "dataspaceServiceCategory": "Participant Agent services",  
  "dataspaceService": [  
    "Credential Store",  
    "Contract Negotiation",  
    "Transfer Process",  
    "Data Plane"  
  ],  
  "dataspaceBuildingBlock": [  
    "Identity Management",  
    "Contract and Usage Policies",  
    "Data Exchange"  
  ],  
  "technologyReadinessLevel": 8,  
  "credentialStore": {  
    "vcDataModel": {  
      "name": "Verifiable Credentials Data Model",  
      "standardizedBy": "W3C",  
      "conformsTo": [  
        "1.1",  
        "2.0"  
      ],  
      "homepage": "https://www.w3.org/TR/vc-data-model/"  
    },  
    "vcIssuanceAPI": {  
      "name": "OpenID for Verifiable Credential Issuance",  
      "standardizedBy": "OpenID",  
      "conformsTo": [  
        "1.0.15"  
      ],  
      "homepage": "https://openid.net/specs/openid-4-verifiable-credential-issuance-1_0.html"  
    },  
    "vcPresentationAPI": {  
      "name": "OpenID for Verifiable Presentations",  
      "standardizedBy": "OpenID",  
      "conformsTo": [  
        "1.0"  
      ],  
      "homepage": "https://openid.net/specs/openid-4-verifiable-presentations-1_0.html"  
    }  
  },  
  "contractNegotiation": {  
    "name": "Agreement Management API",  
    "standardizedBy": "TMForum",  
    "conformsTo": [  
      "5.0.0"  
    ],  
    "homepage": "https://www.tmforum.org/oda/open-apis/agreement"  
  },  
  "transferProcess": {  
    "protocol": {  
      "name": "Dataspace Protocol",  
      "standardizedBy": "DSP",  
      "conformsTo": [  
        "2024-1"  
      ],  
      "homepage": "https://docs.internationaldataspaces.org/dataspace-protocol/"  
    },  
    "authorization": {  
      "name": "ODRL",  
      "standardizedBy": "W3C",  
      "conformsTo": [  
        "2.2"  
      ],  
      "homepage": "https://www.w3.org/TR/odrl-model/"  
    }  
  },  
  "dataPlane": [  
    {  
      "apiSpecification": {  
        "name": "NGSI-LD",  
        "standardizedBy": "ETSI",  
        "conformsTo": [  
          "1.8.1",  
          "1.9.1"  
        ],  
        "homepage": "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.09.01_60/gs_CIM009v010901p.pdf"  
      },  
      "accepts": [  
        "application/json",  
        "application/ld+json"  
      ],  
      "contentType": [  
        "application/json",  
        "application/ld+json",  
        "application/geo+json"  
      ],  
      "openAPI": [  
        "https://forge.etsi.org/rep/cim/ngsi-ld-openapi/-/raw/v1.9.1/ngsi-ld-api-v1.9.1.yaml"  
      ]  
    },  
    {  
      "apiSpecification": {  
        "name": "HTTP File Download",  
        "standardizedBy": "IETF",  
        "conformsTo": [  
          "RFC7231"  
        ],  
        "homepage": "https://tools.ietf.org/html/rfc7231"  
      },  
      "accepts": [],  
      "contentType": [  
        "image/jpeg",  
        "image/png"  
      ]  
    }  
  ]  
}  
```  
</details>  
#### ParticipantAgent NGSI-v2 normalizado Ejemplo  
He aquí un ejemplo de ParticipantAgent en formato JSON-LD normalizado. Esto es compatible con NGSI-v2 cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:ParticipantAgent:FIWARE-DSC-2.28.0",  
  "type": "ParticipantAgent",  
  "title": {  
    "type": "Text",  
    "value": "FIWARE Data Space Connector"  
  },  
  "description": {  
    "type": "Text",  
    "value": "An integrated suite of components implementing DSBA recommendations"  
  },  
  "url": {  
    "type": "URL",  
    "value": "https:/github.com/FIWARE/data-space-connector"  
  },  
  "hasVersion": {  
    "type": "Text",  
    "value": "2.28.0"  
  },  
  "maintainer": {  
    "type": "StructuredValue",  
    "value": {  
      "name": "FIWARE Foundation"  
    }  
  },  
  "dataspaceProductPurpose": {  
    "type": "Text",  
    "value": "To provide a ready-to-use component for participants to join and interact within a data space."  
  },  
  "documentation": {  
    "type": "URL",  
    "value": "https://github.com/FIWARE/data-space-connector/blob/main/README.md"  
  },  
  "license": {  
    "type": "URL",  
    "value": "https://github.com/FIWARE/data-space-connector/blob/main/LICENSE"  
  },  
  "licenseDeclared": {  
    "type": "Text",  
    "value": "MIT"  
  },  
  "dataspaceServiceCategory": {  
    "type": "Text",  
    "value": "Participant Agent services"  
  },  
  "dataspaceService": {  
    "type": "array",  
    "value": [  
      "Credential Store",  
      "Contract Negotiation",  
      "Transfer Process",  
      "Data Plane"  
    ]  
  },  
  "dataspaceBuildingBlock": {  
    "type": "array",  
    "value": [  
      "Identity Management",  
      "Contract and Usage Policies",  
      "Data Exchange"  
    ]  
  },  
  "technologyReadinessLevel": {  
    "type": "Number",  
    "value": 8  
  },  
  "credentialStore": {  
    "type": "StructuredValue",  
    "value": {  
      "vcDataModel": {  
        "name": "Verifiable Credentials Data Model",  
        "standardizedBy": {  
          "type": "Property",  
          "value": "W3C",  
          "conformsTo": [  
            "1.1",  
            "2.0"  
          ],  
          "homepage": "https://www.w3.org/TR/vc-data-model/"  
        },  
        "vcIssuanceAPI": {  
          "name": "OpenID for Verifiable Credential Issuance",  
          "standardizedBy": "OpenID",  
          "conformsTo": "1.0.15",  
          "homepage": "https://openid.net/specs/openid-4-verifiable-credential-issuance-1_0.html"  
        },  
        "vcPresentationAPI": {  
          "name": "OpenID for Verifiable Presentations",  
          "standardizedBy": "OpenID",  
          "conformsTo": "1.0",  
          "homepage": "https://openid.net/specs/openid-4-verifiable-presentations-1_0.html"  
        }  
      },  
      "contractNegotiation": {  
        "type": "StructuredValue",  
        "value": {  
          "name": "Agreement Management API",  
          "standardizedBy": "TMForum",  
          "conformsTo": "5.0.0",  
          "homepage": "https://www.tmforum.org/oda/open-apis/agreement"  
        }  
      },  
      "transferProcess": {  
        "type": "StructuredValue",  
        "value": {  
          "protocol": {  
            "name": "Dataspace Protocol",  
            "standardizedBy": "DSP",  
            "conformsTo": "2024-1",  
            "homepage": "https://docs.internationaldataspaces.org/dataspace-protocol/"  
          },  
          "authorization": {  
            "name": "ODRL",  
            "standardizedBy": "W3C",  
            "conformsTo": "2.2",  
            "homepage": "https://www.w3.org/TR/odrl-model/"  
          }  
        }  
      },  
      "dataPlane": {  
        "type": "StructuredValue",  
        "value": [  
          {  
            "apiSpecification": {  
              "name": "NGSI-LD",  
              "standardizedBy": "ETSI",  
              "conformsTo": [  
                "1.8.1",  
                "1.9.1"  
              ],  
              "homepage": "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.09.01_60/gs_CIM009v010901p.pdf"  
            },  
            "accepts": [  
              "application/json",  
              "application/ld+json"  
            ],  
            "contentType": [  
              "application/json",  
              "application/ld+json",  
              "application/geo+json"  
            ],  
            "openAPI": "https://forge.etsi.org/rep/cim/ngsi-ld-openapi/-/raw/v1.9.1/ngsi-ld-api-v1.9.1.yaml"  
          },  
          {  
            "apiSpecification": {  
              "name": "HTTP File Download",  
              "standardizedBy": "IETF",  
              "conformsTo": "RFC7231",  
              "homepage": "https:/tools.ietf.org/html/rfc7231"  
            },  
            "accepts": "*",  
            "contentType": [  
              "image/jpeg",  
              "image/png"  
            ]  
          }  
        ]  
      }  
    }  
  }  
}  
```  
</details>  
#### ParticipantAgent NGSI-LD key-values Ejemplo  
Aquí hay un ejemplo de un ParticipantAgent en formato JSON-LD como key-values. Esto es compatible con NGSI-LD cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:ParticipantAgent:FIWARE-DSC-2.28.0",  
  "type": "ParticipantAgent",  
  "title": "FIWARE Data Space Connector",  
  "description": "An integrated suite of components implementing DSBA recommendations",  
  "url": "https://github.com/FIWARE/data-space-connector",  
  "hasVersion": "2.28.0",  
  "maintainer": {  
    "name": "FIWARE Foundation"  
  },  
  "dataspaceProductPurpose": "To provide a ready-to-use component for participants to join and interact within a data space.",  
  "documentation": [  
    "https://github.com/FIWARE/data-space-connector/blob/main/README.md"  
  ],  
  "license": [  
    "https://github.com/FIWARE/data-space-connector/blob/main/LICENSE"  
  ],  
  "licenseDeclared": [  
    "MIT"  
  ],  
  "dataspaceServiceCategory": "Participant Agent services",  
  "dataspaceService": [  
    "Credential Store",  
    "Contract Negotiation",  
    "Transfer Process",  
    "Data Plane"  
  ],  
  "dataspaceBuildingBlock": [  
    "Identity Management",  
    "Contract and Usage Policies",  
    "Data Exchange"  
  ],  
  "technologyReadinessLevel": 8,  
  "credentialStore": {  
    "vcDataModel": {  
      "name": "Verifiable Credentials Data Model",  
      "standardizedBy": "W3C",  
      "conformsTo": [  
        "1.1",  
        "2.0"  
      ],  
      "homepage": "https://www.w3.org/TR/vc-data-model/"  
    },  
    "vcIssuanceAPI": {  
      "name": "OpenID for Verifiable Credential Issuance",  
      "standardizedBy": "OpenID",  
      "conformsTo": [  
        "1.0.15"  
      ],  
      "homepage": "https://openid.net/specs/openid-4-verifiable-credential-issuance-1_0.html"  
    },  
    "vcPresentationAPI": {  
      "name": "OpenID for Verifiable Presentations",  
      "standardizedBy": "OpenID",  
      "conformsTo": [  
        "1.0"  
      ],  
      "homepage": "https://openid.net/specs/openid-4-verifiable-presentations-1_0.html"  
    }  
  },  
  "contractNegotiation": {  
    "name": "Agreement Management API",  
    "standardizedBy": "TMForum",  
    "conformsTo": [  
      "5.0.0"  
    ],  
    "homepage": "https://www.tmforum.org/oda/open-apis/agreement"  
  },  
  "transferProcess": {  
    "protocol": {  
      "name": "Dataspace Protocol",  
      "standardizedBy": "DSP",  
      "conformsTo": [  
        "2024-1"  
      ],  
      "homepage": "https://docs.internationaldataspaces.org/dataspace-protocol/"  
    },  
    "authorization": {  
      "name": "ODRL",  
      "standardizedBy": "W3C",  
      "conformsTo": [  
        "2.2"  
      ],  
      "homepage": "https://www.w3.org/TR/odrl-model/"  
    }  
  },  
  "dataPlane": [  
    {  
      "apiSpecification": {  
        "name": "NGSI-LD",  
        "standardizedBy": "ETSI",  
        "conformsTo": [  
          "1.8.1",  
          "1.9.1"  
        ],  
        "homepage": "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.09.01_60/gs_CIM009v010901p.pdf"  
      },  
      "accepts": [  
        "application/json",  
        "application/ld+json"  
      ],  
      "contentType": [  
        "application/json",  
        "application/ld+json",  
        "application/geo+json"  
      ],  
      "openAPI": [  
        "https://forge.etsi.org/rep/cim/ngsi-ld-openapi/-/raw/v1.9.1/ngsi-ld-api-v1.9.1.yaml"  
      ]  
    },  
    {  
      "apiSpecification": {  
        "name": "HTTP File Download",  
        "standardizedBy": "IETF",  
        "conformsTo": [  
          "RFC7231"  
        ],  
        "homepage": "https://tools.ietf.org/html/rfc7231"  
      },  
      "accepts": [],  
      "contentType": [  
        "image/jpeg",  
        "image/png"  
      ]  
    }  
  ],  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.Dataspace/master/context.jsonld"  
  ]  
}  
```  
</details>  
#### ParticipantAgent NGSI-LD normalizado Ejemplo  
He aquí un ejemplo de ParticipantAgent en formato JSON-LD normalizado. Esto es compatible con NGSI-LD cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:ParticipantAgent:FIWARE-DSC-2.28.0",  
  "type": "ParticipantAgent",  
  "title": {  
    "type": "Property",  
    "value": "FIWARE Data Space Connector"  
  },  
  "description": {  
    "type": "Property",  
    "value": "An integrated suite of components implementing DSBA recommendations"  
  },  
  "url": {  
    "type": "Property",  
    "value": "https:/github.com/FIWARE/data-space-connector"  
  },  
  "hasVersion": {  
    "type": "Property",  
    "value": "2.28.0"  
  },  
  "maintainer": {  
    "type": "Property",  
    "value": {  
      "name": "FIWARE Foundation"  
    }  
  },  
  "dataspaceProductPurpose": {  
    "type": "Property",  
    "value": "To provide a ready-to-use component for participants to join and interact within a data space."  
  },  
  "documentation": {  
    "type": "Property",  
    "value": "https://github.com/FIWARE/data-space-connector/blob/main/README.md"  
  },  
  "license": {  
    "type": "Property",  
    "value": "https://github.com/FIWARE/data-space-connector/blob/main/LICENSE"  
  },  
  "licenseDeclared": {  
    "type": "Property",  
    "value": "MIT"  
  },  
  "dataspaceServiceCategory": {  
    "type": "Property",  
    "value": "Participant Agent services"  
  },  
  "dataspaceService": {  
    "type": "Property",  
    "value": [  
      "Credential Store",  
      "Contract Negotiation",  
      "Transfer Process",  
      "Data Plane"  
    ]  
  },  
  "dataspaceBuildingBlock": {  
    "type": "Property",  
    "value": [  
      "Identity Management",  
      "Contract and Usage Policies",  
      "Data Exchange"  
    ]  
  },  
  "technologyReadinessLevel": {  
    "type": "Property",  
    "value": 8  
  },  
  "credentialStore": {  
    "type": "Property",  
    "value": {  
      "vcDataModel": {  
        "name": "Verifiable Credentials Data Model",  
        "standardizedBy": {  
          "type": "Property",  
          "value": "W3C",  
          "conformsTo": [  
            "1.1",  
            "2.0"  
          ],  
          "homepage": "https://www.w3.org/TR/vc-data-model/"  
        },  
        "vcIssuanceAPI": {  
          "name": "OpenID for Verifiable Credential Issuance",  
          "standardizedBy": "OpenID",  
          "conformsTo": "1.0.15",  
          "homepage": "https://openid.net/specs/openid-4-verifiable-credential-issuance-1_0.html"  
        },  
        "vcPresentationAPI": {  
          "name": "OpenID for Verifiable Presentations",  
          "standardizedBy": "OpenID",  
          "conformsTo": "1.0",  
          "homepage": "https://openid.net/specs/openid-4-verifiable-presentations-1_0.html"  
        }  
      },  
      "contractNegotiation": {  
        "type": "Property",  
        "value": {  
          "name": "Agreement Management API",  
          "standardizedBy": "TMForum",  
          "conformsTo": "5.0.0",  
          "homepage": "https://www.tmforum.org/oda/open-apis/agreement"  
        }  
      },  
      "transferProcess": {  
        "type": "Property",  
        "value": {  
          "protocol": {  
            "name": "Dataspace Protocol",  
            "standardizedBy": "DSP",  
            "conformsTo": "2024-1",  
            "homepage": "https://docs.internationaldataspaces.org/dataspace-protocol/"  
          },  
          "authorization": {  
            "name": "ODRL",  
            "standardizedBy": "W3C",  
            "conformsTo": "2.2",  
            "homepage": "https://www.w3.org/TR/odrl-model/"  
          }  
        }  
      },  
      "dataPlane": {  
        "type": "Property",  
        "value": [  
          {  
            "apiSpecification": {  
              "name": "NGSI-LD",  
              "standardizedBy": "ETSI",  
              "conformsTo": [  
                "1.8.1",  
                "1.9.1"  
              ],  
              "homepage": "https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.09.01_60/gs_CIM009v010901p.pdf"  
            },  
            "accepts": [  
              "application/json",  
              "application/ld+json"  
            ],  
            "contentType": [  
              "application/json",  
              "application/ld+json",  
              "application/geo+json"  
            ],  
            "openAPI": "https://forge.etsi.org/rep/cim/ngsi-ld-openapi/-/raw/v1.9.1/ngsi-ld-api-v1.9.1.yaml"  
          },  
          {  
            "apiSpecification": {  
              "name": "HTTP File Download",  
              "standardizedBy": "IETF",  
              "conformsTo": "RFC7231",  
              "homepage": "https:/tools.ietf.org/html/rfc7231"  
            },  
            "accepts": "*",  
            "contentType": [  
              "image/jpeg",  
              "image/png"  
            ]  
          }  
        ]  
      }  
    }  
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
Consulte [FAQ 10](https://smartdatamodels.org/index.php/faqs/) para obtener una respuesta sobre cómo tratar las unidades de magnitud.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
