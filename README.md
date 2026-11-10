# LTDS

## Functional Documentation

| Type                            | Documentation FR                                                                                                                                            | Documentatie NL                                                                                                                                              |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Instructions with track changes | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Instructions_FR.zip)             | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Instructies_NL.zip)              |
| Glossary                        | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Glossaire_FR.pdf)                | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Glossarium_NL.pdf)               |
| Annexes                         | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Annexes_Structur%C3%A9es_FR.zip) | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Gestructureerde_bijlagen_NL.zip) |
| Controls                        | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Controles_FR.xlsx)               | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/business_documentation/Controles_NL.xlsx)               |

## Technical Documentation

| Type                | Description                                                                                                                                                                      |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Technical Schema    | [Retrieve the OpenAPI YAML](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/salaryData-v1.yaml)                                      |
| Technical Schema UI | [Pretty print of the schema](https://smals-belgium.github.io/egov3-services-catalog/?spec=salary)                                                                                |
| Technical Schema    | [Retrieve the Stream generic reply events OpenAPI YAML](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/stream-external-api-v2.yaml) |
| Technical Schema UI | [Pretty print of the Stream generic reply events schema](https://smals-belgium.github.io/egov3-services-catalog/?spec=stream)                                                    |

### Stream AsyncAPI presentation options

| Option                | Description                                                                                                                                                                                                                                                                                                                 |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Without tooling       | [View the YAML on GitHub](https://github.com/smals-belgium/egov3-services-catalog/blob/main/technical_specs/stream-smals-external-partners-asyncapi-v2.yaml) or [download it](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/stream-smals-external-partners-asyncapi-v2.yaml). |
| With AsyncAPI tooling | [View the generated documentation](https://smals-belgium.github.io/egov3-services-catalog/technical_specs/stream-asyncapi/).                                                                                                                                                                                                |

These alternatives are pending client approval. The generated HTML depends on both Stream YAMLs. When either changes, regenerate the HTML and commit the updated file:

```shell
npx --yes @asyncapi/cli@6.3.0 generate fromTemplate 'technical_specs\stream-smals-external-partners-asyncapi-v2.yaml' @asyncapi/html-template@3.5.6 -p singleFile=true -o 'technical_specs\stream-asyncapi' --force-write --registry-url "$(npm config get registry)"
```

| Type                           | Documentation FR                                                                                                                                                                | Documentatie NL                                                                                                                                                         |
|--------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Rest Documentation             | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/LTDS-REST-documentation-FR.pdf)                             | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/LTDS-REST-documentatie-NL.pdf)                     |
| Batch Documentation            | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/Echange%20d%C3%A9clarant%20-%20Stream%20via%20SFTP.pdf)     | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/uitwisseling-aangevers-rsz-via-sftp_no-markup.pdf) |
| Examples                       | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/D%C3%A9clarations%20d'exemple.zip)                          | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/Voorbeeldaangiften.zip)                            |
| Testing Procedure              | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/LTDS_Procedure_Test.pdf)                                    | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/LTDS_Testprocedure.pdf)                            |
| Testing Additional Information | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/LTDS%20testing%20-%20Compl%C3%A9ment%20d%27information.pdf) | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/LTDS%20testing%20-%20Aanvullende%20informatie.pdf) |

# AMD (Asynchronous Message Delivery)

## Technical Documentation

| Type                | Description                                                                                                                                         |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| Technical Schema    | [Retrieve the OpenAPI YAML](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/openapi-amed-rest-1.0.yaml) |
| Technical Schema UI | [Pretty print of the schema](https://smals-belgium.github.io/egov3-services-catalog/?spec=amed)                                                     |

| Type               | Documentation FR                                                                                                                                          | Documentatie NL                                                                                                                                            |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Rest Documentation | [Voir la documentation](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/AMD-REST-1.0-documentatie-FR-1.1.pdf) | [Bekijk de documentatie](https://raw.githubusercontent.com/smals-belgium/egov3-services-catalog/main/technical_specs/AMD-REST-1.0-documentatie-NL-1.1.pdf) |
