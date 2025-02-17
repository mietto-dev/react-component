## 1. React + TypeScript: Building a Dynamic Form Component

**Problem Statement:**
Create a dynamic form component in React using TypeScript. The form should:

- Accept a JSON configuration as a prop to dynamically render form fields (e.g., text inputs, dropdowns, checkboxes).
- Validate inputs based on rules provided in the JSON configuration (e.g., required fields, minimum length, regex patterns).
- Display validation errors dynamically as the user types or submits the form.
- Use TypeScript interfaces to define the shape of the JSON configuration and form data.

**Example JSON Configuration:**

```json
[
  {
    "type": "text",
    "name": "firstName",
    "label": "First Name",
    "required": true,
    "minLength": 2
  },
  { "type": "email", "name": "email", "label": "Email", "required": true },
  {
    "type": "select",
    "name": "country",
    "label": "Country",
    "options": ["USA", "Canada", "UK"],
    "required": true
  }
]
```

**Evaluation Criteria:**

- Proper use of TypeScript interfaces/types.
- Clean, reusable, and modular React component design.
- Efficient state management and validation logic.
- Handling of edge cases (e.g., empty inputs, invalid formats).

---
