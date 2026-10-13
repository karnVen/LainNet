# 🌐 LainNet Synchronous Push & Session State Rule

**Scope**: Repository `karnVen/LainNet` and all Networking learning workflows.  
**Rule Type**: Behavioral Constraint & Pre-Push Invariant.

---

## 🎯 MANDATORY PRE-PUSH WORKFLOW (Before EVERY `git push`)

Whenever preparing to commit and push changes to `karnVen/LainNet`, AI-bou and any coding assistant **MUST strictly execute these steps before pushing**:

1. **Update `README.md`**:
   - Update the **"📍 Where We Are Right Now (Active Milestone)"** table with the exact current status of the active episode, topic, and lab files.
   - Update the **"Current Sprint Status"** badge or summary counter (e.g. `[5 / 24 Episodes Mastered]`).
   - If new labs or assets were added, register them in the **"📦 Hands-on Labs & Artifacts"** section.

2. **Update `SESSION_STATE.md`**:
   - Record today's achievements in **Today's Achievements & Work Log**.
   - Set the precise **Resume Point for Next Session** (next episode URL, upcoming lab target, core concepts).
   - Add new Socratic questions to test the user's comprehension.

3. **Verify Git Hygiene**:
   - Ensure temporary files (like Zone.Identifier, OS caches) are excluded via `.gitignore`.
   - Stage, commit with a semantic commit message (e.g., `feat(ep04): complete real-life packet encapsulation and boson faq`), and push to `origin main`.
