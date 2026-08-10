# Bargain Moulding Academy

Collaborative rebuild of the Bargain Moulding employee training and certification site.

## Current prototype

- Door School, Moulding School, and PVC School
- 8-step locked lesson progression per school
- 80% quiz requirement represented in the prototype flow
- Local device progress persistence via `localStorage`
- SOP School with English / Español switching
- Qoblex terminology intentionally remains in English
- Responsive mobile and desktop layout
- Architecture ready for a later centralized progress/authentication phase

## Run locally

No package install is required.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Collaboration workflow

Use short-lived feature branches and pull requests. Keep `main` deployable. Vercel preview deployments can be used for review before merging.

## Planned next phase

1. Replace prototype lesson copy with approved source content and five-question quizzes.
2. Add final certification exams and manager practical sign-off.
3. Add employee authentication and centralized progress tracking.
4. Add manager reporting for certifications, attempts, and practical evaluations.
5. Store approved SOP source documents securely rather than in the public web bundle.
