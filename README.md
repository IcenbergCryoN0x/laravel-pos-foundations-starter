# Laravel POS Foundations

**Status: starter scaffold only.** This repository is not a runnable Laravel application and does not claim that the TFA5 requirements are complete.

It gives the assignment a Git repository and a place to continue. The required pages, Laravel routes and controllers, sample records, database files, and deployment still need to be created.

## Assignment checklist

- [ ] Create a Laravel project and confirm it runs locally with Artisan.
- [ ] Implement `/`, `/about`, `/customers`, and `/users` in `routes/web.php`.
- [ ] Create `PageController`, `CustomerController`, and `UserController`.
- [ ] Add at least five static sample records to each account controller.
- [ ] Create the four Blade views and loop through customer and user records with `@foreach`.
- [ ] Add navigation between all four pages.
- [ ] Include the requested database export, or migration and seeder files.
- [ ] Run and check every route.
- [ ] Deploy the application and add its live URL here.

**Hosted application:** Not deployed.

## Repository layout

- `routes/` — notes for the required route map.
- `app/Http/Controllers/` — notes for the three required controllers.
- `resources/views/` — notes for the four planned Blade views.
- `database/migrations/` and `database/seeders/` — notes only; no database files are implemented yet.

## Publish this scaffold to GitHub

Create an empty GitHub repository, then from this folder run:

```bash
git add .
git commit -m "Add assignment scaffold"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the example remote with your own repository URL. Publishing this scaffold does not fulfill the app or hosting requirements above.
