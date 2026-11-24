# AWS Networking Lab

An offline-first visual learning portal for building AWS cloud networking foundations.

## Open locally

Open `index.html` directly in a browser, or serve this folder with any static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Included curriculum

- Course shell with progress tracking stored in local browser storage.
- 60 lessons across seven modules, from networking fundamentals to enterprise AWS design.
- Four-step active learning loop for every lesson: orient, trace, decide, recall.
- Animated visual path across client, DNS, network edge, policy, and service boundaries.
- Prediction questions with immediate feedback for every lesson.
- Practice prompts for CIDR plans, route matrices, security-group matrices, hybrid connectivity, DR, and architecture reviews.
- Replay, keyboard shortcuts, responsive navigation, and dark theme.

The modules are:

1. Networking foundations
2. AWS VPC core
3. Application architectures
4. Enterprise networking
5. Hybrid connectivity
6. Advanced architecture
7. Expert practice

The portal is intentionally dependency-free so it can run offline. Lesson content lives in the `curriculum` data structure in `app.js`.
