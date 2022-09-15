RHausamMacbookAir:fhir rhausam$ ./gradlew publish
Starting a Gradle Daemon (subsequent builds will be faster)
Configuration on demand is an incubating feature.

> Configure project :

Kicking off FHIR publishing job!

==============================
Generating code using kindling version 1.0.25-SNAPSHOT
For more information on kindling, and to check latest version, check here:
https://github.com/HL7/kindling

Verbose or customized output can be further configured using the logback.configurationFile gradle property:

  ./gradlew publish -Plogback.configurationFile=~/my-logback-config.xml

==============================

> Task :publish
Publish FHIR in folder /Users/rhausam/git-repo/fhir @ Tue, Sep 6, 2022 10:58-0500 0.015   0sec   20MB
Detected Java version: 11.0.14.1 from /Users/rhausam/.asdf/installs/java/liberica-11.0.14.1+1 on Mac OS X/aarch64 (64bit). 4096MB available 0.021   0sec   21MB
dir = /Users/rhausam/git-repo/fhir, path = /Users/rhausam/.nvm/versions/node/v14.16.0/bin:/Users/rhausam/.asdf/shims:/opt/homebrew/opt/asdf/libexec/bin:/Users/rhausam/.nodenv/shims:/Users/rhausam/.gem/ruby/3.0.2/bin:/Users/rhausam/.rubies/ruby-3.0.2/lib/ruby/gems/3.0.0/bin:/Users/rhausam/.rubies/ruby-3.0.2/bin:/Users/rhausam/.bin:/opt/local/bin:/opt/local/sbin:/opt/homebrew/bin:/opt/homebrew/sbin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Applications/VMware Fusion.app/Contents/Public:/usr/local/MacGPG2/bin:/usr/local/share/dotnet:/opt/X11/bin:~/.dotnet/tools:/Library/Apple/usr/bin:/usr/local/git/bin:/opt/apache-maven-3.6.2/bin:/usr/local/ant/bin:/root/.dotnet/tools 0.001   0sec   21MB
Parameters:                                                                  0.0   0sec   21MB
Start Clock @ Tuesday, September 6, 2022 at 10:58:57 AM Central Daylight Time (2022-09-06T10:58:57-05:00) 0.003   0sec   21MB
                                                                             0.0   0sec   21MB
Build local copy                                                           0.001   0sec   21MB
API keys loaded from /Users/rhausam/fhir-build-keys.ini                    0.017   0sec   21MB
CI_BRANCH_DIRECTORY=null
This is a GitHub Repository: https://github.com/HL7/fhir/FHIR-29653
Load Terminology Cache from /Users/rhausam/.fhir/tx-cache/HL7/fhir/FHIR-29653 1.974   2sec   47MB
Load UTG Terminology                                                       10.946  12sec  428MB
Load Package hl7.terminology#3.1.0
Load DICOM Terminology                                                      3.68  16sec  332MB
Load Package fhir.dicom#2022.1.20220124
Load IHE Format Codes                                                      0.915  17sec  363MB
Load Package ihe.formatcode.fhir#1.1.0
  .. loaded                                                                0.194  17sec  364MB
Checking Source for /Users/rhausam/git-repo/fhir                           0.007  17sec  364MB
Full Build                                                                 0.538  18sec  386MB
Version 5.0.0-cibuild-19fd62dc1b
Load Loinc                                                                 0.064  18sec  394MB
Loading                                                                    0.295  18sec  458MB
Load Common Bindings                                                        0.01  18sec  459MB
Load Code Systems                                                           0.12  18sec  488MB
Load Value Sets                                                            0.007  18sec  489MB
ValueSet http://hl7.org/fhir/ValueSet/days-of-week WG mismatch 4: is fhir, want to set to pa
ValueSet http://hl7.org/fhir/ValueSet/participant-resource-types WG mismatch 4: is fhir, want to set to cds
ValueSet http://hl7.org/fhir/ValueSet/operation-parameter-use WG mismatch 5: is fhir, want to set to cds
ValueSet http://hl7.org/fhir/ValueSet/operation-parameter-use WG mismatch 4: is fhir, want to set to cds
ValueSet http://hl7.org/fhir/ValueSet/citation-artifact-classifier WG mismatch 5: is cds, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/citation-artifact-classifier WG mismatch 4: is cds, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/use-context WG mismatch 4: is fhir, want to set to cds
ValueSet http://hl7.org/fhir/ValueSet/jurisdiction WG mismatch 4: is vocab, want to set to fhir
Load Resources                                                             2.506  21sec  751MB
ValueSet http://hl7.org/fhir/ValueSet/manifestation-or-symptom WG mismatch 4b: is pc, want to set to cds
Load Extras                                                                8.135  29sec  440MB
Load Profiles                                                              0.034  29sec  490MB
ValueSet http://hl7.org/fhir/ValueSet/action-relationship-type WG mismatch 4: is cds, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/condition-cause WG mismatch 4: is pc, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/condition-cause WG mismatch 4: is pc, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/condition-cause WG mismatch 4: is pc, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/jurisdiction WG mismatch 4: is vocab, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/definition-topic WG mismatch 4: is cds, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/action-relationship-type WG mismatch 4: is cds, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/certainty-type WG mismatch 4: is cds, want to set to fhir
ValueSet http://hl7.org/fhir/ValueSet/certainty-rating WG mismatch 4: is cds, want to set to fhir
Copy HTML templates                                                        1.009  30sec 1063MB
 ...diagram uml-example                                                    0.132  30sec 1064MB
 ...diagram primitives                                                       0.0  30sec 1065MB
 ...diagram resources                                                      0.001  30sec 1066MB
 ...vocab #1                                                               0.004  30sec 1066MB
 ...code systems                                                           0.001  30sec 1066MB
 ...value sets                                                             1.828  32sec 1484MB
Terminology server: Check for supported code systems for urn:ietf:bcp:13
Generate Status Code Concept Maps                                          1.277  33sec  698MB
Validating                                                                 0.004  33sec  700MB
Candidate for CodeableReference: [ClinicalImpression.prognosis]
Candidate for CodeableReference: [EvidenceReport.section.entry]
Value Set http://hl7.org/fhir/ValueSet/all-languages: ownership clash patient vs conformance
Code System urn:ietf:bcp:47: ownership clash patient vs conformance
 ...process profiles (base)                                                2.686  36sec 1158MB
 ...process profiles (resources)                                           0.113  36sec 1188MB
Broken ValueSet reference http://hl7.org/fhir/ValueSet/biologicallyderivedproduct-property-type-codes
Broken ValueSet reference http://hl7.org/fhir/ValueSet/medicationrequest-category
 ...process profiles (extensions)                                          2.278  38sec 1672MB
 ...process profiles (packs)                                               0.325  39sec 1804MB
 ...process logical models                                                 0.005  39sec 1809MB
 ...process logical model definition                                         0.0  39sec 1809MB
 ...process logical model event                                            0.001  39sec 1809MB
 ...process logical model request                                            0.0  39sec 1809MB
 ...process logical model fivews                                           0.004  39sec 1809MB
 ...process logical model participant                                        0.0  39sec 1809MB
 ...process logical model participantcontactable                           0.001  39sec 1809MB
 ...process logical model participantliving                                  0.0  39sec 1809MB
 ...process logical model product                                            0.0  39sec 1809MB
 ...process logical model shareable                                          0.0  39sec 1809MB
 ...process logical model publishable                                        0.0  39sec 1810MB
 ...Validate Definitions                                                     0.0  39sec 1810MB
 ...Validate Resource Profiles                                             0.001  39sec 1810MB
 ...Check FHIR Path Expressions                                             0.01  39sec 1821MB
.. Set up Validator                                                        0.256  39sec 1994MB
Generate RDF                                                               4.719  44sec 1564MB
Produce Schemas                                                            1.654  45sec  805MB
Produce Schematrons                                                         1.64  47sec 1663MB
Load R4 Definitions                                                        4.262  51sec 1091MB
Produce Content                                                            6.313  58sec 1696MB
 ...logical model definition                                               0.001  58sec 1696MB
 ...logical model event                                                    0.474  58sec 2012MB
 ...logical model request                                                  0.416  58sec 1039MB
 ...logical model fivews                                                   0.205  59sec 1433MB
 ...logical model participant                                              0.547  59sec 1944MB
 ...logical model participantcontactable                                    0.05  59sec 2008MB
 ...logical model participantliving                                        0.058  59sec 2063MB
 ...logical model product                                                  0.133  59sec 1029MB
 ...logical model shareable                                                 0.05  59sec 1149MB
 ...logical model publishable                                               0.04  59sec 1258MB
 ...default Capability Statements                                          0.711  60sec 1677MB
 ...resource CodeSystem                                                    0.497  61sec 1253MB
 ...resource ValueSet                                                      38.606  99sec 1174MB
 ...value sets                                                             8.247 108sec 1412MB
 ...extensions                                                             99.228 207sec 3175MB
no breadcrumb: name = extension-structuredefinition-conformance-derivedfrom.xml.html, type = extension, prefix = , title = 'http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom'
no breadcrumb: name = extension-structuredefinition-conformance-derivedfrom.json.html, type = extension, prefix = , title = 'http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom'
no breadcrumb: name = extension-structuredefinition-conformance-derivedfrom.ttl.html, type = extension, prefix = , title = 'http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom'
no breadcrumb: name = extension-structuredefinition-conformance-derivedfrom.html, type = extension:fmm, prefix = , title = 'http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom'
no breadcrumb: name = extension-structuredefinition-conformance-derivedfrom.html, type = extension:fmm, prefix = , title = 'http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom'
no breadcrumb: name = extension-structuredefinition-conformance-derivedfrom.html, type = extension:fmm, prefix = , title = 'http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom'
 ...resource identities                                                    192.292 399sec 2151MB
 ...base profiles                                                          5.807 405sec 2797MB
 ...resource MetadataResource                                              42.603 447sec 2465MB
 ...resource DomainResource                                                1.754 449sec 2192MB
 ...resource Parameters                                                    1.106 450sec 2584MB
 ...resource Resource                                                      4.887 455sec 2595MB
 ...resource CanonicalResource                                             1.431 457sec 2138MB
 ...resource Account                                                       2.002 459sec 2227MB
 ...resource ActivityDefinition                                            4.533 463sec 2101MB
 ...resource ActorDefinition                                               8.541 472sec 2487MB
 ...resource AdministrableProductDefinition                                2.345 474sec 2445MB
 ...resource AdverseEvent                                                  6.907 481sec 2973MB
 ...resource AllergyIntolerance                                            10.744 492sec 1920MB
 ...resource Appointment                                                   3.406 495sec 2738MB
 ...resource AppointmentResponse                                           4.537 500sec 2522MB
 ...resource ArtifactAssessment                                            1.723 501sec 1863MB
 ...resource AuditEvent                                                    4.692 506sec 2183MB
 ...resource Basic                                                         8.056 514sec 3074MB
 ...resource Binary                                                        2.752 517sec 2019MB
 ...resource BiologicallyDerivedProduct                                    1.533 518sec 2606MB
 ...resource BodyStructure                                                 3.458 522sec 2268MB
 ...resource Bundle                                                        4.582 526sec 2254MB
 ...resource CapabilityStatement                                           5.619 532sec 1937MB
 ...resource CarePlan                                                      35.47 568sec 2189MB
 ...resource CareTeam                                                      11.648 579sec 1618MB
 ...resource ChargeItem                                                    2.995 582sec 2117MB
 ...resource ChargeItemDefinition                                          7.333 590sec 2975MB
 ...resource Citation                                                      7.145 597sec 2039MB
 ...resource Claim                                                         49.861 647sec 2109MB
 ...resource ClaimResponse                                                 39.941 686sec 2093MB
 ...resource ClinicalImpression                                            16.775 703sec 2465MB
 ...resource ClinicalUseDefinition                                           0.9 704sec 1933MB
 ...resource Communication                                                 2.765 707sec 1753MB
 ...resource CommunicationRequest                                          2.349 709sec 2612MB
 ...resource CompartmentDefinition                                         2.701 712sec 2954MB
 ...resource Composition                                                   4.674 717sec 2263MB
 ...resource ConceptMap                                                    10.79 727sec 2653MB
 ...resource Condition                                                     14.352 742sec 1767MB
 ...resource ConditionDefinition                                           9.825 752sec 2985MB
 ...resource Consent                                                       4.674 756sec 2372MB
 ...resource Contract                                                      17.526 774sec 2057MB
 ...resource Coverage                                                      28.261 802sec 2252MB
 ...resource CoverageEligibilityRequest                                    5.111 807sec 2794MB
 ...resource CoverageEligibilityResponse                                   2.123 809sec 2289MB
 ...resource DetectedIssue                                                 7.138 816sec 2812MB
 ...resource Device                                                        4.286 821sec 2409MB
 ...resource DeviceDefinition                                              18.688 839sec 1798MB
 ...resource DeviceDispense                                                15.911 855sec 2034MB
 ...resource DeviceMetric                                                  15.496 871sec 1645MB
 ...resource DeviceRequest                                                 3.196 874sec 1929MB
 ...resource DeviceUsage                                                   8.881 883sec 2394MB
 ...resource DiagnosticReport                                              4.072 887sec 2388MB
 ...resource DocumentManifest                                              72.17 959sec 2098MB
 ...resource DocumentReference                                             8.188 967sec 1822MB
 ...resource Encounter                                                     13.924 981sec 1978MB
 ...resource Endpoint                                                      11.325 993sec 2553MB
 ...resource EnrollmentRequest                                             1.464 994sec 2269MB
 ...resource EnrollmentResponse                                            1.693 996sec 2919MB
 ...resource EpisodeOfCare                                                 2.025 998sec 1797MB
 ...resource EventDefinition                                               3.379 1001sec 2242MB
 ...resource Evidence                                                      2.246 1003sec 2353MB
 ...resource EvidenceReport                                                16.504 1020sec 2573MB
 ...resource EvidenceVariable                                              7.266 1027sec 2855MB
 ...resource ExampleScenario                                               9.879 1037sec 2481MB
 ...resource ExplanationOfBenefit                                          12.103 1049sec 2473MB
 ...resource FamilyMemberHistory                                           59.75 1109sec 2583MB
 ...resource Flag                                                          18.283 1127sec 2672MB
 ...resource FormularyItem                                                  3.75 1131sec 2103MB
 ...resource GenomicStudy                                                  3.382 1134sec 1948MB
 ...resource Goal                                                          24.411 1159sec 1958MB
 ...resource GraphDefinition                                               6.685 1165sec 1738MB
 ...resource Group                                                         2.809 1168sec 2203MB
No value set at Group.code
No value set at Group.characteristic.code
No value set at Group.characteristic.value[x]
No value set at Group.code
No value set at Group.characteristic.code
No value set at Group.characteristic.value[x]
 ...resource GuidanceResponse                                              18.524 1187sec 2312MB
 ...resource HealthcareService                                             10.411 1197sec 1864MB
 ...resource ImagingSelection                                              18.111 1215sec 1822MB
 ...resource ImagingStudy                                                  13.006 1228sec 2104MB
 ...resource Immunization                                                  10.662 1239sec 1711MB
 ...resource ImmunizationEvaluation                                        5.878 1245sec 2025MB
 ...resource ImmunizationRecommendation                                    2.136 1247sec 2334MB
 ...resource ImplementationGuide                                           1.573 1249sec 1649MB
 ...resource Ingredient                                                    9.996 1259sec 1706MB
 ...resource InsurancePlan                                                 5.425 1264sec 2817MB
 ...resource InventoryReport                                               5.352 1269sec 2376MB
 ...resource Invoice                                                       2.628 1272sec 2030MB
 ...resource Library                                                       2.687 1275sec 2227MB
 ...resource Linkage                                                       28.587 1303sec 3033MB
 ...resource List                                                          0.988 1304sec 1829MB
 ...resource Location                                                       2.72 1307sec 3001MB
 ...resource ManufacturedItemDefinition                                    2.531 1309sec 2344MB
 ...resource Measure                                                       3.245 1313sec 2550MB
 ...resource MeasureReport                                                 21.438 1334sec 2222MB
 ...resource Medication                                                    6.763 1341sec 1759MB
 ...resource MedicationAdministration                                       7.38 1348sec 2323MB
 ...resource MedicationDispense                                             4.69 1353sec 3074MB
 ...resource MedicationKnowledge                                           8.558 1361sec 3078MB
 ...resource MedicationRequest                                             8.644 1370sec 3101MB
 ...resource MedicationUsage                                               19.325 1389sec 2112MB
 ...resource MedicinalProductDefinition                                     3.52 1393sec 2017MB
 ...resource MessageDefinition                                             5.642 1399sec 3322MB
 ...resource MessageHeader                                                 11.225 1410sec 2319MB
 ...resource MolecularSequence                                             5.918 1416sec 2386MB
 ...resource NamingSystem                                                  12.003 1428sec 2373MB
 ...resource NutritionIntake                                               8.064 1436sec 2341MB
 ...resource NutritionOrder                                                  3.2 1439sec 2589MB
 ...resource NutritionProduct                                              23.435 1462sec 2100MB
 ...resource Observation                                                   6.123 1469sec 2343MB
Markup uses non permitted name sup
 ...resource ObservationDefinition                                         101.425 1570sec 2629MB
 ...resource OperationDefinition                                           21.887 1592sec 1967MB
 ...resource OperationOutcome                                                7.9 1600sec 3216MB
 ...resource Organization                                                  1.394 1601sec 1750MB
 ...resource OrganizationAffiliation                                       2.417 1604sec 2353MB
 ...resource PackagedProductDefinition                                     1.376 1605sec 2231MB
 ...resource Patient                                                       3.215 1608sec 2457MB
 ...resource PaymentNotice                                                 10.086 1618sec 2904MB
 ...resource PaymentReconciliation                                         1.462 1620sec 2147MB
 ...resource Permission                                                    7.463 1627sec 2925MB
 ...resource Person                                                        2.615 1630sec 1699MB
 ...resource PlanDefinition                                                2.886 1633sec 2414MB
 ...resource Practitioner                                                  34.731 1667sec 2313MB
 ...resource PractitionerRole                                              4.406 1672sec 2714MB
 ...resource Procedure                                                     2.473 1674sec 2398MB
 ...resource Provenance                                                    4.487 1679sec 2943MB
 ...resource Questionnaire                                                 7.435 1686sec 2837MB
 ...resource QuestionnaireResponse                                         12.393 1699sec 2482MB
 ...resource RegulatedAuthorization                                        5.183 1704sec 1902MB
 ...resource RelatedPerson                                                 3.451 1707sec 2405MB
 ...resource RequestOrchestration                                          2.929 1710sec 1913MB
 ...resource Requirements                                                  23.603 1734sec 1796MB
 ...resource ResearchStudy                                                 3.038 1737sec 1908MB
 ...resource ResearchSubject                                               7.197 1744sec 2582MB
 ...resource RiskAssessment                                                1.856 1746sec 2588MB
 ...resource Schedule                                                        3.3 1749sec 1786MB
 ...resource SearchParameter                                               2.373 1752sec 1927MB
 ...resource ServiceRequest                                                10.797 1762sec 2023MB
 ...resource Slot                                                          16.935 1779sec 2281MB
 ...resource Specimen                                                      1.119 1780sec 1935MB
 ...resource SpecimenDefinition                                             4.59 1785sec 2907MB
 ...resource StructureDefinition                                           10.394 1795sec 1901MB
 ...resource StructureMap                                                  14.309 1810sec 2206MB
 ...resource Subscription                                                  7.654 1817sec 2229MB
 ...resource SubscriptionStatus                                            2.598 1820sec 2388MB
 ...resource SubscriptionTopic                                             4.531 1824sec 2164MB
 ...resource Substance                                                     8.768 1833sec 1786MB
 ...resource SubstanceDefinition                                           1.618 1835sec 2998MB
 ...resource SubstanceNucleicAcid                                          7.346 1842sec 2947MB
 ...resource SubstancePolymer                                              1.616 1844sec 2586MB
 ...resource SubstanceProtein                                              3.046 1847sec 2627MB
 ...resource SubstanceReferenceInformation                                  1.13 1848sec 3392MB
 ...resource SubstanceSourceMaterial                                       1.678 1850sec 2392MB
 ...resource SupplyDelivery                                                4.421 1854sec 2925MB
 ...resource SupplyRequest                                                 5.796 1860sec 2531MB
 ...resource Task                                                          2.786 1863sec 2565MB
 ...resource TerminologyCapabilities                                       9.695 1872sec 2044MB
 ...resource TestReport                                                    5.387 1878sec 3273MB
 ...resource TestScript                                                    6.182 1884sec 2358MB
 ...resource Transport                                                     35.849 1920sec 1896MB
 ...resource VerificationResult                                            12.199 1932sec 2112MB
 ...resource VisionPrescription                                            3.043 1935sec 2188MB
 ...compartment patient                                                    2.806 1938sec 2273MB
 ...compartment encounter                                                  0.015 1938sec 2279MB
 ...compartment relatedPerson                                              0.005 1938sec 2282MB
 ...compartment practitioner                                               0.003 1938sec 2286MB
 ...compartment device                                                     0.005 1938sec 2291MB
 ...page administration-module.html                                        0.063 1938sec 2299MB
 ...page async.html                                                        0.022 1938sec 2317MB
 ...page async-bulk.html                                                   0.014 1938sec 2321MB
 ...page async-bundle.html                                                  0.04 1938sec 2348MB
 ...page cda-intro.html                                                    0.012 1938sec 2356MB
 ...page change.html                                                       0.015 1938sec 2363MB
 ...page clinicalreasoning-module.html                                      0.02 1938sec 2368MB
 ...page clinicalreasoning-cds-on-fhir.html                                0.082 1938sec 2388MB
 ...page clinicalreasoning-knowledge-artifact-distribution.html            0.048 1938sec 2400MB
 ...page clinicalreasoning-knowledge-artifact-representation.html          0.017 1938sec 2406MB
 ...page clinicalreasoning-quality-reporting.html                          0.056 1938sec 2431MB
 ...page clinicalreasoning-evidence-and-statistics.html                     0.05 1938sec 2445MB
 ...page clinicalreasoning-topics-definitional-resources.html              0.073 1938sec 2457MB
 ...page clinicalreasoning-topics-supporting-documentation.html            0.049 1938sec 2463MB
 ...page clinicalreasoning-topics-using-expressions.html                   0.039 1938sec 2467MB
 ...page clinicalsummary-module.html                                       0.112 1939sec 2477MB
 ...page comparison-cda.html                                               0.075 1939sec 2485MB
 ...page comparison-other.html                                             0.064 1939sec 2491MB
 ...page comparison-v2.html                                                0.038 1939sec 2495MB
 ...page comparison-v3.html                                                 0.07 1939sec 2504MB
 ...page comparison.html                                                   0.087 1939sec 2513MB
 ...page conformance-module.html                                           0.046 1939sec 2517MB
 ...page conformance-rules.html                                            0.201 1939sec 2524MB
 ...page credits.html                                                      0.308 1939sec 1733MB
 ...page datatypes-definitions.html                                        0.006 1940sec 1739MB
 ...page datatypes-examples.html                                           0.383 1940sec 1859MB
 ...page datatypes-mappings.html                                           0.184 1940sec 1976MB
 ...page datatypes-version-maps.html                                       0.064 1940sec 2020MB
 ...page datatypes.html                                                    0.146 1940sec 2084MB
 ...page datatypes-extras.html                                              4.72 1945sec 2000MB
 ...page defining-extensions.html                                          0.104 1945sec 2048MB
 ...page diagnostics-module.html                                           0.024 1945sec 2057MB
 ...page diff.html                                                         0.025 1945sec 2066MB
 ...page documentation.html                                                0.514 1946sec 1752MB
 ...page documents.html                                                    0.012 1946sec 1760MB
 ...page downloads.html                                                    0.028 1946sec 1771MB
 ...page dosage-definitions.html                                           0.008 1946sec 1778MB
 ...page dosage-examples.html                                               0.03 1946sec 1807MB
 ...page dosage-mappings.html                                              0.006 1946sec 1810MB
 ...page dosage-extras.html                                                0.009 1946sec 1815MB
 ...page dosage.html                                                       0.007 1946sec 1818MB
 ...page exchanging.html                                                   0.097 1946sec 1907MB
 ...page exchanging-messaging.html                                         0.034 1946sec 2011MB
 ...page exchanging-operation.html                                         0.005 1946sec 2017MB
 ...page exchanging-polling.html                                           0.011 1946sec 2024MB
 ...page exchanging-request.html                                            0.01 1946sec 2029MB
 ...page exchanging-rest.html                                              0.014 1946sec 2039MB
 ...page exchanging-search.html                                            0.042 1946sec 2049MB
 ...page exchanging-subscription.html                                      0.094 1946sec 2057MB
 ...page patterns.html                                                     0.026 1946sec 1706MB
 ...page population-definitions.html                                       0.063 1946sec 1754MB
 ...page population-examples.html                                          0.013 1946sec 1759MB
 ...page population-mappings.html                                          0.008 1946sec 1762MB
 ...page population-extras.html                                            0.007 1946sec 1765MB
 ...page population.html                                                   0.017 1946sec 1768MB
 ...page productshelflife-definitions.html                                 0.049 1946sec 1796MB
 ...page productshelflife-examples.html                                    0.013 1946sec 1802MB
 ...page productshelflife-mappings.html                                    0.005 1946sec 1805MB
 ...page productshelflife-extras.html                                      0.008 1946sec 1808MB
 ...page productshelflife.html                                             0.006 1946sec 1812MB
 ...page marketingstatus-definitions.html                                  0.056 1946sec 1843MB
 ...page marketingstatus-examples.html                                     0.011 1946sec 1856MB
 ...page marketingstatus-mappings.html                                     0.006 1946sec 1859MB
 ...page marketingstatus-extras.html                                       0.005 1946sec 1862MB
 ...page marketingstatus.html                                              0.009 1946sec 1865MB
 ...page ehr-fm.html                                                       0.048 1946sec 1903MB
 ...page elementdefinition-definitions.html                                0.011 1946sec 1910MB
 ...page elementdefinition-examples.html                                   0.061 1946sec 1969MB
 ...page elementdefinition-mappings.html                                   0.014 1947sec 1975MB
 ...page elementdefinition-extras.html                                     0.028 1947sec 1991MB
 ...page elementdefinition.html                                            0.014 1947sec 1999MB
 ...page exchange-module.html                                              1.567 1948sec 2145MB
 ...page extensibility-definitions.html                                    0.037 1948sec 2152MB
 ...page extensibility-examples.html                                       0.024 1948sec 2156MB
 ...page extensibility-registry.html                                       0.041 1948sec 2172MB
 ...page extensibility.html                                                0.595 1949sec 2412MB
 ...page fhirpath.html                                                     0.395 1949sec 1712MB
 ...page fhirpatch.html                                                    0.015 1949sec 1729MB
 ...page financial-module.html                                             0.006 1949sec 1735MB
 ...page fmg.html                                                          0.036 1949sec 1790MB
 ...page formats.html                                                      0.251 1950sec 1926MB
 ...page resource-formats.html                                             0.045 1950sec 1952MB
 ...page foundation-module.html                                            0.007 1950sec 1958MB
 ...page genomics.html                                                     0.011 1950sec 1963MB
 ...page glossary.html                                                     0.006 1950sec 1967MB
 ...page graphql.html                                                      0.009 1950sec 1973MB
 ...page help.html                                                         0.032 1950sec 2001MB
 ...page history.html                                                      0.046 1950sec 2076MB
 ...page http.html                                                         0.186 1950sec 2142MB
 ...page identifier-registry.html                                          0.684 1951sec 1751MB
 ...page implsupport-module.html                                           0.026 1951sec 1754MB
 ...page index.html                                                        0.053 1951sec 1760MB
 ...page integrated-examples.html                                          0.078 1951sec 1766MB
 ...page json.html                                                         0.029 1951sec 1777MB
 ...page languages.html                                                    0.046 1951sec 1791MB
 ...page license.html                                                      0.077 1951sec 1805MB
 ...page lifecycle.html                                                    0.039 1951sec 1812MB
 ...page logical.html                                                      0.067 1951sec 1841MB
 ...page managing.html                                                     0.014 1951sec 1848MB
 ...page mappings.html                                                     0.026 1951sec 1858MB
 ...page mapping-language.html                                             0.021 1951sec 1865MB
 ...page mapping-tutorial.html                                             0.027 1951sec 1882MB
 ...page medications-module.html                                           0.037 1951sec 1895MB
 ...page medication-definition-module.html                                 0.085 1951sec 1926MB
 ...page messaging.html                                                    0.099 1951sec 1953MB
 ...page metadatatypes.html                                                0.033 1951sec 1972MB
 ...page metadatatypes-definitions.html                                    2.694 1954sec 2336MB
 ...page metadatatypes-examples.html                                       0.249 1954sec 2401MB
 ...page metadatatypes-mappings.html                                       0.048 1954sec 2413MB
 ...page modules.html                                                       0.04 1954sec 2420MB
 ...page narrative-definitions.html                                        0.037 1954sec 2427MB
 ...page narrative-example.html                                            0.034 1954sec 2432MB
 ...page narrative.html                                                    0.075 1954sec 2441MB
 ...page nd-json.html                                                      0.152 1955sec 2462MB
 ...page ns.html                                                           0.034 1955sec 2466MB
 ...page op-example-request.html                                           4.266 1959sec 2678MB
 ...page operations.html                                                    0.01 1959sec 2681MB
 ...page operations-for-large-resources.html                               0.034 1959sec 2691MB
 ...page operationslist.html                                                0.03 1959sec 2714MB
 ...page overview.html                                                     0.025 1959sec 2722MB
 ...page overview-arch.html                                                0.013 1959sec 2731MB
 ...page overview-clinical.html                                            0.152 1959sec 2760MB
 ...page overview-dev.html                                                 0.015 1959sec 2771MB
 ...page profilelist.html                                                  0.032 1959sec 2788MB
 ...page profiling-examples.html                                           0.043 1959sec 2803MB
 ...page profiling.html                                                    0.057 1959sec 2829MB
 ...page pushpull.html                                                     0.057 1959sec 2864MB
 ...page r3maps.html                                                       0.005 1959sec 2868MB
 ...page rdf.html                                                          0.028 1959sec 2883MB
 ...page references-definitions.html                                       0.085 1960sec 2936MB
 ...page references-extras.html                                            0.043 1960sec 2945MB
 ...page references.html                                                   0.041 1960sec 2949MB
 ...page resourceguide.html                                                0.232 1960sec 1780MB
 ...page resourcelist.html                                                 0.019 1960sec 1802MB
 ...page safety.html                                                       18.273 1978sec 2031MB
 ...page sc.html                                                           0.261 1978sec 2056MB
 ...page search.html                                                       0.566 1979sec 2123MB
 ...page search-build.html                                                 6.685 1986sec 1898MB
 ...page search_filter.html                                                0.025 1986sec 1901MB
 ...page searchparameter-registry.html                                     0.027 1986sec 1908MB
 ...page secpriv-module.html                                                2.48 1988sec 2376MB
 ...page security-labels.html                                              0.224 1988sec 2390MB
 ...page security.html                                                     0.126 1989sec 2405MB
 ...page services.html                                                     0.397 1989sec 2440MB
 ...page signatures.html                                                     0.2 1989sec 2459MB
 ...page snomedct-usage.html                                               0.061 1989sec 2463MB
Unknown SCT code 1186610007
Unknown SCT code 1149080001
Unknown SCT code 1137434003
Unknown SCT code 1186610007
Unknown SCT code 1149080001
Unknown SCT code 1137434003
 ...page storage.html                                                      9.289 1998sec 2205MB
 ...page subscriptions.html                                                0.012 1998sec 2212MB
 ...page summary.html                                                      0.057 1999sec 2227MB
 ...page terminologies-conceptmaps.html                                    0.044 1999sec 2236MB
 ...page terminologies-systems.html                                         0.09 1999sec 2251MB
 ...page terminologies-valuesets.html                                      0.268 1999sec 2351MB
 ...page terminologies.html                                                20.693 2020sec 1941MB
 ...page terminologies-binding-examples.html                               0.046 2020sec 1966MB
 ...page terminology-module.html                                           0.009 2020sec 1973MB
 ...page terminology-service.html                                          0.025 2020sec 1981MB
 ...page testing.html                                                      0.021 2020sec 2009MB
 ...page todo.html                                                         0.068 2020sec 2096MB
 ...page types-definitions.html                                            0.013 2020sec 2100MB
 ...page types-mappings.html                                                0.19 2020sec 2112MB
 ...page types.html                                                        0.013 2020sec 2118MB
 ...page types-extras.html                                                 0.292 2020sec 2205MB
 ...page types-version-maps.html                                           0.107 2020sec 2217MB
 ...page uml.html                                                           0.15 2021sec 2224MB
 ...page updates.html                                                       0.03 2021sec 2248MB
 ...page usecases.html                                                     0.007 2021sec 2256MB
 ...page validation.html                                                   0.018 2021sec 2264MB
 ...page versions.html                                                     0.023 2021sec 2273MB
 ...page versioning.html                                                   0.077 2021sec 2334MB
 ...page w5.html                                                            0.02 2021sec 2341MB
 ...page workflow.html                                                     0.316 2021sec 1770MB
 ...page workflow-communications.html                                      0.023 2021sec 1784MB
 ...page workflow-ad-hoc.html                                              0.027 2021sec 1799MB
 ...page workflow-management.html                                          0.011 2021sec 1811MB
 ...page workflow-examples.html                                            0.012 2021sec 1828MB
 ...page workflow-module.html                                              0.008 2021sec 1831MB
 ...page xml.html                                                          0.004 2021sec 1840MB
 ...page wglist.html                                                       0.018 2021sec 1852MB
 ...page ballot-intro.html                                                 0.014 2021sec 1862MB
 ...page packages.html                                                     0.005 2021sec 1868MB
 ...page oids.html                                                         0.005 2021sec 1876MB
 ...page best-practices.html                                               0.538 2022sec 1950MB
 ...page ansi.html                                                          0.03 2022sec 1955MB
 ...sid icd-10                                                             0.012 2022sec 1959MB
 ...sid icd-9                                                              0.037 2022sec 1962MB
 ...sid us-ssn                                                             0.006 2022sec 1965MB
 ...check Fragments                                                        0.005 2022sec 1968MB
 ...Profile general-extensions                                              0.28 2022sec 2018MB
 ...Profile iso-21090                                                      0.018 2022sec 2021MB
 ...Profile smart-app-launch                                               0.031 2022sec 2025MB
 ...Profile pharmacy-core                                                  0.005 2022sec 2027MB
 ...Profile element-extensions                                             0.008 2022sec 2029MB
 ...Profile rendering-extensions                                           0.007 2022sec 2031MB
 ...Profile elementdefinition-11179                                        0.005 2022sec 2034MB
 ...Profile elementdefinition-dataelement                                  0.002 2022sec 2036MB
No value set at ElementDefinition.code
 ...Profile elementdefinition-extensions                                   34.887 2057sec 2892MB
 ...Profile timing-extensions                                               0.11 2057sec 2895MB
 ...Profile metadata-extensions                                            0.012 2057sec 2897MB
 ...Profile humanname-extensions                                           0.095 2057sec 2898MB
 ...Profile coding-extensions                                              0.017 2057sec 2900MB
 ...Profile quantity-extensions                                            0.026 2057sec 2902MB
 ...Profile reference-extensions                                            0.02 2057sec 2904MB
 ...Profile contactpoint-extensions                                        0.019 2057sec 2906MB
 ...Profile dosage-extensions                                              0.016 2057sec 2908MB
 ...Profile identifier-extensions                                          0.016 2057sec 2910MB
 ...Profile event-extensions                                               0.018 2057sec 2911MB
 ...Profile request-extensions                                             0.034 2057sec 2915MB
 ...Profile workflow-extensions                                            0.007 2057sec 2917MB
 ...Profile artifact-extensions                                            0.025 2057sec 2923MB
 ...Profile clinicalreasoning-extensions                                   0.031 2057sec 2926MB
 ...Profile meta-extensions                                                0.014 2058sec 2929MB
 ...page toc.html                                                          3.947 2061sec 2075MB
 ...collections                                                            6.332 2068sec 1888MB
Error in StructureDefinition extended-contact-availability: FhirVersion is wrong (should be 5.0.0-cibuild, is 4.6.0)
Installing hl7.fhir.r5.expansions#current to the package cache
  Fetching:
............... 50% EXECUTING [34m 50s]
  Installing: ............... done.54s]
....version maps                                                           38.252 2106sec 1886MB
....definitions                                                            1.073 2107sec 1887MB
....dstu3 format (xml)                                                     4.511 2112sec 1888MB
Convert /Users/rhausam/git-repo/fhir/publish/profiles-types.xml
Convert /Users/rhausam/git-repo/fhir/publish/profiles-resources.xml
Convert /Users/rhausam/git-repo/fhir/publish/profiles-others.xml
Convert /Users/rhausam/git-repo/fhir/publish/extension-definitions.xml
Convert /Users/rhausam/git-repo/fhir/publish/search-parameters.xml
Convert /Users/rhausam/git-repo/fhir/publish/valuesets.xml
Convert /Users/rhausam/git-repo/fhir/publish/conceptmaps.xml
Convert /Users/rhausam/git-repo/fhir/publish/dataelements.xml
....dstu3 format (json)                                                    25.611 2137sec 2096MB
Convert /Users/rhausam/git-repo/fhir/publish/profiles-types.xml
Convert /Users/rhausam/git-repo/fhir/publish/profiles-resources.xml
Convert /Users/rhausam/git-repo/fhir/publish/profiles-others.xml
Convert /Users/rhausam/git-repo/fhir/publish/extension-definitions.xml
Convert /Users/rhausam/git-repo/fhir/publish/search-parameters.xml
Convert /Users/rhausam/git-repo/fhir/publish/valuesets.xml
Convert /Users/rhausam/git-repo/fhir/publish/conceptmaps.xml
Convert /Users/rhausam/git-repo/fhir/publish/dataelements.xml
....r4 in r5 format                                                        22.135 2159sec 1567MB
....IG Builder Resources                                                   7.322 2167sec 1826MB
....IG Builder (2)                                                         3.059 2170sec 1879MB
Generate Package for /Users/rhausam/git-repo/fhir/publish/
 .. Loading v5.0.0-cibuild
 .. Conformance Resources
 .. Other Resources
 .. building IG
 .. Building NPM Package
 .. Built
 .. Building NPM Package (xml)
 .. Built
Installing hl7.fhir.r5.core#current to the package cache
  Fetching:
...............................................................................................
  Installing: ............................................................................................... done.
 ...zips                                                                   69.314 2239sec 2168MB
