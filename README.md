## SNOMED CT Computable Languages

This repository contains the formal syntax, example parser, and valid example files for each computable language in the SNOMED CT Family of Languages.

The SNOMED CT Family of Languages currently includes:
* **SNOMED CT Compositional Grammar** - used to represent SNOMED CT expressions. The SNOMED CT Compositional Grammar Specification and Guide is available at [snomed.org/scg](http://snomed.org/scg).
* **SNOMED CT Expression Constraint Language** - used to represent SNOMED CT expression constraints and simple queries. The SNOMED CT Expression Constraint Language Specification and Guide is available at [snomed.org/ecl](http://snomed.org/ecl).

It is anticipated that the following languages will be added to this repository in the future:
* **SNOMED CT Query Language** - used to represent computable queries over SNOMED CT content.
* **SNOMED CT Templates** - allows slots to be added to expressions, expression constraints or queries that can be filled with specific values at a later time.

The folders are organized as follows:
* *SnomedCTCompositionalGrammar* - contains files relating to SNOMED CT Compositional Grammar
  * *CG Examples* - contains a set of valid example files for SNOMED CT Compositional Grammar
  * *CG Parser* - contains an example parser for SNOMED CT Compositional Grammar (as generated by the APG ABNF Parser Generator)
  * *CG Syntax* - contains the ABNF syntax for SNOMED CT  Compositional Grammar
* *SnomedCTExpressionConstraintLanguage* - contains files relating to the SNOMED CT Expression Constraint Language
  * *ECL Examples* - contains a set of valid example files for the SNOMED CT  Expression Constraint Language
  	* *ECL v1* - contains examples for v1 of the SNOMED CT  Expression Constraint Language
  	* *ECL v1.2* - contains examples for v1.2 of the SNOMED CT  Expression Constraint Language
  * *ECL Parser* - contains an example parser for the brief (normative) and long (informative) ABNF syntaxes of the SNOMED CT Expression Constraint Language (as generated by the APG ABNF Parser Generator)
  * *ECL Syntax* - contains the brief (normative) and long (informative) ABNF syntaxes for the SNOMED CT  Expression Constraint Language
