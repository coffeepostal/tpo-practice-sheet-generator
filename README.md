# Teach Piano Online - Practice Sheet Generator and Random Measure Generator
The Practice Sheet Generator and Random Measure Generator are tools for teachers to create practice resources for their students.

## Dependencies
- [VueJS](https://www.vuejs.org): JavaScript framework and form handling
- [jsPDF](https://github.com/MrRio/jsPDF): for the PDF generation
- [html2canvas](https://github.com/niklasvh/html2canvas): this package creates an image from a specific ```<div>``` that's then put into the PDF
- [Moment.Js](https://github.com/moment/moment): used for the dates used

## Todos
- [ ] Make the minimum number of measures on the practice sheet 1
- [ ] Re-work alert system so that an empty input field doesn't trigger an error while still active
- [x] Make Weekly Missions/Lessons note section only 3 lines, with more spacing
- [x] Have the generated PDF filename be the piece name plus the measure count
- [x] Add a date stamp to generated PDF
- [x] Change Practice Sheet measure width maximum to 8, as most music phrases are in multiples of 2
- [ ] Create user setting to make measure boxes bigger
- [ ] Add email requirement to submit form