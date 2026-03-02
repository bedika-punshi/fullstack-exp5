
# fullstack-exp5
🧪 Experiment 5.1: Component Lazy Loading using React.lazy and Suspense
📌 Aim
To optimize frontend performance by implementing lazy loading of components in a Single Page Application using React.lazy() and Suspense.
🛠 Software Requirements
Node.js
React (Vite)
React Router DOM
VS Code
Web Browser

📚 Theory
Lazy loading is a performance optimization technique in which components are loaded only when they are required. In React, React.lazy() is used to dynamically import components and Suspense is used to display fallback UI while the component is loading.
This reduces the initial bundle size and improves application performance by loading components only when the user navigates to them.

⚙️ Procedure
Created a React application using Vite.
Installed React Router DOM.
Created multiple components (Home, About, Contact).
Applied lazy loading using React.lazy().
Wrapped components inside Suspense.
Introduced 5-second delay using setTimeout() to demonstrate loading behavior.
Navigated between routes to observe lazy loading.

▶️ Output
Initially, no lazy-loaded component is rendered.
On clicking navigation links, fallback UI (Loading...) appears.
Corresponding component loads after 5 seconds.
Initial bundle size is reduced.
<img width="1512" height="982" alt="Screenshot 2026-03-02 at 10 47 11 AM" src="https://github.com/user-attachments/assets/75cd71a4-55ba-4376-891a-772aeef24776" />
<img width="1512" height="982" alt="Screenshot 2026-03-02 at 10 47 17 AM" src="https://github.com/user-attachments/assets/34a87a3a-71af-4c0a-a38f-4c1fd5beb946" />
<img width="1512" height="982" alt="Screenshot 2026-03-02 at 10 48 08 AM" src="https://github.com/user-attachments/assets/b8c920bc-513e-4785-830f-bf3783c39153" />



🧾 Result
Component-level lazy loading was successfully implemented using React.lazy() and Suspense, improving performance by dynamically loading components only when required.

🏁 Conclusion
Lazy loading helps improve frontend performance by reducing the initial loading time of the application and loading components dynamically during navigation.

---------exp5.2   ROUTE LAZY LOADING ---------

🧪 Experiment 5.2: Route-Based Lazy Loading in SPA
📌 Aim
To implement route-based lazy loading to improve performance in a Single Page Application.

🛠 Software Requirements
Node.js
React (Vite)
React Router DOM
VS Code
Web Browser

📚 Theory
Route-based lazy loading ensures that components associated with specific routes are loaded only when the user navigates to that route.
Using React.lazy() and Suspense, page components are dynamically imported during navigation instead of being loaded initially. This reduces the initial bundle size and speeds up application startup time.

⚙️ Procedure
Created a new React application using Vite.
Installed React Router DOM.
Created multiple page components (Dashboard, Profile, Settings).
Applied lazy loading to route components using React.lazy().
Wrapped routes inside Suspense.
Added a 5-second delay using setTimeout() to simulate loading.
Navigated between routes to observe route-based lazy loading.

▶️ Output
Initially, Landing page loads.
Page components are not included in initial bundle.
When navigating to Dashboard/Profile/Settings, fallback UI is displayed.
Corresponding page loads after 5 seconds.

<img width="1512" height="982" alt="Screenshot 2026-03-02 at 10 57 15 AM" src="https://github.com/user-attachments/assets/e1a83bb0-c405-4437-bb9a-85dd3b2bbf9b" />
<img width="1512" height="982" alt="Screenshot 2026-03-02 at 10 57 21 AM" src="https://github.com/user-attachments/assets/6995d908-3e77-4220-8b44-17f11c2d6380" />
<img width="1512" height="982" alt="Screenshot 2026-03-02 at 10 57 29 AM" src="https://github.com/user-attachments/assets/709d9429-d5a8-40e7-9cfe-c56e31f1bc4d" />
<img width="1512" height="982" alt="Screenshot 2026-03-02 at 10 57 39 AM" src="https://github.com/user-attachments/assets/a6e9d004-e01d-4d38-9819-8502d4aefc61" />

🧾 Result
Route-based lazy loading was successfully implemented, dynamically importing page components only when the associated route was accessed.

🏁 Conclusion
Route-based lazy loading enhances application performance by reducing initial load time and dynamically loading route-specific components during navigation in a Single Page Application.
