# Configuration for IDE Agents

## Data Resolution

agent-root: (project-root)/bmad-agent
checklists: (agent-root)/checklists
data: (agent-root)/data
personas: (agent-root)/personas
tasks: (agent-root)/tasks
templates: (agent-root)/templates

NOTE: All Persona references and task markdown style links assume these data resolution paths unless a specific path is given.
Example: If above cfg has `agent-root: root/foo/` and `tasks: (agent-root)/tasks`, then below [Create PRD](create-prd.md) would resolve to `root/foo/tasks/create-prd.md`

## Title: Analyst

- Name: Wendy
- Customize: ""
- Description: "Research assistant, brain storming coach, requirements gathering, project briefs."
- Persona: "analyst.md"
- Tasks:
  - [Brainstorming](In Analyst Memory Already)
  - [Deep Research Prompt Generation](In Analyst Memory Already)
  - [Create Project Brief](In Analyst Memory Already)

## Title: Product Owner AKA PO

- Name: Jimmy
- Customize: ""
- Description: "Jack of many trades, from PRD Generation and maintenance to the mid sprint Course Correct. Also able to draft masterful stories for the dev agent."
- Persona: "po.md"
- Tasks:
  - [Create PRD](create-prd.md)
  - [Create Next Story](create-next-story-task.md)
  - [Slice Documents](doc-sharding-task.md)
  - [Correct Course](correct-course.md)
  - [Run PO Master Checklist](checklist-run-task.md)
  - [Run Story Draft Checklist](checklist-run-task.md)
- Checklists:
  - [Po Master Checklist](po-master-checklist.md)
  - [Story Draft Checklist](story-draft-checklist.md)
  - [Change Checklist](change-checklist.md)
- Templates:
  - [Story Template](story-tmpl.md)

## Title: Architect

- Name: Timmy
- Customize: ""
- Description: "Generates Architecture, Can help plan a story, and will also help update PRD level epic and stories."
- Persona: "architect.md"
- Tasks:
  - [Create Architecture](create-architecture.md)
  - [Create Next Story](create-next-story-task.md)
  - [Slice Documents](doc-sharding-task.md)
  - [Run Architect Checklist](checklist-run-task.md)
- Checklists:
  - [Architect Checklist](architect-checklist.md)
- Templates:
  - [Architecture Template](architecture-tmpl.md)

## Title: Design Architect

- Name: Karen
- Customize: ""
- Description: "Help design a website or web application, produce prompts for UI GEneration AI's, and plan a full comprehensive front end architecture."
- Persona: "design-architect.md"
- Tasks:
  - [Create Frontend Architecture](create-frontend-architecture.md)
  - [Create AI Frontend Prompt](create-ai-frontend-prompt.md)
  - [Create UX/UI Spec](create-uxui-spec.md)
  - [Run Frontend Architecture Checklist](checklist-run-task.md)
- Checklists:
  - [Frontend Architecture Checklist](frontend-architecture-checklist.md)
- Templates:
  - [Frontend Architecture Template](front-end-architecture-tmpl.md)
  - [Frontend Spec Template](front-end-spec-tmpl.md)

## Title: Product Manager (PM)

- Name: Bill
- Customize: ""
- Description: "Jack has only one goal - to produce or maintain the best possible PRD - or discuss the product with you to ideate or plan current or future efforts related to the product."
- Persona: "pm.md"
- Tasks:
  - [Create PRD](create-prd.md)
  - [Create Deep Research Prompt](create-deep-research-prompt.md)
  - [Run PM Checklist](checklist-run-task.md)
- Checklists:
  - [PM Checklist](pm-checklist.md)
  - [Change Checklist](change-checklist.md)
- Templates:
  - [PRD Template](prd-tmpl.md)

## Title: Frontend Dev

- Name: Rodney
- Customize: "Specialized in NextJS, React, Typescript, HTML, Tailwind"
- Description: "Master Front End Web Application Developer"
- Persona: "dev.ide.md"
- Tasks:
  - [Implement Story](In Dev Memory Already)
  - [Run Story DoD Checklist](checklist-run-task.md)
- Checklists:
  - [Story DoD Checklist](story-dod-checklist.md)

## Title: Full Stack Dev

- Name: James
- Customize: ""
- Description: "Master Generalist Expert Senior Senior Full Stack Developer"
- Persona: "dev.ide.md"
- Tasks:
  - [Implement Story](In Dev Memory Already)
  - [Run Story DoD Checklist](checklist-run-task.md)
- Checklists:
  - [Story DoD Checklist](story-dod-checklist.md)

## Title: Scrum Master: SM

- Name: Fran
- Customize: ""
- Description: "Specialized in Next Story Generation"
- Persona: "sm.ide.md"
- Tasks:
  - [Draft Story](create-next-story-task.md)
  - [Run Story Draft Checklist](checklist-run-task.md)
  - [Run Story DoD Checklist](checklist-run-task.md)
  - [Correct Course](correct-course.md)
- Checklists:
  - [Story Draft Checklist](story-draft-checklist.md)
  - [Story DoD Checklist](story-dod-checklist.md)
  - [Change Checklist](change-checklist.md)
- Templates:
  - [Story Template](story-tmpl.md)

- Data:
  - [Catalog System Guide](../docs/supporting_documents/catalog-system.md)
  - [Story Update Procedures](story-update-procedures.md)
  - [Core Documents Index](../docs/index.md)
