---
layout: default
title: User Study
nav_order: 2
has_children: false
permalink: /docs/RQ1_user_study
---
## Program Subjects:

As our program subjects we selected four failures from Defects4J, a large and popular
collection of reproducible real-world failures in Java programs, and two failures from the LibRench, a set of real-world client-library project pairs with at least one library upgrade failure.
Table below shows our six selected subjects, together with
the failure id for the Defects4J projects and a short description of each failure.
To ensure participants could fully comprehend the code and answer numerous questions within a reasonable time frame of about 30 minutes to one hour, we shortened and simplified code snippets, preserving the essence of the changes and the failure while removing implementation details. 

<table style="border-collapse: collapse; width: 100%;">
  <tr>
    <th style="border: 1px solid black; padding: 5px; text-align: center;">Dataset</th>
    <th style="border: 1px solid black; padding: 5px; width: 40px; text-align: center;">Sub. ID</th>
    <th style="border: 1px solid black; padding: 5px; text-align: center;">Project (Failure ID)</th>
    <th style="border: 1px solid black; padding: 5px; text-align: center;">Short Description</th>
  </tr>
  <tr>
    <td rowspan="4" style="border: 1px solid black; padding: 5px; text-align: center;"><strong>Defects4J</strong></td>
    <td style="border: 1px solid black; padding: 5px; width: 40px; text-align: center;">S1</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Commons <strong>Chart</strong> (8)</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Modifying <code>timeZone</code> variable reference</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 5px; width: 40px; text-align: center;">S2</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Commons <strong>Lang</strong> (18)</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Modifying <code>year</code> format</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 5px; width: 40px; text-align: center;">S3</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Commons <strong>Math</strong> (37)</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Deleting conditional calculations</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 5px; width: 40px; text-align: center;">S4</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Joda-<strong>Time</strong> (8)</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Modifying arithmetic expression</td>
  </tr>
  <tr>
    <td rowspan="2" style="border: 1px solid black; padding: 5px; text-align: center;"><strong>Librench</strong></td>
    <td style="border: 1px solid black; padding: 5px; width: 40px; text-align: center;">S5</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;"><strong>Jackson</strong>Databind/OpenAPI</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Removing reference shortcut</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 5px; width: 40px; text-align: center;">S6</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Alibaba-<strong>Druid</strong>/Dble</td>
    <td style="border: 1px solid black; padding: 5px; text-align: center;">Modifying SQL Parsing</td>
  </tr>
</table>



---
---

## Study Questionnaires:
The questionnaires were created using the [Qualtrics](https://www.qualtrics.com), a platform that enables the creation and distribution of surveys, as well as data collection and analysis. Qualtrics is widely used for research, market surveys, customer feedback, employee engagement, and academic purposes. 

Below are the two versions of the study questionnaire, "trace first" and "views first," for each of the six subjects. The structure of the questionnaires is identical across subjects, except for the code views and corresponding textual explanations: 

* ### [S1 Trace First](../../assets/data/questionnaries/S1_TraceFirstQuestionnaire.pdf)

* ### [S1 Views First](../../assets/data/questionnaries/S1_ViewFirstQuestionnaire.pdf)

* ### [S2 Trace First](../../assets/data/questionnaries/S2_TraceFirstQuestionnaire.pdf)

* ### [S2 Views First](../../assets/data/questionnaries/S2_ViewFirstQuestionnaire.pdf)

* ### [S3 Trace First](../../assets/data/questionnaries/S3_TraceFirstQuestionnaire.pdf)

* ### [S3 Views First](../../assets/data/questionnaries/S3_ViewFirstQuestionnaire.pdf)

* ### [S4 Trace First](../../assets/data/questionnaries/S4_TraceFirstQuestionnaire.pdf)

* ### [S4 Views First](../../assets/data/questionnaries/S4_ViewFirstQuestionnaire.pdf)

* ### [S5 Trace First](../../assets/data/questionnaries/S5_TraceFirstQuestionnaire.pdf)

* ### [S5 Views First](../../assets/data/questionnaries/S5_ViewFirstQuestionnaire.pdf)

* ### [S6 Trace First](../../assets/data/questionnaries/S6_TraceFirstQuestionnaire.pdf)

* ### [S6 Views First](../../assets/data/questionnaries/S6_ViewFirstQuestionnaire.pdf)