# Course AI Template

Use this template to give instructors and students a shared way to work with AI in a course.
It covers preparation, live teaching, study, practice, and review. The official syllabus and
instructor directions govern when students may use AI.

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

The guides are Markdown and can be read on GitHub or in a text editor. With a tool that loads
`AGENTS.md`, work in the course repository and name the material you want to use. With other
tools, supply the root guide, the directory guide, and the relevant released material.

## Choose a guide

| Guide | Use it for |
| --- | --- |
| [Course guide](AGENTS.md) | Sources of authority, learning workflow, and assessment boundaries |
| [Lecture guide](lectures/AGENTS.md) | Preparing for class, studying released material, or assisting a live class |
| [Assignment guide](assignments/AGENTS.md) | Hints, feedback, and solution study when permitted |
| [Past-assessment guide](exams/AGENTS.md) | Aligned review questions, timed practice, and released solutions |

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
