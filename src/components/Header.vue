<template>
  <nav class="bg-white border-gray-200 dark:bg-gray-900">
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4 py-6"
    >
      <router-link to="/" class="flex items-center">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="32"
          height="32"
          viewBox="0 0 48 48"
        >
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M20.81 18.422c-.676-2.739-.57-4.269-.57-4.269M24 18.422v-4.269m-13.33.384c-.711-1.53-.433-5.397-.433-5.397c2.134 1.85 2.105 3.76 2.105 3.76l-1.672 1.637Z"
          />
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M31.602 14.003s4.803-7.614 6.973-8.503c2.277 3.415 1.853 7.7 1.853 10.788v23.474A2.738 2.738 0 0 1 37.69 42.5H10.31a2.738 2.738 0 0 1-2.738-2.738V16.288c0-3.088-.424-7.373 1.853-10.788c2.17.89 6.973 8.503 6.973 8.503h15.204Z"
          />
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M27.19 18.422c.676-2.739.57-4.269.57-4.269m9.57.384c.711-1.53.433-5.397.433-5.397c-2.134 1.85-2.105 3.76-2.105 3.76l1.672 1.637Z"
          />
          <circle
            cx="14.264"
            cy="24.119"
            r="2.38"
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M33.452 42.5c0-8.883-4.301-14.23-7.1-16.768a3.507 3.507 0 0 0-4.704 0c-2.8 2.539-7.1 7.885-7.1 16.768"
          />
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M27.765 33.102c-2.14-.851-2.832-1.474-3.765-3.081c-.933 1.607-1.625 2.23-3.765 3.08"
          />
          <circle
            cx="33.736"
            cy="24.119"
            r="2.38"
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
        </svg>
      </router-link>
      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
        aria-controls="navbar-default"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul
          class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700"
        >
          <li>
            <router-link
              to="/"
              class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Home</router-link
            >
          </li>
          <li>
            <router-link
              to="/blogs"
              class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >blogs</router-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
