# # CreditNoteResetToOpen200ResponseObjects

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | The creditNote id | [optional] [readonly]
**object_name** | **string** | The creditNote object name | [optional] [readonly] [default to 'CreditNote']
**create** | **\DateTime** | Date of creditNote creation | [optional] [readonly]
**update** | **\DateTime** | Date of last creditNote update | [optional] [readonly]
**credit_note_number** | **string** | The creditNote number | [optional]
**contact** | [**\Itsmind\Sevdesk\Model\ModelCreditNoteResponseContact**](ModelCreditNoteResponseContact.md) |  | [optional]
**credit_note_date** | **\DateTime** | The credit note date | [optional]
**status** | **mixed** |  | [optional]
**header** | **string** | Normally consist of prefix plus the creditNote number | [optional]
**head_text** | **string** | Certain html tags can be used here to format your text | [optional]
**foot_text** | **string** | Certain html tags can be used here to format your text | [optional]
**address_country** | [**\Itsmind\Sevdesk\Model\ModelCreditNoteResponseAddressCountry**](ModelCreditNoteResponseAddressCountry.md) |  | [optional]
**create_user** | [**\Itsmind\Sevdesk\Model\ModelCreditNoteResponseCreateUser**](ModelCreditNoteResponseCreateUser.md) |  | [optional]
**sev_client** | [**\Itsmind\Sevdesk\Model\ModelCreditNoteResponseSevClient**](ModelCreditNoteResponseSevClient.md) |  | [optional]
**delivery_date** | **\DateTime** | Timestamp. This can also be a date range if you also use the attribute deliveryDateUntil | [optional]
**small_settlement** | **bool** | Defines if the client uses the small settlement scheme.      If yes, the creditNote must not contain any vat | [optional]
**contact_person** | [**\Itsmind\Sevdesk\Model\ModelCreditNoteResponseContactPerson**](ModelCreditNoteResponseContactPerson.md) |  | [optional]
**tax_rate** | **string** | Is overwritten by creditNote position tax rates | [optional]
**tax_set** | [**\Itsmind\Sevdesk\Model\ModelCreditNoteResponseTaxSet**](ModelCreditNoteResponseTaxSet.md) |  | [optional]
**tax_text** | **string** | A common tax text would be &#39;Umsatzsteuer 19%&#39; | [optional]
**tax_type** | **string** | Tax type of the creditNote. There are four tax types: 1. default - Umsatzsteuer ausweisen 2. eu - Steuerfreie innergemeinschaftliche Lieferung (Europäische Union) 3. noteu - Steuerschuldnerschaft des Leistungsempfängers (außerhalb EU, z. B. Schweiz) 4. custom - Using custom tax set 5. ss - Not subject to VAT according to §19 1 UStG Tax rates are heavily connected to the tax type used. | [optional]
**send_date** | **\DateTime** | The date the creditNote was sent to the customer | [optional]
**address** | **string** | Complete address of the recipient including name, street, city, zip and country.&lt;br&gt;       Line breaks can be used and will be displayed on the invoice pdf. | [optional]
**currency** | **string** | Currency used in the creditNote. Needs to be currency code according to ISO-4217 | [optional]
**sum_net** | **string** | Net sum of the creditNote | [optional] [readonly]
**sum_tax** | **string** | Tax sum of the creditNote | [optional] [readonly]
**sum_gross** | **string** | Gross sum of the creditNote | [optional] [readonly]
**sum_discounts** | **string** | Sum of all discounts in the creditNote | [optional] [readonly]
**sum_net_foreign_currency** | **string** | Net sum of the creditNote in the foreign currency | [optional] [readonly]
**sum_tax_foreign_currency** | **string** | Tax sum of the creditNote in the foreign currency | [optional] [readonly]
**sum_gross_foreign_currency** | **string** | Gross sum of the creditNote in the foreign currency | [optional] [readonly]
**sum_discounts_foreign_currency** | **string** | Discounts sum of the creditNote in the foreign currency | [optional] [readonly]
**customer_internal_note** | **string** | Internal note of the customer. Contains data entered into field &#39;Referenz/Bestellnummer&#39; | [optional]
**show_net** | **bool** | If true, the net amount of each position will be shown on the creditNote. Otherwise gross amount | [optional]
**send_type** | **string** | Type which was used to send the creditNote. IMPORTANT: Please refer to the creditNote section of the       *     API-Overview to understand how this attribute can be used before using it! | [optional]
**credit_note_type** | **string** | Type of the creditNote. For more information on the different types, check      &lt;a href&#x3D;&#39;https://api.sevdesk.de/#section/Types-and-status-of-credit-notes&#39;&gt;this&lt;/a&gt;  . | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)