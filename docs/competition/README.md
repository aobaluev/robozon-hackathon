# Competition

# Competition Documentation

This directory contains all documentation related to the hackathon requirements, official clarifications, evaluation criteria, assumptions, and submission process.

The purpose of this section is to maintain a **single source of truth** for the competition requirements and to avoid losing important information scattered across the Telegram chat and other communication channels.

---

## Documentation Structure

| Document                                                         | Description                                                                     | Status |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------- | ------ |
| [requirements.md](requirements/requirements.md)                               | Original competition requirements and task description                          | 🚧     |
| [requirements_clarifications.md](requirements_clarifications.md) | Official answers from organizers, summarized and grouped by topic               | 🚧     |
| [constraints.md](constraints.md)                                 | Technical and organizational constraints identified during the project          | 🚧     |
| [assumptions.md](assumptions.md)                                 | Engineering assumptions made where official clarification is unavailable        | 🚧     |
| [evaluation_criteria.md](evaluation_criteria.md)                 | Competition judging criteria and practical interpretation                       | 🚧     |
| [submission.md](submission.md)                                   | Deliverables, repository structure, required artifacts and submission checklist | 🚧     |

---

# Recommended Reading Order

New team members are recommended to read the documents in the following order:

1. **requirements.md**
2. **requirements_clarifications.md**
3. **constraints.md**
4. **assumptions.md**
5. **evaluation_criteria.md**
6. **submission.md**

---

# Engineering Workflow

```text
Official Task
        │
        ▼
Requirements
        │
        ▼
Official Clarifications
        │
        ▼
Constraints
        │
        ▼
Engineering Assumptions
        │
        ▼
Architecture Decisions (ADR)
        │
        ▼
Implementation
```

---

# Relationship with Other Documentation

This directory contains only **competition-related documentation**.

Project-specific engineering decisions are documented separately:

* `../decisions/`

Research materials, architecture documentation, CAD files, firmware, electronics, software, datasets and experiments are maintained in their respective directories.

---

# Document Status

| Status | Meaning         |
| ------ | --------------- |
| 🚧     | Draft           |
| ✅      | Complete        |
| 🔄     | Under Review    |
| ❗      | Requires Update |

---

# Contributing

Whenever organizers publish new information:

1. Update **requirements_clarifications.md**
2. Update **constraints.md** if any restrictions changed.
3. Update **assumptions.md** if previous assumptions become invalid.
4. Create or update an Architecture Decision Record (ADR) if the clarification affects the implementation.

Keeping these documents synchronized significantly reduces project risks and simplifies future development.
