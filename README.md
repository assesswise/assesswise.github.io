# AssessWise

**An AI partner that makes understanding visible.**

> Status: **concept and clickable mock-up.** The dialogue in the demo is pre-scripted. No actual AI is running, and the student in the demo is fictional.

AssessWise is an educational product concept for the "Minds and Machines in Learning".

## The question

How do we assess understanding when AI can write a good text?

A polished paragraph no longer shows that a student can reason. AI detectors are not a fair answer: they can wrongly flag non-native English writing (Liang et al., 2023). AssessWise instead makes the student's reasoning visible, and keeps the teacher responsible for the final mark.

## The idea

First version: first-year students learning to write reasoned academic arguments (one skill, one task type).

The student goes through a cycle:

1. **First attempt:** short draft, AI-use declaration, self-assessment against the teacher's criteria.
2. **Explain:** the student explains one key choice; the system asks about that exact fragment.
3. **Dialogue:** questions, hints and parallel examples. Feedback has a fixed structure: criterion, quote from the work, suspected issue, question. The student can press **"I disagree"** to challenge any AI comment; unresolved disagreements go to the teacher.
4. **Revise:** the student edits the text and explains the change; versions are compared.
5. **Independent transfer:** a new short task on the same skill, without help.

The teacher sees the original work, revision, explanation, disputes and the transfer answer. **The teacher gives the final mark.** The AI never grades. Using hints never lowers the mark.

## Try the demo

Open assesswise.github.io in any browser.

- The scenario: the claim "Online learning raises achievement". The student writes "the average grade rose, so online learning is more effective"; the dialogue helps them find alternative explanations (for example, a changed exam).
- Use the **"Use a sample answer"** buttons to move quickly through the steps.
- Try **"I disagree with this comment"** (the first dispute is withdrawn by the scripted AI, the second is passed to the teacher), then open **Teacher view** and **Ethics & data**.
- The mock-up is in English only.


## Pedagogical foundation

- **Constructive alignment** (Biggs & Tang): criteria, tasks, feedback and mark fit the learning outcomes.
- **Formative assessment and feedback** (Black & Wiliam; Nicol & Macfarlane-Dick): feedback is used to improve work, not to rank students.
- **Student-centred and social constructivist learning:** the student explains, discusses, revises and transfers the skill.
- **Universal Design for Learning** (CAST) and **TPACK** (Mishra & Koehler): inclusive design; technology serves the pedagogy.

## Ethics by design

- **Transparency:** each comment shows the criterion, the quoted fragment and the reason, and is marked preliminary.
- **Right to disagree:** students can dispute comments and pass them to the teacher.
- **Minimal data:** the demo uses invented text; no names or student ID numbers. If text were sent to an external AI service, the interface must say so.
- **No hidden surveillance:** no keystroke logging, camera or "authorship percentage". An AI-use declaration supports discussion; it is not proof of authorship.
- **Accessibility:** keyboard use, readable contrast, no timers.

## Limitations and evaluation plan

- Effectiveness is **not proven**. A pilot could compare written criteria comments with the AssessWise dialogue on the same task, revision and a new transfer task, with blind marking against one rubric. Measures: transfer quality, ability to explain changes, spotting wrong AI advice, teacher time, share of wrong or unhelpful AI comments.
- The transfer task inside the app cannot stop a student from using another tool; for important marks the teacher may add a short in-class discussion.
- No market review has been done, so no claim of uniqueness is made.
- AI comments can be wrong or generic. Language versions (Kazakh, Russian, English) are a goal, not yet tested.
- Not implemented: working AI dialogue, LMS integration, document handling.

## Authors

Azamat Nagumanov, Kamil Bariev, Zhangir Yussupov, Alisher Berik. CSE-2604M AstanaItUniversity.

## AI-use disclosure

Claude & ChatGPT were used to structure the poster, draft the explanatory texts. The authors checked, edited and are responsible for the content.
