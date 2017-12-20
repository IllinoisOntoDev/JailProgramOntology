###

1. Vocabulary without imports - http://purl.org/lis590OD/Fall17/JailProgramOnt#

2. (2-4) Integration with other vocabularies

My ontology integrates with Erica's and Linh's ontologies, which are the crime charge and ex-offender program ontologies, respectively.

I use Erica's ontologies to determine the eligibility of inmates for some programs. Some jail programs might have restrictions on what types of offenders are allowed to join. For example, a transitional housing program may only accept offenders charged with misdemeanors and reject those charged with felonies. Erica's ontology makes an inference on whether an inmate is charged with a misdemeanor or felony based on their specific law violation.

Linh uses my ontology to help determine the appropriate educational programs for an inmate seeking employment after jail release.

I also use the AgencyRelationship vocabulary for jail program completion. Basically, it allows me to describe that inmates have completed certain jail programs. This is useful especially for education programs, and could further help Linh's ontology.

5. Test Vocabulary - https://github.com/IllinoisOntoDev/JailProgramOntology/blob/master/jail_programs_test.owl
 
6. Inferences

I also import the crime charge ontology in the test vocabulary so I can create the appropriate inferences that depend on the crime classification (e.g. felony).