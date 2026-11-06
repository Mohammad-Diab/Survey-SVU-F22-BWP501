# Survey

The front end of an online survey site in Arabic (right to left), made for the Web Programming II course (BWP501) at the Syrian Virtual University (SVU), semester F22. Static HTML, CSS and JavaScript with Bootstrap and jQuery; there is no backend, so nothing is saved or sent.

## Pages

- **Login** (`login/index.html`): email and password, with Bootstrap form validation.
- **Register** (`register/index.html`): full name, username, password and confirmation, email, phone, age, gender, nationality, marital status, education level and employment status, with form validation.
- **Survey** (`survey/index.html`): a step-by-step questionnaire about sport, diet and fitness, one question per step, with **Next** and **Previous** buttons; a question must be answered before moving on.

The root `index.html` redirects to `./home`, a page that is not in this repository.

## Usage

Open `login/index.html`, `register/index.html` or `survey/index.html` in a browser. There is no build step and no server.

## Credits

- [Bootstrap](https://getbootstrap.com) 5.3.0 (`lib/bootstrap`), MIT License.
- [jQuery](https://jquery.com) 3.7.0 (`lib/jQuery`), MIT License.
- [Font Awesome Free](https://fontawesome.com) 6.4.0 (`lib/fontAwesome`): icons CC BY 4.0, fonts SIL Open Font License 1.1, code MIT License; see `lib/fontAwesome/LICENSE.txt`.
- [Tajawal](https://fonts.google.com/specimen/Tajawal) font by Boutros International (`assets/fonts`), SIL Open Font License 1.1; see `assets/fonts/OFL.txt`.

## Author

Mohammad Diab

## License

[Apache 2.0](LICENSE), except the libraries and fonts listed under Credits, which keep their own licenses.
