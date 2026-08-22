# Contributing

Thanks for taking the time to contribute to Serial Studio. Bug reports, code, examples, and
documentation fixes are all welcome across every repository in the organization.

All contributors are expected to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Before you start

Check whether the repository you are working in has its own `CONTRIBUTING.md`. If it does,
that file is authoritative and this one only fills the gaps. The main
[Serial-Studio](https://github.com/Serial-Studio/Serial-Studio/blob/master/CONTRIBUTING.md)
repository has one, and it covers the build, the code style, and the test suite in detail.

For anything larger than a bug fix, open an issue or start a
[Discussion](https://github.com/Serial-Studio/Serial-Studio/discussions) before writing
code, so the approach is agreed on first.

## Reporting bugs

Open an issue with the bug report template. The report is most useful when it includes:

- Operating system and version
- The version of the software you are running, and which edition (GPL build, Trial, or Pro)
- Connection type, when relevant (UART, TCP/UDP, BLE, MQTT, Modbus, CAN Bus, USB, HID,
  Audio, Process)
- Steps to reproduce, what you expected, and what happened instead
- The project file (`.ssproj`) and console output when relevant

## Suggesting features

Open an issue with the feature request template. Describe the task you are trying to do,
not only the feature you have in mind; the underlying problem is often solvable in more than
one way.

## Submitting changes

1. Fork the repository and create a feature branch (`git checkout -b feature/my-change`).
2. Match the surrounding code style. Run whatever verification scripts the repository
   documents before you push.
3. Commit with descriptive messages.
4. Open a pull request using the template and make sure CI passes.

## Contributor License Agreement

Serial Studio is dual-licensed: GPLv3 for the open-source build, and a commercial license
for the Pro modules. Every source file carries an SPDX header stating which terms apply.

Because of that, contributions are accepted under a Contributor License Agreement. By
submitting a contribution you certify that it is your original work (or that you have the
right to submit it) and you grant Alex Spataru a perpetual, worldwide, royalty-free,
irrevocable, non-exclusive license to use, modify, distribute, sublicense, and relicense it
under both GPLv3 and the Serial Studio Commercial License.

The full text is in
[CONTRIBUTING.md](https://github.com/Serial-Studio/Serial-Studio/blob/master/CONTRIBUTING.md#contributor-license-agreement-cla)
in the main repository. Read it before opening your first pull request.

## Questions

Use [Discussions](https://github.com/Serial-Studio/Serial-Studio/discussions) for questions
and the [help center](https://serial-studio.com/help) for usage documentation.
