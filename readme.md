# Sort a Table using JavaScript

This project demonstrates sorting functionality for an HTML table with pure JavaScript. 

## Features
- Sort table rows based on the values in a specific column.
- Toggle sorting order between ascending and descending by clicking the headers.
- Display sorting indicator (arrow icon) in the column header.

## To use the sorting functionality

1. Include the Bootstrap CSS and Bootstrap Icons CSS files for styling.
2. Add the JavaScript function `sort()` to your project.
3. Apply the `onclick` attribute to the column headers you want to make sortable.

```html
<th class="id" onclick="sort('content-table', 'id')">ID <i></i></th>
<th class="country" onclick="sort('content-table', 'country')">Country <i></i></th>
<th class="some-number" onclick="sort('content-table', 'some-number')">Some number <i></i></th>
```

### Contributing
Contributions are welcome! Feel free to submit issues or pull requests to help improve this project.
Feel free to customize it further based on your specific project details and requirements.



