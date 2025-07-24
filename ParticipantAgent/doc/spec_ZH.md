<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
实体：参与者代理  
========<!-- /10-Header -->  
<!-- 15-License -->  
[开放许可](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/ParticipantAgent/LICENSE.md)  
[文件自动生成](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
全局描述：**参与者代理（连接器）工具的数据模型。该工具可实现多种服务，如凭证存储、合同协商、传输过程和数据平面。它扩展了基础工具信息模型。  
版本： 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 属性列表  

<sup><sub>[*] 如果属性中没有类型，是因为它可能有多个类型或不同的格式/模式</sub></sup>。  
- `additionalBuildingBlock[*]`: 该工具提供的附加积木功能。对应于 tcat:additionalBuildingBlock  - `additionalBuildingBlockDescription[*]`: 附加功能的文字描述。对应于 tcat:additionalBuildingBlockDescription  - `businessOfferings[*]`: 管理服务、SaaS 或支持等业务产品的描述。对应于 tcat:businessOfferings  - `contractNegotiation[*]`: 合同谈判能力详情。  - `credentialStore[object]`: 凭证存储功能的详细信息。  	- `vcDataModel[*]`: 用于可验证凭据的数据模型详情。    
	- `vcIssuanceAPI[*]`: 用于签发可验证凭据的 API 的详细信息。    
	- `vcPresentationAPI[*]`: 用于签发可验证凭据的数据应用程序接口详情。    
- `dataPlane[array]`: 数据平面功能的详细信息，定义一个或多个数据交换 API。  - `dataspaceBuildingBlock[*]`: 该工具相关的数据空间构件。对应于 tcat:dataspaceBuildingBlock  - `dataspaceProductPurpose[string]`: 描述实施工作如何有助于实现 DSSC 的目标。对应于 tcat:dataspaceProductPurpose  - `dataspaceService[*]`: 该工具实现的特定数据空间服务。对应于 tcat:dataspaceService  - `dataspaceServiceCategory[string]`: 数据空间服务的类别。对应于 tcat:dataspaceServiceCategory  - `dependencies[*]`: 其他工具或组件的依赖性或先决条件  - `deploymentsInOperation[*]`: 工具使用/部署情况概览或链接。对应 tcat:existingDeployments  - `description[string]`: 简要概述实施工作的主要重点和主要特点。对应 dc:description  - `documentation[*]`: 指向相关文档（产品页面、软件库、API 规范等）的直接链接。对应于 schema:documentation  - `domain[*]`: 与该工具相关的领域、部门或行业/实体  - `functionalApplicationArea[*]`: 工具的用途  - `geographicalApplicationArea[*]`: 工具所针对的地理区域（如全球、欧洲）  - `hasVersion[string]`: 实现的版本。值必须符合 SemVer 2.0。对应于 dc:hasVersion  - `id[*]`: 实体的唯一标识符  - `image[*]`: 工具用户界面的相关图片或截图。对应 schema:image  - `keywords[*]`: 对工具进行分类的关键字，最好来自受控词汇表。对应于 schema:keywords  - `license[*]`: 访问和使用工具的许可证详细信息链接。对应于 schema:license  - `licenseDeclared[*]`: 机器可搜索的许可证类型。值必须符合 SPDX 许可证列表 (https://spdx.org/licenses/)。对应 spdx.org:licenseDeclared  - `maintainer[object]`: 维护实施的机构。对应于 schema:maintainer  	- `logo[uri]`: 机构徽标的 URL。对应于 schema:logo    
	- `name[string]`: 组织名称    
	- `url[uri]`: 组织网站的 URL    
- `similarTools[*]`: 类似或竞争工具列表  - `supportingAttachments[array]`: 更多信息的附加附件或链接  - `technologyReadinessLevel[number]`: 工具的技术就绪水平 (TRL)。对应于 tcat:technologyReadiness  - `title[string]`: 工具/实现的名称。对应 dc:title  - `transferProcess[object]`: 转移过程能力的详细信息。  	- `authorization[*]`: 传输过程中使用的授权机制详情。    
	- `protocol[*]`: 定义传输过程的协议细节。    
- `trlJustification[string]`: 声明 TRL 的理由。对应于 tcat:technologyReadinessDescription  - `type[string]`: NGSI 实体类型。它必须是 ParticipantAgent。  - `url[uri]`: 指向有关该工具更多信息的网页的 URL。对应于 foaf:homepage 或 schema:url  <!-- /30-PropertiesList -->  
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
## 有效载荷示例  
#### ParticipantAgent NGSI-v2 密钥值示例  
下面是一个以 JSON-LD 格式作为键值的 ParticipantAgent 示例。当使用 `options=keyValues` 时，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
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
#### ParticipantAgent NGSI-v2 标准化示例  
下面是一个规范化 JSON-LD 格式的参与者代理示例。当不使用选项时，它与 NGSI-v2 兼容，并返回单个实体的上下文数据。  
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
#### 参与者代理 NGSI-LD 密钥值示例  
下面是一个以 JSON-LD 格式作为键值的 ParticipantAgent 示例。当使用 `options=keyValues` 时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
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
#### 参与者代理 NGSI-LD 标准化示例  
下面是一个以 JSON-LD 格式规范化的参与者代理（ParticipantAgent）示例。在不使用选项时，它与 NGSI-LD 兼容，并返回单个实体的上下文数据。  
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
请参阅 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)，获取如何处理幅度单位的答案。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
