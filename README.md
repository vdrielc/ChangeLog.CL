# changelog.cl
The changelog.cl project

This project was born in my mind July 2017 when a change to a public API caused failure on multiple projects because we missed a change notification from the API developers.

The issue occured because the registered user for the API was a client and not the development team, the change notification emails go to the registered users and there was, at that time, no way to register anyone else for notifications. Sadly this particular notification ended up in the junk box and was entirely missed until integrations started failing.

The only real solution around this at the time was to monitor the API developers website for change notifications, which is time prohibitive or requires some for of scraping to check for changes and then implementing your own notification system. Sadly this issue will have a slightly different shape for each API, component or product you integrate with.

I've noticed many other items that experience changes over time that may affect a users decision to use or continue to use a product or item. It goes well beyond the world of IT and API's.

The changelog.cl domain was registered shortly after the original issue, but sadly I haven't had time to pursue this project till now.

This serves as a rough initial readme for the project, but changes will be made as progress is made on the concepts offline.

Initial Goals:
- Provide tooling for centrally managing and communicating functional changes to users
	- Central management is self hosted and can be entirely private
- Optional participation in a public change log	repository
- API for integrating change logs into systems
	- Both private and public repositories
- Provision for notification systems
	- UI components for notifying users of changes
- State management for changes, for example
	- Planned
	- Released
	- Pulled/Rolled back
- Plugin system for correctly sorting versions based on different schemes
	- Industries have their own standards for versioning