Check HTML Links                                                           55.31 2294sec 2138MB
Validating Examples                                                        156.449 2451sec 1352MB
 ...validate account-example                                               1.119 2452sec 1658MB
 ...validate account-example-with-guarantor                                1.159 2453sec 1375MB
 ...validate activitydefinition-example                                     0.59 2454sec 1375MB
 ...validate activitydefinition-medicationorder-example                    0.588 2454sec 1375MB
 ...validate activitydefinition-administer-zika-virus-exposure-assessment  0.555 2455sec 1376MB
 ...validate activitydefinition-order-serum-zika-dengue-virus-igm          0.513 2455sec 1376MB
 ...validate activitydefinition-provide-mosquito-prevention-advice         0.473 2456sec 1376MB
 ...validate activitydefinition-servicerequest-example                     0.563 2456sec 1376MB
 ...validate activitydefinition-supplyrequest-example                      0.491 2457sec 1376MB
 ...validate activitydefinition-predecessor-example                        0.534 2457sec 1376MB
 ...validate activitydefinition-order-serum-dengue-virus-igm               0.526 2458sec 1376MB
 ...validate activitydefinition-example-alteplase-dosing                   0.554 2458sec 1376MB
 ...validate actordefinition-client                                        0.537 2459sec 1376MB
 ...validate actordefinition-server                                        0.498 2460sec 1376MB
 ...validate administrableproductdefinition-example                        0.523 2460sec 1376MB
 ...validate allergyintolerance-example                                    0.738 2461sec 1376MB
 ...validate allergyintolerance-medication                                  0.71 2461sec 1376MB
 ...validate allergyintolerance-fishallergy                                1.032 2463sec 1376MB
 ...validate allergyintolerance-nka                                        0.629 2463sec 1376MB
 ...validate allergyintolerance-nkda                                       0.517 2464sec 1376MB
 ...validate allergyintolerance-nkla                                       0.547 2464sec 1376MB
 ...validate appointment-example                                           0.546 2465sec 1376MB
 ...validate appointment-example2doctors                                    0.52 2465sec 1376MB
 ...validate appointment-example-request                                   0.525 2466sec 1376MB
 ...validate appointmentresponse-example                                   0.554 2466sec 1376MB
 ...validate appointmentresponse-example-req                               0.508 2467sec 1376MB
 ...validate artifactassessment-risk-of-bias-example                       0.506 2467sec 1376MB
 ...validate artifactassessment-example-certainty-rating                   0.532 2468sec 1376MB
 ...validate auditevent-example                                            0.516 2468sec 1376MB
 ...validate audit-event-example-login                                      0.52 2469sec 1376MB
 ...validate audit-event-example-logout                                    0.501 2469sec 1376MB
 ...validate audit-event-example-vread                                     0.532 2470sec 1376MB
 ...validate audit-event-example-create-traceID                            0.751 2471sec 1376MB
 ...validate auditevent-example-disclosure                                 0.501 2471sec 1376MB
 ...validate audit-event-example-search                                    0.506 2472sec 1376MB
 ...validate audit-event-example-pixQuery                                  0.572 2472sec 1376MB
 ...validate audit-event-example-media                                     0.596 2473sec 1376MB
 ...validate auditevent-example-error                                      0.508 2473sec 1376MB
 ...validate auditevent-example-breakglass-start                           0.506 2474sec 1376MB
 ...validate auditevent-example-consent-authz                              0.525 2474sec 1376MB
 ...validate auditevent-example-advanced-create                            0.521 2475sec 1376MB
 ...validate basic-example                                                 0.575 2476sec 1376MB
 ...validate basic-example2                                                0.596 2476sec 1376MB
 ...validate basic-example-narrative                                       0.641 2477sec 1376MB
 ...validate binary-example                                                0.685 2477sec 1376MB
 ...validate binary-f006                                                   1.015 2478sec 1377MB
 ...validate biologicallyderivedproduct-example                            0.544 2479sec 1376MB
 ...validate biologicallyderivedproduct-example-allogeneicHCT              0.564 2480sec 1376MB
 ...validate biologicallyderivedproduct-example-autologousHCT              0.615 2480sec 1376MB
 ...validate bodystructure-example-fetus                                   0.512 2481sec 1376MB
 ...validate bodystructure-example-tumor                                    0.53 2481sec 1376MB
 ...validate bodystructure-example-skin-patch                               0.54 2482sec 1376MB
 ...validate bundle-example                                                0.516 2482sec 1376MB
 ...validate bundle-transaction                                             0.64 2483sec 1377MB
 ...validate bundle-response                                               0.598 2484sec 1377MB
 ...validate bundle-request-medsallergies                                  0.524 2484sec 1377MB
 ...validate bundle-response-medsallergies                                 0.588 2485sec 1377MB
 ...validate bundle-request-simplesummary                                  0.564 2485sec 1377MB
 ...validate bundle-response-simplesummary                                 0.571 2486sec 1377MB
 ...validate bundle-search-warning                                         0.608 2486sec 1377MB
 ...validate bundle-references                                             0.505 2487sec 1377MB
 ...validate capabilitystatement-example                                    0.59 2487sec 1377MB
 ...validate capabilitystatement-phr-example                               0.547 2488sec 1377MB
 ...validate capabilitystatement-base                                      0.627 2489sec 1377MB
 ...validate capabilitystatement-base2                                     9.619 2498sec 1392MB
 ...validate capabilitystatement-terminology-server                        0.535 2499sec 1377MB
 ...validate capabilitystatement-knowledge-repository                      1.394 2500sec 1377MB
 ...validate capabilitystatement-measure-processor                         1.416 2502sec 1377MB
 ...validate capabilitystatement-messagedefinition                         0.643 2502sec 1377MB
 ...validate careplan-example                                              0.557 2503sec 1377MB
 ...validate careplan-example-pregnancy                                    0.529 2503sec 1377MB
 ...validate careplan-example-integrated                                   0.565 2504sec 1377MB
 ...validate careplan-example-GPVisit                                      0.659 2505sec 1378MB
 ...validate careplan-example-f001-heart                                   0.601 2505sec 1377MB
 ...validate careplan-example-f002-lung                                    0.543 2506sec 1377MB
 ...validate careplan-example-f003-pharynx                                 0.641 2506sec 1377MB
 ...validate careplan-example-f201-renal                                   0.608 2507sec 1377MB
 ...validate careplan-example-f202-malignancy                              0.585 2508sec 1377MB
 ...validate careplan-example-f203-sepsis                                  0.763 2508sec 1377MB
 ...validate careplan-example-obesity-narrative                            0.806 2509sec 1377MB
 ...validate careteam-example                                              0.677 2510sec 1377MB
 ...validate chargeitem-example                                            0.783 2511sec 1377MB
 ...validate chargeitemdefinition-ebm-example                              0.943 2512sec 1377MB
 ...validate chargeitemdefinition-device-example                            0.81 2512sec 1377MB
 ...validate citation-example-research-doi                                 0.606 2513sec 1377MB
 ...validate claim-example                                                 0.597 2514sec 1378MB
 ...validate claim-example-oral-average                                    0.514 2514sec 1377MB
 ...validate claim-example-oral-contained                                  0.638 2515sec 1378MB
 ...validate claim-example-oral-identifier                                 1.139 2516sec 1378MB
 ...validate claim-example-oral-contained-identifier                       0.533 2516sec 1378MB
 ...validate claim-example-oral-bridge                                     0.613 2517sec 1378MB
 ...validate claim-example-oral-orthoplan                                   0.62 2518sec 1378MB
 ...validate claim-example-vision                                          0.696 2518sec 1378MB
 ...validate claim-example-vision-glasses                                  0.565 2519sec 1378MB
 ...validate claim-example-vision-glasses-3tier                            0.488 2519sec 1378MB
 ...validate claim-example-institutional                                   0.589 2520sec 1378MB
 ...validate claim-example-institutional-rich                              0.769 2521sec 1378MB
 ...validate claim-example-professional                                     1.18 2522sec 1378MB
 ...validate claim-example-pharmacy                                        0.784 2523sec 1378MB
 ...validate claim-example-pharmacy-medication                             0.931 2524sec 1378MB
 ...validate claim-example-pharmacy-compound                               0.965 2525sec 1378MB
 ...validate claim-example-cms1500-medical                                 0.621 2525sec 1378MB
 ...validate claimresponse-example                                         1.317 2527sec 1378MB
 ...validate claimresponse-example-2                                       0.625 2527sec 1378MB
 ...validate claimresponse-example-vision-3tier                            0.627 2528sec 1378MB
 ...validate claimresponse-example-additem                                 0.558 2528sec 1378MB
 ...validate claimresponse-example-unsolicited-preauth                     0.853 2529sec 1378MB
 ...validate clinicalimpression-example                                    1.266 2530sec 1378MB
 ...validate clinicalusedefinition-example                                 0.835 2531sec 1378MB
 ...validate codesystem-example                                             0.77 2532sec 1378MB
 ...validate codesystem-nhin-purposeofuse                                   1.11 2533sec 1378MB
 ...validate codesystem-example-summary                                    0.555 2534sec 1378MB
 ...validate codesystem-example-supplement                                  0.57 2534sec 1378MB
 ...validate codesystem-example-supplement-2                                0.63 2535sec 1378MB
 ...validate codesystem-example-metadata                                   0.569 2535sec 1378MB
 ...validate codesystem-example-metadata-2                                 1.378 2537sec 1378MB
 ...validate communication-example                                         1.108 2538sec 1378MB
 ...validate communication-example-fm-solicited-attachment                 1.029 2539sec 1378MB
 ...validate communication-example-fm-attachment                            0.71 2540sec 1378MB
 ...validate communicationrequest-example                                  0.708 2540sec 1378MB
 ...validate communicationrequest-example-fm-solicit-attachment            0.528 2541sec 1378MB
 ...validate compartmentdefinition-patient                                 0.545 2541sec 1378MB
 ...validate compartmentdefinition-practitioner                            0.612 2542sec 1379MB
 ...validate compartmentdefinition-relatedperson                           0.561 2543sec 1379MB
 ...validate compartmentdefinition-device                                  0.593 2543sec 1379MB
 ...validate compartmentdefinition-encounter                               0.503 2544sec 1379MB
 ...validate compartmentdefinition-example                                 0.588 2544sec 1379MB
 ...validate composition-example                                           0.677 2545sec 1378MB
 ...validate document-example-dischargesummary                             0.713 2546sec 1378MB
 ...validate composition-example-mixed                                     1.098 2547sec 1379MB
 ...validate conceptmap-example                                            0.717 2548sec 1378MB
 ...validate conceptmap-103                                                0.528 2548sec 1379MB
 ...validate conceptmap-example-specimen-type                              0.625 2549sec 1378MB
 ...validate conceptmap-example-2                                          0.693 2549sec 1382MB
 ...validate conceptmap-cdshooks-indicator                                 0.563 2550sec 1378MB
 ...validate conceptmap-example-metadata                                   0.622 2551sec 1378MB
 ...validate conceptmap-example-metadata-2                                 0.649 2551sec 1379MB
 ...validate conceptmap-example-priority                                    0.88 2552sec 1379MB
 ...validate conceptmap-message-adt-a04-to-bundle                           0.56 2553sec 1379MB
 ...validate condition-example                                              0.57 2553sec 1379MB
 ...validate condition-example2                                            0.578 2554sec 1378MB
 ...validate condition-example-f201-fever                                  0.544 2554sec 1378MB
 ...validate condition-example-f202-malignancy                             0.518 2555sec 1379MB
 ...validate condition-example-f203-sepsis                                 0.499 2555sec 1379MB
 ...validate condition-example-f204-renal                                  0.526 2556sec 1379MB
 ...validate condition-example-f205-infection                              0.532 2556sec 1379MB
 ...validate condition-example-f001-heart                                  0.588 2557sec 1379MB
 ...validate condition-example-f002-lung                                   0.671 2558sec 1379MB
 ...validate condition-example-f003-abscess                                0.733 2558sec 1379MB
 ...validate condition-example-stroke                                      0.796 2559sec 1379MB
 ...validate condition-example-family-history                              0.696 2560sec 1378MB
 ...validate condition-example-linkage                                     0.574 2560sec 1378MB
 ...validate conditiondefinition-example                                   0.583 2561sec 1379MB
 ...validate consent-example                                               0.574 2562sec 1379MB
 ...validate consent-example-Out                                           0.569 2562sec 1379MB
 ...validate consent-example-Emergency                                     0.535 2563sec 1379MB
 ...validate consent-example-notThis                                       0.537 2563sec 1379MB
 ...validate consent-example-notTime                                       0.621 2564sec 1379MB
 ...validate consent-example-notOrg                                        0.576 2564sec 1379MB
 ...validate consent-example-notThem                                       0.629 2565sec 1379MB
 ...validate consent-example-notAuthor                                     0.722 2566sec 1379MB
 ...validate consent-example-grantor                                        0.58 2566sec 1379MB
 ...validate consent-example-pkb                                           0.508 2567sec 1379MB
 ...validate consent-example-smartonfhir                                   0.614 2568sec 1379MB
 ...validate consent-example-CDA                                           0.605 2568sec 1379MB
 ...validate contract-example                                              0.601 2569sec 1379MB
 ...validate pcd-example-notOrg                                            0.709 2569sec 1379MB
 ...validate pcd-example-notThem                                           0.639 2570sec 1379MB
 ...validate pcd-example-notThis                                           0.684 2571sec 1379MB
 ...validate pcd-example-notAuthor                                         0.548 2571sec 1379MB
 ...validate pcd-example-notLabs                                           0.579 2572sec 1379MB
 ...validate contract-example-42cfr-part2                                  0.666 2573sec 1379MB
 ...validate contract-example-ins-policy                                   0.678 2573sec 1379MB
 ...validate coverage-example                                              0.561 2574sec 1379MB
 ...validate coverage-example-2                                            0.994 2575sec 1379MB
 ...validate coverage-example-ehic                                         0.865 2576sec 1379MB
 ...validate coverage-example-selfpay                                      0.858 2577sec 1379MB
 ...validate coverageeligibilityrequest-example                            0.861 2577sec 1379MB
 ...validate coverageeligibilityrequest-example-2                          0.533 2578sec 1379MB
 ...validate coverageeligibilityresponse-example                           0.543 2578sec 1379MB
 ...validate coverageeligibilityresponse-example-benefits                  0.533 2579sec 1379MB
 ...validate coverageeligibilityresponse-example-benefits-2                0.498 2579sec 1379MB
 ...validate coverageeligibilityresponse-example-error                     0.882 2580sec 1379MB
 ...validate detectedissue-example                                         0.831 2581sec 1379MB
 ...validate detectedissue-example-dup                                     0.993 2582sec 1379MB
 ...validate detectedissue-example-allergy                                 0.565 2583sec 1379MB
 ...validate detectedissue-example-lab                                     0.493 2583sec 1379MB
 ...validate device-example                                                0.531 2584sec 1379MB
 ...validate device-example-f001-feedingtube                               0.513 2584sec 1379MB
 ...validate device-example-AND20601BPMonitor                               0.56 2585sec 1379MB
 ...validate device-example-ANDThermometer                                 0.507 2585sec 1379MB
 ...validate device-example-AndroidGatewayPHG                              0.487 2586sec 1379MB
 ...validate device-example-Bodimetrics                                    0.493 2586sec 1379MB
 ...validate device-example-KinsaThermometer                               0.492 2587sec 1379MB
 ...validate device-example-Nonin20601PulseOx                              0.505 2587sec 1379MB
 ...validate device-example-NoninBlePulseOx                                 0.54 2588sec 1379MB
 ...validate device-example-PhilipsThermometer                             0.514 2588sec 1379MB
 ...validate device-example-RocheGlucoseMonitor                            0.497 2589sec 1379MB
 ...validate device-example-ihe-pcd                                        0.512 2589sec 1379MB
 ...validate device-example-pacemaker                                      0.542 2590sec 1379MB
 ...validate device-example-software                                       0.525 2590sec 1379MB
 ...validate device-example-udi1                                           0.514 2591sec 1379MB
 ...validate device-example-udi2                                           0.526 2592sec 1379MB
 ...validate device-example-udi3                                           0.563 2592sec 1379MB
 ...validate device-example-udi4                                           0.639 2593sec 1379MB
 ...validate devicedefinition-example                                      0.584 2593sec 1379MB
 ...validate devicedispense-example                                        0.695 2594sec 1379MB
 ...validate devicemetric-example                                          0.668 2595sec 1379MB
 ...validate devicerequest-example                                         0.765 2595sec 1379MB
 ...validate devicerequest-example-insulinpump                             0.835 2596sec 1379MB
 ...validate devicerequest-right-lens                                      0.609 2597sec 1379MB
 ...validate devicerequest-left-lens                                       0.578 2597sec 1379MB
 ...validate deviceusage-example                                           0.548 2598sec 1379MB
 ...validate diagnosticreport-example                                      0.555 2599sec 1379MB
 ...validate diagnosticreport-examples-general                             0.645 2599sec 1380MB
 ...validate diagnosticreport-example-f001-bloodexam                       2.215 2601sec 1390MB
 ...validate diagnosticreport-example-f201-brainct                          0.87 2602sec 1380MB
 ...validate diagnosticreport-example-f202-bloodculture                    0.749 2603sec 1380MB
 ...validate diagnosticreport-example-dxa                                  0.617 2604sec 1380MB
 ...validate diagnosticreport-micro1                                       0.533 2604sec 1380MB
 ...validate bundle-lri-example                                            0.629 2605sec 1381MB
 ...validate diagnosticreport-example-ultrasound                           0.641 2605sec 1381MB
 ...validate diagnosticreport-example-ghp                                  0.845 2606sec 1380MB
 ...validate diagnosticreport-example-papsmear                             0.793 2607sec 1382MB
 ...validate diagnosticreport-example-gingival-mass                        0.627 2608sec 1380MB
 ...validate diagnosticreport-example-gingival-biopsy                      4.817 2613sec 1383MB
 ...validate bundle-lipids                                                 4.228 2617sec 1383MB
 ...validate documentmanifest-example                                      0.549 2617sec 1383MB
 ...validate documentmanifest-fm-attachment                                 0.55 2618sec 1383MB
 ...validate xds-example                                                   0.536 2618sec 1382MB
 ...validate documentreference-example                                     0.527 2619sec 1382MB
 ...validate documentreference-example-diagram                             0.588 2620sec 1382MB
 ...validate documentreference-example-dicom                               0.606 2620sec 1382MB
 ...validate documentreference-example-sound                               0.844 2621sec 1382MB
 ...validate documentreference-example-xray                                0.663 2622sec 1382MB
 ...validate documentreference-example-comprehensive                       0.629 2622sec 1382MB
 ...validate documentreference-example-composition                         0.607 2623sec 1382MB
 ...validate documentreference-example-bundle                              0.533 2623sec 1382MB
 ...validate encounter-example                                             0.512 2624sec 1382MB
 ...validate encounter-example-home                                        0.534 2624sec 1382MB
 ...validate encounter-example-f201-20130404                               0.525 2625sec 1382MB
 ...validate encounter-example-f202-20130128                               0.569 2626sec 1382MB
 ...validate encounter-example-f203-20130311                               0.482 2626sec 1382MB
 ...validate encounter-example-f001-heart                                  0.554 2627sec 1382MB
 ...validate encounter-example-f002-lung                                   0.503 2627sec 1382MB
 ...validate encounter-example-f003-abscess                                0.532 2628sec 1382MB
 ...validate encounter-example-xcda                                        0.525 2628sec 1382MB
 ...validate encounter-example-emerg                                       0.582 2629sec 1382MB
 ...validate endpoint-example                                              0.707 2629sec 1382MB
 ...validate endpoint-examples-general-template                            0.881 2630sec 1382MB
 ...validate endpoint-example-iid                                          0.697 2631sec 1382MB
 ...validate endpoint-example-wadors                                       0.634 2632sec 1382MB
 ...validate endpoint-example-direct                                       0.673 2632sec 1382MB
 ...validate enrollmentrequest-example                                     0.572 2633sec 1382MB
 ...validate enrollmentresponse-example                                    0.548 2633sec 1382MB
 ...validate episodeofcare-example                                         0.563 2634sec 1382MB
 ...validate eventdefinition-example                                       0.621 2635sec 1382MB
 ...validate evidence-example-stroke-alteplase-fatalICH                    0.543 2635sec 1382MB
 ...validate evidence-example-stroke-no-alteplase-fatalICH                 0.605 2636sec 1382MB
 ...validate evidence-example-stroke-0-3-alteplase-vs-no-alteplase-mRS3-6   0.53 2636sec 1382MB
 ...validate evidence-example-stroke-3-4half-alteplase-vs-no-alteplase-mRS0-2 0.533 2637sec 1382MB
 ...validate evidence-example-ASTRAL-12-alteplase-mRS3-6                   0.523 2637sec 1382MB
 ...validate evidencereport-example                                        0.531 2638sec 1382MB
 ...validate evidencevariable-example-placebo                              0.572 2638sec 1382MB
 ...validate evidencevariable-example-no-alteplase                         0.548 2639sec 1382MB
 ...validate evidencevariable-example-alteplase-for-stroke                 0.485 2639sec 1382MB
 ...validate evidencevariable-example-fatal-ICH-in-7-days                  0.492 2640sec 1382MB
 ...validate evidencevariable-example-alive-independent-90day              0.489 2640sec 1382MB
 ...validate evidencevariable-example-dead-or-dependent-90day              0.762 2641sec 1382MB
 ...validate evidencevariable-example-mRS0-2-at-90days                     0.926 2642sec 1382MB
 ...validate evidencevariable-example-mRS3-6-at-90days                     0.664 2643sec 1382MB
 ...validate evidencevariable-example-Wardlaw2014Analysis1.16.3EvidenceSet 0.579 2643sec 1382MB
 ...validate evidencevariable-example-Stroke-Thrombolysis-Trialists-2014-2016-IPD-MA-Cohort 0.542 2644sec 1382MB
 ...validate evidencevariable-example-eligibility-criteria-diabetes-surgery  0.72 2645sec 1382MB
 ...validate evidencevariable-example-eligibility-criteria-ada-rec-bariatric 0.542 2645sec 1383MB
 ...validate evidencevariable-example-eligibility-criteria-adults-with-obesity 0.645 2646sec 1383MB
 ...validate examplescenario-example                                       0.943 2647sec 1382MB
 ...validate examplescenario-example-laborder                              0.932 2648sec 1382MB
 ...validate explanationofbenefit-example                                   0.58 2648sec 1383MB
 ...validate explanationofbenefit-example-2                                0.524 2649sec 1383MB
 ...validate familymemberhistory-example                                   0.551 2649sec 1383MB
 ...validate familymemberhistory-example-mother                            0.791 2650sec 1382MB
 ...validate familymemberhistory-example-negation                          0.695 2651sec 1382MB
 ...validate flag-example                                                  0.535 2651sec 1382MB
 ...validate flag-example-encounter                                        0.516 2652sec 1382MB
 ...validate formularyitemexample01                                        0.629 2653sec 1382MB
 ...validate genomicstudy-example                                          0.542 2653sec 1383MB
 ...validate genomicstudy-example-trio2                                    0.549 2654sec 1383MB
 ...validate genomicstudy-example-lungMass                                 0.519 2654sec 1383MB
 ...validate DocumentReference-CNVAnalysis_called                           0.56 2655sec 1383MB
 ...validate DocumentReference-genomicBEDfile                              0.521 2655sec 1383MB
 ...validate DocumentReference-genomicFile1                                0.583 2656sec 1383MB
 ...validate DocumentReference-genomicFile2                                0.585 2656sec 1383MB
 ...validate DocumentReference-genomicFile3                                0.561 2657sec 1383MB
 ...validate DocumentReference-genomicFile4                                 0.83 2658sec 1383MB
 ...validate DocumentReference-genomicVCFfile_cnv                          0.849 2659sec 1383MB
 ...validate DocumentReference-genomicVCFfile_simple                       0.748 2659sec 1383MB
 ...validate DocumentReference-genomicVCFfile                              0.806 2660sec 1383MB
 ...validate DocumentReference-SimpleVariantAnalysis_called                0.754 2661sec 1383MB
 ...validate DocumentReference-WES_FullSequencedRegion_GRCh38              0.911 2662sec 1383MB
 ...validate DocumentReference-genomicFileProband                          1.378 2663sec 1383MB
 ...validate DocumentReference-genomicFileMother                           0.569 2664sec 1383MB
 ...validate DocumentReference-genomicFileFather                           0.549 2664sec 1383MB
 ...validate DocumentReference-genomicFileGroupAsSubject                   0.704 2665sec 1383MB
 ...validate Device-NGS-device                                             0.674 2666sec 1383MB
 ...validate Device-Triodenovo-SW                                          0.689 2666sec 1383MB
 ...validate Encounter-denovoEncounter                                     0.608 2667sec 1383MB
 ...validate Encounter-genomicEncounter                                    0.548 2668sec 1383MB
 ...validate Group-denovoFamily                                            0.543 2668sec 1383MB
 ...validate Patient-denovoChild                                           0.651 2669sec 1383MB
 ...validate Patient-denovoFather                                          0.493 2669sec 1383MB
 ...validate Patient-denovoMother                                          0.573 2670sec 1383MB
 ...validate Patient-genomicPatient                                        0.503 2670sec 1383MB
 ...validate Practitioner-practitioner01                                   0.543 2671sec 1383MB
 ...validate Practitioner-practitioner02                                   0.478 2671sec 1383MB
 ...validate RelatedPerson-denovoMother                                    0.523 2672sec 1383MB
 ...validate RelatedPerson-denovoFather                                    0.486 2672sec 1383MB
 ...validate ServiceRequest-genomicServiceRequest                          0.479 2673sec 1383MB
 ...validate ServiceRequest-genomicServiceRequest2                          0.49 2673sec 1383MB
 ...validate ServiceRequest-genomicServiceRequest3                         0.514 2674sec 1383MB
 ...validate ServiceRequest-genomicServiceRequest4                         0.585 2674sec 1383MB
 ...validate ServiceRequest-genomicSRProband                               0.499 2675sec 1383MB
 ...validate ServiceRequest-genomicSRMother                                0.583 2676sec 1383MB
 ...validate ServiceRequest-genomicSRFather                                0.512 2676sec 1383MB
 ...validate Specimen-denovo-1                                             0.566 2677sec 1383MB
 ...validate Specimen-denovo-2                                             0.515 2677sec 1383MB
 ...validate Specimen-denovo-3                                             0.557 2678sec 1383MB
 ...validate Specimen-specimenProband                                      0.497 2678sec 1383MB
 ...validate Specimen-specimenMother                                       0.572 2679sec 1383MB
 ...validate Specimen-specimenFather                                       0.523 2679sec 1383MB
 ...validate Specimen-genomicSpecimen                                      0.666 2680sec 1383MB
 ...validate goal-example                                                  0.564 2680sec 1383MB
 ...validate goal-example-stop-smoking                                     0.545 2681sec 1383MB
 ...validate graphdefinition-example                                       0.531 2682sec 1383MB
 ...validate group-example                                                 0.574 2682sec 1383MB
 ...validate group-example-member                                          0.577 2683sec 1383MB
 ...validate group-example-herd1                                           0.558 2683sec 1383MB
 ...validate group-example-patientlist                                     0.604 2684sec 1383MB
 ...validate guidanceresponse-example                                      0.597 2684sec 1383MB
 ...validate healthcareservice-example                                     0.594 2685sec 1383MB
 ...validate imagingselection-example-basic-image-selection                0.581 2686sec 1383MB
 ...validate imagingselection-example-multiframe-image-selection           0.547 2686sec 1383MB
 ...validate imagingselection-example-segmentation-image-selection         0.537 2687sec 1383MB
 ...validate imagingselection-example-dicom-sr-selection                   0.636 2687sec 1383MB
 ...validate imagingselection-example-presentation-state-selection         0.615 2688sec 1383MB
 ...validate imagingselection-example-2d-image-region-selection            0.587 2689sec 1383MB
 ...validate imagingselection-example-3d-image-region-selection            0.549 2689sec 1383MB
 ...validate imagingstudy-example                                          0.594 2690sec 1383MB
 ...validate imagingstudy-example-xr                                       0.619 2690sec 1383MB
 ...validate immunization-example                                          1.069 2691sec 1383MB
 ...validate immunization-example-reaction                                 0.533 2692sec 1383MB
 ...validate immunization-example-refused                                   0.74 2693sec 1383MB
 ...validate immunization-example-historical                               0.521 2693sec 1383MB
 ...validate immunization-example-subpotent                                0.509 2694sec 1383MB
 ...validate immunization-example-protocol                                   0.5 2694sec 1383MB
 ...validate immunizationevaluation-example                                0.602 2695sec 1383MB
 ...validate immunizationevaluation-example-notvalid                       0.518 2695sec 1383MB
 ...validate immunizationrecommendation-example                            0.493 2696sec 1383MB
 ...validate immunizationrecommendation-example-target-disease             0.523 2696sec 1383MB
 ...validate implementationguide-example                                   0.512 2697sec 1383MB
 ...validate ingredient-example                                            0.603 2697sec 1383MB
 ...validate insuranceplan-example                                          0.51 2698sec 1383MB
 ...validate inventoryreport-example                                       0.565 2699sec 1383MB
 ...validate invoice-example                                               0.536 2699sec 1383MB
 ...validate library-example                                               0.538 2700sec 1383MB
 ...validate library-exclusive-breastfeeding-cds-logic                     3.086 2703sec 1384MB
 ...validate library-exclusive-breastfeeding-cqm-logic                     0.875 2704sec 1384MB
 ...validate library-cms146-example                                        1.172 2705sec 1384MB
 ...validate library-quick-model-definition                                1.084 2706sec 1384MB
 ...validate library-fhir-model-definition                                 0.799 2707sec 1384MB
 ...validate library-mmi-suiciderisk-orderset-logic                        7.767 2714sec 1386MB
 ...validate library-fhir-helpers                                          1.201 2716sec 1384MB
 ...validate library-zika-virus-intervention-logic                         0.806 2716sec 1384MB
 ...validate library-composition-example                                   1.304 2718sec 1384MB
 ...validate library-predecessor-example                                   1.338 2719sec 1384MB
 ...validate library-omtk-logic                                            0.795 2720sec 1384MB
 ...validate library-omtk-modelinfo                                        0.843 2721sec 1385MB
 ...validate library-opioidcds-common                                       0.43 2721sec 1384MB
 ...validate library-opioidcds-recommendation-04                           0.457 2722sec 1384MB
 ...validate library-opioidcds-recommendation-05                           0.486 2722sec 1384MB
 ...validate library-opioidcds-recommendation-07                           0.484 2723sec 1384MB
 ...validate library-opioidcds-recommendation-08                           0.505 2723sec 1384MB
 ...validate library-opioidcds-recommendation-10                           0.528 2724sec 1384MB
 ...validate library-opioidcds-recommendation-11                           0.497 2724sec 1384MB
 ...validate library-hiv-indicators                                        0.524 2725sec 1384MB
 ...validate linkage-example                                               0.845 2725sec 1385MB
 ...validate list-example                                                  0.504 2726sec 1384MB
 ...validate list-example-empty                                             0.48 2726sec 1384MB
 ...validate list-example-simple-empty                                     0.469 2727sec 1384MB
 ...validate list-example-medlist                                          0.787 2728sec 1384MB
 ...validate list-example-familyhistory-f201-roel                          0.924 2729sec 1384MB
 ...validate list-example-familyhistory-genetics-profile                   0.635 2729sec 1384MB
 ...validate list-example-familyhistory-genetics-profile-annie             1.788 2731sec 1385MB
 ...validate list-example-allergies                                        2.767 2734sec 1385MB
 ...validate list-example-double-cousin-relationship-pedigree              0.636 2734sec 1384MB
 ...validate list-example-long                                             0.801 2735sec 1384MB
 ...validate location-example                                              0.889 2736sec 1385MB
 ...validate location-example-room                                          0.63 2737sec 1384MB
 ...validate location-example-ambulance                                    0.551 2737sec 1384MB
 ...validate location-example-patients-home                                0.595 2738sec 1384MB
 ...validate location-example-ukpharmacy                                   0.579 2738sec 1384MB
 ...validate location-example-hl7hq                                        0.554 2739sec 1384MB
 ...validate location-examples-general                                     0.539 2740sec 1384MB
 ...validate location-wash-dc-metro                                        0.619 2740sec 1384MB
 ...validate manufactureditemdefinition-example                            0.546 2741sec 1384MB
 ...validate measure-exclusive-breastfeeding                               0.528 2741sec 1384MB
 ...validate measure-cms146-example                                        4.432 2746sec 1384MB
 ...validate measure-component-a-example                                   0.407 2746sec 1385MB
 ...validate measure-component-b-example                                   2.525 2749sec 1385MB
 ...validate measure-composite-example                                     2.054 2751sec 1385MB
 ...validate measure-predecessor-example                                   1.228 2752sec 1385MB
 ...validate measure-hiv-indicators                                        4.762 2757sec 1385MB
 ...validate measurereport-cms146-cat3-example                             0.767 2757sec 1386MB
 ...validate measurereport-cms146-cat1-example                             19.103 2777sec 1386MB
 ...validate measurereport-hiv-indicators                                  17.205 2794sec 1386MB
 ...validate measurereport-general-example                                 0.409 2794sec 1386MB
 ...validate medicationexample1                                             0.44 2795sec 1386MB
 ...validate medicationexample15                                           0.422 2795sec 1386MB
 ...validate medicationexample0301                                          0.43 2795sec 1386MB
 ...validate medicationexample0302                                         0.407 2796sec 1386MB
 ...validate medicationexample0303                                         0.418 2796sec 1386MB
 ...validate medicationexample0304                                         0.424 2797sec 1386MB
 ...validate medicationexample0305                                         0.443 2797sec 1386MB
 ...validate medicationexample0306                                         0.493 2798sec 1386MB
 ...validate medicationexample0307                                          0.46 2798sec 1386MB
 ...validate medicationexample0308                                         0.529 2799sec 1386MB
 ...validate medicationexample0309                                         0.491 2799sec 1386MB
 ...validate medicationexample0310                                         0.498 2800sec 1386MB
 ...validate medicationexample0311                                         0.463 2800sec 1386MB
 ...validate medicationexample0312                                         0.508 2801sec 1386MB
 ...validate medicationexample0313                                         0.454 2801sec 1386MB
 ...validate medicationexample0314                                          0.45 2801sec 1386MB
 ...validate medicationexample0315                                         0.461 2802sec 1386MB
 ...validate medicationexample0316                                         0.455 2802sec 1386MB
 ...validate medicationexample0317                                         0.468 2803sec 1386MB
 ...validate medicationexample0318                                         0.437 2803sec 1386MB
 ...validate medicationexample0319                                         0.468 2804sec 1386MB
 ...validate medicationexample0320                                         0.452 2804sec 1386MB
 ...validate medicationexample0321                                         0.457 2805sec 1386MB
 ...validate medicationexample0323                                          0.47 2805sec 1386MB
 ...validate medicationadministrationexample3                              0.488 2806sec 1386MB
 ...validate medicationadministration0301                                  0.447 2806sec 1386MB
 ...validate medicationadministration0302                                  0.481 2807sec 1386MB
 ...validate medicationadministration0303                                   0.45 2807sec 1386MB
 ...validate medicationadministration0304                                   0.48 2807sec 1386MB
 ...validate medicationadministration0305                                  0.465 2808sec 1386MB
 ...validate medicationadministration0306                                   0.47 2808sec 1386MB
 ...validate medicationadministration0307                                  0.438 2809sec 1386MB
 ...validate medicationadministration0308                                  0.447 2809sec 1386MB
 ...validate medicationadministration0309                                  0.509 2810sec 1386MB
 ...validate medicationadministration0310                                  0.457 2810sec 1386MB
 ...validate medicationadministration0311                                  0.587 2811sec 1386MB
 ...validate medicationadministration0312                                  0.473 2811sec 1386MB
 ...validate medicationadministration0313                                  0.539 2812sec 1386MB
 ...validate medicationdispenseexample8                                    0.472 2812sec 1386MB
 ...validate medicationdispense0301                                        0.587 2813sec 1386MB
 ...validate medicationdispense0302                                        0.505 2813sec 1386MB
 ...validate medicationdispense0303                                         0.44 2814sec 1386MB
 ...validate medicationdispense0304                                        0.447 2814sec 1386MB
 ...validate medicationdispense0305                                        0.485 2815sec 1386MB
 ...validate medicationdispense0306                                        0.473 2815sec 1386MB
 ...validate medicationdispense0307                                         0.46 2816sec 1386MB
 ...validate medicationdispense0308                                        0.436 2816sec 1386MB
 ...validate medicationdispense0309                                        0.487 2817sec 1386MB
 ...validate medicationdispense0310                                         0.43 2817sec 1386MB
 ...validate medicationdispense0311                                        0.525 2818sec 1386MB
 ...validate medicationdispense0312                                        0.457 2818sec 1386MB
 ...validate medicationdispense0313                                         0.47 2819sec 1386MB
 ...validate medicationdispense0314                                        0.431 2819sec 1386MB
 ...validate medicationdispense0315                                         1.25 2820sec 1386MB
 ...validate medicationdispense0316                                        0.464 2821sec 1386MB
 ...validate medicationdispense0317                                        0.736 2821sec 1386MB
 ...validate medicationdispense0318                                        0.955 2822sec 1386MB
 ...validate medicationdispense0319                                        0.523 2823sec 1386MB
 ...validate medicationdispense0320                                        0.459 2823sec 1386MB
 ...validate medicationdispense0321                                        0.448 2824sec 1386MB
 ...validate medicationdispense0322                                        0.421 2824sec 1386MB
 ...validate medicationdispense0324                                        0.826 2825sec 1386MB
 ...validate medicationdispense0325                                        0.617 2826sec 1386MB
 ...validate medicationdispense0326                                        0.449 2826sec 1386MB
 ...validate medicationdispense0327                                        0.458 2827sec 1386MB
 ...validate medicationdispense0328                                        0.454 2827sec 1386MB
 ...validate medicationdispense0329                                        0.433 2827sec 1386MB
 ...validate medicationdispense0330                                        0.447 2828sec 1386MB
 ...validate medicationdispense0331                                        0.438 2828sec 1386MB
 ...validate medicationdispense0332                                        0.423 2829sec 1386MB
 ...validate medicationknowledge-example                                   0.435 2829sec 1386MB
 ...validate medicationrequestexample2                                       0.6 2830sec 1386MB
 ...validate medicationrequest0302                                         0.502 2830sec 1386MB
 ...validate medicationrequest0301                                         0.479 2831sec 1386MB
 ...validate medicationrequest0303                                          0.44 2831sec 1386MB
 ...validate medicationrequest0304                                         0.447 2832sec 1386MB
 ...validate medicationrequest0305                                          0.45 2832sec 1386MB
 ...validate medicationrequest0306                                         0.472 2833sec 1386MB
 ...validate medicationrequest0307                                          0.45 2833sec 1386MB
 ...validate medicationrequest0308                                         0.489 2834sec 1386MB
 ...validate medicationrequest0309                                         0.432 2834sec 1386MB
 ...validate medicationrequest0310                                         0.434 2834sec 1386MB
 ...validate medicationrequestexample1                                      0.51 2835sec 1386MB
 ...validate medicationrequest0312                                         0.474 2835sec 1386MB
 ...validate medicationrequest0313                                         0.472 2836sec 1386MB
 ...validate medicationrequest0314                                         0.489 2836sec 1386MB
 ...validate medicationrequest0315                                         0.527 2837sec 1386MB
 ...validate medicationrequest0316                                         0.435 2837sec 1386MB
 ...validate medicationrequest0317                                         0.468 2838sec 1386MB
 ...validate medicationrequest0318                                         0.445 2838sec 1386MB
 ...validate medicationrequest0319                                         0.462 2839sec 1386MB
 ...validate medicationrequest0320                                         0.467 2839sec 1386MB
 ...validate medicationrequest0321                                         0.478 2840sec 1386MB
 ...validate medicationrequest0322                                         0.471 2840sec 1386MB
 ...validate medicationrequest0323                                         0.752 2841sec 1386MB
 ...validate medicationrequest0324                                         0.495 2841sec 1386MB
 ...validate medicationrequest0325                                         0.469 2842sec 1386MB
 ...validate medicationrequest0326                                         0.483 2842sec 1386MB
 ...validate medicationrequest0327                                         0.508 2843sec 1386MB
 ...validate medicationrequest0328                                         0.455 2843sec 1386MB
 ...validate medicationrequest0329                                         0.486 2844sec 1386MB
 ...validate medicationrequest0330                                         0.482 2844sec 1386MB
 ...validate medicationrequest0331                                         0.535 2845sec 1386MB
 ...validate medicationrequest0332                                         0.434 2845sec 1386MB
 ...validate medicationrequest0333                                         0.457 2846sec 1386MB
 ...validate medicationrequest0334                                          0.46 2846sec 1386MB
 ...validate medicationrequest0335                                          0.49 2847sec 1386MB
 ...validate medicationrequest0336                                         0.439 2847sec 1386MB
 ...validate medicationrequest0337                                         0.493 2848sec 1386MB
 ...validate medicationrequest0338                                         0.455 2848sec 1386MB
 ...validate medicationrequest0339                                         0.464 2848sec 1386MB
 ...validate medicationrequest0343a                                        0.499 2849sec 1386MB
 ...validate medicationrequest0343b                                        0.534 2849sec 1386MB
 ...validate medicationusageexample1                                       0.529 2850sec 1386MB
 ...validate medicationusageexample2                                       0.521 2851sec 1386MB
 ...validate medicationusageexample4                                       0.477 2851sec 1386MB
 ...validate medicationusageexample5                                       0.536 2852sec 1386MB
 ...validate medicationusageexample6                                       0.661 2852sec 1386MB
 ...validate medicationusageexample7                                       0.441 2853sec 1386MB
 ...validate medicationusageexample3                                       0.493 2853sec 1386MB
 ...validate medicinalproductdefinition-example                            0.469 2854sec 1386MB
 ...validate medicinalproductdefinition-example-equilidem-basics           0.738 2854sec 1386MB
 ...validate medicinalproductdefinition-example-equilidem-using-ingredient-and-auth 0.503 2855sec 1386MB
 ...validate medicinalproductdefinition-example-co-packaged-liquid-and-syringe 0.469 2855sec 1386MB
 ...validate medicinalproductdefinition-example-co-packaged-liquid-and-syringe-complete 0.456 2856sec 1386MB
 ...validate medicinalproductdefinition-acetaminophen-500mg-tablets-box-of-20 0.449 2856sec 1386MB
 ...validate medicinalproductdefinition-example-combo-product              0.453 2857sec 1386MB
 ...validate medicinalproductdefinition-example-combo-product-bundle       0.458 2857sec 1386MB
 ...validate medicinalproductdefinition-with-contained-package-and-ingredient 0.453 2858sec 1386MB
 ...validate messagedefinition-example                                     0.444 2858sec 1386MB
 ...validate messagedefinition-patient-link-notification                   0.518 2859sec 1386MB
 ...validate messagedefinition-patient-link-response                        0.45 2859sec 1386MB
 ...validate messageheader-example                                         0.469 2859sec 1386MB
 ...validate message-request-link                                          0.482 2860sec 1386MB
 ...validate message-response-link                                         0.481 2860sec 1386MB
 ...validate molecularsequence-example                                     0.483 2861sec 1387MB
 ...validate sequence-complex-variant                                      0.432 2861sec 1386MB
 ...validate sequence-example-pgx-1                                        0.458 2862sec 1387MB
 ...validate sequence-example-pgx-2                                        0.462 2862sec 1387MB
 ...validate sequence-example-TPMT-one                                     0.456 2863sec 1387MB
 ...validate sequence-example-TPMT-two                                     0.504 2863sec 1387MB
 ...validate coord-0base-example                                           0.448 2864sec 1387MB
 ...validate coord-1base-example                                           0.452 2864sec 1387MB
 ...validate sequence-genetics-example-breastcancer                        0.465 2865sec 1387MB
 ...validate sequence-example-ordinal                                      0.485 2865sec 1386MB
 ...validate sequence-example-fusion                                       0.463 2866sec 1387MB
 ...validate namingsystem-example                                          0.438 2866sec 1387MB
 ...validate namingsystem-example-id                                       0.476 2866sec 1387MB
 ...validate namingsystem-registry                                         0.477 2867sec 1387MB
 ...validate namingsystem-example-metadata                                 0.445 2867sec 1387MB
 ...validate namingsystem-example-metadata-2                               0.656 2868sec 1387MB
 ...validate nutritionintake-example                                        0.48 2869sec 1387MB
 ...validate nutritionorder-example-pureeddiet-simple                      0.458 2869sec 1387MB
 ...validate nutritionorder-example-cardiacdiet                            0.529 2870sec 1387MB
 ...validate nutritionorder-example-diabeticdiet                           0.475 2870sec 1387MB
 ...validate nutritionorder-example-texture-modified                       0.481 2870sec 1387MB
 ...validate nutritionorder-example-pureeddiet                             0.623 2871sec 1387MB
 ...validate nutritionorder-example-renaldiet                              0.513 2872sec 1387MB
 ...validate nutritionorder-example-fiberrestricteddiet                    0.493 2872sec 1387MB
 ...validate nutritionorder-example-diabeticsupplement                     0.508 2873sec 1387MB
 ...validate nutritionorder-example-proteinsupplement                      0.481 2873sec 1387MB
 ...validate nutritionorder-example-energysupplement                       0.642 2874sec 1387MB
 ...validate nutritionorder-example-enteralbolus                           0.849 2875sec 1387MB
 ...validate nutritionorder-example-enteralcontinuous                      0.695 2875sec 1387MB
 ...validate nutritionorder-example-infantenteral                          1.539 2877sec 1387MB
 ...validate nutritionproduct-example                                      0.593 2877sec 1387MB
 ...validate observation-example                                           0.803 2878sec 1387MB
 ...validate observation-example-respiratory-rate                          0.579 2879sec 1387MB
 ...validate observation-example-heart-rate                                0.717 2880sec 1387MB
 ...validate observation-example-body-temperature                          0.669 2880sec 1387MB
 ...validate observation-example-body-height                               0.546 2881sec 1387MB
 ...validate observation-example-body-length                                0.95 2882sec 1387MB
 ...validate observation-example-head-circumference                        0.588 2882sec 1387MB
 ...validate observation-example-bmi                                       0.615 2883sec 1387MB
 ...validate observation-example-bmi-using-related                         0.605 2883sec 1387MB
 ...validate observation-example-satO2                                     0.592 2884sec 1387MB
 ...validate observation-example-bloodpressure                             0.634 2885sec 1387MB
 ...validate observation-example-bloodpressure-dar                         0.609 2885sec 1387MB
 ...validate observation-example-mbp                                       0.953 2886sec 1387MB
 ...validate observation-example-vitals-panel                              0.507 2887sec 1387MB
 ...validate observation-example-bloodpressure-cancel                      0.514 2887sec 1387MB
 ...validate observation-example-f001-glucose                              0.538 2888sec 1387MB
 ...validate observation-example-unsat                                     0.459 2888sec 1387MB
 ...validate observation-example-f002-excess                               0.511 2889sec 1387MB
 ...validate observation-example-f003-co2                                  0.466 2889sec 1387MB
 ...validate observation-example-f004-erythrocyte                          0.566 2890sec 1387MB
 ...validate observation-example-f005-hemoglobin                           0.503 2890sec 1387MB
 ...validate observation-example-date-lastmp                               0.478 2891sec 1387MB
 ...validate observation-example-f202-temperature                          0.491 2891sec 1387MB
 ...validate observation-example-f203-bicarbonate                          0.472 2892sec 1387MB
 ...validate observation-example-f204-creatinine                           0.491 2892sec 1387MB
 ...validate observation-example-f205-egfr                                   0.5 2893sec 1387MB
 ...validate observation-example-f206-staphylococcus                       0.511 2893sec 1387MB
 ...validate observation-example-sample-data                               0.476 2894sec 1387MB
 ...validate observation-example-glasgow                                   0.481 2894sec 1387MB
 ...validate observation-example-glasgow-qa                                0.589 2895sec 1387MB
 ...validate observation-example-1minute-apgar-score                       0.544 2895sec 1387MB
 ...validate observation-example-2minute-apgar-score                       0.548 2896sec 1387MB
 ...validate observation-example-5minute-apgar-score                       0.624 2897sec 1387MB
 ...validate observation-example-10minute-apgar-score                      0.569 2897sec 1387MB
 ...validate observation-example-20minute-apgar-score                      0.649 2898sec 1387MB
 ...validate observation-example-clinical-gender                           0.621 2898sec 1387MB
 ...validate observation-example-eye-color                                 0.456 2899sec 1387MB
 ...validate observation-example-bmd                                       0.494 2899sec 1387MB
 ...validate observation-example-spirometry                                0.489 2900sec 1387MB
 ...validate observation-example-alcohol-type                              0.523 2900sec 1387MB
 ...validate observation-example-vp-oyster                                 0.527 2901sec 1387MB
 ...validate observation-example-herd1                                     0.544 2901sec 1387MB
 ...validate observation-example-vomiting                                  0.529 2902sec 1387MB
 ...validate observation-example-secondsmoke                               0.549 2902sec 1387MB
 ...validate observation-example-trachcare                                 0.641 2903sec 1387MB
 ...validate observation-example-bgpanel                                   0.527 2904sec 1387MB
 ...validate observation-example-bloodgroup                                0.471 2904sec 1387MB
 ...validate observation-example-rhstatus                                  0.531 2905sec 1387MB
 ...validate observation-decimal                                           0.501 2905sec 1387MB
 ...validate observation-example-map-sitting                               0.523 2906sec 1387MB
 ...validate observation-example-abdo-tender                               0.515 2906sec 1387MB
 ...validate krcore-observation-labresult-example-01                       0.527 2907sec 1387MB
 ...validate observation-example-body-weight-with-arabic-code              0.457 2907sec 1387MB
 ...validate observationdefinition-example                                 0.472 2908sec 1387MB
 ...validate operationdefinition-example                                   0.584 2908sec 1387MB
 ...validate operation-valueset-expand                                     0.526 2909sec 1387MB
 ...validate operation-valueset-validate-code                              0.526 2909sec 1387MB
 ...validate operation-codesystem-lookup                                   0.579 2910sec 1387MB
 ...validate operation-conceptmap-translate                                0.597 2910sec 1387MB
 ...validate operation-conceptmap-closure                                  0.584 2911sec 1387MB
 ...validate operation-library-data-requirements                           0.565 2912sec 1387MB
 ...validate operation-measure-data-requirements                            0.53 2912sec 1387MB
 ...validate operation-measure-evaluate-measure                            0.491 2913sec 1387MB
 ...validate operationdefinition-example-query-high-risk                   1.412 2914sec 1387MB
 ...validate operationoutcome-example                                      0.777 2915sec 1387MB
 ...validate operationoutcome-example-exception                             0.54 2915sec 1387MB
 ...validate operationoutcome-example-allok                                0.512 2916sec 1387MB
 ...validate operationoutcome-example-validationfail                       0.511 2916sec 1387MB
 ...validate operationoutcome-example-searchfail                           0.473 2917sec 1387MB
 ...validate operationoutcome-example-break-the-glass                      0.488 2917sec 1387MB
 ...validate organization-example                                          0.493 2918sec 1387MB
 ...validate organization-example-gastro                                   0.597 2918sec 1387MB
 ...validate organization-example-lab                                      0.514 2919sec 1387MB
 ...validate organization-example-insurer                                  0.476 2919sec 1387MB
 ...validate organization-example-good-health-care                         0.556 2920sec 1387MB
 ...validate organization-example-f001-burgers                             0.479 2920sec 1387MB
 ...validate organization-example-f002-burgers-card                        0.486 2921sec 1387MB
 ...validate organization-example-f201-aumc                                0.497 2921sec 1387MB
 ...validate organization-example-f203-bumc                                0.499 2922sec 1387MB
 ...validate organization-example-f003-burgers-ENT                         0.466 2922sec 1387MB
 ...validate organization-example-mmanu                                    0.477 2923sec 1387MB
 ...validate organization-example-mihealth                                   0.5 2923sec 1387MB
 ...validate organization-example-hl7pay                                   0.485 2924sec 1387MB
 ...validate organizationaffiliation-example                               0.473 2924sec 1387MB
 ...validate orgrole-example-hie                                            0.51 2925sec 1387MB
 ...validate orgrole-example-services                                       0.51 2925sec 1387MB
 ...validate packagedproductdefinition-example                             0.457 2926sec 1387MB
 ...validate packagedproductdefinition-example-co-packaged-liquid-and-syringe 0.505 2926sec 1387MB
 ...validate patient-example                                               0.474 2927sec 1387MB
 ...validate patient-example-a                                             0.512 2927sec 1387MB
 ...validate patient-example-b                                             0.469 2928sec 1387MB
 ...validate patient-example-c                                             0.494 2928sec 1387MB
 ...validate patient-example-d                                             0.473 2929sec 1387MB
 ...validate patient-examples-general                                      0.458 2929sec 1387MB
 ...validate patient-example-sex-and-gender                                 0.77 2930sec 1388MB
 ...validate patient-examples-cypress-template                             3.625 2934sec 1388MB
 ...validate patient-example-xcda                                          0.919 2935sec 1393MB
 ...validate patient-example-xds                                            0.69 2935sec 1387MB
 ...validate patient-example-animal                                        0.469 2936sec 1387MB
 ...validate patient-example-dicom                                         0.532 2936sec 1387MB
 ...validate patient-example-ihe-pcd                                       0.463 2937sec 1387MB
 ...validate patient-example-f001-pieter                                   0.454 2937sec 1387MB
 ...validate patient-example-f201-roel                                     0.466 2938sec 1387MB
 ...validate patient-glossy-example                                        0.448 2938sec 1388MB
 ...validate patient-example-proband                                       0.503 2939sec 1387MB
 ...validate patient-genetics-example1                                     0.591 2939sec 1387MB
 ...validate patient-example-chinese                                       0.534 2940sec 1387MB
 ...validate patient-example-newborn                                       0.483 2940sec 1387MB
 ...validate patient-example-mom                                           0.533 2941sec 1387MB
 ...validate patient-example-infant-twin-1                                 0.864 2942sec 1387MB
 ...validate patient-example-infant-twin-2                                 0.658 2942sec 1387MB
 ...validate patient-example-infant-fetal                                  0.508 2943sec 1387MB
 ...validate patient-example-infant-mom                                    0.504 2943sec 1387MB
 ...validate paymentnotice-example                                         0.499 2944sec 1387MB
 ...validate paymentreconciliation-example                                 0.734 2944sec 1388MB
 ...validate permission-example                                            0.752 2945sec 1388MB
 ...validate permission-example-saner                                      0.511 2946sec 1388MB
 ...validate permission-example-vhdir                                      0.513 2946sec 1388MB
 ...validate person-example                                                 0.54 2947sec 1388MB
 ...validate person-grahame                                                0.534 2947sec 1388MB
 ...validate person-patient-portal                                         0.488 2948sec 1388MB
 ...validate person-provider-directory                                     0.499 2948sec 1388MB
 ...validate person-example-f002-ariadne                                   0.491 2949sec 1388MB
 ...validate plandefinition-example                                        0.485 2949sec 1388MB
 ...validate plandefinition-chlamydia-screening-intervention               0.718 2950sec 1388MB
 ...validate plandefinition-exclusive-breastfeeding-intervention-01        0.573 2951sec 1388MB
 ...validate plandefinition-exclusive-breastfeeding-intervention-02         2.57 2953sec 1388MB
 ...validate plandefinition-exclusive-breastfeeding-intervention-03        1.167 2954sec 1388MB
 ...validate plandefinition-exclusive-breastfeeding-intervention-04        4.053 2958sec 1388MB
 ...validate plandefinition-protocol-example                               0.895 2959sec 1388MB
 ...validate plandefinition-example-kdn5-simplified                        1.098 2960sec 1388MB
 ...validate plandefinition-zika-virus-intervention                         0.59 2961sec 1388MB
 ...validate plandefinition-options-example                                0.491 2961sec 1388MB
 ...validate plandefinition-predecessor-example                            0.503 2962sec 1388MB
 ...validate plandefinition-opioidcds-04                                   0.465 2962sec 1388MB
 ...validate plandefinition-opioidcds-05                                   0.497 2963sec 1388MB
 ...validate plandefinition-opioidcds-07                                   0.471 2963sec 1388MB
 ...validate plandefinition-opioidcds-08                                   0.461 2964sec 1388MB
 ...validate plandefinition-opioidcds-10                                   0.434 2964sec 1388MB
 ...validate plandefinition-opioidcds-11                                   0.563 2965sec 1388MB
 ...validate plandefinition-example-cardiology-os                           0.44 2965sec 1388MB
 ...validate practitioner-example                                          1.128 2966sec 1388MB
 ...validate practitioner-example-xcda-author                              0.466 2967sec 1388MB
 ...validate practitioner-examples-general                                 0.433 2967sec 1388MB
 ...validate practitioner-example-f001-evdb                                0.504 2968sec 1389MB
 ...validate practitioner-example-f002-pv                                  0.457 2968sec 1388MB
 ...validate practitioner-example-f003-mv                                   0.47 2969sec 1388MB
 ...validate practitioner-example-f004-rb                                  0.487 2969sec 1388MB
 ...validate practitioner-example-f005-al                                  0.469 2970sec 1388MB
 ...validate practitioner-example-f201-ab                                  0.433 2970sec 1388MB
 ...validate practitioner-example-f202-lm                                  0.576 2971sec 1388MB
 ...validate practitioner-example-f203-jvg                                 0.599 2971sec 1388MB
 ...validate practitioner-example-f204-ce                                  0.514 2972sec 1388MB
 ...validate practitioner-example-f006-rvdb                                0.726 2973sec 1388MB
 ...validate practitioner-example-f007-sh                                  0.533 2973sec 1388MB
 ...validate practitioner-example-xcda1                                    0.515 2974sec 1388MB
 ...validate practitionerrole-example                                      0.495 2974sec 1388MB
 ...validate practitionerrole-examples-general                             0.538 2975sec 1388MB
 ...validate procedure-example                                             0.509 2975sec 1388MB
 ...validate procedure-example-biopsy                                      0.492 2976sec 1388MB
 ...validate procedure-example-f201-tpf                                    0.434 2976sec 1388MB
 ...validate procedure-example-f001-heart                                   0.48 2977sec 1388MB
 ...validate procedure-example-f002-lung                                   0.459 2977sec 1388MB
 ...validate procedure-example-f003-abscess                                0.444 2977sec 1388MB
 ...validate procedure-example-f004-tracheotomy                            0.483 2978sec 1388MB
 ...validate procedure-example-implant                                     0.461 2978sec 1388MB
 ...validate procedure-example-ambulation                                  0.558 2979sec 1388MB
 ...validate procedure-example-colon-biopsy                                0.524 2979sec 1388MB
 ...validate procedure-example-colonoscopy                                 0.659 2980sec 1388MB
 ...validate procedure-example-appendectomy-narrative                      0.502 2981sec 1388MB
 ...validate procedure-example-ob                                          0.507 2981sec 1388MB
 ...validate procedure-example-physical-therapy                            0.509 2982sec 1388MB
 ...validate procedure-example-education                                   0.505 2982sec 1388MB
 ...validate procedure-example-HCBS                                        0.515 2983sec 1388MB
 ...validate provenance-example                                            0.598 2983sec 1388MB
 ...validate provenance-example1                                           0.518 2984sec 1388MB
 ...validate provenance-example2                                           0.519 2984sec 1388MB
 ...validate provenance-example3                                            0.54 2985sec 1388MB
 ...validate provenance-example-sig                                        0.495 2985sec 1388MB
 ...validate provenance-consent-signature                                    0.5 2986sec 1388MB
 ...validate provenance-example-biocompute-object                          0.622 2986sec 1388MB
 ...validate provenance-example-cwl                                        0.534 2987sec 1388MB
 ...validate provenance-example-create-consent                             0.506 2987sec 1388MB
 ...validate provenance-example-advanced                                   0.493 2988sec 1388MB
 ...validate provenance-example-diagnosticreport-sig                       0.501 2988sec 1388MB
 ...validate provenance-example-import                                     0.601 2989sec 1388MB
 ...validate provenance-example-delete                                     0.619 2990sec 1388MB
 ...validate provenance-example-anon0                                      0.634 2990sec 1388MB
 ...validate questionnaire-example                                         0.527 2991sec 1388MB
 ...validate questionnaire-example-f201-lifelines                          0.617 2991sec 1388MB
 ...validate questionnaire-example-bluebook                                0.712 2992sec 1388MB
 ...validate questionnaire-example-gcs                                     0.511 2993sec 1388MB
 ...validate questionnaire-zika-virus-exposure-assessment                  0.642 2993sec 1388MB
 ...validate questionnaire-profile-example-ussg-fht                        0.533 2994sec 1388MB
 ...validate questionnaire-example-practitioner-info                       0.694 2995sec 1390MB
 ...validate questionnaireresponse-example                                  1.19 2996sec 1388MB
 ...validate questionnaireresponse-example-f201-lifelines                   0.55 2996sec 1388MB
 ...validate questionnaireresponse-example-bluebook                        0.558 2997sec 1388MB
 ...validate questionnaireresponse-example-gcs                              0.64 2997sec 1388MB
 ...validate questionnaireresponse-example-ussg-fht-answers                0.708 2998sec 1388MB
 ...validate regulatedauthorization-example                                1.609 3000sec 1392MB
 ...validate regulatedauthorization-example-basic-drug-auth                0.993 3001sec 1389MB
 ...validate relatedperson-example                                         1.937 3003sec 1389MB
 ...validate relatedperson-example-peter                                   0.535 3003sec 1389MB
 ...validate relatedperson-example-f001-sarah                              0.543 3004sec 1389MB
 ...validate relatedperson-example-f002-ariadne                            0.537 3004sec 1389MB
 ...validate relatedperson-example-newborn-mom                             0.538 3005sec 1389MB
 ...validate requestorchestration-example                                  0.508 3005sec 1389MB
 ...validate requestorchestration-kdn5-example                             1.402 3007sec 1389MB
 ...validate Requirements-example1                                         0.582 3007sec 1389MB
 ...validate Requirements-example2                                         0.493 3008sec 1389MB
 ...validate researchstudy-example                                         0.528 3008sec 1389MB
 ...validate researchsubject-example                                       0.513 3009sec 1389MB
 ...validate riskassessment-example                                        0.529 3009sec 1389MB
 ...validate riskassessment-example-prognosis                              0.741 3010sec 1389MB
 ...validate riskassessment-example-cardiac                                0.564 3011sec 1389MB
 ...validate riskassessment-example-population                             0.654 3011sec 1389MB
 ...validate riskassessment-example-breastcancer                           0.526 3012sec 1389MB
 ...validate riskassessment-riskexample                                    0.523 3012sec 1389MB
 ...validate schedule-example                                              0.544 3013sec 1389MB
 ...validate schedule-provider-location1-example                           0.599 3014sec 1389MB
 ...validate schedule-provider-location2-example                           0.513 3014sec 1389MB
 ...validate searchparameter-example                                       0.552 3015sec 1389MB
 ...validate searchparameter-example-extension                             0.529 3015sec 1389MB
 ...validate searchparameter-example-reference                             0.526 3016sec 1389MB
 ...validate searchparameter-filter                                        0.531 3016sec 1389MB
 ...validate searchparameter-example-constraint                            0.561 3017sec 1389MB
 ...validate servicerequest-example-lipid                                  0.619 3017sec 1389MB
 ...validate servicerequest-example-di                                     0.553 3018sec 1389MB
 ...validate servicerequest-example-ft4                                    0.594 3019sec 1389MB
 ...validate servicerequest-example                                        0.499 3019sec 1389MB
 ...validate servicerequest-example-subrequest                              0.55 3020sec 1389MB
 ...validate servicerequest-example2                                       0.517 3020sec 1389MB
 ...validate servicerequest-example3                                       0.565 3021sec 1389MB
 ...validate servicerequest-example4                                       0.528 3021sec 1389MB
 ...validate servicerequest-example-implant                                0.543 3022sec 1389MB
 ...validate servicerequest-example-ambulation                             0.514 3022sec 1389MB
 ...validate servicerequest-example-colonoscopy-bx                         0.583 3023sec 1389MB
 ...validate servicerequest-example-colonoscopy                            0.626 3023sec 1389MB
 ...validate servicerequest-example-appendectomy                           0.526 3024sec 1389MB
 ...validate servicerequest-example-ob                                     0.537 3025sec 1389MB
 ...validate servicerequest-example-pt                                     0.527 3025sec 1389MB
 ...validate servicerequest-example-edu                                    0.525 3026sec 1389MB
 ...validate servicerequest-example-myringotomy                            0.504 3026sec 1389MB
 ...validate servicerequest-example-ventilation                            0.501 3027sec 1389MB
 ...validate slot-example                                                  0.536 3027sec 1389MB
 ...validate slot-example-busy                                             0.568 3028sec 1389MB
 ...validate slot-example-tentative                                        0.513 3028sec 1389MB
 ...validate slot-example-unavailable                                      0.499 3029sec 1389MB
 ...validate specimen-example                                              0.524 3029sec 1389MB
 ...validate specimen-example-isolate                                      0.677 3030sec 1389MB
 ...validate specimen-example-urine                                        0.878 3031sec 1389MB
 ...validate specimen-example-serum                                        0.522 3031sec 1389MB
 ...validate specimen-example-pooled-serum                                 0.523 3032sec 1389MB
 ...validate specimendefinition-example-serum-plasma                       0.518 3032sec 1389MB
 ...validate structuredefinition-example-section-library                   0.519 3033sec 1389MB
 ...validate structuredefinition-example-composition                       0.701 3034sec 1389MB
 ...validate structuremap-example                                          0.691 3034sec 1389MB
 ...validate structuremap-supplyrequest-transform                          0.575 3035sec 1389MB
 ...validate subscription-admission                                        0.523 3035sec 1389MB
 ...validate subscriptionstatus-example                                    0.508 3036sec 1389MB
 ...validate notification-error                                            0.499 3036sec 1389MB
 ...validate notification-handshake                                        0.524 3037sec 1389MB
 ...validate notification-heartbeat                                        0.554 3037sec 1389MB
 ...validate notification-empty                                            0.502 3038sec 1389MB
 ...validate notification-id-only                                          0.584 3039sec 1389MB
 ...validate notification-id-only-with-patient                             0.527 3039sec 1389MB
 ...validate notification-full-resource                                    0.541 3040sec 1389MB
 ...validate notification-full-resource-with-patient                       0.499 3040sec 1390MB
 ...validate notification-query-status                                     0.532 3041sec 1390MB
 ...validate notification-query-event                                      0.512 3041sec 1389MB
 ...validate notification-message-full-resource                            0.537 3042sec 1390MB
 ...validate subscriptiontopic-example-admission                           0.532 3042sec 1390MB
 ...validate substance-example                                             0.796 3043sec 1390MB
 ...validate substance-example-f201-dust                                   0.573 3044sec 1390MB
 ...validate substance-example-f202-staphylococcus                         0.483 3044sec 1390MB
 ...validate substance-example-f203-potassium                              0.588 3045sec 1390MB
 ...validate substance-example-silver-nitrate-product                       0.57 3045sec 1390MB
 ...validate substance-example-amoxicillin-clavulanate                      0.53 3046sec 1390MB
 ...validate substancedefinition-example                                   0.507 3046sec 1390MB
 ...validate substancenucleicacid-example                                  0.749 3047sec 1390MB
 ...validate substancepolymer-example                                      1.194 3048sec 1390MB
 ...validate substanceprotein-example                                      1.355 3050sec 1390MB
 ...validate substancereferenceinformation-example                         0.681 3050sec 1390MB
 ...validate substancesourcematerial-example                               0.866 3051sec 1390MB
 ...validate supplydelivery-example                                        1.368 3052sec 1390MB
 ...validate supplydelivery-example-pumpdelivery                           0.893 3053sec 1390MB
 ...validate supplydelivery-example-ISBT128                                0.619 3054sec 1390MB
 ...validate supplydelivery-example-mphodelivery                           0.612 3055sec 1390MB
 ...validate supplyrequest-example-simpleorder                             0.608 3055sec 1390MB
 ...validate task-example1                                                  0.61 3056sec 1390MB
 ...validate task-example2                                                 0.541 3056sec 1390MB
 ...validate task-example4                                                 0.541 3057sec 1390MB
 ...validate task-example5                                                 0.514 3057sec 1390MB
 ...validate task-example6                                                 0.545 3058sec 1390MB
 ...validate task-example3                                                 0.646 3059sec 1390MB
 ...validate task-example-fm-cancel                                        0.734 3059sec 1390MB
 ...validate task-example-fm-poll                                          0.561 3060sec 1390MB
 ...validate task-example-fm-release                                       0.555 3060sec 1390MB
 ...validate task-example-fm-reprocess                                     1.103 3062sec 1390MB
 ...validate task-example-fm-status                                        0.524 3062sec 1390MB
 ...validate task-example-fm-status-resp                                   0.597 3063sec 1390MB
 ...validate task-cpg-example-1                                            0.501 3063sec 1390MB
 ...validate terminologycapabilities-example                               0.557 3064sec 1390MB
 ...validate terminologycapabilities-terminology-server                    0.887 3065sec 1390MB
 ...validate testreport-example                                            0.527 3065sec 1390MB
 ...validate testscript-example                                            0.585 3066sec 1390MB
 ...validate testscript-example-history                                    0.539 3066sec 1390MB
 ...validate testscript-example-multisystem                                0.553 3067sec 1390MB
 ...validate testscript-example-readtest                                   0.577 3067sec 1390MB
 ...validate testscript-example-search                                     0.643 3068sec 1390MB
 ...validate testscript-example-update                                     0.543 3069sec 1391MB
 ...validate transport-example                                             0.553 3069sec 1390MB
 ...validate valueset-example                                              0.576 3070sec 1390MB
 ...validate valueset-example-intensional                                   0.85 3071sec 1390MB
 ...validate valueset-example-filter                                       0.654 3071sec 1390MB
 ...validate valueset-example-expansion                                    0.517 3072sec 1390MB
 ...validate valueset-ucum-common                                          0.739 3072sec 1390MB
 ...validate valueset-example-cpt-all                                      1.094 3074sec 1394MB
 ...validate valueset-example-yesnodontknow                                0.529 3074sec 1390MB
 ...validate valueset-nhin-purposeofuse                                    0.562 3075sec 1390MB
 ...validate valueset-example-inactive                                     0.539 3075sec 1390MB
 ...validate valueset-example-metadata                                     0.569 3076sec 1390MB
 ...validate valueset-example-metadata-2                                   0.664 3076sec 1390MB
 ...validate verificationresult-example                                    0.622 3077sec 1390MB
 ...validate visionprescription-example                                    0.518 3078sec 1390MB
 ...validate visionprescription-example-1                                  0.519 3078sec 1390MB
