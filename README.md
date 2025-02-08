# ecobuildsolution.github.io
We are a dedicated construction company specializing in creating high quality, durable, and innovative structures.  Our goal is to build spaces that inspire and serve as strong foundations for your future.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Construction Company</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <nav class="bg-blue-700 text-white p-4 flex justify-between">
        <h1 class="text-xl font-bold">Construction Co.</h1>
        <ul class="flex gap-4">
            <li><a href="#home" class="hover:text-yellow-300">Home</a></li>
            <li><a href="#about" class="hover:text-yellow-300">About Us</a></li>
            <li><a href="#services" class="hover:text-yellow-300">Our Services</a></li>
            <li><a href="#projects" class="hover:text-yellow-300">Projects</a></li>
            <li><a href="#contact" class="hover:text-yellow-300">Contact</a></li>
        </ul>
    </nav>
    
    <section id="home" class="h-screen flex items-center justify-center bg-cover bg-center" style="background-image: url('https://source.unsplash.com/1600x900/?construction');">
        <div class="text-center bg-black bg-opacity-50 p-8 rounded-lg text-white">
            <h2 class="text-4xl font-bold">Building Your Dreams</h2>
            <p class="text-lg mt-4">High-quality construction services for every project</p>
        </div>
    </section>
    
    <section id="about" class="p-10 bg-white">
        <h2 class="text-3xl font-bold text-blue-700">About Us</h2>
        <p class="mt-4 text-gray-600">We are a leading construction company with years of experience in delivering top-tier infrastructure projects.</p>
    </section>
    
    <section id="services" class="p-10 bg-gray-200">
        <h2 class="text-3xl font-bold text-blue-700">Our Services</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-6">
            <div class="p-4 bg-white shadow rounded-lg">
                <h3 class="font-semibold">Residential Construction</h3>
                <p class="text-gray-600">High-quality homes built to last.</p>
            </div>
            <div class="p-4 bg-white shadow rounded-lg">
                <h3 class="font-semibold">Commercial Projects</h3>
                <p class="text-gray-600">Modern office spaces and buildings.</p>
            </div>
            <div class="p-4 bg-white shadow rounded-lg">
                <h3 class="font-semibold">Renovations</h3>
                <p class="text-gray-600">Transforming old spaces into new.</p>
            </div>
        </div>
    </section>
    
    <section id="projects" class="p-10 bg-white">
        <h2 class="text-3xl font-bold text-blue-700">Our Projects</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-6">
            <img src="https://source.unsplash.com/400x300/?building" class="rounded-lg shadow" alt="Project 1">
            <img src="https://source.unsplash.com/400x300/?construction-site" class="rounded-lg shadow" alt="Project 2">
            <img src="https://source.unsplash.com/400x300/?architecture" class="rounded-lg shadow" alt="Project 3">
        </div>
    </section>
    
    <section id="contact" class="p-10 bg-gray-200">
        <h2 class="text-3xl font-bold text-blue-700">Contact Us</h2>
        <form class="mt-6 bg-white p-6 rounded-lg shadow">
            <input type="text" placeholder="Your Name" class="w-full p-2 border rounded mb-4">
            <input type="email" placeholder="Your Email" class="w-full p-2 border rounded mb-4">
            <textarea placeholder="Your Message" class="w-full p-2 border rounded mb-4"></textarea>
            <button type="submit" class="bg-blue-700 text-white px-4 py-2 rounded hover:bg-blue-800">Send</button>
        </form>
    </section>
    
    <footer class="bg-blue-700 text-white text-center p-4 mt-10">
        &copy; 2025 Construction Co. All rights reserved.
    </footer>
</body>
</html>
