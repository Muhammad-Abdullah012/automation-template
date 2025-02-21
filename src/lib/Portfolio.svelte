<script lang="ts">
  const images = [
    {
      src: "https://images.unsplash.com/photo-1581092160562-40aa08e78837?auto=format&fit=crop&q=80&w=2070&ixlib=rb-4.0.3",
      alt: "Technical Drawing"
    },
    {
      src: "https://images.unsplash.com/photo-1631083215251-98e1bfa3e19e?auto=format&fit=crop&q=80&w=1974&ixlib=rb-4.0.3",
      alt: "Control Panel"
    },
    {
      src: "https://images.unsplash.com/photo-1621905252507-b35492cc74b4?auto=format&fit=crop&q=80&w=2069&ixlib=rb-4.0.3",
      alt: "Building Exterior"
    }
  ];
</script>

<section class="py-16">
  <div class="container">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      {#each images as image}
        <div class="aspect-[4/3] overflow-hidden rounded-lg shadow-md">
          <img 
            src={image.src} 
            alt={image.alt}
            class="w-full h-full object-cover transition-transform duration-300 hover:scale-105"
          />
        </div>
      {/each}
    </div>
  </div>
</section>