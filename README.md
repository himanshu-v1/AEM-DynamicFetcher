# AEM Dynamic Fetcher Script

This is a custom logic that can be applied to any AEM project. With this logic:
- Architechture becomes more flexible due to decoupling of tight predefined dependency between templates and component clientlibs
- Templates no more loads with a pre-defined set of code, instead template clientlibs are no more the main thing
- This breaks down component clientlib to component level and call them real time only when required, makes page loads faster
- mitigate the risks: Application no longer breaks with even a single error in a component. Risk is mitigated to just that component.
- Improved web core vitals when you have less code to load initially.

_Note: Script is production ready, code has not been published due to confidentiality purpose._
