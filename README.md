# Bootstrap Card Centering Exercise

This project is a basic HTML + Bootstrap 5 exercise that demonstrates how to:

- Integrate Bootstrap using a CDN
- Use a prebuilt Bootstrap card component
- Center content using CSS Flexbox
- Display an image inside the card

---

## 💡 Objective

To create a simple web page that displays a centered card using Bootstrap 5 and Flexbox.

---

## 📸 Preview
![image](https://github.com/user-attachments/assets/f72af6fe-e02b-4495-85a1-4275b2422fed)


## 📌 Steps Implemented

### ✅ Step 1: Add Bootstrap CDN

The Bootstrap 5 CSS was added via CDN inside the `<head>`:

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
  rel="stylesheet"
  integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
  crossorigin="anonymous"
/>
```
### ✅ Step 2: Add Prebuilt Bootstrap Card
```html
<div class="card" style="width: 18rem;">
  <img src="flower.jpg" class="card-img-top" alt="..." />
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">
      Some quick example text to build on the card title and make up the bulk of the card’s content.
    </p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
```

### ✅ Step 3: Add Image
```html
<img src="flower.jpg" class="card-img-top" alt="sunflower image" />
```

### ✅ Step 4:Center the Card Using Flexbox
```html
.flex-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

```

### 🛠️ Requirements
- Bootstrap 5 (via CDN)
- A local image named flower.jpg

### 🧠 Learning Outcomes
- How to itegrate Bootstrap in a project
- How to Use Bootstrap Components
- How to center content with Flexbox