Summary: Errors=0, Warnings=2558, Information messages=575
Other Validation                                                           0.549 3079sec 1391MB

======================================
= Biomedical Research and Regulation =
======================================
Resource AdministrableProductDefinition:
  WARNING: AdministrableProductDefinition.device: Search Parameter 'AdministrableProductDefinition.device' had no found values in any example. Consider reviewing the expression (AdministrableProductDefinition.device)
  WARNING: AdministrableProductDefinition.form-of: Search Parameter 'AdministrableProductDefinition.form-of' had no found values in any example. Consider reviewing the expression (AdministrableProductDefinition.formOf)
  WARNING: AdministrableProductDefinition.ingredient: Search Parameter 'AdministrableProductDefinition.ingredient' had no found values in any example. Consider reviewing the expression (AdministrableProductDefinition.ingredient)
  WARNING: AdministrableProductDefinition.manufactured-item: Search Parameter 'AdministrableProductDefinition.manufactured-item' had no found values in any example. Consider reviewing the expression (AdministrableProductDefinition.producedFrom)
  WARNING: AdministrableProductDefinition.target-species: Search Parameter 'AdministrableProductDefinition.target-species' had no found values in any example. Consider reviewing the expression (AdministrableProductDefinition.routeOfAdministration.targetSpecies.code)

Resource ClinicalUseDefinition:
  WARNING: ClinicalUseDefinition.effect-reference: Search Parameter 'ClinicalUseDefinition.effect-reference' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.undesirableEffect.symptomConditionEffect)
  WARNING: ClinicalUseDefinition.effect: Search Parameter 'ClinicalUseDefinition.effect' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.undesirableEffect.symptomConditionEffect)
  WARNING: ClinicalUseDefinition.identifier: Search Parameter 'ClinicalUseDefinition.identifier' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.identifier)
  WARNING: ClinicalUseDefinition.indication-reference: Search Parameter 'ClinicalUseDefinition.indication-reference' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.indication.diseaseSymptomProcedure)
  WARNING: ClinicalUseDefinition.indication: Search Parameter 'ClinicalUseDefinition.indication' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.indication.diseaseSymptomProcedure)
  WARNING: ClinicalUseDefinition.interaction: Search Parameter 'ClinicalUseDefinition.interaction' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.interaction.type)
  WARNING: ClinicalUseDefinition.product: Search Parameter 'ClinicalUseDefinition.product' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.subject.where(resolve() is MedicinalProductDefinition))
  WARNING: ClinicalUseDefinition.status: Search Parameter 'ClinicalUseDefinition.status' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.status)
  WARNING: ClinicalUseDefinition.subject: Search Parameter 'ClinicalUseDefinition.subject' had no found values in any example. Consider reviewing the expression (ClinicalUseDefinition.subject)

