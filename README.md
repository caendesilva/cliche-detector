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

---

## Sample Text for The Cliche Detector

```
It was the best of times, it was the worst of times. The calm before the storm had settled over the city, but everyone knew it wouldn't last.

He was caught between a rock and a hard place, with no easy way out.

She was the apple of his eye, but their relationship was on the rocks.

He decided to take the bull by the horns and face his problems head-on.

In the end, good triumphed over evil, proving that what goes around comes around.

He knew he had to make a decision, but he was afraid of making the wrong choice.

After all, hindsight is 20/20.

He thought about it long and hard, but he was still at a crossroads.

Finally, he decided to follow his heart.

He knew it wouldn't be easy, but he was determined to make the best of a bad situation.

And as the sun set on the horizon, he took a deep breath and stepped into the unknown.
```
