# Quality Improvement Manuscript AI Grading and Suggestions Resources

This is a collection of resources and prompts for evaluating and grading student papers about quality improvement projects. It is broken down by sections as defined by SQUIRE 2.0 guidelines. It is an extension of the general writing suggestions I provide in https://github.com/cmcntsh/PoWeRWritingGradStudents. The generative models listed in the table below may work. I'm ordering the table by the models that currently seem the best for this purpose. Higher up the list seems to perform better, lower down the list may not perform as well or is untested. Models get updated periodically, so performance may vary over time. 

| Link | Model | Company | Testing Status | Limitations | As of Date |
| --- | --- | --- | --- | --- | --- |
| https://chat.openai.com/ | GPT 3.5 | OpenAI | moderate testing | confused on more complex tasks | 01/31/2024 |
| https://copilot.microsoft.com/ | GPT 4.0 Turbo | Microsoft | little testing | 2000 character input limit (need to split text up into chunks) | 01/31/2024 |
| https://claude.ai/chats | Claude | Anthropic | little testing | | 01/31/2024 |
| https://gemini.google.com/app | Gemini | Google | little testing | superficial analysis, minimal feedback on writing evaluation | 02/26/2024 |
| https://chat.mistral.ai/chat | Mistral Large | Mistral | Untested |  | 02/26/2024 |

### Substantive Editing

Prompts for evaluating content and structure are provided in the individual sections below.

### Copyediting

You should do copyediting (checking grammar, spelling, and punctuation) on the text in each section individually. https://github.com/cmcntsh/PoWeRWritingGradStudents?tab=readme-ov-file#preliminary-check-of-grammar-and-spelling-before-sending-your-work-to-others

```
Please list each sentence of this text in a new line, and please number the lines. In addition, please review each sentence for grammar, syntax, usage, spelling, and punctuation errors and suggest specific improvements. When suggesting revisions, please list the sentence number, the original sentence, the reason a revision might be needed, and then the revised sentence. If no revision is suggested, please indicate that no revision is needed.  Here is the text: "[paste text here inside quotes]"
```

## 1. Title

