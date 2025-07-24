<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
엔티티: 참가자 에이전트  
=============<!-- /10-Header -->  
<!-- 15-License -->  
[오픈 라이선스](https://github.com/smart-data-models//dataModel.DataSpace/blob/master/ParticipantAgent/LICENSE.md)  
[문서 자동 생성](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
글로벌 설명: **참가자 에이전트(커넥터) 도구의 데이터 모델입니다. 이 도구는 자격 증명 저장소, 계약 협상, 전송 프로세스 및 데이터 플레인과 같은 여러 서비스를 구현할 수 있습니다. 기본 도구 정보 모델을 확장합니다.**  
버전: 0.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## 속성 목록  

<sup><sub>[*] 속성에 유형이 없는 것은 여러 유형 또는 다른 형식/패턴을 가질 수 있기 때문입니다</sub></sup>.  
- `additionalBuildingBlock[*]`: 이 도구에서 제공하는 추가 빌딩 블록 기능입니다. tcat:additionalBuildingBlock에 해당합니다.  - `additionalBuildingBlockDescription[*]`: 추가 기능에 대한 텍스트 설명입니다. tcat:추가 건물 블록 설명에 해당합니다.  - `businessOfferings[*]`: 관리형 서비스, SaaS 또는 지원과 같은 비즈니스 오퍼링에 대한 설명입니다. tcat:비즈니스 오퍼링에 해당함  - `contractNegotiation[*]`: 계약 협상 기능에 대한 세부 정보입니다.  - `credentialStore[object]`: 자격증명 저장소 기능에 대한 세부 정보입니다.  	- `vcDataModel[*]`: 확인 가능한 자격 증명에 사용되는 데이터 모델에 대한 세부 정보입니다.    
	- `vcIssuanceAPI[*]`: 확인 가능한 자격증명 발급에 사용되는 API의 세부 정보입니다.    
	- `vcPresentationAPI[*]`: 확인 가능한 자격증명 발급에 사용되는 데이터 API의 세부 정보입니다.    
- `dataPlane[array]`: 하나 이상의 데이터 교환 API를 정의하는 데이터 플레인 기능에 대한 세부 정보입니다.  - `dataspaceBuildingBlock[*]`: 이 도구와 관련된 데이터 공간 빌딩 블록입니다. tcat:dataspaceBuildingBlock에 해당합니다.  - `dataspaceProductPurpose[string]`: 구현이 DSSC의 목표에 어떻게 기여하는지에 대한 설명입니다. tcat:dataspaceProductPurpose에 해당합니다.  - `dataspaceService[*]`: 이 도구가 구현하는 특정 데이터 공간 서비스입니다. tcat:dataspaceService에 해당합니다.  - `dataspaceServiceCategory[string]`: 데이터 스페이스 서비스의 카테고리입니다. tcat:dataspaceServiceCategory에 해당합니다.  - `dependencies[*]`: 다른 도구 또는 구성 요소에 대한 종속성 또는 전제 조건  - `deploymentsInOperation[*]`: 운영에서 도구의 사용/배포에 대한 개요 또는 링크입니다. tcat:existingDeployments에 해당합니다.  - `description[string]`: 구현의 주요 초점과 주요 기능에 대한 간략한 개요입니다. dc:설명에 해당  - `documentation[*]`: 관련 문서(제품 페이지, 소프트웨어 리포지토리, API 사양 등)로 직접 연결되는 링크입니다. 스키마:문서에 해당  - `domain[*]`: 해당 도구가 관련된 도메인, 섹터 또는 산업 분야  - `functionalApplicationArea[*]`: 도구의 용도가 되는 애플리케이션  - `geographicalApplicationArea[*]`: 도구의 대상 지역(예: 글로벌, 유럽)  - `hasVersion[string]`: 구현 버전입니다. 값은 SemVer 2.0을 준수해야 합니다. dc:hasVersion에 해당합니다.  - `id[*]`: 엔티티의 고유 식별자  - `image[*]`: 도구의 사용자 인터페이스 관련 사진 또는 스크린샷. 스키마:이미지에 해당  - `keywords[*]`: 도구를 분류하는 키워드, 가급적이면 제어된 어휘로 분류합니다. 스키마:키워드에 해당  - `license[*]`: 도구에 액세스하고 사용하기 위한 라이선스 세부 정보에 대한 링크입니다. 스키마:라이선스에 해당  - `licenseDeclared[*]`: 컴퓨터에서 검색 가능한 라이선스 유형입니다. 값은 SPDX 라이선스 목록(https://spdx.org/licenses/)을 준수해야 합니다. spdx.org:licenseDeclared에 해당합니다.  - `maintainer[object]`: 구현을 유지 관리하는 조직입니다. 스키마:유지 관리자에 해당  	- `logo[uri]`: 조직 로고의 URL입니다. 스키마:로고에 해당    
	- `name[string]`: 조직 이름    
	- `url[uri]`: 조직 웹사이트의 URL    
- `similarTools[*]`: 유사하거나 경쟁하는 도구 목록  - `supportingAttachments[array]`: 자세한 정보를 위한 추가 첨부 파일 또는 링크  - `technologyReadinessLevel[number]`: 도구의 기술 준비 수준(TRL)입니다. tcat:technologyReadiness에 해당합니다.  - `title[string]`: 도구/구현의 이름입니다. dc:title에 해당  - `transferProcess[object]`: 전송 프로세스 기능에 대한 자세한 내용입니다.  	- `authorization[*]`: 전송 프로세스 뒤에 사용되는 인증 메커니즘에 대한 세부 정보입니다.    
	- `protocol[*]`: 전송 프로세스를 정의하는 프로토콜의 세부 정보입니다.    
- `trlJustification[string]`: 선언된 TRL에 대한 정당성. tcat:technologyReadinessDescription에 해당합니다.  - `type[string]`: NGSI 엔티티 유형. 참가자 에이전트여야 합니다.  - `url[uri]`: 도구에 대한 자세한 정보가 있는 웹페이지의 URL입니다. foaf:홈페이지 또는 스키마:url에 해당합니다.  <!-- /30-PropertiesList -->  
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
## 페이로드 예시  
#### 참가자 에이전트 NGSI-v2 키 값 예제  
다음은 키 값으로 JSON-LD 형식의 참가자 에이전트의 예입니다. 이는 `옵션=키값`을 사용할 때 NGSI-v2와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
#### 참가자 에이전트 NGSI-v2 정규화 예제  
다음은 정규화된 JSON-LD 형식의 참가자 에이전트의 예입니다. 이는 옵션을 사용하지 않을 때 NGSI-v2와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
#### 참가자 에이전트 NGSI-LD 키 값 예제  
다음은 키 값으로 JSON-LD 형식의 참가자 에이전트의 예입니다. 이는 `옵션=키값`을 사용할 때 NGSI-LD와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
#### 참가자 에이전트 NGSI-LD 정규화 예제  
다음은 정규화된 JSON-LD 형식의 참가자 에이전트의 예입니다. 이는 옵션을 사용하지 않을 때 NGSI-LD와 호환되며 개별 엔티티의 컨텍스트 데이터를 반환합니다.  
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
규모 단위를 다루는 방법에 대한 답변은 [FAQ 10](https://smartdatamodels.org/index.php/faqs/)을 참조하세요.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
