### Release notes

<!-- Please add your release notes in the following format:
- My change description (#PR)
-->
- Update Python Worker Version to [4.29.0](https://github.com/Azure/azure-functions-python-worker/releases/tag/4.29.0)
- DotnetIsolated worker artifact clean up (#9976)
  - Move symbols from dotnet-isolated worker to symbols package
  - Removed linux executables from dotnet-isolated worker.
- Update Azure.Identity to 1.11.0 (#10002)
- Update Node.js Worker Version to [3.10.0](https://github.com/Azure/azure-functions-nodejs-worker/releases/tag/v3.10.0) (#9999)
- Update PowerShell worker 7.2 to [4.0.3220](https://github.com/Azure/azure-functions-powershell-worker/releases/tag/v4.0.3220)
- Update PowerShell worker 7.4 to [4.0.3219](https://github.com/Azure/azure-functions-powershell-worker/releases/tag/v4.0.3219)
- Ensuring proxies are disabled, with a warning, when running in Flex Consumption. 
- Fixed an issue leading to a race when invocation responses returned prior to HTTP requests being sent in proxied scenarios.
- Language worker channels will not be started during placeholder mode if we are in-process (#10161)
- Ordered invocations are now the default (#10201)
- Skip worker description if none of the profile conditions are met (#9932)
- Fixed incorrect function count in the log message.(#10220)
- Updated dotnet-isolated worker to [1.0.9](https://github.com/Azure/azure-functions-dotnet-worker/pull/2552) (#10262)
- Fix race condition on startup with extension RPC endpoints not being available. (#10255)
- Adding a timeout when retrieving function metadata from metadata providers (#10219)
- Upgraded the following package versions (#10287):
  - `Microsoft.Azure.WebJobs` updated to 3.0.41
  - `Microsoft.Azure.WebJobs.Host.Storage` updated to 5.0.1
  - `Microsoft.Extensions.Azure` updated to 1.7.1
  - `Azure.Storage.Blobs` updated to 12.19.1