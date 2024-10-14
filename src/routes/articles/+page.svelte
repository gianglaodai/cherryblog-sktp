<div class="mx-auto max-w-5xl px-6">
  <h1 class="text-title font-black text-blue-700">My Articles</h1>
  <div class="articles">
    <article>
      <h2 class="mb-4 text-3xl font-bold text-gray-900">My experience attending at CSS Day 2024</h2>
      <p class="mb-4 leading-relaxed text-gray-700">
        I’ve written and rewritten this post about five times now. This version seems to be the one
        to finally stick, though it’s taken a bit of a different direction than I was originally
        planning. In it, I talk about my experience attending CSS Day, both as an attendee, which
        was the original plan, but also as a well-known figure.
      </p>
      <p class="mb-4 text-blue-500 underline">
        Last week, I posted about
        <a href="#" class="hover:text-blue-700">my experience speaking at CSS Day 2024</a>
        .
      </p>
      <p class="mb-6 font-semibold">
        The <span class="font-bold">best</span>
        part about being a speaker, though, was finally being able to attend CSS Day!
      </p>
      <a href="#" class="rounded-full bg-blue-600 px-6 py-2 text-white hover:bg-blue-700">
        Read More
      </a>
    </article>

    <!-- Article 2 -->
    <article class="mb-12">
      <h2 class="mb-4 text-3xl font-bold text-gray-900">My experience talking at CSS Day 2024</h2>
      <p class="mb-4 leading-relaxed text-gray-700">
        So, it’s been a minute (or like, 3 years...) since I last posted something here, and it
        probably will be a while before I post again to be honest. This post turned out to be way
        too long to include as the introduction to my newsletter, so I broke it off here.
      </p>
      <p class="mb-4 text-blue-500 underline">
        I’ll have a follow-up at one point about my experience attending it as well. <a
          href="#"
          class="hover:text-blue-700">
          my recent experience at CSS Day 2024
        </a>
        .
      </p>
      <a href="#" class="rounded-full bg-blue-600 px-6 py-2 text-white hover:bg-blue-700">
        Read More
      </a>
    </article>
  </div>
</div>

<style>
  .articles > article:first-of-type {
    @apply mt-20;
  }

  .articles > article:not(:last-child) {
    @apply mt-3;
  }

  .articles > article:not(:last-child)::after {
    @apply relative bottom-0 left-0 right-0 top-0 my-24 block border-b-2 border-solid border-b-neutral-300;
    content: '';
  }
</style>
