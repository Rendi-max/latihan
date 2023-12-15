<template>
    <div>
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.2/font/bootstrap-icons.min.css">
      <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet"/>
      <body class="font-sans">
        <NavbarUtama />
        <MyProfile />
        <div class="bg-violet-800 h-[68px] overflow-hidden w-full"></div>
        <MySkill />
        <MyProject />
        <div class="bg-violet-800 h-[68px] overflow-hidden w-full"></div>
      </body>
    </div>
</template>

<script src="https://cdn.tailwindcss.com"></script>

<script>
  import NavbarUtama from '~/components/NavbarUtama';
  import MyProfile from '~/components/MyProfile';
  import MySkill from '~/components/MySkill';
  import MyProject from '~/components/MyProject';

  export default ({
    name: 'IndexPage',
    components :{
      NavbarUtama,
      MyProfile,
      MySkill,
      MyProject,
    }
  })
</script>

<style>
  body
  {
    background-color: #000036;
  }
</style>
