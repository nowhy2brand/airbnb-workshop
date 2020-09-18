<template>
  <div class="flex flex-col w-screen relative">
    <Navigation class="absolute top-0 z-10">
      <template v-slot:items>
        <Logo class="h-16"/>
        <SearchInput />
        <UserMenu />
      </template>
    </Navigation>
    <HeaderContent 
      imgURL="https://images.pexels.com/photos/1538177/pexels-photo-1538177.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
      heading1="It's time to travel local"
      heading2="Settle in somewhere new. Discover nearby stays to live, work, or just relax."
    />
    <PopularPlace />
    <Footer />
  </div>
</template>

<script>
export default {}
</script>
