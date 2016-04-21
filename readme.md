#Offline RD-SCORM-Player

Electro project to run RD SCORM material, offline.

To add lessons:

1. Copy your lesson(s) to the `src/courses/` folder.
2. Add the required entries to `src/courses.js`.

To test:

1. Run `npm install` to install required dependencies (you only need to run this command once).
2. Run `npm start`.

To build and pack (with asar):

- For Windows, run `npm run build-win`.
- For Mac, run `npm run build-mac`.

To build without packing:

- For Windows, run `npm run build-win-no-pkg`.
- For Mac, run `npm run build-mac-no-pkg`.

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

## Branding

To change the aspect of the main window, just edit the files `src/branding/style.css`

