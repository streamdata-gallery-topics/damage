---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Creates a declaration for a locksmithing damage
  description: Creates a declaration for a locksmithing damage
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the policy holders details for the electric damage
      description: Gets the policy holders details for the electric damage
      operationId: getAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holderAssistance
      - detailsthe
      - electric
      - damage
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the policy holders details for the gas damage
      description: Gets the policy holders details for the gas damage
      operationId: getAssistanceV1HomeGas_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holderAssistance
      - detailsthe
      - gaAssistance
      - damage
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the glaziery damage
        declaration
      description: Gets the information linked to the policy holder of the glaziery
        damage declaration
      operationId: getAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the home appliance
        damage declaration
      description: Gets the information linked to the policy holder of the home appliance
        damage declaration
      operationId: getAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      description: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      operationId: getAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information related to each the policy holder of the water
        damage declaration
      description: Gets the information related to each the policy holder of the water
        damage declaration
      operationId: getAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - related
      - to
      - each
      - the
      - policy
      - holder
      - of
      - the
      - water
      - damage
      - Declarations
  /assistance/v1/home/electric_damage/declarations:
    post:
      summary: Create a declaration for an electric damage
      description: Create a declaration for an electric damage
      operationId: postAssistanceV1HomeElectric_damageDeclarations
      x-api-path-slug: assistancev1homeelectric-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreateDeclarationsan
      - electric
      - damage
  /assistance/v1/home/gas_damage/declarations:
    post:
      summary: Creates a declaration for a gas damage
      description: Creates a declaration for a gas damage
      operationId: postAssistanceV1HomeGas_damageDeclarations
      x-api-path-slug: assistancev1homegas-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreatesDeclarationsa
      - gaAssistance
      - damage
  /assistance/v1/home/glaziery_damage/declarations:
    post:
      summary: Creates a declaration for a glaziery damage
      description: Creates a declaration for a glaziery damage
      operationId: postAssistanceV1HomeGlaziery_damageDeclarations
      x-api-path-slug: assistancev1homeglaziery-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreatesDeclarationsa
      - glaziery
      - damage
  /assistance/v1/home/home_appliance_damage/declarations:
    post:
      summary: Creates a declaration for a home appliance damage
      description: Creates a declaration for a home appliance damage
      operationId: postAssistanceV1HomeHome_appliance_damageDeclarations
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreatesDeclarationsa
      - home
      - appliance
      - damage
  /assistance/v1/home/locksmithing_damage/declarations:
    post:
      summary: Creates a declaration for a locksmithing damage
      description: Creates a declaration for a locksmithing damage
      operationId: postAssistanceV1HomeLocksmithing_damageDeclarations
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreatesDeclarationsa
      - locksmithing
      - damage
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---