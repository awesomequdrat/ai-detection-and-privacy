# AI Detection and Privacy

> Final group project for **ITIS 4353 — Social Technology Design**, Fall 2024, UNC Charlotte.

**AI Detection and Privacy** is a human-centered browser-extension project designed to help users identify potentially AI-generated content while giving them more control over privacy, notifications, and detection sensitivity.

The project explores the intersection of **artificial intelligence, misinformation, online trust, privacy, user experience, and human-computer interaction**.

## Research Question

**How can we design an intuitive tool that helps users detect AI-generated content while protecting their privacy?**

## Problem

AI-generated text, images, videos, and deepfakes can make it harder for people to judge whether online content is authentic. Existing detection tools can also be too technical, require users to upload content to third-party services, or provide limited privacy controls.

This project investigated how a more accessible, integrated, and privacy-conscious experience could help everyday users make better-informed decisions online.

## Proposed Solution

The team designed and developed a Chrome browser-extension concept/prototype that combines AI-content detection with user-facing privacy and customization controls.

### Key Features

- **Real-time detection notifications** for potentially AI-generated content
- **Adjustable detection sensitivity**
- **Privacy Mode** to reduce data collection
- **Notification preferences**, including pop-up and sound options
- **Detection history**
- **Educational resources** explaining AI-generated content and its implications
- **Reporting workflow** for potentially malicious AI use

## Design and Development Process

1. **Research** — Reviewed AI-detection, misinformation, and privacy challenges.
2. **Feature selection** — Prioritized notifications, Privacy Mode, and sensitivity controls.
3. **UX prototyping** — Designed user flows and interfaces in Figma.
4. **Browser-extension development** — Used Chrome APIs to implement the project prototype.
5. **Usability testing** — Collected feedback from users with different levels of technical experience.
6. **Iteration** — Identified onboarding, notification clarity, discoverability, and performance improvements.

## Tools and Technologies

- **Figma** — Interface design and prototyping
- **Chrome APIs** — Browser-extension functionality
- **HTML / CSS / JavaScript** — Core extension interface files described in the final report
- **User testing** — Evaluation of usability, comprehension, and privacy controls
- **Literature review** — Research on AI detection, privacy, misinformation, and trust

## Usability Testing

The project report documents testing with **4 participants**:

- 2 beginner users
- 2 advanced users

Participants completed tasks involving AI-content detection, sensitivity settings, Privacy Mode, and notification interpretation.

### Reported Results

| Metric | Result |
| --- | --- |
| Average time to detect AI content | 4 seconds |
| Sensitivity-setting task | 100% successful |
| Detection pop-up interpretation | 100% successful |
| Privacy Mode activation | 100% successful |

### User Feedback

Positive feedback emphasized the clean interface, customizable sensitivity, and Privacy Mode.

Challenges included:

- Some first-time notification wording was unclear
- The sensitivity slider could be easier to find
- Older devices experienced slight browser slowdown

Suggested improvements included a short onboarding tutorial and clearer, more actionable notifications.

## Limitations

- AI-detection accuracy can vary by content type and platform.
- More advanced AI-generated media may be increasingly difficult to detect.
- Browser performance may be affected on older or slower devices.
- First-time users may need additional onboarding and guidance.
- Detection tools themselves can potentially be misused.

## Future Work

Potential next steps identified by the project include:

- Improve detection accuracy and reduce false positives/negatives
- Support emerging and multimodal AI-generated content
- Expand to mobile platforms and additional browsers
- Integrate more closely with social platforms such as Instagram and YouTube
- Add multilingual support
- Improve user education and onboarding
- Add feedback mechanisms to help refine detection behavior

## Course Context

This project was completed as the semester-long collaborative research project for **ITIS 4353 — Social Technology Design**. The course emphasized human-centered computing, UX research and design, social technologies, privacy, research ethics, misinformation, trust, and safety.

## Team

**Tech Titans**

- Qudrat Siyal
- Abdul Mohamad
- Joshua Huffman
- Yaz Obuliraja Parimala

Because this was a collaborative academic project, the repository preserves full team credit.

## Repository Contents

```text
ai-detection-and-privacy/
├── README.md
├── PROJECT_NOTES.md
├── .gitignore
├── docs/
│   ├── AI-Detection-and-Privacy-Report.pdf
│   └── AI-Detection-and-Privacy-Presentation.pdf
└── src/
    └── README.md
```

- [Final Project Report](docs/AI-Detection-and-Privacy-Report.pdf)
- [Final Presentation](docs/AI-Detection-and-Privacy-Presentation.pdf)
- [`src/README.md`](src/README.md) explains which source files are referenced by the report but were not included in the uploaded materials used to assemble this repository.

## Project Status

**Academic project / prototype**

The final report describes a functional Chrome extension built with core files such as `manifest.json`, `popup.html`, `popup.css`, and `popup.js`. Those original source files were not included in the materials used to prepare this GitHub package, so this repository currently focuses on the project documentation.

If the original extension source code is recovered, it can be added to the `src/` directory.

## Academic Integrity and Attribution

This repository is intended as a portfolio record of a **team project**, not as a claim of sole authorship. Individual contributions should be described accurately if a personal-contributions section is added later.
