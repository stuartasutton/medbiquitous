## Association of American Medical Colleges (AAMC):
### *Core Entrustable Professional Activities for Entering Residency: Curriculum Developer's Guide*

The Association of American Medical Colleges (AAMC) has a competency framework titled [*Core Entrustable Professional Activities for Entering Residency: Curriculum Developer's Guide*](https://store.aamc.org/downloadable/download/sample/sample_id/63/%20). The framework relies on two other AAMC competency frameworks: (1) *Expected Behaviors for Pre-Entrustable and Entrustable Learners*, and (2) *Reference List of General Physician Competencies by Domain* (both found in the appendices of the Guide).

The purpose of the [*Core Entrustable Professional Activities for Entering Residency: Curriculum Developer's Guide*](https://store.aamc.org/downloadable/download/sample/sample_id/63/%20) framework is to relate (conextualize) the 58 general physicians competencies in the [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) (Secondary Source) framework to the 13 expected activities (EPAs) in the [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) (Secondary Source) framework.  As a result, the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) reuses EPAs and competencies by importing all (or desired parts) of them from the Secondary Source files.

All but 3 of the competencies in the [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) Secondary Source framework are assigned to from 2 to 13 of the EPAs in the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) Primary File .

The following process was followed with the editor:

* First, the 13 EPAs are imported into the [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) Primary File as derivitaive nodes from the [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) Secondary Source File;

* Second, each of the 58 the competencies in the [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) Secondary Source framework are imported into the Primary File as derivative nodes from the Secondary File (see JSON-LD lines 391-416) and assigned to the first of the 13 EPAs to which the competency has been assigned; and

* Using the editor's copy-and-pasted functionality, each competency that hase bee assigned to a subsequent EPA is duplicated (e.g., see JSON-LD lines 904-929). 
* 
### CaSS Editor Dependencies

* Import competencies from other frameworks
* Duplicate competencies (Copy competency/Paste competency)

### JSON-LD Files in the CaSS Editor (Sandbox)

1. [*CoreEntrustableBehaviors*](https://sandbox.credentialengine.org/publisher/competencies) (***Partial*** Primary File)
2. [*ExpectedBehaviors*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-56493611-b46b-4658-88d4-f80c0427f011) (***Complete*** Secondary Source File)
3. [*GeneralPhysicianCompetencies*](https://sandbox.credentialengine.org/publisher/competencies/?frameworkctid=ce-8c2da966-9c5a-4d65-aa51-f2808ffab550) (Secondary Source File)

### Corrected JSON-LD File

1. [*CoreEntrustableBehaviors.json*](https://github.com/stuartasutton/medbiquitous/blob/main/CoreEntrustableBehaviors.json) (***Partial*** Primary File)--***Note: Correctings made per text below***
2. [*ExpectedBehaviors.json*](https://github.com/stuartasutton/medbiquitous/blob/main/ExpectedBehaviors.json) (Secondary Source File)
3. [*GeneralPhysicianCompetencies.json*](https://github.com/stuartasutton/medbiquitous/blob/main/GeneralPhysicianCompetencies.json) (Secondary Source File)
