# scto-Ethiopian Date Picker SurveyCTO Field Plug-in

A high-quality field plug-in for SurveyCTO that provides an intuitive date picker supporting both Gregorian (GC) and Ethiopian (EC) calendars with automatic conversion between them.

## Features

- **Dual Calendar Support**: Toggle between Gregorian and Ethiopian calendars
- **Interactive Calendar Grid**: Visual calendar for easy date selection
- **Dropdown Selectors**: Month, day, and year dropdowns for precise input
- **Automatic Conversion**: Seamless conversion between GC and EC dates
- **Responsive Design**: Works on various screen sizes including mobile devices
- **Accessibility**: Keyboard navigation and screen reader support
- **SurveyCTO Integration**: Full integration with SurveyCTO's field plug-in system

## Default SurveyCTO feature support

| Feature | Support |
|---------|---------|
| Data types | Text |
| Required response | Yes |
| Custom label | Yes |
| Read only | Yes |
| External app integration | No |
| External data collection | No |
| Audio audit | No |

## Installation

1. Download the plug-in files:
   - `template.html`
   - `style.css`
   - `script.js`
   - `manifest.json`

2. Upload the files to your SurveyCTO server or include them in your form's media files.

3. In your SurveyCTO form, add a text field and set its appearance to use this plug-in.
4. ### Option 2: Download ZIP File

1. [Download the complete field plug-in package](ethiopian-date-picker.fieldplugin.zip)

2. Extract the ZIP file and upload the contents to your SurveyCTO server or include them in your form's media files.

3. In your SurveyCTO form, add a text field and set its appearance to use this plug-in.

## Usage

1. The plug-in defaults to Gregorian calendar.
<img width="824" height="868" alt="image" src="https://github.com/user-attachments/assets/15fe12a9-dc45-498c-bfbf-c5ebc094ed8e" />
2. Use the toggle switch to switch between Gregorian (GC) and Ethiopian (EC) calendars.
<img width="825" height="862" alt="image" src="https://github.com/user-attachments/assets/8c70c0f8-7af9-4b05-be5d-8efe7984a3a8" />

3. Select dates using the dropdown selectors or by clicking on the calendar grid.
<img width="824" height="868" alt="image" src="https://github.com/user-attachments/assets/2b355b1f-660d-414c-8ec1-8f5c8b05cef9" />

4. The selected date is automatically converted and displayed in both calendars.
<img width="820" height="861" alt="image" src="https://github.com/user-attachments/assets/88b0b80c-3c03-4fbb-90bf-261605005402" />

5. Data is stored in JSON format including both calendar representations.

## Data Storage

The plug-in stores data in the following JSON format:

```json
{
    "date": "2024-01-15",
    "calendar": "gregorian",
    "display": "January 15, 2024",
    "gc_date": "January 15, 2024",
    "ec_date": "5 ጥር 2016"
}
```

## Supported Field Types

- `text`

## Requirements

- SurveyCTO platform
- Modern web browser with JavaScript enabled

## Customization

The plug-in can be customized by modifying the CSS in `style.css` to match your survey's theme.

## License

This plug-in is provided as-is for use with SurveyCTO.

## Author

Dagem Feleke
