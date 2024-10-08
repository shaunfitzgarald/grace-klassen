```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grace Klassen Marketing Solutions</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
    body {
      font-family: 'Bebas Neue', sans-serif;
    }
  </style>
</head>
<body class="bg-white text-black">

  <!-- Navbar -->
  <nav class="bg-white text-black shadow">
    <div class="max-w-7xl mx-auto px-16 sm:px-24 lg:px-32">
      <div class="flex justify-between h-16">
        <div class="flex">
          <div class="flex-shrink-0 flex items-center">
            <img class="h-16" src="images/star.png" alt="Logo"> <!-- Ensure the star image is in the correct path -->
            <span class="ml-2 font-bold text-xl">Grace Klassen</span>
          </div>
        </div>
        <div class="hidden md:ml-6 md:flex md:items-center">
          <a href="#about" class="text-black hover:text-gray-700 px-3 py-2 rounded-md text-sm">About Me</a>
          <a href="#portfolio" class="text-black hover:text-gray-700 px-3 py-2 rounded-md text-sm">Portfolio</a>
          <a href="#contact" class="text-black hover:text-gray-700 px-3 py-2 rounded-md text-sm">Contact</a>
        </div>
      </div>
    </div>
  </nav>

  <!-- Main Image -->
 <section>
  <div>
    
  </div>
 </section>>

  <!-- Main Content -->
  <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
    
    <!-- About Me Section -->
    <section id="about" class="py-10">
      <h2 class="text-4xl font-bold text-left mb-6">About</h2>
      <img class="xs:h-36 sm:h-48 md:h-56 lg:h-82" src="images/grace.jpeg" alt="Grace Klassen">
      <div class="max-w-2xl mx-auto text-center">
        <p class="text-lg text-gray-700">Welcome to Grace Klassen Marketing Solutions. I specialize in providing top-notch marketing strategies that help businesses thrive in a competitive market. With a focus on creativity, innovation, and results, I am dedicated to helping you achieve your marketing goals.</p>
      </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-10 bg-gray-100">
      <h2 class="text-4xl font-bold text-center mb-6">Portfolio</h2>
      <div class="flex justify-center flex-wrap">
        <div class="w-full md:w-1/3 p-4">
          <img class="w-full h-64 object-cover mb-4" src="images/project1.jpg" alt="Project 1"> <!-- Ensure project images are in the correct path -->
          <iframe class="w-full h-64 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_1" frameborder="0" allowfullscreen></iframe>
          <a href="https://www.instagram.com/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-instagram text-2xl"></i> Instagram</a>
        </div>
        <div class="w-full md:w-1/3 p-4">
          <img class="w-full h-64 object-cover mb-4" src="images/project2.jpg" alt="Project 2">
          <iframe class="w-full h-64 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_2" frameborder="0" allowfullscreen></iframe>
          <a href="https://www.twitter.com/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-twitter text-2xl"></i> Twitter</a>
        </div>
        <div class="w-full md:w-1/3 p-4">
          <img class="w-full h-64 object-cover mb-4" src="images/project3.jpg" alt="Project 3">
          <iframe class="w-full h-64 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_3" frameborder="0" allowfullscreen></iframe>
          <a href="https://www.linkedin.com/in/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-linkedin text-2xl"></i> LinkedIn</a>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-10">
      <h2 class="text-4xl font-bold text-center mb-6">Contact</h2>
      <div class="max-w-3xl mx-auto">
        <div class="mb-6">
          <div class="calendly-inline-widget" data-url="https://calendly.com/YOUR_CALENDLY_URL" style="min-width:320px;height:630px;"></div>
          <script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
        </div>
        <form action="#" method="POST" class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="name">
              Name
            </label>
            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="name" type="text" placeholder="Your name">
          </div>
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="email">
              Email
            </label>
            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email" type="email" placeholder="Your email">
          </div>
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="message">
              Message
            </label>
            <textarea class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="message" placeholder="Your message"></textarea>
          </div>
          <div class="flex items-center justify-between">
            <button class="bg-black hover:bg-gray-800 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
              Send
            </button>
          </div>
        </form>
      </div>
    </section>
  </main>

</body>
</html>

```html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grace Klassen Marketing Solutions</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
    body {
      font-family: 'Bebas Neue', sans-serif;
    }
  </style>
