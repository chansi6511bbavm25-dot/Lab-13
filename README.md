### LAB 13 – Retrieval-Augmented Generation and Source Verification

This lab focused on understanding **Retrieval-Augmented Generation (RAG)** and how it can help AI provide answers based on a supplied source document. RAG involves two main processes: retrieval of relevant information from a document and generation of an answer using that retrieved information. The activity also highlighted that RAG improves grounding but does not guarantee that every answer is completely accurate.

The lab first compared a **normal chatbot with a RAG or document-grounded chatbot**. A normal chatbot mainly uses general model knowledge and prompt context, while a RAG chatbot retrieves information from an approved document. RAG can provide source-based answers and citations, but human verification is still required.

For the practical activity, a fictional **AeroVista Airlines Baggage Policy** was selected. The source was reviewed before use to identify its purpose, audience, topics covered, missing information, revision date, and approval status. No real passenger information, passport details, booking references, or confidential airline information was used.

An **ungrounded question** about delayed baggage was first tested without providing the policy document. The AI correctly avoided claiming exact reporting procedures, delivery timelines, reimbursement amounts, or compensation conditions. After the source was supplied, grounding instructions were added so that answers had to rely only on the document and state **“Not found in the supplied document”** when information was unavailable.

The activity included a **claim–source–match–context–action verification routine**. This helped check whether each AI claim was actually supported by the cited source and whether important conditions or exceptions were preserved. A missing-information test and conditional-information test were also performed.

The lab also examined RAG limitations, including outdated sources, missing information, incorrect retrieval, weak citations, lost context, unsupported claims, and excessive AI confidence. A RAG risk audit was completed, followed by a grounded passenger response and reflection.

Overall, the lab demonstrated that RAG can support aviation-management work by helping users locate information in approved documents. However, **source quality, citation checking, context preservation, and human verification remain essential** before using AI-generated information for business or passenger communication.
