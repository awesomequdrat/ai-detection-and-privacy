# AI Detection and Privacy

> Final group project for **ITIS 4353 — Social Technology Design**, Fall 2024, UNC Charlotte.

**AI Detection and Privacy** is a human-centered browser extension project designed to help users identify potentially AI-generated content while giving them greater control over privacy, notifications, and detection sensitivity.

The project explores the intersection of **artificial intelligence, misinformation, online trust, privacy, user experience, and human-computer interaction (HCI)**.

## Research Question

**How can we design an intuitive tool that helps users detect AI-generated content while protecting their privacy?**

## Problem

AI-generated text, images, videos, and deepfakes can make it increasingly difficult for people to determine whether online content is authentic.

Many existing AI-detection tools can also be too technical for everyday users, require content to be uploaded to third-party services, focus on only one type of media, or provide limited privacy controls.

This project investigated how a more accessible, integrated, and privacy-conscious solution could help users make better-informed decisions while interacting with online content.

## Proposed Solution

Our team designed and developed a Chrome browser extension prototype that combines AI-content detection with user-facing privacy and customization controls.

The goal was to make AI detection easier to understand and use while maintaining a strong focus on transparency, user control, and privacy.

### Key Features

- **Real-time detection notifications** for potentially AI-generated content
- **Adjustable detection sensitivity**
- **Privacy Mode** to reduce unnecessary data collection
- **Notification preferences**, including pop-up and sound options
- **Detection history**
- **Educational resources** explaining AI-generated content and its implications
- **Reporting options** for potentially malicious AI-generated content

## Design and Development Process

1. **Research** — Investigated challenges involving AI-generated content, misinformation, privacy, and existing detection tools.
2. **Feature Selection** — Identified key functionality including AI-detection notifications, Privacy Mode, sensitivity controls, and notification preferences.
3. **UX Prototyping** — Designed user flows and interfaces in Figma.
4. **Browser Extension Development** — Built the Chrome extension prototype using Chrome APIs and web technologies.
5. **Usability Testing** — Evaluated the interface with users with different levels of technical experience.
6. **Iteration** — Used feedback to identify improvements to onboarding, notification clarity, feature discoverability, and performance.

## Tools and Technologies

- **Figma** — UX/UI design and interactive prototyping
- **Chrome APIs** — Browser extension functionality
- **HTML** — Extension interface structure
- **CSS** — Interface styling
- **JavaScript** — Extension behavior and interactions
- **User Testing** — Usability and feature evaluation
- **Literature Review** — Research on AI detection, privacy, misinformation, trust, and human-centered computing

## My Contributions

This was a collaborative team project. My personal contributions included:

- **Figma Design and Prototyping** — Designed and developed interface concepts and user flows for the AI-detection experience.
- **Chrome Extension Development** — Worked on coding and implementing the browser extension using Chrome extension technologies.
- **Usability Testing** — Helped conduct and evaluate usability testing to understand how users interacted with detection notifications, sensitivity settings, and Privacy Mode.
- **Report Writing** — Contributed to documenting the research problem, methodology, resulting solution, testing findings, limitations, and future directions in the final project report.
- **Final Presentation** — Contributed to developing and presenting the project's research, prototype, findings, and proposed future improvements.

These responsibilities gave me hands-on experience connecting **HCI and UX principles with software development, privacy, responsible AI, and user research**.

## Usability Testing

The project included usability testing with **4 participants with different levels of technical experience**:

- 2 beginner users
- 2 advanced users

Participants completed tasks involving:

- Detecting AI-generated content
- Adjusting detection sensitivity
- Activating Privacy Mode
- Understanding AI-detection notifications

### Reported Results

| Metric | Result |
| --- | --- |
| Average time to detect AI content | 4 seconds |
| Sensitivity-setting task | 100% successful |
| Detection pop-up interpretation | 100% successful |
| Privacy Mode activation | 100% successful |

### User Feedback

Participants responded positively to the clean interface, customizable sensitivity settings, and Privacy Mode.

Testing also identified several opportunities for improvement:

- Some first-time notification wording was unclear
- The sensitivity slider could be easier to discover
- Older devices experienced slight browser slowdown
- New users could benefit from additional onboarding guidance

Suggested improvements included a short onboarding tutorial and clearer, more actionable notifications.

## Design Implications

The project highlighted several important human-centered design considerations for AI systems:

- Users should be given understandable information rather than only an AI-generated score.
- Privacy controls should be visible and understandable.
- AI-detection systems should communicate uncertainty rather than encouraging users to blindly trust detection results.
- Customization can help accommodate different user preferences and levels of technical knowledge.
- AI tools should support users in making informed decisions rather than attempting to make decisions entirely for them.

## Limitations

Several limitations were identified during the project:

- AI-detection accuracy may vary depending on content type and platform.
- Increasingly advanced AI-generated media may become more difficult to detect.
- False positives and false negatives remain important challenges for AI-detection technologies.
- Browser performance may be affected on older or slower devices.
- First-time users may require additional onboarding and guidance.
- Detection technologies themselves may potentially be misused.

## Future Work

Potential future improvements include:

- Improve AI-detection accuracy and reduce false positives and false negatives
- Support emerging and multimodal AI-generated content
- Expand compatibility to additional browsers
- Develop mobile support
- Integrate more closely with platforms such as Instagram and YouTube
- Add multilingual support
- Improve educational resources and onboarding
- Develop clearer explanations for detection results
- Add user-feedback mechanisms to improve the detection experience
- Continue evaluating privacy, transparency, and user trust

## Course Context

This project was completed as the semester-long collaborative research project for:

**ITIS 4353 — Social Technology Design**  
**UNC Charlotte — Fall 2024**

The course focused on **User Experience (UX), Human-Centered Computing (HCC), social computing, privacy, research ethics, misinformation, trust, safety, and the relationship between people and technology**.

The project allowed us to apply these concepts to a contemporary challenge involving AI-generated content.

## Team

### Tech Titans

- **Qudrat Siyal**
- Abdul Mohamad
- Joshua Huffman
- Yaz Obuliraja Parimala

This repository represents a collaborative academic project and preserves credit for all members of the original project team.

## Repository Contents

```text
ai-detection-and-privacy/
├── README.md
├── AI-Detection-and-Privacy-Report.pdf
└── AI-Detection-and-Privacy-Presentation.pdf