Resource Ingredient:
  INFORMATION: Ingredient.group: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Ingredient.manufacturer.manufacturer (example ingredient-example): Unable to resolve example reference to Organization/example in ingredient-example (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: Ingredient.substance.strength.basis: An element of type CodeableConcept or Coding must have a binding
  WARNING: Ingredient.for: Search Parameter 'Ingredient.for' had no found values in any example. Consider reviewing the expression (Ingredient.for)
  WARNING: Ingredient.function: Search Parameter 'Ingredient.function' had no found values in any example. Consider reviewing the expression (Ingredient.function)
  WARNING: Ingredient.identifier: Search Parameter 'Ingredient.identifier' had no found values in any example. Consider reviewing the expression (Ingredient.identifier)
  WARNING: Ingredient.substance-definition: Search Parameter 'Ingredient.substance-definition' had no found values in any example. Consider reviewing the expression (Ingredient.substance.code.reference)
  WARNING: Ingredient.substance: Search Parameter 'Ingredient.substance' had no found values in any example. Consider reviewing the expression (Ingredient.substance.code.reference)

Resource ManufacturedItemDefinition:
  INFORMATION: ManufacturedItemDefinition.component.constituent.function: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: ManufacturedItemDefinition.component.constituent.location: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: ManufacturedItemDefinition.component.function: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: ManufacturedItemDefinition.component.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: ManufacturedItemDefinition.manufacturer (example manufactureditemdefinition-example): Unable to resolve example reference to Organization/example in manufactureditemdefinition-example (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  WARNING: ManufacturedItemDefinition.identifier: Search Parameter 'ManufacturedItemDefinition.identifier' had no found values in any example. Consider reviewing the expression (ManufacturedItemDefinition.identifier)
  WARNING: ManufacturedItemDefinition.ingredient: Search Parameter 'ManufacturedItemDefinition.ingredient' had no found values in any example. Consider reviewing the expression (ManufacturedItemDefinition.ingredient)
  WARNING: ManufacturedItemDefinition.name: Search Parameter 'ManufacturedItemDefinition.name' had no found values in any example. Consider reviewing the expression (ManufacturedItemDefinition.name)

Resource MedicinalProductDefinition:
  WARNING: MedicinalProductDefinition.characteristic-type: Search Parameter 'MedicinalProductDefinition.characteristic-type' had no found values in any example. Consider reviewing the expression (MedicinalProductDefinition.characteristic.type)
  WARNING: MedicinalProductDefinition.characteristic: Search Parameter 'MedicinalProductDefinition.characteristic' had no found values in any example. Consider reviewing the expression (MedicinalProductDefinition.characteristic.value)
  WARNING: MedicinalProductDefinition.contact: Search Parameter 'MedicinalProductDefinition.contact' had no found values in any example. Consider reviewing the expression (MedicinalProductDefinition.contact.contact)
  WARNING: MedicinalProductDefinition.domain: Search Parameter 'MedicinalProductDefinition.domain' had no found values in any example. Consider reviewing the expression (MedicinalProductDefinition.domain)
  WARNING: MedicinalProductDefinition.status: Search Parameter 'MedicinalProductDefinition.status' had no found values in any example. Consider reviewing the expression (MedicinalProductDefinition.status)
  WARNING: MedicinalProductDefinition.type: Search Parameter 'MedicinalProductDefinition.type' had no found values in any example. Consider reviewing the expression (MedicinalProductDefinition.type)

Resource PackagedProductDefinition:
  INFORMATION: PackagedProductDefinition.packageFor (example packagedproductdefinition-example-co-packaged-liquid-and-syringe): Unable to resolve example reference to MedicinalProductDefinition/ProductThatHasThisPackType in packagedproductdefinition-example-co-packaged-liquid-and-syringe (Possible Ids: example, equilidem-basics, equilidem-with-ing-and-auth, drug-and-device, drug-and-device-complete, Acetamin-500-20-generic, drug-combo-product, drug-combo-product-bundle, product-with-contained-package-and-ingredient, )
  INFORMATION: PackagedProductDefinition.packaging.containedItem.item: Name of child (item) overlaps with name of parent (containedItem)
  INFORMATION: PackagedProductDefinition.packaging.manufacturer (example packagedproductdefinition-example): Unable to resolve example reference to Organization/example in packagedproductdefinition-example (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  WARNING: PackagedProductDefinition.name: Search Parameter 'PackagedProductDefinition.name' had no found values in any example. Consider reviewing the expression (PackagedProductDefinition.name)
  WARNING: PackagedProductDefinition.status: Search Parameter 'PackagedProductDefinition.status' had no found values in any example. Consider reviewing the expression (PackagedProductDefinition.status)

Resource RegulatedAuthorization:
  INFORMATION: RegulatedAuthorization.holder (example regulatedauthorization-example): Unable to resolve example reference to Organization/example in regulatedauthorization-example (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: RegulatedAuthorization.holder (example regulatedauthorization-example-basic-drug-auth): Unable to resolve example reference to Organization/EqlidrugCo in regulatedauthorization-example-basic-drug-auth (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: RegulatedAuthorization.regulator (example regulatedauthorization-example): Unable to resolve example reference to Organization/example in regulatedauthorization-example (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: RegulatedAuthorization.regulator (example regulatedauthorization-example-basic-drug-auth): Unable to resolve example reference to Organization/FDA in regulatedauthorization-example-basic-drug-auth (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: RegulatedAuthorization.subject (example regulatedauthorization-example-basic-drug-auth): Unable to resolve example reference to MedicinalProductDefinition/equilidem in regulatedauthorization-example-basic-drug-auth (Possible Ids: example, equilidem-basics, equilidem-with-ing-and-auth, drug-and-device, drug-and-device-complete, Acetamin-500-20-generic, drug-combo-product, drug-combo-product-bundle, product-with-contained-package-and-ingredient, )

Resource ResearchStudy:
  INFORMATION: ResearchStudy.associatedParty.party: Name of child (party) overlaps with name of parent (associatedParty)
  INFORMATION: ResearchStudy.focus.focusType: Name of child (focusType) overlaps with name of parent (focus)
  INFORMATION: ResearchStudy.studyDesign: Name of child (studyDesign) overlaps with name of parent (ResearchStudy)
  INFORMATION: ResearchStudy: Search Parameter name 'recruitment_actual' does not follow the style guide
  INFORMATION: ResearchStudy: Search Parameter name 'recruitment_target' does not follow the style guide
  WARNING: ResearchStudy.associatedParty.name: Short description doesn't add any new content: 'Name of associated party'
  WARNING: ResearchStudy.condition: Search Parameter 'ResearchStudy.condition' had no found values in any example. Consider reviewing the expression (ResearchStudy.condition)
  WARNING: ResearchStudy.date: Search Parameter 'ResearchStudy.date' had no found values in any example. Consider reviewing the expression (ResearchStudy.period)
  WARNING: ResearchStudy.focus: Search Parameter 'ResearchStudy.focus' had no found values in any example. Consider reviewing the expression (ResearchStudy.focus)
  WARNING: ResearchStudy.identifier: Search Parameter 'ResearchStudy.identifier' had no found values in any example. Consider reviewing the expression (ResearchStudy.identifier)
  WARNING: ResearchStudy.keyword: Search Parameter 'ResearchStudy.keyword' had no found values in any example. Consider reviewing the expression (ResearchStudy.keyword)
  WARNING: ResearchStudy.objective.description: Short description doesn't add any new content: 'Description of the objective'
  WARNING: ResearchStudy.outcomeMeasure.description: Short description doesn't add any new content: 'Description of the outcome'
  WARNING: ResearchStudy.partof: Search Parameter 'ResearchStudy.partof' had no found values in any example. Consider reviewing the expression (ResearchStudy.partOf)
  WARNING: ResearchStudy.protocol: Search Parameter 'ResearchStudy.protocol' had no found values in any example. Consider reviewing the expression (ResearchStudy.protocol)
  WARNING: ResearchStudy.recruitment_actual: Search Parameter 'ResearchStudy.recruitment_actual' had no found values in any example. Consider reviewing the expression (ResearchStudy.recruitment.actualNumber)
  WARNING: ResearchStudy.recruitment_target: Search Parameter 'ResearchStudy.recruitment_target' had no found values in any example. Consider reviewing the expression (ResearchStudy.recruitment.targetNumber)
  WARNING: ResearchStudy.region: Search Parameter 'ResearchStudy.region' had no found values in any example. Consider reviewing the expression (ResearchStudy.region)
  WARNING: ResearchStudy.site: Search Parameter 'ResearchStudy.site' had no found values in any example. Consider reviewing the expression (ResearchStudy.site)
  WARNING: ResearchStudy.title: Search Parameter 'ResearchStudy.title' had no found values in any example. Consider reviewing the expression (ResearchStudy.title)
  WARNING: ResearchStudy: A resource that contains a url element must have a search parameter 'url'
  WARNING: ResearchStudy: Resource elements are out of order. The correct order is '[identifier(=id), status(=status), condition(=what), recruitment(=who.focus), period(=when.done), site(=where), whyStopped(=why)]' but the actual order is '[identifier(=id), status(=status), condition(=what), period(=when.done), site(=where), whyStopped(=why), recruitment(=who.focus)]'

Resource ResearchSubject:
  INFORMATION: ResearchSubject.subject: Name of child (subject) overlaps with name of parent (ResearchSubject)
  INFORMATION: ResearchSubject: Search Parameter name 'subject_state' does not follow the style guide
  WARNING: ResearchSubject.actualArm: Element has a todo associated with it (This ought to have an identifer as well as a name  OR - allocation is to a Group which is part of a planDefinition which represents an Arm.)
  WARNING: ResearchSubject.assignedArm: Element has a todo associated with it (This ought to have an identifer as well as a name  OR - allocation is to a Group which is part of a planDefinition which represents an Arm.)
  WARNING: ResearchSubject.date: Search Parameter 'ResearchSubject.date' had no found values in any example. Consider reviewing the expression (ResearchSubject.period)
  WARNING: ResearchSubject.period: Element has a todo associated with it (.effectiveTime.)

Resource Substance:
  WARNING: Substance.code-reference: Search Parameter 'Substance.code-reference' had no found values in any example. Consider reviewing the expression (Substance.code.reference)

Resource SubstanceDefinition:
  INFORMATION: SubstanceDefinition.classification: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceDefinition.code.code: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceDefinition.moiety.role: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceDefinition: A resource must have w5 mappings
  INFORMATION: SubstanceDefinition: A resource that contains a status element must have a search parameter 'status'

Resource SubstanceNucleicAcid:
  INFORMATION: SubstanceNucleicAcid.oligoNucleotideType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceNucleicAcid.sequenceType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceNucleicAcid.subunit.fivePrime: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceNucleicAcid.subunit.threePrime: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceNucleicAcid: A resource must have w5 mappings
  WARNING: SubstanceNucleicAcid: A resource must have an 'entered in error' status
  WARNING: SubstanceNucleicAcid: All resources should have an identifier

Resource SubstancePolymer:
  INFORMATION: SubstancePolymer.class: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.copolymerConnectivity: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.geometry: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.monomerSet.ratioType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.monomerSet.startingMaterial.category: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.monomerSet.startingMaterial.code: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.repeat.repeatUnit.orientation: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.repeat.repeatUnit.structuralRepresentation.format: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.repeat.repeatUnit.structuralRepresentation.representation: Name of child (representation) overlaps with name of parent (structuralRepresentation)
  INFORMATION: SubstancePolymer.repeat.repeatUnit.structuralRepresentation.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.repeat.repeatUnit.unit: Name of child (unit) overlaps with name of parent (repeatUnit)
  INFORMATION: SubstancePolymer.repeat.repeatUnit: Name of child (repeatUnit) overlaps with name of parent (repeat)
  INFORMATION: SubstancePolymer.repeat.repeatUnitAmountType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstancePolymer.repeat.repeatUnitAmountType: Name of child (repeatUnitAmountType) overlaps with name of parent (repeat)
  INFORMATION: SubstancePolymer: A resource must have w5 mappings
  WARNING: SubstancePolymer: A resource that contains an identifier must have a search parameter 'identifier'

Resource SubstanceProtein:
  INFORMATION: SubstanceProtein.sequenceType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceProtein: A resource must have w5 mappings
  WARNING: SubstanceProtein: A resource must have an 'entered in error' status
  WARNING: SubstanceProtein: All resources should have an identifier

Resource SubstanceReferenceInformation:
  INFORMATION: SubstanceReferenceInformation.gene.gene: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation.gene.geneSequenceOrigin: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation.gene.geneSequenceOrigin: Name of child (geneSequenceOrigin) overlaps with name of parent (gene)
  INFORMATION: SubstanceReferenceInformation.geneElement.element: Name of child (element) overlaps with name of parent (geneElement)
  INFORMATION: SubstanceReferenceInformation.geneElement.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation.target.amountType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation.target.interaction: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation.target.organism: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation.target.organismType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation.target.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceReferenceInformation: A resource must have w5 mappings
  WARNING: SubstanceReferenceInformation.comment: MnM must have confirmed this should not be an Annotation
  WARNING: SubstanceReferenceInformation: A resource must have an 'entered in error' status
  WARNING: SubstanceReferenceInformation: All resources should have an identifier

Resource SubstanceSourceMaterial:
  INFORMATION: SubstanceSourceMaterial.countryOfOrigin: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.developmentStage: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.fractionDescription.materialType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.author.authorDescription: Name of child (authorDescription) overlaps with name of parent (author)
  INFORMATION: SubstanceSourceMaterial.organism.author.authorType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.author.authorType: Name of child (authorType) overlaps with name of parent (author)
  INFORMATION: SubstanceSourceMaterial.organism.family: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.genus: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.hybrid.hybridType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.hybrid.hybridType: Name of child (hybridType) overlaps with name of parent (hybrid)
  INFORMATION: SubstanceSourceMaterial.organism.intraspecificType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.organismGeneral.class: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.organismGeneral.kingdom: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.organismGeneral.order: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.organismGeneral.phylum: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.organism.organismGeneral: Name of child (organismGeneral) overlaps with name of parent (organism)
  INFORMATION: SubstanceSourceMaterial.organism.species: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.partDescription.part: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.partDescription.partLocation: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.sourceMaterialClass: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.sourceMaterialClass: Name of child (sourceMaterialClass) overlaps with name of parent (SubstanceSourceMaterial)
  INFORMATION: SubstanceSourceMaterial.sourceMaterialState: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.sourceMaterialState: Name of child (sourceMaterialState) overlaps with name of parent (SubstanceSourceMaterial)
  INFORMATION: SubstanceSourceMaterial.sourceMaterialType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: SubstanceSourceMaterial.sourceMaterialType: Name of child (sourceMaterialType) overlaps with name of parent (SubstanceSourceMaterial)
  INFORMATION: SubstanceSourceMaterial: A resource must have w5 mappings
  WARNING: SubstanceSourceMaterial: A resource must have an 'entered in error' status
  WARNING: SubstanceSourceMaterial: All resources should have an identifier

  INFORMATION: brr:CodeSystem[administrable-dose-form].define[0]: Code System 'http://hl7.org/fhir/administrable-dose-form' has a code without a definition ('100000073362')
  INFORMATION: brr:CodeSystem[animal-tissue-type].define[0]: Code System 'http://hl7.org/fhir/animal-tissue-type' has a code without a definition ('100000072091')
  INFORMATION: brr:CodeSystem[clinical-use-definition-category].define: Code System brr:CodeSystem[clinical-use-definition-category].define (ClinicalUseDefinitionCategory/http://hl7.org/fhir/clinical-use-definition-category): Defined codes must be lowercase-dash: Pregnancy
  INFORMATION: brr:CodeSystem[clinical-use-definition-category].define[0]: Code System 'http://hl7.org/fhir/clinical-use-definition-category' has a code without a definition ('Pregnancy')
  INFORMATION: brr:CodeSystem[combined-dose-form].define[0]: Code System 'http://hl7.org/fhir/combined-dose-form' has a code without a definition ('100000073366')
  INFORMATION: brr:CodeSystem[ingredient-function].define: Code System brr:CodeSystem[ingredient-function].define (IngredientFunction/http://hl7.org/fhir/ingredient-function): Defined codes must be lowercase-dash: Antioxidant
  INFORMATION: brr:CodeSystem[ingredient-function].define[0]: Code System 'http://hl7.org/fhir/ingredient-function' has a code without a definition ('Antioxidant')
  INFORMATION: brr:CodeSystem[ingredient-manufacturer-role].define[0]: Code System 'http://hl7.org/fhir/ingredient-manufacturer-role' has a code without a definition ('allowed')
  INFORMATION: brr:CodeSystem[ingredient-role].define: Value set brr:CodeSystem[ingredient-role].define (IngredientRole/http://hl7.org/fhir/ingredient-role): Display Names must be TitleCase: bioenhancer
  INFORMATION: brr:CodeSystem[ingredient-role].define[0]: Code System 'http://hl7.org/fhir/ingredient-role' has a code without a definition ('100000072072')
  INFORMATION: brr:CodeSystem[interaction-incidence].define: Code System brr:CodeSystem[interaction-incidence].define (InteractionIncidence/http://hl7.org/fhir/interaction-incidence): Defined codes must be lowercase-dash: Theoretical
  INFORMATION: brr:CodeSystem[interaction-incidence].define[0]: Code System 'http://hl7.org/fhir/interaction-incidence' has a code without a definition ('Theoretical')
  INFORMATION: brr:CodeSystem[interaction-type].define: Value set brr:CodeSystem[interaction-type].define (InteractionType/http://hl7.org/fhir/interaction-type): Display Names must be TitleCase: drug to drug interaction
  INFORMATION: brr:CodeSystem[interaction-type].define[0]: Code System 'http://hl7.org/fhir/interaction-type' has a code without a definition ('drug-drug')
  INFORMATION: brr:CodeSystem[legal-status-of-supply].define[0]: Code System 'http://hl7.org/fhir/legal-status-of-supply' has a code without a definition ('100000072076')
  INFORMATION: brr:CodeSystem[manufactured-dose-form].define[0]: Code System 'http://hl7.org/fhir/manufactured-dose-form' has a code without a definition ('100000073362')
  INFORMATION: brr:CodeSystem[medicinal-product-additional-monitoring].define: Code System brr:CodeSystem[medicinal-product-additional-monitoring].define (AdditionalMonitoring/http://hl7.org/fhir/medicinal-product-additional-monitoring): Defined codes must be lowercase-dash: BlackTriangleMonitoring
  INFORMATION: brr:CodeSystem[medicinal-product-confidentiality].define: Code System brr:CodeSystem[medicinal-product-confidentiality].define (ProductConfidentiality/http://hl7.org/fhir/medicinal-product-confidentiality): Defined codes must be lowercase-dash: CommerciallySensitive
  INFORMATION: brr:CodeSystem[medicinal-product-contact-type].define: Code System brr:CodeSystem[medicinal-product-contact-type].define (ProductContactType/http://hl7.org/fhir/medicinal-product-contact-type): Defined codes must be lowercase-dash: ProposedMAH
  INFORMATION: brr:CodeSystem[medicinal-product-cross-reference-type].define: Code System brr:CodeSystem[medicinal-product-cross-reference-type].define (ProductCrossReferenceType/http://hl7.org/fhir/medicinal-product-cross-reference-type): Defined codes must be lowercase-dash: InvestigationalProduct
  INFORMATION: brr:CodeSystem[medicinal-product-domain].define: Code System brr:CodeSystem[medicinal-product-domain].define (MedicinalProductDomain/http://hl7.org/fhir/medicinal-product-domain): Defined codes must be lowercase-dash: Human
  INFORMATION: brr:CodeSystem[medicinal-product-name-part-type].define: Code System brr:CodeSystem[medicinal-product-name-part-type].define (ProductNamePartType/http://hl7.org/fhir/medicinal-product-name-part-type): Defined codes must be lowercase-dash: FullName
  INFORMATION: brr:CodeSystem[medicinal-product-name-part-type].define[0]: Code System 'http://hl7.org/fhir/medicinal-product-name-part-type' has a code without a definition ('FullName')
  INFORMATION: brr:CodeSystem[medicinal-product-name-type].define: Code System brr:CodeSystem[medicinal-product-name-type].define (ProductNameType/http://hl7.org/fhir/medicinal-product-name-type): Defined codes must be lowercase-dash: BAN
  INFORMATION: brr:CodeSystem[medicinal-product-name-type].define[0]: Code System 'http://hl7.org/fhir/medicinal-product-name-type' has a code without a definition ('BAN')
  INFORMATION: brr:CodeSystem[medicinal-product-package-type].define[0]: Code System 'http://hl7.org/fhir/medicinal-product-package-type' has a code without a definition ('100000073490')
  INFORMATION: brr:CodeSystem[medicinal-product-pediatric-use].define: Code System brr:CodeSystem[medicinal-product-pediatric-use].define (PediatricUse/http://hl7.org/fhir/medicinal-product-pediatric-use): Defined codes must be lowercase-dash: InUtero
  INFORMATION: brr:CodeSystem[medicinal-product-special-measures].define: Code System brr:CodeSystem[medicinal-product-special-measures].define (SpecialMeasures/http://hl7.org/fhir/medicinal-product-special-measures): Defined codes must be lowercase-dash: Post-authorisationStudies
  INFORMATION: brr:CodeSystem[medicinal-product-type].define: Code System brr:CodeSystem[medicinal-product-type].define (MedicinalProductType/http://hl7.org/fhir/medicinal-product-type): Defined codes must be lowercase-dash: MedicinalProduct
  INFORMATION: brr:CodeSystem[package-characteristic].define: Code System brr:CodeSystem[package-characteristic].define (PackageCharacteristic/http://hl7.org/fhir/package-characteristic): Defined codes must be lowercase-dash: HospitalPack
  INFORMATION: brr:CodeSystem[package-characteristic].define[0]: Code System 'http://hl7.org/fhir/package-characteristic' has a code without a definition ('HospitalPack')
  INFORMATION: brr:CodeSystem[package-material].define[0]: Code System 'http://hl7.org/fhir/package-material' has a code without a definition ('200000003200')
  INFORMATION: brr:CodeSystem[package-type].define: Code System brr:CodeSystem[package-type].define (PackageType/http://hl7.org/fhir/package-type): Defined codes must be lowercase-dash: MedicinalProductPack
  INFORMATION: brr:CodeSystem[package-type].define[0]: Code System 'http://hl7.org/fhir/package-type' has a code without a definition ('MedicinalProductPack')
  INFORMATION: brr:CodeSystem[packaging-type].define: Value set brr:CodeSystem[packaging-type].define (PackagingType/http://hl7.org/fhir/packaging-type): Display Names must be TitleCase: disk
  INFORMATION: brr:CodeSystem[packaging-type].define[0]: Code System 'http://hl7.org/fhir/packaging-type' has a code without a definition ('100000073490')
  INFORMATION: brr:CodeSystem[product-intended-use].define: Code System brr:CodeSystem[product-intended-use].define (ProductIntendedUse/http://hl7.org/fhir/product-intended-use): Defined codes must be lowercase-dash: Prevention
  INFORMATION: brr:CodeSystem[product-intended-use].define[0]: Code System 'http://hl7.org/fhir/product-intended-use' has a code without a definition ('Prevention')
  INFORMATION: brr:CodeSystem[regulated-authorization-basis].define: Code System brr:CodeSystem[regulated-authorization-basis].define (RegulatedAuthorizationBasis/http://hl7.org/fhir/regulated-authorization-basis): Defined codes must be lowercase-dash: Full
  INFORMATION: brr:CodeSystem[regulated-authorization-basis].define[0]: Code System 'http://hl7.org/fhir/regulated-authorization-basis' has a code without a definition ('Full')
  INFORMATION: brr:CodeSystem[regulated-authorization-case-type].define: Code System brr:CodeSystem[regulated-authorization-case-type].define (RegulatedAuthorizationCaseType/http://hl7.org/fhir/regulated-authorization-case-type): Defined codes must be lowercase-dash: InitialMAA
  INFORMATION: brr:CodeSystem[regulated-authorization-case-type].define[0]: Code System 'http://hl7.org/fhir/regulated-authorization-case-type' has a code without a definition ('InitialMAA')
  INFORMATION: brr:CodeSystem[regulated-authorization-type].define: Code System brr:CodeSystem[regulated-authorization-type].define (RegulatedAuthorizationType/http://hl7.org/fhir/regulated-authorization-type): Defined codes must be lowercase-dash: MarketingAuth
  INFORMATION: brr:CodeSystem[regulated-authorization-type].define[0]: Code System 'http://hl7.org/fhir/regulated-authorization-type' has a code without a definition ('MarketingAuth')
  INFORMATION: brr:CodeSystem[research-study-classifiers].define: Code System brr:CodeSystem[research-study-classifiers].define (ResearchStudyClassifiers/http://hl7.org/fhir/research-study-classifiers): Defined codes must be lowercase-dash: SEVCO:01000
  INFORMATION: brr:CodeSystem[research-study-classifiers].define: Value set brr:CodeSystem[research-study-classifiers].define (ResearchStudyClassifiers/http://hl7.org/fhir/research-study-classifiers): Display Names must be TitleCase: randomized assignment
  INFORMATION: brr:CodeSystem[research-study-classifiers].define[0]: Code System 'http://hl7.org/fhir/research-study-classifiers' has a code without a definition ('research-study-prim-purp-type')
  INFORMATION: brr:CodeSystem[research-study-party-role].define: Value set brr:CodeSystem[research-study-party-role].define (ResearchStudyPartyRole/http://hl7.org/fhir/research-study-party-role): Display Names must be TitleCase: sponsor
  INFORMATION: brr:CodeSystem[research-subject-milestone].define: Code System brr:CodeSystem[research-subject-milestone].define (ResearchSubjectMilestone/http://terminology.hl7.org/CodeSystem/research-subject-milestone): Defined codes must be lowercase-dash: SignedUp
  INFORMATION: brr:CodeSystem[research-subject-state-type].define: Code System brr:CodeSystem[research-subject-state-type].define (ResearchSubjectStateType/http://terminology.hl7.org/CodeSystem/research-subject-state-type): Defined codes must be lowercase-dash: Milestone
  INFORMATION: brr:CodeSystem[state-change-reason].define: Code System brr:CodeSystem[state-change-reason].define (StateChangeReason/http://terminology.hl7.org/CodeSystem/state-change-reason): Defined codes must be lowercase-dash: adverseEvent
  INFORMATION: brr:CodeSystem[state-change-reason].define: Value set brr:CodeSystem[state-change-reason].define (StateChangeReason/http://terminology.hl7.org/CodeSystem/state-change-reason): Display Names must be TitleCase: adverse event
  INFORMATION: brr:CodeSystem[substance-amount-type].define: Code System brr:CodeSystem[substance-amount-type].define (SubstanceAmountType/http://hl7.org/fhir/substance-amount-type): Defined codes must be lowercase-dash: Average
  INFORMATION: brr:CodeSystem[substance-amount-type].define[0]: Code System 'http://hl7.org/fhir/substance-amount-type' has a code without a definition ('Average')
  INFORMATION: brr:CodeSystem[substance-grade].define: Code System brr:CodeSystem[substance-grade].define (SubstanceGrade/http://hl7.org/fhir/substance-grade): Defined codes must be lowercase-dash: USP-NF
  INFORMATION: brr:CodeSystem[substance-grade].define[0]: Code System 'http://hl7.org/fhir/substance-grade' has a code without a definition ('USP-NF')
  INFORMATION: brr:CodeSystem[substance-name-authority].define: Code System brr:CodeSystem[substance-name-authority].define (SubstanceNameAuthority/http://hl7.org/fhir/substance-name-authority): Defined codes must be lowercase-dash: BAN
  INFORMATION: brr:CodeSystem[substance-name-authority].define[0]: Code System 'http://hl7.org/fhir/substance-name-authority' has a code without a definition ('BAN')
  INFORMATION: brr:CodeSystem[substance-name-domain].define: Code System brr:CodeSystem[substance-name-domain].define (SubstanceNameDomain/http://hl7.org/fhir/substance-name-domain): Defined codes must be lowercase-dash: ActiveIngredient
  INFORMATION: brr:CodeSystem[substance-name-domain].define[0]: Code System 'http://hl7.org/fhir/substance-name-domain' has a code without a definition ('ActiveIngredient')
  INFORMATION: brr:CodeSystem[substance-name-type].define: Code System brr:CodeSystem[substance-name-type].define (SubstanceNameType/http://hl7.org/fhir/substance-name-type): Defined codes must be lowercase-dash: Systematic
  INFORMATION: brr:CodeSystem[substance-name-type].define: Value set brr:CodeSystem[substance-name-type].define (SubstanceNameType/http://hl7.org/fhir/substance-name-type): Display Names must be TitleCase: systematic
  INFORMATION: brr:CodeSystem[substance-name-type].define[0]: Code System 'http://hl7.org/fhir/substance-name-type' has a code without a definition ('Systematic')
  INFORMATION: brr:CodeSystem[substance-optical-activity].define: Code System brr:CodeSystem[substance-optical-activity].define (SubstanceOpticalActivity/http://hl7.org/fhir/substance-optical-activity): Defined codes must be lowercase-dash: +
  INFORMATION: brr:CodeSystem[substance-optical-activity].define: Value set brr:CodeSystem[substance-optical-activity].define (SubstanceOpticalActivity/http://hl7.org/fhir/substance-optical-activity): Display Names must be TitleCase: dextrorotary
  INFORMATION: brr:CodeSystem[substance-optical-activity].define[0]: Code System 'http://hl7.org/fhir/substance-optical-activity' has a code without a definition ('+')
  INFORMATION: brr:CodeSystem[substance-relationship-type].define: Code System brr:CodeSystem[substance-relationship-type].define (SubstanceRelationshipType/http://hl7.org/fhir/substance-relationship-type): Defined codes must be lowercase-dash: Salt
  INFORMATION: brr:CodeSystem[substance-relationship-type].define[0]: Code System 'http://hl7.org/fhir/substance-relationship-type' has a code without a definition ('Salt')
  INFORMATION: brr:CodeSystem[substance-representation-format].define: Code System brr:CodeSystem[substance-representation-format].define (SubstanceRepresentationFormat/http://hl7.org/fhir/substance-representation-format): Defined codes must be lowercase-dash: InChI
  INFORMATION: brr:CodeSystem[substance-representation-format].define: Value set brr:CodeSystem[substance-representation-format].define (SubstanceRepresentationFormat/http://hl7.org/fhir/substance-representation-format): Display Names must be TitleCase: mmCIF
  INFORMATION: brr:CodeSystem[substance-representation-format].define[0]: Code System 'http://hl7.org/fhir/substance-representation-format' has a code without a definition ('InChI')
  INFORMATION: brr:CodeSystem[substance-representation-type].define: Code System brr:CodeSystem[substance-representation-type].define (SubstanceRepresentationType/http://hl7.org/fhir/substance-representation-type): Defined codes must be lowercase-dash: Systematic
  INFORMATION: brr:CodeSystem[substance-representation-type].define: Value set brr:CodeSystem[substance-representation-type].define (SubstanceRepresentationType/http://hl7.org/fhir/substance-representation-type): Display Names must be TitleCase: systematic
  INFORMATION: brr:CodeSystem[substance-representation-type].define[0]: Code System 'http://hl7.org/fhir/substance-representation-type' has a code without a definition ('Systematic')
  INFORMATION: brr:CodeSystem[substance-source-material-genus].define: Code System brr:CodeSystem[substance-source-material-genus].define (SubstanceSourceMaterialGenus/http://hl7.org/fhir/substance-source-material-genus): Defined codes must be lowercase-dash: Mycobacterium
  INFORMATION: brr:CodeSystem[substance-source-material-genus].define[0]: Code System 'http://hl7.org/fhir/substance-source-material-genus' has a code without a definition ('Mycobacterium')
  INFORMATION: brr:CodeSystem[substance-source-material-part].define: Code System brr:CodeSystem[substance-source-material-part].define (SubstanceSourceMaterialPart/http://hl7.org/fhir/substance-source-material-part): Defined codes must be lowercase-dash: Animal
  INFORMATION: brr:CodeSystem[substance-source-material-part].define: Value set brr:CodeSystem[substance-source-material-part].define (SubstanceSourceMaterialPart/http://hl7.org/fhir/substance-source-material-part): Display Names must be TitleCase: animal
  INFORMATION: brr:CodeSystem[substance-source-material-part].define[0]: Code System 'http://hl7.org/fhir/substance-source-material-part' has a code without a definition ('Animal')
  INFORMATION: brr:CodeSystem[substance-source-material-species].define: Code System brr:CodeSystem[substance-source-material-species].define (SubstanceSourceMaterialSpecies/http://hl7.org/fhir/substance-source-material-species): Defined codes must be lowercase-dash: GinkgoBiloba
  INFORMATION: brr:CodeSystem[substance-source-material-species].define[0]: Code System 'http://hl7.org/fhir/substance-source-material-species' has a code without a definition ('GinkgoBiloba')
  INFORMATION: brr:CodeSystem[substance-source-material-type].define: Code System brr:CodeSystem[substance-source-material-type].define (SubstanceSourceMaterialType/http://hl7.org/fhir/substance-source-material-type): Defined codes must be lowercase-dash: Animal
  INFORMATION: brr:CodeSystem[substance-source-material-type].define: Value set brr:CodeSystem[substance-source-material-type].define (SubstanceSourceMaterialType/http://hl7.org/fhir/substance-source-material-type): Display Names must be TitleCase: animal
  INFORMATION: brr:CodeSystem[substance-source-material-type].define[0]: Code System 'http://hl7.org/fhir/substance-source-material-type' has a code without a definition ('Animal')
  INFORMATION: brr:CodeSystem[substance-stereochemistry].define: Code System brr:CodeSystem[substance-stereochemistry].define (SubstanceStereochemistry/http://hl7.org/fhir/substance-stereochemistry): Defined codes must be lowercase-dash: ConstitutionalIsomer
  INFORMATION: brr:CodeSystem[substance-stereochemistry].define: Value set brr:CodeSystem[substance-stereochemistry].define (SubstanceStereochemistry/http://hl7.org/fhir/substance-stereochemistry): Display Names must be TitleCase: constitutional isomer
  INFORMATION: brr:CodeSystem[substance-stereochemistry].define[0]: Code System 'http://hl7.org/fhir/substance-stereochemistry' has a code without a definition ('ConstitutionalIsomer')
  INFORMATION: brr:CodeSystem[substance-structure-technique].define: Code System brr:CodeSystem[substance-structure-technique].define (SubstanceStructureTechnique/http://hl7.org/fhir/substance-structure-technique): Defined codes must be lowercase-dash: X-Ray
  INFORMATION: brr:CodeSystem[substance-structure-technique].define[0]: Code System 'http://hl7.org/fhir/substance-structure-technique' has a code without a definition ('X-Ray')
  INFORMATION: brr:CodeSystem[substance-weight-method].define: Code System brr:CodeSystem[substance-weight-method].define (SubstanceWeightMethod/http://hl7.org/fhir/substance-weight-method): Defined codes must be lowercase-dash: SDS-PAGE
  INFORMATION: brr:CodeSystem[substance-weight-method].define: Value set brr:CodeSystem[substance-weight-method].define (SubstanceWeightMethod/http://hl7.org/fhir/substance-weight-method): Display Names must be TitleCase: calculated
  INFORMATION: brr:CodeSystem[substance-weight-method].define[0]: Code System 'http://hl7.org/fhir/substance-weight-method' has a code without a definition ('SDS-PAGE')
  INFORMATION: brr:CodeSystem[substance-weight-type].define: Code System brr:CodeSystem[substance-weight-type].define (SubstanceWeightType/http://hl7.org/fhir/substance-weight-type): Defined codes must be lowercase-dash: Exact
  INFORMATION: brr:CodeSystem[substance-weight-type].define: Value set brr:CodeSystem[substance-weight-type].define (SubstanceWeightType/http://hl7.org/fhir/substance-weight-type): Display Names must be TitleCase: exact
  INFORMATION: brr:CodeSystem[substance-weight-type].define[0]: Code System 'http://hl7.org/fhir/substance-weight-type' has a code without a definition ('Exact')
  INFORMATION: brr:CodeSystem[target-species].define[0]: Code System 'http://hl7.org/fhir/target-species' has a code without a definition ('100000108874')
  INFORMATION: brr:CodeSystem[undesirable-effect-frequency].define: Code System brr:CodeSystem[undesirable-effect-frequency].define (UndesirablEffectFrequency/http://hl7.org/fhir/undesirable-effect-frequency): Defined codes must be lowercase-dash: Common
  INFORMATION: brr:CodeSystem[undesirable-effect-frequency].define[0]: Code System 'http://hl7.org/fhir/undesirable-effect-frequency' has a code without a definition ('Common')
  INFORMATION: brr:CodeSystem[unit-of-presentation].define[0]: Code System 'http://hl7.org/fhir/unit-of-presentation' has a code without a definition ('200000002108')
  INFORMATION: brr:CodeSystem[warning-type].define: Code System brr:CodeSystem[warning-type].define (WarningType/http://hl7.org/fhir/warning-type): Defined codes must be lowercase-dash: P313
  WARNING: brr:ValueSetComparison: Duplicate Valueset Definitions: valueset-research-study-arm-type.html (ResearchStudyArmType) & valueset-research-study-focus-type.html (ResearchStudyFocusType) (description: [intents, mains, studies] / [intents, mains, studies])
  WARNING: brr:ValueSetComparison: Duplicate Valueset Definitions: valueset-research-study-arm-type.html (ResearchStudyArmType) & valueset-research-study-prim-purp-type.html (ResearchStudyPrimaryPurposeType) (description: [intents, mains, studies] / [intents, mains, studies])
  WARNING: brr:ValueSetComparison: Duplicate Valueset Definitions: valueset-research-study-focus-type.html (ResearchStudyFocusType) & valueset-research-study-prim-purp-type.html (ResearchStudyPrimaryPurposeType) (description: [intents, mains, studies] / [intents, mains, studies])
  WARNING: brr:ValueSetComparison: Duplicate Valueset Definitions: valueset-substance-optical-activity.html (OpticalActivity) & valueset-substance-stereochemistry.html (Stereochemistry) (description: [types, substances, rotations, opticals] / [types, substances, rotations, opticals])
  WARNING: brr:ValueSetComparison: Duplicate Valueset Definitions: valueset-substance-relationship-type.html (SubstanceRelationshipType) & valueset-substance-amount-type.html (SubstanceAmountType) (description: [relationships, twos, types, substances, betweens] / [relationships, twos, types, substances, betweens])
  WARNING: brr:ValueSetComparison: Duplicate Valueset Definitions: valueset-substance-representation-type.html (SubstanceRepresentationType) & valueset-substance-name-type.html (SubstanceNameType) (description: [types, names, substances, givens, tos] / [types, names, substances, givens, tos])
  WARNING: brr:ValueSetComparison: Duplicate Valueset Names: valueset-product-characteristic-codes.html (ProductCharacteristic) & valueset-measurement-property.html (Codes for Product Characteristics) (name: [characteristics, products] / [characteristics, products]))

=============================
= Clinical Decision Support =
=============================
Resource ArtifactAssessment:
  WARNING: ArtifactAssessment: A resource must have an 'entered in error' status
  WARNING: ArtifactAssessment: A resource that contains an identifier must have a search parameter 'identifier'

Resource Citation:
  INFORMATION: Citation.citedArtifact.relatesTo.type: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/related-artifact-type-expanded)
  WARNING: Citation.citedArtifact.contributorship.entry.forenameInitials: Short description doesn't add any new content: 'Initials for forename'
  WARNING: Citation.context-quantity: Search Parameter 'Citation.context-quantity' had no found values in any example. Consider reviewing the expression ((Citation.useContext.value as Quantity) | (Citation.useContext.value as Range))
  WARNING: Citation.context-type-quantity: Search Parameter 'Citation.context-type-quantity' had no found values in any example. Consider reviewing the expression (Citation.useContext)
  WARNING: Citation.context-type-value: Search Parameter 'Citation.context-type-value' had no found values in any example. Consider reviewing the expression (Citation.useContext)
  WARNING: Citation.context-type: Search Parameter 'Citation.context-type' had no found values in any example. Consider reviewing the expression (Citation.useContext.code)
  WARNING: Citation.context: Search Parameter 'Citation.context' had no found values in any example. Consider reviewing the expression ((Citation.useContext.value as CodeableConcept))
  WARNING: Citation.effective: Search Parameter 'Citation.effective' had no found values in any example. Consider reviewing the expression (Citation.effectivePeriod)
  WARNING: Citation.jurisdiction: Search Parameter 'Citation.jurisdiction' had no found values in any example. Consider reviewing the expression (Citation.jurisdiction)
  WARNING: Citation.name: Search Parameter 'Citation.name' had no found values in any example. Consider reviewing the expression (Citation.name)
  WARNING: Citation.url: Search Parameter 'Citation.url' had no found values in any example. Consider reviewing the expression (Citation.url)
  WARNING: Citation.version: Search Parameter 'Citation.version' had no found values in any example. Consider reviewing the expression (Citation.version)

Resource EventDefinition:
  WARNING: EventDefinition.author: Element has a todo associated with it (Does this apply?)
  WARNING: EventDefinition.composed-of: Search Parameter 'EventDefinition.composed-of' had no found values in any example. Consider reviewing the expression (EventDefinition.relatedArtifact.where(type='composed-of').resource)
  WARNING: EventDefinition.context-quantity: Search Parameter 'EventDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((EventDefinition.useContext.value as Quantity) | (EventDefinition.useContext.value as Range))
  WARNING: EventDefinition.context-type-quantity: Search Parameter 'EventDefinition.context-type-quantity' had no found values in any example. Consider reviewing the expression (EventDefinition.useContext)
  WARNING: EventDefinition.context-type-value: Search Parameter 'EventDefinition.context-type-value' had no found values in any example. Consider reviewing the expression (EventDefinition.useContext)
  WARNING: EventDefinition.context-type: Search Parameter 'EventDefinition.context-type' had no found values in any example. Consider reviewing the expression (EventDefinition.useContext.code)
  WARNING: EventDefinition.context: Search Parameter 'EventDefinition.context' had no found values in any example. Consider reviewing the expression ((EventDefinition.useContext.value as CodeableConcept))
  WARNING: EventDefinition.date: Search Parameter 'EventDefinition.date' had no found values in any example. Consider reviewing the expression (EventDefinition.date)
  WARNING: EventDefinition.depends-on: Search Parameter 'EventDefinition.depends-on' had no found values in any example. Consider reviewing the expression (EventDefinition.relatedArtifact.where(type='depends-on').resource)
  WARNING: EventDefinition.derived-from: Search Parameter 'EventDefinition.derived-from' had no found values in any example. Consider reviewing the expression (EventDefinition.relatedArtifact.where(type='derived-from').resource)
  WARNING: EventDefinition.description: Search Parameter 'EventDefinition.description' had no found values in any example. Consider reviewing the expression (EventDefinition.description)
  WARNING: EventDefinition.editor: Element has a todo associated with it (Does this apply?)
  WARNING: EventDefinition.effective: Search Parameter 'EventDefinition.effective' had no found values in any example. Consider reviewing the expression (EventDefinition.effectivePeriod)
  WARNING: EventDefinition.endorser: Element has a todo associated with it (Does this apply?)
  WARNING: EventDefinition.identifier: Search Parameter 'EventDefinition.identifier' had no found values in any example. Consider reviewing the expression (EventDefinition.identifier)
  WARNING: EventDefinition.jurisdiction: Search Parameter 'EventDefinition.jurisdiction' had no found values in any example. Consider reviewing the expression (EventDefinition.jurisdiction)
  WARNING: EventDefinition.name: Search Parameter 'EventDefinition.name' had no found values in any example. Consider reviewing the expression (EventDefinition.name)
  WARNING: EventDefinition.predecessor: Search Parameter 'EventDefinition.predecessor' had no found values in any example. Consider reviewing the expression (EventDefinition.relatedArtifact.where(type='predecessor').resource)
  WARNING: EventDefinition.publisher: Search Parameter 'EventDefinition.publisher' had no found values in any example. Consider reviewing the expression (EventDefinition.publisher)
  WARNING: EventDefinition.relatedArtifact: Element has a todo associated with it (Does this apply?)
  WARNING: EventDefinition.reviewer: Element has a todo associated with it (Does this apply?)
  WARNING: EventDefinition.successor: Search Parameter 'EventDefinition.successor' had no found values in any example. Consider reviewing the expression (EventDefinition.relatedArtifact.where(type='successor').resource)
  WARNING: EventDefinition.title: Search Parameter 'EventDefinition.title' had no found values in any example. Consider reviewing the expression (EventDefinition.title)
  WARNING: EventDefinition.topic: Element has a todo associated with it (Does this apply?)
  WARNING: EventDefinition.topic: Search Parameter 'EventDefinition.topic' had no found values in any example. Consider reviewing the expression (EventDefinition.topic)
  WARNING: EventDefinition.url: Search Parameter 'EventDefinition.url' had no found values in any example. Consider reviewing the expression (EventDefinition.url)
  WARNING: EventDefinition.usage: Element has a todo associated with it (Does this apply?)
  WARNING: EventDefinition.version: Search Parameter 'EventDefinition.version' had no found values in any example. Consider reviewing the expression (EventDefinition.version)

Resource Evidence:
  INFORMATION: Evidence.statistic.category: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Evidence.statistic.modelCharacteristic.variable.valueCategory: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Evidence.statistic.modelCharacteristic.variable.variableDefinition: Name of child (variableDefinition) overlaps with name of parent (variable)
  INFORMATION: Evidence.statistic.statisticType: Name of child (statisticType) overlaps with name of parent (statistic)
  INFORMATION: Evidence.variableDefinition.intended (example evidence-example-ASTRAL-12-alteplase-mRS3-6): Unable to resolve example reference to Group/ASTRAL-12 in evidence-example-ASTRAL-12-alteplase-mRS3-6 (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.intended (example evidence-example-stroke-0-3-alteplase-vs-no-alteplase-mRS3-6): Unable to resolve example reference to Group/AcuteIschemicStroke0-3Hours in evidence-example-stroke-0-3-alteplase-vs-no-alteplase-mRS3-6 (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.intended (example evidence-example-stroke-3-4half-alteplase-vs-no-alteplase-mRS0-2): Unable to resolve example reference to Group/AcuteIschemicStroke3-4halfHours in evidence-example-stroke-3-4half-alteplase-vs-no-alteplase-mRS0-2 (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.intended (example evidence-example-stroke-alteplase-fatalICH): Unable to resolve example reference to Group/AcuteIschemicStroke in evidence-example-stroke-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.intended (example evidence-example-stroke-alteplase-fatalICH): Unable to resolve example reference to Group/AcuteIschemicStrokeTreatedWithAlteplase in evidence-example-stroke-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.intended (example evidence-example-stroke-no-alteplase-fatalICH): Unable to resolve example reference to Group/AcuteIschemicStroke in evidence-example-stroke-no-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.intended (example evidence-example-stroke-no-alteplase-fatalICH): Unable to resolve example reference to Group/AcuteIschemicStrokeTreatedWithoutAlteplase in evidence-example-stroke-no-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.observed (example evidence-example-ASTRAL-12-alteplase-mRS3-6): Unable to resolve example reference to Group/ASTRAL-Cooray-validation-cohort in evidence-example-ASTRAL-12-alteplase-mRS3-6 (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.observed (example evidence-example-stroke-0-3-alteplase-vs-no-alteplase-mRS3-6): Unable to resolve example reference to EvidenceVariable/Wardlaw2014Analysis1.16.3EvidenceSet in evidence-example-stroke-0-3-alteplase-vs-no-alteplase-mRS3-6 (Possible Ids: example-placebo, example-no-alteplase, example-alteplase-for-stroke, example-fatal-ICH-in-7-days, example-alive-independent-90day, example-dead-or-dependent-90day, example-mRS0-2-at-90days, example-mRS3-6-at-90days, example-Wardlaw2014Analysis1.16.3EvidenceSet, example-Stroke-Thrombolysis-Trialists-2014-2016-IPD-MA-Cohort, example-eligibility-criteria-diabetes-surgery, example-eligibility-criteria-ada-rec-bariatric, example-eligibility-criteria-adults-with-obesity, )
  INFORMATION: Evidence.variableDefinition.observed (example evidence-example-stroke-3-4half-alteplase-vs-no-alteplase-mRS0-2): Unable to resolve example reference to EvidenceVariable/Stroke-Thrombolysis-Trialists-2014-2016-IPD-MA-Cohort in evidence-example-stroke-3-4half-alteplase-vs-no-alteplase-mRS0-2 (Possible Ids: example-placebo, example-no-alteplase, example-alteplase-for-stroke, example-fatal-ICH-in-7-days, example-alive-independent-90day, example-dead-or-dependent-90day, example-mRS0-2-at-90days, example-mRS3-6-at-90days, example-Wardlaw2014Analysis1.16.3EvidenceSet, example-Stroke-Thrombolysis-Trialists-2014-2016-IPD-MA-Cohort, example-eligibility-criteria-diabetes-surgery, example-eligibility-criteria-ada-rec-bariatric, example-eligibility-criteria-adults-with-obesity, )
  INFORMATION: Evidence.variableDefinition.observed (example evidence-example-stroke-alteplase-fatalICH): Unable to resolve example reference to Group/AcuteIschemicStroke in evidence-example-stroke-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.observed (example evidence-example-stroke-alteplase-fatalICH): Unable to resolve example reference to Group/Emberson-2014-IPD-MA-Alteplase-Cohort in evidence-example-stroke-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.observed (example evidence-example-stroke-no-alteplase-fatalICH): Unable to resolve example reference to Group/AcuteIschemicStroke in evidence-example-stroke-no-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: Evidence.variableDefinition.observed (example evidence-example-stroke-no-alteplase-fatalICH): Unable to resolve example reference to Group/Emberson-2014-IPD-MA-No-Alteplase-Cohort in evidence-example-stroke-no-alteplase-fatalICH (Possible Ids: 101, 102, herd1, example-patientlist, )
  WARNING: Evidence.context-quantity: Search Parameter 'Evidence.context-quantity' had no found values in any example. Consider reviewing the expression ((Evidence.useContext.value as Quantity) | (Evidence.useContext.value as Range))
  WARNING: Evidence.context-type-quantity: Search Parameter 'Evidence.context-type-quantity' had no found values in any example. Consider reviewing the expression (Evidence.useContext)
  WARNING: Evidence.context-type-value: Search Parameter 'Evidence.context-type-value' had no found values in any example. Consider reviewing the expression (Evidence.useContext)
  WARNING: Evidence.context-type: Search Parameter 'Evidence.context-type' had no found values in any example. Consider reviewing the expression (Evidence.useContext.code)
  WARNING: Evidence.context: Search Parameter 'Evidence.context' had no found values in any example. Consider reviewing the expression ((Evidence.useContext.value as CodeableConcept))
  WARNING: Evidence.date: Search Parameter 'Evidence.date' had no found values in any example. Consider reviewing the expression (Evidence.date)
  WARNING: Evidence.publisher: Search Parameter 'Evidence.publisher' had no found values in any example. Consider reviewing the expression (Evidence.publisher)
  WARNING: Evidence.version: Search Parameter 'Evidence.version' had no found values in any example. Consider reviewing the expression (Evidence.version)

Resource EvidenceReport:
  WARNING: EvidenceReport.context-quantity: Search Parameter 'EvidenceReport.context-quantity' had no found values in any example. Consider reviewing the expression ((EvidenceReport.useContext.value as Quantity) | (EvidenceReport.useContext.value as Range))
  WARNING: EvidenceReport.context-type-quantity: Search Parameter 'EvidenceReport.context-type-quantity' had no found values in any example. Consider reviewing the expression (EvidenceReport.useContext)
  WARNING: EvidenceReport.context-type-value: Search Parameter 'EvidenceReport.context-type-value' had no found values in any example. Consider reviewing the expression (EvidenceReport.useContext)
  WARNING: EvidenceReport.context-type: Search Parameter 'EvidenceReport.context-type' had no found values in any example. Consider reviewing the expression (EvidenceReport.useContext.code)
  WARNING: EvidenceReport.context: Search Parameter 'EvidenceReport.context' had no found values in any example. Consider reviewing the expression ((EvidenceReport.useContext.value as CodeableConcept))
  WARNING: EvidenceReport.identifier: Search Parameter 'EvidenceReport.identifier' had no found values in any example. Consider reviewing the expression (EvidenceReport.identifier)
  WARNING: EvidenceReport.publisher: Search Parameter 'EvidenceReport.publisher' had no found values in any example. Consider reviewing the expression (EvidenceReport.publisher)
  WARNING: EvidenceReport.subject.characteristic.code: Short description doesn't add any new content: 'Characteristic code'
  WARNING: EvidenceReport.subject.characteristic: Short description doesn't add any new content: 'Characteristic'
  WARNING: EvidenceReport.url: Search Parameter 'EvidenceReport.url' had no found values in any example. Consider reviewing the expression (EvidenceReport.url)
  WARNING: EvidenceReport: Resource elements are out of order. The correct order is '[url(=id), identifier(=id), status(=status), publisher(=who.witness)]' but the actual order is '[url(=id), status(=status), identifier(=id), publisher(=who.witness)]'
  WARNING: EvidenceReport: Short description doesn't add any new content: 'A EvidenceReport'

Resource EvidenceVariable:
  INFORMATION: EvidenceVariable.characteristic.definitionCodeableConcept: An element of type CodeableConcept or Coding must have a binding
  WARNING: EvidenceVariable.composed-of: Search Parameter 'EvidenceVariable.composed-of' had no found values in any example. Consider reviewing the expression (EvidenceVariable.relatedArtifact.where(type='composed-of').resource)
  WARNING: EvidenceVariable.context-quantity: Search Parameter 'EvidenceVariable.context-quantity' had no found values in any example. Consider reviewing the expression ((EvidenceVariable.useContext.value as Quantity) | (EvidenceVariable.useContext.value as Range))
  WARNING: EvidenceVariable.context-type-quantity: Search Parameter 'EvidenceVariable.context-type-quantity' had no found values in any example. Consider reviewing the expression (EvidenceVariable.useContext)
  WARNING: EvidenceVariable.context-type-value: Search Parameter 'EvidenceVariable.context-type-value' had no found values in any example. Consider reviewing the expression (EvidenceVariable.useContext)
  WARNING: EvidenceVariable.context-type: Search Parameter 'EvidenceVariable.context-type' had no found values in any example. Consider reviewing the expression (EvidenceVariable.useContext.code)
  WARNING: EvidenceVariable.context: Search Parameter 'EvidenceVariable.context' had no found values in any example. Consider reviewing the expression ((EvidenceVariable.useContext.value as CodeableConcept))
  WARNING: EvidenceVariable.depends-on: Search Parameter 'EvidenceVariable.depends-on' had no found values in any example. Consider reviewing the expression (EvidenceVariable.relatedArtifact.where(type='depends-on').resource)
  WARNING: EvidenceVariable.derived-from: Search Parameter 'EvidenceVariable.derived-from' had no found values in any example. Consider reviewing the expression (EvidenceVariable.relatedArtifact.where(type='derived-from').resource)
  WARNING: EvidenceVariable.predecessor: Search Parameter 'EvidenceVariable.predecessor' had no found values in any example. Consider reviewing the expression (EvidenceVariable.relatedArtifact.where(type='predecessor').resource)
  WARNING: EvidenceVariable.successor: Search Parameter 'EvidenceVariable.successor' had no found values in any example. Consider reviewing the expression (EvidenceVariable.relatedArtifact.where(type='successor').resource)
  WARNING: EvidenceVariable.url: Search Parameter 'EvidenceVariable.url' had no found values in any example. Consider reviewing the expression (EvidenceVariable.url)
  WARNING: EvidenceVariable.version: Search Parameter 'EvidenceVariable.version' had no found values in any example. Consider reviewing the expression (EvidenceVariable.version)

Resource GuidanceResponse:
  INFORMATION: GuidanceResponse.performer (example guidanceresponse-example): Unable to resolve example reference to Device/software in guidanceresponse-example (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )

Resource RequestOrchestration:
  WARNING: RequestOrchestration.code: Search Parameter 'RequestOrchestration.code' had no found values in any example. Consider reviewing the expression (RequestOrchestration.code)
  WARNING: RequestOrchestration.instantiates-uri: Search Parameter 'RequestOrchestration.instantiates-uri' had no found values in any example. Consider reviewing the expression (RequestOrchestration.instantiatesUri)

Resource RiskAssessment:
  INFORMATION: RiskAssessment.basis (example riskassessment-example-breastcancer): Unable to resolve example reference to Observation/example-genetics-brcapat in riskassessment-example-breastcancer (Possible Ids: example, respiratory-rate, heart-rate, body-temperature, body-height, body-length, head-circumference, bmi, bmi-using-related, satO2, blood-pressure, blood-pressure-dar, mbp, vitals-panel, blood-pressure-cancel, f001, unsat, f002, f003, f004, f005, date-lastmp, f202, f203, f204, f205, f206, ekg, glasgow, gcs-qa, 1minute-apgar-score, 2minute-apgar-score, 5minute-apgar-score, 10minute-apgar-score, 20minute-apgar-score, clinical-gender, eye-color, bmd, 656, alcohol-type, vp-oyster, herd1, vomiting, secondsmoke, trachcare, bgpanel, bloodgroup, rhstatus, decimal, map-sitting, abdo-tender, krcore-observation-labresult-example-01, body-weight-with-arabic-code, )
  INFORMATION: RiskAssessment.basis (example riskassessment-example-cardiac): Unable to resolve example reference to DiagnosticReport/lipids in riskassessment-example-cardiac (Possible Ids: 101, 72ac8493-52ac-41bd-8d5d-7258c289b5ea, f001, f201, f202, 102, micro, lri-example, ultrasound, ghp, pap, gingival-mass, gingival-biopsy, )
  INFORMATION: RiskAssessment.basis (example riskassessment-riskexample): Unable to resolve example reference to DiagnosticReport/example in riskassessment-riskexample (Possible Ids: 101, 72ac8493-52ac-41bd-8d5d-7258c289b5ea, f001, f201, f202, 102, micro, lri-example, ultrasound, ghp, pap, gingival-mass, gingival-biopsy, )
  INFORMATION: RiskAssessment.code: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: RiskAssessment.parent (example riskassessment-riskexample): Unable to resolve example reference to DiagnosticReport/example in riskassessment-riskexample (Possible Ids: 101, 72ac8493-52ac-41bd-8d5d-7258c289b5ea, f001, f201, f202, 102, micro, lri-example, ultrasound, ghp, pap, gingival-mass, gingival-biopsy, )
  INFORMATION: RiskAssessment: A resource that contains a status element must have a search parameter 'status'

  INFORMATION: cds:CodeSystem[attribute-estimate-type].define: Code System cds:CodeSystem[attribute-estimate-type].define (AttributeEstimateType/http://terminology.hl7.org/CodeSystem/attribute-estimate-type): Defined codes must be lowercase-dash: C53324
  INFORMATION: cds:CodeSystem[certainty-rating].define: Value set cds:CodeSystem[certainty-rating].define (EvidenceCertaintyRating/http://terminology.hl7.org/CodeSystem/certainty-rating): Display Names must be TitleCase: no serious concern
  INFORMATION: cds:CodeSystem[certainty-type].define: Code System cds:CodeSystem[certainty-type].define (EvidenceCertaintyType/http://terminology.hl7.org/CodeSystem/certainty-type): Defined codes must be lowercase-dash: Overall
  INFORMATION: cds:CodeSystem[characteristic-offset].define: Code System cds:CodeSystem[characteristic-offset].define (CharacteristicOffset/http://terminology.hl7.org/CodeSystem/characteristic-offset): Defined codes must be lowercase-dash: UNL
  INFORMATION: cds:CodeSystem[citation-artifact-classifier].define: Code System cds:CodeSystem[citation-artifact-classifier].define (CitationArtifactClassifier/http://hl7.org/fhir/citation-artifact-classifier): Defined codes must be lowercase-dash: D001877
  INFORMATION: cds:CodeSystem[cited-artifact-part-type].define: Value set cds:CodeSystem[cited-artifact-part-type].define (CitedArtifactPartType/http://terminology.hl7.org/CodeSystem/cited-artifact-part-type): Display Names must be TitleCase: pages
  INFORMATION: cds:CodeSystem[contributor-summary-source].define: Value set cds:CodeSystem[contributor-summary-source].define (ContributorSummarySource/http://terminology.hl7.org/CodeSystem/contributor-summary-source): Display Names must be TitleCase: custom format
  INFORMATION: cds:CodeSystem[evidence-classifier-code].define: Code System cds:CodeSystem[evidence-classifier-code].define (EvidenceClassifier/http://terminology.hl7.org/CodeSystem/evidence-classifier-code): Defined codes must be lowercase-dash: COVID19Specific
  INFORMATION: cds:CodeSystem[evidence-classifier-code].define: Value set cds:CodeSystem[evidence-classifier-code].define (EvidenceClassifier/http://terminology.hl7.org/CodeSystem/evidence-classifier-code): Display Names must be TitleCase: classified as randomized controlled trial
  INFORMATION: cds:CodeSystem[evidence-classifier-code].define[12]: Code System 'http://terminology.hl7.org/CodeSystem/evidence-classifier-code' has a code without a definition ('RatedAsYes')
  INFORMATION: cds:CodeSystem[evidence-report-section].define: Code System cds:CodeSystem[evidence-report-section].define (ReportSectionType/http://terminology.hl7.org/CodeSystem/evidence-report-section): Defined codes must be lowercase-dash: Evidence
  INFORMATION: cds:CodeSystem[evidence-report-section].define[24]: Code System 'http://terminology.hl7.org/CodeSystem/evidence-report-section' has a code without a definition ('Table')
  INFORMATION: cds:CodeSystem[published-in-type].define: Code System cds:CodeSystem[published-in-type].define (PublishedInType/http://terminology.hl7.org/CodeSystem/published-in-type): Defined codes must be lowercase-dash: D020492
  INFORMATION: cds:CodeSystem[report-relation-type].define: Code System cds:CodeSystem[report-relation-type].define (ReportRelationshipType/http://hl7.org/fhir/report-relation-type): Defined codes must be lowercase-dash: replacedWith
  INFORMATION: cds:CodeSystem[statistic-model-code].define: Code System cds:CodeSystem[statistic-model-code].define (StatisticModelCode/http://terminology.hl7.org/CodeSystem/statistic-model-code): Defined codes must be lowercase-dash: oneTailedTest
  INFORMATION: cds:CodeSystem[statistic-model-code].define: Value set cds:CodeSystem[statistic-model-code].define (StatisticModelCode/http://terminology.hl7.org/CodeSystem/statistic-model-code): Display Names must be TitleCase: one-tailed test (1 threshold)
  INFORMATION: cds:CodeSystem[statistic-type].define: Code System cds:CodeSystem[statistic-type].define (StatisticType/http://terminology.hl7.org/CodeSystem/statistic-type): Defined codes must be lowercase-dash: absolute-MedianDiff
  INFORMATION: cds:CodeSystem[synthesis-type].define: Code System cds:CodeSystem[synthesis-type].define (SynthesisType/http://terminology.hl7.org/CodeSystem/synthesis-type): Defined codes must be lowercase-dash: std-MA
  INFORMATION: cds:CodeSystem[synthesis-type].define: Value set cds:CodeSystem[synthesis-type].define (SynthesisType/http://terminology.hl7.org/CodeSystem/synthesis-type): Display Names must be TitleCase: summary data meta-analysis
  INFORMATION: cds:CodeSystem[variable-handling].define: Value set cds:CodeSystem[variable-handling].define (EvidenceVariableHandling/http://hl7.org/fhir/variable-handling): Display Names must be TitleCase: continuous variable
  INFORMATION: cds:CodeSystem[variable-role].define: Code System cds:CodeSystem[variable-role].define (EvidenceVariableRole/http://terminology.hl7.org/CodeSystem/variable-role): Defined codes must be lowercase-dash: referenceExposure
  INFORMATION: cds:CodeSystem[variable-role].define: Value set cds:CodeSystem[variable-role].define (EvidenceVariableRole/http://terminology.hl7.org/CodeSystem/variable-role): Display Names must be TitleCase: population
  WARNING: cds:ValueSetComparison: Duplicate Valueset Definitions: valueset-contributor-role.html (ContributorRole) & valueset-contributor-summary-style.html (ContributorSummaryStyle) (description: [useds, formats, strings, tos, displays] / [useds, formats, strings, tos, displays])

=====================
= Clinical Genomics =
=====================
Resource GenomicStudy:
  INFORMATION: GenomicStudy.analysis.device.device (example genomicstudy-example): Unable to resolve example reference to Device/NGS-device in genomicstudy-example (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )
  INFORMATION: GenomicStudy.analysis.device.device (example genomicstudy-example): Unable to resolve example reference to Device/Triodenovo-SW in genomicstudy-example (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )
  INFORMATION: GenomicStudy.analysis.device.device (example genomicstudy-example-lungMass): Unable to resolve example reference to Device/NGS-device in genomicstudy-example-lungMass (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )
  INFORMATION: GenomicStudy.analysis.device.device (example genomicstudy-example-trio2): Unable to resolve example reference to Device/NGS-device in genomicstudy-example-trio2 (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )
  INFORMATION: GenomicStudy.analysis.device.device (example genomicstudy-example-trio2): Unable to resolve example reference to Device/Triodenovo-SW in genomicstudy-example-trio2 (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )
  INFORMATION: GenomicStudy.analysis.device.function: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: GenomicStudy.analysis.input.file (example genomicstudy-example): Unable to resolve example reference to DocumentReference/genomicFile1 in genomicstudy-example (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.input.file (example genomicstudy-example): Unable to resolve example reference to DocumentReference/genomicFile2 in genomicstudy-example (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.input.file (example genomicstudy-example): Unable to resolve example reference to DocumentReference/genomicFile3 in genomicstudy-example (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.input.file (example genomicstudy-example-trio2): Unable to resolve example reference to DocumentReference/genomicFileFather in genomicstudy-example-trio2 (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.input.file (example genomicstudy-example-trio2): Unable to resolve example reference to DocumentReference/genomicFileMother in genomicstudy-example-trio2 (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.input.file (example genomicstudy-example-trio2): Unable to resolve example reference to DocumentReference/genomicFileProband in genomicstudy-example-trio2 (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.output.file (example genomicstudy-example-lungMass): Unable to resolve example reference to DocumentReference/genomicVCFfile_cnv in genomicstudy-example-lungMass (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.output.file (example genomicstudy-example-lungMass): Unable to resolve example reference to DocumentReference/genomicVCFfile_simple in genomicstudy-example-lungMass (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.output.file (example genomicstudy-example-trio2): Unable to resolve example reference to DocumentReference/genomicFileGroupAsSubject in genomicstudy-example-trio2 (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.performer.actor (example genomicstudy-example): Unable to resolve example reference to Practitioner/practitioner02 in genomicstudy-example (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.analysis.performer.actor (example genomicstudy-example-lungMass): Unable to resolve example reference to Practitioner/practitioner02 in genomicstudy-example-lungMass (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.analysis.performer.actor (example genomicstudy-example-trio2): Unable to resolve example reference to Practitioner/practitioner02 in genomicstudy-example-trio2 (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.analysis.performer.role: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: GenomicStudy.analysis.regionsCalled (example genomicstudy-example-lungMass): Unable to resolve example reference to DocumentReference/CNVAnalysis_called in genomicstudy-example-lungMass (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.regionsCalled (example genomicstudy-example-lungMass): Unable to resolve example reference to DocumentReference/SimpleVariantAnalysis_called in genomicstudy-example-lungMass (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.regionsStudied (example genomicstudy-example-lungMass): Unable to resolve example reference to DocumentReference/WES_FullSequencedRegion_GRCh38 in genomicstudy-example-lungMass (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: GenomicStudy.analysis.specimen (example genomicstudy-example): Unable to resolve example reference to Specimen/denovo-1 in genomicstudy-example (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: GenomicStudy.analysis.specimen (example genomicstudy-example): Unable to resolve example reference to Specimen/denovo-2 in genomicstudy-example (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: GenomicStudy.analysis.specimen (example genomicstudy-example): Unable to resolve example reference to Specimen/denovo-3 in genomicstudy-example (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: GenomicStudy.analysis.specimen (example genomicstudy-example-lungMass): Unable to resolve example reference to Specimen/genomicSpecimen in genomicstudy-example-lungMass (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: GenomicStudy.analysis.specimen (example genomicstudy-example-trio2): Unable to resolve example reference to Specimen/specimenFather in genomicstudy-example-trio2 (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: GenomicStudy.analysis.specimen (example genomicstudy-example-trio2): Unable to resolve example reference to Specimen/specimenMother in genomicstudy-example-trio2 (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: GenomicStudy.analysis.subject (example genomicstudy-example): Unable to resolve example reference to Patient/denovoChild in genomicstudy-example (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: GenomicStudy.analysis.subject (example genomicstudy-example): Unable to resolve example reference to Patient/denovoFather in genomicstudy-example (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: GenomicStudy.analysis.subject (example genomicstudy-example): Unable to resolve example reference to Patient/denovoMother in genomicstudy-example (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: GenomicStudy.analysis.subject (example genomicstudy-example-lungMass): Unable to resolve example reference to Patient/genomicPatient in genomicstudy-example-lungMass (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: GenomicStudy.analysis.subject (example genomicstudy-example-trio2): Unable to resolve example reference to Patient/father in genomicstudy-example-trio2 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: GenomicStudy.analysis.subject (example genomicstudy-example-trio2): Unable to resolve example reference to Patient/mother in genomicstudy-example-trio2 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: GenomicStudy.basedOn (example genomicstudy-example): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in genomicstudy-example (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: GenomicStudy.basedOn (example genomicstudy-example-lungMass): Unable to resolve example reference to ServiceRequest/genomicServiceRequest2 in genomicstudy-example-lungMass (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: GenomicStudy.basedOn (example genomicstudy-example-trio2): Unable to resolve example reference to ServiceRequest/genomicSRFather in genomicstudy-example-trio2 (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: GenomicStudy.basedOn (example genomicstudy-example-trio2): Unable to resolve example reference to ServiceRequest/genomicSRMother in genomicstudy-example-trio2 (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: GenomicStudy.basedOn (example genomicstudy-example-trio2): Unable to resolve example reference to ServiceRequest/genomicSRProband in genomicstudy-example-trio2 (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: GenomicStudy.encounter (example genomicstudy-example): Unable to resolve example reference to Encounter/denovoEncounter in genomicstudy-example (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: GenomicStudy.encounter (example genomicstudy-example-lungMass): Unable to resolve example reference to Encounter/genomicEncounter in genomicstudy-example-lungMass (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: GenomicStudy.encounter (example genomicstudy-example-trio2): Unable to resolve example reference to Encounter/denovoEncounter in genomicstudy-example-trio2 (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: GenomicStudy.interpreter (example genomicstudy-example): Unable to resolve example reference to Practitioner/practitioner02 in genomicstudy-example (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.interpreter (example genomicstudy-example-lungMass): Unable to resolve example reference to Practitioner/practitioner02 in genomicstudy-example-lungMass (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.interpreter (example genomicstudy-example-trio2): Unable to resolve example reference to Practitioner/practitioner02 in genomicstudy-example-trio2 (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.referrer (example genomicstudy-example): Unable to resolve example reference to Practitioner/practitioner01 in genomicstudy-example (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.referrer (example genomicstudy-example-lungMass): Unable to resolve example reference to Practitioner/practitioner01 in genomicstudy-example-lungMass (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.referrer (example genomicstudy-example-trio2): Unable to resolve example reference to Practitioner/practitioner01 in genomicstudy-example-trio2 (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: GenomicStudy.subject (example genomicstudy-example): Unable to resolve example reference to Patient/denovoChild in genomicstudy-example (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: GenomicStudy.subject (example genomicstudy-example-lungMass): Unable to resolve example reference to Patient/genomicPatient in genomicstudy-example-lungMass (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  WARNING: GenomicStudy.description: Short description doesn't add any new content: 'Description of the genomic study'
  WARNING: GenomicStudy.identifier: Short description doesn't add any new content: 'Identifiers for this genomic study'
  WARNING: GenomicStudy.status: Short description doesn't add any new content: 'The status of the genomic study'
  WARNING: GenomicStudy: Short description doesn't add any new content: 'Genomic Study'

Resource MolecularSequence:
  INFORMATION: MolecularSequence.specimen (example sequence-complex-variant): Unable to resolve example reference to Specimen/genetics-example1-somatic in sequence-complex-variant (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: MolecularSequence.subject (example sequence-genetics-example-breastcancer): Unable to resolve example reference to Patient/brcapat in sequence-genetics-example-breastcancer (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )

  INFORMATION: cg:CodeSystem[genomicstudy-changetype].define: Code System cg:CodeSystem[genomicstudy-changetype].define (GenomicStudyChangeType/http://hl7.org/fhir/genomicstudy-changetype): Defined codes must be lowercase-dash: DNA
  INFORMATION: cg:CodeSystem[genomicstudy-dataformat].define: Code System cg:CodeSystem[genomicstudy-dataformat].define (GenomicStudyDataFormat/http://hl7.org/fhir/genomicstudy-dataformat): Defined codes must be lowercase-dash: bigWig
  INFORMATION: cg:CodeSystem[genomicstudy-dataformat].define: Value set cg:CodeSystem[genomicstudy-dataformat].define (GenomicStudyDataFormat/http://hl7.org/fhir/genomicstudy-dataformat): Display Names must be TitleCase: bigBed
  INFORMATION: cg:CodeSystem[genomicstudy-dataformat].define[0]: Code System 'http://hl7.org/fhir/genomicstudy-dataformat' has a code without a definition ('bam')
  INFORMATION: cg:CodeSystem[genomicstudy-methodtype].define[0]: Code System 'http://hl7.org/fhir/genomicstudy-methodtype' has a code without a definition ('biochemical-genetics')

================================
= Clinical Quality Information =
================================
Resource MeasureReport:
  WARNING: MeasureReport.location: Search Parameter 'MeasureReport.location' had no found values in any example. Consider reviewing the expression (MeasureReport.location)

  INFORMATION: cqi:CodeSystem[fhir-types].define: Code System cqi:CodeSystem[fhir-types].define (FHIRTypes/http://hl7.org/fhir/fhir-types): Defined codes must be lowercase-dash: Base
  INFORMATION: cqi:CodeSystem[fhir-types].define: Value set cqi:CodeSystem[fhir-types].define (FHIRTypes/http://hl7.org/fhir/fhir-types): Display Names must be TitleCase: base64Binary
  INFORMATION: cqi:CodeSystem[fhir-types].define: Value set cqi:CodeSystem[fhir-types].define (FHIRTypes/http://hl7.org/fhir/fhir-types): Display Names must be TitleCase: xhtml
  WARNING: cqi:ValueSet[measure-scoring-unit].copyright: Value set valueset-measure-scoring-unit (MeasureScoringUnit): A copyright statement should be present for any value set that includes non-HL7 sourced codes (http://unitsofmeasure.org)

======================================
= Community Based Collaborative Care =
======================================
Resource Consent:
  INFORMATION: Consent.verification.verificationDate: Name of child (verificationDate) overlaps with name of parent (verification)
  INFORMATION: Consent.verification.verificationType: Name of child (verificationType) overlaps with name of parent (verification)
  WARNING: Consent.action: Search Parameter 'Consent.action' had no found values in any example. Consider reviewing the expression (Consent.provision.action)
  WARNING: Consent.actor: Search Parameter 'Consent.actor' had no found values in any example. Consider reviewing the expression (Consent.provision.actor.reference)
  WARNING: Consent.data: Search Parameter 'Consent.data' had no found values in any example. Consider reviewing the expression (Consent.provision.data.reference)
  WARNING: Consent.manager: Search Parameter 'Consent.manager' had no found values in any example. Consider reviewing the expression (Consent.manager)
  WARNING: Consent.purpose: Search Parameter 'Consent.purpose' had no found values in any example. Consider reviewing the expression (Consent.provision.purpose)
  WARNING: Consent.security-label: Search Parameter 'Consent.security-label' had no found values in any example. Consider reviewing the expression (Consent.provision.securityLabel)


=======================
= FHIR Infrastructure =
=======================
Resource ActorDefinition:
  WARNING: ActorDefinition.context-quantity: Search Parameter 'ActorDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((ActorDefinition.useContext.value as Quantity) | (ActorDefinition.useContext.value as Range))
  WARNING: ActorDefinition.context-type-quantity: Search Parameter 'ActorDefinition.context-type-quantity' had no found values in any example. Consider reviewing the expression (ActorDefinition.useContext)
  WARNING: ActorDefinition.context-type-value: Search Parameter 'ActorDefinition.context-type-value' had no found values in any example. Consider reviewing the expression (ActorDefinition.useContext)
  WARNING: ActorDefinition.context-type: Search Parameter 'ActorDefinition.context-type' had no found values in any example. Consider reviewing the expression (ActorDefinition.useContext.code)
  WARNING: ActorDefinition.context: Search Parameter 'ActorDefinition.context' had no found values in any example. Consider reviewing the expression ((ActorDefinition.useContext.value as CodeableConcept))
  WARNING: ActorDefinition.description: Search Parameter 'ActorDefinition.description' had no found values in any example. Consider reviewing the expression (ActorDefinition.description)
  WARNING: ActorDefinition.jurisdiction: Search Parameter 'ActorDefinition.jurisdiction' had no found values in any example. Consider reviewing the expression (ActorDefinition.jurisdiction)
  WARNING: ActorDefinition.publisher: Search Parameter 'ActorDefinition.publisher' had no found values in any example. Consider reviewing the expression (ActorDefinition.publisher)
  WARNING: ActorDefinition.version: Search Parameter 'ActorDefinition.version' had no found values in any example. Consider reviewing the expression (ActorDefinition.version)

Resource CapabilityStatement:
  INFORMATION: CapabilityStatement.rest.resource.operation.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/OperationDefinition/CodeSystem-subsumes in capabilitystatement-terminology-server (Possible Ids: example, ValueSet-expand, ValueSet-validate-code, CodeSystem-lookup, ConceptMap-translate, ConceptMap-closure, Library-data-requirements, Measure-data-requirements, Measure-evaluate-measure, example-query-high-risk, )
  INFORMATION: CapabilityStatement.rest.resource.operation.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/OperationDefinition/CodeSystem-validate-code in capabilitystatement-terminology-server (Possible Ids: example, ValueSet-expand, ValueSet-validate-code, CodeSystem-lookup, ConceptMap-translate, ConceptMap-closure, Library-data-requirements, Measure-data-requirements, Measure-evaluate-measure, example-query-high-risk, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-example): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Patient-general-practitioner in capabilitystatement-example (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-example): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Patient-identifier in capabilitystatement-example (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-composed-of in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-depends-on in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-derived-from in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-description in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-identifier in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-predecessor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-status in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-successor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-title in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-topic in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ActivityDefinition-version in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-composed-of in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-depends-on in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-derived-from in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-description in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-identifier in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-predecessor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-status in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-successor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-title in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-topic in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Library-version in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-composed-of in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-depends-on in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-derived-from in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-description in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-identifier in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-predecessor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-status in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-successor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-title in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-topic in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-version in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-composed-of in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-depends-on in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-derived-from in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-description in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-identifier in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-predecessor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-status in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-successor in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-title in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-topic in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/PlanDefinition-version in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-code in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-context in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-date in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-identifier in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-publisher in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-status in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-title in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-knowledge-repository): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Questionnaire-version in capabilitystatement-knowledge-repository (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-measure-processor): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-identifier in capabilitystatement-measure-processor (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-measure-processor): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-status in capabilitystatement-measure-processor (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-measure-processor): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Measure-version in capabilitystatement-measure-processor (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/CodeSystem-name in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/CodeSystem-status in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/CodeSystem-title in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/CodeSystem-url in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/CodeSystem-version in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ConceptMap-name in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ConceptMap-status in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ConceptMap-title in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ConceptMap-url in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ConceptMap-version in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ValueSet-name in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ValueSet-status in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ValueSet-title in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ValueSet-url in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  INFORMATION: CapabilityStatement.rest.resource.searchParam.definition (example capabilitystatement-terminology-server): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/ValueSet-version in capabilitystatement-terminology-server (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  WARNING: CapabilityStatement.context-quantity: Search Parameter 'CapabilityStatement.context-quantity' had no found values in any example. Consider reviewing the expression ((CapabilityStatement.useContext.value as Quantity) | (CapabilityStatement.useContext.value as Range))
  WARNING: CapabilityStatement.implementationGuide (example capabilitystatement-example): Unable to resolve invalid example reference http://hl7.org/fhir/us/lab in capabilitystatement-example

Resource CompartmentDefinition:
  WARNING: CompartmentDefinition.context-quantity: Search Parameter 'CompartmentDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((CompartmentDefinition.useContext.value as Quantity) | (CompartmentDefinition.useContext.value as Range))

Resource DomainResource:
  INFORMATION: DomainResource: Search Parameter name '_text' does not follow the style guide

Resource ExampleScenario:
  INFORMATION: ExampleScenario.instance.containedInstance.instanceReference: Name of child (instanceReference) overlaps with name of parent (containedInstance)
  WARNING: ExampleScenario.context-quantity: Search Parameter 'ExampleScenario.context-quantity' had no found values in any example. Consider reviewing the expression ((ExampleScenario.useContext.value as Quantity) | (ExampleScenario.useContext.value as Range))
  WARNING: ExampleScenario.context-type-quantity: Search Parameter 'ExampleScenario.context-type-quantity' had no found values in any example. Consider reviewing the expression (ExampleScenario.useContext)
  WARNING: ExampleScenario.context-type-value: Search Parameter 'ExampleScenario.context-type-value' had no found values in any example. Consider reviewing the expression (ExampleScenario.useContext)
  WARNING: ExampleScenario.context-type: Search Parameter 'ExampleScenario.context-type' had no found values in any example. Consider reviewing the expression (ExampleScenario.useContext.code)
  WARNING: ExampleScenario.context: Search Parameter 'ExampleScenario.context' had no found values in any example. Consider reviewing the expression ((ExampleScenario.useContext.value as CodeableConcept))
  WARNING: ExampleScenario.date: Search Parameter 'ExampleScenario.date' had no found values in any example. Consider reviewing the expression (ExampleScenario.date)
  WARNING: ExampleScenario.identifier: Search Parameter 'ExampleScenario.identifier' had no found values in any example. Consider reviewing the expression (ExampleScenario.identifier)
  WARNING: ExampleScenario.jurisdiction: Search Parameter 'ExampleScenario.jurisdiction' had no found values in any example. Consider reviewing the expression (ExampleScenario.jurisdiction)
  WARNING: ExampleScenario.name: Search Parameter 'ExampleScenario.name' had no found values in any example. Consider reviewing the expression (ExampleScenario.name)
  WARNING: ExampleScenario.publisher: Search Parameter 'ExampleScenario.publisher' had no found values in any example. Consider reviewing the expression (ExampleScenario.publisher)
  WARNING: ExampleScenario.url: Search Parameter 'ExampleScenario.url' had no found values in any example. Consider reviewing the expression (ExampleScenario.url)
  WARNING: ExampleScenario.version: Search Parameter 'ExampleScenario.version' had no found values in any example. Consider reviewing the expression (ExampleScenario.version)

Resource GraphDefinition:
  WARNING: GraphDefinition.context-quantity: Search Parameter 'GraphDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((GraphDefinition.useContext.value as Quantity) | (GraphDefinition.useContext.value as Range))
  WARNING: GraphDefinition.context-type-quantity: Search Parameter 'GraphDefinition.context-type-quantity' had no found values in any example. Consider reviewing the expression (GraphDefinition.useContext)
  WARNING: GraphDefinition.context-type-value: Search Parameter 'GraphDefinition.context-type-value' had no found values in any example. Consider reviewing the expression (GraphDefinition.useContext)
  WARNING: GraphDefinition.context-type: Search Parameter 'GraphDefinition.context-type' had no found values in any example. Consider reviewing the expression (GraphDefinition.useContext.code)
  WARNING: GraphDefinition.context: Search Parameter 'GraphDefinition.context' had no found values in any example. Consider reviewing the expression ((GraphDefinition.useContext.value as CodeableConcept))
  WARNING: GraphDefinition.jurisdiction: Search Parameter 'GraphDefinition.jurisdiction' had no found values in any example. Consider reviewing the expression (GraphDefinition.jurisdiction)
  WARNING: GraphDefinition.version: Search Parameter 'GraphDefinition.version' had no found values in any example. Consider reviewing the expression (GraphDefinition.version)

Resource Group:
  INFORMATION: Group.managingEntity (example Group-denovoFamily): Unable to resolve example reference to Practitioner/practitioner02 in Group-denovoFamily (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Group.member.entity (example Group-denovoFamily): Unable to resolve example reference to RelatedPerson/relatedPersonDenovoFather in Group-denovoFamily (Possible Ids: benedicte, peter, f001, f002, newborn-mom, )
  INFORMATION: Group.member.entity (example Group-denovoFamily): Unable to resolve example reference to RelatedPerson/relatedPersonDenovoMother in Group-denovoFamily (Possible Ids: benedicte, peter, f001, f002, newborn-mom, )

Resource ImplementationGuide:
  INFORMATION: ImplementationGuide.definition.resource.profile (example implementationguide-example): Unable to resolve example reference to http://hl7.org/fhir/us/core/StructureDefinition/patient in implementationguide-example (Possible Ids: example-section-library, example-composition, )
  INFORMATION: ImplementationGuide.definition.resource.reference (example implementationguide-example): Unable to resolve example reference to Patient/test in implementationguide-example (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: ImplementationGuide.dependsOn.uri (example implementationguide-example): Unable to resolve example reference to http://hl7.org/fhir/ImplementationGuide/uscore in implementationguide-example (Possible Ids: example, )
  INFORMATION: ImplementationGuide.global.profile (example implementationguide-example): Unable to resolve example reference to http://hl7.org/fhir/us/core/StructureDefinition/patient in implementationguide-example (Possible Ids: example-section-library, example-composition, )
  INFORMATION: ImplementationGuide.manifest.resource.profile (example implementationguide-example): Unable to resolve example reference to http://hl7.org/fhir/us/core/StructureDefinition/patient in implementationguide-example (Possible Ids: example-section-library, example-composition, )
  INFORMATION: ImplementationGuide.manifest.resource.reference (example implementationguide-example): Unable to resolve example reference to Patient/test in implementationguide-example (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  WARNING: ImplementationGuide.context-quantity: Search Parameter 'ImplementationGuide.context-quantity' had no found values in any example. Consider reviewing the expression ((ImplementationGuide.useContext.value as Quantity) | (ImplementationGuide.useContext.value as Range))
  WARNING: ImplementationGuide.context-type-quantity: Search Parameter 'ImplementationGuide.context-type-quantity' had no found values in any example. Consider reviewing the expression (ImplementationGuide.useContext)
  WARNING: ImplementationGuide.context-type-value: Search Parameter 'ImplementationGuide.context-type-value' had no found values in any example. Consider reviewing the expression (ImplementationGuide.useContext)
  WARNING: ImplementationGuide.context-type: Search Parameter 'ImplementationGuide.context-type' had no found values in any example. Consider reviewing the expression (ImplementationGuide.useContext.code)
  WARNING: ImplementationGuide.context: Search Parameter 'ImplementationGuide.context' had no found values in any example. Consider reviewing the expression ((ImplementationGuide.useContext.value as CodeableConcept))
  WARNING: ImplementationGuide.title: Search Parameter 'ImplementationGuide.title' had no found values in any example. Consider reviewing the expression (ImplementationGuide.title)

Resource OperationDefinition:
  INFORMATION: OperationDefinition.base (example operationdefinition-example): Unable to resolve example reference to http://hl7.org/fhir/OperationDefinition/Questionnaire-populate in operationdefinition-example (Possible Ids: example, ValueSet-expand, ValueSet-validate-code, CodeSystem-lookup, ConceptMap-translate, ConceptMap-closure, Library-data-requirements, Measure-data-requirements, Measure-evaluate-measure, example-query-high-risk, )
  WARNING: OperationDefinition.context-quantity: Search Parameter 'OperationDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((OperationDefinition.useContext.value as Quantity) | (OperationDefinition.useContext.value as Range))
  WARNING: OperationDefinition.input-profile: Search Parameter 'OperationDefinition.input-profile' had no found values in any example. Consider reviewing the expression (OperationDefinition.inputProfile)
  WARNING: OperationDefinition.output-profile: Search Parameter 'OperationDefinition.output-profile' had no found values in any example. Consider reviewing the expression (OperationDefinition.outputProfile)

Resource Questionnaire:
  WARNING: Questionnaire.context-quantity: Search Parameter 'Questionnaire.context-quantity' had no found values in any example. Consider reviewing the expression ((Questionnaire.useContext.value as Quantity) | (Questionnaire.useContext.value as Range))
  WARNING: Questionnaire.version: Search Parameter 'Questionnaire.version' had no found values in any example. Consider reviewing the expression (Questionnaire.version)

Resource QuestionnaireResponse:
  WARNING: QuestionnaireResponse.item-subject: Search Parameter 'QuestionnaireResponse.item-subject' had no found values in any example. Consider reviewing the expression (QuestionnaireResponse.item.where(extension('http://hl7.org/fhir/StructureDefinition/questionnaireresponse-isSubject').exists()).answer.value.ofType(Reference))

Resource Requirements:
  WARNING: Requirements.context-quantity: Search Parameter 'Requirements.context-quantity' had no found values in any example. Consider reviewing the expression ((Requirements.useContext.value as Quantity) | (Requirements.useContext.value as Range))
  WARNING: Requirements.context-type-quantity: Search Parameter 'Requirements.context-type-quantity' had no found values in any example. Consider reviewing the expression (Requirements.useContext)
  WARNING: Requirements.context-type-value: Search Parameter 'Requirements.context-type-value' had no found values in any example. Consider reviewing the expression (Requirements.useContext)
  WARNING: Requirements.context-type: Search Parameter 'Requirements.context-type' had no found values in any example. Consider reviewing the expression (Requirements.useContext.code)
  WARNING: Requirements.context: Search Parameter 'Requirements.context' had no found values in any example. Consider reviewing the expression ((Requirements.useContext.value as CodeableConcept))
  WARNING: Requirements.description: Search Parameter 'Requirements.description' had no found values in any example. Consider reviewing the expression (Requirements.description)
  WARNING: Requirements.jurisdiction: Search Parameter 'Requirements.jurisdiction' had no found values in any example. Consider reviewing the expression (Requirements.jurisdiction)
  WARNING: Requirements.publisher: Search Parameter 'Requirements.publisher' had no found values in any example. Consider reviewing the expression (Requirements.publisher)
  WARNING: Requirements.statement: Short description doesn't add any new content: 'Statement of requirements'
  WARNING: Requirements.version: Search Parameter 'Requirements.version' had no found values in any example. Consider reviewing the expression (Requirements.version)

Resource Resource:
  INFORMATION: Resource: Search Parameter name '_content' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_id' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_in' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_language' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_lastUpdated' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_list' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_profile' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_query' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_security' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_source' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_tag' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_text' does not follow the style guide
  INFORMATION: Resource: Search Parameter name '_type' does not follow the style guide
  WARNING: Resource: Search Parameter _in : reference type illegal for Resource.id : id (id)

Resource SearchParameter:
  INFORMATION: SearchParameter.derivedFrom (example searchparameter-example): Unable to resolve example reference to http://hl7.org/fhir/SearchParameter/Resource-id in searchparameter-example (Possible Ids: example, example-extension, example-reference, filter, example-constraint, )
  WARNING: SearchParameter.component: Search Parameter 'SearchParameter.component' had no found values in any example. Consider reviewing the expression (SearchParameter.component.definition)
  WARNING: SearchParameter.context-quantity: Search Parameter 'SearchParameter.context-quantity' had no found values in any example. Consider reviewing the expression ((SearchParameter.useContext.value as Quantity) | (SearchParameter.useContext.value as Range))

Resource StructureDefinition:
  WARNING: StructureDefinition.base-path: Search Parameter 'StructureDefinition.base-path' had no found values in any example. Consider reviewing the expression (StructureDefinition.snapshot.element.base.path | StructureDefinition.differential.element.base.path)
  WARNING: StructureDefinition.context-quantity: Search Parameter 'StructureDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((StructureDefinition.useContext.value as Quantity) | (StructureDefinition.useContext.value as Range))
  WARNING: StructureDefinition.context-type-quantity: Search Parameter 'StructureDefinition.context-type-quantity' had no found values in any example. Consider reviewing the expression (StructureDefinition.useContext)
  WARNING: StructureDefinition.context-type-value: Search Parameter 'StructureDefinition.context-type-value' had no found values in any example. Consider reviewing the expression (StructureDefinition.useContext)
  WARNING: StructureDefinition.context-type: Search Parameter 'StructureDefinition.context-type' had no found values in any example. Consider reviewing the expression (StructureDefinition.useContext.code)
  WARNING: StructureDefinition.context: Search Parameter 'StructureDefinition.context' had no found values in any example. Consider reviewing the expression ((StructureDefinition.useContext.value as CodeableConcept))
  WARNING: StructureDefinition.description: Search Parameter 'StructureDefinition.description' had no found values in any example. Consider reviewing the expression (StructureDefinition.description)
  WARNING: StructureDefinition.ext-context-expression: Search Parameter 'StructureDefinition.ext-context-expression' had no found values in any example. Consider reviewing the expression (StructureDefinition.context.expression)
  WARNING: StructureDefinition.ext-context-type: Search Parameter 'StructureDefinition.ext-context-type' had no found values in any example. Consider reviewing the expression (StructureDefinition.context.type)
  WARNING: StructureDefinition.ext-context: Search Parameter 'StructureDefinition.ext-context' had no found values in any example. Consider reviewing the expression (StructureDefinition.context)
  WARNING: StructureDefinition.jurisdiction: Search Parameter 'StructureDefinition.jurisdiction' had no found values in any example. Consider reviewing the expression (StructureDefinition.jurisdiction)
  WARNING: StructureDefinition.keyword: Search Parameter 'StructureDefinition.keyword' had no found values in any example. Consider reviewing the expression (StructureDefinition.keyword)
  WARNING: StructureDefinition.publisher: Search Parameter 'StructureDefinition.publisher' had no found values in any example. Consider reviewing the expression (StructureDefinition.publisher)
  WARNING: StructureDefinition.valueset: Search Parameter 'StructureDefinition.valueset' had no found values in any example. Consider reviewing the expression (StructureDefinition.snapshot.element.binding.valueSet)
  WARNING: StructureDefinition.version: Search Parameter 'StructureDefinition.version' had no found values in any example. Consider reviewing the expression (StructureDefinition.version)

Resource StructureMap:
  INFORMATION: StructureMap.structure.url (example structuremap-supplyrequest-transform): Unable to resolve example reference to http://hl7.org/fhir/StructureDefinition/activitydefinition in structuremap-supplyrequest-transform (Possible Ids: example-section-library, example-composition, )
  INFORMATION: StructureMap.structure.url (example structuremap-supplyrequest-transform): Unable to resolve example reference to http://hl7.org/fhir/StructureDefinition/supplyrequest in structuremap-supplyrequest-transform (Possible Ids: example-section-library, example-composition, )
  WARNING: StructureMap.context-quantity: Search Parameter 'StructureMap.context-quantity' had no found values in any example. Consider reviewing the expression ((StructureMap.useContext.value as Quantity) | (StructureMap.useContext.value as Range))
  WARNING: StructureMap.context-type-quantity: Search Parameter 'StructureMap.context-type-quantity' had no found values in any example. Consider reviewing the expression (StructureMap.useContext)
  WARNING: StructureMap.context-type-value: Search Parameter 'StructureMap.context-type-value' had no found values in any example. Consider reviewing the expression (StructureMap.useContext)
  WARNING: StructureMap.context-type: Search Parameter 'StructureMap.context-type' had no found values in any example. Consider reviewing the expression (StructureMap.useContext.code)
  WARNING: StructureMap.context: Search Parameter 'StructureMap.context' had no found values in any example. Consider reviewing the expression ((StructureMap.useContext.value as CodeableConcept))

Resource Subscription:
  INFORMATION: Subscription.filterBy.modifier: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/subscription-search-modifier)
  INFORMATION: Subscription.status: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/subscription-status)
  WARNING: Subscription.contact: Search Parameter 'Subscription.contact' had no found values in any example. Consider reviewing the expression (Subscription.contact)
  WARNING: Subscription.identifier: Search Parameter 'Subscription.identifier' had no found values in any example. Consider reviewing the expression (Subscription.identifier)

Resource SubscriptionStatus:
  INFORMATION: SubscriptionStatus.notificationEvent.eventNumber: Name of child (eventNumber) overlaps with name of parent (notificationEvent)
  INFORMATION: SubscriptionStatus.status: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/subscription-status)
  INFORMATION: SubscriptionStatus.status: Name of child (status) overlaps with name of parent (SubscriptionStatus)
  INFORMATION: SubscriptionStatus: A resource that contains a status element must have a search parameter 'status'
  WARNING: SubscriptionStatus.notificationEvent.additionalContext: Short description doesn't add any new content: 'Additional context for this event'
  WARNING: SubscriptionStatus.notificationEvent.eventNumber: Short description doesn't add any new content: 'Event number'
  WARNING: SubscriptionStatus.notificationEvent.focus: Short description doesn't add any new content: 'The focus of this event'
  WARNING: SubscriptionStatus: All resources should have an identifier

Resource SubscriptionTopic:
  INFORMATION: SubscriptionTopic.canFilterBy.modifier: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/subscription-search-modifier)
  WARNING: SubscriptionTopic.date: Search Parameter 'SubscriptionTopic.date' had no found values in any example. Consider reviewing the expression (SubscriptionTopic.date)
  WARNING: SubscriptionTopic.version: Search Parameter 'SubscriptionTopic.version' had no found values in any example. Consider reviewing the expression (SubscriptionTopic.version)

Resource TestReport:
  INFORMATION: TestReport: A resource that contains a status element must have a search parameter 'status'

  INFORMATION: fhir:CodeSystem[assert-direction-codes].define: Value set fhir:CodeSystem[assert-direction-codes].define (AssertionDirectionType/http://hl7.org/fhir/assert-direction-codes): Display Names must be TitleCase: response
  INFORMATION: fhir:CodeSystem[assert-operator-codes].define: Code System fhir:CodeSystem[assert-operator-codes].define (AssertionOperatorType/http://hl7.org/fhir/assert-operator-codes): Defined codes must be lowercase-dash: notEquals
  INFORMATION: fhir:CodeSystem[assert-operator-codes].define: Value set fhir:CodeSystem[assert-operator-codes].define (AssertionOperatorType/http://hl7.org/fhir/assert-operator-codes): Display Names must be TitleCase: equals
  INFORMATION: fhir:CodeSystem[assert-response-code-types].define: Code System fhir:CodeSystem[assert-response-code-types].define (AssertionResponseTypes/http://hl7.org/fhir/assert-response-code-types): Defined codes must be lowercase-dash: noContent
  INFORMATION: fhir:CodeSystem[assert-response-code-types].define: Value set fhir:CodeSystem[assert-response-code-types].define (AssertionResponseTypes/http://hl7.org/fhir/assert-response-code-types): Display Names must be TitleCase: okay
  INFORMATION: fhir:CodeSystem[compartment-type].define: Code System fhir:CodeSystem[compartment-type].define (CompartmentType/http://hl7.org/fhir/compartment-type): Defined codes must be lowercase-dash: Patient
  INFORMATION: fhir:CodeSystem[conformance-expectation].define: Code System fhir:CodeSystem[conformance-expectation].define (ConformanceExpectation/http://hl7.org/fhir/conformance-expectation): Defined codes must be lowercase-dash: SHALL
  INFORMATION: fhir:CodeSystem[event-timing].define: Code System fhir:CodeSystem[event-timing].define (EventTiming/http://hl7.org/fhir/event-timing): Defined codes must be lowercase-dash: MORN
  INFORMATION: fhir:CodeSystem[fhirpath-types].define: Code System fhir:CodeSystem[fhirpath-types].define (FHIRPathTypes/http://hl7.org/fhir/CodeSystem/fhirpath-types): Defined codes must be lowercase-dash: http://hl7.org/fhirpath/System.String
  INFORMATION: fhir:CodeSystem[fhirpath-types].define[0]: Code System 'http://hl7.org/fhir/CodeSystem/fhirpath-types' has a code without a definition ('http://hl7.org/fhirpath/System.String')
  INFORMATION: fhir:CodeSystem[http-verb].define: Code System fhir:CodeSystem[http-verb].define (HTTPVerb/http://hl7.org/fhir/http-verb): Defined codes must be lowercase-dash: GET
  INFORMATION: fhir:CodeSystem[iana-link-relations].define: Code System fhir:CodeSystem[iana-link-relations].define (LinkRelationTypes/http://hl7.org/fhir/CodeSystem/iana-link-relations): Defined codes must be lowercase-dash: convertedFrom
  INFORMATION: fhir:CodeSystem[iana-link-relations].define: Value set fhir:CodeSystem[iana-link-relations].define (LinkRelationTypes/http://hl7.org/fhir/CodeSystem/iana-link-relations): Display Names must be TitleCase: refers to a resource associated with a time interval that ends before the beginning of the time interval associated with the context resource
  INFORMATION: fhir:CodeSystem[inheritance-control-code].define: Code System fhir:CodeSystem[inheritance-control-code].define (InheritanceControlCodes/http://hl7.org/fhir/inheritance-control-code): Defined codes must be lowercase-dash: Additive
  INFORMATION: fhir:CodeSystem[map-source-list-mode].define: Code System fhir:CodeSystem[map-source-list-mode].define (StructureMapSourceListMode/http://hl7.org/fhir/map-source-list-mode): Defined codes must be lowercase-dash: not_first
  INFORMATION: fhir:CodeSystem[map-transform].define: Code System fhir:CodeSystem[map-transform].define (StructureMapTransform/http://hl7.org/fhir/map-transform): Defined codes must be lowercase-dash: dateOp
  INFORMATION: fhir:CodeSystem[map-transform].define: Value set fhir:CodeSystem[map-transform].define (StructureMapTransform/http://hl7.org/fhir/map-transform): Display Names must be TitleCase: create
  INFORMATION: fhir:CodeSystem[property-representation].define: Code System fhir:CodeSystem[property-representation].define (PropertyRepresentation/http://hl7.org/fhir/property-representation): Defined codes must be lowercase-dash: xmlAttr
  INFORMATION: fhir:CodeSystem[quantity-comparator].define: Code System fhir:CodeSystem[quantity-comparator].define (QuantityComparator/http://hl7.org/fhir/quantity-comparator): Defined codes must be lowercase-dash: <
  INFORMATION: fhir:CodeSystem[questionnaire-answer-constraint].define: Code System fhir:CodeSystem[questionnaire-answer-constraint].define (QuestionnaireAnswerConstraint/http://hl7.org/fhir/questionnaire-answer-constraint): Defined codes must be lowercase-dash: optionsOnly
  INFORMATION: fhir:CodeSystem[questionnaire-display-category].define: Value set fhir:CodeSystem[questionnaire-display-category].define (QuestionnaireDisplayCategories/http://hl7.org/fhir/questionnaire-display-category): Display Names must be TitleCase: legal
  INFORMATION: fhir:CodeSystem[questionnaire-enable-operator].define: Code System fhir:CodeSystem[questionnaire-enable-operator].define (QuestionnaireItemOperator/http://hl7.org/fhir/questionnaire-enable-operator): Defined codes must be lowercase-dash: =
  INFORMATION: fhir:CodeSystem[questionnaire-item-control].define: Value set fhir:CodeSystem[questionnaire-item-control].define (QuestionnaireItemUIControlCodes/http://hl7.org/fhir/questionnaire-item-control): Display Names must be TitleCase: legal-Button
  INFORMATION: fhir:CodeSystem[resource-slicing-rules].define: Code System fhir:CodeSystem[resource-slicing-rules].define (SlicingRules/http://hl7.org/fhir/resource-slicing-rules): Defined codes must be lowercase-dash: openAtEnd
  INFORMATION: fhir:CodeSystem[restful-interaction].define: Value set fhir:CodeSystem[restful-interaction].define (FHIR Restful Interactions/http://hl7.org/fhir/restful-interaction): Display Names must be TitleCase: history-instance
  INFORMATION: fhir:CodeSystem[restful-interaction].define: Value set fhir:CodeSystem[restful-interaction].define (FHIR Restful Interactions/http://hl7.org/fhir/restful-interaction): Display Names must be TitleCase: read
  INFORMATION: fhir:CodeSystem[restful-interaction].define: Value set fhir:CodeSystem[restful-interaction].define (FHIR Restful Interactions/http://hl7.org/fhir/restful-interaction): Display Names must be TitleCase: search-type
  INFORMATION: fhir:CodeSystem[restful-security-service].define: Code System fhir:CodeSystem[restful-security-service].define (RestfulSecurityService/http://terminology.hl7.org/CodeSystem/restful-security-service): Defined codes must be lowercase-dash: OAuth
  INFORMATION: fhir:CodeSystem[spdx-license].define: Code System fhir:CodeSystem[spdx-license].define (SPDXLicense/http://hl7.org/fhir/spdx-license): Defined codes must be lowercase-dash: 0BSD
  INFORMATION: fhir:CodeSystem[spdx-license].define: Value set fhir:CodeSystem[spdx-license].define (SPDXLicense/http://hl7.org/fhir/spdx-license): Display Names must be TitleCase: bzip2 and libbzip2 License v1.0.5
  INFORMATION: fhir:CodeSystem[special-values].define: Value set fhir:CodeSystem[special-values].define (SpecialValues/http://terminology.hl7.org/CodeSystem/special-values): Display Names must be TitleCase: true
  INFORMATION: fhir:CodeSystem[subscription-payload-content].define: Value set fhir:CodeSystem[subscription-payload-content].define (SubscriptionPayloadContent/http://hl7.org/fhir/subscription-payload-content): Display Names must be TitleCase: empty
  INFORMATION: fhir:CodeSystem[subscription-search-modifier].define: Code System fhir:CodeSystem[subscription-search-modifier].define (SubscriptionSearchModifer/http://terminology.hl7.org/CodeSystem/subscription-search-modifier): Defined codes must be lowercase-dash: =
  INFORMATION: fhir:CodeSystem[subscriptiontopic-cr-behavior].define: Value set fhir:CodeSystem[subscriptiontopic-cr-behavior].define (CriteriaNotExistsBehavior/http://hl7.org/fhir/subscriptiontopic-cr-behavior): Display Names must be TitleCase: test passes
  INFORMATION: fhir:CodeSystem[testscript-scope-phase-codes].define: Value set fhir:CodeSystem[testscript-scope-phase-codes].define (TestScriptScopePhaseType/http://terminology.hl7.org/CodeSystem/testscript-scope-phase-codes): Display Names must be TitleCase: unit
  INFORMATION: fhir:CodeSystem[timing-abbreviation].define: Code System fhir:CodeSystem[timing-abbreviation].define (TimingAbbreviation/http://terminology.hl7.org/CodeSystem/timing-abbreviation): Defined codes must be lowercase-dash: C
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-conformance-expectation.html (ConformanceExpectation) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-conformance-expectation.html (ConformanceExpectation) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-example-intensional.html (LOINCCodesForCholesterolInSerumPlasma) & valueset-example-expansion.html (LOINCCodesForCholesterolInSerumPlasma) (description: [loincs, v236s, examples, ans, cholesterols, is, froms, serumplasmas, alls] / [loincs, v236s, examples, ans, cholesterols, is, froms, serumplasmas, alls])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-example-metadata.html (ExampleMetadata) & valueset-example-metadata-2.html (ExampleMetadata) (description: [r5s, illustrates, metadata, examples, introduceds, ans, elements, resources, is, usages, ins] / [r5s, illustrates, metadata, examples, introduceds, ans, elements, resources, is, usages, ins])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-example.html (LOINCCodesForCholesterolInSerumPlasma) & valueset-example-expansion.html (LOINCCodesForCholesterolInSerumPlasma) (description: [loincs, v236s, examples, ans, cholesterols, is, froms, serumplasmas, alls] / [loincs, v236s, examples, ans, cholesterols, is, froms, serumplasmas, alls])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-example.html (LOINCCodesForCholesterolInSerumPlasma) & valueset-example-intensional.html (LOINCCodesForCholesterolInSerumPlasma) (description: [loincs, v236s, examples, ans, cholesterols, is, froms, serumplasmas, alls] / [loincs, v236s, examples, ans, cholesterols, is, froms, serumplasmas, alls])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-inheritance-control-code.html (InheritanceControlCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-resource-validation-mode.html (ResourceValidationMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-inheritance-control-code.html (InheritanceControlCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-resource-validation-mode.html (ResourceValidationMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-inheritance-control-code.html (InheritanceControlCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Definitions: valueset-type-characteristics-code.html (TypeCharacteristicCodes) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Names: valueset-dataelement-sdcobjectclassproperty.html (DataElementSDCObjectClass) & valueset-dataelement-sdcobjectclass.html (DataElementSDCObjectClass) (name: [sdcobjects, data, elements, classes] / [sdcobjects, data, elements, classes]))
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Names: valueset-example-intensional.html (LOINCCodesForCholesterolInSerumPlasma) & valueset-example-expansion.html (LOINCCodesForCholesterolInSerumPlasma) (name: [plasmas, cholesterols, serums, loinccodes, ins] / [plasmas, cholesterols, serums, loinccodes, ins]))
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Names: valueset-example-metadata.html (ExampleMetadata) & valueset-example-metadata-2.html (ExampleMetadata) (name: [metadata, examples] / [metadata, examples]))
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Names: valueset-example.html (LOINCCodesForCholesterolInSerumPlasma) & valueset-example-expansion.html (LOINCCodesForCholesterolInSerumPlasma) (name: [plasmas, cholesterols, serums, loinccodes, ins] / [plasmas, cholesterols, serums, loinccodes, ins]))
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Names: valueset-example.html (LOINCCodesForCholesterolInSerumPlasma) & valueset-example-intensional.html (LOINCCodesForCholesterolInSerumPlasma) (name: [plasmas, cholesterols, serums, loinccodes, ins] / [plasmas, cholesterols, serums, loinccodes, ins]))
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Names: valueset-fhir-types.html (FHIRTypes) & valueset-data-types.html (FHIRTypes) (name: [fhirtypes] / [fhirtypes]))
  WARNING: fhir:ValueSetComparison: Duplicate Valueset Names: valueset-resource-types.html (ResourceTypes) & valueset-definition-resource-types.html (DefinitionResourceTypes) (name: [types, resources] / [types, resources]))
  WARNING: fhir:ValueSet[nhin-purposeofuse].copyright: Value set Value set Example valueset-nhin-purposeofuse (NHIN PurposeOfUse): A copyright statement should be present for any value set that includes non-HL7 sourced codes (http://healthit.gov/nhin/purposeofuse)
  WARNING: fhir:ValueSet[timezones].copyright: Value set valueset-timezones (IANATimezones): A copyright statement should be present for any value set that includes non-HL7 sourced codes (https://www.iana.org/time-zones)

========================
= Financial Management =
========================
Resource Claim:
  INFORMATION: Claim.item.bodySite.site: Name of child (site) overlaps with name of parent (bodySite)

Resource ClaimResponse:
  INFORMATION: ClaimResponse.addItem.bodySite.site: Name of child (site) overlaps with name of parent (bodySite)
  INFORMATION: ClaimResponse.addItem.itemSequence: Name of child (itemSequence) overlaps with name of parent (addItem)
  INFORMATION: ClaimResponse.item.detail.detailSequence: Name of child (detailSequence) overlaps with name of parent (detail)
  INFORMATION: ClaimResponse.item.detail.subDetail.subDetailSequence: Name of child (subDetailSequence) overlaps with name of parent (subDetail)
  INFORMATION: ClaimResponse.item.itemSequence: Name of child (itemSequence) overlaps with name of parent (item)

Resource Contract:
  WARNING: Contract.instantiates: Search Parameter 'Contract.instantiates' had no found values in any example. Consider reviewing the expression (Contract.instantiatesUri)
  WARNING: Contract.patient: Search Parameter 'Contract.patient' had no found values in any example. Consider reviewing the expression (Contract.subject.where(resolve() is Patient))
  WARNING: Contract.url: Search Parameter 'Contract.url' had no found values in any example. Consider reviewing the expression (Contract.url)

Resource ExplanationOfBenefit:
  INFORMATION: ExplanationOfBenefit.addItem.bodySite.site: Name of child (site) overlaps with name of parent (bodySite)
  INFORMATION: ExplanationOfBenefit.addItem.itemSequence: Name of child (itemSequence) overlaps with name of parent (addItem)
  INFORMATION: ExplanationOfBenefit.benefitBalance: Name of child (benefitBalance) overlaps with name of parent (ExplanationOfBenefit)
  INFORMATION: ExplanationOfBenefit.benefitPeriod: Name of child (benefitPeriod) overlaps with name of parent (ExplanationOfBenefit)
  INFORMATION: ExplanationOfBenefit.item.bodySite.site: Name of child (site) overlaps with name of parent (bodySite)

Resource Invoice:
  INFORMATION: Invoice.participant.role: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Invoice.type: An element of type CodeableConcept or Coding must have a binding
  WARNING: Invoice.date: Search Parameter 'Invoice.date' had no found values in any example. Consider reviewing the expression (Invoice.date)
  WARNING: Invoice.lineItem: Short description doesn't add any new content: 'Line items of this Invoice'
  WARNING: Invoice.recipient: Search Parameter 'Invoice.recipient' had no found values in any example. Consider reviewing the expression (Invoice.recipient)
  WARNING: Invoice.recipient: Short description doesn't add any new content: 'Recipient of this invoice'
  WARNING: Invoice.totalGross: Short description doesn't add any new content: 'Gross total of this Invoice'
  WARNING: Invoice.totalNet: Short description doesn't add any new content: 'Net total of this Invoice'
  WARNING: Invoice.totalPriceComponent: Short description doesn't add any new content: 'Components of Invoice total'
  WARNING: Invoice.type: Search Parameter 'Invoice.type' had no found values in any example. Consider reviewing the expression (Invoice.type)
  WARNING: Invoice.type: Short description doesn't add any new content: 'Type of Invoice'

Resource PaymentReconciliation:
  WARNING: PaymentReconciliation.allocation-account: Search Parameter 'PaymentReconciliation.allocation-account' had no found values in any example. Consider reviewing the expression (PaymentReconciliation.allocation.account)
  WARNING: PaymentReconciliation.allocation-encounter: Search Parameter 'PaymentReconciliation.allocation-encounter' had no found values in any example. Consider reviewing the expression (PaymentReconciliation.allocation.encounter)

  INFORMATION: fm:CodeSystem[invoice-status].define: Value set fm:CodeSystem[invoice-status].define (InvoiceStatus/http://hl7.org/fhir/invoice-status): Display Names must be TitleCase: draft
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-subtype.html (ContractResourceDefinitionSubtypeCodes) & valueset-contract-expiration-type.html (ContractResourceExpirationTypeCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-subtype.html (ContractResourceDefinitionSubtypeCodes) & valueset-contract-legalstate.html (ContractResourceLegalStateCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-subtype.html (ContractResourceDefinitionSubtypeCodes) & valueset-contract-publicationstatus.html (ContractResourcePublicationStatusCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-subtype.html (ContractResourceDefinitionSubtypeCodes) & valueset-contract-status.html (ContractResourceStatusCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-type.html (ContractResourceDefinitionTypeCodes) & valueset-contract-definition-subtype.html (ContractResourceDefinitionSubtypeCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-type.html (ContractResourceDefinitionTypeCodes) & valueset-contract-expiration-type.html (ContractResourceExpirationTypeCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-type.html (ContractResourceDefinitionTypeCodes) & valueset-contract-legalstate.html (ContractResourceLegalStateCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-type.html (ContractResourceDefinitionTypeCodes) & valueset-contract-publicationstatus.html (ContractResourcePublicationStatusCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-definition-type.html (ContractResourceDefinitionTypeCodes) & valueset-contract-status.html (ContractResourceStatusCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-expiration-type.html (ContractResourceExpirationTypeCodes) & valueset-contract-legalstate.html (ContractResourceLegalStateCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-expiration-type.html (ContractResourceExpirationTypeCodes) & valueset-contract-publicationstatus.html (ContractResourcePublicationStatusCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-expiration-type.html (ContractResourceExpirationTypeCodes) & valueset-contract-status.html (ContractResourceStatusCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-publicationstatus.html (ContractResourcePublicationStatusCodes) & valueset-contract-legalstate.html (ContractResourceLegalStateCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-status.html (ContractResourceStatusCodes) & valueset-contract-legalstate.html (ContractResourceLegalStateCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-contract-status.html (ContractResourceStatusCodes) & valueset-contract-publicationstatus.html (ContractResourcePublicationStatusCodes) (description: [statuses, contracts, specifics] / [statuses, contracts, specifics])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-eligibility-outcome.html (EligibilityOutcome) & valueset-remittance-outcome.html (RemittanceOutcome) (description: [outcomes, processings] / [outcomes, processings])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-eligibilityrequest-purpose.html (EligibilityRequestPurpose) & valueset-eligibilityresponse-purpose.html (EligibilityResponsePurpose) (description: [types, requesteds, information, specifyings, beings] / [types, requesteds, information, specifyings, beings])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-enrollment-outcome.html (EnrollmentOutcome) & valueset-eligibility-outcome.html (EligibilityOutcome) (description: [outcomes, processings] / [outcomes, processings])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-enrollment-outcome.html (EnrollmentOutcome) & valueset-payment-outcome.html (PaymentOutcome) (description: [outcomes, processings] / [outcomes, processings])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-enrollment-outcome.html (EnrollmentOutcome) & valueset-remittance-outcome.html (RemittanceOutcome) (description: [outcomes, processings] / [outcomes, processings])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-payment-outcome.html (PaymentOutcome) & valueset-eligibility-outcome.html (EligibilityOutcome) (description: [outcomes, processings] / [outcomes, processings])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Definitions: valueset-payment-outcome.html (PaymentOutcome) & valueset-remittance-outcome.html (RemittanceOutcome) (description: [outcomes, processings] / [outcomes, processings])
  WARNING: fm:ValueSetComparison: Duplicate Valueset Names: valueset-claim-use.html (Use) & valueset-definition-use.html (DefinitionUseCodes) (name: [uses] / [uses]))
  WARNING: fm:ValueSetComparison: Duplicate Valueset Names: valueset-contract-scope.html (ContractResourceScopeCodes) & valueset-contract-security-classification.html (ContractResourceScopeCodes) (name: [resources, scopes, contracts] / [resources, scopes, contracts]))
  WARNING: fm:ValueSetComparison: Duplicate Valueset Names: valueset-contract-security-category.html (ContractResourceScopeCodes) & valueset-contract-scope.html (ContractResourceScopeCodes) (name: [resources, scopes, contracts] / [resources, scopes, contracts]))
  WARNING: fm:ValueSetComparison: Duplicate Valueset Names: valueset-contract-security-category.html (ContractResourceScopeCodes) & valueset-contract-security-classification.html (ContractResourceScopeCodes) (name: [resources, scopes, contracts] / [resources, scopes, contracts]))

==================
= Grahame Grieve =
==================
Profile cholesterol:
  INFORMATION: cholesterol.profile.html: StructureDefinition http://hl7.org/fhir/StructureDefinition/cholesterol is not an example, however 'experimental is true

Profile hdlcholesterol:
  INFORMATION: hdlcholesterol.profile.html: StructureDefinition http://hl7.org/fhir/StructureDefinition/hdlcholesterol is not an example, however 'experimental is true

Profile ldlcholesterol:
  INFORMATION: ldlcholesterol.profile.html: StructureDefinition http://hl7.org/fhir/StructureDefinition/ldlcholesterol is not an example, however 'experimental is true

Profile lipidprofile:
  INFORMATION: lipidprofile.profile.html: StructureDefinition http://hl7.org/fhir/StructureDefinition/lipidprofile is not an example, however 'experimental is true

Profile triglyceride:
  INFORMATION: triglyceride.profile.html: StructureDefinition http://hl7.org/fhir/StructureDefinition/triglyceride is not an example, however 'experimental is true


=====================
= HL7 FHIR Standard =
=====================
Data Type CodeableReference:
  INFORMATION: CodeableReference.concept: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: CodeableReference.reference: Name of child (reference) overlaps with name of parent (CodeableReference)

Data Type DataRequirement:
  INFORMATION: DataRequirement.codeFilter.code: An element of type CodeableConcept or Coding must have a binding

Data Type ElementDefinition:
  INFORMATION: ElementDefinition.definition: Name of child (definition) overlaps with name of parent (ElementDefinition)
  WARNING: ElementDefinition.comment: MnM must have confirmed this should not be an Annotation
  WARNING: ElementDefinition.mapping.comment: MnM must have confirmed this should not be an Annotation

Data Type Expression:
  INFORMATION: Expression.expression: Name of child (expression) overlaps with name of parent (Expression)

Data Type ExtendedContactDetail:
  WARNING: ExtendedContactDetail.address: Short description doesn't add any new content: 'Address for the contact'

Data Type MarketingStatus:
  INFORMATION: MarketingStatus.country: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MarketingStatus.jurisdiction: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MarketingStatus.status: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MarketingStatus.status: Name of child (status) overlaps with name of parent (MarketingStatus)

Data Type MonetaryComponent:
  INFORMATION: Binding @ MonetaryComponent.code: Need to provide a binding
  WARNING: MonetaryComponent.code: Element needs a definition of its own

Data Type Population:
  INFORMATION: Population.age[x]: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Population.gender: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Population.physiologicalCondition: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Population.race: An element of type CodeableConcept or Coding must have a binding

Data Type ProductShelfLife:
  INFORMATION: ProductShelfLife.specialPrecautionsForStorage: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: ProductShelfLife.type: An element of type CodeableConcept or Coding must have a binding

Data Type Reference:
  INFORMATION: Reference.reference: Name of child (reference) overlaps with name of parent (Reference)

Data Type SampledData:
  INFORMATION: SampledData.data: Name of child (data) overlaps with name of parent (SampledData)

Data Type Timing:
  INFORMATION: Timing.repeat.when: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/event-timing)

Data Type TriggerDefinition:
  INFORMATION: TriggerDefinition.code: An element of type CodeableConcept or Coding must have a binding

Data Type VirtualServiceDetail:
  WARNING: VirtualServiceDetail.channelType: Short description doesn't add any new content: 'Channel Type'

  INFORMATION: null:CodeSystem[etsi-signature-type].define: Code System null:CodeSystem[etsi-signature-type].define (ETSISignatureTypeCodes/http://uri.etsi.org/01903/v1.2.2): Defined codes must be lowercase-dash: ProofOfOrigin
  INFORMATION: null:CodeSystem[extra-activity-type].define: Value set null:CodeSystem[extra-activity-type].define (ExtraActivityType/http://hl7.org/fhir/extra-activity-type): Display Names must be TitleCase: aggregate
  INFORMATION: null:CodeSystem[name-assembly-order].define: Code System null:CodeSystem[name-assembly-order].define (HumanNameAssemblyOrder/http://terminology.hl7.org/CodeSystem/name-assembly-order): Defined codes must be lowercase-dash: NL1
  INFORMATION: null:CodeSystem[name-assembly-order].define[0]: Code System 'http://terminology.hl7.org/CodeSystem/name-assembly-order' has a code without a definition ('NL1')
  INFORMATION: null:CodeSystem[safety-entries].define: Code System null:CodeSystem[safety-entries].define (FHIRSafetyCheckListEntries/http://hl7.org/fhir/safety-entries): Defined codes must be lowercase-dash: check=validation
  INFORMATION: null:CodeSystem[sample-security-structural-roles].define[1].concept[0]: Code System 'http://hl7.org/fhir/sample-security-structural-roles' has a code without a definition ('receptionist')
  INFORMATION: null:CodeSystem[tldc].define: Value set null:CodeSystem[tldc].define (TemplateStatusCodeLifeCycle/urn:oid:2.16.840.1.113883.3.1937.98.5.8): Display Names must be TitleCase: active
  INFORMATION: null:CodeSystem[w3c-provenance-activity-type].define: Code System null:CodeSystem[w3c-provenance-activity-type].define (W3cProvenanceActivityType/http://hl7.org/fhir/w3c-provenance-activity-type): Defined codes must be lowercase-dash: Generation
  INFORMATION: null:CodeSystem[w3c-provenance-activity-type].define: Value set null:CodeSystem[w3c-provenance-activity-type].define (W3cProvenanceActivityType/http://hl7.org/fhir/w3c-provenance-activity-type): Display Names must be TitleCase: wasGeneratedBy
  WARNING: http://hl7.org/fhir/StructureDefinition/DiagnosticReport#DiagnosticReport.result: Cannot check whether the target profile http://hl7.org/fhir/StructureDefinition/cholesterol is valid constraint on the base because it is not known
  WARNING: http://hl7.org/fhir/StructureDefinition/DiagnosticReport#DiagnosticReport.result: Cannot check whether the target profile http://hl7.org/fhir/StructureDefinition/hdlcholesterol is valid constraint on the base because it is not known
  WARNING: http://hl7.org/fhir/StructureDefinition/DiagnosticReport#DiagnosticReport.result: Cannot check whether the target profile http://hl7.org/fhir/StructureDefinition/ldlcholesterol is valid constraint on the base because it is not known
  WARNING: http://hl7.org/fhir/StructureDefinition/DiagnosticReport#DiagnosticReport.result: Cannot check whether the target profile http://hl7.org/fhir/StructureDefinition/triglyceride is valid constraint on the base because it is not known
  WARNING: http://hl7.org/fhir/StructureDefinition/Observation#Observation.derivedFrom: Cannot check whether the target profile http://hl7.org/fhir/StructureDefinition/vitalsigns is valid constraint on the base because it is not known
  WARNING: http://hl7.org/fhir/StructureDefinition/Observation#Observation.hasMember: Cannot check whether the target profile http://hl7.org/fhir/StructureDefinition/vitalsigns is valid constraint on the base because it is not known

=======================
= Health Care Devices =
=======================
Resource DeviceMetric:
  INFORMATION: DeviceMetric.parent (example devicemetric-example): Unable to resolve example reference to Device/dc102 in devicemetric-example (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )
  INFORMATION: DeviceMetric.source (example devicemetric-example): Unable to resolve example reference to Device/dev1 in devicemetric-example (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )


=======================
= Imaging Integration =
=======================
Resource ImagingSelection:
  INFORMATION: ImagingSelection.imageRegion.regionType: Name of child (regionType) overlaps with name of parent (imageRegion)
  INFORMATION: ImagingSelection.instance.imageRegion.regionType: Name of child (regionType) overlaps with name of parent (imageRegion)
  INFORMATION: ImagingSelection: A resource that contains a status element must have a search parameter 'status'
  WARNING: ImagingSelection.based-on: Search Parameter 'ImagingSelection.based-on' had no found values in any example. Consider reviewing the expression (ImagingSelection.basedOn)
  WARNING: ImagingSelection.body-site: Search Parameter 'ImagingSelection.body-site' had no found values in any example. Consider reviewing the expression (ImagingSelection.bodySite.concept)
  WARNING: ImagingSelection.issued: Search Parameter 'ImagingSelection.issued' had no found values in any example. Consider reviewing the expression (ImagingSelection.issued)


================================
= Infrastructure And Messaging =
================================
Resource MessageDefinition:
  INFORMATION: MessageDefinition.focus.profile (example messagedefinition-patient-link-notification): Unable to resolve example reference to http://hl7.org/fhir/StructureDefinition/example in messagedefinition-patient-link-notification (Possible Ids: example-section-library, example-composition, )
  INFORMATION: MessageDefinition.focus.profile (example messagedefinition-patient-link-response): Unable to resolve example reference to http://hl7.org/fhir/StructureDefinition/example in messagedefinition-patient-link-response (Possible Ids: example-section-library, example-composition, )
  WARNING: MessageDefinition.context-quantity: Search Parameter 'MessageDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((MessageDefinition.useContext.value as Quantity) | (MessageDefinition.useContext.value as Range))
  WARNING: MessageDefinition.parent: Search Parameter 'MessageDefinition.parent' had no found values in any example. Consider reviewing the expression (MessageDefinition.parent)


============================
= Modeling and Methodology =
============================
  INFORMATION: mnm:CodeSystem[resource-status].define: Value set mnm:CodeSystem[resource-status].define (Canonical Status Codes for FHIR Resources/http://hl7.org/fhir/resource-status): Display Names must be TitleCase: error

===========================
= Orders and Observations =
===========================
Resource BiologicallyDerivedProduct:
  INFORMATION: BiologicallyDerivedProduct.collection.source (example biologicallyderivedproduct-example-allogeneicHCT): Unable to resolve example reference to Patient/example-b in biologicallyderivedproduct-example-allogeneicHCT (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: BiologicallyDerivedProduct.collection.source (example biologicallyderivedproduct-example-autologousHCT): Unable to resolve example reference to Patient/example-a in biologicallyderivedproduct-example-autologousHCT (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: BiologicallyDerivedProduct.processingFacility (example biologicallyderivedproduct-example): Unable to resolve example reference to Organization/A9999 in biologicallyderivedproduct-example (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: BiologicallyDerivedProduct.processingFacility (example biologicallyderivedproduct-example-autologousHCT): Unable to resolve example reference to Organization/Example in biologicallyderivedproduct-example-autologousHCT (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: BiologicallyDerivedProduct.processingFacility (example supplydelivery-example-ISBT128): Unable to resolve example reference to Organization/A9999 in supplydelivery-example-ISBT128 (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: BiologicallyDerivedProduct.processingFacility (example supplydelivery-example-mphodelivery): Unable to resolve example reference to Organization/A9999 in supplydelivery-example-mphodelivery (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: BiologicallyDerivedProduct.productCategory: Name of child (productCategory) overlaps with name of parent (BiologicallyDerivedProduct)
  INFORMATION: BiologicallyDerivedProduct.productCode: Name of child (productCode) overlaps with name of parent (BiologicallyDerivedProduct)
  INFORMATION: BiologicallyDerivedProduct.productStatus: Name of child (productStatus) overlaps with name of parent (BiologicallyDerivedProduct)
  INFORMATION: BiologicallyDerivedProduct.request (example biologicallyderivedproduct-example-allogeneicHCT): Unable to resolve example reference to BiologicallyDerivedProduct/HCTcollection-servicerequest in biologicallyderivedproduct-example-allogeneicHCT (Possible Ids: example, allogeneicHCT, autologousHCT, )
  INFORMATION: BiologicallyDerivedProduct.request (example biologicallyderivedproduct-example-autologousHCT): Unable to resolve example reference to BiologicallyDerivedProduct/HCTcollection-servicerequest in biologicallyderivedproduct-example-autologousHCT (Possible Ids: example, allogeneicHCT, autologousHCT, )
  WARNING: BiologicallyDerivedProduct.collector: Search Parameter 'BiologicallyDerivedProduct.collector' had no found values in any example. Consider reviewing the expression (BiologicallyDerivedProduct.collection.collector)

Resource BodyStructure:
  INFORMATION: BodyStructure.excludedStructure.structure: Name of child (structure) overlaps with name of parent (excludedStructure)
  INFORMATION: BodyStructure.includedStructure.structure: Name of child (structure) overlaps with name of parent (includedStructure)
  WARNING: BodyStructure.structure: Search Parameter 'BodyStructure.structure' had no found values in any example. Consider reviewing the expression (BodyStructure.excludedStructure.structure)

Resource Device:
  INFORMATION: Device.association.statusReason: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Device.deviceName.name: Name of child (name) overlaps with name of parent (deviceName)
  INFORMATION: Device.deviceName: Name of child (deviceName) overlaps with name of parent (Device)
  INFORMATION: Device.udiCarrier.carrierAIDC: Name of child (carrierAIDC) overlaps with name of parent (udiCarrier)
  INFORMATION: Device.udiCarrier.carrierHRF: Name of child (carrierHRF) overlaps with name of parent (udiCarrier)
  WARNING: Device.biological-source-event: Search Parameter 'Device.biological-source-event' had no found values in any example. Consider reviewing the expression (Device.biologicalSourceEvent)
  WARNING: Device.definition: Search Parameter 'Device.definition' had no found values in any example. Consider reviewing the expression (Device.definition.reference)
  WARNING: Device.location: Search Parameter 'Device.location' had no found values in any example. Consider reviewing the expression (Device.location)
  WARNING: Device.organization: Search Parameter 'Device.organization' had no found values in any example. Consider reviewing the expression (Device.owner)
  WARNING: Device.parent: Search Parameter 'Device.parent' had no found values in any example. Consider reviewing the expression (Device.parent)
  WARNING: Device.patient: Search Parameter 'Device.patient' had no found values in any example. Consider reviewing the expression (Device.association.humanSubject.where(resolve() is Patient))

Resource DeviceDefinition:
  INFORMATION: DeviceDefinition.chargeItem.chargeItemCode: Name of child (chargeItemCode) overlaps with name of parent (chargeItem)
  INFORMATION: DeviceDefinition.deviceName.name: Name of child (name) overlaps with name of parent (deviceName)
  INFORMATION: DeviceDefinition.languageCode: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceDefinition.material.substance: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceDefinition.packaging.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceDefinition.productionIdentifierInUDI: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/device-productidentifierinudi)
  INFORMATION: DeviceDefinition.property.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceDefinition.udiDeviceIdentifier.deviceIdentifier: Name of child (deviceIdentifier) overlaps with name of parent (udiDeviceIdentifier)
  INFORMATION: DeviceDefinition.version.type: An element of type CodeableConcept or Coding must have a binding
  WARNING: DeviceDefinition.parent: Search Parameter 'DeviceDefinition.parent' had no found values in any example. Consider reviewing the expression (DeviceDefinition.parentDevice)
  WARNING: DeviceDefinition.type: Search Parameter 'DeviceDefinition.type' had no found values in any example. Consider reviewing the expression (DeviceDefinition.classification.type)

Resource DeviceDispense:
  INFORMATION: DeviceDispense.category: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceDispense.performer.function: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceDispense.status: Bindings for code datatypes should only use internally defined codes (http://hl7.org/fhir/ValueSet/devicedispense-status)
  INFORMATION: DeviceDispense.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceDispense: A resource that contains a status element must have a search parameter 'status'
  WARNING: DeviceDispense.subject: Elements with name 'subject' cannot be a reference to just a patient
  WARNING: DeviceDispense: A resource that contains a subject that can be a patient reference must have a search parameter 'patient'
  WARNING: DeviceDispense: A resource that contains an identifier must have a search parameter 'identifier'
  WARNING: DeviceDispense: Short description doesn't add any new content: 'Device Dispense'

Resource DeviceRequest:
  INFORMATION: DeviceRequest.asNeededFor: An element of type CodeableConcept or Coding must have a binding
  WARNING: DeviceRequest.instantiates-uri: Search Parameter 'DeviceRequest.instantiates-uri' had no found values in any example. Consider reviewing the expression (DeviceRequest.instantiatesUri)
  WARNING: DeviceRequest.insurance: Search Parameter 'DeviceRequest.insurance' had no found values in any example. Consider reviewing the expression (DeviceRequest.insurance)

Resource DeviceUsage:
  INFORMATION: DeviceUsage.category: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceUsage.usageReason: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: DeviceUsage.usageReason: Name of child (usageReason) overlaps with name of parent (DeviceUsage)
  INFORMATION: DeviceUsage.usageStatus: Name of child (usageStatus) overlaps with name of parent (DeviceUsage)
  INFORMATION: DeviceUsage: A resource that contains a status element must have a search parameter 'status'

Resource DocumentReference:
  INFORMATION: DocumentReference.context (example documentreference-example-xray): Unable to resolve example reference to DocumentReference/documentreference-example-xray-encounter in documentreference-example-xray (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: DocumentReference.relatesTo.target (example documentreference-example-composition): Unable to resolve example reference to DocumentReference/old-example in documentreference-example-composition (Possible Ids: xds, example, example-diagram, 1.2.840.11361907579238403408700.3.1.04.19970327150033, sound, xray, example-comprehensive, example-composition, example-bundle, )
  INFORMATION: DocumentReference.subject (example DocumentReference-genomicFile1): Unable to resolve example reference to Patient/denovoChild in DocumentReference-genomicFile1 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: DocumentReference.subject (example DocumentReference-genomicFile2): Unable to resolve example reference to Patient/denovoMother in DocumentReference-genomicFile2 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: DocumentReference.subject (example DocumentReference-genomicFile3): Unable to resolve example reference to Patient/denovoFather in DocumentReference-genomicFile3 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: DocumentReference.subject (example DocumentReference-genomicFile4): Unable to resolve example reference to Patient/denovoChild in DocumentReference-genomicFile4 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: DocumentReference.subject (example DocumentReference-genomicFileFather): Unable to resolve example reference to Patient/father in DocumentReference-genomicFileFather (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: DocumentReference.subject (example DocumentReference-genomicFileGroupAsSubject): Unable to resolve example reference to Group/groupDenovoFamily in DocumentReference-genomicFileGroupAsSubject (Possible Ids: 101, 102, herd1, example-patientlist, )
  INFORMATION: DocumentReference.subject (example DocumentReference-genomicFileMother): Unable to resolve example reference to Patient/mother in DocumentReference-genomicFileMother (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  WARNING: DocumentReference.based-on: Search Parameter 'DocumentReference.based-on' had no found values in any example. Consider reviewing the expression (DocumentReference.basedOn)
  WARNING: DocumentReference.format-canonical: Search Parameter 'DocumentReference.format-canonical' had no found values in any example. Consider reviewing the expression ((DocumentReference.content.profile.value as canonical))
  WARNING: DocumentReference.format-uri: Search Parameter 'DocumentReference.format-uri' had no found values in any example. Consider reviewing the expression ((DocumentReference.content.profile.value as uri))

Resource InventoryReport:
  INFORMATION: InventoryReport.inventoryListing.itemStatus: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InventoryReport.inventoryListing.items.category: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InventoryReport.operationType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InventoryReport.operationTypeReason: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InventoryReport: A resource that contains a status element must have a search parameter 'status'
  WARNING: InventoryReport.identifier: Short description doesn't add any new content: 'Identifiers for the report'
  WARNING: InventoryReport.inventoryListing.itemStatus: Short description doesn't add any new content: 'The status of the items'
  WARNING: InventoryReport.inventoryListing.items.category: Short description doesn't add any new content: 'The category of the item or items'
  WARNING: InventoryReport.inventoryListing.items.manufacturingDate: Short description doesn't add any new content: 'The manufacturingDate of the item or items'
  WARNING: InventoryReport.inventoryListing.items.quantity: Short description doesn't add any new content: 'The quantity of the item or items'
  WARNING: InventoryReport.inventoryListing.items: Element names should be singular
  WARNING: InventoryReport.note: The max cardinality of 'note' must be *
  WARNING: InventoryReport.operationTypeReason: Element needs a definition of its own
  WARNING: InventoryReport: A resource that contains an identifier must have a search parameter 'identifier'

Resource Observation:
  INFORMATION: Observation.derivedFrom (example observation-example-bmi-using-related): Unable to resolve example reference to Observation/bodyheight in observation-example-bmi-using-related (Possible Ids: example, respiratory-rate, heart-rate, body-temperature, body-height, body-length, head-circumference, bmi, bmi-using-related, satO2, blood-pressure, blood-pressure-dar, mbp, vitals-panel, blood-pressure-cancel, f001, unsat, f002, f003, f004, f005, date-lastmp, f202, f203, f204, f205, f206, ekg, glasgow, gcs-qa, 1minute-apgar-score, 2minute-apgar-score, 5minute-apgar-score, 10minute-apgar-score, 20minute-apgar-score, clinical-gender, eye-color, bmd, 656, alcohol-type, vp-oyster, herd1, vomiting, secondsmoke, trachcare, bgpanel, bloodgroup, rhstatus, decimal, map-sitting, abdo-tender, krcore-observation-labresult-example-01, body-weight-with-arabic-code, )
  INFORMATION: Observation.performer (example observation-example-spirometry): Unable to resolve example reference to Patient/PatientId-patientId in observation-example-spirometry (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Observation.subject (example observation-example-bgpanel): Unable to resolve example reference to Patient/infant in observation-example-bgpanel (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Observation.subject (example observation-example-bloodgroup): Unable to resolve example reference to Patient/infant in observation-example-bloodgroup (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Observation.subject (example observation-example-rhstatus): Unable to resolve example reference to Patient/infant in observation-example-rhstatus (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Observation.subject (example observation-example-secondsmoke): Unable to resolve example reference to Patient/infant in observation-example-secondsmoke (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Observation.subject (example observation-example-spirometry): Unable to resolve example reference to Patient/PatientId-patientId in observation-example-spirometry (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Observation.subject (example observation-example-trachcare): Unable to resolve example reference to Patient/infant in observation-example-trachcare (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Observation.subject (example observation-example-vomiting): Unable to resolve example reference to Patient/infant in observation-example-vomiting (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )

Resource ObservationDefinition:
  INFORMATION: ObservationDefinition.performerType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: ObservationDefinition.subject: An element of type CodeableConcept or Coding must have a binding
  WARNING: ObservationDefinition.experimental: Search Parameter 'ObservationDefinition.experimental' had no found values in any example. Consider reviewing the expression (ObservationDefinition.experimental)
  WARNING: ObservationDefinition.identifier: Search Parameter 'ObservationDefinition.identifier' had no found values in any example. Consider reviewing the expression (ObservationDefinition.identifier)
  WARNING: ObservationDefinition.title: Search Parameter 'ObservationDefinition.title' had no found values in any example. Consider reviewing the expression (ObservationDefinition.title)
  WARNING: ObservationDefinition.url: Search Parameter 'ObservationDefinition.url' had no found values in any example. Consider reviewing the expression (ObservationDefinition.url)

Resource ServiceRequest:
  INFORMATION: ServiceRequest.encounter (example ServiceRequest-genomicSRFather): Unable to resolve example reference to Encounter/denovoEncounter in ServiceRequest-genomicSRFather (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: ServiceRequest.encounter (example ServiceRequest-genomicSRMother): Unable to resolve example reference to Encounter/denovoEncounter in ServiceRequest-genomicSRMother (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: ServiceRequest.encounter (example ServiceRequest-genomicSRProband): Unable to resolve example reference to Encounter/denovoEncounter in ServiceRequest-genomicSRProband (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: ServiceRequest.encounter (example ServiceRequest-genomicServiceRequest): Unable to resolve example reference to Encounter/denovoEncounter in ServiceRequest-genomicServiceRequest (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: ServiceRequest.encounter (example ServiceRequest-genomicServiceRequest2): Unable to resolve example reference to Encounter/genomicEncounter in ServiceRequest-genomicServiceRequest2 (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: ServiceRequest.encounter (example ServiceRequest-genomicServiceRequest3): Unable to resolve example reference to Encounter/denovoEncounter in ServiceRequest-genomicServiceRequest3 (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: ServiceRequest.encounter (example ServiceRequest-genomicServiceRequest4): Unable to resolve example reference to Encounter/denovoEncounter in ServiceRequest-genomicServiceRequest4 (Possible Ids: example, home, f201, f202, f203, f001, f002, f003, xcda, emerg, )
  INFORMATION: ServiceRequest.performer (example servicerequest-example-myringotomy): Unable to resolve example reference to https://fhir.orionhealth.com/blaze/fhir/Practitioner/76597 in servicerequest-example-myringotomy (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: ServiceRequest.requester (example servicerequest-example-myringotomy): Unable to resolve example reference to https://fhir.orionhealth.com/blaze/fhir/Practitioner/77272 in servicerequest-example-myringotomy (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: ServiceRequest.subject (example ServiceRequest-genomicSRFather): Unable to resolve example reference to Patient/father in ServiceRequest-genomicSRFather (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: ServiceRequest.subject (example ServiceRequest-genomicSRMother): Unable to resolve example reference to Patient/mother in ServiceRequest-genomicSRMother (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: ServiceRequest.subject (example ServiceRequest-genomicServiceRequest): Unable to resolve example reference to Patient/denovoChild in ServiceRequest-genomicServiceRequest (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: ServiceRequest.subject (example ServiceRequest-genomicServiceRequest2): Unable to resolve example reference to Patient/genomicPatient in ServiceRequest-genomicServiceRequest2 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: ServiceRequest.subject (example ServiceRequest-genomicServiceRequest3): Unable to resolve example reference to Patient/denovoMother in ServiceRequest-genomicServiceRequest3 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: ServiceRequest.subject (example ServiceRequest-genomicServiceRequest4): Unable to resolve example reference to Patient/denovoFather in ServiceRequest-genomicServiceRequest4 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: ServiceRequest.subject (example servicerequest-example-myringotomy): Unable to resolve example reference to https://fhir.orionhealth.com/blaze/fhir/Patient/77662 in servicerequest-example-myringotomy (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  WARNING: ServiceRequest.body-structure: Search Parameter 'ServiceRequest.body-structure' had no found values in any example. Consider reviewing the expression (ServiceRequest.bodyStructure)
  WARNING: ServiceRequest.code-reference: Search Parameter 'ServiceRequest.code-reference' had no found values in any example. Consider reviewing the expression (ServiceRequest.code.reference)
  WARNING: ServiceRequest.instantiates-canonical: Search Parameter 'ServiceRequest.instantiates-canonical' had no found values in any example. Consider reviewing the expression (ServiceRequest.instantiatesCanonical)
  WARNING: ServiceRequest.instantiates-uri: Search Parameter 'ServiceRequest.instantiates-uri' had no found values in any example. Consider reviewing the expression (ServiceRequest.instantiatesUri)

Resource Specimen:
  INFORMATION: Specimen.collection.collector (example Specimen-denovo-1): Unable to resolve example reference to Practitioner/practitioner01 in Specimen-denovo-1 (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Specimen.collection.collector (example Specimen-denovo-2): Unable to resolve example reference to Practitioner/practitioner01 in Specimen-denovo-2 (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Specimen.collection.collector (example Specimen-denovo-3): Unable to resolve example reference to Practitioner/practitioner01 in Specimen-denovo-3 (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Specimen.collection.collector (example Specimen-genomicSpecimen): Unable to resolve example reference to Practitioner/practitioner01 in Specimen-genomicSpecimen (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Specimen.collection.collector (example Specimen-specimenFather): Unable to resolve example reference to Practitioner/practitioner01 in Specimen-specimenFather (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Specimen.collection.collector (example Specimen-specimenMother): Unable to resolve example reference to Practitioner/practitioner01 in Specimen-specimenMother (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Specimen.collection.collector (example Specimen-specimenProband): Unable to resolve example reference to Practitioner/practitioner01 in Specimen-specimenProband (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )
  INFORMATION: Specimen.container.device (example specimen-example): Unable to resolve example reference to Specimen/specimen-device-container-example-green-gel-vacutainer in specimen-example (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: Specimen.container.device (example specimen-example-pooled-serum): Unable to resolve example reference to Specimen/specimen-device-container-example-red-top-vacutainer in specimen-example-pooled-serum (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: Specimen.container.device (example specimen-example-serum): Unable to resolve example reference to Specimen/specimen-device-container-example-sst-vacutainer in specimen-example-serum (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: Specimen.container.device (example specimen-example-urine): Unable to resolve example reference to Specimen/specimen-device-container-example-polycup in specimen-example-urine (Possible Ids: 101, isolate, vma-urine, sst, pooled-serum, )
  INFORMATION: Specimen.request (example Specimen-denovo-1): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in Specimen-denovo-1 (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: Specimen.request (example Specimen-denovo-2): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in Specimen-denovo-2 (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: Specimen.request (example Specimen-denovo-3): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in Specimen-denovo-3 (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: Specimen.request (example Specimen-genomicSpecimen): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in Specimen-genomicSpecimen (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: Specimen.request (example Specimen-specimenFather): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in Specimen-specimenFather (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: Specimen.request (example Specimen-specimenMother): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in Specimen-specimenMother (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: Specimen.request (example Specimen-specimenProband): Unable to resolve example reference to ServiceRequest/genomicServiceRequest in Specimen-specimenProband (Possible Ids: lipid, di, ft4, example, subrequest, physiotherapy, do-not-turn, benchpress, example-implant, ambulation, colon-biopsy, colonoscopy, appendectomy-narrative, ob, physical-therapy, education, myringotomy, vent, )
  INFORMATION: Specimen.subject (example Specimen-denovo-1): Unable to resolve example reference to Patient/denovoChild in Specimen-denovo-1 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Specimen.subject (example Specimen-denovo-2): Unable to resolve example reference to Patient/denovoMother in Specimen-denovo-2 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Specimen.subject (example Specimen-denovo-3): Unable to resolve example reference to Patient/denovoFather in Specimen-denovo-3 (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Specimen.subject (example Specimen-genomicSpecimen): Unable to resolve example reference to Patient/genomicPatient in Specimen-genomicSpecimen (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Specimen.subject (example Specimen-specimenFather): Unable to resolve example reference to Patient/father in Specimen-specimenFather (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Specimen.subject (example Specimen-specimenMother): Unable to resolve example reference to Patient/mother in Specimen-specimenMother (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  WARNING: Specimen.bodysite: Search Parameter 'Specimen.bodysite' had no found values in any example. Consider reviewing the expression (Specimen.collection.bodySite.reference)
  WARNING: Specimen.container-device: Search Parameter 'Specimen.container-device' had no found values in any example. Consider reviewing the expression (Specimen.container.device.where(resolve() is Device))
  WARNING: Specimen.procedure: Search Parameter 'Specimen.procedure' had no found values in any example. Consider reviewing the expression (Specimen.collection.procedure)

Resource SpecimenDefinition:
  INFORMATION: SpecimenDefinition: A resource must have w5 mappings
  WARNING: SpecimenDefinition.experimental: Search Parameter 'SpecimenDefinition.experimental' had no found values in any example. Consider reviewing the expression (SpecimenDefinition.experimental)
  WARNING: SpecimenDefinition.identifier: Search Parameter 'SpecimenDefinition.identifier' had no found values in any example. Consider reviewing the expression (SpecimenDefinition.identifier)
  WARNING: SpecimenDefinition.is-derived: Search Parameter 'SpecimenDefinition.is-derived' had no found values in any example. Consider reviewing the expression (SpecimenDefinition.typeTested.isDerived)
  WARNING: SpecimenDefinition.title: Search Parameter 'SpecimenDefinition.title' had no found values in any example. Consider reviewing the expression (SpecimenDefinition.title)
  WARNING: SpecimenDefinition.url: Search Parameter 'SpecimenDefinition.url' had no found values in any example. Consider reviewing the expression (SpecimenDefinition.url)

Resource Task:
  INFORMATION: Task.requester (example task-example-fm-cancel): Unable to resolve example reference to Organization/example in task-example-fm-cancel (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: Task.requester (example task-example-fm-poll): Unable to resolve example reference to Organization/example in task-example-fm-poll (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: Task.requester (example task-example-fm-release): Unable to resolve example reference to Organization/example in task-example-fm-release (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: Task.requester (example task-example-fm-reprocess): Unable to resolve example reference to Organization/example in task-example-fm-reprocess (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: Task.requester (example task-example-fm-status): Unable to resolve example reference to Organization/example in task-example-fm-status (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: Task.requester (example task-example-fm-status-resp): Unable to resolve example reference to Organization/example in task-example-fm-status-resp (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )

Resource Transport:
  INFORMATION: Transport.currentLocation (example transport-example): Unable to resolve example reference to Transport/location-labA in transport-example (Possible Ids: simpledelivery, )
  INFORMATION: Transport.requestedLocation (example transport-example): Unable to resolve example reference to Transport/location-hospitalLab in transport-example (Possible Ids: simpledelivery, )
  WARNING: Transport.currentLocation: Short description doesn't add any new content: 'The current location'
  WARNING: Transport: Resource elements are out of order. The correct order is '[intent(=class), priority(=grade), code(=what), focus(=what), for(=who.focus), encounter(=context), completionTime(=when.done), authoredOn(=when.recorded), requester(=who.author), performerType(=who.actor), owner(=who.actor), location(=where), requestedLocation(=where), currentLocation(=where), reasonCode(=why), reasonReference(=why), history(=why)]' but the actual order is '[intent(=class), priority(=grade), code(=what), focus(=what), for(=who.focus), encounter(=context), completionTime(=when.done), authoredOn(=when.recorded), requester(=who.author), performerType(=who.actor), owner(=who.actor), location(=where), reasonCode(=why), reasonReference(=why), requestedLocation(=where), currentLocation(=where), history(=why)]'

  INFORMATION: oo:CodeSystem[container-cap].define: Value set oo:CodeSystem[container-cap].define (ContainerCap/http://terminology.hl7.org/CodeSystem/container-cap): Display Names must be TitleCase: red cap
  INFORMATION: oo:CodeSystem[device-category].define: Value set oo:CodeSystem[device-category].define (FHIRDeviceCategory/http://hl7.org/fhir/device-category): Display Names must be TitleCase: communicating
  INFORMATION: oo:CodeSystem[device-operation-status-reason].define: Code System oo:CodeSystem[device-operation-status-reason].define (FHIRDeviceOperationStatusReason/http://terminology.hl7.org/CodeSystem/device-operation-status-reason): Defined codes must be lowercase-dash: 3::6728
  INFORMATION: oo:CodeSystem[devicedefinition-relationtype].define: Value set oo:CodeSystem[devicedefinition-relationtype].define (DeviceDefinitionRelationType/http://hl7.org/fhir/devicedefinition-relationtype): Display Names must be TitleCase: container
  INFORMATION: oo:CodeSystem[handling-condition].define: Value set oo:CodeSystem[handling-condition].define (HandlingConditionSet/http://terminology.hl7.org/CodeSystem/handling-condition): Display Names must be TitleCase: room temperature
  INFORMATION: oo:CodeSystem[observation-range-category].define: Value set oo:CodeSystem[observation-range-category].define (ObservationRangeCategory/http://hl7.org/fhir/observation-range-category): Display Names must be TitleCase: reference range
  INFORMATION: oo:CodeSystem[permitted-data-type].define: Code System oo:CodeSystem[permitted-data-type].define (ObservationDataType/http://hl7.org/fhir/permitted-data-type): Defined codes must be lowercase-dash: Quantity
  INFORMATION: oo:CodeSystem[permitted-data-type].define: Value set oo:CodeSystem[permitted-data-type].define (ObservationDataType/http://hl7.org/fhir/permitted-data-type): Display Names must be TitleCase: string
  INFORMATION: oo:CodeSystem[product-category].define: Code System oo:CodeSystem[product-category].define (BiologicallyDerivedProductCategory/http://hl7.org/fhir/product-category): Defined codes must be lowercase-dash: biologicalAgent
  INFORMATION: oo:CodeSystem[rejection-criteria].define: Value set oo:CodeSystem[rejection-criteria].define (RejectionCriterion/http://terminology.hl7.org/CodeSystem/rejection-criteria): Display Names must be TitleCase: hemolized specimen
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-bodystructure-code.html (SNOMEDCTMorphologicAbnormalities) & valueset-body-site.html (SNOMEDCTBodyStructures) (description: [acquireds, anatomicals, bodies, structures, sites, snomeds, isas, concepts, wheres, froms, cthttpsnomedinfoscts, alls, 442083009s] / [acquireds, anatomicals, bodies, structures, sites, snomeds, isas, concepts, wheres, froms, cthttpsnomedinfoscts, alls, 442083009s])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-conformance-expectation.html (ConformanceExpectation) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-device-property-type.html (DeviceType) & valueset-device-type.html (DeviceType) (description: [identifies, cts, devices, is, suggestives, snomeds, provideds, isas, httpwwwsnomedorgs, useds, medicals, as, concepts, examples, wheres, 49062001s, tos, froms] / [identifies, cts, devices, is, suggestives, snomeds, provideds, isas, httpwwwsnomedorgs, useds, medicals, as, concepts, examples, wheres, 49062001s, tos, froms])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-deviceusage-adherence-code.html (DeviceUsageAdherenceCode) & valueset-deviceusage-adherence-reason.html (DeviceUsageAdherenceReason) (description: [concepts, devices, codeds, indicatings, usages, adherences] / [concepts, devices, codeds, indicatings, usages, adherences])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-implantStatus.html (Implant Status) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-implantStatus.html (Implant Status) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-not-consumed-reason.html (Reasons for why a food item was not consumed) & valueset-edible-substance-type.html (Types of Edible Substances) (description: [types, substances, its, is, suggestives, includes, snomeds, provideds, edibles, isas, represents, as, examples, concepts, wheres, froms, 762766007s, cthttpsnomedinfoscts] / [types, substances, its, is, suggestives, includes, snomeds, provideds, edibles, isas, represents, as, examples, concepts, wheres, froms, 762766007s, cthttpsnomedinfoscts])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-nutritionproduct-status.html (NutritionProductStatus) & valueset-permission-status.html (PermissionStatus) (description: [stages, lifecycles, identifyings, products] / [stages, lifecycles, identifyings, products])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-nutritionproduct-status.html (NutritionProductStatus) & valueset-product-status.html (ProductStatus) (description: [stages, lifecycles, identifyings, products] / [stages, lifecycles, identifyings, products])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-observation-statistics.html (StatisticsCode) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-implantStatus.html (Implant Status) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-implantStatus.html (Implant Status) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-implantStatus.html (Implant Status) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-transport-code.html (TransportCode) & valueset-task-code.html (TaskCode) (description: [bes, types, expecteds, performeds, indicatings, tos, is, actions] / [bes, types, expecteds, performeds, indicatings, tos, is, actions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Definitions: valueset-type-characteristics-code.html (TypeCharacteristicCodes) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: oo:ValueSetComparison: Duplicate Valueset Names: valueset-device-property-type.html (DeviceType) & valueset-device-type.html (DeviceType) (name: [types, devices] / [types, devices]))

==========================
= Patient Administration =
==========================
Resource Account:
  INFORMATION: Account.relatedAccount.account: Name of child (account) overlaps with name of parent (relatedAccount)

Resource Appointment:
  WARNING: Appointment.service-type-reference: Search Parameter 'Appointment.service-type-reference' had no found values in any example. Consider reviewing the expression (Appointment.serviceType.reference)

Resource ChargeItem:
  INFORMATION: ChargeItem.overrideReason: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: ChargeItem: A resource that contains a status element must have a search parameter 'status'

Resource ChargeItemDefinition:
  INFORMATION: ChargeItemDefinition.instance (example chargeitemdefinition-device-example): Unable to resolve example reference to Device/12345 in chargeitemdefinition-device-example (Possible Ids: example, f001, and20601bpmonitor, ANDThermometer, AndroidGatewayPHG, Bodimetrics, KinsaThermometer, Nonin20601PulseOx, NoninBlePulseOx, PhilipsThermometer, RocheGlucoseMonitor, ihe-pcd, example-pacemaker, example-software, example-udi1, example-udi2, example-udi3, example-udi4, )
  INFORMATION: ChargeItemDefinition.propertyGroup.priceComponent.code: An element of type CodeableConcept or Coding must have a binding
  WARNING: ChargeItemDefinition.context-quantity: Search Parameter 'ChargeItemDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((ChargeItemDefinition.useContext.value as Quantity) | (ChargeItemDefinition.useContext.value as Range))
  WARNING: ChargeItemDefinition.context-type-quantity: Search Parameter 'ChargeItemDefinition.context-type-quantity' had no found values in any example. Consider reviewing the expression (ChargeItemDefinition.useContext)
  WARNING: ChargeItemDefinition.context-type-value: Search Parameter 'ChargeItemDefinition.context-type-value' had no found values in any example. Consider reviewing the expression (ChargeItemDefinition.useContext)
  WARNING: ChargeItemDefinition.context-type: Search Parameter 'ChargeItemDefinition.context-type' had no found values in any example. Consider reviewing the expression (ChargeItemDefinition.useContext.code)
  WARNING: ChargeItemDefinition.context: Search Parameter 'ChargeItemDefinition.context' had no found values in any example. Consider reviewing the expression ((ChargeItemDefinition.useContext.value as CodeableConcept))
  WARNING: ChargeItemDefinition.date: Search Parameter 'ChargeItemDefinition.date' had no found values in any example. Consider reviewing the expression (ChargeItemDefinition.date)
  WARNING: ChargeItemDefinition.jurisdiction: Search Parameter 'ChargeItemDefinition.jurisdiction' had no found values in any example. Consider reviewing the expression (ChargeItemDefinition.jurisdiction)
  WARNING: ChargeItemDefinition.publisher: Search Parameter 'ChargeItemDefinition.publisher' had no found values in any example. Consider reviewing the expression (ChargeItemDefinition.publisher)
  WARNING: ChargeItemDefinition.title: Search Parameter 'ChargeItemDefinition.title' had no found values in any example. Consider reviewing the expression (ChargeItemDefinition.title)

Resource Encounter:
  INFORMATION: Encounter.subject (example Encounter-denovoEncounter): Unable to resolve example reference to Patient/denovoChild in Encounter-denovoEncounter (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: Encounter.subject (example Encounter-genomicEncounter): Unable to resolve example reference to Patient/genomicPatient in Encounter-genomicEncounter (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  WARNING: Encounter.careteam: Search Parameter 'Encounter.careteam' had no found values in any example. Consider reviewing the expression (Encounter.careTeam)
  WARNING: Encounter.practitioner: Search Parameter 'Encounter.practitioner' had no found values in any example. Consider reviewing the expression (Encounter.participant.actor.where(resolve() is Practitioner))
  WARNING: Encounter.reason-reference: Search Parameter 'Encounter.reason-reference' had no found values in any example. Consider reviewing the expression (Encounter.reason.reference)
  WARNING: Encounter.subject-status: Search Parameter 'Encounter.subject-status' had no found values in any example. Consider reviewing the expression (Encounter.subjectStatus)

Resource Endpoint:
  INFORMATION: Endpoint.managingOrganization (example endpoint-example-direct): Unable to resolve example reference to Organization/299 in endpoint-example-direct (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )

Resource EpisodeOfCare:
  INFORMATION: EpisodeOfCare.careTeam: Name of child (careTeam) overlaps with name of parent (EpisodeOfCare)
  WARNING: EpisodeOfCare.condition-concept: Search Parameter 'EpisodeOfCare.condition-concept' had no found values in any example. Consider reviewing the expression (EpisodeOfCare.diagnosis.condition.concept)

Resource HealthcareService:
  INFORMATION: HealthcareService.serviceProvisionCode: Name of child (serviceProvisionCode) overlaps with name of parent (HealthcareService)
  WARNING: HealthcareService.offered-in: Search Parameter 'HealthcareService.offered-in' had no found values in any example. Consider reviewing the expression (HealthcareService.offeredIn)

Resource InsurancePlan:
  INFORMATION: InsurancePlan.coverage.benefit.limit.code: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.coverage.benefit.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.coverage.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.plan.generalCost.cost: Name of child (cost) overlaps with name of parent (generalCost)
  INFORMATION: InsurancePlan.plan.generalCost.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.plan.specificCost.benefit.cost.qualifiers: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.plan.specificCost.benefit.cost.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.plan.specificCost.benefit.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.plan.specificCost.category: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.plan.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: InsurancePlan.plan: Name of child (plan) overlaps with name of parent (InsurancePlan)
  WARNING: InsurancePlan.address-city: Search Parameter 'InsurancePlan.address-city' had no found values in any example. Consider reviewing the expression (InsurancePlan.contact.address.city)
  WARNING: InsurancePlan.address-country: Search Parameter 'InsurancePlan.address-country' had no found values in any example. Consider reviewing the expression (InsurancePlan.contact.address.country)
  WARNING: InsurancePlan.address-postalcode: Search Parameter 'InsurancePlan.address-postalcode' had no found values in any example. Consider reviewing the expression (InsurancePlan.contact.address.postalCode)
  WARNING: InsurancePlan.address-state: Search Parameter 'InsurancePlan.address-state' had no found values in any example. Consider reviewing the expression (InsurancePlan.contact.address.state)
  WARNING: InsurancePlan.address-use: Search Parameter 'InsurancePlan.address-use' had no found values in any example. Consider reviewing the expression (InsurancePlan.contact.address.use)
  WARNING: InsurancePlan.address: Search Parameter 'InsurancePlan.address' had no found values in any example. Consider reviewing the expression (InsurancePlan.contact.address)
  WARNING: InsurancePlan.administered-by: Search Parameter 'InsurancePlan.administered-by' had no found values in any example. Consider reviewing the expression (InsurancePlan.administeredBy)
  WARNING: InsurancePlan.coverage.benefit.limit: Short description doesn't add any new content: 'Benefit limits'
  WARNING: InsurancePlan.coverage.benefit.type: Short description doesn't add any new content: 'Type of benefit'
  WARNING: InsurancePlan.coverage.type: Short description doesn't add any new content: 'Type of coverage'
  WARNING: InsurancePlan.endpoint: Search Parameter 'InsurancePlan.endpoint' had no found values in any example. Consider reviewing the expression (InsurancePlan.endpoint)
  WARNING: InsurancePlan.identifier: Search Parameter 'InsurancePlan.identifier' had no found values in any example. Consider reviewing the expression (InsurancePlan.identifier)
  WARNING: InsurancePlan.owned-by: Search Parameter 'InsurancePlan.owned-by' had no found values in any example. Consider reviewing the expression (InsurancePlan.ownedBy)
  WARNING: InsurancePlan.plan.generalCost.comment: MnM must have confirmed this should not be an Annotation
  WARNING: InsurancePlan.plan.generalCost.type: Short description doesn't add any new content: 'Type of cost'
  WARNING: InsurancePlan.plan.specificCost.benefit.cost.qualifiers: Element names should be singular
  WARNING: InsurancePlan.plan.specificCost.benefit.cost.type: Short description doesn't add any new content: 'Type of cost'
  WARNING: InsurancePlan.plan.specificCost.benefit.type: Short description doesn't add any new content: 'Type of specific benefit'
  WARNING: InsurancePlan.plan.specificCost: Short description doesn't add any new content: 'Specific costs'
  WARNING: InsurancePlan.plan.type: Short description doesn't add any new content: 'Type of plan'
  WARNING: InsurancePlan.status: Search Parameter 'InsurancePlan.status' had no found values in any example. Consider reviewing the expression (InsurancePlan.status)
  WARNING: InsurancePlan.type: Search Parameter 'InsurancePlan.type' had no found values in any example. Consider reviewing the expression (InsurancePlan.type)

Resource Location:
  WARNING: Location.address-city: Search Parameter 'Location.address-city' had no found values in any example. Consider reviewing the expression (Location.address.city)
  WARNING: Location.address-country: Search Parameter 'Location.address-country' had no found values in any example. Consider reviewing the expression (Location.address.country)
  WARNING: Location.address-postalcode: Search Parameter 'Location.address-postalcode' had no found values in any example. Consider reviewing the expression (Location.address.postalCode)
  WARNING: Location.address-state: Search Parameter 'Location.address-state' had no found values in any example. Consider reviewing the expression (Location.address.state)
  WARNING: Location.address-use: Search Parameter 'Location.address-use' had no found values in any example. Consider reviewing the expression (Location.address.use)
  WARNING: Location.address: Search Parameter 'Location.address' had no found values in any example. Consider reviewing the expression (Location.address)
  WARNING: Location.characteristic: Search Parameter 'Location.characteristic' had no found values in any example. Consider reviewing the expression (Location.characteristic)

Resource OrganizationAffiliation:
  INFORMATION: OrganizationAffiliation.endpoint (example orgrole-example-hie): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/Endpoint/foundingfathersHIE in orgrole-example-hie (Possible Ids: example, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, example-iid, example-wadors, direct-endpoint, )
  INFORMATION: OrganizationAffiliation.healthcareService (example orgrole-example-services): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/HealthcareService/independencerehab1 in orgrole-example-services (Possible Ids: example, )
  INFORMATION: OrganizationAffiliation.healthcareService (example orgrole-example-services): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/HealthcareService/independencerehab2 in orgrole-example-services (Possible Ids: example, )
  INFORMATION: OrganizationAffiliation.location (example orgrole-example-services): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/Location/foundingfathers1 in orgrole-example-services (Possible Ids: 1, 2, amb, ph, ukp, hl7, 3ad0687e-f477-468c-afd5-fcc2bf897819, wash-dc-metro, )
  INFORMATION: OrganizationAffiliation.organization (example orgrole-example-hie): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/Organization/monumentHIE in orgrole-example-hie (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: OrganizationAffiliation.organization (example orgrole-example-services): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/Organization/foundingfathers in orgrole-example-services (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: OrganizationAffiliation.participatingOrganization (example orgrole-example-hie): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/Organization/foundingfathers in orgrole-example-hie (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  INFORMATION: OrganizationAffiliation.participatingOrganization (example orgrole-example-services): Unable to resolve example reference to http://hl7.org/fhir/ig/vhdir/Organization/independencerehab in orgrole-example-services (Possible Ids: hl7, 1, 1832473e-2fe0-452d-abe9-3cdb9879522f, 2, 2.16.840.1.113883.19.5, f001, f002, f201, f203, f003, mmanu, 3, hl7pay, )
  WARNING: OrganizationAffiliation.network (example orgrole-example-services): Unable to resolve invalid example reference http://hl7.org/fhir/ig/vhdir/Network/patriotppo in orgrole-example-services

Resource Patient:
  INFORMATION: Patient.generalPractitioner (example patient-example-infant-mom): Unable to resolve example reference to Practitioner/21B in patient-example-infant-mom (Possible Ids: example, xcda-author, 3ad0687e-f477-468c-afd5-fcc2bf897809, f001, f002, f003, f004, f005, f201, f202, f203, f204, f006, f007, xcda1, )

Resource Person:
  WARNING: Person.death-date: Search Parameter 'Person.death-date' had no found values in any example. Consider reviewing the expression ((Person.deceased as dateTime))

Resource Practitioner:
  WARNING: Practitioner.death-date: Search Parameter 'Practitioner.death-date' had no found values in any example. Consider reviewing the expression ((Practitioner.deceased as dateTime))

Resource RelatedPerson:
  INFORMATION: RelatedPerson.patient (example RelatedPerson-denovoFather): Unable to resolve example reference to Patient/denovoChild in RelatedPerson-denovoFather (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )
  INFORMATION: RelatedPerson.patient (example RelatedPerson-denovoMother): Unable to resolve example reference to Patient/denovoChild in RelatedPerson-denovoMother (Possible Ids: example, pat1, pat2, pat3, pat4, b248b1b2-1686-4b94-9936-37d7a5f94b51, patient-example-sex-and-gender, b0a5e4277-83c4-4adb-87e2-e3efe3369b6f, xcda, xds, animal, dicom, ihe-pcd, f001, f201, glossy, proband, genetics-example1, ch-example, newborn, mom, infant-twin-1, infant-twin-2, infant-fetal, infant-mom, )

Resource Schedule:
  WARNING: Schedule.name: Search Parameter 'Schedule.name' had no found values in any example. Consider reviewing the expression (Schedule.name)
  WARNING: Schedule.service-type-reference: Search Parameter 'Schedule.service-type-reference' had no found values in any example. Consider reviewing the expression (Schedule.serviceType.reference)

Resource Slot:
  WARNING: Slot.service-type-reference: Search Parameter 'Slot.service-type-reference' had no found values in any example. Consider reviewing the expression (Slot.serviceType.reference)

Resource VerificationResult:
  INFORMATION: VerificationResult: A resource must have w5 mappings
  INFORMATION: VerificationResult: A resource that contains a status element must have a search parameter 'status'
  WARNING: VerificationResult.attestation.proxySignature: Short description doesn't add any new content: 'Proxy signature'
  WARNING: VerificationResult.target: Search Parameter 'VerificationResult.target' had no found values in any example. Consider reviewing the expression (VerificationResult.target)
  WARNING: VerificationResult.validator.attestationSignature: Short description doesn't add any new content: 'Validator signature'
  WARNING: VerificationResult: A resource must have an 'entered in error' status
  WARNING: VerificationResult: All resources should have an identifier

  INFORMATION: pa:CodeSystem[account-relationship].define[0]: Code System 'http://hl7.org/fhir/account-relationship' has a code without a definition ('parent')
  INFORMATION: pa:CodeSystem[international-civil-aviation-organization-sex-or-gender].define: Code System pa:CodeSystem[international-civil-aviation-organization-sex-or-gender].define (International Civil Aviation Organization Sex or Gender/http://terminology.hl7.org/CodeSystem/international-civil-aviation-organization-sex-or-gender): Defined codes must be lowercase-dash: F
  INFORMATION: pa:CodeSystem[invoice-priceComponentType].define: Value set pa:CodeSystem[invoice-priceComponentType].define (InvoicePriceComponentType/http://hl7.org/fhir/invoice-priceComponentType): Display Names must be TitleCase: base price
  INFORMATION: pa:CodeSystem[language-preference-type].define: Value set pa:CodeSystem[language-preference-type].define (LanguagePreferenceType/http://hl7.org/fhir/language-preference-type): Display Names must be TitleCase: verbal
  INFORMATION: pa:CodeSystem[location-characteristic].define: Value set pa:CodeSystem[location-characteristic].define (LocationCharacteristic/http://hl7.org/fhir/location-characteristic): Display Names must be TitleCase: translation services available
  INFORMATION: pa:CodeSystem[organization-role].define: Code System pa:CodeSystem[organization-role].define (OrganizationAffiliationRole/http://hl7.org/fhir/organization-role): Defined codes must be lowercase-dash: HIE/HIO
  INFORMATION: pa:CodeSystem[practitioner-job-title].define[0]: Code System 'http://hl7.org/fhir/practitioner-job-title' has a code without a definition ('head-surgery')
  INFORMATION: pa:CodeSystem[price-component-type].define: Value set pa:CodeSystem[price-component-type].define (PriceComponentType/http://hl7.org/fhir/price-component-type): Display Names must be TitleCase: base price
  INFORMATION: pa:CodeSystem[week-of-month].define[0]: Code System 'http://hl7.org/fhir/week-of-month' has a code without a definition ('first')
  WARNING: pa:ValueSetComparison: Duplicate Valueset Definitions: valueset-invoice-priceComponentType.html (InvoicePriceComponentType) & valueset-price-component-type.html (PriceComponentType) (description: [components, indicatings, kinds, prices] / [components, indicatings, kinds, prices])
  WARNING: pa:ValueSetComparison: Duplicate Valueset Names: valueset-encounter-diet.html (Diet) & valueset-diet-type.html (DietCodes) (name: [diets] / [diets]))
  WARNING: pa:ValueSetComparison: Duplicate Valueset Names: valueset-verificationresult-status.html (status) & valueset-definition-status.html (DefinitionStatus) (name: [statuses] / [statuses]))
  WARNING: pa:ValueSet[recorded-sex-or-gender-type].compose.include[2]: The code '0010,0040' is not valid in the system http://dicom.nema.org/resources/ontology/DCM (1)

================
= Patient Care =
================
Resource AdverseEvent:
  WARNING: AdverseEvent.actuality: Search Parameter 'AdverseEvent.actuality' had no found values in any example. Consider reviewing the expression (AdverseEvent.actuality)
  WARNING: AdverseEvent.category: Search Parameter 'AdverseEvent.category' had no found values in any example. Consider reviewing the expression (AdverseEvent.category)
  WARNING: AdverseEvent.code: Search Parameter 'AdverseEvent.code' had no found values in any example. Consider reviewing the expression (AdverseEvent.code)
  WARNING: AdverseEvent.date: Search Parameter 'AdverseEvent.date' had no found values in any example. Consider reviewing the expression (AdverseEvent.occurrence)
  WARNING: AdverseEvent.identifier: Search Parameter 'AdverseEvent.identifier' had no found values in any example. Consider reviewing the expression (AdverseEvent.identifier)
  WARNING: AdverseEvent.location: Search Parameter 'AdverseEvent.location' had no found values in any example. Consider reviewing the expression (AdverseEvent.location)
  WARNING: AdverseEvent.patient: Search Parameter 'AdverseEvent.patient' had no found values in any example. Consider reviewing the expression (AdverseEvent.subject)
  WARNING: AdverseEvent.recorder: Search Parameter 'AdverseEvent.recorder' had no found values in any example. Consider reviewing the expression (AdverseEvent.recorder)
  WARNING: AdverseEvent.resultingcondition: Search Parameter 'AdverseEvent.resultingcondition' had no found values in any example. Consider reviewing the expression (AdverseEvent.resultingCondition)
  WARNING: AdverseEvent.seriousness: Search Parameter 'AdverseEvent.seriousness' had no found values in any example. Consider reviewing the expression (AdverseEvent.seriousness)
  WARNING: AdverseEvent.status: Search Parameter 'AdverseEvent.status' had no found values in any example. Consider reviewing the expression (AdverseEvent.status)
  WARNING: AdverseEvent.study: Search Parameter 'AdverseEvent.study' had no found values in any example. Consider reviewing the expression (AdverseEvent.study)
  WARNING: AdverseEvent.subject: Search Parameter 'AdverseEvent.subject' had no found values in any example. Consider reviewing the expression (AdverseEvent.subject)
  WARNING: AdverseEvent.substance: Search Parameter 'AdverseEvent.substance' had no found values in any example. Consider reviewing the expression ((AdverseEvent.suspectEntity.instance as Reference))

Resource AllergyIntolerance:
  WARNING: AllergyIntolerance.manifestation-reference: Search Parameter 'AllergyIntolerance.manifestation-reference' had no found values in any example. Consider reviewing the expression (AllergyIntolerance.reaction.manifestation.reference)

Resource CarePlan:
  WARNING: CarePlan.instantiates-canonical: Search Parameter 'CarePlan.instantiates-canonical' had no found values in any example. Consider reviewing the expression (CarePlan.instantiatesCanonical)

Resource ClinicalImpression:
  WARNING: ClinicalImpression.finding-ref: Search Parameter 'ClinicalImpression.finding-ref' had no found values in any example. Consider reviewing the expression (ClinicalImpression.finding.item.reference)
  WARNING: ClinicalImpression.previous: Search Parameter 'ClinicalImpression.previous' had no found values in any example. Consider reviewing the expression (ClinicalImpression.previous)
  WARNING: ClinicalImpression.supporting-info: Search Parameter 'ClinicalImpression.supporting-info' had no found values in any example. Consider reviewing the expression (ClinicalImpression.supportingInfo)

Resource Communication:
  WARNING: Communication.instantiates-canonical: Search Parameter 'Communication.instantiates-canonical' had no found values in any example. Consider reviewing the expression (Communication.instantiatesCanonical)
  WARNING: Communication.topic: Search Parameter 'Communication.topic' had no found values in any example. Consider reviewing the expression (Communication.topic)

Resource ConditionDefinition:
  INFORMATION: ConditionDefinition.definition: Name of child (definition) overlaps with name of parent (ConditionDefinition)
  INFORMATION: ConditionDefinition.plan.role: An element of type CodeableConcept or Coding must have a binding
  WARNING: ConditionDefinition.context-quantity: Search Parameter 'ConditionDefinition.context-quantity' had no found values in any example. Consider reviewing the expression ((ConditionDefinition.useContext.value as Quantity) | (ConditionDefinition.useContext.value as Range))
  WARNING: ConditionDefinition.context-type-quantity: Search Parameter 'ConditionDefinition.context-type-quantity' had no found values in any example. Consider reviewing the expression (ConditionDefinition.useContext)
  WARNING: ConditionDefinition.context-type-value: Search Parameter 'ConditionDefinition.context-type-value' had no found values in any example. Consider reviewing the expression (ConditionDefinition.useContext)
  WARNING: ConditionDefinition.context-type: Search Parameter 'ConditionDefinition.context-type' had no found values in any example. Consider reviewing the expression (ConditionDefinition.useContext.code)
  WARNING: ConditionDefinition.context: Search Parameter 'ConditionDefinition.context' had no found values in any example. Consider reviewing the expression ((ConditionDefinition.useContext.value as CodeableConcept))
  WARNING: ConditionDefinition.description: Search Parameter 'ConditionDefinition.description' had no found values in any example. Consider reviewing the expression (ConditionDefinition.description)
  WARNING: ConditionDefinition.jurisdiction: Search Parameter 'ConditionDefinition.jurisdiction' had no found values in any example. Consider reviewing the expression (ConditionDefinition.jurisdiction)
  WARNING: ConditionDefinition.publisher: Search Parameter 'ConditionDefinition.publisher' had no found values in any example. Consider reviewing the expression (ConditionDefinition.publisher)
  WARNING: ConditionDefinition.questionnaire: Short description doesn't add any new content: 'Questionnaire for this condition'
  WARNING: ConditionDefinition.version: Search Parameter 'ConditionDefinition.version' had no found values in any example. Consider reviewing the expression (ConditionDefinition.version)
  WARNING: ConditionDefinition: Short description doesn't add any new content: 'A definition of a condition'

Resource FamilyMemberHistory:
  WARNING: FamilyMemberHistory.instantiates-canonical: Search Parameter 'FamilyMemberHistory.instantiates-canonical' had no found values in any example. Consider reviewing the expression (FamilyMemberHistory.instantiatesCanonical)

Resource Goal:
  INFORMATION: Goal: Search Parameter name 'lifecycle-status' does not follow the style guide

  INFORMATION: pc:CodeSystem[adverse-event-causality-method].define[0]: Code System 'http://terminology.hl7.org/CodeSystem/adverse-event-causality-method' has a code without a definition ('probability-scale')
  INFORMATION: pc:CodeSystem[flag-priority].define: Code System pc:CodeSystem[flag-priority].define (FlagPriorityCodes/http://hl7.org/fhir/flag-priority-code): Defined codes must be lowercase-dash: PN
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-implantStatus.html (Implant Status) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-inheritance-control-code.html (InheritanceControlCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-resource-validation-mode.html (ResourceValidationMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-acceptance-status.html (GoalAcceptanceStatus) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-goal-relationship-type.html (GoalRelationshipType) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-goal-acceptance-status.html (GoalAcceptanceStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-goal-acceptance-status.html (GoalAcceptanceStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-implantStatus.html (Implant Status) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-inheritance-control-code.html (InheritanceControlCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-resource-validation-mode.html (ResourceValidationMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-goal-acceptance-status.html (GoalAcceptanceStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-reaction-event-certainty.html (AllergyIntoleranceCertainty) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: pc:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])

============
= Pharmacy =
============
Resource FormularyItem:
  INFORMATION: FormularyItem: A resource that contains a status element must have a search parameter 'status'
  WARNING: FormularyItem.identifier: Search Parameter 'FormularyItem.identifier' had no found values in any example. Consider reviewing the expression (FormularyItem.identifier)

Resource MedicationKnowledge:
  INFORMATION: MedicationKnowledge.cost.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.indicationGuideline.dosingGuideline.administrationTreatment: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.indicationGuideline.dosingGuideline.treatmentIntent: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.intendedJurisdiction: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.medicineClassification.classification: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.medicineClassification.classification: Name of child (classification) overlaps with name of parent (medicineClassification)
  INFORMATION: MedicationKnowledge.medicineClassification.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.monitoringProgram.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.monograph.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.productType: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.regulatory.regulatoryAuthority: Name of child (regulatoryAuthority) overlaps with name of parent (regulatory)
  INFORMATION: MedicationKnowledge.regulatory.schedule: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.regulatory.substitution.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.relatedMedicationKnowledge.type: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: MedicationKnowledge.storageGuideline.environmentalSetting.type: An element of type CodeableConcept or Coding must have a binding
  WARNING: MedicationKnowledge.classification-type: Search Parameter 'MedicationKnowledge.classification-type' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.medicineClassification.type)
  WARNING: MedicationKnowledge.classification: Search Parameter 'MedicationKnowledge.classification' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.medicineClassification.classification)
  WARNING: MedicationKnowledge.identifier: Search Parameter 'MedicationKnowledge.identifier' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.identifier)
  WARNING: MedicationKnowledge.ingredient-code: Search Parameter 'MedicationKnowledge.ingredient-code' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.definitional.ingredient.item.concept)
  WARNING: MedicationKnowledge.ingredient: Search Parameter 'MedicationKnowledge.ingredient' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.definitional.ingredient.item.reference)
  WARNING: MedicationKnowledge.monitoring-program-name: Search Parameter 'MedicationKnowledge.monitoring-program-name' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.monitoringProgram.name)
  WARNING: MedicationKnowledge.monitoring-program-type: Search Parameter 'MedicationKnowledge.monitoring-program-type' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.monitoringProgram.type)
  WARNING: MedicationKnowledge.monograph-type: Search Parameter 'MedicationKnowledge.monograph-type' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.monograph.type)
  WARNING: MedicationKnowledge.monograph: Search Parameter 'MedicationKnowledge.monograph' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.monograph.source)
  WARNING: MedicationKnowledge.product-type: Search Parameter 'MedicationKnowledge.product-type' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.productType)
  WARNING: MedicationKnowledge.source-cost: Search Parameter 'MedicationKnowledge.source-cost' had no found values in any example. Consider reviewing the expression (MedicationKnowledge.cost.source)

  INFORMATION: phx:CodeSystem[medication-intended-performer-role].define[0]: Code System 'http://hl7.org/fhir/CodeSystem/medication-intended-performer-role' has a code without a definition ('registerednurse')

============
= Security =
============
Resource Permission:
  INFORMATION: Permission.rule.data.security: An element of type CodeableConcept or Coding must have a binding
  INFORMATION: Permission: A resource must have w5 mappings
  WARNING: Permission: All resources should have an identifier

  WARNING: sec:ValueSetComparison: Duplicate Valueset Definitions: valueset-product-status.html (ProductStatus) & valueset-permission-status.html (PermissionStatus) (description: [stages, lifecycles, identifyings, products] / [stages, lifecycles, identifyings, products])

========================
= Structured Documents =
========================
Resource Composition:
  WARNING: Composition.url: Search Parameter 'Composition.url' had no found values in any example. Consider reviewing the expression (Composition.url)
  WARNING: Composition.version: Search Parameter 'Composition.version' had no found values in any example. Consider reviewing the expression (Composition.version)

  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-catalogType.html (CatalogType) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-catalogType.html (CatalogType) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-catalogType.html (CatalogType) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-catalogType.html (CatalogType) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-catalogType.html (CatalogType) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: sd:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])

==============
= Vocabulary =
==============
Resource CodeSystem:
  WARNING: CodeSystem.context-quantity: Search Parameter 'CodeSystem.context-quantity' had no found values in any example. Consider reviewing the expression ((CodeSystem.useContext.value as Quantity) | (CodeSystem.useContext.value as Range))
  WARNING: CodeSystem.derived-from: Search Parameter 'CodeSystem.derived-from' had no found values in any example. Consider reviewing the expression (CodeSystem.relatedArtifact.where(type='derived-from').resource)
  WARNING: CodeSystem.effective: Search Parameter 'CodeSystem.effective' had no found values in any example. Consider reviewing the expression (CodeSystem.effectivePeriod)
  WARNING: CodeSystem.predecessor: Search Parameter 'CodeSystem.predecessor' had no found values in any example. Consider reviewing the expression (CodeSystem.relatedArtifact.where(type='predecessor').resource)
  WARNING: CodeSystem.supplements (example codesystem-example-supplement-2): Unable to resolve invalid example reference http://hl7.org/fhir/bundle-type in codesystem-example-supplement-2
  WARNING: CodeSystem.topic: Search Parameter 'CodeSystem.topic' had no found values in any example. Consider reviewing the expression (CodeSystem.topic)

Resource ConceptMap:
  INFORMATION: ConceptMap.group.element.target.dependsOn.value[x]: An element of type CodeableConcept or Coding must have a binding
  WARNING: ConceptMap.context-quantity: Search Parameter 'ConceptMap.context-quantity' had no found values in any example. Consider reviewing the expression ((ConceptMap.useContext.value as Quantity) | (ConceptMap.useContext.value as Range))
  WARNING: ConceptMap.derived-from: Search Parameter 'ConceptMap.derived-from' had no found values in any example. Consider reviewing the expression (ConceptMap.relatedArtifact.where(type='derived-from').resource)
  WARNING: ConceptMap.effective: Search Parameter 'ConceptMap.effective' had no found values in any example. Consider reviewing the expression (ConceptMap.effectivePeriod)
  WARNING: ConceptMap.group.source (example conceptmap-example): Unable to resolve invalid example reference http://hl7.org/fhir/address-use in conceptmap-example
  WARNING: ConceptMap.group.source (example conceptmap-example-metadata): Unable to resolve invalid example reference http://hl7.org/fhir/address-use in conceptmap-example-metadata
  WARNING: ConceptMap.group.source (example conceptmap-example-metadata-2): Unable to resolve invalid example reference http://hl7.org/fhir/address-use in conceptmap-example-metadata-2
  WARNING: ConceptMap.group.target (example conceptmap-103): Unable to resolve invalid example reference http://hl7.org/fhir/sid/icd-10-cm in conceptmap-103
  WARNING: ConceptMap.group.target (example conceptmap-example-priority): Unable to resolve invalid example reference http://hl7.org/fhir/sid/icd-10 in conceptmap-example-priority
  WARNING: ConceptMap.predecessor: Search Parameter 'ConceptMap.predecessor' had no found values in any example. Consider reviewing the expression (ConceptMap.relatedArtifact.where(type='predecessor').resource)
  WARNING: ConceptMap.topic: Search Parameter 'ConceptMap.topic' had no found values in any example. Consider reviewing the expression (ConceptMap.topic)

Resource NamingSystem:
  WARNING: NamingSystem.context-quantity: Search Parameter 'NamingSystem.context-quantity' had no found values in any example. Consider reviewing the expression ((NamingSystem.useContext.value as Quantity) | (NamingSystem.useContext.value as Range))
  WARNING: NamingSystem.context-type-quantity: Search Parameter 'NamingSystem.context-type-quantity' had no found values in any example. Consider reviewing the expression (NamingSystem.useContext)
  WARNING: NamingSystem.context-type-value: Search Parameter 'NamingSystem.context-type-value' had no found values in any example. Consider reviewing the expression (NamingSystem.useContext)
  WARNING: NamingSystem.context-type: Search Parameter 'NamingSystem.context-type' had no found values in any example. Consider reviewing the expression (NamingSystem.useContext.code)
  WARNING: NamingSystem.context: Search Parameter 'NamingSystem.context' had no found values in any example. Consider reviewing the expression ((NamingSystem.useContext.value as CodeableConcept))

Resource TerminologyCapabilities:
  WARNING: TerminologyCapabilities.codeSystem.uri (example terminologycapabilities-terminology-server): Unable to resolve invalid example reference http://hl7.org/fhir/gender-identity in terminologycapabilities-terminology-server
  WARNING: TerminologyCapabilities.context-quantity: Search Parameter 'TerminologyCapabilities.context-quantity' had no found values in any example. Consider reviewing the expression ((TerminologyCapabilities.useContext.value as Quantity) | (TerminologyCapabilities.useContext.value as Range))
  WARNING: TerminologyCapabilities.context-type-quantity: Search Parameter 'TerminologyCapabilities.context-type-quantity' had no found values in any example. Consider reviewing the expression (TerminologyCapabilities.useContext)
  WARNING: TerminologyCapabilities.context-type-value: Search Parameter 'TerminologyCapabilities.context-type-value' had no found values in any example. Consider reviewing the expression (TerminologyCapabilities.useContext)
  WARNING: TerminologyCapabilities.context-type: Search Parameter 'TerminologyCapabilities.context-type' had no found values in any example. Consider reviewing the expression (TerminologyCapabilities.useContext.code)
  WARNING: TerminologyCapabilities.context: Search Parameter 'TerminologyCapabilities.context' had no found values in any example. Consider reviewing the expression ((TerminologyCapabilities.useContext.value as CodeableConcept))
  WARNING: TerminologyCapabilities.jurisdiction: Search Parameter 'TerminologyCapabilities.jurisdiction' had no found values in any example. Consider reviewing the expression (TerminologyCapabilities.jurisdiction)

Resource ValueSet:
  WARNING: ValueSet.derived-from: Search Parameter 'ValueSet.derived-from' had no found values in any example. Consider reviewing the expression (ValueSet.relatedArtifact.where(type='derived-from').resource)
  WARNING: ValueSet.effective: Search Parameter 'ValueSet.effective' had no found values in any example. Consider reviewing the expression (ValueSet.effectivePeriod)
  WARNING: ValueSet.predecessor: Search Parameter 'ValueSet.predecessor' had no found values in any example. Consider reviewing the expression (ValueSet.relatedArtifact.where(type='predecessor').resource)
  WARNING: ValueSet.topic: Search Parameter 'ValueSet.topic' had no found values in any example. Consider reviewing the expression (ValueSet.topic)

  INFORMATION: vocab:CodeSystem[concept-properties].define: Code System vocab:CodeSystem[concept-properties].define (ConceptProperties/http://hl7.org/fhir/concept-properties): Defined codes must be lowercase-dash: effectiveDate
  INFORMATION: vocab:CodeSystem[concept-properties].define: Value set vocab:CodeSystem[concept-properties].define (ConceptProperties/http://hl7.org/fhir/concept-properties): Display Names must be TitleCase: effectiveDate
  INFORMATION: vocab:CodeSystem[concept-property-type].define: Code System vocab:CodeSystem[concept-property-type].define (PropertyType/http://hl7.org/fhir/concept-property-type): Defined codes must be lowercase-dash: Coding
  INFORMATION: vocab:CodeSystem[concept-property-type].define: Value set vocab:CodeSystem[concept-property-type].define (PropertyType/http://hl7.org/fhir/concept-property-type): Display Names must be TitleCase: code (internal reference)
  INFORMATION: vocab:CodeSystem[conceptmap-properties].define: Code System vocab:CodeSystem[conceptmap-properties].define (ConceptMap Properties/http://hl7.org/fhir/conceptmap-properties): Defined codes must be lowercase-dash: relationshipRefinement
  INFORMATION: vocab:CodeSystem[filter-operator].define: Code System vocab:CodeSystem[filter-operator].define (FilterOperator/http://hl7.org/fhir/filter-operator): Defined codes must be lowercase-dash: =
  INFORMATION: vocab:CodeSystem[operation-outcome].define: Code System vocab:CodeSystem[operation-outcome].define (OperationOutcomeCodes/http://terminology.hl7.org/CodeSystem/operation-outcome): Defined codes must be lowercase-dash: DELETE_MULTIPLE_MATCHES
  INFORMATION: vocab:CodeSystem[operation-outcome].define: Value set vocab:CodeSystem[operation-outcome].define (OperationOutcomeCodes/http://terminology.hl7.org/CodeSystem/operation-outcome): Display Names must be TitleCase: unable to allocate resource id
  INFORMATION: vocab:CodeSystem[operation-outcome].define[0]: Code System 'http://terminology.hl7.org/CodeSystem/operation-outcome' has a code without a definition ('DELETE_MULTIPLE_MATCHES')
  WARNING: vocab:CodeSystem[cdshooks-indicator].copyright: Value set codesystem-cdshooks-indicator (Indicator): A copyright statement should be present for any value set that includes non-HL7 sourced codes (http://cds-hooks.hl7.org/CodeSystem/indicator)
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-altcode-kind.html (AlternativeCodeKind) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-devicedefinition-relationtype.html (DeviceDefinitionRelationType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-goal-relationship-type.html (GoalRelationshipType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-hl7-work-group.html (HL7Workgroup) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-implantStatus.html (Implant Status) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-inheritance-control-code.html (InheritanceControlCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-match-grade.html (MatchGrade) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-resource-validation-mode.html (ResourceValidationMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-standards-status.html (StandardsStatus) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-template-status-code.html (TemplateStatusCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-expansion-parameter-source.html (ExpansionParameterSource) & valueset-allerg-intol-substance-exp-risk.html (AllergyIntoleranceSubstanceExposureRisk) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-expansion-parameter-source.html (ExpansionParameterSource) & valueset-catalogType.html (CatalogType) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-expansion-parameter-source.html (ExpansionParameterSource) & valueset-choice-list-orientation.html (ChoiceListOrientation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-expansion-parameter-source.html (ExpansionParameterSource) & valueset-conformance-expectation.html (ConformanceExpectation) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-expansion-parameter-source.html (ExpansionParameterSource) & valueset-observation-statistics.html (StatisticsCode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-expansion-parameter-source.html (ExpansionParameterSource) & valueset-type-characteristics-code.html (TypeCharacteristicCodes) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-hl7-work-group.html (HL7Workgroup) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-inheritance-control-code.html (InheritanceControlCodes) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-match-grade.html (MatchGrade) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-namingsystem-identifier-type.html (NamingSystemIdentifierType) & valueset-namingsystem-identifier-system-type.html (NamingSystemIdentifierSystemType) (description: [useds, identifies, identifiers, uniques, tos, styles, namespaces] / [useds, identifies, identifiers, uniques, tos, styles, namespaces])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-questionnaire-usage-mode.html (QuestionnaireItemUsageMode) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-codesystem-properties-mode.html (CodeSystemPropertiesMode) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-security-category.html (ResourceSecurityCategory) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-codesystem-altcode-kind.html (AlternativeCodeKind) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-resource-validation-mode.html (ResourceValidationMode) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-standards-status.html (StandardsStatus) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-concept-subsumption-outcome.html (ConceptSubsumptionOutcome) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Definitions: valueset-template-status-code.html (TemplateStatusCode) & valueset-expansion-parameter-source.html (ExpansionParameterSource) (description: [heres, neededs, descriptions] / [heres, neededs, descriptions])
  WARNING: vocab:ValueSetComparison: Duplicate Valueset Names: valueset-namingsystem-identifier-type.html (NamingSystemIdentifierType) & valueset-namingsystem-identifier-system-type.html (NamingSystemIdentifierSystemType) (name: [types, identifiers, namings] / [types, identifiers, namings]))
  WARNING: vocab:ValueSet[cdshooks-indicator].copyright: Value set valueset-cdshooks-indicator (Indicator): A copyright statement should be present for any value set that includes non-HL7 sourced codes (http://cds-hooks.hl7.org/CodeSystem/indicator)
  WARNING: vocab:ValueSet[jurisdiction].copyright: Value set valueset-jurisdiction (Jurisdiction ValueSet): A copyright statement should be present for any value set that includes non-HL7 sourced codes (http://unstats.un.org/unsd/methods/m49/m49.htm)

Errors: 0 Warnings: 763 Hints: 702

===Resources with FMM forced to 0===
Biomedical Research and Regulation:
  AdministrableProductDefinition(2), ClinicalUseDefinition(2), Ingredient(2), ManufacturedItemDefinition(2), MedicinalProductDefinition(3), PackagedProductDefinition(2), RegulatedAuthorization(2), Substance(2), SubstanceDefinition(1)
Clinical Decision Support:
  Evidence(1), EvidenceVariable(1), GuidanceResponse(2), RequestOrchestration(2), RiskAssessment(1)
Clinical Quality Information:
  MeasureReport(3)
Community Based Collaborative Care:
  Consent(2)
FHIR Infrastructure:
  CapabilityStatement(5), CompartmentDefinition(1), DomainResource(5), ExampleScenario(1), GraphDefinition(1), ImplementationGuide(1), OperationDefinition(5), Questionnaire(3), QuestionnaireResponse(3), Resource(5), SearchParameter(3), StructureDefinition(5), StructureMap(2), Subscription(2)
Financial Management:
  Claim(2), ClaimResponse(2), Contract(1), ExplanationOfBenefit(2), PaymentReconciliation(2)
Imaging Integration:
  ImagingSelection(1)
Infrastructure And Messaging:
  MessageDefinition(1)
Orders and Observations:
  BiologicallyDerivedProduct(2), BodyStructure(1), Device(2), DeviceDefinition(1), DeviceUsage(1), DocumentReference(3), Observation(5), ObservationDefinition(1), ServiceRequest(2), Specimen(2), SpecimenDefinition(1), Task(2)
Patient Administration:
  Account(2), Appointment(3), Encounter(2), Endpoint(2), EpisodeOfCare(2), HealthcareService(2), Location(3), Patient(5), Person(2), Practitioner(3), RelatedPerson(2), Schedule(3), Slot(3)
Patient Care:
  AllergyIntolerance(3), CarePlan(2), Communication(2), FamilyMemberHistory(2), Goal(2)
Pharmacy:
  MedicationKnowledge(1)
Structured Documents:
  Composition(2)
Vocabulary:
  CodeSystem(5), ConceptMap(1), NamingSystem(2), TerminologyCapabilities(1), ValueSet(5)
 4.845 3084sec 1924MB
This was a Full Build                                                      0.365 3084sec 2051MB
Finished publishing FHIR @ Tue, Sep 6, 2022 11:50-0500                     0.862 3085sec 2051MB

Deprecated Gradle features were used in this build, making it incompatible with Gradle 8.0.

You can use '--warning-mode all' to show the individual deprecation warnings and determine if they come from your own scripts or plugins.

See https://docs.gradle.org/7.3.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 51m 32s
1 actionable task: 1 executed
RHausamMacbookAir:fhir rhausam$ 
