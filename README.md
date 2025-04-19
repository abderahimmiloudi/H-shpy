<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>H shpy | معرض الأعمال</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(to left, #007BFF, #FFA500);
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav button {
      background: none;
      border: none;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      margin-left: 1rem;
    }
    section {
      padding: 2rem;
    }
    .works {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .work {
      background: white;
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>H shpy</h1>
    <nav>
      <button onclick="setLang('ar')">العربية</button>
      <button onclick="setLang('en')">English</button>
    </nav>
  </header>
  <main>
    <section id="intro">
      <h2>مرحبًا بكم في معرض أعمالي</h2>
      <p>هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير.</p>
    </section><section id="works">
  <h2>أعمالي</h2>
  <div class="works">
    <div class="work">
      <h3>مشروع 1</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
    <div class="work">
      <h3>مشروع 2</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
  </div>
</section>

<section id="about">
  <h2>من أنا؟</h2>
  <p>مصمم ومطور مواقع مهتم بعرض أعمالي للعالم.</p>
</section>

<section id="contact">
  <h2>تواصل معي</h2>
  <form>
    <input type="text" placeholder="الاسم" required><br><br>
    <input type="email" placeholder="البريد الإلكتروني" required><br><br>
    <textarea placeholder="رسالتك"></textarea><br><br>
    <button type="submit">إرسال</button>
  </form>
</section>

  </main>  <footer>
    &copy; 2025 H shpy
  </footer>  <script>
    const texts = {
      ar: {
        intro: ["مرحبًا بكم في معرض أعمالي", "هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير."],
        works: "أعمالي",
        about: ["من أنا؟", "مصمم ومطور مواقع مهتم بعرض أعمالي للعالم."],
        contact: "تواصل معي",
        placeholderName: "الاسم",
        placeholderEmail: "البريد الإلكتروني",
        placeholderMessage: "رسالتك",
        send: "إرسال"
      },
      en: {
        intro: ["Welcome to My Portfolio", "Here are some of my best design and development projects."],
        works: "My Work",
        about: ["About Me", "I'm a web designer and developer passionate about showcasing my work to the world."],
        contact: "Contact Me",
        placeholderName: "Name",
        placeholderEmail: "Email",
        placeholderMessage: "Your Message",
        send: "Send"
      }
    };

    function setLang(lang) {
      document.querySelector('#intro h2').textContent = texts[lang].intro[0];
      document.querySelector('#intro p').textContent = texts[lang].intro[1];
      document.querySelector('#works h2').textContent = texts[lang].works;
      document.querySelector('#about h2').textContent = texts[lang].about[0];
      document.querySelector('#about p').textContent = texts[lang].about[1];
      document.querySelector('#contact h2').textContent = texts[lang].contact;
      const form = document.querySelector('form');
      form.children[0].placeholder = texts[lang].placeholderName;
      form.children[2].placeholder = texts[lang].placeholderEmail;
      form.children[4].placeholder = texts[lang].placeholderMessage;
      form.children[6].textContent = texts[lang].send;

      if (lang === 'en') {
        document.documentElement.lang = 'en';
        document.documentElement.dir = 'ltr';
      } else {
        document.documentElement.lang = 'ar';
        document.documentElement.dir = 'rtl';
      }
    }
  </script></body>
</html><!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>H shpy | معرض الأعمال</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(to left, #007BFF, #FFA500);
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav button {
      background: none;
      border: none;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      margin-left: 1rem;
    }
    section {
      padding: 2rem;
    }
    .works {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .work {
      background: white;
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>H shpy</h1>
    <nav>
      <button onclick="setLang('ar')">العربية</button>
      <button onclick="setLang('en')">English</button>
    </nav>
  </header>
  <main>
    <section id="intro">
      <h2>مرحبًا بكم في معرض أعمالي</h2>
      <p>هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير.</p>
    </section><section id="works">
  <h2>أعمالي</h2>
  <div class="works">
    <div class="work">
      <h3>مشروع 1</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
    <div class="work">
      <h3>مشروع 2</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
  </div>
</section>

<section id="about">
  <h2>من أنا؟</h2>
  <p>مصمم ومطور مواقع مهتم بعرض أعمالي للعالم.</p>
</section>

<section id="contact">
  <h2>تواصل معي</h2>
  <form>
    <input type="text" placeholder="الاسم" required><br><br>
    <input type="email" placeholder="البريد الإلكتروني" required><br><br>
    <textarea placeholder="رسالتك"></textarea><br><br>
    <button type="submit">إرسال</button>
  </form>
</section>

  </main>  <footer>
    &copy; 2025 H shpy
  </footer>  <script>
    const texts = {
      ar: {
        intro: ["مرحبًا بكم في معرض أعمالي", "هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير."],
        works: "أعمالي",
        about: ["من أنا؟", "مصمم ومطور مواقع مهتم بعرض أعمالي للعالم."],
        contact: "تواصل معي",
        placeholderName: "الاسم",
        placeholderEmail: "البريد الإلكتروني",
        placeholderMessage: "رسالتك",
        send: "إرسال"
      },
      en: {
        intro: ["Welcome to My Portfolio", "Here are some of my best design and development projects."],
        works: "My Work",
        about: ["About Me", "I'm a web designer and developer passionate about showcasing my work to the world."],
        contact: "Contact Me",
        placeholderName: "Name",
        placeholderEmail: "Email",
        placeholderMessage: "Your Message",
        send: "Send"
      }
    };

    function setLang(lang) {
      document.querySelector('#intro h2').textContent = texts[lang].intro[0];
      document.querySelector('#intro p').textContent = texts[lang].intro[1];
      document.querySelector('#works h2').textContent = texts[lang].works;
      document.querySelector('#about h2').textContent = texts[lang].about[0];
      document.querySelector('#about p').textContent = texts[lang].about[1];
      document.querySelector('#contact h2').textContent = texts[lang].contact;
      const form = document.querySelector('form');
      form.children[0].placeholder = texts[lang].placeholderName;
      form.children[2].placeholder = texts[lang].placeholderEmail;
      form.children[4].placeholder = texts[lang].placeholderMessage;
      form.children[6].textContent = texts[lang].send;

      if (lang === 'en') {
        document.documentElement.lang = 'en';
        document.documentElement.dir = 'ltr';
      } else {
        document.documentElement.lang = 'ar';
        document.documentElement.dir = 'rtl';
      }
    }
  </script></body>
</html><!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>H shpy | معرض الأعمال</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(to left, #007BFF, #FFA500);
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav button {
      background: none;
      border: none;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      margin-left: 1rem;
    }
    section {
      padding: 2rem;
    }
    .works {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .work {
      background: white;
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>H shpy</h1>
    <nav>
      <button onclick="setLang('ar')">العربية</button>
      <button onclick="setLang('en')">English</button>
    </nav>
  </header>
  <main>
    <section id="intro">
      <h2>مرحبًا بكم في معرض أعمالي</h2>
      <p>هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير.</p>
    </section><section id="works">
  <h2>أعمالي</h2>
  <div class="works">
    <div class="work">
      <h3>مشروع 1</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
    <div class="work">
      <h3>مشروع 2</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
  </div>
</section>

<section id="about">
  <h2>من أنا؟</h2>
  <p>مصمم ومطور مواقع مهتم بعرض أعمالي للعالم.</p>
</section>

<section id="contact">
  <h2>تواصل معي</h2>
  <form>
    <input type="text" placeholder="الاسم" required><br><br>
    <input type="email" placeholder="البريد الإلكتروني" required><br><br>
    <textarea placeholder="رسالتك"></textarea><br><br>
    <button type="submit">إرسال</button>
  </form>
</section>

  </main>  <footer>
    &copy; 2025 H shpy
  </footer>  <script>
    const texts = {
      ar: {
        intro: ["مرحبًا بكم في معرض أعمالي", "هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير."],
        works: "أعمالي",
        about: ["من أنا؟", "مصمم ومطور مواقع مهتم بعرض أعمالي للعالم."],
        contact: "تواصل معي",
        placeholderName: "الاسم",
        placeholderEmail: "البريد الإلكتروني",
        placeholderMessage: "رسالتك",
        send: "إرسال"
      },
      en: {
        intro: ["Welcome to My Portfolio", "Here are some of my best design and development projects."],
        works: "My Work",
        about: ["About Me", "I'm a web designer and developer passionate about showcasing my work to the world."],
        contact: "Contact Me",
        placeholderName: "Name",
        placeholderEmail: "Email",
        placeholderMessage: "Your Message",
        send: "Send"
      }
    };

    function setLang(lang) {
      document.querySelector('#intro h2').textContent = texts[lang].intro[0];
      document.querySelector('#intro p').textContent = texts[lang].intro[1];
      document.querySelector('#works h2').textContent = texts[lang].works;
      document.querySelector('#about h2').textContent = texts[lang].about[0];
      document.querySelector('#about p').textContent = texts[lang].about[1];
      document.querySelector('#contact h2').textContent = texts[lang].contact;
      const form = document.querySelector('form');
      form.children[0].placeholder = texts[lang].placeholderName;
      form.children[2].placeholder = texts[lang].placeholderEmail;
      form.children[4].placeholder = texts[lang].placeholderMessage;
      form.children[6].textContent = texts[lang].send;

      if (lang === 'en') {
        document.documentElement.lang = 'en';
        document.documentElement.dir = 'ltr';
      } else {
        document.documentElement.lang = 'ar';
        document.documentElement.dir = 'rtl';
      }
    }
  </script></body>
</html><!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>H shpy | معرض الأعمال</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(to left, #007BFF, #FFA500);
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav button {
      background: none;
      border: none;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      margin-left: 1rem;
    }
    section {
      padding: 2rem;
    }
    .works {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .work {
      background: white;
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>H shpy</h1>
    <nav>
      <button onclick="setLang('ar')">العربية</button>
      <button onclick="setLang('en')">English</button>
    </nav>
  </header>
  <main>
    <section id="intro">
      <h2>مرحبًا بكم في معرض أعمالي</h2>
      <p>هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير.</p>
    </section><section id="works">
  <h2>أعمالي</h2>
  <div class="works">
    <div class="work">
      <h3>مشروع 1</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
    <div class="work">
      <h3>مشروع 2</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
  </div>
</section>

<section id="about">
  <h2>من أنا؟</h2>
  <p>مصمم ومطور مواقع مهتم بعرض أعمالي للعالم.</p>
</section>

<section id="contact">
  <h2>تواصل معي</h2>
  <form>
    <input type="text" placeholder="الاسم" required><br><br>
    <input type="email" placeholder="البريد الإلكتروني" required><br><br>
    <textarea placeholder="رسالتك"></textarea><br><br>
    <button type="submit">إرسال</button>
  </form>
</section>

  </main>  <footer>
    &copy; 2025 H shpy
  </footer>  <script>
    const texts = {
      ar: {
        intro: ["مرحبًا بكم في معرض أعمالي", "هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير."],
        works: "أعمالي",
        about: ["من أنا؟", "مصمم ومطور مواقع مهتم بعرض أعمالي للعالم."],
        contact: "تواصل معي",
        placeholderName: "الاسم",
        placeholderEmail: "البريد الإلكتروني",
        placeholderMessage: "رسالتك",
        send: "إرسال"
      },
      en: {
        intro: ["Welcome to My Portfolio", "Here are some of my best design and development projects."],
        works: "My Work",
        about: ["About Me", "I'm a web designer and developer passionate about showcasing my work to the world."],
        contact: "Contact Me",
        placeholderName: "Name",
        placeholderEmail: "Email",
        placeholderMessage: "Your Message",
        send: "Send"
      }
    };

    function setLang(lang) {
      document.querySelector('#intro h2').textContent = texts[lang].intro[0];
      document.querySelector('#intro p').textContent = texts[lang].intro[1];
      document.querySelector('#works h2').textContent = texts[lang].works;
      document.querySelector('#about h2').textContent = texts[lang].about[0];
      document.querySelector('#about p').textContent = texts[lang].about[1];
      document.querySelector('#contact h2').textContent = texts[lang].contact;
      const form = document.querySelector('form');
      form.children[0].placeholder = texts[lang].placeholderName;
      form.children[2].placeholder = texts[lang].placeholderEmail;
      form.children[4].placeholder = texts[lang].placeholderMessage;
      form.children[6].textContent = texts[lang].send;

      if (lang === 'en') {
        document.documentElement.lang = 'en';
        document.documentElement.dir = 'ltr';
      } else {
        document.documentElement.lang = 'ar';
        document.documentElement.dir = 'rtl';
      }
    }
  </script></body>
</html><!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>H shpy | معرض الأعمال</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(to left, #007BFF, #FFA500);
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav button {
      background: none;
      border: none;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      margin-left: 1rem;
    }
    section {
      padding: 2rem;
    }
    .works {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .work {
      background: white;
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>H shpy</h1>
    <nav>
      <button onclick="setLang('ar')">العربية</button>
      <button onclick="setLang('en')">English</button>
    </nav>
  </header>
  <main>
    <section id="intro">
      <h2>مرحبًا بكم في معرض أعمالي</h2>
      <p>هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير.</p>
    </section><section id="works">
  <h2>أعمالي</h2>
  <div class="works">
    <div class="work">
      <h3>مشروع 1</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
    <div class="work">
      <h3>مشروع 2</h3>
      <p>وصف قصير للمشروع.</p>
    </div>
  </div>
</section>

<section id="about">
  <h2>من أنا؟</h2>
  <p>مصمم ومطور مواقع مهتم بعرض أعمالي للعالم.</p>
</section>

<section id="contact">
  <h2>تواصل معي</h2>
  <form>
    <input type="text" placeholder="الاسم" required><br><br>
    <input type="email" placeholder="البريد الإلكتروني" required><br><br>
    <textarea placeholder="رسالتك"></textarea><br><br>
    <button type="submit">إرسال</button>
  </form>
</section>

  </main>  <footer>
    &copy; 2025 H shpy
  </footer>  <script>
    const texts = {
      ar: {
        intro: ["مرحبًا بكم في معرض أعمالي", "هنا أعرض بعضًا من مشاريعي المميزة في التصميم والتطوير."],
        works: "أعمالي",
        about: ["من أنا؟", "مصمم ومطور مواقع مهتم بعرض أعمالي للعالم."],
        contact: "تواصل معي",
        placeholderName: "الاسم",
        placeholderEmail: "البريد الإلكتروني",
        placeholderMessage: "رسالتك",
        send: "إرسال"
      },
      en: {
        intro: ["Welcome to My Portfolio", "Here are some of my best design and development projects."],
        works: "My Work",
        about: ["About Me", "I'm a web designer and developer passionate about showcasing my work to the world."],
        contact: "Contact Me",
        placeholderName: "Name",
        placeholderEmail: "Email",
        placeholderMessage: "Your Message",
        send: "Send"
      }
    };

    function setLang(lang) {
      document.querySelector('#intro h2').textContent = texts[lang].intro[0];
      document.querySelector('#intro p').textContent = texts[lang].intro[1];
      document.querySelector('#works h2').textContent = texts[lang].works;
      document.querySelector('#about h2').textContent = texts[lang].about[0];
      document.querySelector('#about p').textContent = texts[lang].about[1];
      document.querySelector('#contact h2').textContent = texts[lang].contact;
      const form = document.querySelector('form');
      form.children[0].placeholder = texts[lang].placeholderName;
      form.children[2].placeholder = texts[lang].placeholderEmail;
      form.children[4].placeholder = texts[lang].placeholderMessage;
      form.children[6].textContent = texts[lang].send;

      if (lang === 'en') {
        document.documentElement.lang = 'en';
        document.documentElement.dir = 'ltr';
      } else {
        document.documentElement.lang = 'ar';
  ![Uploading file_000000003158622fa801f6f2f578a05a_conversation_id=67fcf24a-0814-8012-861a-545a1f788b50&message_id=7e4c2daf-a986-4082-ad92-f04f1b7febc5.png…]()
      document.documentElement.dir = 'rtl';
      }
    }
  </script></body>
</html>
