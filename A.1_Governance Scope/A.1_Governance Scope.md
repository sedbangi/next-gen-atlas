``` json
{
    "A.1.3": {
        "Name": "Atlas Documents",
        "Version": 1,
        "Type": "Article",
        "Components": {
            "Content": "Atlas Documents are integral to NEWDAO's structure and governance. They are organized into document trees, starting with Immutable Documents, containing the Spirit of the Atlas, and Adaptive Documents for operationalization and evolution. The Sections of this Article provide detailed insight into the properties, evolution, and processes related to Atlas Documents."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.1",
            "A.1.3.2",
            "A.1.3.3",
            "A.1.3.4",
            "A.1.3.5"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.0": {
        "Name": "Supporting Root",
        "Version": 1,
        "Type": "Supporting Root",
        "Components": {},
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.0.0"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.0.0": {
        "Name": "Atlas Documents Navigation Hub",
        "Version": 1,
        "Type": "Navigation Hub",
        "Components": {
            "Content": "The Atlas Documents Document contains all of the rules and specifications related to Atlas Documents. Further navigation: Definition and Properties of Atlas Documents Child Document contains core structural rules of Atlas Document contents and identifiers. Recursive Governance Improvement of Adaptive Documents Child Document is a stub that covers how Atlas Documents interact with NEWDAO Governance. Structure, categories and types of Atlas Documents Hub contains the rules and specifications for different types and categories of Atlas Documents."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {
            "Definition and Properties of Atlas Documents": "A.1.3.1",
            "Recursive Governance Improvement of Adaptive Documents": "A.1.3.2",
            "Structure, categories and types of Atlas Documents Hub": "A.1.3.3.0.0"
        },
        "linked_from": []
    },
    "A.1.3.1": {
        "Name": "Definition and Properties of Atlas Documents",
        "Version": 1,
        "Type": "Section",
        "Components": {
            "Content": "Atlas Documents are the basic building blocks for structuring data in the Atlas. They are organized as nested document trees, each with a unique Document Identifier. The first three layers contain the Immutable Documents, which together enshrine the Spirit of the Atlas and the core, permanent boundaries for how to operationalize it without risking slippery slope misalignment. In the layers below the Immutable Documents are the Adaptive Documents, which are continuously improved through the NEWDAO governnace process to interpret and practically operationalize the Spirit of the Atlas, within the boundaries of the Immutable Documents."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.1.1",
            "A.1.3.1.2"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.1.1": {
        "Name": "Document Identifiers",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "All Atlas Documents are distinguishable through their unique Document Identifier. The Document Identifier is the technical name of the Atlas Document, and it determines its position in the Document Tree of the Atlas. All Document Identifiers begin with a capital A, and the numbers and letters of the Document Identifiers are separated with dots, with each dot signifying that the Atlas Document is one layer deeper in the tree structure. The Document Identifiers help determine the position of each Atlas Document, and makes it easier to estimate the relationship between two different Atlas Documents."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.1.2": {
        "Name": "Atlas Document Properties",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "All Atlas Documents have 5 standard properties that provide key information about them. The subdocuments of A.1.3.2 specify the characteristics of each of the 5 standard properties.\nThe standard properties of Atlas Documents should be listed in the following order:\n1. Name\n2. Version\n3. Last Modified\n4. Type\n5. Components"
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.1.2.1",
            "A.1.3.1.2.2",
            "A.1.3.1.2.3",
            "A.1.3.1.2.4",
            "A.1.3.1.2.5"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.1.2.1": {
        "Name": "Name Property",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The Name property is used to provide each Atlas Document a human-readable name, to make it more easily distinguishable by humans, and to give a very rough overview of its purpose and function. The actual names of Atlas Documents for data-keeping purposes are their Document Identifiers, as a result it is possible to modify the name property with no consequences."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.1.2.2": {
        "Name": "Version Property",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The version property of Atlas Documents specifies how many times it has been modified. Every time an Atlas Document is modified, the newly modified Document gets its version number incremented, and the old version is recorded as a historical version with a Document Identifier equivalent to its version number. As an example, if an Atlas Document located 1.1.1 with version number 3 is modified, the new Atlas Document will have version number 4, and the old Atlas Document will be located at 1.1.1.v3. This means all historical versions of Atlas Documents are kept permanently as a part of the Atlas, to ensure the data isn't lost over time."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.1.2.3": {
        "Name": "Last Modified Property",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The 'Last Modified' property specifies the exact date and time when the Atlas Document was updated to its current version. It is recorded in the UTC timezone and follows the format 'YYYY-MM-DD-HH:MM:SS'. This property provides a timestamp for tracking modifications and ensuring transparency in the governance and update process. When an Atlas Document is at version 1, then Last Modified property denotes when the Atlas Document was created."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.1.2.4": {
        "Name": "Type Property",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The Type Property of Atlas Documents specifies the function, characteristic and purpose of the Atlas Document. The Type determines the data that must be contained in the Components Property. The various Document Types and their characteristics are specified in *A.1.3.3*."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.1.2.5": {
        "Name": "Components Property",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The Components Property of Atlas Documents contains an object that specifies the data components of the Atlas Document as nested properties. The Components of an Atlas Document is determined by its Type. Some Document Types have no Components, in which the object is just empty. An Atlas Document with Components must always have all of its components properly filled according to the requirements defined by its Type Specification. Some documents have custom logic for how their Components behave, and this custom logic is specified through a special reserved component property called 'custom'. Atlas Documents of Types with specified custom logic components can have variable number of components, and different characteristics of each component, for each instance of the Type. Custom components are always appended to the end of the list of components."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.2": {
        "Name": "Recursive governance improvement of Adaptive Documents",
        "Version": 1,
        "Type": "Section",
        "Components": {
            "Content": "Adaptive Documents are updated quarterly through the AVC process, based on Aligned Scope Proposals produced by AVCs. These updates must always be aligned with the principles and boundaries of the Immutable Documents, and must aim to objectively improve the quality of the Adaptive Documents over time to ensure the NEW Ecosystem always trends towards greater Universal Alignment, lower inner incentive requirements of its participants, greater efficiency, greater resilience and sustainable growth."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3": {
        "Name": "Structure, categories and types of Atlas Documents",
        "Version": 1,
        "Type": "Section",
        "Components": {
            "Content": "This Section must provide clear specifications of the basic structure of Atlas Documents, their general categories and individual types, their syntax and content requirements, and their functions and composability in the Atlas."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.3.1",
            "A.1.3.3.2"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.0": {
        "Name": "Supporting Root",
        "Version": 1,
        "Type": "Supporting Root",
        "Components": {},
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.3.0.0"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.0.0": {
        "Name": "Structure, categories and types of Atlas Documents Navigation Hub",
        "Version": 1,
        "Type": "Navigation Hub",
        "Components": {
            "Content": "The Structure, categories and types of Atlas Documents Document is the root of the document subtree that covers all rules about the unique characteristics and differentiating factors of Atlas Documents, in particular Document Types. Further navigation: Atlas Document Type Categories Child Document contains the overview of the high level classification of Atlas Documents Types. List of Document Types and their specifications Child Document contains all of the Document Types and their rules as Child Documents."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {
            "Atlas Document Type Categories": "A.1.3.3.1",
            "List of Document Types and their specifications": "A.1.3.3.2"
        },
        "linked_from": []
    },
    "A.1.3.3.1": {
        "Name": "Atlas Document Type Categories",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The Atlas Document Types can be broadly categorized into distinct groups that determine how they are modified and how they function in the Atlas. At the highest level there are the Immutable Documents and the Adaptive Documents. The Adaptive Documents are further subdivided into 3 distinct groups: Primary Documents, Supporting Documents, and Accessory Documents. The category of an Atlas Document can be inferred from its Document Identifier, as each group has unique and non-overlapping rules for validity of their Document Identifiers."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.3.1.1",
            "A.1.3.3.1.2",
            "A.1.3.3.1.3",
            "A.1.3.3.1.4"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.1.1": {
        "Name": "Immutable Document category",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "Immutable Documents are the most important part the Atlas, as they record the Spirit of the Atlas, detailing the vision, purpose and unalienable principles of NEWDAO. They are fully immutable and can never be changed once the Sagittarius Lockstake Engine has been deployed. Any attempt to change or circumvent the Spirit of the Atlas as specified in the Immutable Documents is severe misalignment. Immutable Documents have Document identifiers that are at most 3 layers deep in the Document Tree."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.1.2": {
        "Name": "Primary Document category",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "Primary Documents are the cornerstone of the Adaptive Documents and the practical operationalization and resilience of the Atlas. They detail specific, practical principles, rules, processes and roles necessary to operationalize the Spirit of the Atlas. Primary Documents are modified through AVC process only, and generally must be modified as slowly as possible, and as little as possible while remaining fully adapted to the external environment. Every modification of a Primary Document should aim to future-proof against the need for future modifications. The exception to this, is when Primary Documents are modified to adapt to changing external conditions, as it is important they stay up to date and are fully adapted in their ability to protect the Spirit of the Atlas against threats from a changing environment. Primary Documents have Document Identifiers that are 4 layers or deeper in the Document Tree, and cannot contain 0's."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.1.3": {
        "Name": "Supporting Document category",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "Supporting Documents are attached to Immutable Documents and Primary Documents (called their Target Document). They provide context and in some cases advanced functionality to the Target Documents, enabling them to be fully operationally effective and unambiguous. The different Types of Supporting Documents have different functions, and some of them are required for all Immutable Documents and Primary Documents, while others are only required for certain Primary Document Types. Some Supporting Documents can only be modified through the AVC process, while others have active data components that can be modified in real time by processes specified in the Atlas, either in the Target Document or elsewhere in the Atlas, depending on the Supporting Document. Supporting Documents always have Document Identifiers that contain at least one 0."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.1.4": {
        "Name": "Accessory Document category",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "Accessory Documents provide accessory data to every other Atlas Document type. There are two types of Accessory Documents; Translation Documents and Archive Documents. Translation Documents can be edited directly by FacilitatorDAOs, while Archive Documents are immutable. Accessory Documents always have Document Identifiers that contain letters in addition to the standard 'A' prefix of all Atlas Document Identifiers."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2": {
        "Name": "List of Document Types and their specifications",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The subdocuments of this Core Document are Type Specification Documents that contain specifications of each of the Atlas Document Types, specifying their standardized characteristics and requirements which must be followed by all Atlas Documents to be valid and aligned."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.3.2.1",
            "A.1.3.3.2.10",
            "A.1.3.3.2.11",
            "A.1.3.3.2.12",
            "A.1.3.3.2.13",
            "A.1.3.3.2.14",
            "A.1.3.3.2.15",
            "A.1.3.3.2.16",
            "A.1.3.3.2.17",
            "A.1.3.3.2.18",
            "A.1.3.3.2.19",
            "A.1.3.3.2.2",
            "A.1.3.3.2.20",
            "A.1.3.3.2.21",
            "A.1.3.3.2.22",
            "A.1.3.3.2.23",
            "A.1.3.3.2.24",
            "A.1.3.3.2.25",
            "A.1.3.3.2.3",
            "A.1.3.3.2.4",
            "A.1.3.3.2.5",
            "A.1.3.3.2.6",
            "A.1.3.3.2.7",
            "A.1.3.3.2.8",
            "A.1.3.3.2.9"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.1": {
        "Name": "The Type Specification Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Type Specification",
            "Type Overview": "The Type Specification Type is used for Type Specification Documents that specify the characteristics of each of the different Document Types. It ensures that all Type Specifications contain all necessary information to make it easy to reason about whether a document follows the requirements for its type.",
            "Type Components": {
                "Type Name": "The Type Name Component must contain the name of the Document Type",
                "Type Overview": "The Type Overview Component must contain high level information as human-readable text about the type, such as what it is used for and why it is necessary.",
                "Type Components": "If the Type has Components, they must be specified in this Component as a nested object.",
                "Type Category": "This Component must specify whether the Type is an Immutable Document, a Primary Document, a Supporting Document, or a Translation Document.",
                "Document Identifier Rules": "This Component must specify as human-readable text rules related to the Document Identifier for Atlas Documents of this Type, and their locations in the Document Trees.",
                "Type Authority": "This Component must specify, as a number from 0 to 1, the authority of Documents of this type, in order to assist in resolving contradictions between Documents of different types.",
                "Additional Logic": "This Component can contain additional logic that applies to all Documents of the Type."
            },
            "Type Category": "Primary Document",
            "Document Identifier Rules": "Type Specification Documents must follow the Document Identifier rules for Primary Documents and be grouped together in the Governance Scope Article relevant to Document creation and data integration.",
            "Type Authority": 0.91,
            "Additional Logic": "The rules specified in Type Specification Documents must be followed for all Atlas Documents"
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },

    "A.1.3.3.2.10": {
        "Name": "The Element Annotation Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Element Annotation",
            "Type Overview": "Element Annotation Documents provide further specification of the semantic meaning of vague or ambiguous terms in the Target Document. Element Annotation Documents can also briefly define technical jargon that is unique to the Target Document. Element Annotation Documents can be thought of as serving a function similar to that of a footnote: they can provide useful context or commentary. Element Annotations should be as concise as possible.",
            "Type Components": {
                "Element": "The Element Component should contain the unique word or phrase from the Target Document that is being annotated.",
                "Annotation": "The Annotation Component should concisely disambiguate and bound the semantic meaning of problematic terms in the Target Document. Such terms can be vague, ambiguous or technical jargon specific to the Target Document.",
                "Status": "The Status Component reflects whether the Element Annotation Document instance is \"Provisional\" or \"Approved\".\n An Element Annotation Document instance can be integrated into the Atlas on an experimental basis. The \"Provisional\" status enables ecosystem participants to interact with the Element Annotation Document instance in a practical context, resulting in valuable feedback or other data concerning the Document's appropriateness. FacilitatorDAOs are not bound to observe an Element Annotation Document instance whose status is \"Provisional\". They may choose to do so however, in which case the concrete utility of the Document instance for their decisionmaking becomes a valuable input.\n Alternatively, an Element Annotation Document instance can be integrated into the Atlas under \"Approved\" status. This status denotes a significantly higher level of confidence in the Document instance. However, a Document instance with \"Approved\" status remains modifiable pursuant to the customary governance protocol. FacilitatorDAOs are required to factor into their decisionmaking any relevant Element Annotation Document instance with \"Approved\" status.\n The purpose of the Status Component is to operationalize continuous research on Universal Alignment and enable recursive improvement of Atlas infrastructure.\n Atlas Axis, an authorized Ecosystem Actor, is responsible for assigning this Status where it is a required component of Atlas documents.",
                "Needed Research": "An array that contains descriptions of potential problems or concerns associated with an Element Annotation Document instance. Through the standardized Atlas data integration protocol, entries in this Component are selectively sourced from inputs from Facilitators, Atlas workstream contributors or other ecosystem participants. \"Needed Research\" entries are progressively processed and integrated as appropriate.\n The \"Needed Research\" Component is only present in the Core Type document and specific Supporting Document types. These document types have the objective of extrapolating from the abstract logic of their Parent documents to formulate rules and processes that are more concrete and actionable. Therefore, inputs for \"Needed Research\" are more appropriately sourced at this level in the document tree. The \"Needed Research\" Component is not included in the Article or Section Document types, whose language tends to be broad in nature." 
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Element Annotation Documents must always be located as subdocuments to the Element Annotation Directory Document of their Target Document.",
            "Type Authority": 0.4,
            "Additional Logic": "Element Annotation Documents should be updated as necessary to reflect changes in the understanding or interpretation of the Element and/or any related Atlas document, while maintaining consistency with the Target Document. The Element Annotation should not contradict its Target Document or other context data of the Target Document.\n The \"Name\" property of each Element Annotation Document instance must follow a standardized template: the annotated Element is listed first, followed by a hyphen, and the phrase \"Element Annotation.\""
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },   
    
    "A.1.3.3.2.11": {
        "Name": "The FacilitatorDAO Action Tenet Directory Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "FacilitatorDAO Action Tenet Directory",
            "Type Overview": "The FacilitatorDAO Action Tenet Directory Type is a directory Type used to list all of the FacilitatorDAO Action Tenet Documents that pertain to a Target Document. FacilitatorDAO Action Tenet Documents specify adjudication principles and guidelines that are directly derived from the Target Document. When a controversy concerns the Target Document, the FacilitatorDAOs must consult and apply the pertinent Action Tenet(s) in their decisionmaking.",
            "Type Components": {
                "Directory index": "This Component should contain a list of the FacilitatorDAO Action Tenets contained within, with keys being the document identifiers and values being their document names."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "FacilitatorDAO Action Tenet Directory Documents must always be located at the .0.4 position of their Target Document.",
            "Type Authority": "N/A",
            "Additional Logic": "N/A"
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    
    "A.1.3.3.2.12": {
        "Name": "The FacilitatorDAO Action Tenet Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "FacilitatorDAO Action Tenet",
            "Type Overview": "The FacilitatorDAO Action Tenet Type is used to provide concrete adjudication principles derived from its Target Document. It distills the governance logic of the Target Document into a concise principle to guide FacilitatorDAOs in resolving disputes related to the Target Document. The practical application of the Tenet is demonstrated by its \"Scenario\" Subdocuments.",
            "Type Components": {
                "Tenet": "The Tenet Component specifies the adjudication logic, principle or doctrine that is directly derived from the Target Document. This Component can include policy statements underpinning the adjudication principle. Such policy statements can highlight the values that are served by, or the benefits gained from, adhering to the Tenet. When facing edge cases, these policy statements can help FacilitatorDAOs to extrapolate from the Tenet's logic to achieve the most suitable outcome.",
                "Status": "The Status Component reflects whether the FacilitatorDAO Action Tenet (“Action Tenet”) Document instance is \"Provisional\" or \"Approved\".\n An Action Tenet Document instance can be integrated into the Atlas on an experimental basis. The \"Provisional\" status enables ecosystem participants to interact with the Action Tenet Document instance in a practical context, resulting in valuable feedback or other data concerning the Document's appropriateness. FacilitatorDAOs are not bound to observe an Action Tenet Document instance whose status is \"Provisional\". They may choose to do so however, in which case they should specify the concrete reasons and utility of the Document instance for their decisionmaking. This input becomes a valuable contribution to ongoing Atlas research.\n Alternatively, an Action Tenet Document instance can be integrated into the Atlas under \"Approved\" status. This status denotes a significantly higher level of confidence in the Document instance. However, a Document instance with \"Approved\" status remains modifiable pursuant to the customary governance or Atlas workstream protocol. In contrast to Document instances with \"Provisional\" status, FacilitatorDAOs are required to factor into their decisionmaking any relevant Action Tenet Document instance with \"Approved\" status.\n The purpose of the Status Component is to operationalize continuous research on Universal Alignment and enable recursive improvement of Atlas infrastructure.\n Atlas Axis, an authorized Ecosystem Actor, is responsible for assigning this Status where it is a required component of Atlas documents.",
                "Needed Research": "An array that contains descriptions of problems or concerns associated with the Action Tenet and its Target Document. Such problems can include potential gaps or conflicts in the logic of the Action Tenet and/or its Target Document, relative to their related Atlas Documents; questions regarding the operation of the Target Document to which there are currently no answers; and other risks.\n Through the standardized Atlas data integration protocol, entries in this Component are selectively sourced from inputs from Facilitators, Atlas workstream contributors or other ecosystem participants and are gradually processed upward to its Article Function Supporting Document. Further processing can lead to modifications to the organization of the Article and its child Sections; or modifications of the content of the Article and its child Sections, and/or other related Atlas documents.\n The \"Needed Research\" Component is only present in the Core Type document and specific Supporting Document types. These document types have the objective of extrapolating from the abstract logic of their Parent documents to formulate rules and processes that are more concrete and actionable. Therefore, inputs for \"Needed Research\" are more appropriately sourced at this level in the document tree. The \"Needed Research\" Component is not included in the Article or Section Document types, whose language tends to be broad in nature."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "FacilitatorDAO Action Tenet Documents must always be located as subdocuments of the FacilitatorDAO Action Tenet Directory Document (located at position .0.4) of their Target Document.",
            "Type Authority": 0.5,
            "Additional Logic": "FacilitatorDAO Action Tenet Documents are likely to be necessary supplements for interpreting the Immutable Document types, as these tend to have generalized, broad language. The Core Document type has the function of operationalizing the Immutable Documents, and thus its language will tend to be far more specific and concrete. For that reason, Action Tenet Supporting Documents may not be necessary for a particular Core Document. This is not a hard-coded rule, however. The determination of whether an Action Tenet Document is needed for any given Atlas document should always be tailor-made.\n Action Tenet Documents should be created and updated as necessary to reflect changes in governance practices, provide clarity on decision-making processes, and enhance understanding of governance principles and rules. The examples should not contradict their Target Document or other Supporting Documents of the Target Document.\n The \"Name\" property of each FacilitatorDAO Action Tenet Document instance must follow a standardized template. If the Action Tenet can be anchored to a specific term from the Target Document, that term is listed first; followed by a hyphen; and then, an abstract of the Action Tenet logic, e.g., \"Organizational Drift - ACs' Mandate When Instigating Action Can Be Traced Back to a Discrete Entity\". If the Action Tenet cannot be anchored to a specific term from the Target Document, the \"Name\" property should simply summarize the Action Tenet logic, e.g., \"Evaluating AC breach of role-specific requirement vs. general requirement\"."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },

    "A.1.3.3.2.13": {
        "Name": "The FacilitatorDAO Action Precedent Directory Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "FacilitatorDAO Action Precedent Directory",
            "Type Overview": "FacilitatorDAO Action Precedent Directory Documents list all of the FacilitatorDAO Action Precedent Documents that pertain to a Target Document. FacilitatorDAO Action Precedent Documents record data about FacilitatorDAO Actions, including ongoing actions, that are primarily based on interpretation of content of the Target Document.",
            "Type Components": {
                "Directory index": "This Component should contain a list of the FacilitatorDAO Action Precedents contained within, with keys being the document identifiers and values being their document names."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "FacilitatorDAO Action Precedent Directory Documents must always be located at the .0.5 position below their Target Document.",
            "Type Authority": "N/A",
            "Additional Logic": "A FacilitatorDAO Action Precedent Directory Document must be updated whenever a new FacilitatorDAO Action Precedent Document is added that meaningfully changes what should be contained in the Directory overview Component."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.14": {
        "Name": "The FacilitatorDAO Action Precedent Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "FacilitatorDAO Action Precedent",
            "Type Overview": "The FacilitatorDAO Action Precedent Type is used to record all the relevant data related to a FacilitatorDAO Action, to serve as precedent for future FacilitatorDAO Actions and decision-making processes. It is also used for ongoing FacilitatorDAO Actions, and the creation of a FacilitatorDAO Action Precedent is the formal method that FacilitatorDAOs use to take action against misalignment, or explicitly approve ecosystem activity.",
            "Type Components": {
                "Input": "The Input Component must contain a description of the situation or context in which the FacilitatorDAO Action takes place. This could include any relevant information, such as the state of governance or the specific issue at hand.",
                "Output": "The Output Component must contain a description of the FacilitatorDAO's action and the outcome or decision that resulted from it. This should provide a clear illustration of how the FacilitatorDAO responded to the situation.",
                "Label": "The Label Component indicates whether the FacilitatorDAO's action is considered aligned or misaligned according to the principles and rules of governance. This judgment is intended to guide future actions and decisions. If the label is misaligned, it must also specify the penalty that is applied to the FacilitatorDAO for misalignment. The Label must always be marked as Aligned when it is created by the FacilitatorDAO, and further action by NEWDAO Governance can directly modify this later according to the specifications of the Atlas Documents relevant to appealing Facilitator Actions."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "FacilitatorDAO Action Precedent Documents must always be located as subdocuments of the FacilitatorDAO Action Precedent Directory Document of their Target Document.",
            "Type Authority": 0.5,
            "Additional Logic": "FacilitatorDAO Action Precedent Documents should be created and updated as necessary to reflect changes in governance practices, provide clarity on decision-making processes, and enhance understanding of governance principles and rules. The Precedents should not contradict their Target Document or other Supporting Documents of the Target Document."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.15": {
        "Name": "The Active Data Controller Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Active Data Controller",
            "Type Overview": "Active Data Controller Documents are Primary Documents that can have Active Data Documents attached to them as Supporting Documents, and contain variable state that can be directly modified by Facilitators and other processes external to the standard AVC process. Active Data can be lists of authorized actors, parameters, or externally collected data being prepared for data integration with the Atlas.",
            "Type Components": {
                "Content": "The Content Component of Active Data Controller Documents is used to describe flexible rules of how the Active Data Documents must behave, and how they can be modified. The Custom Components format and requirements of the Active Data Documents must be defined as well."
            },
            "Type Category": "Primary",
            "Document Identifier Rules": "Active Data Controller Documents follow the Document Identifier Rules of Primary Documents.",
            "Type Authority": 0.89,
            "Additional Logic": "Active Data Controller Documents must have an Active Data Directory Document located below it at the .0.5 position. The Active Data Controller Document can reference its Active Data subdocuments for its own logic. This allows Active Data Documents to be self-improving and adaptive at high speeds."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.16": {
        "Name": "The Active Data Directory Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Active Data Directory",
            "Type Overview": "The Active Data Directory Type is a directory Type used to list all of the Active Data Documents that pertain to an Active Data Controller Document. Active Data Documents contain variable state that can be directly modified by Facilitators and other processes external to the standard AVC process.",
            "Type Components": {
                "Directory overview": "This Component should contain a brief explanation of overall patterns and themes of the Active Data Documents contained within."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Active Data Directory Documents must always be located at the .0.5 position of their Active Data Controller Document or Budget Controller Document.",
            "Type Authority": "N/A",
            "Additional Logic": "An Active Data Directory Document should be updated whenever a new Active Data Document is added that meaningfully changes what should be contained in the Directory overview Component."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.17": {
        "Name": "Test Document",
        "Version": null,
        "Type": null,
        "Components": {},
        "Last_Modified": "2023-09-23",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.18": {
        "Name": "The Active Data Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Active Data",
            "Type Overview": "The Active Data Type is used for Supporting Documents that contain variable state that can be directly modified by Facilitators and other processes external to the standard AVC process. Active Data can be lists of authorized actors, parameters, or externally collected data being prepared for data integration with the Atlas.",
            "Type Components": {
                "Custom Components": "The Custom Components of Active Data Documents are defined by the Active Data Controller Document. They contain the variable state that can be directly modified."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Active Data Documents must always be located as subdocuments of the Active Data Directory Document of their Active Data Controller Document.",
            "Type Authority": 0.1,
            "Additional Logic": "Active Data Documents can contain arbitrary types of data, and can contain large amounts of data or code. The function and purpose of the contained data depends on the logic specified in the Active Data Controller Document. Active Data Documents can be modified directly through processes external to the Standard AVC process."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.19": {
        "Name": "The Budget Controller Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Budget Controller",
            "Type Overview": "The Budget Controller Type is used to manage the budgets used by NEWDAO to operationalize the Scopes to achieve the purpose and goals of the Spirit of the Atlas. It controls variable state that specifically authorizes executive votes to disburse payments from the NEWDAO Surplus Buffer, or authorize smart contracts to disbuse such payments. The Budget Controller Document determines the rules and processes for modifying and using the budgets contained in the Budget Documents that are attached to it. Budget Controllers also have Active Data Documents attached that are used to report on the status and results of projects funded through the Budget Documents.",
            "Type Components": {
                "Content": "The Content Component of Budget Controller Documents is used to describe flexible rules of how the Active Data Documents and Budget Documents must behave, and how they can be modified. The Custom Components format and requirements of the Active Data Documents and the Budget Documents must be defined as well."
            },
            "Type Category": "Primary",
            "Document Identifier Rules": "Budget Controller Documents follow the Document Identifier Rules of Primary Documents.",
            "Type Authority": 0.89,
            "Additional Logic": "Budget Controller Documents must have an Active Data Directory Document located below it at the .0.5 position, and a Budget Directory Document located below it at the .0.6 position."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.2": {
        "Name": "The Atlas Preamble Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Atlas Preamble",
            "Type Overview": "The Atlas Preamble Type is used for the Atlas Preamble Document Tree which starts at the 0th position of the first layer of the Atlas. The Atlas Preamble details the Spirit of the Atlas in human-readable language, and specifies important definitions for understanding the Spirit of the Atlas, that must be used as context when interpreting all other parts of the Atlas.",
            "Type Components": {
                "Content": "The content Component is very flexible and defines in broad human-readable language the Spirit of the Atlas."
            },
            "Type Category": "Immutable",
            "Document Identifier Rules": "Atlas Preamble Documents are located at A.0 or as nested Documents one layer below A.0.",
            "Type Authority": 1,
            "Additional Logic": "Atlas Preamble Documents are immutable, foundational parts of the Atlas and their content must be considered when interpreting all other Atlas Documents."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.20": {
        "Name": "The Budget Directory Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Budget Directory",
            "Type Overview": "The Budget Directory Type is a directory Type used to list all of the Budget Documents that pertain to a Budget Controller Document.",
            "Type Components": {
                "Directory overview": "This Component should contain a brief explanation of overall patterns and themes of the Budget Documents contained within."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Budget Directory Documents must always be located at the .0.6 position of their Budget Controller Document.",
            "Type Authority": "N/A",
            "Additional Logic": "A Budget Directory Document should be updated whenever a new Budget Document is added that meaningfully changes what should be contained in the Directory overview Component."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.21": {
        "Name": "The Budget Document Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Budget",
            "Type Overview": "Budget Documents contain state that can authorize executive votes to disburse payments from the NEWDAO Surplus Buffer, or authorize smart contracts to disburse such payments.",
            "Type Components": {
                "Custom Components": "The Custom Components of Budget Documents are defined by the Budget Controller Document. They contain the variable state that can be directly modified."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Budget Documents must always be located as subdocuments of the Budget Directory Document of their Budget Controller Document.",
            "Type Authority": 0.2,
            "Additional Logic": "Budget Documents specify a budget rate expressed as NEW per unit of time. Additionally, they can contain large amounts of data, or code, and their function and purpose depends on their Budget Controller Document. Budget Documents can be modified directly through processes external to the Standard AVC process as specified by their Budget Controller Document."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.22": {
        "Name": "The Definition Directory Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Definition Directory",
            "Type Overview": "The Definition Directory Type is used for Target Documents with many complex subdocuments, and acts as a directory for definitions of unique terms that are only referenced in its subdocuments.",
            "Type Components": {},
            "Type Category": "Supporting",
            "Document Identifier Rules": "Definition Directory Documents must always be located at the .0.0 position of their Target Document.",
            "Type Authority": "N/A",
            "Additional Logic": "Definition Directory Documents only need to be present in Atlas Documents that require definitions for unique terms in their Subdocuments."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.23": {
        "Name": "The Definition Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Definition",
            "Type Overview": "The Definition Type is used for documents that define unique concepts contained in Subdocuments to the Target Document of the Definition Document",
            "Type Components": {
                "Term": "The Term Component contains the name of the term that is being defined.",
                "Definition": "The Definition Component contains the detailed definition of the term."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Definition Documents must always be located as subdocuments of the Definition Directory Document of their Target Document.",
            "Type Authority": 0.1,
            "Additional Logic": "To the extent possible it should be avoided to have the same term defined multiple times in the Atlas, and instead always put a single defininition at a location in the Atlas that covers all of its use. The main exception to this principle should be when relatively niche terms are present in two different Scopes."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.24": {
        "Name": "The Translation Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Translation",
            "Type Overview": "The Translation Type is used for creating translated versions of Atlas Documents to make the Atlas accessible to non-English speakers. Translation Documents are Accessory Documents and they do not have any impact on the governance or operation of NEWDAO, but they are important for accessibility and inclusivity.",
            "Type Components": {
                "Original Document Type": "The Type of the original document that is being translated must be specified in this component.",
                "Language": "The Language Component specifies the language in which the Atlas Document is translated.",
                "Translated Name": "The Translated Name component contains the name of the translated Atlas Document in the new language.",
                "Custom": "Translation Documents contain Custom Components that mirror the components of the original Document with component name and component data translated to the new language."
            },
            "Type Category": "Accessory",
            "Document Identifier Rules": "Translation Documents are located as subdocuments to the Atlas Document they are translating. Their Document Identifier is the same as the Atlas Document they are translating, with an additional suffix that represents the language of the translation. For example, a Spanish translation of A.1 would have the Document Identifier A.1.es.",
            "Type Authority": "N/A",
            "Additional Logic": "Translation Documents should be updated whenever the Atlas Document they are translating is updated to ensure that the translation remains accurate. However, in case of any discrepancies or contradictions, the original English version of the Atlas Document always takes precedence."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.25": {
        "Name": "The Archive Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Archive",
            "Type Overview": "The Archive Type is used for storing historical versions of Atlas Documents. Archive Documents are Accessory Documents and they do not have any impact on the governance or operation of NEWDAO, but they are important for maintaining a record of changes and evolution of the Atlas over time.",
            "Type Components": {
                "Original Document Type": "The Type of the original document that is being archived must be specified in this component.",
                "Custom": "Archive Documents contain Custom Components that mirror the components of the original Document at the time of the version being archived."
            },
            "Type Category": "Accessory",
            "Document Identifier Rules": "Archive Documents are located as subdocuments to the Atlas Document they are archiving. Their Document Identifier is the same as the Atlas Document they are archiving, with an additional suffix 'v' followed by the version number of the document being archived. For example, the third version of A.1 would have the Document Identifier A.1.v3.",
            "Type Authority": "N/A",
            "Additional Logic": "Archive Documents should be created whenever an Atlas Document is updated to ensure that a record of all previous versions is maintained. They are not meant to be modified or deleted once created."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.26": {
        "Name": "The Navigation Hub Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Navigation Hub",
            "Type Overview": "The Navigation Hub Type is used for Navigation Hubs that provide summarized content and links to child documents or Focus Hubs that dive deeper or provide supporting data for a specific action. It acts as an entry point and guide for navigating the content of an Immutable or Primary Document.",
            "Type Components": {
                "Content": "The Content Component must contain summarized information and links to the child documents of the associated Immutable or Primary Document. It must also link to the nearest navigation hubs below its position if its Child Documents do not have Navigation Hubs. "
            },
            "Type Category": "Supporting Document",
            "Document Identifier Rules": "Navigation Hub Documents must be located at the .0.0 position of an Immutable or Primary Document.",
            "Type Authority": 0.89,
            "Additional Logic": "Navigation Hubs serve as a guide for users to understand and navigate the main content of the associated Immutable or Primary Document."
        },
        "Last_Modified": "2023-10-06",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.27": {
        "Name": "The Focus Hub Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Focus Hub",
            "Type Overview": "The Focus Hub Type is used for Focus Hubs that delve deeper into specific topics or sections from the Navigation Hub. It can be used to slice up a lot of child documents or a lot of hubs into independent groups, so only the relevant group needs to be read. It can also be used to provide relevant data for a specific type of action or workflow related to the Focus Hubs Immutable or Primary Document or its subtree.",
            "Type Components": {
                "Content": "The Content Component must contain detailed information about the specific topic or section from the Navigation Hub.",
                "links_to": "This Component can provide links to related documents or sections, with keys being the document names and values being their respective identifiers."
            },
            "Type Category": "Supporting Document",
            "Document Identifier Rules": "Focus Hub Documents must be located at the nonzero numerical positions below Navigation Hubs, e.g., x.0.0.1, x.0.0.2, etc.",
            "Type Authority": 0.88,
            "Additional Logic": "Focus Hubs serve as a detailed guide on specific topics, giving users an in-depth understanding of the subject matter."
        },
        "Last_Modified": "2023-10-06",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.28": {
        "Name": "Article Function Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Article Function",
            "Type Overview": "The Article Function Type describes the purpose of the Article in terms of what it should achieve to serve Universal Alignment. Because our knowledge of Universal Alignment and the Spirit of the Atlas is continually changing, Article Function's role is to operationalize continual research in this domain.\n Prior to Endgame, the Article Function type serves as a focus point for aggregating the ecosystem's evolutionary learning with regard to potential improvements to the Immutable Documents and the Atlas as a whole. Once Endgame state is reached and the Immutable Documents are locked down, Article Function type will continue to assist in the incremental enhancement of the Atlas' Adaptive Documents.\n Article Function documents will be slowly developed over time, in parallel with the advancing development of its associated Sections and Adaptive Documents.",
            "Type Components": {
                "Function": "Specifies the problem(s) that the Article is intended to address, including the nature and impact of the problem(s) on NEWDAO ecosystem. Specifies the purpose of the Article: how its function is situated holistically within the solution to the problem, and what the Article should achieve to serve the Spirit of the Atlas, according to the current state of knowledge regarding Universal Alignment.",
                "Modules": { 
                    "Introduction to Module Component": "The \"Modules\" Component is an object that contains as many key-value pairs as there are Modules constituting the Article. Modules are structural devices that group related atomic Sections together. Each numbered Module has a nested object as its value, which object specifies data including 'Title,' 'Summary,' 'Co-Sections,' 'Section Contingencies', and 'Article/Module Contingencies'. This value must always be populated. Further specifications of these data fields follow.",
                    "Title": "The \"Title\" field succinctly abstracts the Module contents or logic. The Module Title is always prefixed with the Module's 'class.' Classes are categories of Modules whose names correlate to the broad purpose of the Module. Classes may include 'Powers and Constraints,' 'Resources', and 'Mandate', etc.\n The Title - and its Module Class prefix - ensure that a Module's constituent atomic Sections can be quickly identified as serving a unified purpose within the Article structure as a whole. This value must always be populated.",
                    "Summary": "Summarizes the purpose of the Module in the scheme of the Article as a whole. This value must always be populated.",
                    "Co-Sections": "An array that lists all constituent Sections of a Module. This value must always be populated.",
                    "Section Contingencies": "Optional value. Lists problems or concerns associated with a particular Section of the pertinent Module. Such problems can include gaps in logic of the Section; conflicts between a Section and other Atlas Documents; questions regarding the operation of the Section to which there are currently no answers; and other risks. Contains a field for 'Forecasted Modifications', which specifies changes to the Section that are likely to be needed to resolve the issues. Through the standardized Atlas data integration protocol, entries in this Component are sourced from the \"Needed Research\" inputs found in certain Document types.",
                    "Article/Module Contingencies": "Optional value. Lists problems or concerns associated with the Module's constituent Sections that cannot be isolated to a single Section. Contains a field for \"Forecasted Modifications\", which specifies changes to the general Article or Module logic that are likely to be needed to resolve the issues. Through the standardized Atlas data integration protocol, entries in this Component are sourced from the \"Needed Research\" inputs found in certain Document types.",
                "Custom": ""
    
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Article Function Documents must always be located at the 0.2 position of their Target Document.",
            "Type Authority": "N/A",
            "Additional Logic": "The Article Function Type is a Supporting Document unique to only the Article Document Type. It is continually modified outside of the customary AVC process.\n Prior to Endgame, any modifications to its parent Article or child Sections must be grounded in existing inputs in the Article Function, which inputs have gone through progressive stages of processing. This ensures that Immutable Document modifications can never be attempted without first being validated through progressive stages of methodical, holistic analysis."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    }
},

"A.1.3.3.2.29": {
    "Name": "The FacilitatorDAO Scenario Directory Type",
    "Version": 1,
    "Type": "Type Specification",
    "Components": {
        "Type Name": "FacilitatorDAO Scenario Directory",
        "Type Overview": "The FacilitatorDAO Scenario Directory Type is a directory used to list all of the Scenarios that pertain to a FacilitatorDAO Action Tenet. Scenarios are hypothetical fact patterns that are designed to illustrate the practical application of a single FacilitatorDAO Action Tenet, i.e., its parent FacilitatorDAO Action Tenet Document. Scenarios are classified as either Aligned or Misaligned. Aligned Scenarios conform to the logic of the Target Document. Misaligned Scenarios have breached the Target Document logic and are thus in violation of the Atlas.",
        "Type Components": {
            "Directory index": "This Component should contain a list of the FacilitatorDAO Scenarios contained within, with keys being the document identifiers and values being their document names."
        },
        "Type Category": "Supporting Document",
        "Document Identifier Rules": "FaciltatorDAO Scenario Directory Documents must always be located at the .0.1 position below their parent FacilitatorDAO Action Tenet Document, e.g., A.1.m1-1.0.4.1.1.",
        "Type Authority": 0.88,
        "Additional Logic": ""
    },
    "Last_Modified": "2023-10-06",
    "Child_Documents": [],
    "links_to": {},
    "linked_from": []

},

    "A.1.3.3.2.3": {
        "Name": "The Scope Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Scope",
            "Type Overview": "The Scope Type is used for the 5 nonzero Immutable Documents of the first layer of the Atlas that directly describe focus areas, principles, rules and processes of NEWDAO Governance. Scope Documents define the broad boundaries, requirements and objectives of each of the 5 Atlas Scopes, so that they together can fully cover all activities that are needed for NEWDAO to function while maintaining its resilient equilibrium.",
            "Type Components": {
                "Content": "The content Component is very flexible and defines in broad human-readable language core principles, rules and processes."
            },
            "Type Category": "Immutable",
            "Document Identifier Rules": "Scope Documents have the Document Identifiers from A.1 to A.5.",
            "Type Authority": 0.99,
            "Additional Logic": "Scope Documents are immutable, foundational parts of the Atlas and their content must be considered when interpreting all principles, rules and processes of Atlas Documents nested below them"
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },

    "A.1.3.3.2.30": {
        "Name": "The FacilitatorDAO Scenario Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "FacilitatorDAO Scenario",
            "Type Overview": "FacilitatorDAO Scenario Documents contain hypothetical fact patterns that are designed to illustrate the practical application of a single FacilitatorDAO Action Tenet, i.e., its parent FacilitatorDAO Action Tenet Document. Scenarios are classified as either Aligned or Misaligned. Aligned Scenarios conform to the logic of the Target Document. Misaligned Scenarios have breached the Target Document logic and are thus in violation of the Atlas.",
            "Type Components": {
                "Description": "This Component contains the hypothetical fact pattern that illustrates the application of its parent FacilitatorDAO Action Tenet. The fact pattern should be as concrete in its details as possible, so as to be helpful to the FacilitatorDAOs' decisionmaking.",
                "Finding": "This Component indicates whether, in this Scenario, the Target Document logic was or was not breached. If the Target Document was not breached, the Finding is \"Aligned\". If the Target Document was breached, the Finding is \"Misaligned\".",
                "Additional Guidance": "This Component provides additional context on the specific aspects of the Scenario that were salient to the Aligned or Misaligned finding. It can also provide guidance in terms of how the FacilitatorDAOs should respond to such a Scenario, i.e., follow-up actions or means of investigation.",
                "Needed Research": "An array that contains descriptions of potential problems or concerns associated with a FacilitatorDAO Scenario instance. Through the standardized Atlas data integration protocol, entries in this Component are selectively sourced from inputs from Facilitators, Atlas workstream contributors or other ecosystem participants. \"Needed Research\" entries are progressively processed and integrated as appropriate.\n The \"Needed Research\" Component is only present in the Core Type document and specific Supporting Document types. These document types have the objective of extrapolating from the abstract logic of their Parent documents to formulate rules and processes that are more concrete and actionable. Therefore, inputs for \"Needed Research\" are more appropriately sourced at this level in the document tree. The \"Needed Research\" Component is not included in the Article or Section Document types, whose language tends to be broad in nature.",
                "Variations": "The \"Variations\" Component is an object that contains as many key-value pairs as there are Variations of the Scenario. Each Variation substitutes elements of the original Scenario to demonstrate whether and why the finding of Aligned/Misaligned would change. Each numbered Variation has a nested object as its value, which object specifies data including 'Description,' 'Finding,''Additional Guidance,' and 'Needed Research'. The function of these latter Components mirrors those of the Scenario Document type listed above."

            },
            "Type Category": "Supporting Document",
            "Document Identifier Rules": "FaciltatorDAO Scenario Documents must always be located as subdocuments of the FacilitatorDAO Scenario Directory Document, which in turn is nested under its FacilitatorDAO Action Tenet Document.",
            "Type Authority": 0.88,
            "Additional Logic": ""
        },
        "Last_Modified": "2023-10-06",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },

    "A.1.3.3.2.4": {
        "Name": "The Article Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Article",
            "Type Overview": "The Article Type is used for the second layer documents nested below the 5 Scope documents of the Atlas. They directly describe individual focus areas that together fully cover everything needed for the purpose of the Scope to be fulfilled.",
            "Type Components": {
                "Content": "The content Component is very flexible and defines in broad human-readable language core principles, rules and processes of the specific focus area of the Scope that the Article covers, and provides the starting point, requirements, boundaries, and in some cases immutable specifications, needed to develop the Adaptive Documents that are nested at lower layers of the Document Trees to maximally fulfill their practical purpose without violating the Spirit of the Atlas."
            },
            "Type Category": "Immutable",
            "Document Identifier Rules": "Article Documents have Document Identifiers one layer below the Scope Documents.",
            "Type Authority": 0.98,
            "Additional Logic": "Article Documents are immutable, foundational parts of the Atlas and their content must be considered when interpreting all principles, rules and processes of Atlas Documents nested below them"
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.5": {
        "Name": "The Section Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Section",
            "Type Overview": "The Section Type is used for the third layer of Immutable Documents nested under the Articles of each Scope in the Atlas. They provide additional structure and specification to the principles, rules and processes within the focus area of the Article, and act as a foundation and boundary against misalignment of the Adaptive Documents that are nested below it. Generally, Section Documents should be restricted to specifying only a single unit of logic.",
            "Type Components": {
                "Content": "The content Component is very flexible and provides in-depth human-readable language to elaborate on the specific principles, rules, and processes of the Article that the Section is nested under.",
                "Needed Research": ""
            },
            "Type Category": "Immutable",
            "Document Identifier Rules": "Section Documents have Document Identifiers one layer below the Article Documents. Section Document Identifiers have two components. The first is a prefix and number that indicates the Section's associated Module (i.e.,A.1.m1-3). The second component is the Section number itself.",
            "Type Authority": 0.97,
            "Additional Logic": "Section Documents are immutable parts of the Atlas and their content must be considered when interpreting all principles, rules and processes of Adaptive Documents nested below them.\n Modules are not an Atlas Document type; they are a structural device integrated into the Section Document type Document Identifier scheme."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.6": {
        "Name": "The Core Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Core",
            "Type Overview": "The Core Type is the basic building block of the Primary Documents. Core Documents flexibly specify the core principles, rules and processes required to fulfil the specifications made by the Immutable Documents with a focus on clarity, practicality and applicability.",
            "Type Components": {
                "Content": "The content Component is very flexible and defines in human-readable language core principles, rules or processes, or subcomponents thereof.",
                "Needed Research": "An array that contains descriptions of potential problems or concerns associated with the Core Document instance. Through the standardized Atlas data integration protocol, entries in this Component are selectively sourced from inputs from Facilitators, Atlas workstream contributors or other ecosystem participants. \"Needed Research\" entries are progressively processed and integrated as appropriate.\n The \"Needed Research\" Component is only present in the Core Type document and specific Supporting Document types. These Document types have the objective of extrapolating from the abstract logic of their Parent documents to formulate rules and processes that are more concrete and actionable. Therefore, inputs for \"Needed Research\" are more appropriately sourced at this level in the Atlas Document tree. The \"Needed Research\" Component is not included in the Article or Section Document types, whose language tends to be broad in nature."
            },
            "Type Category": "Primary",
            "Document Identifier Rules": "Core Documents follow the Document Identifier Rules of Primary Documents, and can have whatever Document Identifier within those constraints that are useful for their purpose.",
            "Type Authority": 0.9,
            "Additional Logic": "To support the Resilient Equilibrium of NEWDAO Governance, Core Documents are meant to be as future-proofed as possible. A key principle is that when an Aligned Scope Proposal edits a Core Document, it must justify why the edit will reduce the need for future edits, and takes the Core Document closer to an effectively near-immutable end state where it is strong enough that it naturally covers all probable external events."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.7": {
        "Name": "The Supporting Root Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Supporting Root",
            "Type Overview": "The Supporting Root Type is used to mark the beginning of the Supporting Document subtree of an Immutable or Primary Document. All Immutable and Primary Documents must have a Supporting Root.",
            "Type Components": {},
            "Type Category": "Supporting",
            "Document Identifier Rules": "Supporting Root Documents must always be located at the .0 position of its Target Document.",
            "Type Authority": "N/A",
            "Additional Logic": "The Supporting Root Documents have no function other than structurally acting as a directory for nested Supporting Documents in a standardized format. All Immutable Documents and Primary Documents must have a Supporting Root Document attached."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.8": {
        "Name": "The Original Context Data Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Original Context Data",
            "Type Overview": "Original Context Data Documents explain the intention and reasoning behind the content of its Target Document, to make interpretation and extrapolation of its contents easier, and provide additional information to other forms of analysis. Original Context Data helps anchor the fundamental purpose and meaning of the target document to its original context, and should help mitigate cultural drift over time. Original Context Data can contain unstructured data used for genesis data integration of early Atlas Documents. Original Context Data Documents can form nested subtrees to organize their data if relevant.",
            "Type Components": {
                "Content": "The Content Component should contain all relevant information to understand the intention and reasoning behind the wording and elements of the main Document."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Original Context Data Documents must always be located at the .0.1 position of their Target Document, or nested in a subtree of Original Context Data Documents below the .0.1 position.",
            "Type Authority": 0.3,
            "Additional Logic": "The Original Context Data Document should be in a finished form alongside the creation or modification of its Target Document, as it aims to capture the original context and intention of the contents of the Target Document. However, it can and should be modified if new evidence and data comes to light that helps to better describe the original context and intention of the Target Document, or if new perspectives or new external events makes it possible and useful to modify the Original Context Data Document in a way that doesn\\u2019t contradict its earlier language."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.3.2.9": {
        "Name": "The Element Annotation Directory Type",
        "Version": 1,
        "Type": "Type Specification",
        "Components": {
            "Type Name": "Element Annotation Directory",
            "Type Overview": "The Element Annotation Directory Type is a directory used to list all of the Element Annotation Documents pertaining to a Target Document.",
            "Type Components": {
                "Directory index": "This Component should contain a list of the Element Annotation Documents contained within, with keys being the document identifiers and values being their document names."
            },
            "Type Category": "Supporting",
            "Document Identifier Rules": "Element Annotation Directory Documents must always be located at the .0.3 position of their Target Document.",
            "Type Authority": "N/A",
            "Additional Logic": "N/A"
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.4": {
        "Name": "Conflict resolution",
        "Version": 1,
        "Type": "Section",
        "Components": {
            "Content": "This Section must cover a process for appeals where an Atlas Document misalignment is perceived, and how the Governance Scope processes these appeals. They also detail how appeal outcomes are recorded and the rules for resolving Ecosystem Agreement appeals."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.4.1"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.4.1": {
        "Name": "Atlas Document appeals process",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "Atlas Document appeal proposals are submitted by AVC Members, and can be accepted or rejected by a majority of the Governance FacilitatorDAOs. If a Atlas Document appeal is accepted, the Governance FacilitatorDAOs must review it. Governance FacilitatorDAOs can also directly choose to review a Atlas Document for adherence with Scope boundaries and Atlas alignment."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [
            "A.1.3.4.1.1",
            "A.1.3.4.1.2"
        ],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.4.1.1": {
        "Name": "FacilitatorDAO direct edits",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "The Governance FacilitatorDAOs can by consensus directly edit a Atlas Document to align its content with the Scope boundaries and other Atlas requirements such as neutrality."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.4.1.2": {
        "Name": "Governance edits",
        "Version": 1,
        "Type": "Core",
        "Components": {
            "Content": "A majority of the Governance FacilitatorDAOs can trigger an MKR governance poll to implement an edit to the appealed Atlas Document that will align it with the Scope boundaries and other Atlas requirements such as neutrality."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    },
    "A.1.3.5": {
        "Name": "Ossification of Adaptive Documents",
        "Version": 1,
        "Type": "Section",
        "Components": {
            "Content": "This Section must cover the ossification of Adaptive Documents over time for greater stability, certainty, and predictability of protection against long-term slippery slope misalignment. This must be carefully applied only to Adaptive Documents that are safe to ossify to ensure it doesn't result in inflexibility or unintentional misalignment."
        },
        "Last_Modified": "2023-08-16-19:07:00",
        "Child_Documents": [],
        "links_to": {},
        "linked_from": []
    }
}

```

