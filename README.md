# project

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Web Developer Landing Page</title>
<link rel="icon" href="my-image.jpg/esther.jpg" type="image/jpeg">
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
<style>
/* Custom Styles */
.hero {
background: url('path-to-your-hero-background.jpg') no-repeat center center/cover;
color: #3d12da; }
</style>
</head>
<body class="font-sans bg-gray-100">
<!-- Header -->
<header class="bg-blue-600 text-white flex justify-between items-center p-4">
<div class="text-2xl font-bold">YourLogo</div>
<nav>
<ul class="flex space-x-4">
<li><a href="index.html" class="hover:underline">Home</a></li>
<li><a href="about.html" class="hover:underline">About Me</a></li>
</ul>
</nav>
</header>

<!-- Main Content -->
<main>
<!-- Hero Section -->
<section class="hero text-white text-center p-16">
<div class="container mx-auto">
<h1 class="text-4xl md:text-5xl font-bold mb-4">Hi, I'm Favour amakwe </h1>
<p class="text-lg md:text-xl mb-6">A passionate web developer.</p>
<img src="my-image.jpg/esther.jpg" alt="esther" class="mx-auto rounded-full w-100 h-100 object-cover" >
</div>
</section>

<!-- Skills Section -->
<section class="p-8">
<div class="container mx-auto">
<h2 class="text-3xl font-bold mb-6 text-center">Skills</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
<div class="bg-white p-6 shadow-md rounded-lg">
<h3 class="text-xl font-semibold mb-2">HTML</h3>
<p>Experienced in creating structured, semantic HTML.</p>
</div>
<div class="bg-white p-6 shadow-md rounded-lg">
<h3 class="text-xl font-semibold mb-2">CSS</h3>
<p>Proficient in styling with TailwindCSS and custom CSS.</p>
</div>
<div class="bg-white p-6 shadow-md rounded-lg">
<h3 class="text-xl font-semibold mb-2">JavaScript</h3>
<p>Skilled in client-side scripting and interactivity.</p>
</div>
<div class="bg-white p-6 shadow-md rounded-lg">
<h3 class="text-xl font-semibold mb-2">React</h3>
<p>Experienced with building dynamic user interfaces with React.</p>
</div>
</div>
</div>
</section>
</main>
</body>
</html>