Prompt: Evaluate the title of a quality improvement paper (See 1. Title at https://www.squire-statement.org/index.cfm?fuseaction=page.viewpage&pageid=504)

```
How well does this title meet the following criteria: Does the title indicate that it is about an initiative to improve safety, value, and/or quality in healthcare? Does the title describe the aim of the project? Does the title describe the context in which the project occurred? Is the title descriptive? Is the title simply written? Which terms in the title allow the reader to identify easily that the project is within the field of healthcare improvement? Which medical subject headings (MeSH) in the National Library of Medicine’s Medline database apply to this title? Please suggest ways the title could be improved and provide a revised title. Here is the title: "[paste the title here inside quotes]"
```

## 2. Abstract (write last)

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting 

## 3. Problem Description

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem or information that is simply not available at this point. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text answer each of these questions? Why are you doing this project? What is the problem you’re addressing? Who is affected? When is it a problem? Why does it matter? How does it affect the patient or system? Has a cause been identified? What will happen if this problem is not addressed?
"[Paste the text you want evaluated here.]"
```
#### Prompt when text exceeds character limits

Prompt: Include this phrase instead of the text in the prompt above if the text is too long to submit in a single entry.

```
The text is long and I need to submit it in sections. Please tell me when you're ready for the first section of text. After you receive the first section of text, tell me when you're ready for the next section of text. After each submission, keep asking for the next section of text until I tell you I'm done submitting text. Don't analyze the text until after I tell you all the text is submitted.
```


### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```

## 4. Available Knowledge

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem or information that is simply not available at this point. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
What evidence is cited in the following text to answer each of these questions? What is currently known about the problem in general, including relevant previous studies? Who is affected by the problem? What are the impacts of the problem? How does the problem affect those individuals? When is it a problem? Why is it a problem or why does the problem matter? What are the costs or the other negative impacts of the problem? How prevalent is the problem or how many people are affected? Are there any existing trends that contribute to the problem? Are probable causes of the problem identified? Are there any formal standards related to this problem? How are the main concepts relevant to the problem defined? Is any supporting literature or evidence cited?
"[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful, well-supported with credible evidence | Strong understanding, relevant and valid evidence | Adequate understanding, limited or irrelevant evidence, superficial | Limited understanding, weak or irrelevant evidence, inaccurate |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 5. Rationale

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements? What frameworks, models, concepts, or theories are used to explain the problem? What frameworks, models, concepts, or theories were used to develop the intervention? What reasons or assumptions were used to develop the intervention? Why is the intervention expected to work? Describe the framework, model, or theory used to guide the activities of your project? Describe how the framework, model, or theory aligns with and guides the work on the project? Is any relevant literature cited? Is there any evidence this type of intervention may work?
"[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful, well-supported with credible evidence | Strong understanding, relevant and valid evidence | Adequate understanding, limited or irrelevant evidence, superficial | Limited understanding, weak or irrelevant evidence, inaccurate |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 6. Specific Aims

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements? What is the purpose of the project? What are the objectives of the project? Do the objectives support the overall purpose? Are the objectives stated in a logical order? Are the project purpose and objectives clearly stated?
"[Paste the text you want evaluated here.]"
```

### Evaluate how well each objective is supported by text in the Problem Description section

Project objectives should be selected because they address the local problems outlined in the Problem Description section.

Prompt (This prompt could be tried in https://chat.openai.com/ or https://bard.google.com/chat .)

```
I'm conducting a healthcare quality improvement project and reporting the results following SQUIRE 2.0 guidelines. Categorize how well the problem description text supports each project objective using the following categories. (available categories are directly supported, indirectly supported, and not supported)  Here are the project objectives: "[paste project objectives text here]" Here is the problem description text: "[paste Problem Description text here]"
```

### Evaluate how well each objective is supported by the evidence cited in the Available Knowledge section

Project objectives should also be selected because they address problems identified in published literature.

Prompt (This prompt could be tried in https://chat.openai.com/ or https://bard.google.com/chat .)

```
I'm conducting a healthcare quality improvement project. Categorize how well the cited evidence supports each project objective using the following categories. (available categories are directly supported, indirectly supported, and not supported) Here are the project objectives: "[paste project objectives text here]" Here is the available knowledge text: "[paste Problem Description text here]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 7. Context

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements? What are the conditions that existed before the project started? What is the setting where the project is taking place? What processes were in use before the project started? Is this project part of a larger project? Who are the sponsors of the project? Who are the team members working on the project? Who are the beneficiaries of the project? Who will be directly impacted by the project? Who may be indirectly impacted by the project? Are there any contextual factors that may impact the success of the project? Is any literature or supporting evidence cited?
"[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 8. Intervention(s)

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? How is the intervention described? Is there sufficient detail that someone else could replicate the intervention? Who is involved in implementing the intervention?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 9. Study of the Intervention(s)

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? What approach will be used to evaluate the effectiveness of the intervention? What approach will be used to establish whether the outcomes were due to the intervention?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 10. Measures

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? What tools, instruments, or measures are described? What are the operational definitions for key concepts? What is the reliability and validity of the tools, instruments, or measures? What is the approach for assessing contextual elements that impact the success or failure of the intervention? What methods to assess the completeness and accuracy of the data are described?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful, well-supported with credible evidence | Strong understanding, relevant and valid evidence | Adequate understanding, limited or irrelevant evidence, superficial | Limited understanding, weak or irrelevant evidence, inaccurate |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 11. Analysis

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? What qualitative methods are described to draw inferences from the data? What quantitative methods are described to draw inferences from the data?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 12. Ethical Considerations

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements? What ethical review process is described? What conflicts of interest are described? What are the ethical aspects particular to this project? Is any literature or evidence cited?
"[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful, well-supported with credible evidence | Strong understanding, relevant and valid evidence | Adequate understanding, limited or irrelevant evidence, superficial | Limited understanding, weak or irrelevant evidence, inaccurate |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 13. Results

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? What were the steps to implement the project? Did the project go as planned? What were the results? What was measured? Were there any unintended consequences? Is missing data or any other data quality issues described?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 14. Summary

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? What were key findings for the project? Which results were most compelling? What is the link between key findings and project objectives?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 15. Interpretation

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? How do the results of this project compare with results of other publications? What was the impact of the project on people or systems? What were the reasons for any differences between observed and anticipated outcomes? Did the project accomplish the stated purposes? What lessons were learned by conducting the project? What pitfalls or challenges were encountered during the project? What solutions were found to overcome the challenges? Is any literature or evidence cited?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 16. Limitations

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? What are the limitations to the generalizability of the work? What factors may limit internal validity? What are the limitations of the project? What efforts were made to adjust for limitations?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```



## 17. Conclusions

### Get a quick overall understanding of what is covered in the section by getting an outline

Prompt

```
Please display the following text in outline format. In addition, please make the level 1 headings bold. In addition, please make the level 2 headings italics. Here is the text: "[paste text here inside quotes]"
```

### Copyediting

See copyediting prompt above. https://github.com/cmcntsh/QualImpAIGrading#copyediting

### Evaluate the Comprehensiveness of Content Coverage

This section should cover most of the aspects described in the section instructions unless there are elements that are not relevant to this particular problem. I would assess the comprehensiveness of the student's writing and identify any gaps left unaddressed by the student, and assign a grade according to the point rubric accordingly.

Prompt: This is the substantive editing prompt that evaluates general content.

```
How well does the following text discuss each of these elements for each project objective? What is the usefulness of the work? Is the work sustainable? What is the potential to spread this work to other contexts? What are the implications for practice? What are the implications for further study in the field? What is the overall usefulness of the work done for this project? Are there any larger implications to the field beyond this local setting? What else might still need to be done? What are the next steps? Are there any areas where current literature does not address questions you had or issues you encountered?
Here are the project objectives: "[Paste text describing each objective here.]" Here is the section text: "[Paste the text you want evaluated here.]"
```

### Grading a piece of writing using a specific rubric

Prompt

```
Please grade the following text based on this rubric
[Paste the text of the rubric here, including the point values along the top and the grading categories along the side.]
Here is the text:
"[Paste the text to be graded here inside quotes.]"
```

Rubric

| Criteria |  4  |  3  |  2  |  1  |
| --- | --- | --- | --- | --- |
| Grammar & Punctuation | The author makes no errors in grammar, mechanics, or spelling. | The author makes a few errors in grammar, mechanics, or spelling, but they do not interfere with understanding. | The author makes several errors in grammar, mechanics, or spelling that interfere with understanding. | The author makes numerous errors in grammar, mechanics, or spelling that interfere with understanding. |
| Logic & Flow | The author consistently uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author mostly uses well-formed paragraphs that have clear topics, suitable transitions between sentences and paragraphs, logical arrangement, and clearly written sentences. | The author has some paragraphs that are not well-formed. Topics in some paragraphs may not be clear. Some transitions between sentences and paragraphs may be abrupt or disjointed. Some paragraphs or sentences may not follow a logical arrangement or may not be clearly written. | The author has several paragraphs that are not well-formed. Topics in several paragraphs may not be clear. Transitions between sentences and paragraphs may be abrupt or disjointed. Several paragraphs or sentences may not follow a logical arrangement or may not be clearly written. |
| Content | Original and insightful | Strong understanding | Adequate understanding, superficial | Limited understanding, weak |
| Style & Voice | Engages reader, clear and confident voice, stylistic control and flexibility, perfect tone | Clear and engaging, consistent voice, may lack originality or nuanced tone | Unclear or uneven voice, struggles to engage, inconsistent voice | Lacks clarity and engagement, unable to convey ideas, inconsistent or inappropriate voice |
| APA Formatting | Flawless adherence to APA guidelines, including citations, references, formatting, and structure | Consistent application of APA principles, minor deviations not affecting clarity | Partial understanding of APA, inconsistent application, errors hinder clarity | Frequent APA errors, inaccurate formatting, citations or references unclear or missing |

#### Follow up to get specific suggestions for improvement

ChatGPT suggested a grade and made some geneneral suggestions for improvement. I followed up with another prompt and received specific examples with suggested fixes.

Prompt

```
Please provide specific examples where the author could make corrections and how they could be corrected.
```

## References

Prompt: Check the formatting of references in the references list. (These need to be double-checked to verify correctness, but this prompt caught many formatting problems.)

```
Do these references follow proper APA 7 formatting guidelines? Please suggest specific improvements where needed. Here are the references: "[paste references here in quotes]"
```


