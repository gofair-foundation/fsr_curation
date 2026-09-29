## **Important Links**

Here are the Nanopub APIs and Searches that are needed in the qualification workflows:
1. Use the API: [**check duplicates**](https://nanodash.knowledgepixels.com/query?115&id=RAm0_gAm9xiNz_RkvqqT4P0LRpNWn3JtC7SHoPRDYOUEY/find-gofair-qualified-things) by searching with the most common name (and similar names) of the FSR to check if there exists more than one nanopub.
2. Check if the FSR is used in FIPs by using this API: [**find FSRs in FIP**](https://knowledgepixels.com/csv_viewer/?u=https%3A%2F%2Fraw.githubusercontent.com%2Fpeta-pico%2Fdsw-nanopub-api%2Frefs%2Fheads%2Fmain%2Ftables%2Fmatrix_reduced.csv). You can use this table to search for the FSR Thing URI or its label.
3. For a quick overview you might also want to use the [**FAIR Implementation Space**](https://w3id.org/spaces/FAIR-Implementation-Space) on Nanodash, which provides all kinds of information on FSRs, FIPs and FICs as well as the possibility to search for them.

### Additional info

1. Use  [**get all FSRs for type**](https://nanodash.knowledgepixels.com/query?id=RARbQh51JW7ufDVdSdJEFEMiWiFo8WtBJ070RuPDRyLW0/get-gofair-qualified-things) to get all FSRs for a particular `type`.

For `type` in the query, use a type IRI from the [FIP ontology](https://w3id.org/fair/fip/terms/Registry) (e.g., for Registries use <https://w3id.org/fair/fip/terms/Registry>).
