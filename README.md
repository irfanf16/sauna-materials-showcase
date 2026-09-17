# Sauna Material Kit — Specialist eCommerce

**Specialist eCommerce · Laravel**

eCommerce for sauna construction materials, where products compose into buildable kits priced across a bill of materials.

> **Source code is private.** This repository documents the architecture and engineering work.

## My role
Full-stack engineer

## Engineering highlights

**Kit-based catalogue.** Products compose into buildable kits, so pricing and stock resolve across a bill of materials rather than flat SKUs — a customer ordering a sauna kit decrements every component.

**Role-based trade access.** `spatie/laravel-permission` separates retail and trade customers, with pricing tiers and catalogue visibility driven by role.

**Admin reporting.** Yajra DataTables for server-side order and inventory tables; SweetAlert confirmation flows on stock-affecting actions.

**External integrations.** `mashape/unirest-php` for third-party supplier and shipping API calls.



## Stack

`Laravel` · `PHP` · `MySQL` · `Blade` · `JavaScript` · `Spatie Permission` · `DataTables`
