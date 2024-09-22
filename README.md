<!DOCTYPE html>
<html lang="en">
<head>
  <title>Got Milk?</title>

  <!-- Include Tailwind CSS from CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Include FontAwesome from CDN -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400&display=swap');
    body {
      font-family: 'Roboto', sans-serif;
    }

    /* Navigation styling */
    .nav-link {
      margin: 0 15px;
      font-weight: 600;
    }

    .nav-link:hover {
      text-decoration: underline;
    }

    /* Styling for content blocks */
    .content-box {
      background-color: #f9f9f9;
      border: 1px solid #e5e7eb;
      padding: 20px;
      text-align: center;
      border-radius: 10px;
    }

    .content-box h3 {
      font-size: 1.25rem;
      font-weight: 700;
      margin-bottom: 10px;
    }

    .content-box p {
      font-size: 0.9rem;
      color: #4a5568;
    }

    /* Footer styling */
    footer {
      margin-top: 20px;
      text-align: center;
      padding: 10px 0;
      font-size: 0.8rem;
      color: #6b7280;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-900 flex flex-col items-center min-h-screen">
  <!-- Navigation Bar -->
  <nav class="bg-white shadow-md w-full py-4">
    <ul class="flex justify-center space-x-8 text-lg">
      <li class="nav-link">Got Milk?</li>
      <li class="nav-link">Recipes</li>
      <li class="nav-link">Store</li>
      <li class="nav-link">Fun</li>
      <li class="nav-link">News</li>
    </ul>
  </nav>

  <!-- Main Content Block -->
  <div class="mt-8 w-full max-w-4xl text-center">
    <h1 class="text-4xl font-bold mb-6">Welcome to Got Milk?</h1>
    <p class="text-lg text-gray-600 mb-4">
      Explore our collection of recipes, shop at our store, and stay updated with the latest milk news!
    </p>
  </div>

  <!-- Content Cards Section (replacing images with text-based content) -->
  <div class="mt-8 flex justify-center space-x-6 max-w-4xl">
    <!-- First Content Box -->
    <div class="content-box w-64">
      <h3>Recipes</h3>
      <p>Discover delicious, milk-based recipes that are perfect for any meal or occasion.</p>
    </div>

    <!-- Second Content Box -->
    <div class="content-box w-64">
      <h3>Store</h3>
      <p>Visit our store for a wide selection of dairy products and accessories.</p>
    </div>

    <!-- Third Content Box -->
    <div class="content-box w-64">
      <h3>Fun Facts</h3>
      <p>Learn interesting facts about milk and how it benefits your health.</p>
    </div>
  </div>

  <!-- Footer -->
  <footer class="w-full bg-white mt-12 py-4">
    <p>© 2024 Got Milk? All rights reserved. | Privacy Policy | Terms of Service</p>
  </footer>
</body>
</html>
