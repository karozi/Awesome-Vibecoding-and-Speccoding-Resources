# UI Prompts

* **Author**: [Karo Zieminski](https://karozieminski.substack.com/)

* **Last Updated**: November 2025

---

## 100 Most Common UI Elements For Vibecoders

A collection of prompts used to operationalize prompt and file generation:

* [100 Most Common UI Elements For Vibecoders](https://karozieminski.substack.com/p/prompt-pack-100-most-common-ui-elements-for-vibecoding) - A database cataloging 100+ common UI elements with ready-to-use vibecoding prompts for each one. It’s essentially a prompt library specifically designed for building interfaces with AI.

---

### Structure of Each Entry

* UI Element name (Button, Text Input, Modal, Chat Message, etc.)

* Category (Navigation, Input, Display, Feedback, Layout, Media, Interactive, Data)

* Description (what the element does)

* Complexity (Simple/Medium/Complex)

* Backend Required (Yes/No)

* Database Required (Yes/No)

* Vibecoding Prompt - Detailed, structured prompts covering frontend, backend, and database considerations

---

### Example

**Text Input Field**

```
Create a text input field for [email/name/search]. Requirements:
1) Frontend: Style with focus states, borders, proper padding
2) Add real-time validation with error messages
3) Include character counter if max length specified
4) Support placeholder text and labels
5) Implement debouncing for search inputs
6) Backend: Create validation endpoint if needed
7) Sanitize input to prevent XSS attacks
8) Database: Design table column with appropriate varchar length
```
---
