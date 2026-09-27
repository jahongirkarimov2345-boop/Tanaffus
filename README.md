# Tanaffus

AI grading assistant for schools and universities. Tanaffus reads photos of student work and online answers, suggests scores and feedback, fills the gradebook and writes reports. Nothing reaches students until the teacher approves it.

**Live demo:** https://claude.ai/artifact/PXzj3B3To8KYni1VtnyBNh

## Try it

Open the live demo and press **Try the teacher demo**, or log in with one of these demo accounts:

| Role | Username | Password |
|---|---|---|
| Teacher (Malika Karimova, maths, 7-A, 7-B, 8-A) | `malika` | `teacher123` |
| Student (Aziz Tursunov, 7-B) | `aziz` | `student123` |
| Student (Dilnoza Rahimova, 7-B) | `dilnoza` | `student123` |
| School (deputy director) | `director` | `admin123` |

## Features

- **Snap & Grade:** photograph paper work or collect answers online; QR answer sheets match papers to students.
- **Trust Lights:** every AI suggestion is green, yellow or red by confidence, so teachers know what to check first.
- **Review and approve:** by question or by student, with blind review, a consistency check and one-tap "approve all green".
- **Feedback Studio:** feedback can be made shorter or warmer, or translated into Oʻzbekcha, Русский or English.
- **Mistake Radar:** the class's top mistakes after each set, with a 5-minute re-teach plan and practice sent to students.
- **Gradebook and attendance:** approved grades fill the gradebook; attendance by quick command ("absent Aziz, late Bekzod").
- **Reports:** class and school reports as PDF or CSV, parent notes, and a simulated eMaktab export.
- **Three roles:** teachers, students and school administrators each see only what they need.

## How it runs

Tanaffus is a single self-contained file, `index.html`, with no build step and no server.

- Demo data is generated in the browser and saved to the visitor's `localStorage`. Nothing is shared between visitors.
- In the Claude artifact viewer, Tanaffus can use live AI through the viewer's own Claude account. Everywhere else, including GitHub Pages, it uses the built-in demo AI: rules for typed answers and known answers for sample scans.
- To host it with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

Prototype for Case A: Smarter Teacher Workflow. All names and grades are demo data.
