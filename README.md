
## 1. Setup & Layout
* Created a new Laravel project named "blade-template".
* Built a base Blade layout at resources/views/layout.blade.php containing shared header, navigation, and footer.
* Utilized Blade directives @extends, @section, and @yield to structure the pages.
## 2. Component
* Separated the header, navigation, and footer into Blade components or partials. Header and navigation in "resources\views\partials\header.blade.php" file and footer in "resources\views\partials\footer.blade.php"
* Used @include or Blade components for repeated UI elements.
## 3. Page Conversion
* Created a registration page view at resources/views/registration.blade.php that extends the base layout.
* Moved the provided registration form and related content into this view.
## 4. Styling & Assets
* Placed custom CSS and JavaScript files in Laravel’s public/ folder and linked them using the Blade asset() helper.
* Ensured Tailwind CSS and FontAwesome were correctly integrated.
