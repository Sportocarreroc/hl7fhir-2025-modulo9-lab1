//https://hapi.fhir.org/baseR5/MedicationRequest?subject=Patient/810708

{
    "resourceType": "Bundle",
    "id": "3c5cfa9d-15ab-4809-adcc-1b152a917e8f",
    "meta": {
        "lastUpdated": "2025-09-22T22:33:34.001+00:00"
    },
    "type": "searchset",
    "total": 1,
    "link": [
        {
            "relation": "self",
            "url": "https://hapi.fhir.org/baseR5/MedicationRequest?subject=Patient%2F810708"
        }
    ],
    "entry": [
        {
            "fullUrl": "https://hapi.fhir.org/baseR5/MedicationRequest/810714",
            "resource": {
                "resourceType": "MedicationRequest",
                "id": "810714",
                "meta": {
                    "versionId": "1",
                    "lastUpdated": "2025-09-22T22:22:27.064+00:00",
                    "source": "#FO9cHC5EMXmxMgpa"
                },
                "status": "active",
                "intent": "order",
                "subject": {
                    "reference": "Patient/810708"
                },
                "encounter": {
                    "reference": "Encounter/810710"
                },
                "authoredOn": "2025-09-11"
            },
            "search": {
                "mode": "match"
            }
        }
    ]
}