# Course AI Template

Use this template to give instructors and students a shared way to work with AI in a course.
It covers preparation, live teaching, study, practice, and review. The official syllabus and
instructor directions govern when students may use AI.

## Who uses which files

- **Instructors and TAs** use this README to set up the course repository. If they release past
  questions, they use the [past-assessment index](exams/README.md) to map them to course topics.
- **Students** use the course README to find the syllabus, course materials, and example prompts.
  They use the past-assessment index to find questions on topics they have covered.
- **AI assistants** follow the root `AGENTS.md` and the guide for the material in use.

## What the AI tool reads

Codex loads `AGENTS.md` files from the repository root through its starting directory by default.
For example, starting in `assignments/` loads the root guide and `assignments/AGENTS.md`.
If you start at the root, name the file you want to use so the assistant can open the matching
guide. [Codex documentation](https://learn.chatgpt.com/docs/agent-configuration/agents-md#how-codex-discovers-guidance)

The assistant reads the syllabus, lecture notes, and problems as needed. Name the files you want
it to use or attach them. If your tool requires you to supply instructions manually, attach or
paste the root guide and the relevant directory guide along with the released material.

| Instruction file | What it tells the assistant |
| --- | --- |
| [Course guide](AGENTS.md) | Sources of authority, learning workflow, and assessment boundaries |
| [Lecture guide](lectures/AGENTS.md) | How to support class preparation, study, and live teaching |
| [Assignment guide](assignments/AGENTS.md) | When and how to give hints, feedback, and solutions |
| [Past-assessment guide](exams/AGENTS.md) | How to choose aligned questions and run timed practice or solution study |

## Set up a course repository

1. Select **Use this template** on GitHub. For an existing course repository, copy the instruction
   files into their corresponding directories and use the setup steps below to update your README.
2. Replace the title and introduction with your course name and description. Add links to the
   current syllabus, AI-use and assessment policies, released materials, and announcements.
3. Review the [course guide](AGENTS.md) and the directory guides. Adapt the vocabulary, permitted
   sources, disciplinary conventions, and workflows to your course. Update links and instructions
   if you rename or omit a directory.
4. Add only materials cleared for the repository audience. Populate the
   [past-assessment index](exams/README.md) if you release past questions.
5. Try one student request and one instructor request using released material. Check that the
   assistant cites the right files and follows the relevant guide and course policy.

## Example requests

Replace the backticked placeholders with released filenames, headings, or problem numbers.

- **Prepare.** Help me prepare for `<lecture file>`. Check my recall of the prerequisites and give
  me time to try the preparation questions.
- **Study.** Help me understand `<heading>` in `<lecture file>`. Use the course's terminology and
  give me a short follow-up question to try on my own.
- **Practice.** Help me with `<problem>` in `<practice file>`. Read the assigned material and
  start with a strategic hint.
- **Review.** Choose released past questions aligned with `<topics>`. Keep solutions closed
  while I attempt them.
- **Teach.** Start an instructor session for `<lecture file>`. Track what I confirm we cover and
  wait for my approval before changing course files.
