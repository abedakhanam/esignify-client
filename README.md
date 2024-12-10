## Frontend:
#### Framework:
- Next.js (v14.2.15): Provides server-side rendering (though only CSR is used) and static generation for improved performance and scalability.

#### Programming Language:
- TypeScript (v5.6.3): Enforces type safety, reducing runtime errors, and improving maintainability.
Styling:
- Tailwind CSS (v3.4.1): A utility-first CSS framework, enabling faster UI development with pre-defined classes.

#### PDF Handling:
- react-pdf (v7.7.0): Renders PDFs in the browser.
- pdf-lib (v1.17.1): Manipulates PDF documents (e.g., embedding fields, signatures).
- @react-pdf-viewer/core (v3.12.0): Provides advanced PDF viewing functionalities.

#### State Management:
- Local state with React hooks (useState, useReducer) is leveraged since no global state management is required.

#### Utilities:
- axios (v1.7.7): For HTTP requests to the backend.
- react-dnd & react-draggable: Enable drag-and-drop functionality for placing fields on PDFs.
- react-hot-toast: For user notifications (e.g., errors, success messages).