# package-starter-kit

Contains starter kit for my npm packages

package.json has common structure each project should have. Just replace **starter-kit** on valid package name. And you are ready to go ;)

Projects should be created according to these rules:

1. Project name should be kebab-cased.

Example:

**superDuperProject** - wrong variant.

**super-duper-project** - correct variant.

2. Each project should be written on TypeScript.

No exclusions here.

3. Each project should have tests with 100% coverage.

And no exclusions here. Cause - no tests - no code ;).

4. Each project should contain in README documentation.

This documentation should be enough to understand when and how to use this project
without researching source code. All details, possible cases should be described in good fashion.

5. All modules in scope of package should be:
- camel-cased if module doesn't export class.
  If module contains specific functionality like one specific service, model and etc. it should have name of main exported method.
  If module contains common functionality like utilities, helpers and etc. it should have common descriptive name.

- pascal-cased if module exports class. It should have name of exported class.
