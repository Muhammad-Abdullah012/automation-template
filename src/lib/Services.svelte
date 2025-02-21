<script lang="ts">
  const services = [
    'Civil systems, both residential and commercial',
    'Public and private lighting systems',
    'Photovoltaic generation plants',
    'Electrical distribution plants in industries',
    'Plants in places with explosion hazard (ATEX)',
    'Automation and machine board plants',
    'Safety circuits according to ISO 13849-1 and 2'
  ];
</script>

<section class="py-16">
  <div class="flex flex-row md:flex-col">
    <h2 class="text-5xl mb-8 text-dark">Study Silato</h2>
    <div class="grid gap-8">
      <div class="w-fit">
        <h3 class="text-3xl mb-4 text-dark">Services offered</h3>
        <p class="text-gray-700">Studio Silato is active in the field of electrical design in several areas, including:</p>
        <ul class="mt-6">
          {#each services as service}
            <li class="mb-4 pl-6 relative text-gray-600 before:content-['•'] before:absolute before:left-0 before:text-primary">
              {service}
            </li>
          {/each}
        </ul>
      </div>
    </div>
  </div>
</section>