# MyExerciseRecord
Record personal exercise activities.

Functionality:
• The application should consist of a single web page
• The page should provide the following functionality:
• Show a list of exercise records currently in the system
• Allow the user to search existing records by exercise name
• Allow the user to enter new exercise records
Data:
• The Exercise Record should consist of the following:
• ExerciseName string max 100 characters required
• ExerciseDate Datetime required
• DurationInMinutes int range 1-120 required
Exercise Record List:
• Should show a maximum of 10 records at a time
• Should be ordered in most recent date order
• The search should be executed as an ajax request
New Exercise Record Entry Form:
• Should be shown as a popup on the main page
• Should be launched via a button on the main page
• On successful submission of the form the user should be redirected back onto the main page.
Data Store:
• Should be implemented as an in-memory repository with a view to using database
storage at some time in the future
• The repository should be provided to the controller via dependency injection during
construction (Optional)
• The repository should allow the addition of new ExerciseRecord entities
• The repository should expose existing ExerciseRecord entities as an IQueryable
Validation:
• Validation should be enforced both client side and server side
• Validation should enforce the data constraints as define in the ExerciseRecord above
• A specific exercise (ie. exerciseName) can only be entered once on a single day. This
constraint only needs to be enforced on the server. The mechanism used to enforce
this constraint is at your own discretion.
Structure:
• -The application should make use of asp.net mvc layout files and all pages should use
this layout
• -All javascript should be contained in js files rather than in the page directly
• -All css should be contained in css files rather than in the page directly
• -The main layout should allow child page to place file references in the head section
of the page.
• -All common js files should be referenced via the layout page.
• -All page specific js files should be referenced via the child page
