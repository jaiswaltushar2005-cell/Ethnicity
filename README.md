<!DOCTYPE html>
<html lang="en"><head>
<meta charset="utf-8"/>
<link crossorigin="" href="https://fonts.gstatic.com/" rel="preconnect"/>
<link as="style" href="https://fonts.googleapis.com/css2?display=swap&amp;family=Be+Vietnam+Pro%3Awght%40400%3B500%3B700%3B900&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900" onload="this.rel='stylesheet'" rel="stylesheet"/>
<title>Ethnic Threads</title>
<link href="data:image/x-icon;base64," rel="icon" type="image/x-icon"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script>
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              primary: "#ec1337",
              "background-light": "#f8f6f6",
              "background-dark": "#221013",
            },
            fontFamily: {
              display: ["Be Vietnam Pro"],
            },
            borderRadius: { DEFAULT: "0.25rem", lg: "0.5rem", xl: "0.75rem", full: "9999px" },
          },
        },
      };
    </script>
<style>
      .range-slider {
        --thumb-size: 1rem;
        --track-height: 0.25rem;
        --track-color: #e5e7eb;
        --track-color-dark: #374151;
        --progress-color: #ec1337;
      }
      .range-slider input[type="range"] {
        -webkit-appearance: none;
        appearance: none;
        width: 100%;
        height: var(--thumb-size);
        background-color: transparent;
        pointer-events: none;
      }
      .range-slider input[type="range"]::-webkit-slider-thumb {
        -webkit-appearance: none;
        appearance: none;
        width: var(--thumb-size);
        height: var(--thumb-size);
        background-color: var(--progress-color);
        border-radius: 9999px;
        pointer-events: auto;
        cursor: pointer;
      }
      .dark .range-slider input[type="range"]::-webkit-slider-thumb {
        background-color: var(--progress-color);
      }
      .range-slider input[type="range"]::-moz-range-thumb {
        width: var(--thumb-size);
        height: var(--thumb-size);
        background-color: var(--progress-color);
        border: none;
        border-radius: 9999px;
        pointer-events: auto;
        cursor: pointer;
      }
      .range-slider_track {
        position: absolute;
        width: 100%;
        height: var(--track-height);
        top: 50%;
        transform: translateY(-50%);
        background-color: var(--track-color);
        border-radius: 9999px;
      }
      .dark .range-slider_track {
         background-color: var(--track-color-dark);
      }
      .range-slider_progress {
        position: absolute;
        height: var(--track-height);
        background-color: var(--progress-color);
        border-radius: 9999px;
        top: 50%;
        transform: translateY(-50%);
      }
    </style>
