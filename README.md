# 📋 Trello Task ID

- [ ] **RSS-SE-##** (Task ID / Trello Card)
- [x] **No ID** (Final release: develop → main)

# ⚡️ Summary

Merge the `develop` branch into `main` for the final release of the **Swagger/OpenAPI UI** application. This PR encompasses the complete implementation of the REST client and API specification editor according to the project requirements.

---

1. **Task:** [Swagger/OpenAPI UI Task](https://github.com/rolling-scopes-school/tasks/blob/master/react/modules/tasks/final.md)
2. **Deployment:** https://swagger-editor-app-gmt.vercel.app/en/home
3. **Demo Video:** https://youtu.be/MxXD0E_D5gs
4. **Done:** `13.07.2026` / **Deadline:** `13.07.2026`
5. **Score: 550 / 550**

### 🏆 Evaluation Criteria (550 max)

- **Feature 1: App Header (60/60)**
  - [x] Non-authenticated users see Sign In and Sign Up buttons in the header's upper right corner. (15)
  - [x] Authenticated users see History and Sign Out buttons in the header's upper right corner. (10)
  - [x] Navigation link to About page is available in header and footer. (10)
  - [x] If the token is expired/invalid, the user is redirected from private routes to the Main page. (10)
  - [x] Pressing the Sign In / Sign Up button redirects to the route with the respective form. (15)

- **Feature 2: Sign In / Sign Up (50/50)**
  - [x] Buttons for Sign In / Sign Up / Sign Out are present everywhere they should be. (10)
  - [x] Client-side validation is implemented (email format, password strength: min 8 chars, at least one letter, one digit, one special character, Unicode supported). (20)
  - [x] Upon successful login, the user is redirected to the Main page. (10)
  - [x] If the user is already logged in and tries to reach Sign In / Sign Up routes, they are redirected to the Main page. (10)

- **Feature 3: Swagger Editor (120/120)**
  - [x] Loading/pasting OpenAPI/Swagger schema in JSON and YAML formats is supported. (25)
  - [x] Auto-detection of input format (JSON vs YAML) is implemented. (20)
  - [x] Format switching with automatic conversion (JSON ↔ YAML) works correctly. (20)
  - [x] Schema validation with error indication is implemented. (15)
  - [x] Authenticated users can save schemas; the saved schema is automatically restored in the editor upon next login. (10)
  - [x] The Viewer automatically populates with endpoints when the schema is valid. (10)
  - [x] Responsive split view adjusts based on screen orientation (horizontal/vertical). (20)

- **Feature 4: Swagger Viewer (120/120)**
  - [x] Endpoint list is displayed with organization by path/method. (20)
  - [x] Endpoint details show method, path, and all parameter types (path, query, header, cookie). (25)
  - [x] Request schema and example payloads are displayed. (20)
  - [x] Response schema, examples, and all supported status codes are displayed. (25)
  - [x] Try-It-Out functionality allows filling parameters, headers, and body; executing requests; and displaying responses. (20)
  - [x] Generate cURL button with copy-to-clipboard functionality is implemented. (10)

- **Feature 5: History and Analytics (70/70)**
  - [x] History and analytics is server-side generated and shows an informational message with links to the editor/viewer when there are no requests in the database. (15)
  - [x] Requests are displayed sorted by timestamp (most recent first). (10)
  - [x] The following analytics are recorded from the server side and displayed: request duration, response status code, request timestamp, request method, request size, response size, error details, endpoint/URL. (45)

- **Feature 6: About Page (25/25)**
  - [x] About page is accessible to all users (public route). (5)
  - [x] About page contains information about the RS School course. (5)
  - [x] About page contains team member information (names, roles, GitHub links). (10)
  - [x] About page design is consistent with the application design. (5)

- **Feature 7: General Requirements (55/55)**
  - [x] Multiple (at least 2) languages are supported with an i18n toggler in the header. (30)
  - [x] Sticky header with animation when it becomes sticky is implemented. (10)
  - [x] Errors are displayed in a user-friendly format. (10)
  - [x] Private routes are properly protected (401 if not authenticated). (5)

- **Feature 8: YouTube Video (50/50)**
  - [x] A 5–7 minute YouTube video is linked in the pull request demonstrating all implemented features. (50)

### ⛔ Penalties (0 points applied)

- [ ] No forbidden frameworks used.
- [ ] No `@ts-ignore` or code-smells present.
- [ ] Test coverage meets the required thresholds.
- [ ] Lazy-loaded routes are implemented correctly.
- [ ] No unexpected console errors/warnings/logs.
- [ ] ESLint, Prettier, and Husky git hooks are properly configured.
- [ ] Custom favicon is set.
- [ ] Commit history and PR guidelines followed correctly.
