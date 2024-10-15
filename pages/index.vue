<template>
  <div class="md:flex md:justify-center md:items-center md:h-[100vh]">
    <div class="flex flex-col h-[100vh] md:flex-row md:h-[60%] md:w-[60%] md:shadow-md md:rounded-3xl">
      <div class="rounded-b-3xl md:rounded-3xl md:flex-1 h-[45%] md:h-[100%] w-[100%] bg-gradient-to-b from-[hsl(252,100%,67%)] to-[hsl(241,81%,54%)] flex flex-col items-center p-5">
        <p class="mb-5 text-[hsla(0,0%,100%,0.5)]">
          Your Result
        </p>
        <div class="rounded-full bg-gradient-to-b from-[hsla(256,72%,46%,1)] to-[hsla(241,72%,46%,0)] flex justify-center items-center w-[145px] h-[145px] flex-col mb-5">
          <p class="text-white text-[3.5rem] font-[700]">
            76
          </p>
          <p class="text-[hsl(241,100%,89%)] text-[16px] text-[hsla(0,0%,100%,0.5)]">
            of 100
          </p>
        </div>
        <p class="text-white text-[25px] font-[700]">
          Great
        </p>

        <p class="text-[16px] text-center w-[280px] text-[hsla(0,0%,100%,0.5)]">
          You scored higher than 65% of the people who have taken these tests.
        </p>
      </div>
      <div class="flex flex-col p-5 gap-[20px] md:flex-1 md:p-8">
        <p class="md:text-[1.5rem]">Summary</p>
        <div class="flex items-center justify-between bg-[hsla(0,100%,67%,0.1)] p-4 rounded-xl">
          <div class="flex items-center">
            <img src="/images/icon-reaction.svg" alt="Icon Reaction">
            <p class="ml-[15px] text-[16px] text-[hsl(0,100%,67%)] font-[700]">
              Reaction
            </p>
          </div>
          <p>80 <span class="text-[hsla(0,100%,0%,0.4)]">/ 100</span></p>
        </div>
        <div class="flex items-center justify-between bg-[hsla(39,100%,56%,0.1)] p-4 rounded-xl">
          <div class="flex items-center">
            <img src="/images/icon-memory.svg" alt="Icon Reaction">
            <p class="ml-[15px] text-[16px] text-[hsl(39,100%,56%)] font-[700]">
              Memory
            </p>
          </div>
          <p>92 <span class="text-[hsla(0,100%,0%,0.4)]">/ 100</span></p>
        </div>
        <div class="flex items-center justify-between bg-[hsla(166,100%,37%,0.1)] p-4 rounded-xl">
          <div class="flex items-center">
            <img src="/images/icon-verbal.svg" alt="Icon Reaction">
            <p class="ml-[15px] text-[16px] text-[hsl(166,100%,37%)] font-[700]">
              Verbal
            </p>
          </div>
          <p>61 <span class="text-[hsla(0,100%,0%,0.4)]">/ 100</span></p>
        </div>
        <div class="flex items-center justify-between bg-[hsla(234,85%,45%,0.1)] p-4 rounded-xl">
          <div class="flex items-center">
            <img src="/images/icon-visual.svg" alt="Icon Reaction">
            <p class="ml-[15px] text-[16px] text-[hsl(234,85%,45%)] font-[700]">
              Visual
            </p>
          </div>
          <p>72 <span class="text-[hsla(0,100%,0%,0.4)]">/ 100</span></p>
        </div>
        <button class="bg-[hsl(224,30%,27%)] p-4 rounded-full text-[hsl(0,0%,100%)]">
          Continue
        </button>
      </div>
    </div>
  </div>

  <!-- <div>

    Memory
    92 / 100

    Verbal
    61 / 100

    Visual
    72 / 100

    Continue

    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
      Coded by <a href="#">Your Name Here</a>.
    </div>
  </div> -->
</template>
