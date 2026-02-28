# Sprint 1 – Functional & Non-Functional Requirements

## Functional Requirements (FR)

| ID   | Requirement Description | Notes / Ethical Considerations |
|------|------------------------|-------------------------------|
| FR-1 | The system shall allow users to answer 3–5 daily self-reported questions. | - |
| FR-2 | The system shall collect daily data related to sleep, work hours, mood, and rest. | - |
| FR-3 | The system shall allow users to skip daily input without penalty. | User-friendly |
| FR-4 | The system shall store user responses with timestamps. | Data tracking |
| FR-5 | The system shall automatically clean and preprocess collected data. | Data integrity |
| FR-6 | The system shall compute derived features such as sleep score and mood trends. | - |
| FR-7 | The system shall handle missing or incomplete data gracefully. | Robustness |
| **FR-8** | The system shall generate a burnout risk score based on user inputs. | Informational only, not diagnostic |
| **FR-9** | The system shall update the burnout risk score when new data is entered. | Timely updates |
| **FR-10** | The system shall use machine-learning models to estimate burnout risk trends. | Ethical ML use |
| FR-11 | The system shall track daily engagement streaks for each user. | Engagement |
| FR-12 | The system shall reset streaks after multiple consecutive missed days. | - |
| FR-13 | The system shall visually display streak information on the dashboard. | UX-focused |
| FR-14 | The system shall allow users to add trusted profiles (friends or family). | Consent-based |
| FR-15 | The system shall allow users to enable or disable weekly summary sharing. | User control |
| FR-16 | The system shall share only aggregated trend summaries with trusted profiles. | Privacy-focused |
| FR-17 | The system shall generate weekly well-being summaries. | - |
| FR-18 | The system shall highlight high-level trends such as improvement or decline. | Clear communication |
| FR-19 | The system shall restrict weekly summaries to authorized viewers only. | Security |
| FR-20 | The system shall provide an interactive dashboard for users. | Usability |
| FR-21 | The system shall display charts for mood, sleep, and burnout risk trends. | Visualization |
| FR-22 | The system shall allow users to view historical data over time. | Tracking progress |
| FR-23 | The system shall allow users to pause data collection. | User control |
| FR-24 | The system shall allow users to delete or reset their profile data. | Privacy-first |
| FR-25 | The system shall allow users to write short educational or personal articles. | - |
| FR-26 | The system shall allow users to select article visibility (women-only or public). | Privacy options |
| FR-27 | The system shall categorize articles by topic (well-being, beauty, career, startup, etc.). | Organization |
| FR-28 | The system shall perform basic content validation before publishing articles. | Content responsibility |
| FR-29 | The system shall display published articles in a community feed. | Visibility |
| FR-30 | The system shall allow users to edit or delete their own articles. | User control |

## Non-Functional Requirements (NFR)

| ID   | Requirement Description | Notes / Ethical Considerations |
|------|------------------------|-------------------------------|
| **NFR-1** | The system shall ensure all data sharing is consent-based. | Privacy-first |
| **NFR-2** | The system shall not provide medical diagnoses or professional advice. | Ethical boundaries |
| NFR-3 | The system shall securely store and process user data. | Security |
| NFR-4 | The system shall be easy to use for non-technical users. | Usability |
| NFR-5 | The system shall present insights in clear, non-alarming language. | Ethical communication |
| NFR-6 | The article interface shall support simple and distraction-free writing. | UX |
| NFR-7 | The system shall update burnout risk scores within a reasonable time after data entry. | Performance |
| NFR-8 | The system shall function reliably across multiple sessions. | Reliability |
| NFR-9 | The system shall be modular and well-documented for future enhancements. | Maintainability |
| NFR-10 | The system shall use version control for all source code. | Collaboration |
| NFR-11 | Articles shall be experience-based and non-diagnostic. | Ethical responsibility |
| NFR-12 | The system shall allow authors to remain anonymous if desired. | Privacy |
| NFR-13 | Users shall retain full control over article visibility settings. | User control |
