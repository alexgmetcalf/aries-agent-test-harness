# Aries Interoperability Testing Overview


This web site shows the current status of Aries Interoperability.

The latest interoperability test results are provided below. Each item is for a test runset, a combination
of Aries agents and frameworks running a subset of the overall tests in the repository. The subset of tests
run represent the set of tests expected to be supported by the combination of components being tested.

The following test agents are currently included in the runsets:

- [Aries Cloud Agent Python](https://github.com/hyperledger/aries-cloudagent-python) (ACA-Py)
- [Aries Framework .NET](https://github.com/hyperledger/aries-framework-dotnet) (AF-.NET)
- [Aries Framework - JavaScript](https://github.com/hyperledger/aries-framework-javascript) (AF-JS)
- [Aries Framework Go](https://github.com/hyperledger/aries-framework-go) (AF-Go)

Want to add your Aries component to this page? You need to add a runset to the
[Aries Agent Test Harness](https://github.com/hyperledger/aries-agent-test-harness).

## Summary

|   #   | Runset Name     | Scope | Results |
| :---- | :-------------- | ----- | ------: |
| 1 | [ACA-PY to AF-Go](./acapy-afgo.md) | AIP 2.0 RFC0023 Only | **0 / 5** (0%) |
| 2 | [ACA-PY to AF-.NET](./acapy-dotnet.md) | AIP 1.0 except proof proposals | **25 / 25** (100%) |
| 3 | [ACA-PY to AF-JS](./acapy-javascript.md) | AIP 1.0 except revocation | **15 / 30** (50%) |
| 4 | [ACA-PY to ACA-Py](./acapy.md) | AIP 1.0, AIP 2.0 (RFC0023 Only) | **41 / 41** (100%) |
| 5 | [AF-Go to AF-Go](./afgo.md) | AP 2.0 RFC0023 Only | **3 / 5** (60%) |
| 6 | [AF-.NET to AF-.NET](./dotnet.md) | AIP 1.0 except revocation and proof proposals | **13 / 13** (100%) |
| 7 | [AF-JS to AF-.NET](./javascript-dotnet.md) | AIP 1.0 except revocation and proof proposals | **12 / 13** (92%) |
| 8 | [AF-JS to AF-JS](./javascript.md) | AIP 1.0 except revocation | **17 / 18** (94%) |

*Results last updated: Fri Mar 5 14:31:59 PST 2021*

