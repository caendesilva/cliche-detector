## Design Specification: Cliche Detector Website

**1.  Overall Goal:**

Develop a simple, client-side website that helps users identify cliches in their writing.

**2.  User Interface (UI):**

*   **Layout:**
    *   Clean and minimalist design.
    *   A prominent textarea for text input.
    *   A "Check for Cliches" button below the textarea.
    *   A sidebar or panel to display detected cliches with corresponding line numbers.
*   **Responsiveness:**
    *   Ensure the layout adapts well to different screen sizes (desktop, tablet, mobile).

**3.  Functionality:**

*   **Cliche Detection:**
    *   Load a predefined list of cliches from a `cliches.yml` file located in the same directory as `index.html`.
    *   Implement case-insensitive matching.
    *   Normalize input text to handle variations in punctuation (e.g., `I’m` vs. `I'm`).
    *   Display detected cliches along with their line numbers in the designated output area.
*   **Performance Considerations:**
    *   Inform users that the application is client-side and large text inputs may impact performance or stability on low-powered devices.

**4.  Technical Requirements:**

*   **Languages:** HTML, CSS, JavaScript
*   **Libraries/Frameworks:** None
*   **Client-Side Execution:** All code, styles, and scripts reside within `index.html`.
*   **Data Source:** `cliches.yml` (YAML format)
*   **Data Normalization:**  Implement text normalization to ensure accurate cliche detection.

**5.  Content:**

*   **About Section:**
    *   Provide information about the purpose of the tool and how it works.
    *   Mention the use of AI models (OpenAI o1 Mini, Claude 3.5 Sonnet, Claude 3 Haiku, Gemini 1.5 Pro) in generating the cliche dataset.
    *   Explain the efforts made to ensure the dataset is gender-neutral and inoffensive.
    *   Include a disclaimer that the presence of cliches doesn't necessarily indicate poor writing.
    *   Optimize the content for search engines, targeting keywords like "cliche detector," "identify cliches," etc.
*   **Footer:**
    *   Acknowledge the use of a dataset with 1000+ cliches (link to the repository).
    *   Link to the source code on GitHub (github.com/caendesilva/cliche-detector [invalid URL removed]).
    *   Credit the creator (@CodeWithCaen on Twitter).

**6.  Additional Considerations:**

*   **Error Handling:** Implement appropriate error handling for file loading and processing.
*   **User Experience (UX):**  Strive for a user-friendly interface with clear instructions and feedback.
*   **Accessibility:** Follow accessibility best practices to make the site usable for everyone.

This design specification provides a comprehensive guide for developing the cliche detector website. It outlines the key features, technical requirements, and content guidelines to ensure a successful implementation.
