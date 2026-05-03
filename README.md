# FirstAngularApp

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 21.2.9.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Copilot CLI Settings

- Project settings: `.github/copilot-settings.json`
- Cloud agent bootstrap: `.github/workflows/copilot-setup-steps.yml`
- MCP plugins/servers: `.vscode/mcp.json`

## Deploy to GitHub Pages

This app can be deployed as a repository site (`https://<user>.github.io/<repo>/`) using GitHub Actions.

1. In repository settings, set **Pages** source to **GitHub Actions**.
2. Push to the repository default branch (or run the workflow manually) to trigger `.github/workflows/deploy-pages.yml`.
3. The workflow builds a static artifact, sets `base-href` to `/<repo>/`, and deploys it to Pages.
4. On the first run, open **Actions** and confirm both `build` and `deploy` jobs succeed, then use the `github-pages` environment URL.
5. If `Setup Pages` fails with `Resource not accessible by integration`, ensure Pages is enabled once in **Settings → Pages → Build and deployment → GitHub Actions**.

For local verification, run:

```bash
npm run build:pages -- --base-href "/<repo>/"
```
