
## What's inside

- Adminpanel with default one admin user (_admin@admin.com/password_) and two roles
- Users/Roles/permissions management function (based on our own code similar to Spatie Roles-Permissions)
- One demo CRUD for Products management - name/description/price
- Everything that is needed for CRUDs: model+migration+controller+requests+views

From that boilerplate you can manually create more CRUDs, assign permissions etc. Or use our [online generator](https://2019.quickadminpanel.com) for this.

__Notice__: AdminLTE 3 version was not released officially. At the time of writing (April 2019), the latest was [v3.0.0-Alpha 2 release in May 2018](https://github.com/ColorlibHQ/AdminLTE/releases/tag/v3.0.0-alpha.2). But, at current alpha state, the theme is good enough to use for simple CRUDs like ours.

## Screenshots

![Laravel + AdminLTE3 screenshot 01](https://laraveldaily.com/wp-content/uploads/2019/04/Screen-Shot-2019-04-16-at-11.25.35-AM.png)

![Laravel + AdminLTE3 screenshot 02](https://laraveldaily.com/wp-content/uploads/2019/04/Screen-Shot-2019-04-16-at-10.26.32-AM.png)

![Laravel + AdminLTE3 screenshot 03](https://laraveldaily.com/wp-content/uploads/2019/04/Screen-Shot-2019-04-16-at-10.26.16-AM.png)

![Laravel + AdminLTE3 screenshot 04](https://laraveldaily.com/wp-content/uploads/2019/04/Screen-Shot-2019-04-16-at-10.27.20-AM.png)

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL or go to __/login__ and login with default credentials __admin@admin.com__ - __password__

## License

Basically, feel free to use and re-use any way you want.

---