</head>
<body class="bg-white text-black">

  <!-- Navbar -->
  <nav class="bg-white text-black shadow">
    <div class="max-w-7xl mx-auto px-16 sm:px-24 lg:px-32">
      <div class="flex justify-between h-16">
        <div class="flex">
          <div class="flex-shrink-0 flex items-center">
            <img class="h-8 w-8" src="images/star.png" alt="Logo"> <!-- Ensure the star image is in the correct path -->
            <span class="ml-2 font-bold text-xl">Grace Klassen Marketing Solutions</span>
          </div>
        </div>
        <div class="hidden md:ml-6 md:flex md:items-center">
          <a href="#about" class="text-black hover:text-gray-700 px-3 py-2 rounded-md text-sm">About Me</a>
          <a href="#portfolio" class="text-black hover:text-gray-700 px-3 py-2 rounded-md text-sm">Portfolio</a>
          <a href="#contact" class="text-black hover:text-gray-700 px-3 py-2 rounded-md text-sm">Contact</a>
        </div>
      </div>
    </div>
  </nav>

  <!-- Main Image -->
  

  <!-- Main Content -->
  <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
    
    <!-- About Me Section -->
    <section id="about" class="py-10">
      <h2 class="text-4xl font-bold text-left mb-6">About</h2>
      <div class="flex flex-col items-center lg:flex-row lg:items-start">
        <img class="w-full lg:w-1/3 h-auto mb-6 lg:mb-0 lg:mr-6 rounded-lg" src="images/grace.jpeg" alt="Grace Klassen"> <!-- Ensure Grace's photo is in the correct path -->
        <div class="max-w-2xl mx-auto text-left">
          <p class="text-lg text-gray-700">Welcome to Grace Klassen Marketing Solutions. I specialize in providing top-notch marketing strategies that help businesses thrive in a competitive market. With a focus on creativity, innovation, and results, I am dedicated to helping you achieve your marketing goals.</p>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-10">
      <h2 class="text-4xl font-bold text-center mb-6">Services</h2>
      <div class="max-w-7xl mx-auto px-4">
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
          <div class="text-center">
            <i class="fas fa-bullseye text-4xl mb-4"></i>
            <h3 class="text-xl font-semibold mb-2">Strategy and Planning</h3>
            <p class="text-gray-700">Developing comprehensive marketing strategies to achieve your business goals.</p>
          </div>
          <div class="text-center">
            <i class="fas fa-pen-nib text-4xl mb-4"></i>
            <h3 class="text-xl font-semibold mb-2">Content Creation</h3>
            <p class="text-gray-700">Creating engaging content to captivate your audience and drive traffic.</p>
          </div>
          <div class="text-center">
            <i class="fas fa-edit text-4xl mb-4"></i>
            <h3 class="text-xl font-semibold mb-2">Copywriting and Editing</h3>
            <p class="text-gray-700">Crafting compelling copy and editing content to perfection.</p>
          </div>
          <div class="text-center">
            <i class="fas fa-code text-4xl mb-4"></i>
            <h3 class="text-xl font-semibold mb-2">Website Development</h3>
            <p class="text-gray-700">Building professional websites that drive business success.</p>
          </div>
          <div class="text-center">
            <i class="fas fa-video text-4xl mb-4"></i>
            <h3 class="text-xl font-semibold mb-2">Video Editing</h3>
            <p class="text-gray-700">Editing videos to tell your brand’s story effectively.</p>
          </div>
          <div class="text-center">
            <i class="fas fa-paint-brush text-4xl mb-4"></i>
            <h3 class="text-xl font-semibold mb-2">Graphic Design</h3>
            <p class="text-gray-700">Designing visually appealing graphics for your marketing materials.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-10 bg-gray-100">
      <h2 class="text-4xl font-bold text-center mb-6">Portfolio</h2>
      
      <div class="space-y-8">
        <!-- Project 1 -->
        <div class="w-full p-4">
          <h3 class="text-2xl font-semibold mb-2">Project 1</h3>
          <iframe src="https://drive.google.com/file/d/1FWL3-LwqJNeBQCDpvBDiSfv2cIAA2bar/preview" class="w-full h-72 mb-4" allow="autoplay"></iframe>
        </div>
        <!-- Project 2 -->
        <div class="w-full p-4">
          <h3 class="text-2xl font-semibold mb-2">Project 2</h3>
          <img class="w-full h-64 object-cover mb-4" src="images/project2.jpg" alt="Project 2">
          <href="https://keystonepacking.org" class="text-black hover:text-gray-700"><i class="fas fa-link text-2xl">Keystone Packing</i></a>
          <iframe class="w-full h-72 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_2" frameborder="0" allowfullscreen></iframe>
          <a href="https://www.facebook.com/people/Keystone-Packing/61559563343479/" class="text-black hover:text-gray-700">Keystone Packing Facebook<i class="fab fa-facebook text-2xl"></i></a>
          <a href="https://www.instagram.com/keystonepacking" class="text-black hover:text-gray-700"><i class="fab fa-instagram text-2xl">Keystone Packing Instagram</i></a>
        </div>
        <!-- Project 3 -->
        <div class="w-full p-4">
          <h3 class="text-2xl font-semibold mb-2">Project 3</h3>
          <img class="w-full h-64 object-cover mb-4" src="images/project3.jpg" alt="Project 3">
          <iframe class="w-full h-72 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_3" frameborder="0" allowfullscreen></iframe>
        </div>
        <!-- Project 4 -->
        <div class="w-full p-4">
          <h3 class="text-2xl font-semibold mb-2">Project 4</h3>
          <img class="w-full h-64 object-cover mb-4" src="images/project4.jpg" alt="Project 4">
          <iframe class="w-full h-72 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_4" frameborder="0" allowfullscreen></iframe>
        </div>
        <!-- Project 5 -->
        <div class="w-full p-4">
          <h3 class="text-2xl font-semibold mb-2">Project 5</h3>
          <img class="w-full h-72 object-cover mb-4" src="images/project5.jpg" alt="Project 5">
          <iframe class="w-full h-64 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_5" frameborder="0" allowfullscreen></iframe>
        </div>
        <!-- Project 6 -->
        <div class="w-full p-4">
          <h3 class="text-2xl font-semibold mb-2">Project 6</h3>
          <img class="w-full h-72 object-cover mb-4" src="images/project6.jpg" alt="Project 6">
          <iframe class="w-full h-64 mb-4" src="https://www.youtube.com/embed/VIDEO_ID_6" frameborder="0" allowfullscreen></iframe>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-10">
      <h2 class="text-4xl font-bold text-center mb-6">Contact</h2>
      <div class="max-w-3xl mx-auto">
        <div class="mb-6">
          <div class="calendly-inline-widget" data-url="https://calendly.com/YOUR_CALENDLY_URL" style="min-width:320px;height:630px;"></div>
          <script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
        </div>
        <form action="#" method="POST" class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="name">
              Name
            </label>
            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="name" type="text" placeholder="Your name">
          </div>
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="email">
              Email
            </label>
            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email" type="email" placeholder="Your email">
          </div>
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="message">
              Message
            </label>
            <textarea class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="message" placeholder="Your message"></textarea>
          </div>
          <div class="flex items-center justify-between">
            <button class="bg-black hover:bg-gray-800 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
              Send
            </button>
          </div>
        </form>
      </div>
    </section>
    
    <!-- Footer -->
    <footer class="bg-white text-black py-4">
      <div class="max-w-7xl mx-auto px-4">
        <a href="https://www.instagram.com/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-instagram text-2xl"></i></a>
        <a href="https://www.twitter.com/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-twitter text-2xl"></i></a>
        <a href="https://www.linkedin.com/in/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-linkedin text-2xl"></i></a>
        <a href="https://www.facebook.com/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-facebook text-2xl"></i></a>
        <a href="https://www.pinterest.com/graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-pinterest text-2xl"></i></a>
        <a href="https://www.tiktok.com/@graceklassen" class="text-black hover:text-gray-700"><i class="fab fa-tiktok text-2xl"></i></a>
        <p class="text-center">© 2023 Grace Klassen. All rights reserved.</p>
      </div>
    </footer>
  </main>

</body>
</html>
```html