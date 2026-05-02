# IdeaForge Postman Documentation

This folder contains ready-to-import Postman files for the IdeaForge MERN SaaS API.

## Files

- `IdeaForge.postman_collection.json` - grouped API collection with endpoint descriptions and sample request bodies.
- `IdeaForge.render.postman_environment.json` - production environment using `https://crmideaforge.onrender.com`.

## Quick Import

1. Open Postman.
2. Click `Import`.
3. Import both JSON files from this folder.
4. Select the `IdeaForge Render Production` environment.
5. Run `Authentication > Register User` or `Authentication > Login User` first.
6. Postman will store the HTTP-only `jwt` cookie automatically for protected routes.

## Publishing Documentation

1. Open the imported `IdeaForge MERN SaaS API` collection.
2. Click the collection menu.
3. Select `View documentation`.
4. Use `Publish` or `Share` depending on your Postman workspace settings.

## Notes For Evaluation

- Protected APIs require the login cookie.
- Google Gmail and Calendar APIs require Google OAuth login first.
- IDs such as `projectId`, `taskId`, `teamId`, and `meetingId` should be copied from create/list responses into the environment variables.
- The collection documents authentication, projects, tasks, teams, meetings, dashboard, reports, notifications, search, Gmail, Calendar, and Google OAuth APIs.
