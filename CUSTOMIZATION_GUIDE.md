# Customization Guide

## 1. Replace the avatar with your photo
In `index.html`, search for:

```html
<div class="avatar-circle">PKR</div>
```

Replace it with an image tag such as:

```html
<img src="your-photo.jpg" alt="Pabitra Kumar Roy" style="width:118px;height:118px;border-radius:999px;object-fit:cover;border:1px solid #cfe0f4;display:block;margin:0 auto;" />
```

Then upload `your-photo.jpg` into the same GitHub repository.

## 2. Change the total number of project sites
Search for:

```javascript
PROJECT.totalProjectSites: 92
```

Update `92` to your new statewide total.

## 3. Rename the field loops
Search for the `tripNames` block and edit the labels.

## 4. Replace the KML later
Keep the new file name the same, or update:

```javascript
PROJECT.kmlPath
```

## 5. Add a results section later
A good place is right after the methodology section. You can add:
- before-after mean speed chart
- 85th percentile speed chart
- speed compliance comparison
- summary findings by site type or district
