


```
definitions:
  LinkedAccountDtl:
    type: object
    properties:
      linkedAccntId:
        type: string
        format: uuid
      last4DigitAcntNbr:
        type: string
      accountNickName:
        type: string
      Status:
        type: string
      verfiedDtm:
        type: string
        format: date-time
      VerifiedMthd:
        type: string

  LinkedAccountDtlResponse:
    type: object
    properties:
      LinkedAccntList:
        type: array
        items:
          $ref: '#/definitions/LinkedAccountDtl'



            ```
