Entity: ExcAVR7  
===============  
[Open License](https://github.com/smart-data-models//dataModel.EnergyCIM/blob/master/ExcAVR7/LICENSE.md)  
Global description: **Adapted from CIM data models. IVO excitation system.**  

## List of properties  

- `a1`: Lead coefficient (A1).  Typical Value = 0.5. Default: 0.0  - `a2`: Lag coefficient (A2).  Typical Value = 0.5. Default: 0.0  - `a3`: Lead coefficient (A3).  Typical Value = 0.5. Default: 0.0  - `a4`: Lag coefficient (A4).  Typical Value = 0.5. Default: 0.0  - `a5`: Lead coefficient (A5).  Typical Value = 0.5. Default: 0.0  - `a6`: Lag coefficient (A6).  Typical Value = 0.5. Default: 0.0  - `address`: The mailing address.  - `alternateName`: An alternative name for this item  - `areaServed`: The geographic area where a service or offered item is provided  - `dataProvider`: A sequence of characters identifying the provider of the harmonised data entity.  - `dateCreated`: Entity creation timestamp. This will usually be allocated by the storage platform.  - `dateModified`: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.  - `description`: A description of this item  - `id`: Unique identifier of the entity  - `k1`: Gain (K1).  Typical Value = 1. Default: 0.0  - `k3`: Gain (K3).  Typical Value = 3. Default: 0.0  - `k5`: Gain (K5).  Typical Value = 1. Default: 0.0  - `location`:   - `name`: The name of this item.  - `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)  - `seeAlso`: list of uri pointing to additional resources about the item  - `source`: A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.  - `t1`: Lead time constant (T1).  Typical Value = 0.05. Default: 0  - `t2`: Lag time constant (T2).  Typical Value = 0.1. Default: 0  - `t3`: Lead time constant (T3).  Typical Value = 0.1. Default: 0  - `t4`: Lag time constant (T4).  Typical Value = 0.1. Default: 0  - `t5`: Lead time constant (T5).  Typical Value = 0.1. Default: 0  - `t6`: Lag time constant (T6).  Typical Value = 0.1. Default: 0  - `type`: NGSI type. It has to be ExcAVR7  - `vmax1`: Lead-lag max. limit (Vmax1).  Typical Value = 5. Default: 0.0  - `vmax3`: Lead-lag max. limit (Vmax3).  Typical Value = 5. Default: 0.0  - `vmax5`: Lead-lag max. limit (Vmax5).  Typical Value = 5. Default: 0.0  - `vmin1`: Lead-lag min. limit (Vmin1).  Typical Value = -5. Default: 0.0  - `vmin3`: Lead-lag min. limit (Vmin3).  Typical Value = -5. Default: 0.0  - `vmin5`: Lead-lag min. limit (Vmin5).  Typical Value = -2. Default: 0.0    
Required properties  
This data model is a direct conversion of the Common Information Model (CIM) specified by the IEC61970 standard into smart data models. The python classes this model is based on were developed by these entities Institute for Automation of Complex Power Systems (ACS), EON Energy Research Center (EONERC) and RWTH University Aachen, Germany. some properties can have wrong type. This was the case, pelase raise an issue or send mail to alberto.abella@fiware.org  
## Data Model description of properties  
Sorted alphabetically (click for details)  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
ExcAVR7:    
  description: 'Adapted from CIM data models. IVO excitation system.'    
  properties:    
    a1:    
      description: 'Lead coefficient (A1).  Typical Value = 0.5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    a2:    
      description: 'Lag coefficient (A2).  Typical Value = 0.5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    a3:    
      description: 'Lead coefficient (A3).  Typical Value = 0.5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    a4:    
      description: 'Lag coefficient (A4).  Typical Value = 0.5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    a5:    
      description: 'Lead coefficient (A5).  Typical Value = 0.5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    a6:    
      description: 'Lag coefficient (A6).  Typical Value = 0.5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
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
      anyOf: &excavr7_-_properties_-_owner_-_items_-_anyof    
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
    k1:    
      description: 'Gain (K1).  Typical Value = 1. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    k3:    
      description: 'Gain (K3).  Typical Value = 3. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    k5:    
      description: 'Gain (K5).  Typical Value = 1. Default: 0.0'    
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
        anyOf: *excavr7_-_properties_-_owner_-_items_-_anyof    
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
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: Property    
    t1:    
      description: 'Lead time constant (T1).  Typical Value = 0.05. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    t2:    
      description: 'Lag time constant (T2).  Typical Value = 0.1. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    t3:    
      description: 'Lead time constant (T3).  Typical Value = 0.1. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    t4:    
      description: 'Lag time constant (T4).  Typical Value = 0.1. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    t5:    
      description: 'Lead time constant (T5).  Typical Value = 0.1. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    t6:    
      description: 'Lag time constant (T6).  Typical Value = 0.1. Default: 0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    type:    
      description: 'NGSI type. It has to be ExcAVR7'    
      enum:    
        - ExcAVR7    
      type: Property    
    vmax1:    
      description: 'Lead-lag max. limit (Vmax1).  Typical Value = 5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vmax3:    
      description: 'Lead-lag max. limit (Vmax3).  Typical Value = 5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vmax5:    
      description: 'Lead-lag max. limit (Vmax5).  Typical Value = 5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vmin1:    
      description: 'Lead-lag min. limit (Vmin1).  Typical Value = -5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vmin3:    
      description: 'Lead-lag min. limit (Vmin3).  Typical Value = -5. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
    vmin5:    
      description: 'Lead-lag min. limit (Vmin5).  Typical Value = -2. Default: 0.0'    
      type: number    
      x-ngsi:    
        model: https://schema.org/Number    
  required: []    
  type: object    
```  
</details>    
## Example payloads    
Not available the example of a ExcAVR7 in JSON format as key-values. This is compatible with NGSI V2 when  using `options=keyValues` and returns the context data of an individual entity.  
Not available the example of a ExcAVR7 in JSON format as normalized. This is compatible with NGSI V2 when not using options and returns the context data of an individual entity.  
Not available the example of a ExcAVR7 in JSON-LD format as key-values. This is compatible with NGSI-LD when  using `options=keyValues` and returns the context data of an individual entity.  
Not available the example of a ExcAVR7 in JSON-LD format as normalized. This is compatible with NGSI-LD when not using options and returns the context data of an individual entity.  
