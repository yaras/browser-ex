# browser-ex
Browser tools and extensions

---

## Greasemonkey

### redmine-toggl-button.user.js

Dodaje przycisk na redmine, który startuje zadanie na Toggl

Konfiguracja:
- ustawić zmienne w skrypcie:
```
var toggl_api_key = 'x'; // DO UZUPEŁNIENIA
var toggl_workspace_id = 1; // DO UZUPEŁNIENIA
```
wartości można znaleźć w https://www.toggl.com/api/v8/me
- opcjonalnie ustawić mapowanie projektów redmine &raquo; toggl (zmienna `projects`), np.
```
var projects = {
	'MyProject': 12345
};
```
Id projektów można pobrać przez link: https://www.toggl.com/api/v8/workspaces/{workspace_id}/projects
