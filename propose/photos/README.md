# Photos folder

Your 5 photos are already in place here:

- `photo1.jpg`
- `photo2.jpg`
- `photo3.jpg`
- `photo4.jpg`
- `photo5.jpg`

Want to swap one out or add more? Overwrite the file (or add `photo6.jpg`, etc.) and add a matching entry to the `PHOTOS` array near the top of the `<script>` in `../index.html`.

If a file is ever missing, the page shows a soft placeholder heart instead of a broken image, so it's safe to test before everything's in place.

Each photo has a **date** and an **activity** line under it — edit those in the `PHOTOS` array in `../index.html`:

```js
{ src: "photos/photo1.jpg", date: "Add the date", activity: "Add what we were doing" },
```

Tips:
- Portrait or square photos (e.g. 4:5 or 1:1) look best in the gallery.
- Keep each file under ~2MB so the page loads quickly on her phone.
