<template>
  <div>
    <label class="block text-sm font-medium text-gray-700 dark:text-gray-200">
      Foto
    </label>
    <div
      class="
        mt-1
        flex
        justify-center
        px-6
        pt-5
        pb-6
        border-2 border-gray-300
        dark:border-gray-600
        border-dashed
        rounded-md
      "
    >
      <div class="space-y-1 text-center">
        <svg
          class="mx-auto h-12 w-12 text-gray-400 dark:text-gray-500"
          stroke="currentColor"
          fill="none"
          viewBox="0 0 48 48"
          aria-hidden="true"
        >
          <path
            d="M28 8H12a4 4 0 00-4 4v20m32-12v8m0 0v8a4 4 0 01-4 4H12a4 4 0 01-4-4v-4m32-4l-3.172-3.172a4 4 0 00-5.656 0L28 28M8 32l9.172-9.172a4 4 0 015.656 0L28 28m0 0l4 4m4-24h8m-4-4v8m-12 4h.02"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
        </svg>
        <div class="flex text-sm text-gray-600 dark:text-gray-300">
          <label
            for="file-upload"
            class="
              relative
              cursor-pointer
              bg-transparent
              rounded-md
              font-medium
              text-yellow-600
              dark:text-yellow-500
              hover:text-yellow-500
              focus-within:outline-none
              focus-within:ring-2
              focus-within:ring-offset-2
              focus-within:ring-yellow-500
            "
          >
            <span>Upload a file</span>
            <input
              id="file-upload"
              name="file-upload"
              type="file"
              class="sr-only"
            />
          </label>
          <p class="pl-1">or drag and drop</p>
        </div>
        <p class="text-xs text-gray-500 dark:text-gray-400">
          PNG, JPG, GIF up to 10MB
        </p>
      </div>
    </div>
  </div>
</template>
