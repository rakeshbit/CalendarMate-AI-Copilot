# CalendarMate AI Copilot & Sub-Agent Workflows

CalendarMate is an autonomous AI Copilot designed for Technical Program Managers to manage calendar operations and delegate context-processing tasks to specialized sub-agents.

## 🚀 Architecture Overview
- **Calendar Mate Agent (Parent)**: Handles scheduling, availability checks, event updates, and delegates sub-tasks.
- **Meeting Notes Consolidator Agent (Sub-Agent)**: Processes transcripts from Google Drive and generates HTML email digests.
- **Email Summarizer Agent (Sub-Agent)**: Summarizes email chains, categorizes priority, and logs digests to Google Sheets and Gmail.

## 📁 Repository Structure
- `workflows/`: Contains sanitized n8n workflow JSON exports.
- `docs/`: Presentation slides (`presentation.pdf`).
- `assets/`: System visual diagrams and output execution snapshots.

## 📸 Output Snapshots
### Workflow Execution
![CalendarMate Workflow](assets/execution-outputs/calendar-mate-execution.png)

### Generated Email Digest
![Email Digest](assets/execution-outputs/meeting-notes-digest-output.png)

## 🛠️ How to Import Workflows
1. Download the `.json` files from the `workflows/` directory.
2. Open your n8n instance and click **Import from File**.
3. Re-link your Google Calendar, Drive, Sheets, and Gmail credentials.# CalendarMate-AI-Copilot
CalendarMate is an autonomous AI Copilot designed for Technical Program Managers to manage calendar operations and delegate context-processing tasks to specialized sub-agents.
