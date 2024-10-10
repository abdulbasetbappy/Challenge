<template>
    <header class="bg-white p-4 flex justify-between items-center">
      <!-- Left: Logo -->
      <div class="flex items-center space-x-2">
        <Icon name="ri:links-fill" class="bg-[#643cfd] w-6 h-6 rounded-md"/>
        <span class="font-semibold text-lg">devlinks</span>
      </div>
  
      <!-- Center: Navigation Links -->
      <nav class="flex space-x-6">
        <a
          href="#"
          class="flex items-center space-x-1 text-purple-600 font-medium hover:text-purple-800"
        >
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 14.828a4 4 0 005.657 0l1.414-1.414a4 4 0 000-5.657l-4.95-4.95a4 4 0 00-5.657 0L7.757 7.757a4 4 0 000 5.657l1.414 1.414" />
          </svg>
          <span>Links</span>
        </a>
  
        <a href="#" class="flex items-center space-x-1 text-gray-500 font-medium hover:text-gray-800">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor">
            <path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/>
          </svg>
          <span>Profile Details</span>
        </a>
      </nav>
  
      <!-- Right: Preview Button -->
      <div>
        <button class="px-4 py-2 text-purple-600 font-medium border border-purple-600 rounded-md hover:bg-purple-600 hover:text-white">
          Preview
        </button>
      </div>
    </header>
  </template>
  