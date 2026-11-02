# Orcraft

Orcraft is the platform for test development and orchestration that lets you and your AI agents run the entire testing operation.

A plain-Python test framework gives suites a defined structure. A controller runs those suites from a GUI, the command line or a CI pipeline and collects the logs and results in one place. An endpoint application on each test machine lets the controller run tests there, so a run covers the local machine or a fleet of remote machines with the same suites.

Your AI agents work across all of them. They write suites in the framework's structure, run them on the machines registered in the controller and read the logs the runs leave behind. The person decides what to test, reviews what the AI agents wrote in the controller GUI, runs it and corrects it, unless the whole loop is handed to the AI agents and runs fully automated.

## This repository

The releases of Orcraft: each one carries the wheels of its version, one per platform, and the software bill of materials of the installed package. The same wheels are on [PyPI](https://pypi.org/project/orcraft/):

```
pip install --upgrade orcraft
```

Python 3.14 or newer, on Windows, Linux and macOS. The source code of Orcraft is proprietary and is not in this repository.

## First steps

- [Orcraft's Web Site](https://orcraft.app): what Orcraft is and its documentation.
- [Watch the demo](https://orcraft.app/demo/): see Orcraft in action.
- [Getting started](https://orcraft.app/setup/getting-started/): install the controller and run the first test.
- [Adding endpoints](https://orcraft.app/setup/endpoints/): run the endpoint application on your machines and register them in the controller.
- [Tutorial](https://orcraft.app/tutorial/): the framework, one feature at a time, with a [suite you can run](https://github.com/GMCoreAI/orcraft-test-suite-tutorial).
- [Framework reference](https://orcraft.app/framework/): every class, field and status of the framework.

## Support

Ask any question, report an issue, request a feature: support@orcraft.app. A vulnerability goes the way [SECURITY.md](SECURITY.md) describes.

## License

© 2026 GM Core Ltd. All rights reserved.
The Orcraft software is provided under the Orcraft Software License Agreement in [LICENSE](LICENSE); its source code is proprietary.
Orcraft™ is a trademark of GM Core Ltd. The Orcraft name, logo and branding assets are proprietary and may not be used without prior written permission.

## Website

https://orcraft.app
