# JavaScript BookList App | No Frameworks
- https://www.youtube.com/watch?v=JaMCxVWtW58&


## Setup

- Style
   Download or Refer  [Bootswatch](https://bootswatch.com/), yeti
- Font
  https://use.fontawesome.com/releases/v5.6.3/css/all.css



## APIs
- Create row in table
```
   const list = document.querySelector('#book-list');

   const row = document.createElement('tr');

   row.innerHTML = `
      <td></td>
   `;

   list.appendChild(row);
```

- Events
```
   document.addEventListener('DOMContentLoaded', UI.displayBooks);
```