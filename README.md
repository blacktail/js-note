1. function's length property

2. function's name property

3. typeof obj == 'function' will result wrong when:

	- Firefox: Doing a typeof on the HTML <object> element yields an inaccurate "function" result, instead of "object" as we might expect..
	- Internet Explorer: When attempting to find the type of a function that was part of another window (such as an iframe) that no longer exists, its type will be reported as 'unknown'.
	- Safari: Safari considers a D OM NodeList t o be a function.So: typeof document.body.childNodes == "function".
