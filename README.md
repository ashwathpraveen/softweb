# Ex.07 Restuarant Website
## Date: 08/11/25

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

### Home
```
<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lovely Moon — Home</title>
  <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
  <header class="nav">
    <div class="wrap inner">
      <div class="brand">Lovely</div>
      <nav class="links">
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="#">Administration</a>
        <a href="#">Contact</a>
      </nav>
    </div>
  </header>
  <section class="hero">
    <img src="assets/images/rest.jpeg" alt="lovely Moon banner">
    <div class="overlay"></div>
    <div class="content">
      <span class="badge">Since 1998</span>
      <h1>Crafted Flavors, Warm Hospitality</h1>
      <p class="subtitle">A modern trattoria vibe with seasonal ingredients and wood-fired classics.</p>
      <div class="cta">
        <a class="btn primary" href="menu.html">Explore Menu</a>

      </div>
    </div>
  </section>
  <section class="section">
    <div class="wrap grid3">
      <div class="card">
        <h3>Wood‑Fired Ovens</h3>
        <p>Perfect char and chewy crusts.</p>
      </div>
      <div class="card">
        <h3>Local Produce</h3>
        <p>Fresh, seasonal and sourced nearby.</p>
      </div>
      <div class="card">
        <h3>Cozy Atmosphere</h3>
        <p>Low light, soft music, relaxed seating.</p>
      </div>
    </div>
  </section>
  <footer>
    <div class="wrap">© 2025 Lovely Moon — Designed by <strong>AHAMADH SULAIMAN M</strong></div>
  </footer>
</body>

</html>

```

### Menu:

```
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Lovely Moon — Menu</title>
    <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
    <header class="nav">
        <div class="wrap inner">
            <div class="brand">Lovely Moon</div>
            <nav class="links">
                <a href="index.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="#">Administration</a>
                <a href="#">Contact</a>
            </nav>
        </div>
    </header>
    <main class="wrap section">
        <h2 class="section-title">Menu</h2>
        <section class="menu-grid">
            <article class="item">
                <img src="assets/images/pizza.jpeg" alt="Margherita Pizza">
                <div class="pad">
                    <div class="row">
                        <div class="name">Margherita Pizza</div>
                        <div class="price">₹699</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/bbqc.jpeg" alt="BBQ Chicken">
                <div class="pad">
                    <div class="row">
                        <div class="name">BBQ Chicken</div>
                        <div class="price">₹799</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/arr.jpeg" alt="Arrabbiata">
                <div class="pad">
                    <div class="row">
                        <div class="name">Arrabbiata</div>
                        <div class="price">₹649</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/carbo.jpeg" alt="Carbonara">
                <div class="pad">
                    <div class="row">
                        <div class="name">Carbonara</div>
                        <div class="price">₹749</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/salmon.jpeg" alt="Grilled Salmon">
                <div class="pad">
                    <div class="row">
                        <div class="name">Grilled Salmon</div>
                        <div class="price">₹1099</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/butter.jpeg" alt="Butter Chicken">
                <div class="pad">
                    <div class="row">
                        <div class="name">Butter Chicken</div>
                        <div class="price">₹799</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/vegb.jpeg" alt="Veg Biryani">
                <div class="pad">
                    <div class="row">
                        <div class="name">Veg Biryani</div>
                        <div class="price">₹649</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/pan.jpeg" alt="Paneer Tikka">
                <div class="pad">
                    <div class="row">
                        <div class="name">Paneer Tikka</div>
                        <div class="price">₹599</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/cae.jpeg" alt="Caesar Salad">
                <div class="pad">
                    <div class="row">
                        <div class="name">Caesar Salad</div>
                        <div class="price">₹449</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/gre.jpeg" alt="Greek Salad">
                <div class="pad">
                    <div class="row">
                        <div class="name">Greek Salad</div>
                        <div class="price">₹499</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/lava.jpeg" alt="Lava Cake">
                <div class="pad">
                    <div class="row">
                        <div class="name">Lava Cake</div>
                        <div class="price">₹349</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="assets/images/gulab.jpeg" alt="Gulab Jamun">
                <div class="pad">
                    <div class="row">
                        <div class="name">Gulab Jamun</div>
                        <div class="price">₹199</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
        </section>
    </main>
    <footer>
        <div class="wrap">© 2025 Lovely Moon — Designed by <strong>AHAMADH SULAIMAN M</strong></div>
    </footer>
</body>

</html>

```

### Adminstration:

