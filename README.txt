SPICE GARDEN - AZURE BLOB STATIC WEBSITE
==============================================

Files:
  index.html       Main website
  style.css        Website styling
  script.js        Mobile navigation + year
  404.html         Error page for Azure static website
  images/          Put your developer.jpg and other images here

CUSTOMIZE:
1. Open index.html.
2. Replace "Your Name" with the developer's name.
3. Change restaurant address, phone number and opening hours.
4. Add your own image as:
       images/developer.jpg
   The developer photo section will automatically display it.
5. Replace the emoji/image placeholders with real restaurant images if desired.

LOCAL TEST:
Simply open index.html in a browser.

AZURE BLOB STATIC WEBSITE:
1. Create an Azure Storage Account.
2. Open the Storage Account.
3. Go to Data management > Static website.
4. Enable Static website.
5. Index document name: index.html
6. Error document path: 404.html
7. Azure creates a $web container.
8. Upload all files/folders in this ZIP into $web.
9. Open the Primary endpoint shown by Azure.

IMPORTANT:
This is a static website. It does not require a backend server or database.
