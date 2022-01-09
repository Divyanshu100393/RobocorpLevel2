# Template: Standard Robot Framework

Want to get started using [Robot Framework](https://robocorp.com/docs/languages-and-frameworks/robot-framework/basics) this is the simplest template to start from.

This template robot:

- Uses [Robot Framework](https://robocorp.com/docs/languages-and-frameworks/robot-framework/basics) syntax.
- Includes all the necessary dependencies and initialization commands (`conda.yaml`).
- Provides a simple task template to start from (`tasks.robot`).

## Learning materials

- [All docs related to Robot Framework](https://robocorp.com/docs/languages-and-frameworks/robot-framework)

## Some Points about code

- For embedding the screenshot in same page as order details I tried the 'Add Watermark Image To Pdf' but it always resulted in error. I suppose it's a bug affecting multiple users.
- Locally setting up vault works perfectly for me, but for the requirement "Verify that it is possible to run your robot without manual setup" I'm not sure whether it'll work perfectly or not as I was not able to find a way to give dynamic path value for vault.json.
