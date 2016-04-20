#Offline RD-SCORM-Player

Electro project to run RD SCORM material, offline.

To add lessons:

2. Copy your lesson(s) to the `src/courses/` folder.
3. If `courses.js` doen't exist, create it by copying `src/courses.sample.js`.
4. Add the required entries to `src/courses.js`.

To test:

1. Run `npm install` to install required dependencies (you only need to run this command once).
2. Run `npm start`.

To build:

- For Windows, run `npm run build-win`.
- For Mac, run `npm run buld-mac`.

## Example `src/courses.js`

```javascript
LMS.courses = [

	{
		id: "uxns",
		name: "Unidos Por Niños Saludables"
	},

	{
		id: "nutrir",
		name: "Nestlé Nutrir"
	}

];
```