</head>
<body class="bg-background-light dark:bg-background-dark font-display">
<div class="flex h-auto min-h-screen w-full flex-col text-stone-900 dark:text-stone-100">
<div class="flex h-full grow flex-col">
<header class="flex items-center justify-between whitespace-nowrap border-b border-primary/20 dark:border-primary/30 px-10 py-3">
<div class="flex items-center gap-8">
<div class="flex items-center gap-3 text-stone-900 dark:text-stone-100">
<div class="h-6 w-6 text-primary">
<svg fill="none" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
<path clip-rule="evenodd" d="M24 4H42V17.3333V30.6667H24V44H6V30.6667V17.3333H24V4Z" fill="currentColor" fill-rule="evenodd"></path>
</svg>
</div>
<h2 class="text-xl font-bold">Ethnic Threads</h2>
</div>
<nav class="hidden md:flex items-center gap-8">
<a class="text-sm font-medium hover:text-primary" href="#">New Arrivals</a>
<a class="text-sm font-medium hover:text-primary" href="#">Categories</a>
<a class="text-sm font-medium hover:text-primary" href="#">Sale</a>
<a class="text-sm font-medium hover:text-primary" href="#">About Us</a>
</nav>
</div>
<div class="flex items-center justify-end gap-4">
<label class="relative hidden sm:block">
<div class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3">
<svg class="h-5 w-5 text-stone-500 dark:text-stone-400" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
<path d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" stroke-linecap="round" stroke-linejoin="round"></path>
</svg>
</div>
<input class="form-input w-full min-w-0 rounded-lg border-primary/20 bg-background-light dark:bg-background-dark dark:border-primary/30 py-2 pl-10 pr-4 text-sm placeholder:text-stone-500 dark:placeholder:text-stone-400 focus:border-primary focus:ring-primary" placeholder="Search" type="search"/>
</label>
<div class="flex items-center gap-2">
<button class="flex h-10 w-10 cursor-pointer items-center justify-center overflow-hidden rounded-lg bg-primary/10 text-stone-900 dark:bg-primary/20 dark:text-stone-100 hover:bg-primary/20 dark:hover:bg-primary/30">
<svg fill="currentColor" height="20px" viewBox="0 0 256 256" width="20px" xmlns="http://www.w3.org/2000/svg">
<path d="M178,32c-20.65,0-38.73,8.88-50,23.89C116.73,40.88,98.65,32,78,32A62.07,62.07,0,0,0,16,94c0,70,103.79,126.66,108.21,129a8,8,0,0,0,7.58,0C136.21,220.66,240,164,240,94A62.07,62.07,0,0,0,178,32ZM128,206.8C109.74,196.16,32,147.69,32,94A46.06,46.06,0,0,1,78,48c19.45,0,35.78,10.36,42.6,27a8,8,0,0,0,14.8,0c6.82-16.67,23.15-27,42.6-27a46.06,46.06,0,0,1,46,46C224,147.61,146.24,196.15,128,206.8Z"></path>
</svg>
</button>
<button class="flex h-10 w-10 cursor-pointer items-center justify-center overflow-hidden rounded-lg bg-primary/10 text-stone-900 dark:bg-primary/20 dark:text-stone-100 hover:bg-primary/20 dark:hover:bg-primary/30">
<svg fill="currentColor" height="20px" viewBox="0 0 256 256" width="20px" xmlns="http://www.w3.org/2000/svg">
<path d="M216,40H40A16,16,0,0,0,24,56V200a16,16,0,0,0,16,16H216a16,16,0,0,0,16-16V56A16,16,0,0,0,216,40Zm0,160H40V56H216V200ZM176,88a48,48,0,0,1-96,0,8,8,0,0,1,16,0,32,32,0,0,0,64,0,8,8,0,0,1,16,0Z"></path>
</svg>
</button>
</div>
<div class="h-10 w-10 rounded-full bg-cover bg-center bg-no-repeat" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuBfL7FuG916VOs7cFFX6Y4Bg0qQ1PkmwlQuz0nf_0vV0ninM1Ay5_p0H6zpjPFUuMMl9-cuYMkiljwIbdiwX_hPUHRdXYMnO4NyPCLCaLZiux05pZ6CTZMyvnPzwu_7LyUAXNKg2ASmpEbxx9ozcHjmf_87Skoa4Xi4uQghwA_93vwc5-vE6hVBXT-ni-OmH9AuCVu4wnhJokeVAsC6SBUmii1b5v4enBoVCSA0VISXU-2RhJgvR-DUeG1qHyu3lsegtmzp1V7QTE4");'></div>
</div>
</header>
<main class="flex flex-1">
<aside class="w-80 flex-shrink-0 border-r border-primary/20 dark:border-primary/30 p-6">
<h2 class="text-2xl font-bold tracking-tight">Filters</h2>
<div class="mt-6 space-y-8">
<div>
<h3 class="text-lg font-bold">Category</h3>
<div class="mt-4 space-y-3">
<label class="flex items-center gap-3">
<input class="h-5 w-5 rounded border-primary/30 bg-transparent text-primary focus:ring-primary focus:ring-offset-background-light dark:focus:ring-offset-background-dark" type="checkbox"/>
<span class="text-sm">Kurtis</span>
</label>
<label class="flex items-center gap-3">
<input class="h-5 w-5 rounded border-primary/30 bg-transparent text-primary focus:ring-primary focus:ring-offset-background-light dark:focus:ring-offset-background-dark" type="checkbox"/>
<span class="text-sm">Sarees</span>
</label>
<label class="flex items-center gap-3">
<input class="h-5 w-5 rounded border-primary/30 bg-transparent text-primary focus:ring-primary focus:ring-offset-background-light dark:focus:ring-offset-background-dark" type="checkbox"/>
<span class="text-sm">Lehengas</span>
</label>
</div>
</div>
<div>
<h3 class="text-lg font-bold">Price Range</h3>
<div class="range-slider mt-4">
<div class="relative h-4">
<div class="range-slider_track"></div>
<div class="range-slider_progress" style="left: 20%; right: 40%"></div>
<input max="1000" min="0" type="range" value="200"/>
<input max="1000" min="0" type="range" value="600"/>
</div>
<div class="mt-2 flex justify-between text-sm">
<span>$200</span>
<span>$600</span>
</div>
</div>
</div>
<div>
<h3 class="text-lg font-bold">Size</h3>
<div class="mt-4 space-y-3">
<label class="flex items-center gap-3">
<input class="h-5 w-5 rounded border-primary/30 bg-transparent text-primary focus:ring-primary focus:ring-offset-background-light dark:focus:ring-offset-background-dark" type="checkbox"/>
<span class="text-sm">S</span>
</label>
<label class="flex items-center gap-3">
<input class="h-5 w-5 rounded border-primary/30 bg-transparent text-primary focus:ring-primary focus:ring-offset-background-light dark:focus:ring-offset-background-dark" type="checkbox"/>
<span class="text-sm">M</span>
</label>
<label class="flex items-center gap-3">
<input class="h-5 w-5 rounded border-primary/30 bg-transparent text-primary focus:ring-primary focus:ring-offset-background-light dark:focus:ring-offset-background-dark" type="checkbox"/>
<span class="text-sm">L</span>
</label>
<label class="flex items-center gap-3">
<input class="h-5 w-5 rounded border-primary/30 bg-transparent text-primary focus:ring-primary focus:ring-offset-background-light dark:focus:ring-offset-background-dark" type="checkbox"/>
<span class="text-sm">XL</span>
</label>
</div>
</div>
<div>
<h3 class="text-lg font-bold">Color</h3>
<div class="mt-4 flex flex-wrap gap-3">
<label class="h-8 w-8 cursor-pointer rounded-full border-2 border-stone-300 dark:border-stone-600 ring-offset-2 ring-offset-background-light dark:ring-offset-background-dark has-[:checked]:ring-2 has-[:checked]:ring-primary" style="background-color: #ffffff"><input class="invisible" name="color" type="radio"/></label>
<label class="h-8 w-8 cursor-pointer rounded-full border-2 border-stone-300 dark:border-stone-600 ring-offset-2 ring-offset-background-light dark:ring-offset-background-dark has-[:checked]:ring-2 has-[:checked]:ring-primary" style="background-color: #000000"><input class="invisible" name="color" type="radio"/></label>
<label class="h-8 w-8 cursor-pointer rounded-full border-2 border-stone-300 dark:border-stone-600 ring-offset-2 ring-offset-background-light dark:ring-offset-background-dark has-[:checked]:ring-2 has-[:checked]:ring-primary" style="background-color: #ff0000"><input checked="" class="invisible" name="color" type="radio"/></label>
<label class="h-8 w-8 cursor-pointer rounded-full border-2 border-stone-300 dark:border-stone-600 ring-offset-2 ring-offset-background-light dark:ring-offset-background-dark has-[:checked]:ring-2 has-[:checked]:ring-primary" style="background-color: #00ff00"><input class="invisible" name="color" type="radio"/></label>
<label class="h-8 w-8 cursor-pointer rounded-full border-2 border-stone-300 dark:border-stone-600 ring-offset-2 ring-offset-background-light dark:ring-offset-background-dark has-[:checked]:ring-2 has-[:checked]:ring-primary" style="background-color: #0000ff"><input class="invisible" name="color" type="radio"/></label>
</div>
</div>
</div>
</aside>
<div class="flex-1 p-6">
<h1 class="text-4xl font-bold tracking-tight">Ethnic Wear</h1>
<div class="mt-4 border-b border-primary/20 dark:border-primary/30">
<div class="flex gap-8">
<a class="border-b-2 border-primary py-3 text-sm font-bold text-primary" href="#">New Arrivals</a>
<a class="border-b-2 border-transparent py-3 text-sm font-bold text-stone-500 hover:border-primary/50 hover:text-stone-900 dark:text-stone-400 dark:hover:text-stone-100" href="#">Price: Low to High</a>
<a class="border-b-2 border-transparent py-3 text-sm font-bold text-stone-500 hover:border-primary/50 hover:text-stone-900 dark:text-stone-400 dark:hover:text-stone-100" href="#">Price: High to Low</a>
</div>
</div>
<div class="mt-6 grid grid-cols-[repeat(auto-fill,minmax(220px,1fr))] gap-6">
<div class="group relative">
<div class="aspect-[3/4] w-full overflow-hidden rounded-lg bg-background-light dark:bg-background-dark">
<img alt="Elegant Embroidered Kurti" class="h-full w-full object-cover object-center transition-transform duration-300 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDTT58qNqu0H-G3GyyjGuJ805n9j2zCxpUWkq7JF7ZBwVHKpnkov0TVRlL9bi7Un-_Fs0f-NCZ4kOO1LNjEDXVMUnHZ_PgIu6Qjohxq1-0mj_hE_h6XA7B5QPkS3uL2Oty8M-F-EMzJD8iHf8axNJ0NkRkwBNZF-J_TIgsLCofDpXWH030v2VuYgh-uMho6TedV9ec0dAMh0i9BU2XLTPYo5FQkKSVpngxJTbXNG4sVQvEXnkpFO85JQLRStFD9JujB3Zjrtm3Iz54"/>
</div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 transition-opacity group-hover:opacity-100">
<button class="rounded-lg bg-primary px-4 py-2 text-sm font-bold text-white">Add to Cart</button>
</div>
<div class="mt-2">
<h3 class="text-base font-medium">Elegant Embroidered Kurti</h3>
<p class="text-sm text-stone-500 dark:text-stone-400">$150</p>
</div>
</div>
<div class="group relative">
<div class="aspect-[3/4] w-full overflow-hidden rounded-lg bg-background-light dark:bg-background-dark">
<img alt="Silk Blend Saree" class="h-full w-full object-cover object-center transition-transform duration-300 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAyzPJmvP4JQ_AYHzTBbBV8fNM7YKjp7itA4fxgcwc7sRgyFQsasFSbUAvrlV9OQw0ZrxrAj5ia5lx4o-1yDga2pGx8X4hgR8oh0kWnxAFWcaciq_FNw76eyI218iWsFrUMw6ZlpvdDplOtvKcWZ_LwhxWSNQjDZy5e8EmaNJy3XCfQYHkSGJ4T6YWfiokGabNHDoRcU3BuTISWzjDMGFgooQpFbxxGvcZwG3O--96t0eMu2eK5nL8uwm9_Mq00t1LnKFRCnCJd1Co"/>
</div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 transition-opacity group-hover:opacity-100">
<button class="rounded-lg bg-primary px-4 py-2 text-sm font-bold text-white">Add to Cart</button>
</div>
<div class="mt-2">
<h3 class="text-base font-medium">Silk Blend Saree</h3>
<p class="text-sm text-stone-500 dark:text-stone-400">$250</p>
</div>
</div>
<div class="group relative">
<div class="aspect-[3/4] w-full overflow-hidden rounded-lg bg-background-light dark:bg-background-dark">
<img alt="Designer Lehenga Set" class="h-full w-full object-cover object-center transition-transform duration-300 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD0O7zkJmRXZpEZ0FxdwgOGtPumheMd7FCTOBS41lheu3Z_ccJdShLcBKIzvMHghhGOfhsvykfNpTWPoSPEthS-qq89wcmBKndA5FH1m_ArzLnwrF1zkXddsMiGg2FfDKhNK2qzQasaOMZ5hd0UyHqk6rAce_jpb8TjTUrMYq6_fl6iJlAoMmfUa_8sPyXO32t2-6WwZdu9GcGM5t_8BdC0KbN64olDcQUbVQUUqXbynMkuulPSeGRjn7k1vcyKfIFNWxhluNXqle0"/>
</div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 transition-opacity group-hover:opacity-100">
<button class="rounded-lg bg-primary px-4 py-2 text-sm font-bold text-white">Add to Cart</button>
</div>
<div class="mt-2">
<h3 class="text-base font-medium">Designer Lehenga Set</h3>
<p class="text-sm text-stone-500 dark:text-stone-400">$400</p>
</div>
</div>
<div class="group relative">
<div class="aspect-[3/4] w-full overflow-hidden rounded-lg bg-background-light dark:bg-background-dark">
<img alt="Casual Cotton Kurti" class="h-full w-full object-cover object-center transition-transform duration-300 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCDicVZ4OOYkIm9x5B4YtBX09xoR4xHuep1_tofmtV_hBsjJLs3RZjTJGyrdJ41AS0kcjJiJ-K0_JAyDgb9Ea9bUUDMbam7xq4gw73UszqTBA-iFZeZAErowAQ0DZ_Du0HtLfSfUfjLh8BUBgyIJckN7vFc3HyOHI-GNx4uhgpzhnUX4LvtZOi4N7rsJ2wkFFGuTjezvHOat32tjf7C8YSAbZCjPyiJD6fR-DkPeLkHmpdXfge0F0PH2fKEvTj2RNE7kCqVo7BU0FI"/>
</div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 transition-opacity group-hover:opacity-100">
<button class="rounded-lg bg-primary px-4 py-2 text-sm font-bold text-white">Add to Cart</button>
</div>
<div class="mt-2">
<h3 class="text-base font-medium">Casual Cotton Kurti</h3>
<p class="text-sm text-stone-500 dark:text-stone-400">$120</p>
</div>
</div>
<div class="group relative">
<div class="aspect-[3/4] w-full overflow-hidden rounded-lg bg-background-light dark:bg-background-dark">
<img alt="Festive Wear Saree" class="h-full w-full object-cover object-center transition-transform duration-300 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBcXyHnJ8ioOUwWREeqctbPHwB8oesFafiSVf9iCest4BuQ1bqRCxsKsvOfe6Rq6XtgDiaaBRxa8KzFYaQKOhHrbNToiAWLSeWGuKVj5R_67VYfUa2edh-_eUt1Xx5Blq2HySSQswTBps9m5egdtRTeoS089B3Lji-nyQjH_mVAm17_fI07ldQsjegFgmROv0xYlQl9p0AIi-jglIIR9FZ2rYR0EuakhLqGLKlxP_YL60v6HiXOfJBufe7R6z6CBQzDeU8Qc4YqD8k"/>
</div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 transition-opacity group-hover:opacity-100">
<button class="rounded-lg bg-primary px-4 py-2 text-sm font-bold text-white">Add to Cart</button>
</div>
<div class="mt-2">
<h3 class="text-base font-medium">Festive Wear Saree</h3>
<p class="text-sm text-stone-500 dark:text-stone-400">$300</p>
</div>
</div>
<div class="group relative">
<div class="aspect-[3/4] w-full overflow-hidden rounded-lg bg-background-light dark:bg-background-dark">
<img alt="Party Wear Lehenga" class="h-full w-full object-cover object-center transition-transform duration-300 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB2_BqvyZ8l1uTVuyRI1fVoOYIEoYGb-FaaI4CifBofFV2eEwEa0I1_rJzzRrNRKL0n1IeWsjzSjiXPyt5cjO6hVhH6_odTvt_BJrqTMwh-BicCj8O3mku5Dtt30dTLA0N1CCNdSBRFQNb_H70NRAu-qA7PCx29TDIKr_mc0aCcEzPxRlQmQr6rZUzsgYYhlmPwEx_34A2rREMfxBUKzBkkCl8Tg0HnGJqtLPRAdCuwU_DOCb2BE9kbrB5MHGh_yVGTqDAzNqmmcSg"/>
</div>
<div class="absolute inset-0 flex items-center justify-center bg-black/40 opacity-0 transition-opacity group-hover:opacity-100">
<button class="rounded-lg bg-primary px-4 py-2 text-sm font-bold text-white">Add to Cart</button>
</div>
<div class="mt-2">
<h3 class="text-base font-medium">Party Wear Lehenga</h3>
<p class="text-sm text-stone-500 dark:text-stone-400">$450</p>
</div>
</div>
</div>
</div>
</main>
</div>
</div>

</body></html>
