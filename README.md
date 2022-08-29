## Association of American Medical Colleges (AAMC):
### *Core Entrustable Professional Activities for Entering Residency: Curriculum Developer's Guide*

The Association of American Medical Colleges (AAMC) has a competency framework titled [*Core Entrustable Professional Activities for Entering Residency: Curriculum Developer's Guide*](https://store.aamc.org/downloadable/download/sample/sample_id/63/%20). The framework relies on two other AAMC competency frameworks: (1) *Expected Behaviors for Pre-Entrustable and Entrustable Learners*, and (2) *Reference List of General Physician Competencies by Domain* (both found in the appendices of the Guide).

The purpose of the [*Core Entrustable Professional Activities for Entering Residency: Curriculum Developer's Guide*](https://store.aamc.org/downloadable/download/sample/sample_id/63/%20) framework is to contextualize and relate the 58 general physicians competencies in the [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) (Secondary Source) framework to the 13 expected activities (EPAs) in the [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) (Secondary Source) framework.  As a result, the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) reuses EPAs and competencies by importing all (or desired parts) of them from the Secondary Source files.

All but 3 of the competencies in the [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) Secondary Source framework are assigned to from 2 to 13 of the EPAs in the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) Primary File .  

* First, the 13 EPAs are imported into the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) Primary File as derivitaive nodes from the [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) Secondary Source File;

* Second, each of the 58 the competencies in the [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) Secondary Source framework are imported into the Primary File as a derivative node from the Secondary File (see JSON-LD lines 391-416) and assigned to a prcific (here EPA 1_; and then

* copy and pasted that node on EPA 2 (JSON-LD lines 904-929). The Copy and Paste function would make it possible to import once and then copy/paste. So this is doable if the search functionality made it possible to find the competency to import in the first place.

***All three of these competency frameworks have been published in the Sandbox***:

### JSON-LD Files in the CaSS Editor (Sandbox)

1. [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) (***Partial*** Primary File)
2. [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) (***Complete*** Secondary Source File)
3. [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) (Secondary Source File)

### Corrected JSON-LD File

1. [*CoreEntrustableBehaviors.json*](https://github.com/stuartasutton/medbiquitous/blob/main/CoreEntrustableBehaviors.json) (***Partial*** Primary File)--***Note: Correctings made per text below***
2. [*ExpectedBehaviors.json*](https://github.com/stuartasutton/medbiquitous/blob/main/ExpectedBehaviors.json) (Secondary Source File)
3. [*GeneralPhysicianCompetencies.json*](https://github.com/stuartasutton/medbiquitous/blob/main/GeneralPhysicianCompetencies.json) (Secondary Source File)

### CaSS Editor Dependencies

* Import competencies from other frameworks
* Duplicate competencies (Copy competency/Paste competency)

### Nature of the Problem

The purpose of the [*Core Entrustable Professional Activities for Entering Residency: Curriculum Developer's Guide*](https://store.aamc.org/downloadable/download/sample/sample_id/63/%20) framework is to contextualize and relate the 58 general physicians competencies in the [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) Secondary Source File framework to the 13 expected behaviors (EPAs) in the [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) Secondary Source File framework.  As a result, the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) reuses EPAs and competencies by importing all (or desired parts) of them from the Secondary Source files. 

#### Issue: 

Even with the two secondary framework documents in the Sandbox, the search and import functionality was problematic in creating the primary file. It was impossible to find anything. Since an import would generate a new derivatived resource in the Primary framework, I *manually* created the data from the Secondary Source Files adding the ceasn:derivedFrom to the Primary File's JSON-LD after download. So, while the built-in editor process did not work, the end result for this issue was achieved manually though manipulation of the JSON-LD files after export from the editor. This means that the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) in the editor is incorrect while the [*CoreEntrustableBehaviors.json*](https://github.com/stuartasutton/medbiquitous/blob/main/CoreEntrustableBehaviors.json) Primary JSON_LD file is correct. This all may be an issue with trying to do this in the Sandbox. 

With the exception of 3 competencies in the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) Primary File framework, all other competencies appear in as many as all 13 EPAs in the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) (Secondary Source File).  So, I've imported a specific competency into the Primary File as a derivative node from the Primary File (JSON-LD lines 391-416) on EPA 1 and then copy and pasted that node on EPA 2 (JSON-LD lines 904-929). The Copy and Paste function would make it possible to import once and then copy/paste. So this is doable if the search functionality made it possible to find the competency to import in the first place. 

### The Result

Until these editor issues are straightened out, the Primary framework JSON-LD file only covers EPA 1 and EPA 2; but, that's enough since that involves the import from both Secondary Source files and the repeat of one of the competencies (PC 1) in both EPA 1 and EPA 2. 


