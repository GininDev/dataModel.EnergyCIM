Entity: ExcIEEEAC7B  
===================  
[Open License](https://github.com/smart-data-models//dataModel.EnergyCIM/blob/master/ExcIEEEAC7B/LICENSE.md)  
Global description: **Adapted from CIM data models. The class represents IEEE Std 421.5-2005 type AC7B model. The model represents excitation systems which consist of an ac alternator with either stationary or rotating rectifiers to produce the dc field requirements. It is an upgrade to earlier ac excitation systems, which replace only the controls but retain the ac alternator and diode rectifier bridge.  Reference: IEEE Standard 421.5-2005 Section 6.7.  In the IEEE Standard 421.5 - 2005, the [1 / sT] block is shown as [1 / (1 + sT)], which is incorrect.**  

## List of properties  

- `address`: The mailing address.  - `alternateName`: An alternative name for this item  - `areaServed`: The geographic area where a service or offered item is provided  - `dataProvider`: A sequence of characters identifying the provider of the harmonised data entity.  - `dateCreated`: Entity creation timestamp. This will usually be allocated by the storage platform.  - `dateModified`: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.  - `description`: A description of this item  - `id`: Unique identifier of the entity  - `kc`: Rectifier loading factor proportional to commutating reactance (K). Typical Value = 0.18. Default: 0.0  - `kd`: Demagnetizing factor, a function of exciter alternator reactances (K).  Typical Value = 0.02. Default: 0.0  - `kdr`: Voltage regulator derivative gain (K).  Typical Value = 0. Default: 0.0  - `ke`: Exciter constant related to self-excited field (K).  Typical Value = 1. Default: 0.0  - `kf1`: Excitation control system stabilizer gain (K).  Typical Value = 0.212. Default: 0.0  - `kf2`: Excitation control system stabilizer gain (K).  Typical Value = 0. Default: 0.0  - `kf3`: Excitation control system stabilizer gain (K).  Typical Value = 0. Default: 0.0  - `kia`: Voltage regulator integral gain (K).  Typical Value = 59.69. Default: 0.0  - `kir`: Voltage regulator integral gain (K).  Typical Value = 4.24. Default: 0.0  - `kl`: Exciter field voltage lower limit parameter (K).  Typical Value = 10. Default: 0.0  - `kp`: Potential circuit gain coefficient (K).  Typical Value = 4.96. Default: 0.0  - `kpa`: Voltage regulator proportional gain (K).  Typical Value = 65.36. Default: 0.0  - `kpr`: Voltage regulator proportional gain (K).  Typical Value = 4.24. Default: 0.0  - `location`:   - `name`: The name of this item.  - `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)  - `seeAlso`: list of uri pointing to additional resources about the item  - `seve1`: Exciter saturation function value at the corresponding exciter voltage, V, back of commutating reactance (S[V]).  Typical Value = 0.44. Default: 0.0  - `seve2`: Exciter saturation function value at the corresponding exciter voltage, V, back of commutating reactance (S[V]).  Typical Value = 0.075. Default: 0.0  - `source`: A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.  - `tdr`: Lag time constant (T).  Typical Value = 0. Default: 0  - `te`: Exciter time constant, integration rate associated with exciter control (T).  Typical Value = 1.1. Default: 0  - `tf`: Excitation control system stabilizer time constant (T).  Typical Value = 1. Default: 0  - `type`: NGSI type. It has to be ExcIEEEAC7B  - `vamax`: Maximum voltage regulator output (V).  Typical Value = 1. Default: 0.0  - `vamin`: Minimum voltage regulator output (V).  Typical Value = -0.95. Default: 0.0  - `ve1`: Exciter alternator output voltages back of commutating reactance at which saturation is defined (V) equals V (V).  Typical Value = 6.3. Default: 0.0  - `ve2`: Exciter alternator output voltages back of commutating reactance at which saturation is defined (V).  Typical Value = 3.02. Default: 0.0  - `vemin`: Minimum exciter voltage output (V).  Typical Value = 0. Default: 0.0  - `vfemax`: Exciter field current limit reference (V).  Typical Value = 6.9. Default: 0.0  - `vrmax`: Maximum voltage regulator output (V).  Typical Value = 5.79. Default: 0.0  - `vrmin`: Minimum voltage regulator output (V).  Typical Value = -5.79. Default: 0.0    
Required properties  
This data model is a direct conversion of the Common Information Model (CIM) specified by the IEC61970 standard into smart data models. The python classes this model is based on were developed by these entities Institute for Automation of Complex Power Systems (ACS), EON Energy Research Center (EONERC) and RWTH University Aachen, Germany. some properties can have wrong type. This was the case, pelase raise an issue or send mail to alberto.abella@fiware.org  
## Data Model description of properties  
Sorted alphabetically (click for details)  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
ExcIEEEAC7B:    
  description: 'Adapted from CIM data models. The class represents IEEE Std 421.5-2005 type AC7B model. The model represents excitation systems which consist of an ac alternator with either stationary or rotating rectifiers to produce the dc field requirements. It is an upgrade to earlier ac excitation systems, which replace only the controls but retain the ac alternator and diode rectifier bridge.  Reference: IEEE Standard 421.5-2005 Section 6.7.  In the IEEE Standard 421.5 - 2005, the [1 / sT] block is shown as [1 / (1 + sT)], which is incorrect.'    
  properties:    
    address:    
      description: 'The mailing address.'    
      properties:    
        addressCountry:    
          description: 'Property. The country. For example, Spain. Model:''https://schema.org/Text'''    
          type: string    
        addressLocality:    
          description: 'Property. The locality in which the street address is, and which is in the region. Model:''https://schema.org/Text'''    
          type: string    
        addressRegion:    
          description: 'Property. The region in which the locality is, and which is in the country. Model:''https://schema.org/Text'''    
          type: string    
        areaServed:    
          description: 'Property. The geographic area where a service or offered item is provided. Model:''https://schema.org/Text'''    
          type: string    
        postOfficeBoxNumber:    
          description: 'Property. The post office box number for PO box addresses. For example, Spain. Model:''https://schema.org/Text'''    
          type: string    
        postalCode:    
          description: 'Property. The postal code. For example, Spain. Model:''https://schema.org/Text'''    
          type: string    
        streetAddress:    
          description: 'Property. The street address. Model:''https://schema.org/Text'''    
          type: string    
      type: Property    
    alternateName:    
      description: 'An alternative name for this item'    
      type: Property    
    areaServed:    
      description: 'The geographic area where a service or offered item is provided'    
      type: Property    
      x-ngsi:    
        model: https://schema.org/Text    
    dataProvider:    
      description: 'A sequence of characters identifying the provider of the harmonised data entity.'    
      type: Property    
    dateCreated:    
      description: 'Entity creation timestamp. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: Property    
    dateModified:    
      description: 'Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: Property    
    description:    
      description: 'A description of this item'    
      type: Property    
    id:    
      anyOf: &excieeeac7b_-_properties_-_owner_-_items_-_anyof    
        - description: 'Property. Identifier format of any NGSI entity'    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: 'Property. Identifier format of any NGSI entity'    
          format: uri    
          type: string    
      description: 'Unique identifier of the entity'    
      type: Property    
    kc:    
      description: 'Rectifier loading factor proportional to commutating reactance (K). Typical Value = 0.18. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kd:    
      description: 'Demagnetizing factor, a function of exciter alternator reactances (K).  Typical Value = 0.02. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kdr:    
      description: 'Voltage regulator derivative gain (K).  Typical Value = 0. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    ke:    
      description: 'Exciter constant related to self-excited field (K).  Typical Value = 1. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kf1:    
      description: 'Excitation control system stabilizer gain (K).  Typical Value = 0.212. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kf2:    
      description: 'Excitation control system stabilizer gain (K).  Typical Value = 0. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kf3:    
      description: 'Excitation control system stabilizer gain (K).  Typical Value = 0. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kia:    
      description: 'Voltage regulator integral gain (K).  Typical Value = 59.69. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kir:    
      description: 'Voltage regulator integral gain (K).  Typical Value = 4.24. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kl:    
      description: 'Exciter field voltage lower limit parameter (K).  Typical Value = 10. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kp:    
      description: 'Potential circuit gain coefficient (K).  Typical Value = 4.96. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kpa:    
      description: 'Voltage regulator proportional gain (K).  Typical Value = 65.36. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    kpr:    
      description: 'Voltage regulator proportional gain (K).  Typical Value = 4.24. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    location:    
      $id: https://geojson.org/schema/Geometry.json    
      $schema: "http://json-schema.org/draft-07/schema#"    
      oneOf:    
        - properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                type: number    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - Point    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON Point'    
          type: object    
        - properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - LineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON LineString'    
          type: object    
        - properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 4    
                type: array    
              type: array    
            type:    
              enum:    
                - Polygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON Polygon'    
          type: object    
        - properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPoint    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiPoint'    
          type: object    
        - properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiLineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiLineString'    
          type: object    
        - properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    items:    
                      type: number    
                    minItems: 2    
                    type: array    
                  minItems: 4    
                  type: array    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPolygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiPolygon'    
          type: object    
      title: 'GeoJSON Geometry'    
    name:    
      description: 'The name of this item.'    
      type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf: *excieeeac7b_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: Property    
    seeAlso:    
      description: 'list of uri pointing to additional resources about the item'    
      oneOf:    
        - items:    
            - format: uri    
              type: string    
          minItems: 1    
          type: array    
        - format: uri    
          type: string    
      type: Property    
    seve1:    
      description: 'Exciter saturation function value at the corresponding exciter voltage, V, back of commutating reactance (S[V]).  Typical Value = 0.44. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    seve2:    
      description: 'Exciter saturation function value at the corresponding exciter voltage, V, back of commutating reactance (S[V]).  Typical Value = 0.075. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: Property    
    tdr:    
      description: 'Lag time constant (T).  Typical Value = 0. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    te:    
      description: 'Exciter time constant, integration rate associated with exciter control (T).  Typical Value = 1.1. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    tf:    
      description: 'Excitation control system stabilizer time constant (T).  Typical Value = 1. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    type:    
      description: 'NGSI type. It has to be ExcIEEEAC7B'    
      enum:    
        - ExcIEEEAC7B    
      type: Property    
    vamax:    
      description: 'Maximum voltage regulator output (V).  Typical Value = 1. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vamin:    
      description: 'Minimum voltage regulator output (V).  Typical Value = -0.95. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    ve1:    
      description: 'Exciter alternator output voltages back of commutating reactance at which saturation is defined (V) equals V (V).  Typical Value = 6.3. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    ve2:    
      description: 'Exciter alternator output voltages back of commutating reactance at which saturation is defined (V).  Typical Value = 3.02. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vemin:    
      description: 'Minimum exciter voltage output (V).  Typical Value = 0. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vfemax:    
      description: 'Exciter field current limit reference (V).  Typical Value = 6.9. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vrmax:    
      description: 'Maximum voltage regulator output (V).  Typical Value = 5.79. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vrmin:    
      description: 'Minimum voltage regulator output (V).  Typical Value = -5.79. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
  required: []    
  type: object    
```  
</details>    
## Example payloads    
Not available the example of a ExcIEEEAC7B in JSON format as key-values. This is compatible with NGSI V2 when  using `options=keyValues` and returns the context data of an individual entity.  
Not available the example of a ExcIEEEAC7B in JSON format as normalized. This is compatible with NGSI V2 when not using options and returns the context data of an individual entity.  
Not available the example of a ExcIEEEAC7B in JSON-LD format as key-values. This is compatible with NGSI-LD when  using `options=keyValues` and returns the context data of an individual entity.  
Not available the example of a ExcIEEEAC7B in JSON-LD format as normalized. This is compatible with NGSI-LD when not using options and returns the context data of an individual entity.  