```
<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lovely — Administration</title>
  <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
  <header class="nav">
    <div class="wrap inner">
      <div class="brand">Lovely Moon</div>
      <nav class="links">
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact</a>
      </nav>
    </div>
  </header>

  <main class="wrap section">
    <h2 class="section-title">Administration</h2>
    <p class="small" style="margin-bottom:12px">Meet the core team behind the flavor and the service.</p>
    <section class="menu-grid">
      <article class="item">
        <img src="sanji.jpeg" alt="Chef Aisha — Head Chef">
        <div class="pad">
          <div class="row">
            <div class="name">Mr.Vinsmoke Sanji</div>
            <div class="small">Head Chef</div>
          </div>
          <div class="small">Leads the kitchen, menu R&D, and training.</div>
        </div>
      </article>
      <article class="item">
        <img src="koyurim.jpeg" alt="Chef David — Sous Chef">
        <div class="pad">
          <div class="row">
            <div class="name">Ms. Ko Yu Rim</div>
            <div class="small">Asst Chef</div>
          </div>
          <div class="small">Runs prep, quality checks, and line coordination.</div>
        </div>
      </article>
      <article class="item">
        <img src="luffy.jpeg" alt="Meera Sharma — Manager">
        <div class="pad">
          <div class="row">
            <div class="name">Mr. Luffy Taro</div>
            <div class="small">Restaurant Manager</div>
          </div>
          <div class="small">Guest experience, floor operations, and events.</div>
        </div>
      </article>
    </section>
  </main>

  <footer>
    <div class="wrap">© 2025 Lovely Moon — Designed by <strong>AHAMADH SULAIMAN M</strong></div>
  </footer>
</body>

</html>

```
### Contact Page:
```
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Lovely Moon — Contact</title>
    <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
    <header class="nav">
        <div class="wrap inner">
            <div class="brand">Lovely Moon</div>
            <nav class="links">
                <a href="index.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="administration.html">Administration</a>
                <a href="contact.html">Contact</a>
            </nav>
        </div>
    </header>

    <section class="hero" style="min-height:48vh">
        <img src="assets/images/con.jpeg" alt="Contact hero">
        <div class="overlay"></div>
        <div class="content">
            <span class="badge">We'd love to hear from you</span>
            <h1>Contact & Reservations</h1>
            <p class="subtitle">Questions, events, or bookings — drop us a line.</p>
        </div>
    </section>

    <main class="wrap section">
        <div class="grid3">
            <div class="card">
                <h3>Address</h3>
                <p class="small">Lovely Moon, 21 MG Road, Indiranagar<br>Bengaluru, Karnataka 560038, India</p>
                <h3>Hours</h3>
                <p class="small">Mon–Sun: 11:30–22:30</p>
            </div>
            <div class="card">
                <h3>Contact</h3>
                <p class="small"><strong>Phone:</strong> <a href="tel:+918045001234">+91 80450 01234</a></p>
                <p class="small"><strong>Email:</strong> <a
                        href="mailto:reservations@lovelymoon.example">reservations@lovelymoon.example</a></p>
            </div>
            <div class="card">
                <h3>Social</h3>
                <p class="small">Instagram • Facebook • Maps</p>
                <p class="small">Follow for specials and events.</p>
            </div>
        </div>

        <div class="card" style="margin-top:16px">
            <h3 style="margin:0 0 8px">Send us a message</h3>
            <form onsubmit="event.preventDefault(); alert('Thanks! We will get back to you soon.');">
                <div class="grid3" style="grid-template-columns:1fr 1fr 1fr;gap:12px">
                    <p><input placeholder="Name"
                            style="width:100%;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)">
                    </p>
                    <p><input placeholder="Email" type="email"
                            style="width:100%;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)">
                    </p>
                    <p><input placeholder="Phone"
                            style="width:100%;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)">
                    </p>
                </div>
                <p><textarea placeholder="Message"
                        style="width:100%;min-height:140px;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)"></textarea>
                </p>
                <p><button class="btn primary" type="submit">Send</button></p>
            </form>
        </div>
    </main>

    <footer>
        <div class="wrap">© 2025 Lovely Moon — Designed by <strong>AHAMADH SULAIMAN M</strong></div>
    </footer>
</body>

</html>

```


## OUTPUT:
<img width="1915" height="1199" alt="image" src="https://github.com/user-attachments/assets/44c9ee8d-a15a-4ed5-aa02-bd5b4a5cd9e6" />
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/0e3829e8-37b1-48ab-8315-d980277f91fc" />
<img width="1915" height="1195" alt="image" src="https://github.com/user-attachments/assets/0be5771c-c504-4391-8fba-eb909671e8c2" />
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/0893e056-007e-4fa9-84c5-9f51ff3c33d1" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
