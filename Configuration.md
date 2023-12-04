---


---

<h1 id="software-configuration-management-audit-report"># Software Configuration Management Audit Report</h1>
<h2 id="audit-use-case-1">Audit <a href="https://github.com/Giuseph-CT/FIS-Proyecto-2023/blob/TerceraEntrega_MD/Artifacts/use%20cases.md">use-case 1</a></h2>
<ol>
<li>Is the use-case name meaningful and unambiguous?  <strong>YES</strong></li>
</ol>
<blockquote>
<p>Use Case 1: Record Patient Progress</p>
</blockquote>
<ol start="2">
<li>Does the brief description clearly describe the primary goal of the use case? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Objective:</strong> The nutritionist should be able to efficiently record and update the progress of a patient’s nutritional journey within the cloud-based system.</p>
</blockquote>
<ol start="3">
<li>Are associated Actors and information exchanged clearly defined? YES</li>
</ol>
<blockquote>
<p><strong>Actors:</strong><br>
-   Nutritionist (Primary User)<br>
-   Cloud Storage</p>
</blockquote>
<ol start="4">
<li>.Are the pre-conditions specified? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Preconditions:</strong><br>
-   The nutritionist has access to an internet connection.<br>
-   The nutritional calculation software is functioning correctly.</p>
</blockquote>
<ol start="5">
<li>Are the basic flow and alternative flows complete, correct, and consistent? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Main Flow of Events:</strong><br>
1.  The nutritionist logs into the nutritional calculation software in the cloud.<br>
2.  Selects the “Record Patient Progress” option from the main menu.<br>
3.  Chooses a specific patient for whom they want to update nutritional progress.<br>
4.  The system displays the patient’s current nutritional data, such as weight, dietary habits, and any notes from previous sessions.<br>
5.  The nutritionist updates the information, adding details about the patient’s recent progress, changes in dietary preferences, or any relevant notes.<br>
6.  The system securely saves the updated data in the cloud.<br>
<strong>Alternative Event Flows:</strong><br>
1.  If the system encounters an error while saving the updated information, it notifies the nutritionist and suggests retrying.<br>
2.  If the selected patient does not exist, the system informs the nutritionist and prompts them to verify the patient’s details.</p>
</blockquote>
<ol start="6">
<li>Are the post-conditions specified? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Postconditions:</strong><br>
-   The nutritionist successfully records and updates the patient’s progress data in the cloud.</p>
</blockquote>
<ol start="7">
<li>Are applicable nonfunctional requirements captured? <strong>NO</strong></li>
</ol>
<h2 id="audit-use-case-2">Audit <a href="https://github.com/Giuseph-CT/FIS-Proyecto-2023/blob/TerceraEntrega_MD/Artifacts/use%20cases.md">use-case 2</a></h2>
<ol>
<li>Is the use-case name meaningful and unambiguous?  <strong>YES</strong></li>
</ol>
<blockquote>
<p>Use Case 2: Generate Nutritional Reports</p>
</blockquote>
<ol start="2">
<li>Does the brief description clearly describe the primary goal of the use case? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Objective:</strong> The nutritionist should be able to generate comprehensive nutritional reports for a selected patient using the cloud-based system.</p>
</blockquote>
<ol start="3">
<li>Are associated Actors and information exchanged clearly defined? YES</li>
</ol>
<blockquote>
<p><strong>Actors:</strong><br>
-   Nutritionist (Primary User)<br>
-   Cloud Storage</p>
</blockquote>
<ol start="4">
<li>.Are the pre-conditions specified? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Preconditions:</strong><br>
-   The nutritionist has access to an internet connection.<br>
-   The nutritional calculation software is functioning correctly.</p>
</blockquote>
<ol start="5">
<li>Are the basic flow and alternative flows complete, correct, and consistent? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Main Flow of Events:</strong><br>
1.  The nutritionist logs into the nutritional calculation software in the cloud.<br>
2.  Selects the “Generate Nutritional Report” option from the main menu.<br>
3.  Chooses a specific patient for whom they want to create a report.<br>
4.  The system retrieves the patient’s historical nutritional data from the cloud.<br>
5.  The nutritionist selects the parameters for the report, such as daily caloric intake, nutrient distribution, and progress over time.<br>
6.  The system processes the selected parameters and generates a detailed nutritional report for the chosen patient.<br>
7.  The nutritionist can view, download, or print the generated report.<br>
<strong>Alternative Event Flows:</strong><br>
1.  If there is insufficient data for the selected patient, the system notifies the nutritionist and suggests collecting more information before generating the report.<br>
2.  If there is an error in the report generation process, the system informs the nutritionist and provides guidance on resolving the issue.</p>
</blockquote>
<ol start="6">
<li>Are the post-conditions specified? <strong>YES</strong></li>
</ol>
<blockquote>
<p><strong>Postconditions:</strong><br>
-   The nutritionist obtains a detailed nutritional report for the selected patient, which is stored in the cloud and can be accessed at any time.</p>
</blockquote>
<ol start="7">
<li>Are applicable nonfunctional requirements captured? <strong>NO</strong></li>
</ol>
<p>This use-cases does’nt fills all the points required for, so the configuration and versioning  it’s<br>
uncompleted. It’s necessary to cover all this points and try to guarantee user satisfaction.<br>
A well-made and complete use-case improves the effectiveness of the system under development and contributes to the success of the project.<br>
SOURCE:<br>
<a href="https://www.utm.mx/~caff/doc/OpenUPWeb/openup/guidances/checklists/use_case_C5362874.html">Checklist: Use Case (utm.mx)</a></p>

