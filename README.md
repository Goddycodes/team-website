# Team Name: Lab 2 Website

**Live site:** https://goddycodes.github.io/team-website/

## Team
| Name             | Registration no. | GitHub username |
|------------------|------------------|-----------------|
| Godfrey Mark     |  COM/3492/26     |   Goddycodes    |
| Shalom Equistine |  COM/7193/26     |   Shammycodes   |

## Who drove each part
- Part 0, 2, 4: Godfrey Mark
- Part 1, 3: Shalom Equistine

## Personalisation
- Our colours: #2b9474 #3c6274
- Projects we added: Team Website Repository, Android App Analysis
- Extension challenge(s) completed: E1 Add a fourth page

## Reflection
1. Using a <div> instead of a <button> would remove built-in keyboard support, so users could not easily activate the menu using the Tab, Enter, or Space keys. It would also reduce accessibility because screen readers would not automatically identify it as a button, making navigation more difficult for people with disabilities.
2. Without defer, the browser would execute the JavaScript before the HTML elements are fully loaded. As a result, the script might not find elements like the navigation menu, dark mode button, or contact form, causing interactive features to fail.
3. If innerHTML were used with visitor-provided input, someone could insert malicious HTML or JavaScript into the page. Using textContent prevents this by displaying the text exactly as entered instead of treating it as HTML, improving security.
4. Client-side JavaScript can be disabled or bypassed, so it cannot be trusted on its own. The server must validate the data again to ensure it is complete, correct, and safe before storing or processing it.
5. The theme is stored in the browser's localStorage, which is separated by origin. A file opened directly from the computer (file://) and the same file served through Live Server (http://127.0.0.1:5500) have different origins, so they do not share the same stored data.
6. The navigation bar and footer are repeated across all the HTML pages. This duplication makes maintenance harder because every change must be made in multiple files, increasing the chance of inconsistencies. In larger projects, this can be avoided by using templates, server-side includes, or reusable components.

