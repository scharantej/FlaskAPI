## Flask Application Design for Test

### HTML Files

- **index.html**: A simple home page that greets the user with a welcome message. 
- **form.html**: A page with an HTML form that allows users to input information and submit it to the server. 
- **results.html**: A page that displays the results or outcome of the data submitted through the form.

### Routes

- `/`: A route that renders the home page (`index.html`).
- `/form`: A route that renders the form page (`form.html`).
- `/submit`: A route that handles form submissions. It collects the data entered into the form and redirects to the results page (`/results`).
- `/results`: A route that displays the results of the form submission (`results.html`).