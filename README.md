# ContosoUniversity
## Test Plan

### Manual Tests
1. Run the application with `dotnet run` or by pressing F5 in Visual Studio.
2. Navigate through the app:
   - Go to **Students** and test Create, Read, Update, and Delete operations.
   - Go to **Courses** and verify course CRUD functionality.
   - Go to **Enrollments** to confirm that assigning students to courses works.
3. Enter invalid data into forms (e.g., missing required fields, entering letters where numbers are expected) and confirm that validation messages appear.
4. Use the navigation menu to ensure all pages load without errors.

### Automated Tests
- This solution does not currently include a test project.  
- To add tests in the future:
  1. Create a new xUnit or NUnit test project in the solution.
  2. Run tests with `dotnet test`.

### Expected Results
- All CRUD operations should work correctly.
- Validation messages should display for invalid input.
- Navigation between Students, Courses, and Enrollments should function without errors.
