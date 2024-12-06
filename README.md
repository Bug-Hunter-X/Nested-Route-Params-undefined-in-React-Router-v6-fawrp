This repository demonstrates a bug encountered in React Router v6 when using nested routes with parameters. The issue arises when a nested route attempts to access parameters from the URL, resulting in undefined values. The bug.js file contains the buggy code, while the bugSolution.js file provides a corrected implementation, showcasing how to properly access nested route parameters. The solution involves using the 'useParams' hook correctly within the nested component to access the parameters. 