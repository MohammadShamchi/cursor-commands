Here’s a cleaned, company-neutral version of `documenter.md` you can drop in as-is 👇

SESSION WRAP-UP & DOCUMENTATION

We just finished a work session. Help me close it perfectly.

Topic we worked on today: [replace this with 1 short sentence, e.g. "Refactor login flow and improve error handling"]

Now do ALL of these automatically:

1. One-sentence summary of what we actually achieved / decided.

2. Problem Definition (2–4 bullet points max)

   - What was broken or missing before?
   - Why did it matter?
   - What was the root cause (if known)?

3. Final Solution / Outcome (3–6 bullet points)

   - What did we ship or decide?
   - Key implementation decisions
   - Any trade-offs we accepted

4. Suggest a session folder name

   - Format: `YYYY-MM-DD_short-kebab-case`
   - Example: `2025-11-26_login-flow-refactor`

5. Identify which file(s) are now the canonical source of truth

   - This can include plans, docs, or key implementation files
   - If none yet, say: `none – will be created next session`

6. Generate the full markdown content for a file called `SESSION_SUMMARY.md` with this exact structure (fill it with real content for THIS session):

   ```md
   # 2025-11-26 – Refactor login flow and improve error handling

   ## Goal / Problem

   - …

   ## What We Achieved

   - …

   ## Open Next Steps (if any)

   - …

   ## Canonical Files

   - `.ai/plans/login-flow-final.md`
   - `src/features/auth/login.tsx`

   ## Session Folder

   → `.ai/sessions/2025-11-26_login-flow-refactor`
   ```

- Use today’s date instead of `2025-11-26`.
- Use a short, meaningful title and folder name based on the topic and outcome.
- Replace example file paths with the real canonical files from this session.

7. After that, give me the exact bash commands to:

   - Create the session folder you suggested.
   - Save `SESSION_SUMMARY.md` into that session folder.
   - Move all today's “messy” working files (notes, scratch docs, logs, temporary task lists, etc.) into that session folder.

     - Use safe commands and common patterns (e.g. `*.md`, `*.txt`, `logs/`, `tasks/`) but clearly indicate where the user should adjust paths/patterns.

   - Move / promote the canonical files into appropriate long-term locations such as `.ai/plans/` or `docs/`.
   - (optional) Run `git add` and `git commit` with a message in the format:
     `"chore: close session – <short-session-name>"`

Do everything in one go. Make it clean, professional, and future-proof.
