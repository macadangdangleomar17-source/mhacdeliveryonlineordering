MHAC DELIVERY FINAL PACKAGE V13
================================

THIS IS THE FINAL CLEAN GITHUB PAGES PACKAGE FOR THE CURRENT TEST VERSION.

UPLOAD:
1. Extract this ZIP.
2. Upload EVERYTHING inside it to the ROOT of the new GitHub repository.
3. Do NOT upload the ZIP itself.
4. Do NOT move or rename any files/folders.
5. Do NOT mix files from previous MHAC packages.

EXPECTED ROOT:
index.html
manifest.json
admin/
rider/
shared/
assets/
README.txt

IMPORTANT:
- ROOT index.html = CUSTOMER APP.
- admin/index.html = ADMIN APP.
- rider/index.html = RIDER APP.
- shared/ contains the CSS/data used by all apps.
- assets/ contains the logo/menu images.

AFTER GITHUB PAGES IS ENABLED:
Customer:
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/

Admin:
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/admin/

Rider:
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/rider/

TEST FLOW:
Customer -> Choose Store -> Jollibee -> Chickenjoy -> + -> add-on -> Cart -> Checkout
Admin -> Refresh -> Confirm -> Assign Rider
Rider -> Refresh -> assigned order only -> ON THE WAY -> DELIVERED

RATE LOGIC:
First 1 km = P40
Each succeeding km = +P10
10% service fee
Maximum 2 stores
2nd store = +P5

CURRENT TEST LIMITATION:
Orders are stored in browser localStorage. This is a working interface/order-flow test, not yet the final real-time multi-phone Firebase system.

DO NOT PROCEED TO FIREBASE UNTIL THIS PACKAGE IS CONFIRMED WORKING ON GITHUB PAGES.
