# M3224.000300.  인공신경망을 통한 자연어 처리

## Links

🗓 [Course schedule](https://lee-jay-yoon.notion.site/10347caa5a88495a89947af04bc4d941?v=39c2b3b47b3e40a5bbbe0aee2d78cb6e)
 📕 [Reference Texts](https://leejayyoon.github.io/nlp-gsds/#reference-texts)
 🕰 [Time & Location](https://leejayyoon.github.io/nlp-gsds/#time--location)

👨🏻‍🏫 [Instructor & TAs](https://leejayyoon.github.io/nlp-gsds/#instructor)
 🏃🏻‍♂️ [Course description](https://leejayyoon.github.io/nlp-gsds/#course-description)
 📐 [Grading policy](https://leejayyoon.github.io/nlp-gsds/#grading-policy) 


## **Reference Texts**

No specific text book is required for this course but the following texts could be useful.  (First two are free online)

- Dan Jurafsky and James H. Martin, [Speech and Language Processing (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/)
- Jacob Eisenstein, [Natural Language Processing](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
- Masato Hagiwara, [Real-World Natural Language Processing](https://www.manning.com/books/real-world-natural-language-processing)

## Time & Location

- **Time:** Fri 9:30am-12:20am
- **Location:** Building 43, room 201 or virtually via Zoom.
- Zoom link will be provided through ETL and possibly via emails.

## Instructor

[Lee, Jay-Yoon](https://leejayyoon.github.io/) 

- email: lee.jayyoon@snu.ac.kr
- office: Building 43, Room 513
- office hours: By appointment

## Teaching Assistants
- TA Office hours: By appointment
- Oh, Jeongseok, [luke0112@snu.ac.kr](mailto:luke0112@snu.ac.kr)
- Jeon, Hyewon, [pingpong0926@snu.ac.kr](mailto:pingpong0926@snu.ac.kr)

## Course description

This course introduces core deep learning techniques used in modern natural language processing and visits recent advances and the challenges unresolved.

This course covers the following topics:

- How NLP utilizes representation learning.
- How problems in NLP motivated novel deep learning approaches such as attention and self-attention.
- Architectures: RNN, Sequence-to-sequence model, Transformer.
- Applications: word embedding, Language Model, core NLP (Parsing, SRL), QA and natural language generation (Summarization, Machine Translation, etc.) problems.
- Recent concerns: controllability, injection of constraints and knowledge, bias & fairness

## Grading policy
- Up to 7 **grace days** are provided (maximum 3 days per assignment). Using grace days for final project report is not allowed.
- **Final grade** will be determined as a weighted average of the assignments, midterm, and project.
    - Cutoffs for final grades will be approximately 97+ A+, 93+ A, 90+ A-, 87+ B+, 83+ B, 80+ B-, etc.
- **Participation**: 5%
- **Paper presentation**: 5%
- **Quiz**: 10%
   - When computing the total quiz score, we will exclude the 3 lowest quiz scores from the calculation.
- **Assignments**: 40%  A+ (100), A (96), A- (92), B+ (88), B (85), B- (82), or below.
    - There will be FOUR assignments (10% each). Links to be provided.
       - [Assignment 1]
       - [Assignment 2]
       - [Assignment 3]
       - [Assignment 4]
- **Project** : 40%
   - Teams of 2-3. Individual project requires permission from instructor.
   - From the project proposal, write your document in the [NeurIPS 2024 format](https://www.overleaf.com/latex/templates/neurips-2024/kxymzbjpwsqx) using latex (perhaps through overleaf).

## Detailed description on project:
- (1) Idea proposal (1 page description of proposed idea; 10%)
   The idea proposal should include following:
    - Description of task.
    - Description of challenges to resolve, or project goal that the project wants to achieve.
    - Small survey of existing approaches (and their limitations) in short.
    - There will be a selection of potential research topics provided by TAs. Students have the option to either select one of these provided topics and expand upon it, or suggest their own research idea.
- (2) Progress report (4 pages; 10%) 
   The progress report should include the following
    - Baseline establishment: running the state-of-the-art models & analyzing it. Try to recover the state-of-the-art reusult and describe the difficulties (especially if you were not successful in recovering it). Based on the experiments and error analysis, what are the weakness of the baseline model? Describe how you might improve the baseline.
    - More extensive literature survey compared to idea proposal.
    - Grading criteria:
      - A+: Stands out, or surpringly creative.
      - A: An extensive survey and well-grounded project proposal based on this survey.
      - A-: The survey has good structure but misses a few pieces of relevant related work, or survey is OK but misses few important analysis that grounds the project proposal. (Proposal seems to be less groudned)
       - B+: The survey lacks in coverage or analysis.
       - B or B-: The survey is lacking in both coverage and analysis, but makes some effort.
       - C+ or below: Clear lack of effort or incompleteness.
- (3) Final report & presentation (about 6 pages or more, up to 8 pages; 20%)    
    - On top of the project proposal, you should describe (1) newly proposed method or (2) how existing method was applied to new NLP task with description of unique challenge for such task, (3) how existing method and existing NLP task have been newly applied to new doamain/langauge.
    - Grading criteria.
      - A+: Exceptional or surprisingly creative. The project notably stands out compared to most of other projects.
      - A: A reserach contribution that is resepctable both in terms of novelty and effectiveness (performance). Most papers with this grade should have a quality that can be submitted to a conference.
      - A-: A reserach contribution that is resepctable both in terms of novelty and effectiveness, but with small incomplete parts.
      - B+: An idea is novel and well orgaznied, but result or analysis might be missing.
      - B or B-: Results, analysis, or novelty are lacking. 
      - C+ or below: Clear lack of effort or incompleteness.
