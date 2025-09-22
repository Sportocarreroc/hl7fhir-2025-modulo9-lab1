//https://hapi.fhir.org/baseR5/ServiceRequest?subject=Patient/810708

{
    "resourceType": "Bundle",
    "id": "c361a735-658f-42c1-9fc3-252b614ef1ef",
    "meta": {
        "lastUpdated": "2025-09-22T22:35:44.545+00:00"
    },
    "type": "searchset",
    "total": 1,
    "link": [
        {
            "relation": "self",
            "url": "https://hapi.fhir.org/baseR5/ServiceRequest?subject=Patient%2F810708"
        }
    ],
    "entry": [
        {
            "fullUrl": "https://hapi.fhir.org/baseR5/ServiceRequest/810715",
            "resource": {
                "resourceType": "ServiceRequest",
                "id": "810715",
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
                }
            },
            "search": {
                "mode": "match"
            }
        }
    ]
}