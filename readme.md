# GPT Integration Folder

## Purpose

Centralize AI outputs (ChatGPT, Claude, LM Studio) and project docs. Target: 20% manual, 80% AI-generated drafts for efficient workflow.

## Tasks

- [ ] Organize folder structure for AI outputs and downloads.
- [ ] Edit files to match tested workflows.
- [ ] Create GitHub repos per project category.
- [ ] Break milestones into actionable GitHub tasks.
- [ ] Polish and publish repos.
- [ ] Share profile link for easy collaboration.

### Bonus

- [ ] Build a reusable README template.
- [ ] Document finalized workflows.
- [ ] Automate file organization for new downloads.
- [ ] Schedule bi-weekly folder reviews.
- [ ] Test sharing workflows with collaborators.

## Roadmap

- [ ] Create AI Workflow folder and subfolders (Claude, ChatGPT, LM Studio).
- [ ] Add data for each AI.
- [ ] Create readme/roadmap per AI domain.
- [ ] Download and configure GitKraken for repo management.
- [ ] Push folders to GitHub.
- [ ] Install JetBrains IDEs.
- [ ] Create project folders (`MacJunkins/projects/project-domain`).
- [ ] Export Linear data to CSV; convert to markdown via LM Studio.
- [ ] Split markdown into GitHub/Obsidian issues.
- [ ] Transfer Apple Notes to Obsidian; separate dev and family tasks.
- [ ] Use MS To Do or OneNote for family tasks.
- [ ] Delete unused repos/projects; move active ones to `MacJunkins/projects/project_name`.

---

## Recommended Model

> Nous Hermes 2 Mistral 7B (Q6_K or Q8_0)

- Instruction-following, reasoning, structured docs.
- Fast, fits 24GB RAM.

### Alternatives

- **OpenHermes 2.5 Mistral 7B:** Concise, good for summaries.
- **MythoMax L2 13B (Q4_K_M/Q5_K_M):** Creative, narrative-heavy docs.
- **Deepseek Coder 6.7B:** Code-focused planning.

### Quantization

- **Q6_K:** Best balance for 24GB RAM.
- **Q8_0:** Max quality, higher memory use.
- Avoid Q4 for complex reasoning.

### Get Models

- LM Studio model browser
- [TheBloke’s Hugging Face](https://huggingface.co/TheBloke)

### Setup Flow

1. Open LM Studio, browse models.
2. Download "Nous Hermes 2 Mistral" (Q6_K).
3. Enable system prompts.
4. Use chat templates for markdown docs.
