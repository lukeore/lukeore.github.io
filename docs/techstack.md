---
title: Tech Stack
---
## Lists
### Test
- [behave](https://github.com/behave/behave)
- [pytest](https://docs.pytest.org/)
- [gcov](https://gcc.gnu.org/onlinedocs/gcc/Gcov.html) - code coverage collection for use during test execution
- [wireshark / tshark](https://www.wireshark.org/) - network capture and dissector. Can be used in automated test by calling tshark. Also possible to open pipes, and so custom capture application scan be created to feed packets into Wireshark for dissection. Written a few plug-ins for dissection when required.

### Build
- west
- cmake
- make

### Documentation
- [behave](https://github.com/behave/behave) - living requirements documentation
- [mermaid](https://mermaid.js.org/) - for diagrams in markdown documentation
- [hedgedoc](https://docs.hedgedoc.org/) - markdown based multi-user documentation system (I like the look of this but not used it yet, currently just use markdown)
- [lcov](https://github.com/linux-test-project/lcov) - for unit test report generation
- [strctdoc](https://github.com/strictdoc-project/strictdoc) - going full-bore on the requirements traceability? This open source tool is being used by the [zephyr project](https://docs.zephyrproject.org/latest/safety/safety_overview.html#) in it's search for IEC 61508 compliance.

