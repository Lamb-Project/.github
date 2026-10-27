# LAMB: Learning Assistants Manager and Builder

**Bring generative AI into your institution's LMS.** Teachers create RAG assistants and rubric-based pre-assessment activities; the institution manages access, model providers and data.

<div align="center">

[![Website](https://img.shields.io/badge/Website-lamb--project.org-blue)](https://lamb-project.org/en/)
[![License](https://img.shields.io/badge/license-GPL%20v3-blue.svg)](https://github.com/Lamb-Project/lamb/blob/main/LICENSE)
[![Safe AI in Education](https://img.shields.io/badge/Safe_AI_Education-Manifesto-green)](https://manifesto.safeaieducation.org)
[![GitHub](https://img.shields.io/badge/GitHub-Lamb--Project-black)](https://github.com/Lamb-Project/lamb)

[📚 **Guides (LAMB 0.8)**](https://lamb-project.org/en/guides/0.8/) ·
[👩‍🏫 Teaching](https://lamb-project.org/en/teaching/) ·
[🏛️ Institutions](https://lamb-project.org/en/institutions/) ·
[👨‍💻 Developers](https://lamb-project.org/en/developers/) ·
[🔬 Research](https://lamb-project.org/en/research/)

</div>

**LAMB** is free software (GNU GPL v3) created by Marc Alier and Juanan Pereira at the Universitat Politècnica de Catalunya (UPC) and the Universidad del País Vasco (UPV/EHU). It integrates into the institutional LMS through LTI (Moodle, Canvas and other LTI-capable platforms), so AI activities live inside the courses teachers and students already use.

## What LAMB does

### 🎓 RAG assistants built around your course
Retrieval-augmented generation brings relevant passages from your own teaching materials into an assistant's answers. Create an assistant, connect its sources and make it available inside your LMS through LTI.
[Create your first assistant →](https://lamb-project.org/en/guides/0.8/first-assistant/) · [Add your course materials →](https://lamb-project.org/en/guides/0.8/knowledge/)

### 📝 PRE: rubric-based pre-assessment
Create assistants that apply a rubric to student work and propose feedback. The teacher reviews the result and decides how it is used in assessment.
[Explore PRE →](https://lamb-project.org/en/teaching/#rubric-based-pre-assessment-pre)

### 🔍 Testing and evaluation
Use test cases, saved results and activity analysis to inspect responses, find weaknesses and assess changes before you publish.
[Test and evaluate an assistant →](https://lamb-project.org/en/guides/0.8/testing/)

### 🤖 LAMB LEGATUS: an agent that works for the teacher
An agent built into LAMB, with tools for LAMB and your Moodle course, your account's permissions and an approval step the model cannot skip. It helps you create and improve assistants, build and run tests, and prepare knowledge bases from your course. Changes wait for your approval. No additional Moodle plugin is required: the connector uses standard Moodle web services.
[Meet LAMB LEGATUS →](https://lamb-project.org/en/guides/0.8/legatus/) · [Connect LAMB and Moodle →](https://lamb-project.org/en/guides/0.8/moodle/)

## For institutions

- **Your AI, under your rules.** Choose where inference runs: your own infrastructure or supported cloud providers. Manage access, provider choices and data handling as part of your AI governance and GDPR work (LAMB provides the controls; compliance also depends on your policies and deployment).
- **The last mile for your AI.** Your LMS knows who is enrolled, in which course and with which role; LAMB learns it through LTI. The organization sets the rules and each teacher's allowance, teachers set limits and a timetable per course, and each student gets a personal key for their own tools, with every key's use counted.
  [How the last mile works →](https://lamb-project.org/en/guides/0.8/llm-access/)
- **Free software you can inspect and adapt.** Licensed under GNU GPL v3.
- **Plan adoption with us.** Training, demonstrations, pilot design and deployment planning: [training and consultancy →](https://lamb-project.org/en/contact/)

[Install LAMB on your own servers →](https://lamb-project.org/en/guides/0.8/installation/)

## For developers

Build tools on the same institutional foundation: public APIs, a tool template and development utilities.

| Project | What it is |
|---|---|
| [lamb](https://github.com/Lamb-Project/lamb) | The LAMB platform |
| [lamb-tool-template](https://github.com/Lamb-Project/lamb-tool-template) | Sample LTI-enabled tool that uses an authorized LAMB assistant |
| [lamb-lti-test-tool](https://github.com/Lamb-Project/lamb-lti-test-tool) | Exercise LTI launches, roles and grade return during development |
| [moodle-cli](https://github.com/Lamb-Project/moodle-cli) | Python CLI for the Moodle web services API |
| [lamb-cli](https://github.com/Lamb-Project/lamb/tree/main/lamb-cli) | Manage assistants, materials, tests and analytics from the terminal |
| [lamb-evals](https://github.com/Lamb-Project/lamb-evals) | Evaluation framework for LAMB's LLM responses |

Contributions are welcome: see [Contribute to LAMB](https://lamb-project.org/en/developers/contribute/).

## 🎓 Research & academic foundation

LAMB is studied and written about with research groups at UPC, UPV/EHU, the Universidad de Salamanca and the Universidad de Alicante (EduSTEAM, ONEKIN, GRIAL, Smart Learning), and adheres to the **[Safe AI in Education Manifesto](https://manifesto.safeaieducation.org)**.
[Research groups & publications →](https://lamb-project.org/en/research/)

### 📚 Cite LAMB

**"LAMB: An open-source software framework to create artificial intelligence assistants deployed and integrated into learning management systems"**

- **Authors:** Marc Alier, Juanan Pereira, Francisco José García-Peñalvo, Maria Jose Casañ, Jose Cabré
- **Journal:** Computer Standards & Interfaces, Volume 92, March 2025
- **DOI:** [10.1016/j.csi.2024.103940](https://doi.org/10.1016/j.csi.2024.103940)

### 🏛️ Academic Partners

- **Universidad del País Vasco (UPV/EHU)** - Research institution and development partner
- **Universitat Politècnica de Catalunya (UPC)** - Research institution and development partner
  - Barcelona School of Informatics
  - Institut de Ciències de l'Educació - ICE
  - Department of Service and Information System Engineering (ESSI)

### 🙏 Acknowledgments

Special thanks to the **Open WebUI Project**, **Tsugi Project** (Dr. Chuck Severance), **TEEM Conference** community, and **Tknika** Basque VET Applied Research Centre for their support and collaboration.

---

Looking for your course assistant? Your teacher or institution provides access through your course: [start here as a student](https://lamb-project.org/en/students/).
