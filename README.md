# WordPress maintenance checklist

Thirteen small jobs that keep a WordPress site working, grouped by how often to do them. Each line says where to look in the dashboard (yoursite.com/wp-admin). Copy it, print it, or fork it and tick the boxes.

## Every week

- [ ] **Open the site like a visitor.** Load the home page and the busiest page, on a phone too. A blank page or an error comes before everything else.
- [ ] **See what needs updating.** Dashboard › Updates lists new versions of WordPress, plugins and themes. Read the note under each plugin; security releases go first.
- [ ] **Update plugins one at a time.** Update one, open the site, then do the next. If something breaks, you know which plugin did it.

## Every month

- [ ] **Check that a recent copy of the site exists.** Your host or a backup plugin makes it. Check the date of the newest one and ask your host how you would restore it.
- [ ] **Update WordPress itself.** Dashboard › Updates tells you whether the site updates on its own. If it does not, make sure a recent copy exists first.
- [ ] **Remove plugins you don't use.** Plugins › Installed Plugins › Inactive. A switched-off plugin still sits on the server and still needs updates.
- [ ] **Check who can log in as an administrator.** Users › All Users › Administrator. Remove anyone who no longer works on the site.
- [ ] **Look for abandoned plugins.** Each plugin's page on wordpress.org shows its last update. Over a year with no update: find a replacement.
- [ ] **Test the contact form.** Send yourself a message. Forms can stop sending email with no sign on the site. Shops: place a test order too.
- [ ] **Read Site Health.** Tools › Site Health lists what WordPress thinks needs attention, with a reason for each line.

## Every 3 months

- [ ] **Check the SSL certificate.** Click the icon left of the address bar and open the certificate to see when it runs out. Many hosts renew it automatically.
- [ ] **Check the PHP version.** Tools › Site Health › Info › Server. Before asking your host for a newer one, check your plugins support it.

## Once a year

- [ ] **Renew what keeps the site online.** Domain, hosting and premium plugin licences should renew on a card that still works.

---

The same checklist, with the places in the dashboard to look, is on the guides page at [CMSHands](https://cmshands.com/guides/wp-maintenance-checklist).
