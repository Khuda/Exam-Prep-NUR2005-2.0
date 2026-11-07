# NUR2005 Exam Prep

A static, client-side revision website for NUR2005 Applied Pathophysiology and Pharmacology.

## Included

- Eight topic sections covering the complete supplied exam-plan scope.
- 50 tricky "most correct answer" MCQs per topic: 400 questions total.
- Dedicated skin-treatment, mental-health and poisons/envenomation coverage.
- 20 multi-step medication-calculation problems with worked solutions.
- Short-answer clinical-reasoning prompts.
- Mixed mock-exam mode and local browser progress tracking.

## Run locally

```bash
python3 -m http.server 3000
```

Open `http://localhost:3000`.

## GitHub Pages

Upload the contents of this ZIP to a repository, commit to `main`, then open **Settings → Pages**. Select **Deploy from a branch**, choose `main`, and choose the `/ (root)` folder. Save and wait for GitHub Pages to publish.

The site has no server or database dependency. Progress is stored in each learner's browser using `localStorage`.

## Educational note

This is a revision aid based on the supplied NUR2005 materials. It does not replace your TAFE learning resources, medication policies, MIMS/local protocols or advice from your teacher and pharmacist. Always follow the prescribed order and local policy for real medication administration.
