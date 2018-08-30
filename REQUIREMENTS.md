WordPress core provides an internal API, or library, of functions for issuing server-side HTTP
requests. However, that API is pretty basic and leaves a lot to be desired. In this exercise, your
mission is to build a few enhancements around the HTTP request server-side API for
WordPress

The requirements for this API to be written in PHP are as follows:
● Caches identical HTTP requests for a default of 5 minutes.
● Logs HTTP errors and request times in a performant and secure manner.
● Uses modern PHP standards and language features.
● Extensible via WordPress actions and filters.
● Distributable as a Composer package.
● Provide a README for developers that wanting to integrate this library into projects.
Consider different levels of experience and the range of use cases they may need to
address.