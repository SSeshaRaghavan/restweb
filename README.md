# Ex.07 Restaurant Website
## Date:02-05-2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mom's Munch Box - Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { background-color: #f4f4f4; color: #333; }

    header { background-color: #222; padding: 10px 0; text-align: center; }
    .banner { width: 100%; max-height: 300px; object-fit: cover; }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      background-color: #333;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      padding: 12px 18px;
      display: inline-block;
    }

    nav ul li a:hover {
      background-color: #555;
      border-radius: 5px;
    }

    main {
      text-align: center;
      padding: 30px 20px;
    }

    main h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    main p {
      font-size: 1.2rem;
      margin-bottom: 30px;
      color: #666;
    }

    .hero-banner {
      position: relative;
      margin-bottom: 40px;
    }

    .hero-banner img {
      width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .hero-banner h2 {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      font-size: 2rem;
      background: rgba(0, 0, 0, 0.5);
      padding: 15px 30px;
      border-radius: 8px;
    }

    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .feature-box {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      width: 300px;
      padding: 20px;
      text-align: center;
    }

    .feature-box img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .feature-box h2 {
      font-size: 1.5rem;
      margin-bottom: 10px;
    }

    .feature-box a {
      display: inline-block;
      margin-top: 10px;
      text-decoration: none;
      background-color: #e67e22;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
    }

    .feature-box a:hover {
      background-color: #d35400;
    }

    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1400&q=80" alt="Restaurant Banner" class="banner">
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Welcome to Mom's Munch Box</h1>
    <p>A Restaurant To Relish</p>

    <section class="hero-banner">
      <h2>30% Off This Weekend!</h2>
    </section>

    <section class="features">
      <div class="feature-box">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046751.png" alt="New Menu">
        <h2>Our New Menu</h2>
        <p>Explore our latest dishes that satisfy every craving.</p>
        <a href="menu.html">See Menu</a>
      </div>

      <div class="feature-box">
        <h2>Book a Table</h2>
        <p>Reserve your spot and enjoy great dining experiences.</p>
        <a href="contact.html">Book Now</a>
      </div>

      <div class="feature-box">
        <img src="https://cdn-icons-png.flaticon.com/512/2553/2553691.png" alt="Opening Hours">
        <h2>Opening Hours</h
          <p>
            Mon - Fri: 2pm - 10pm<br>
            Sat: 2pm - 11pm<br>
            Sun: 2pm - 9pm
          </p>
        </div>
      </section>
    </main>
  
    <footer>
      <p>Created by S Sesha Raghavan (212224040302)</p>
    </footer>
  
  </body>
  </html>
  </html>

  menu.html
  <!-- menu.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Delish Bites</title>
  <link rel="stylesheet" href="style.css">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { background-color: #fff8f0; color: #333; }

    header {
      background-color: #222;
      text-align: center;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      background-color: #333;
      padding: 10px 0;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      padding: 12px 18px;
      display: inline-block;
    }

    nav ul li a:hover {
      background-color: #555;
      border-radius: 5px;
    }

    main {
      padding: 30px 20px;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 30px;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 25px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .menu-item {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      text-align: center;
      padding: 15px;
    }

    .menu-item img {
      width: 100%;
      height: 170px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    .menu-item-name {
      font-size: 1.2rem;
      margin: 10px 0 5px;
    }

    .menu-item-price {
      color: #e67e22;
      font-weight: bold;
      font-size: 1rem;
    }

    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>Our Menu</h1>
    <div class="menu-grid">
      <div class="menu-item">
        <img src="https://img.freepik.com/free-psd/delicious-veggie-pizza-freshly-baked-toppings-cheese-mushrooms-peppers-olives_84443-37364.jpg" alt="Pizza">
        <p>Pizza - ₹150</p>
      </div>
      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1550547660-d9450f859349?auto=format&fit=crop&w=800&q=80" alt="Burger">
        <p>Burger - ₹120</p>
      </div>
      <div class="menu-item">
        <img src="https://img.freepik.com/free-psd/delicious-pasta-spaghetti-bowl-transparent-background_84443-27509.jpg" alt="Pasta">
        <p>Pasta - ₹100</p>
      </div>
      <div class="menu-item">
        <img src="https://img.pikbest.com/origin/10/09/44/55zpIkbEsTKau.png!w700wp" alt="Fries">
        <p>Fries - ₹70</p>
      </div>
      <div class="menu-item">
        <img src="https://img.pikbest.com/png-images/20240728/salad-healthy-green-vegetable-bowl-nutritious-_10685144.png!bw700" alt="Salad">
        <p>Salad - ₹50</p>
      </div>
      <div class="menu-item">
        <img src="https://png.pngtree.com/png-vector/20240802/ourmid/pngtree-yummy-and-delicious-chicken-corn-soup-png-image_13345659.png" alt="Soup">
        <p>Soup - ₹50</p>
      </div>
      <div class="menu-item">
        <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxISEhUUExQWFhUWGBobGBgXFx4bHxohIR0aHR8eHRoYHSggHyAlIBsaITEhJSktLjAuGyAzODUsNygtLisBCgoKDg0OGxAQGy8mICYwMDI1LTAtLS8vLy0tLS0wLy0tLy0tLy8tLystLS0tLS0tLS0tLy0tLSstLS8tLS0tLf/AABEIALcBEwMBEQACEQEDEQH/xAAcAAEAAwEBAQEBAAAAAAAAAAAABAUGBwMCAQj/xAA8EAACAQMDAgQEAwcDBAIDAAABAhEAAyEEEjEFQQYiUWETMnGBkaGxFCNCUsHR8Adi4RVygvEzskOiwv/EABoBAQADAQEBAAAAAAAAAAAAAAADBAUCAQb/xAA3EQACAgECAwYFBAICAQUBAAAAAQIDEQQhEjFBEyJRYXHwBTKBkaGxwdHhFPEjQmIzNFJyghX/2gAMAwEAAhEDEQA/AO40AoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUB+E0BR6nxjobZhr6zJEKrNn/wAQZqvLV0xeHI8yWOh6pZvCbbg+3B9cq0EfcV7XqabHiMln13+x1wvGcHlqOpWyrhW8yNtYcEZA49PeorNXXwyw91sxgjp1dVEk9wOfWoF8Qgluz3hJ66wEgR3jn/irytTeDzBKqU8FAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUBE1fUbduAWG44A/9VVu1lNW0pbksKZz5IxfinqL3ibUnZ3AxOcf0r5fVfE7rJvDwl0/k0K9PCMd0Q/C3SLRvNnzW1+U+jd5OZx+daHw6M7su32mUrqoweYmj1Gks27bhSEgH5ORjnHfvV66ipwa9o4qk4yyjnWl1ZnbafzSckFRNfO2UqPe6L3k8lfCUu71Pxeu6yzdT4kNydqAFl9S0gmInP51bqppglbCWfr73PW/M23QOr3NVa+IFe0ey3Aqz6FT3U+sVpdvXF4ct+eAoTe6ReafVXrQBuuGBIHykc8AHufx+1Sw1k444k2vHGF+eY7J+JLu9XVY8rZj0/v8AlXVvxSmuSjhvPgjuOmnJZI93xHbVtpS5kwCq7vvAzH2rmv4xppScW8Y8evodS0lijxLctNPqFcSp+xBB+4ORWhC2E/leSu4uPM9akORQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAVXW/EFjSgfFbzHhRkn7envVe7URr25vwOlHbL2RkNT13Uavh/gWv5LZBcjmGccY5C5HrXzWt+LXSk4QXv8Af9PI06tPXFcRW2uqpp0Ztq4Jw0kgH+YSSWIzn1zXmh0y4nfbu/36v9vAllJKHFJtR8isvaG7dV/hMVcKDtfhgcgfN81X+yhN/LyObtcpRdck14PbYieBunaltQxDtb+GTbZGB3EGDEcAZkGe1WODDymQKMZQT8PybPU+HXuWXto7qDJYkRuJ5yAJmlVOU0vu/e4rddcuRhtF0HU3bzW7QhpksTCr2kmPwAE1W7J54Srfo3GzK5M6D4c8LjTmXb49xlE3H3ELnhQSQB780VKjJRhFYxnOOTz78zuNcYrL5mhF9NxYkHAyf6Dt35rp6inLnnLwt/D6HfZzxhI+3uwoIO4Hgz/eoLrLK604y4k+T/r9zyMcy5YKvX69EMHzEGfYfhVK7UqEuGS4mt/Jfb34lquqTWVsR9N1G4T84A9Ao/t9KrR116y+PCXkv4JJUQxy/LJiG4wM3GCjnNI3X2Rlm18K57+JDN1wfyrIsa+/ZvBWKvYI5Mh0OPQQy8/5itbR/Ev8aKrtba236pPx8Un9iCVcbd47S8PH0Lu31KyxCrdQsYgBhJkEiBPoD+FfQxthLGGiq65rmme2ovqil2ICqJJOP1rqUlFZZwfmm1C3FDoQyngivITjOKlF5QPWuwKAUAoBQCgFAKAUAoBQCgFAKAUAoBQFXr+rgKRa/ePkDbkAgwZPGPSs/Va5QTjUuKXlyz5snrp3TnsjlGv8P6y7cuXLlwSZl3PPeIVSAomBn17kmsyqU7Y8bXX9CXUqvOz2wR/Dmnt2/i/F1C7X2oGQmFkzyRgkkCTwPqK8arnYoyX1Kyk1Xw52ZU+IBf0tw5+IoPcQW+pjNWFFyl3vuaWjtnVB1yjmL/Bb9K1rtbOpA2i5LFTnABXnGJ744FdqHC2ULku0bf2KnR+LDcvxlVcBS+YMTtI+h/8Asaiurk4tyf08MFrR1TnU4bJc/PJ0ax15rdgFnXZu2s0ElhBhVXlnJ7CefvUWltsVfDnk+fl/P7cyaVHBji3ZadFsgofIEVmmBzmMM3dj3jAwBxJ87RW7f9c/d+H169DyxtPL5lhZ1SsDsdSFJUgZgg5BI5ODP0rrtJJYytumM/7yuv2IeDfdFVcZrr7V+QTJGPw9ay25XWcMfl+xcWK45fMja/qDmbdo/LAnuRx9aklGxrhi+W2fIQjH5pdSHf16rBcyVEH3IxwBGa8lhSy+a/0dqOdkV5658MBhGSAZ45/zFUlTKUng81EuCBMPitIZEClpliQwHPEwBM4qzXpIxpcbHz328tzKsm1vgmXdXdu6K5dCfvLYYqq8nHvwZ7T7TU9eghdUkn8r6+De5Lp7FF8UkYbpljVaW5aLHfdukuCEZiDAIgL82TPbitKL4J8MVhLl/JNDUq3KkdT0ly49hreoJBJwZyR6EKcjkQa8s+JV1xlXNvyxz8yCylSacCXo2Fi0qhgqTC7o+yqMT3NK9RqHSpVtRhvu/wAJLbn7ZH2cVLh5s8l8QsJ/dNAaJZlBI7kKsx7An6xXP/8AaVeE05LO7eE19EvfiT/4TfVF8jAgEcGvoE01lFFrDwfoNenh+0AoBQCgFAKAUAoBQCgFAKAUBm/FvWTbHwrZ8zfOwMFF9BGQx/IZ5isn4n8RWnj2cH33+PfQt6bT8b4nyGhdBZlRCqo2x6ACI+nFUtPqEqZWNcvzj3ghmmpNMx3iPq+os2yChS2xMP8ADL7gZP8A2j70pvv7JKMdnvn1eTlz8EZXooW6yNHkJZiDxgwARxloNe1V5tfFzRZrrlZZmfqaTxRrLK6cm8ATzP8ASAPzq62sctzQqhwyznYzSdEutp7S3r163acTsBCgL/CsRznM859qOTisla2mL4pJbll0PoNvTgrJuEruS0xhmB/icgQiZ+pgxVDVyhnjn9iGvT8b8jQ9E6OzsC7jyyPKsJaB5S0O092OTyewqh2stVNJ7Q/X3+PPrexGiOy3LzqOsFoRt8sQoHaCD3zx3rq6zg2xt0Xhhr68jmuHHvncr+nILVprgVipcsoDZJPpnAHpiuIqUo8WOvjy+xJN5lw9Tx1Wrf4Yc+VphUBMQe/uRByQD7DvPGpQjnr7/Q564Kcap1DEGfoMjjn6+ldwi0j1tMyev6/FxQ3m3TiYn3B/4ruvTcacn0PJ28oQ+ZkDp73blzaodz5mM9wokQ2PY49hGanlTFrbBVdblZix7bZZs+iam28JqLfw3QlWEDBEeYHIIyPUc813KMH3X0NG6quyPDW8rZr06G16Hq0ayVCBVQlZUYbM+X29u1QT1Ea6XGS38uvUy4VvPDjdEvTeadoCwDn0H17D6elZtcr9YnCDxhPx8er6Lny8CSVUKsNrJ+LrhP7obsSXPb/tWJPfmIqzXOmmUpVLil4vly6HrrlJLi2RW6zVJaG9hLkQuNzMSYAA9z7/AFqOnvYXNvf7+RNj8EqyHeCUaBBkfxYk9sCcfau5LPejFtfqRTniOz3J2rW5cGTBjicfSP61of5Nsku0e/4IapRg+X8mP6j1LUK6i3acOrci2SBB7wIP9RUdl847rmjeoo08otzksPzR0jpuq+LbV+5A3CCIPcQ2ea3aLVbBSR8vbBQm0uRKqUjFAKAUAoBQCgFAKAUAoCJ1LUFUO0gOQYJ7f7o7xI/Kq2qudVbccZ8+Xr9DuCTe/Izo6fbKt5t7EEsT37mvnY6auSk+Pik92yey5yxhYSPKx1e2PIQNsRBHp3I9KhWoSfDjKe2METWS6tXhcteVNyEY4AiMROIrc01zlUsR2+xxjByvqPRho7l0Agm4TcCIx22l9CTAyTMRjP3j4k5NLmWqm3tF4fmRegdPe/fBvsH2Dyp7zzHcj/OK6ijWsfDBI3vVbe1VtqFjn4mG+GQREIwIJOc8CqOs1yrWIYZVqjxPL/2Vi2Az7bY8zndcc5J9WY9/p9qxnKV7y3sizlQWSfq7jpbU6dlABAAMS2ckzHtVipN4mnhckuvqRcKbamtz91NxLv7152oO+Ax9Pp7e9STlxPLEU4d2PUr7fUWuq5LR8VtoAlfKBkz6VPSspt85HrhjCS5EbTdLu3kOwy4JE9xBHHpx+dWqtPKcfM8k1HeTweWq8L3dSfJdLOgAYHEY47TUsdPxppc0QSshvHODN9f8KXwAGUbw0eZ4XOBBHf2z9a5rqnVLHQquuce+nleK/c+NS50ltTcRw1sfwqSMLBO4eUCP5oqB6acpvpn+Su223hn70PS/9TvJcDlbaAs4UyY9JGJbiO2a6sS0sJce/voWtLOyEsR6nTtMCSqW1AwAF4CqIB49prJ06nqLltu/wi7PEINt/wBnx1bqSWbcZ2IfP3LH6fXj61ovhjWqa1jD3fi+rf7ED2zbN+hnrHW7L/8Ax3DJTeApKwpPBMwT2j613p6a4t5WMPxINTKbipZ2ZJ6eEdjdKsy2kgBuFnOARljEc8DETnjVVTTTpW2P9cyOqcpLhzyPTT9cvQ4ZhaU/KZDFQOTERPsMe9Q6ei2lJdphdcr9Opbhobrcvl4Y3+/Q0mkvEWVLsXO0EmZknMz9TS6zKfaPP8+JVUXF8L5kHS9YS/bN0EpaAyWxxzOar6qFkrVDphfU74GnwnhoPEzKzXth+AwAXIyR3HvyPTitbRTelcnNbS/UtvSVzjGtS7+Sx03jiw5ja2TAyDP0rRXxGlvB7P4LfBZNBpHBl9oUtHaG4xu9TViu1PLlhb+8+fUypLGyJAM1MpJrKOD9r0CgFAKAUAoBQCgMFqOtrd1O87gjg2lDYgboBA/3NHvBHpXy2p1Sv1Tg/lw4+/qaKoapfjzLFNpV2BCKojOAMeYn8PzrmlQkpOOyW38lLqYTqfi/SIT8JXvMGHnUAKYOYzJj86mWly08fcl7KWDQnxYG01o2G3B1hQZWIOxZ3ZGcZr3U9u5KqEvXyXQjwo8zEePb+57WlJP71lW5cUScwdvuWMQM4q3RX2UW4LLX5CTe5b+Gunraci0jlCoV77XGLNGNlr2GZcR6Ccmqes1PDDDfeb5Lw6+/b0KFN/MXWt1Jwq5Y4UDk+1YUYObUYl1bbs9RfTTgK+C3zNmCfQGMgcfjVhLElHHd/V+PmjjDn3iuSLuy45LJbM2wcAniWHcDtPefapbLXUlGO7x+DvGWTPFPUEtrbDEtC7j2UnkD3AAP5VbhBKEcbvx8/wCiCvLbMpf8QrcuoyqPlUbQABPEAVLiWc4L1NS4Xlmy6NptXbtsFsXAWacwD+JOfrV2MbUu6irbZp5SWZLYrOp+ILmglrqOG3AZGJJAGTgjPIPrUMFbGeOpJJVThlNNe0Yy51i51O65dnFpDgrjc3tPoP1rnUWTpSct5Pp4Ihu18NPiFCT8c++RM6H+13bn7K7JcTJYuSxRV5MiCeRgnkjipLLoxr7R8uZBYqpyjOpYfpt9jaaHQWtMuywgQMcwPM57Fj/Ec/2r5m7UXaiS4n6ItxhFbv7l6oNm0WMbtpL/AE7Ak8f8Vr6el0VrHN8ypOStn5dDC29Ra1Eh7oDk5UkHyjsBIP3z2qxpdPHCm39DjWTkk4cO3iU+o0lvTK5FyFJAA5I3EDEfWrE6oy3KdOHNRnyPvU9URU2JMDnJ+5z+pqvFvPdXvyPrqfhVSS40sfv5+J4LryWAkndxAJP0/wA9DXM4POTS7OMYZ8Pfv6Gk0XWLuluLavEhSshRBjPIIwVPHNU9RTPGVs1+hhanS16mPaU8yk69fGnv3J+I2must1NqllUsZbc8jYQS3lPaKv1LtIqS5r3yMxRn8s9seX7kXxV4hLWLItsVFtiRBBmJ2HHaP0qzGUpvhkjrRSUbHxczeeEtIhCXLiMGKBgsTBI4J4n25qhVRGnNs998RXi+mPexZ12tnZ/xxe3U1mrs3LgFkSu8S9wYgTkLmQx4B7DNaFcJvhqlze7f1y8fov6MfMVmX2Rc2LKooVRCqAAPQCtdJJYRWbbeWelengoBQCgFAKAUBA69qxa0164f4bbH8sVFfLhrk/IkqWZpHPOk6CGtEAfDtMsT6L/n418Zp3JTVsvHP5NK+5Ri4I/fHd5l0t9EwSGMDG4kjEz3A/OrtaUr1Bck236/6KFaedjnl/p9uzaS4zEEj+EEAA5zBGSf1rYjkt8OxG6f1Z2t3NlwhEcKirg8Y/2nvCma6nXyz1OUozyn0Nf0Tw8bifF1D3IuHcEYBSV2gA4+WRiAAYxiTWbrNaqf+OPMlqqX0L/VXVtriABwBiIxHtXz0o8c8p5yXI+B8WD8IfEfFxx5Qf4FPf8A7j+Q+9WmlXHgXN8zz5n5H1q7i6gBX/8AjUyR6/7e0e9S9qoJSf0XvojxRaex4W9fpL1t0HK+VYGMZ8sc44j+1daerhnm2Ly98iziW6exnvEHUGGnhw11VPzAAlRuKwIPzTE9sd81rQhlqJT7eEZNdTOeHtGlzU6baXB+KpZWGPKwaOZkAH+1T5w3Fo5tvjjhTO6dT6mUt4cgxkgSQIzAPf0r2c5RjtIpPkZnx9dXVaT4TEsrFGmCTiGIAXM8ECPyrm2+aSZ5CaiYHVk6a1at2UdrrsFS2ILfUiOe/wD6NUo1K6blNrHPJ0oym+Jm50NgadIO03GANxhGWA4+g4+1Yuou432cPlRsabT8Ec9Sd4b0zOzXGJIDeWT/ABf2Xn6mremrcpKeN+S9fH6HupsSXCvr6f2eHWrjXdyhiQvlcTie4PrjFXaanJPLeV+pZ08IRWZLny9DmK23sam5uE+Xy+YiVJyIAg8cH0q20uzSI79LKc4pru5xn1PTqmiLIGt9oZhOYnmJiP8A3UFVvefETS+HaaWaavnXV55+D6blXp9UIIJII+UEGZ9MdxViUGt0TaX4gq4dlftKOxsfC2u0umstevYuzti4IK9xA9xJn0qOWeUd/wBDO+JfE3a+CL7q/JIbTHW3BeF4h52rbdVAIAkKJOMmZJ/4rynxS7OS38SDT/EJafEJR25vHN5Lvw/0rUBnW6RIG4lTIzOOI7dqj7Cfa5j9S/qPitE8KuL+vQpdX4b+Pqt9xf3dsq3w4A39gpPEA7iZ/mAq5p3J5XL9l1Zn22qVkpx8l6m86t1W3o9KdQRBEC2qgDecAnPEgd+ABXiTnHtYPHSPpnd//rH2IVFuXA9/H9l9P1K/wv1q9dZ715mCBSRtUDzQpClcwYMckdiZqKGJ3KcptPd5XXHRdMfT9Tq2MeFRitybqvFGtayl3T6dSskXPiNLDAyFG0gAz2+wzWhHWOVLlB7rbfr9sFeFVfE1J/b+yP0zx1dZkV7ckvs2qIJmYIngiIjjPbmqtXxO5zScc+S99CvJLJvq3jkUAoBQCgFAUvirVotlkZlBYd/SeT+FZPxa+MaXUn3pdPI7reHk55p+p7Swtnep9WxI7/TNfOYlFKE0/QszScONPJUavWO1xpIcgMd0YDcxuiCQB8oMiO3fZ0dcoxcpLDZ7p5LkZPrthryoxvXFN1VDblG2CY/rA/XNX6movkTWpyjszadA6SrXjaU7NNpgpKrgsZmDP8xyTzzVbU3qEXZI6jHC4UaLquqgkk18rNOdjec5LcI4WCDbSQLrie6J6+jN7eg7/Tm5CvsllfM/x5/weSeXhFTq+oG9dFlfNdY+Y/yL3YngQOPtVmqlKLnYHLGyPXrWu+EoRQAsQScmOMLGSe5P1zVemDtnxy+hItkYDX9cvIpyAdpCgc5idzDkwIxHJrdoog5be/Qq2zfDua3Q6rTlDBhPhLncQcYnZ8vMnEV1hp8iCVEJvJW9B6e2p1Z+CTCoW8wjnyjIzkbsR2/Hi2tuGFzZUtpUflZ1O/bXaFbsu3P580e+x6omS8SdQvaRVe2qXd7bGSCPLBIgg4j17Zr2Cy8Txg4VO+D98G9GNi2166+93J2EljAPJAbgkysxwPesj4rqFtXXtnn6GvTBruvkidcttcdUTljH09SfYAVR01Tm8Fic1FZZM8Rdat6OyFUnyCBx5j3JPGcn6n7Vpw78lCHT37+5FRS5ycpdSs8PambAZjm4TcPtuyB/zWlUowXDkvXRblsuWxi/GnUrS37akjIYkg4GQBP4GpFW7ItxLFeshppxhbsmufh4fcmaIhSD9Ij+9UbY9C+2pRy3sfHUOradDK2V3qfnHaew9f8APSplU5VuEjD1elWoyU4sXr9570KZLbVYgGAcEboHAHeaki4VVqHpufPXaG+EeJokeGlvWrstINx9qoCGIKjcG3hiqz8sH2qHVSrnDuv5d88vxzfiRuTaw+h0rw94gVme0M3gRuXu5IHH0+U+kV1p3LgTfNkqg1BSNHb0Ks3w+SfNebt7Kpjv39h7ioZyV1nZQf8A9n09F+/7lmLcIcb+n8/wYvxrq7WsuS9pm0unxvDEBtxAJCr8wkDJ7A1Zdk1NuKTS29vx8vJFNajhbWMrqygt9fv6ZUs2W/dlWIcDbt8wJzAglSAPqKgnQrMW5acX6cy1bNTgmlg0vTurW7TAP8QkKjDYMsTuMFux8oOSPmrKoplKfaebKXElsz603iWzZd9Tas/GYk7UGCpJUEwAdpInsCJPImtDRWSrt78Vl9eXv6ElUYWS3ePob/w94jt6obY+HdA3G2WBMTEiORPeK+hquU9ns/A9uolXv08S6qYgFAKAUB8XroUFmMAVxOcYR4pcj1LJgPFWqR5N1dwPAiYA+1fNXNX35m8Pp448EdvCXIyGi1xFwta05a2AQWys9vL6kD15nHrV7HC08Za6k1dFkovHJ9Cr8VdbR9MTZJtPbMbCACVO0EpmMGPpmalqkpsQhOp7rmVnSbdzUae0b0YYW1G0yZIUAAYniCZ+biu54jLYtV8U44Z0ZT8K1sBmMsYiTGACckKMSe8nvXy+r1Dulwp7fv75F6NaW/v2ytuapVh7oZgcooBIMcs0cLiIPzE+gqWmjgWds9MnMn0RJ6Ja1PUbh2r8Kyvz3GPmn0CjHGecegrW0eh4+9J/39f6Kd9yrWEtz50vThYR0BQ3SpLOixgtiNxLZgEkkmqusmrJOuC2X5JKs4UpMwvXrm2WcnvE9+2Kk0seLZEs5YRj2vFm3zIUZxgTOI71sxhwx4SjKeXnwL3SaRXexaDFUafjAgwIG45IwWgiOJnvUfFzbO8ZSS6lld6+NGzvYVwHcfEeTBjdAEntniuFFz6ntkUkfT+Nr191QSFJEk8/b+9R2UtRbbLHw+iFs+90LTT9MfV3LaywRW3XXk+VROB7t8v4ntUNt0KKnOX09SfU1Ri0oo1HiXqS2LMiBEBQOwHEV83pq5ai7L6nUUoo9PCuncWG1FzFy6ItiMqgIn7sRn6LWrZCNcOGHv3/AGV5S4ppdEYHxz1jc+09s+xjj+/2q1oaX830LkJqESp01/UrY+ILkKQSPPtERMD/AHc44q7KqHHg7j8Rko5lFMpdd1RWQrG4lh5jyMD+tWK6HF55Gbqtc7X3t+S9C603WjcXby8xA/X0g1DZW08/kvU6uEo4f2LDw90U37k3AQAcgiP1/wAxXC/8SOy+Nr7stlzS6v18C66/0mEZphQCARxjt/f71zxJk0L8fKY4WT8MZbeG3ILeDOQNzcd+MmuuLv8ATGMPP7GFq+zlY3Wjr/hvpz6S0r3VB1d2SF5+Hu+bJzPr7AD65GrvVTddXzPr4LovVkml0+e9Ll1PXxlfe2UsW7hG5Zu95B7A9t2Z9h74jenhpmpZeceO2fH+jy25zi4pe/AzVzqL2ka1JPBEY80yAAft9Z7V3VJ4SjyfvP0wVFDhTPPS+Pi6lLggyVnbH4gdvetOTsUcPcgcj60b2bsXSjH+YA7J7bgIyfYmqVdiqlw2HiZa9O6Z08MyB13ITuViFOD32xuAjBPp3rThCqaU1uSrKllcz56V4g0uk6iwQO5Fsqw3SFB2HBYH+XsY5mulJUyylsaMa530tyl1OsdP1qXra3LZlWEj1+hHrWhXZGceKJQnBwlwyJNdnAoBQH46gggiQeRXkoqSwwUnirpqPpnAQSokRAgfxZ+k1R1ulU6lwJJxaa++/wCDuG8kjFdCXbYdLm1XDHYARwOPxqOTTRqwjJPkc38ZKq3VYkAhoE9zwYAz3n7VDpoOLaRav4VVmT36Gz8I6J4W45kWlJAHG58pAMzADOfciq+uv7Gptc3svqVYrLUSff8AM0H5RlsxPovrn9AaxNHUn3n0LU5YRX624t+6tq0ss7hSQO5AACj1CjnhVUk4EVuUaZXSTfvyKc7ezR0+9p7Wk0nw0hFVYH35JPryZrXvkqaXjwM+GbLNzj3X/FOzfsyzExxjsB9O8epr5+iqVjyzWeImK0vV1Zbq3R+8MkBu4EGPXBBwPethUcCXCV+1TbTPjwfYQm69xYVlhfLMsCT5YGCIqS9tJJPcqpTc1KC6llcvfEmzedlYAG3yJ79v0PGar8Cg+KK9TQnRwycuSf6mW6j8Rwxa6WVGCqDyRiOMd6uQ4U1hczNnOTnwczz6bqoYSGZyYULkngARS2viXkWNLrJaeXElnyO3dOH7Npwjkb/muEcbvT6LxPsT3r47WXO+zEOS5GmnKb45LHl4FGSddqFH/wCIOAv+5pifov6/SrdFXYrg/wCz5+SPJvY1HiDXBbRsqdqquTEnYkYngbjAPtPpUkZ8WdvfT36eRDGG6kzjet0d6+xfy7ZOSeBEyRzHateqddUeHr+5Bdq48onxc0t+6LbrbItKwRWjkbo3Z/T6c1OnCOcvfmRuc2k8bHhf6Ez3B8JlYse0wPUmfTuK7jdhbo4sqy8p7ml6d4WWW3X2S4p8kAbTGVJBEsJMdqgldw4ytiyqpPdPctOk67T/AAt126yX2YwxBKNBMjgccGc4qDhWXgow1ChNsyfjDX33vfDR5tcAhSoPc5PvNXKaq4riZLPUWNYjsjff6e9Ca1ZtarVkFQCbSxkrGGPp7dzg1j6/UV1Wd1c+h1RQ5mztuFDa2/ysm2s9zgCJyTMTmCfas/RRbk7eif3f16FnUzUIdmjm2s8SvdZ7jyW3wWMAGMYAGBjFX56dzeZvLaKNiUcb7v8ABPW4GKuCJfcxPOAo/TaR9qqqD+V9CB78zxe9a1i5UB0gl1ByBjI9OBNS11ToeMvh8OZpy+CuUE1LEn0f6Ey7pHVVIYFZElWjHEQcmu5UJQc47mdbobKk3Lp08vEsv2L9oAdrV1riCAVBKgNgn4fyyYgkCe/rUcVZZW+zW/XpnHmQptoyVu3a6XqH2W7juCN+9cW1IEhpWCDMyDwePXSi9Rak5pJr8/qaFFndalyZvfAepuspfTEhJMKYKtBJiDB7jIjn6gxzvvqklRDi8USzVclix+jOm6PU71naVIwVYZH9x71rae9XQzhp9U+afvqZtkOB4zk96nOBQCgIXWdG16xdtKwVnRlDETBIwYrmceKLR3CXDJS8Dg/iboPV9GZuXVFs8Nb2mT6ZQEH6/nWfa404Ulz+xqV3u35WZjVdO3j4ty5vIPmkkntAzn1Me3auozxsjma4t2dN8Nuy6CzvMll3z7HCcf7Av41858Vs47lWun6smpXUjXd1y8tpJe4QQFHCknzMfUgAKPvmCYu6GlyXAl6s4usUe8zovhDwuukUs0Ndbk9lHO0H3OWPeBwFUD6KutVxwjKssc3lmc/1K6k2/wCHMKAP7/59qw/iNsp6jss4SwaGjglDi6nKOrt2VYIaVIAJMH1PrP2q1TBRWCSx55FD0ktd+KxCkiJZhIGCYkD2MfSrU1w4RXrfE2yTeS9p9iB7cNvcEfLwcYPp2jv7TXOYzySJyhyPu1ol1SMWvTeUE7TAiODC9iCDn+9eObg+Wx1KbujwtkO9pb14W2RQCxG4HiQYGDXacYt5KzhKbUktzTeBPDoF46qS1q2sAsNs3fYEZCjP1K/bN+Jaxxp4Fzf6FmuhdpnPr6k3qepuavUfs1ncx5faJgfbuaq6PTcEO0xl9F4/0WrLVHu+0a7pPTG0x86FCqeUEcT5QfyavLarKYt2fNL9CONkbHiPJGc8e64LaIQ+ZvLAmT3P4Cu9HTmab5HtktmYnpmoubtl226jylRET/4t836YrWlVFbxKNUEnllxa6jcveS0CvwiGdgo2xGVaSMnme34VFKvCy+vvJLZOU1wQW55rpXLai3YYNdG0gjGNxY9+5iTXuWnHK2/ojqoscuHO63Paz0nVlwSigx8xcSePfEHjtziop21w2bLt0VHCdiT+v8Eb/omo+HctOyDzgr/FtJhiQRBIYE/5x6rq3dFxT3W/n4fYzJUOVmFvnr0Pvw90HUa3V29Pc8tuzLXHA/g9Z/3cDuM+hqxZONUG115e/IlmnlJ80dT1Ost3yzyF0tjvwDt//kRz7V8xapTsfj0XVJ7fdl+OKoefv9Dm/jjql7qFy2bDKbCMEthSDBONzgGQc4ngfUzvaOEaY8E1vgzJ35ltyLnpHQz8NXdMNEA+hgz7E5rxQxu+ZA3xPLLT/o1raVNsgQwgMRzg8HvFcSgk+JI7hJwkpLmiT4R6Elm3fMhw8IZaPLBkex836ZqlqLHLE49M7PbmXLddOxxlycf1KjqnTXsPBJa0x8jesHg+49uanpmpRbjyexfd8dTHdb9TWeF+p2NsW79zawBEoSFIw0MF9Rx9fWrCUK3wReP5MSGmslHMVseHi/pL3QLiqSxhHzgqCZMRtggnnIx6EGayE1HijzLVC4e6+RlNOr2L1lCzW1iLS+ZZBPcHlpPzL68GqWnk85knl8376Fe+qXHxZyvI6n4Z6rc+EWvNIXGV80/iZ+vfmrv+dGlN2PZEddUp8jTgzkVqJ5WURn7XoFAKAi9T6fb1FtrdwSp/L3HvUdtUbY8MjuE3B5RyLrvgO7bukLOxjAYDsf8ADg1iTquofDzXiacLozWepcdT8NdQFu0NJbtFUULFx9p8qgLjaRE5PfHvXNPwuVlsrrOr2Xv8Eb1UYrhRpvA3hL9ht7rrfF1D5uXPf0X0A/z33Kqo1rEUUbLHN7mpqUjOZ/6m2Ntwt2Kg/hj+lfNfEoY1afil/Bq6OWa/Q4d1a88nfIVs+U49M1q0wSSSO+OGHxo0Wgv2rGlVAyXEMvt2kNc9p9s8z+VR2ZlZl8zyPDGOFyLMdAsXAkWv3K+YB3JO48L9D7+3NcRsmm23uJQg0kRNR4QtFG/ZlO/n3XGZ3HKn04yK7Wok/nOexjH5T3fpgvmylqx8G5uCjLBflJY7CBAUAn7VVg518TnLMd/X7nldcornyNN1Gw4+HpNKNx2hbfuZO93IxA5PufcCs6iv/Kuzj/RZ41VFykdE8GeE7XT7O1fNdbN26eXbv9B6Cvq661BYMayxzeWUviXUS7Nx5j+AwP0J/wDKvntdb2uowuS9/wAmlpocMDifjDXt+0Hz5WQpPAJ7n+9XtHDuM81EmlxLoVmo6k+o+G21jdUbZAJj1PMRg/gatRrVeV0Ie1VmH/25Gj0XQRaSTel3y67twJ9PIwOKgldCXVGlH4dYlupZfvwPO01rR311AEFn23Enyw3MYnBhq5jOcu5zwv0Jf8SOnipb+vqXKeK9NdYjAEmMemT33fiKqWae1vLRzO/Sy7kt8dcFTY6y2p1tsae2zW7gW2ARBkEjePbMQew7VeVaqrxJ7+9iqtTFSTh8r6enU6he0psWVs2vmuGGMZcgZ+ij0+3c1h36qVvJbdPPx9/wdxipT4pf6RkP9Rddbtrp+nKxm66/H2nhMc++Z+gzzV3QaXgza+a/X3sVNXa5ppHMutdHvaTUG2A0jzLtEys4Jj8K2YWRshmRnPwOn+CeuXns27VxV8gbcd0H0ReMAYBJ596pWTim0jqMW+RfarpFzVA7LqWtpgNyw9RK3FB/MYryD4uXI7VUn0InT+j3NEDau3A6ltysiwDIE/xHOJ5MzNZvxWlrE1y+55wNFl10p8Bw87UAadwE7JYfiARjME1U0kpK7giumP4fvxO4qX/UofB/iFArFUChiSFwVAJJCj1j6elall3YTbxzPppaPjhFLkkt0b234gBQkwccAc+1Wqddxoy7dA4ZwV17q6p8MtktchVmDME4B5IisnjcbOPfC54+xncDWzRcdSYFJUAGQT9/Ue9dfF4wnSpJb7blzR5T35Fx4d1gu2FzJTyN7Ees+og/etr4Xd2ulg3zW32/opaqHBa0WdaBXFAKAUAoBQCgFAYf/VTSs1hHRQYJBn0IJEx2kVm6+MVw2yWcfuXNHLdxOD6m7tb94hK7Y2AFhiSDLe5mKRkprusly1LdbES50m5cDG0P3YYhjML6iPftj71Mppby5iUcvY1fT+o/BsW0dg2AGXEgcAEng4BzmfvVWa4m3glhtsQL3iy+174dpA5JEbW3BgYwNomRHbvNP8aLjxTYd7UsRRvNHpn083ShF4pssWSZbMZaCfMTA9gD64zbpdpJU19Xu/Il4srifI3vgrwwNIhe4d2ouSXY52yZ2L6ATW/ptPGmKSW5l33Ox+Ror7QrH0BqayXDFy8CGKy0jkvjHXbJCk4Xn/P8xXyVOJS2N2KxE4r1Am5dz3OeTAn0Ga+kpXBAqXvojXdDRQu1yyuWC5AXeIwAvaq9nPZHta6vmaDV6DT3FWzcBUoRtKYmBEN3IggzNVozlGUlI6o1V/bSi2c38Sv8K9ctiYVvKfwJg+1aVNaaUjvVa+bjwSy/M0SeHrXwhfOoCsV88rKzE+WI/Wq3b4fDj+Tzs895Gr/0v0bWNK2tvgLgrZERAnzP9+B7Kf5qo/FLcPhr3fvYiphxtZ6Gr015nT4u7zNItb+wJEtH0j8BNU9LRxPD5L2/fqWL5qKwj50nRLFlWIJNx/nuky7Zk+bkZ7CB6RWra+7iJmvfmYfriF2FsWXaCAziCVEj5GIxIn9KqQSg+JS+j5HFdEZN8Useudyw6IxTy2mW4ozjB/8AIHg/8etRSs6zWGbcdXVHEbYuLx9Po1zRoLvUSdOQh2lpg/WZIP17iup2OFax1JYaeNqbqafn5ko9SQ27ah8qoE+hA5H/ADU0LoWVdnPkRz+Hz3yjn3jXW3G1NwXnDWgg2EBYEgfyiSZH4YkVbjRCCzBblCrCzFoz2h11pUWGcPj5l8g9RKgk/hXNlMpSfElj8mhRrtSp9lHCXTZs0PS+vOdybUeQNrbnWPpx+YqrKmMFsvf3NGvTayUu0nZHHglz+6LrTtautbN0AsnykiQJiQQcHis3M604xezPdfoHZHjhtL3sdKsFNu4lSGgyIlv71ZcJY70sr16eh8woz4sYeT58K3yt57QBKlN24nuCBEfQ5PsPtJ8AnidkM898e/Um+IRzGM/oamvpzLFAKAUAoBQCgFAeWpsLcUo4lWEEVzKKksM9TaeUc38Q+BFt7nSWXkGAdv8A3QCY9wI9YrJnoZVPMN0aFeqUtpGL/Y7lgMlyCWJbAgLAEAGc+s1zGany5osGP+AwuH4B3G4Yb1Xt35FT9ouHvdPyR8Dzk33SOl2unWjq3A+PdxZVjME4xAkk+wmPc1Sstla1XH/SPcJbm/8AAXhZ7IGp1RL6lxJ3Gdk+3AOeBwMepOrptNGpZx/Xvr7So3XOey5G0q2VyH1c/uX+g/UVn/FXjSWPy/cm0/8A6qOJeMLhYt7Y/wCa+d0K5G5PZGH6HomdnFsH4pBO4tAUbhzgg8TFfRTk9vApcKy/ElaktbuWy4O8N80bR3XA9DPvSOHnBzJNYbLu1cu342wLigEkOBkzkiJ4AxxznFV5RWfImg2luiqu9FKXyLqHZdAG45knAMqcSD/zPMvHiGz5EEO9Y1Jcy28N9BL3TYPxHXcdlwghVUATE+VhB/pjNQ33cMe0JorCaZtOsWwzixhNJp7alyTgASAn2VQST2PvWLTB2Nzz3m/t5/sv6JU+CJmNN1a1r9WLtsuq2PJZEwCrHLERMkiI9lMTWtOEtPBVrqULJcb4jcNoBHmLH2rnss/MyErertatW2ZmVQoJPqPtXXZxa4UDkF/qLG+13SuVSZO4lV988iftVtUx7NQtW/5Joal14eFJf/FrKf8AHqi3vdZVCo3s+6flOB3yZ/yKqLSOWehvab41poVqNVPC/BYx9/6LvohGqs3JubT8yBTtwp9Tkggz9gaKmFU+HG+ObIL9Xbf3s7Z5IodX1N9Ut226oxXctp9wDeVv4sZx2xI9Oasxiqcb7fpnwKEpdonhb/qWnQ9NZ/Z/2dwWkNLAHBB+b5uc+grmU3xcSRJCOFz3RS6LTuhm0fiIzFZHMgTke4yPXik5LG+xo6H4guPsrefR9GavoXS79zO0xicTE9z6fesq7G+OnM1dTrq6ljqdQsdKTT2sfNGWJndn/wB/jUllKqqy0s+vn7+h8vLUSutcmRfCT7tfehvksqCI4LNPP0Aqf4FB8Mptc3z/AGIdfjEd9/D9zcV9AZooBQCgFAKAUAoBQCgKPrnhbT6pSGXaTMlcZPrH9IqvZpoS3WzJoXzgVHTvAduxOwIZOSQf0/5qq9DLPMmeqyXFjwvphct3nQXLtoEIzTCT3VJ2g+/PvVnT6WNK23bILLXMu6skQoCs8R3tmnuNEwOKzPjH/tJLxwvu0WNKv+VHEetP8S4wnG6Pr9vT8azdBp+GtSZrWz3wUGnuLYF02EZ3bDJtIVechmye2BP2rT+dJS5Fd91vHMg9cvai58O/m2MEJM7YjvGfWCPWuocEW48/M4kpSSecGo0ltdIFCktfcA3WOARBEL2gEmB7Tmagc+PPgiWMOFb7tlb1PrZkm5eDAQ1o5WCpMqIwSCAO/fHr7CvPJPPU9lZjnjBvejaj9n0n7Q3nuX4FpIiZwqgROTk+wHpWbqU5zVa5dffvoep8TMj/AKi9TNrTpolub795t14jtOYOZyYgdgvpV3QUpN2PkiC+bfdXUxPQta2ndclXDqGjMiRiDjsMxV+2PHv0IVhRxLmdbu+IQcm6v0qmo5OMIy/ijr2n+DeWV+JcTbIiTggcfU1NVBuSwg0o7mH6JorhG5G5JBQ5ke496sXSi9mvqI08RbjpDOPhvtRQqndhjAxAUH/9jUXaJd5cyzwSa4S78H3LiEoi/EuWxLRwE43ZGcEHH0qtdmxqS2XvY6ruhGvMvTzyV3i3o4Yq6N5jvkDA5BXd64MSf5asUWcyrKztN1sV/T+oXy5UGVgAtOBiOecf2ri2MIxz1PY6tcmbLw70lFUFWEfEWdrZJXPH4f4axtRqJtvK6Fi2yGIzg02n/s6r022kBWK7SJUhRE8znMmp6FBpRsax02X+xZNy78D561eSzauO3y2kLEDnE4z3P9a5vri/+NPlhfk9qk3ufngDp7Rc1TLtOoCeXduws8YHrHvHAra0Ok/xocGcop6m5WNPBr6ulYUAoBQCgFAKAUAoBQCgFAKAUAoCD1zRm9YuWwYLKYI9eRVbWUdvS4e9tyWmzgmpH8+9ZsMhJXysCRuAE+n0rG0uoeFHBrzin3isc3rSbxdLOykndBURPaM+n95rRwm8Y2K+6Wc7lPe6yLlp12EM4gjtPqJ+X6VIquGSedjlzcovbcsOlC411XJLstsyGnzfKAoPsMj6fWoLJLha8ziiMlNykavw94IF+98W4gRAZz39Sf8AIqm9S+FpPZdS1NRTzjc6D1HopW5b1DtFu0hFm1HGAC7e8QAsYE5zA5jRKFfaT5yfLy6IiVib4I/c4b4guFte7NyZOff68nFaVS/4sI8lhTySBaTefiMNrI20khWVueY5InPsK83xse9dyiXSW3uOEZiIBUnlo5icE8VY4nGKyV1GMpPBa9Yb46LaRJdGkiQNkj3OftUVa4ZcT6ktneWEt0RujpesDeV222lSx7HOF7zk+3Ne2uMtlzOJOVceJLmSdYYJuI8giD2MTNRJZWGR6TUdnP8A5N0ab/TWw7s728vhZ7BeY+nOKp6uFrnGNe3X6kl//PL/AI+S5vGNy26x4Yvaq8ttStpWJ+KTz/4L3Jz7CCfavdPc8uuxYkt/JlayMliLK5PDCae+1sSF/hnn33ev/NR23ynLD2PI1Jmh6Z0a0LoVW2tgkKQMjiO26qt0uGUY8372O3pklxI33Tn2JDCQCcATPefL9ak0k+GtrGVl7Yz59PUlgsrbmZjrWqsavdp0t3w91mtldwBIBIJBkxPv2kmIqxX8PjZNaiDa6+O/o9yftnWuCWGdE6VpTas27ZO4oiqT6kDJ/Gt2KaSzzM6TTbaJVdHIoBQCgFAKAUAoBQCgFAKAUAoBQCgMB4t8CfFL3LU+YkkDkH2BwRzjmsuzQ8M3ZX64L1Wq7vDI5h1TozbglwjaikEcFjPtlYwDXkZvLeNyxhNJZM9ZVXvA27agECQOAfUfX+le2yxDdhLfB03w34bJ2lozms9wctsnrkkdG6T05cQPIvf+Y/2H6/erul0yk0/+q/L/AIX6lW61r1f4IPi0ljAzA4H4z+ddax5tS8Bp9on8/wDjHpxN9j3LQB+le0WYbRZcco/E0racSpLrHmVhMcAwTxGPzFStca8GcJcD8iJ4lUJF5Ghidu0Y7ZOO/Fd079xnF/d76LXwS9240BEUMdxdhnbxkjMSRHrJ+tRXpR68ianLXFjmXnXej3HRrJUKrMrLdUzIBUnBM5yO+Qe1cVSSxJEvY9r3c4M51roTafaUJNtsGc7T/UHt+HpU0sYyQy0DlYox5M6H/p5bSygI+Ug49Z5J9zVCNuZ5kad2kVdfZwXI1fVfgr+8nzp5kYc7oI49wSCPc1ZtvqjF55mY6JSjvyMomk1l/a1/bPZlENHvGPyrLl3pJnkaoxZo9H0S2LA2yH/iPf2Ne8Fc6fM6balh8iVYa5ZBa4RAEnBO76Rwaq1VSqnxcSWfFPD/AIZz2cf+qZbeFulsC2pvAfGujgCAgx5eTmAATPavqNPHbPT9+r/ZFG2XRGiqyQigFAKAUAoBQCgFAKAUAoBQCgFAKAUAoCr610DT6oRdQT2cYYRxnvHoZqOyqNi3O4WShyMen+m1u1hFRxM8lTzORkH8azrNDN9c/guLVp8zV6Dou0AOQAOyz/8AY/2qSrQ4+d/RfyRT1GflLhVAEDAFaCSSwiqUvV7W1t22Q/Jn5YHueMD8azNXFwnx42f4LlD4o48Dl/j3pSbw4Azkj1gj9aoysUJp+JeqWVhlUmvDH4a4CAZ7RB9fpVxLbIctzLdY6ffe8SFa9p2uLuAEspgGD3AOM+lTxlFR2eJdCJQ4rEp/JnfHMnafqgZptQIXAGQRHG0QaqtY+c0p0N71NNHovilENtZLyYuHzDbGODzzPPb6VNGrCytiGqT49/fia7Vi0bJ+LGwjOeQfQ/mD9K8diS3LnZtvulH4d1DK2xZaTg8CJ/L1rOtljc0LZJwzI6H07QgwzElgPw+1RR4eeTBvscn5FvbtLEfhXqaawVXlM+00+JHFexpclxI8dmHgkdO6e9xg7nyKZRY78TIOf0HYd6vaOmdiT5R/L9Mfr9vEgusUdlzL8CK2UklhFI/a9AoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgPPUWQ6lTwa4sgpxcZHUZOLyjn3jboj7Vg4UwAOI4rA1ennW14Gpp71LJgep9HVkI81sgwWUxGeZByIM1NRbhEklk+36obTBG8oCxuX+I4+YAYJ9f0rt1RbbZ6ptLBnOsdEdrhZFBYsXJHo2YIHoTg9xHcZmdsYx3OalJSymfmh8N3Bl8xNVrdX0ii7SlHfJq7Hh9yiteP7lBEbjK+kKAZ+k1V45y5c/oTPVKOyLPT+HXYK9i01naRua4zBmQjzbVHHeJz96nhXGO9jz5e+f0KVmrnJ4z+DYWtVc8u7TlFTDMWBk4EADJ9ZMfnVa+PZQjJRyk8fR+JWWHJri5rJbWAzx8Nd3ucAffv9qlrVljTphxLxeyX16/Qhlwx+Z4JadGVmD3YYjIUfKD655/Kr9fw7ilx3PP/ivlz5+P4XkQS1GFiH36lqK1CsKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAfF60riGAI965lFSWGeptPKMx1XwctwlrbRIja3H4j8OKo2aBN5gy1DVNfMjI67/Ty+W8qyh+YBlI+0kGq70t8PlLMdVW1uXPS/BxtCBYn63B/Q1DLQ3vz+v8B6uHj+Ce3h8+WbJEHIVgZEe/vFcf4moW0o/Z/yP8mPSX4JydOaABYxPBcAfkalektmknX93/BF20Vvxfgkr066SJKCO+Wj7QP1qaOjvbTk0ser/gjd1a5ZJdjpaCNxLn/dx+HH4zViv4fVH5sy9eX25ffJFK+T5bE4CrxCKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQCgFAKAUAoBQH//2Q==" alt="Tacos">
        <p>Tacos - ₹90</p>
      </div>
      <div class="menu-item">
        <img src="data:image/jpeg;base64,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" alt="Ice Cream">
        <p>Ice Cream - ₹95</p>
      </div>
      <div class="menu-item">
        <img src="data:image/jpeg;base64,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" alt="Cake">
        <p>Cake - ₹450</p>
      </div>
      <div class="menu-item">
        <img src="https://static.vecteezy.com/system/resources/previews/047/490/432/non_2x/colorful-fruit-smoothies-isolated-on-a-transparent-background-free-png.png" alt="Smoothie">
        <p>Smoothie - ₹165</p>
      </div>
      <div class="menu-item">
        <img src="https://www.budgetbytes.com/wp-content/uploads/2024/06/Grilled-Chicken-Overhead-500x500.jpg" alt="Grilled Chicken">
        <p>Grilled Chicken - ₹210</p>
      </div>
      <div class="menu-item">
        <img src="https://www.chefkunalkapur.com/wp-content/uploads/2022/03/paneer-kulcha-roll-scaled.jpg?v=1647833164" alt="Paneer Wrap">
        <p>Paneer Wrap - ₹140</p>
      </div>
    </div>
  </main>
  <footer>
    <p>Created by S Sesha Raghavan(212224040302)</p>
  </footer>
</body>
</html>

admin.html
<!-- admin.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Mom's Munch Box</title>
  <link rel="stylesheet" href="style.css">
</head>
<body class="background">
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Our Team</h1>
    <div class="team-grid">
      <div class="team-member">
        <img src="https://i.ibb.co/kGRfqGv/member1.jpg" alt="Vijayalakshmi">
        <p><strong>Vijayalakshmi</strong><br>Head Chef</p>
      </div>
      <div class="team-member">
        <img src="https://i.ibb.co/5RbdzHt/member2.jpg" alt="S Sesha Raghavan">
        <p><strong>S Sesha Raghavan</strong><br>Manager</p>
      </div>
      <div class="team-member">
        <img src="https://i.ibb.co/vDhnGBX/member3.jpg" alt="Ali">
        <p><strong>Ali</strong><br>Assistant Chef</p>
      </div>
      <div class="team-member">
        <img src="https://i.ibb.co/b6B6cyT/member4.jpg" alt="Kavya">
        <p><strong>Kavya</strong><br>Waitress</p>
      </div>
    </div>
  </main>

  <footer>
    <p>Created by S Sesha Raghavan (212224040302)</p>
  </footer>
</body>
</html>

contact.html
<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Delish Bites</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>Contact Us</h1>
    <p>Address: 149 Arignar Anna Salai Street, Co-operative Nagar, Phase-4, Thiruverkadu, Chennai-600077</p>
    <p>Phone: +91 6366464433</p>
    <p>Email: contact@momsmunchbox.com</p>
  </main>
  <footer>
    <p>Created by S Sesha Raghavan(212224040302)</p>
  </footer>
</body>
</html>

style.css

```
## OUTPUT:
![alt text](<Screenshot 2025-05-02 132340.png>)
![alt text](<Screenshot 2025-05-02 133719.png>)
![alt text](<Screenshot 2025-05-02 140748.png>)
![alt text](<Screenshot 2025-05-02 140800.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
