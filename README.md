# SPLC2020 - A Conceptual Model for Unifying Variability in Space and Time - Artifacts

These artifacts relate to the SPLC'20 research paper "A Conceptual Model for Unifying Variability in Space and Time" (no. 37). For arriving at the unified conceptual model presented in the paper, we

	1. conducted interviews with experts of selected tools to understand to what extent the initial conceptual model captures concepts of contemporary tools and which adaptations are needed
	2. refined and unified the conceptual model based on the answers and follow-up joint workshops until the model converged to a consensual state
	3. provided questionnaires to the tool experts to map concepts and relations of their tool to the unified conceptual model 
	4. based on the questionnaires, qualitatively and quantitatively validated the fit of the unified conceptual model to the considered tools

In the following, we provide a short description of the artifacts produced during the construction process of the unified conceptual model.


* InitialConceptualModel_Interviews

* UnifiedConceptualModel_Questionnaires

* Validation_Output
    * `model_mapping.xlsx`
    * `model_metrics_evaluation.xlsx`

For a holistic understanding of the construction process of the unified conceptual model, we refer to Figure 4 of the research paper where we describe the complete process.

## Interviews 

The unified conceptual model described in the research paper is built upon the completed interviews (InitialConceptualModel_Interviews). 
The interviews have been performed between one interviewer and one tool expert. We interviewed tool experts for the following tools: DarwinSPL, DeltaEcore, ECCO, FeatureIDE, GIT, SVN, SiPL, SuperMod, VaVe, pure::variants. Note, that we did not conduct interviews on Git and SVN because they are widely used and extensive documentation is available, allowing us to complete the interview by ourselves. One week before each interview, we provided the blank interview form (`InterviewGuideline_InitialConceptualModel.pdf`) to each tool expert and completed it jointly during the interview. Subsequently, we conducted a follow-up inspection of the answers we documented while interviewing each tool expert to ensure they were complete and consistent. The eight interviews took 83 minutes on average.
Each interview involved four parts. First, the initial conceptual model (Ananieva et al.[1]) and definitions of the involved concepts. Second, a mapping between concepts of the initial conceptual model to constructs of the interviewee’s tool. Third, main use cases of the tool and its scope in order to distinguish it from other tools. Finally, in the fourth part, the tool's operations (e.g., code analysis) to obtain a holistic understanding of the tool.

## Questionnaires 

For the validation of the unified conceptual model, we conducted a survey based on a questionnaire that we provided to the tool experts that were interviewed before (`QuestionnaireGuideline_UnifiedConceptualModel.pdf`). Each questionnaire comprised two parts and was structured similarly to the interview. First, we introduced the unified (not the initial) conceptual model and provided definitions of its concepts and relations. Second, we asked whether each concept and relation of the unified conceptual model could be mapped to constructs and relations of the respective tool, also taking into account unmapped constructs and the names of each tool construct. We also asked for general remarks. Note, that we refrained from explicit expert interviews since all tool experts were already familiar with the mapping procedure. The answers of tool experts in the questionnaires were occasionally vague, incomplete or posing questions. We carefully analyzed the answers and conferred with tool experts. Text that has been added to a questionnaire due to clarification is colored red. Generally, we took the answers in the questionnaires as literally as possible with minimum amount of interpretation.

## model_mapping

The spreadsheet `model_mapping.xlsx` contains the information extracted from the completed questionnaires. It is comprised of two sheets: The first sheet (Mapping Concepts) provides an overview of mapping of concepts of the unified conceptual model to respective tool constructs. The second sheet (Mapping Relations) provides an overview of the mapping of relations of the unified conceptual model to respective relations in the tools. 

## model_metrics_evaluation 

The spreadsheet `model_metrics_evaluation.xlsx` relies on the *model_mapping* to quantify the fit of the unified conceptual model to the selected tools. It contains numeric results for mapping each tool individually based on four definded metrics (laconic, lucid, complete, sound). For the definition of the four metrics, we refer to the research paper. We display the values of the four metrics (columns) per tool (rows), separated by concepts and relations that belong to the space, time, both, and the unified dimensions. Each row contains the percentage as well as the absolute number of conceptual model concepts and relations (in case of lucidity and soundness) or tool constructs and relations (in case of laconicity and completeness) that satisfy the condition for each metric.

## Misc

Please note: We did not receive permission to publish the completed interview and questionnaire for pure::variants.

## References

[1] Sofia  Ananieva,  Timo  Kehrer,  Heiko  Klare,  Anne  Koziolek,  Henrik  Lönn,  S.Ramesh, Andreas Burger, Gabriele Taentzer, and Bernhard Westfechtel. Towards a conceptual model for unifying variability in space and time. Proceedings of the 23rd International Systems and Software Product Line Conference (SPLC’19), Volume B, Paris, France, September 9-13, 2019. ACM, 67:1–67:5.
