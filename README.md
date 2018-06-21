# aspnetrefreshrolesrepro
Repository for code and reproduction steps for the stamp validation refresh bug of ASP.NET Core

Reproduction steps:
1. Register an account
2. Log in
3. Click "Add to role" on the homepage to add the user to "Test role"
4. Wait 1 minute for refresh
5. Refresh once - the role claim now appears in the list
6. Refresh again - the claim is gone
